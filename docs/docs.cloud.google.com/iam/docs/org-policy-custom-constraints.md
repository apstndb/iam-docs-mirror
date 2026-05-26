---
name: documents/docs.cloud.google.com/iam/docs/org-policy-custom-constraints
uri: https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints
title: Use custom organization policies for allow policies
description: How to use custom organization policies for IAM allow policies.
data_source: docs.cloud.google.com
---

This page shows you how to use Organization Policy Service custom constraints to restrict specific operations on the following Google Cloud resources:

  - `iam.googleapis.com/AllowPolicy`

To learn more about Organization Policy, see [Custom organization policies](https://docs.cloud.google.com/organization-policy/overview#custom-organization-policies) .

## About organization policies and constraints

The Google Cloud Organization Policy Service gives you centralized, programmatic control over your organization's resources. As the [organization policy administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin) , you can define an organization policy, which is a set of restrictions called *constraints* that apply to Google Cloud resources and descendants of those resources in the [Google Cloud resource hierarchy](https://docs.cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy) . You can enforce organization policies at the organization, folder, or project level.

Organization Policy provides built-in [managed constraints](https://docs.cloud.google.com/organization-policy/reference/org-policy-constraints) for various Google Cloud services. However, if you want more granular, customizable control over the specific fields that are restricted in your organization policies, you can also create *custom constraints* and use those custom constraints in an organization policy.

### Policy inheritance

By default, organization policies are inherited by the descendants of the resources on which you enforce the policy. For example, if you enforce a policy on a folder, Google Cloud enforces the policy on all projects in the folder. To learn more about this behavior and how to change it, refer to [Hierarchy evaluation rules](https://docs.cloud.google.com/organization-policy/hierarchy-evaluation#disallow_inheritance) .

### Benefits

You can use custom organization policies that reference IAM attributes to control how your allow policies can be modified. Specifically, you can control the following:

  - Who can be granted roles
  - Who can have their roles revoked
  - Which roles can be granted
  - Which roles can be revoked

For example, you can prevent roles that contain the word `admin` from being granted to principals whose email addresses end in `@gmail.com` .

## Limitations

  - Custom organization policies in [dry-run mode](https://docs.cloud.google.com/resource-manager/docs/organization-policy/dry-run-policy) that reference IAM attributes have some limitations. Namely, audit logs for violations that involve the `setIamPolicy` method might be missing the following fields:
    
      - `resourceName`
      - `serviceName`
      - `methodName`

  - Audit logs aren't generated for all IAM-related custom organization policy violations. Namely, if a custom organization policy causes a `setIamPolicy` operation on the organization resource to fail, then Google Cloud doesn't generate an audit log for that event.

  - Custom organization policies that reference IAM attributes don't affect the following:
    
      - Default grants by [Cloud Storage ACLs](https://docs.cloud.google.com/storage/docs/access-control/lists#default) .
      - Automatic role grants for [Cloud Storage convenience values](https://docs.cloud.google.com/storage/docs/access-control/iam-roles#basic-roles-modifiable) and [BigQuery default dataset access](https://docs.cloud.google.com/bigquery/docs/access-control-basic-roles#dataset-basic-roles) .
      - Roles granted by [default allow policies](https://docs.cloud.google.com/iam/docs/allow-policies#default) —for example, a project creator automatically being granted the Owner role ( `roles/owner` ) on the project.

  - Users can be sent invitations to become owners, even if you have a custom organization policy that prevents the Owner role ( `roles/owner` ) from being granted. However, while the custom organization policy doesn't prevent an invitation from being sent, it does prevent invited users from being granted the Owner role. If invited users try to accept the invitation, they'll encounter an error and won't be granted the Owner role.

  - Some actions in Google Cloud, such as creating resources or enabling APIs, involve automatically granting a role to a [service agent](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) or [default service account](https://docs.cloud.google.com/iam/docs/service-account-types#default) . If an action involves automatically granting a role and an organization policy prevents that role from being granted, then the entire operation might fail.
    
    If you encounter this issue, you can use [tags](https://docs.cloud.google.com/resource-manager/docs/organization-policy/tags-organization-policy#setting_an_organization_policy_with_tags) to temporarily disable the constraint that prevents the role grant. Then, perform the action. After the action finishes, re-enable the constraint.

## Before you begin

  - If you want to test out custom organization policies that reference IAM resources, create a new project. Testing these organization policies in an existing project could disrupt security workflows.
    
    1.  In the Google Cloud console, go to the project selector page.
    
    2.  Select or create a Google Cloud project.
        
        **Roles required to select or create a project**
        
          - **Select a project** : Selecting a project doesn't require a specific IAM role—you can select any project that you've been granted a role on.
          - **Create a project** : To create a project, you need the Project Creator role ( `roles/resourcemanager.projectCreator` ), which contains the `resourcemanager.projects.create` permission. [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .
        
        > **Note** : If you don't plan to keep the resources that you create in this procedure, create a project instead of selecting an existing project. After you finish these steps, you can delete the project, removing all resources associated with the project.

### Required roles

To get the permissions that you need to manage organization policies, ask your administrator to grant you the following IAM roles:

  - [Organization Policy Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin) ( `roles/orgpolicy.policyAdmin` ) on the organization
  - Test the organization policies described on this page: [Project IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin) ( `roles/resourcemanager.projectIamAdmin` ) on the project

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to manage organization policies. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to manage organization policies:

  - `orgpolicy.*` on the organization
  - Test the organization policies described on this page: `resourcemanager.projects.setIamPolicy` on the project

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Identity and Access Management supported resources

IAM supports the `AllowPolicy` resource. This resource has the attribute `resources.bindings` attribute, which is returned for all methods that modify a resource's allow policy. All of the methods that modify a resource's allow policy end with `setIamPolicy` .

The `resource.bindings` attribute has the following structure, where `  BINDINGS  ` is an array of role bindings that were modified during a change to an allow policy:

    {
      "bindings": {
        BINDINGS
      }
    }

Each binding in `resource.bindings` has the following structure, where `  ROLE  ` is the name of the role in the role binding and `  MEMBERS  ` is a list of identifiers for all principals that were added to or removed from the role binding:

    {
      "role": "ROLE"
      "members": {
        MEMBERS
      }
    }

To see the formats that principal identifiers can have, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

You can only evaluate the `resource.bindings` attribute and its fields using the [supported functions](https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints#supported-functions) . Other operators and functions—like `==` , `!=` , `in` , `contains` , `startsWith` , and `endsWith` —are not supported.

### Supported functions

You can use the following CEL functions to evaluate individual roles and members in a binding.

To evaluate all bindings in the `bindings` array or all members in the `members` array, use the `all` and `exists` macros. For more information, see [Macros to evaluate lists](https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints#list-macros) on this page.

You can also use the logical operators `&&` ( `and` ) and `||` ( `or` ) to write multipart conditions.

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Function</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">RoleNameMatches(  role,  roleNames: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the role <code dir="ltr" translate="no">role</code> fully matches at least one of the roles listed in <code dir="ltr" translate="no">roleNames</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">role</code> : the role to evaluate.
</dd>
<dd><code dir="ltr" translate="no">roleNames</code> : a list of role names to match against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the <code dir="ltr" translate="no">role</code> in the specified <code dir="ltr" translate="no">binding</code> is <code dir="ltr" translate="no">roles/storage.admin</code> or <code dir="ltr" translate="no">roles/compute.admin</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>RoleNameMatches(binding.role, [&#39;roles/storage.admin&#39;, &#39;roles/compute.admin&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">RoleNameStartsWith(  role,  rolePrefixes: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the role <code dir="ltr" translate="no">role</code> starts with at least one of the strings listed in <code dir="ltr" translate="no">rolePrefixes</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">role</code> : the role to evaluate.
</dd>
<dd><code dir="ltr" translate="no">rolePrefixes</code> : a list of strings to match the start of the role against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the <code dir="ltr" translate="no">role</code> in the specified <code dir="ltr" translate="no">binding</code> starts with <code dir="ltr" translate="no">roles/storage</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>RoleNameStartsWith(binding.role, [&#39;roles/storage&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">RoleNameEndsWith(  role,  roleSuffixes: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the role <code dir="ltr" translate="no">role</code> ends with at least one of the strings listed in <code dir="ltr" translate="no">roleSuffixes</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">role</code> : the role to evaluate.
</dd>
<dd><code dir="ltr" translate="no">roleSuffixes</code> : a list of strings to match the end of the role against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the <code dir="ltr" translate="no">role</code> in the specified <code dir="ltr" translate="no">binding</code> ends with <code dir="ltr" translate="no">.admin</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>RoleNameEndsWith(binding.role, [&#39;.admin&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">RoleNameContains(  role,  roleSubstrings: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the role <code dir="ltr" translate="no">role</code> contains at least one of the strings listed in <code dir="ltr" translate="no">roleSubstrings</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">role</code> : the role to evaluate.
</dd>
<dd><code dir="ltr" translate="no">roleSubstrings</code> : a list of strings to match any part of the role to.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the <code dir="ltr" translate="no">role</code> in the specified <code dir="ltr" translate="no">binding</code> contains the string <code dir="ltr" translate="no">admin</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>RoleNameContains(binding.role, [&#39;admin&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">MemberSubjectMatches(  member,  memberNames: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> fully matches at least one of the members listed in <code dir="ltr" translate="no">memberNames</code> .</p>
<p>If the identifier for <code dir="ltr" translate="no">member</code> is an email address, this function evaluates the email address as well as any <a href="https://support.google.com/a/answer/33327">aliases</a> for that email address.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">member</code> : the member to evaluate.
</dd>
<dd><code dir="ltr" translate="no">memberNames</code> : a list of member names to match against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> is <code dir="ltr" translate="no">rosario@example.com</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>MemberSubjectMatches(member, [&#39;user:rosario@example.com&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">MemberSubjectStartsWith(  member,  memberPrefixes: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> starts with at least one of the strings listed in <code dir="ltr" translate="no">memberPrefixes</code> .</p>
<p>If the identifier for <code dir="ltr" translate="no">member</code> is an email address, this function evaluates the email address as well as any <a href="https://support.google.com/a/answer/33327">aliases</a> for that email address.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">member</code> : the member to evaluate.
</dd>
<dd><code dir="ltr" translate="no">memberPrefixes</code> : a list of strings to match the beginning of the member name against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> begins with <code dir="ltr" translate="no">user:prod-</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>MemberSubjectStartsWith(member, [&#39;user:prod-&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">MemberSubjectEndsWith(  member,  memberSuffixes: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> ends with at least one of the strings listed in <code dir="ltr" translate="no">memberSuffixes</code> .</p>
<p>If the identifier for <code dir="ltr" translate="no">member</code> is an email address, this function evaluates the email address as well as any <a href="https://support.google.com/a/answer/33327">aliases</a> for that email address.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">member</code> : the member to evaluate.
</dd>
<dd><code dir="ltr" translate="no">memberSuffixes</code> : a list of strings to match the end of the member name against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> ends with <code dir="ltr" translate="no">@example.com</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>MemberSubjectEndsWith(member, [&#39;@example.com&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">MemberInPrincipalSet(  member,  principalSets: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the member belongs to at least one of the listed principal sets.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">member</code> : the member to evaluate.
</dd>
<dd><p><code dir="ltr" translate="no">principalSets</code> : a list of principal sets. For the function to evaluate to <code dir="ltr" translate="no">true</code> , the member must be in at least one of these principal sets.</p>
<p>The only principal set that is supported is the organization principal set, which has the format <code dir="ltr" translate="no">//cloudresourcemanager.googleapis.com/organizations/            ORGANIZATION_ID          </code> . When used in the <code dir="ltr" translate="no">MemberInPrincipalSet</code> function, this principal set includes the following principals:</p>
<ul>
<li>All identities in all domains associated with your Google Workspace customer ID</li>
<li>All workforce identity pools in your organization</li>
<li>All service accounts and workload identity pools in any project in the organization</li>
<li>All <a href="https://docs.cloud.google.com/iam/docs/service-account-types#service-agents">service agents</a> associated with resources in your organization.</li>
</ul>
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> belongs to the <code dir="ltr" translate="no">@example.com</code> organization, which has the ID <code dir="ltr" translate="no">123456789012</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>MemberInPrincipalSet(member, [&#39;//cloudresourcemanager.googleapis.com/organizations/123456789012&#39;])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">MemberTypeMatches(  member,  principalType: list  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the member is one of the listed principal types.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">member</code> : the member to evaluate.
</dd>
<dd><code dir="ltr" translate="no">principalType</code> : a list of principal types. For the function to evaluate to <code dir="ltr" translate="no">true</code> , the member must be one of the listed principal types. To learn which principal types are supported, see <a href="https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints#member-type-matches-supported-principal-types">Supported principal types for <code dir="ltr" translate="no">MemberTypeMatches</code></a> .
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the member <code dir="ltr" translate="no">member</code> has the principal type <code dir="ltr" translate="no">iam.googleapis.com/WorkspacePrincipal</code> or <code dir="ltr" translate="no">iam.googleapis.com/WorkspaceGroup</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>MemberTypeMatches(member, [&#39;iam.googleapis.com/WorkspacePrincipal&#39;, &#39;iam.googleapis.com/WorkspaceGroup&#39;])</code></pre>
</dd>
</dl></td>
</tr>
</tbody>
</table>

### Macros to evaluate lists

Use the `all` and `exists` macros to evaluate a condition expression for a list of items.

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Macro</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">list.</code> <code dir="ltr" translate="no">all(  item,  conditionExpression  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if <code dir="ltr" translate="no">conditionExpression</code> evaluates to <code dir="ltr" translate="no">true</code> for <em>every</em> <code dir="ltr" translate="no">item</code> in <code dir="ltr" translate="no">list</code> .</p>
<p>This macro is typically used for custom organization policies with the <code dir="ltr" translate="no">actionType</code> <code dir="ltr" translate="no">ALLOW</code> . For example, you can use this macro to ensure that an action is only allowed if <em>all</em> modified principals meet the condition.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">list</code> : the list of items to evaluate.
</dd>
<dd><code dir="ltr" translate="no">item</code> : the list item to evaluate. For example, if you call this method on the list <code dir="ltr" translate="no">resource.bindings</code> , then use the value <code dir="ltr" translate="no">binding</code> .
</dd>
<dd><code dir="ltr" translate="no">conditionExpression</code> : the condition expression to evaluate each <code dir="ltr" translate="no">item</code> against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if all of the bindings in <code dir="ltr" translate="no">resource.bindings</code> have roles that start with <code dir="ltr" translate="no">roles/storage.</code> . Returns <code dir="ltr" translate="no">false</code> if any of the bindings have roles that don't start with <code dir="ltr" translate="no">roles/storage.</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.bindings.all(binding, RoleNameStartsWith(binding.role, [&#39;roles/storage.&#39;]))</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">list.</code> <code dir="ltr" translate="no">exists(  item,  conditionExpression  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if <code dir="ltr" translate="no">conditionExpression</code> evaluates to <code dir="ltr" translate="no">true</code> for <em>any</em> <code dir="ltr" translate="no">item</code> in <code dir="ltr" translate="no">list</code> .</p>
<p>This macro is typically used for custom organization policies with the <code dir="ltr" translate="no">actionType</code> <code dir="ltr" translate="no">DENY</code> . For example, you can use this macro to ensure that an action is denied if <em>any</em> of the modified principals meet the condition.</p>
<dl>
<dt>Parameters</dt>
<dd><code dir="ltr" translate="no">list</code> : the list of items to evaluate.
</dd>
<dd><code dir="ltr" translate="no">item</code> : the list item to evaluate. For example, if you call this method on the list <code dir="ltr" translate="no">resource.bindings</code> , then use the value <code dir="ltr" translate="no">binding</code> .
</dd>
<dd><code dir="ltr" translate="no">conditionExpression</code> : the condition expression to evaluate each <code dir="ltr" translate="no">item</code> against.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if any of the bindings in <code dir="ltr" translate="no">resource.bindings</code> have roles that start with <code dir="ltr" translate="no">roles/storage.</code> . Returns <code dir="ltr" translate="no">false</code> if none of the bindings have roles that start with <code dir="ltr" translate="no">roles/storage.</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.bindings.exists(binding, RoleNameStartsWith(binding.role, [&#39;roles/storage.&#39;]))</code></pre>
</dd>
</dl></td>
</tr>
</tbody>
</table>

#### Conditions with nested lists

In general, if your condition includes nested lists, you should use the same macro for all lists in the condition.

Consider the following examples:

  - If your policy has the `actionType` `ALLOW` , then use the `all` macro for both the `members` list and the `bindings` list to ensure that policy modifications are only allowed if *all* members in *all* modified bindings satisfy the condition.
  - If your policy has the `actionType` `DENY` , then use the `exists` macro for both the `members` list and the `bindings` list to ensure that policy modifications aren't allowed if *any* member in *any* modified binding satisfies the condition.

Mixing macros in a single condition might result in a condition that doesn't behave how you intended.

For example, imagine that you want to prevent roles from being granted to members outside of the `example.com` organization. The `example.com` organization has the ID `123456789012` .

To accomplish this goal, you write the following condition:

Not recommended — misconfigured condition

    "resource.bindings.all(
      binding,
      binding.members.exists(member,
        MemberInPrincipalSet(member, ['//cloudresourcemanager.googleapis.com/organizations/123456789012'])
      )
    )"

This condition appears to prevent roles from being granted to members outside of the `example.com` organization. However, the condition evaluates to `true` if *any* member in each of the modified role bindings is in the `example.com` organization. As a result, you can still grant roles to members outside of the `example.com` organization if you also grant the same role to a member in the `example.com` organization.

For example, the condition evaluates to `true` for the following set of bindings, even though one of the members isn't in the `example.com` organization:

``` 
 "bindings": [
    {
      "members": [
        "user:raha@altostrat.com",
        "user:jie@example.com"
      ],
      "role": "roles/resourcemanager.projectCreator"
    }
  ],
```

Instead, you should write a condition like the following:

Recommended — correctly configured condition

    "resource.bindings.all(
      binding,
      binding.members.all(member,
        MemberInPrincipalSet(member, ['//cloudresourcemanager.googleapis.com/organizations/123456789012'])
      )
    )"

Using the `all` macro for both the `members.bindings` array and the `resource.bindings` array ensures that the condition evaluates to `true` only if *all* members in *all* bindings are in the `example.com` principal set.

### Supported principal types for `MemberTypeMatches`

The `MemberTypeMatches` function requires you to specify which principal type the specified member must match.

The following table lists the principal types that you can enter and a description of what the principal type represents. It also lists the principal identifiers that correspond with each principal type. These identifiers are the values that are used in IAM policies.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal type</th>
<th>Description</th>
<th>Principal identifiers</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ConsumerPrincipal</code></td>
<td>A <a href="https://docs.cloud.google.com/architecture/identity/overview-google-authentication#google_for_consumers">consumer Google Account</a> . The email addresses for these accounts typically end in <code dir="ltr" translate="no">gmail.com</code> .</td>
<td><code dir="ltr" translate="no">user:         USER_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkspacePrincipal</code></td>
<td>A Google Account that is part of a Cloud Identity or Google Workspace account. These accounts are also called <a href="https://docs.cloud.google.com/architecture/identity/overview-google-authentication#managed_user_account">managed user accounts</a> .</td>
<td><code dir="ltr" translate="no">user:         USER_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ConsumerGroup</code></td>
<td>A <a href="https://docs.cloud.google.com/architecture/identity/overview-google-authentication#group">Google group</a> created by a consumer Google Account. These groups aren't owned by a Cloud Identity or Google Workspace account. The email addresses for these groups typically end in <code dir="ltr" translate="no">googlegroups.com</code> .</td>
<td><code dir="ltr" translate="no">group:         GROUP_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkspaceGroup</code></td>
<td>A <a href="https://docs.cloud.google.com/architecture/identity/overview-google-authentication#group">Google group</a> that's owned by a Cloud Identity or Google Workspace account.</td>
<td><code dir="ltr" translate="no">group:         GROUP_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  Domain</code></td>
<td>A Cloud Identity or Google Workspace account.</td>
<td><code dir="ltr" translate="no">domain:         DOMAIN       </code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkforcePoolPrincipal</code></td>
<td>A single principal in a <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pools">workforce identity pool</a> .</td>
<td><code dir="ltr" translate="no">principal://iam.googleapis.com/  locations/  global/  workforcePools/          POOL_ID        /  subject/          SUBJECT_ATTRIBUTE_VALUE       </code></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkforcePoolPrincipalSet</code></td>
<td>A principal set that contains a set of identities in a <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pools">workforce identity pool</a> . For example, a principal set containing all principals in a workforce identity pool.</td>
<td><ul>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/  locations/  global/  workforcePools/            POOL_ID          /  group/            GROUP_ID         </code></li>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/  locations/  global/  workforcePools/            POOL_ID          /attribute.            ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/  locations/  global/  workforcePools/           POOL_ID          /*</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkloadPoolPrincipal</code></td>
<td>A single identity in a <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#pools">workload identity pool</a></td>
<td><code dir="ltr" translate="no">principal://iam.googleapis.com/projects/          PROJECT_NUMBER        /  locations/  global/  workloadIdentityPools/          POOL_ID        /  subject/          SUBJECT_ATTRIBUTE_VALUE       </code></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  WorkloadPoolPrincipalSet</code></td>
<td>A principal set that contains a set of identities in a <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#pools">workload identity pool</a> . For example, a principal set containing all principals in a workload identity pool.</td>
<td><ul>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/projects/            PROJECT_NUMBER          /  locations/  global/  workloadIdentityPools/            POOL_ID          /  group/            GROUP_ID         </code></li>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/projects/            PROJECT_NUMBER          /  locations/  global/  workloadIdentityPools/            POOL_ID          /  attribute.            ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principalSet://iam.googleapis.com/  projects/            PROJECT_NUMBER          /  locations/  global/  workloadIdentityPools/            POOL_ID          /*</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ServiceAccount</code></td>
<td><p>Any <a href="https://docs.cloud.google.com/iam/docs/service-account-overview">service account</a> . A service account is a special type of account that represents a workload rather than a human user.</p>
<p>In the context of the <code dir="ltr" translate="no">MemberTypeMatches</code> function, this principal type doesn't include <a href="https://docs.cloud.google.com/iam/docs/service-account-types#service-agents">service agents</a> .</p></td>
<td><code dir="ltr" translate="no">serviceAccount:         SERVICE_ACCOUNT_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ServiceAgent</code></td>
<td>Any <a href="https://docs.cloud.google.com/iam/docs/service-account-types#service-agents">service agent</a> . A service agent is a special type of service account that Google Cloud creates and manages. When granted roles in your projects, service agents let Google Cloud services perform actions on your behalf.</td>
<td><code dir="ltr" translate="no">serviceAccount:         SERVICE_AGENT_EMAIL_ADDRESS       </code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  PublicPrincipals</code></td>
<td>The principals <code dir="ltr" translate="no">allUsers</code> and <code dir="ltr" translate="no">allAuthenticatedUsers</code> .</td>
<td><ul>
<li><code dir="ltr" translate="no">allUsers</code></li>
<li><code dir="ltr" translate="no">allAuthenticatedUsers</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ProjectRoleReference</code></td>
<td>Principals that are defined based on the role granted to them. These principals are also called <a href="https://docs.cloud.google.com/storage/docs/access-control/iam#convenience-values">convenience values</a> .</td>
<td><ul>
<li><code dir="ltr" translate="no">projectOwner:           PROJECT_ID         </code></li>
<li><code dir="ltr" translate="no">projectEditor:           PROJECT_ID         </code></li>
<li><code dir="ltr" translate="no">projectViewer:           PROJECT_ID         </code></li>
</ul></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ResourcePrincipal</code></td>
<td>A resource with a <a href="https://docs.cloud.google.com/iam/docs/built-in-resource-identities">built-in identity</a> .</td>
<td>Any of the principal identifiers listed in <a href="https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities#single-resources">Principal identifiers for single resources</a> .</td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/  ResourcePrincipalSet</code></td>
<td>Resources with <a href="https://docs.cloud.google.com/iam/docs/built-in-resource-identities">built-in identities</a> that share certain characteristics, such as type or ancestor.</td>
<td>Any of the identifiers listed in <a href="https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities#resource-sets">Principal identifiers for sets of resources</a> .</td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">iam.googleapis.com/AgenticIdentityPoolPrincipal</code></td>
<td>A single <a href="https://docs.cloud.google.com/iam/docs/workload-identities#agent-identity">agent identity</a> .</td>
<td><ul>
<li><code dir="ltr" translate="no">principal://agents.global.org-           ORG_ID          .system.id.goog/            SUBJECT_ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principal://agents.global.proj-           PROJECT_NUMBER          .system.id.goog/            SUBJECT_ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principal://agents-nonprod.global.org-           ORG_ID          .system.id.goog/            SUBJECT_ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principal://agents-nonprod.global.proj-           PROJECT_NUMBER          .system.id.goog/            SUBJECT_ATTRIBUTE_VALUE         </code></li>
</ul></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">iam.googleapis.com/AgenticIdentityPoolPrincipalSet</code></td>
<td>A principal set that contains a set of <a href="https://docs.cloud.google.com/iam/docs/workload-identities#agent-identity">agent identities</a> .</td>
<td><ul>
<li><code dir="ltr" translate="no">principalSet://agents.global.org-           ORG_ID          .system.id.goog/*</code></li>
<li><code dir="ltr" translate="no">principalSet://agents.global.proj-           PROJECT_NUMBER          .system.id.goog/*</code></li>
<li><code dir="ltr" translate="no">principalSet://agents-nonprod.global.org-           ORG_ID          .system.id.goog/*</code></li>
<li><code dir="ltr" translate="no">principalSet://agents-nonprod.global.proj-           PROJECT_NUMBER          .system.id.goog/*</code></li>
<li><code dir="ltr" translate="no">principalSet://agents.global.org-           ORG_ID          .system.id.goog/  attribute.           ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principalSet://agents.global.proj-           PROJECT_NUMBER          .system.id.goog/  attribute.           ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principalSet://agents-nonprod.global.org-           ORG_ID          .system.id.goog/  attribute.           ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
<li><code dir="ltr" translate="no">principalSet://agents-nonprod.global.proj-           PROJECT_NUMBER          .system.id.goog/  attribute.           ATTRIBUTE_NAME          /            ATTRIBUTE_VALUE         </code></li>
</ul>
<p>Example: <code dir="ltr" translate="no">principalSet://agents.global.org-123456789012.system.id.goog/*</code></p></td>
</tr>
</tbody>
</table>

## Set up a custom constraint

A custom constraint is defined in a YAML file by the resources, methods, conditions, and actions that are supported by the service on which you are enforcing the organization policy. Conditions for your custom constraints are defined using [Common Expression Language (CEL)](https://github.com/google/cel-spec/blob/master/doc/intro.md) . For more information about how to build conditions in custom constraints using CEL, see the CEL section of [Creating and managing custom constraints](https://docs.cloud.google.com/organization-policy/create-custom-constraints#common_expression_language) .

### Console

To create a custom constraint, do the following:

In the Google Cloud console, go to the **Organization policies** page.

From the project picker, select the project that you want to set the organization policy for.

Click add **Custom constraint** .

In the **Display name** box, enter a human-readable name for the constraint. This name is used in error messages and can be used for identification and debugging. Don't use personally identifiable information (PII) or sensitive data in display names because this name could be exposed in error messages. This field can contain up to 200 characters.

In the **Constraint ID** box, enter the ID that you want for your new custom constraint. A custom constraint can only contain letters (including upper and lowercase) or numbers, for example `custom.denyProjectIAMAdmin` . This field can contain up to 70 characters, not counting the prefix ( `custom.` ), for example, `organizations/123456789/customConstraints/custom` . Don't include PII or sensitive data in your constraint ID, because it could be exposed in error messages.

In the **Description** box, enter a human-readable description of the constraint. This description is used as an error message when the policy is violated. Include details about why the policy violation occurred and how to resolve the policy violation. Don't include PII or sensitive data in your description, because it could be exposed in error messages. This field can contain up to 2000 characters.

In the **Resource type** box, select the name of the Google Cloud REST resource containing the object and field that you want to restrict—for example, `container.googleapis.com/NodePool` . Most resource types support up to 20 custom constraints. If you attempt to create more custom constraints, the operation fails.

Under **Enforcement method** , select whether to enforce the constraint on a REST `CREATE` method or both `CREATE` and `UPDATE` methods. If you enforce the constraint with the `UPDATE` method on a resource that violates the constraint, changes to that resource are blocked by the organization policy unless the change resolves the violation.

To see supported methods for each service, find the service in [Services that support custom constraints](https://docs.cloud.google.com/organization-policy/reference/custom-constraint-supported-services) .

To define a condition, click edit **Edit condition** .

1.  In the **Add condition** panel, create a CEL condition that refers to a supported service resource, for example, `resource.management.autoUpgrade == false` . This field can contain up to 1000 characters. For details about CEL usage, see [Common Expression Language](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) . For more information about the service resources you can use in your custom constraints, see [Custom constraint supported services](https://docs.cloud.google.com/resource-manager/docs/organization-policy/custom-constraint-supported-services) .
2.  Click **Save** .

Under **Action** , select whether to allow or deny the evaluated method if the condition is met.

The deny action means that the operation to create or update the resource is blocked if the condition evaluates to true.

The allow action means that the operation to create or update the resource is permitted only if the condition evaluates to true. Every other case except those explicitly listed in the condition is blocked.

Click **Create constraint** .

When you have entered a value into each field, the equivalent YAML configuration for this custom constraint appears on the right.

### gcloud

To create a custom constraint, create a YAML file using the following format:

    name: organizations/ORGANIZATION_ID/customConstraints/CONSTRAINT_NAME
    resourceTypes: RESOURCE_NAME
    methodTypes:
      - CREATE
      - UPDATE 
    condition: "CONDITION"
    actionType: ACTION
    displayName: DISPLAY_NAME
    description: DESCRIPTION

Replace the following:

  - `  ORGANIZATION_ID  ` : your organization ID, such as `123456789` .
  - `  CONSTRAINT_NAME  ` : the name that you want for your new custom constraint. A custom constraint can only contain letters (including upper and lowercase) or numbers, for example, `custom.denyProjectIAMAdmin` . This field can contain up to 70 characters, not counting the prefix ( `custom.` )— for example, `organizations/123456789/customConstraints/custom` . Don't include PII or sensitive data in your constraint ID, because it could be exposed in error messages.
  - `  RESOURCE_NAME  ` : the fully qualified name of the Google Cloud resource containing the object and field that you want to restrict. For example, `iam.googleapis.com/AllowPolicy` . Most resource types support up to 20 custom constraints. If you attempt to create more custom constraints, the operation fails.
  - `methodTypes` : the REST methods that the constraint is enforced on. Can be `CREATE` or both `CREATE` and `UPDATE` . If you enforce the constraint with the `UPDATE` method on a resource that violates the constraint, changes to that resource are blocked by the organization policy unless the change resolves the violation.
  - `  CONDITION  ` : a [CEL condition](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) that is written against a representation of a supported service resource. This field can contain up to 1000 characters. For example, `resource.bindings.exists(binding, RoleNameMatches(binding.role, ['roles/resourcemanager.projectIamAdmin']))` .
  - `  ACTION  ` : the action to take if the `condition` is met. Possible values are `ALLOW` and `DENY` .
  - `  DISPLAY_NAME  ` : a human-readable name for the constraint. This name is used in error messages and can be used for identification and debugging. Don't use PII or sensitive data in display names because this name could be exposed in error messages. This field can contain up to 200 characters.
  - `  DESCRIPTION  ` : a human-friendly description of the constraint to display as an error message when the policy is violated. This field can contain up to 2000 characters.

After you have created the YAML file for a new custom constraint, you must set it up to make it available for organization policies in your organization. To set up a custom constraint, use the [`gcloud org-policies set-custom-constraint`](https://docs.cloud.google.com/sdk/gcloud/reference/org-policies/set-custom-constraint) command:

    gcloud org-policies set-custom-constraint CONSTRAINT_PATH

Replace `  CONSTRAINT_PATH  ` with the full path to your custom constraint file. For example, `/home/user/customconstraint.yaml` .

After this operation is complete, your custom constraints are available as organization policies in your list of Google Cloud organization policies.

To verify that the custom constraint exists, use the [`gcloud org-policies list-custom-constraints`](https://docs.cloud.google.com/sdk/gcloud/reference/org-policies/list-custom-constraints) command:

    gcloud org-policies list-custom-constraints --organization=ORGANIZATION_ID

Replace `  ORGANIZATION_ID  ` with the ID of your organization resource.

For more information, see [Viewing organization policies](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-policies#viewing_organization_policies) .

## Enforce a custom organization policy

You can enforce a constraint by creating an organization policy that references it, and then applying that organization policy to a Google Cloud resource.

### Console

1.  In the Google Cloud console, go to the **Organization policies** page.
2.  From the project picker, select the project that you want to set the organization policy for.
3.  From the list on the **Organization policies** page, select your constraint to view the **Policy details** page for that constraint.
4.  To configure the organization policy for this resource, click **Manage policy** .
5.  On the **Edit policy** page, select **Override parent's policy** .
6.  Click **Add a rule** .
7.  In the **Enforcement** section, select whether this organization policy is enforced or not.
8.  Optional: To make the organization policy conditional on a tag, click **Add condition** . Note that if you add a conditional rule to an organization policy, you must add at least one unconditional rule or the policy cannot be saved. For more information, see [Scope organization policies with tags](https://docs.cloud.google.com/organization-policy/scope-policies) .
9.  To enforce the organization policy in dry-run mode, click **Set dry run policy** . For more information, see [Test organization policies](https://docs.cloud.google.com/organization-policy/test-policies) .
10. After you verify that the organization policy in dry-run mode works as intended, set the live policy by clicking **Set policy** .

### gcloud

To create an organization policy with boolean rules, create a policy YAML file that references the constraint:

    name: projects/PROJECT_ID/policies/CONSTRAINT_NAME
    spec:
      rules:
      - enforce: true
    
    dryRunSpec:
      rules:
      - enforce: true

Replace the following:

  - `  PROJECT_ID  ` : the project that you want to enforce your constraint on.
  - `  CONSTRAINT_NAME  ` : the name you defined for your custom constraint. For example, `custom.denyProjectIAMAdmin` .

To enforce the organization policy in [dry-run mode](https://docs.cloud.google.com/organization-policy/test-policies) , run the following command with the `dryRunSpec` flag:

    gcloud org-policies set-policy POLICY_PATH --update-mask=dryRunSpec

Replace `  POLICY_PATH  ` with the full path to your organization policy YAML file. The policy requires up to 15 minutes to take effect.

After you verify that the organization policy in dry-run mode works as intended, set the live policy with the `org-policies set-policy` command and the `spec` flag:

    gcloud org-policies set-policy POLICY_PATH --update-mask=spec

Replace `  POLICY_PATH  ` with the full path to your organization policy YAML file. The policy requires up to 15 minutes to take effect.

## Test the custom organization policy

Optionally, you can test the organization policy by setting the policy and then trying to take an action that the policy should prevent.

### Create the constraint

1.  Save the following file as `constraint-deny-project-iam-admin` .
    
        name: organizations/ORG_ID/customConstraints/custom.denyProjectIAMAdmin
        resourceTypes: iam.googleapis.com/AllowPolicy
        methodTypes:
          - CREATE
          - UPDATE
        condition:
          "resource.bindings.exists(
            binding,
            RoleNameMatches(binding.role, ['roles/resourcemanager.projectIamAdmin']) &&
            binding.members.exists(member,
              MemberSubjectMatches(member, ['user:EMAIL_ADDRESS'])
            )
          )"
        actionType: DENY
        displayName: Do not allow EMAIL_ADDRESS to be granted the Project IAM Admin role.
    
    Replace the following values:
    
      - `  ORG_ID  ` : the numeric ID of your Google Cloud organization.
      - `  MEMBER_EMAIL_ADDRESS  ` : the email address of the principal that you want to use to test the custom constraint. While the constraint is active, this principal won't be able to be granted the Project IAM Admin role ( `roles/resourcemanager.projectIamAdmin` ) on the project that you enforce the constraint for.

2.  Apply the constraint:
    
        gcloud org-policies set-custom-constraint ~/constraint-deny-project-iam-admin.yaml

3.  Verify that the constraint exists:
    
        gcloud org-policies list-custom-constraints --organization=ORGANIZATION_ID

### Create the policy

1.  Save the following file as `policy-deny-project-iam-admin.yaml` :
    
        name: projects/PROJECT_ID/policies/custom.denyProjectIamAdmin
        spec:
          rules:
          - enforce: true
    
    Replace `  PROJECT_ID  ` with your project ID.

2.  Apply the policy:
    
        gcloud org-policies set-policy ~/policy-deny-project-iam-admin.yaml

3.  Verify that the policy exists:
    
        gcloud org-policies list --project=PROJECT_ID

After you apply the policy, wait for about two minutes for Google Cloud to start enforcing the policy.

### Test the policy

Try to grant the Project IAM Admin role ( `roles/resourcemanager.projectIamAdmin` ) to the principal whose email address you included in the custom constraint. Before running the command, replace the following values:

  - `  PROJECT_ID  ` : The ID of the Google Cloud project where you enforced the constraint
  - `  EMAIL_ADDRESS  ` : The email address of the principal that you specified when you created the organization policy constraint.

<!-- end list -->

    gcloud projects add-iam-policy-binding PROJECT_ID \
        --member=user:EMAIL_ADDRESS --role=roles/resourcemanager.projectIamAdmin

The output is the following:

    Operation denied by custom org policies: ["customConstraints/custom.denyProjectIAMAdmin": "EMAIL_ADDRESS can't be granted the Project IAM Admin role."]

## Example custom organization policies for common use cases

The following table provides the syntax of some custom constraints for common use cases.

The following examples use the CEL macros `all` and `exists` . For more information about these macros, see [Macros to evaluate lists](https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints#list-macros) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Description</th>
<th>Constraint syntax</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Block the ability to grant a specific role.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.denyRole
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
&quot;resource.bindings.exists(
    binding,
    RoleNameMatches(binding.role, [&#39;ROLE&#39;])
  )&quot;
actionType: DENY
displayName: Do not allow the ROLE role to be granted</code></pre></td>
</tr>
<tr class="even">
<td>Only allow specific roles to be granted.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.specificRolesOnly
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.all(
    binding,
    RoleNameMatches(binding.role, [&#39;ROLE_1&#39;, &#39;ROLE_2&#39;])
  )&quot;
actionType: ALLOW
displayName: Only allow the ROLE_1 role and ROLE_2 role to be granted</code></pre></td>
</tr>
<tr class="odd">
<td>Prevent any roles that start with <code dir="ltr" translate="no">roles/storage.</code> from being granted.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.dontgrantStorageRoles
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.exists(
    binding,
    RoleNameStartsWith(binding.role, [&#39;roles/storage.&#39;])
  )&quot;
actionType: DENY
displayName: Prevent roles that start with &quot;roles/storage.&quot; from being granted</code></pre></td>
</tr>
<tr class="even">
<td>Prevent any roles with <code dir="ltr" translate="no">admin</code> in the name from being revoked.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.dontRevokeAdminRoles
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - REMOVE_GRANT
condition:
  &quot;resource.bindings.exists(
    binding,
    RoleNameContains(binding.role, [&#39;admin&#39;])
  )&quot;
actionType: DENY
displayName: Prevent roles with &quot;admin&quot; in their names from being revoked</code></pre></td>
</tr>
<tr class="odd">
<td>Only allow specific principals to be granted roles.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.allowSpecificPrincipals
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.all(
    binding,
    binding.members.all(member,
      MemberSubjectMatches(member, [&#39;user:USER&#39;,&#39;serviceAccount:SERVICE_ACCOUNT&#39;])
    )
  )&quot;
actionType: ALLOW
displayName: Only allow roles to be granted to USER and SERVICE_ACCOUNT</code></pre></td>
</tr>
<tr class="even">
<td>Prevent any roles from being revoked from specific principals.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.denyRemovalOfSpecificPrincipals
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - REMOVE_GRANT
condition:
  &quot;resource.bindings.exists(
    binding,
    binding.members.exists(member,
      MemberSubjectMatches(member, [&#39;user:USER_1&#39;,&#39;user:USER_2&#39;])
    )
  )&quot;
actionType: DENY
displayName: Do not allow roles to be revoked from USER_1 or USER_2</code></pre></td>
</tr>
<tr class="odd">
<td>Prevent principals with email addresses ending in <code dir="ltr" translate="no">@gmail.com</code> from being granted roles.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.dontGrantToGmail
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.exists(
    binding,
    binding.members.exists(member,
      MemberSubjectEndsWith(member, [&#39;@gmail.com&#39;])
    )
  )&quot;
actionType: DENY
displayName: Do not allow members whose email addresses end with &quot;@gmail.com&quot; to be granted roles</code></pre></td>
</tr>
<tr class="even">
<td>Only allow specific roles to be granted, and only to specific principals.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.allowSpecificRolesAndPrincipals
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.all(
    binding,
    RoleNameMatches(binding.role, [&#39;ROLE_1&#39;, &#39;ROLE_2&#39;])  &amp;&amp;
    binding.members.all(member,
      MemberSubjectMatches(member, [&#39;serviceAccount:SERVICE_ACCOUNT&#39;, &#39;group:GROUP&#39;])
    )
  )&quot;
actionType: ALLOW
displayName: Only allow ROLE_1 and ROLE_2 to be granted to SERVICE_ACCOUNT and GROUP</code></pre></td>
</tr>
<tr class="odd">
<td>Prevent Cloud Storage roles from being granted to <code dir="ltr" translate="no">allUsers</code> and <code dir="ltr" translate="no">allAuthenticatedUsers</code> .</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.denyStorageRolesForPrincipalAllUsers
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.exists(
    binding,
    RoleNameStartsWith(binding.role, [&#39;roles/storage.&#39;]) &amp;&amp;
    binding.members.exists(member,
      MemberSubjectMatches(member, [&#39;allUsers&#39;, &#39;allAuthenticatedUsers&#39;])
    )
  )&quot;
actionType: DENY
displayName: Do not allow storage roles to be granted to allUsers or allAuthenticatedUsers</code></pre></td>
</tr>
<tr class="even">
<td>Prevent any identities outside of your organization from being granted roles.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.allowInternaldentitiesOnly
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.all(
    binding,
    binding.members.all(member,
      MemberInPrincipalSet(member, [&#39;//cloudresourcemanager.googleapis.com/organizations/ORG_ID&#39;])
    )
  )&quot;
actionType: ALLOW
displayName: Only allow organization members to be granted roles</code></pre></td>
</tr>
<tr class="odd">
<td>Only allow service accounts to be granted roles.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.allowServiceAccountsOnly
resourceTypes: iam.googleapis.com/AllowPolicy
methodTypes:
  - CREATE
  - UPDATE
condition:
  &quot;resource.bindings.all(
    binding,
    binding.members.all(member,
      MemberTypeMatches(member, [&#39;iam.googleapis.com/ServiceAccount&#39;])
    )
  )&quot;
actionType: ALLOW
displayName: Only allow service accounts to be granted roles</code></pre></td>
</tr>
<tr class="even">
<td>Prevent removal of Google-managed service agents from role bindings.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>name: organizations/ORG_ID/customConstraints/custom.denyRemovalOfGoogleManagedServiceAgents
resource_types: iam.googleapis.com/AllowPolicy
method_types:
  - REMOVE_GRANT
condition: |-
  resource.bindings.all(
      binding,
      binding.members.all(member,
        MemberTypeMatches(member, [&#39;iam.googleapis.com/ServiceAgent&#39;])
      )
    )
action_type: DENY
display_name: Deny Removal Of Google-Managed Service Agents
description: Restricts the removal of Google-managed service agents from role bindings. Please reach out to your organization admins for if you have any questions.</code></pre></td>
</tr>
</tbody>
</table>

### Conditional organization policies

You can make a custom organization policy conditional using [tags](https://docs.cloud.google.com/resource-manager/docs/organization-policy/tags-organization-policy#setting_an_organization_policy_with_tags) . For example, imagine that you wrote the following custom constraint to prevent any roles that start with `roles/storage.` from being granted:

    name: organizations/ORG_ID/customConstraints/custom.dontgrantStorageRoles
    resourceTypes: iam.googleapis.com/AllowPolicy
    methodTypes:
      - CREATE
      - UPDATE
    condition:
      "resource.bindings.exists(
        binding,
        RoleNameStartsWith(binding.role, ['roles/storage.'])
      )"
    actionType: DENY
    displayName: Prevent roles that start with "roles/storage." from being granted

To enforce the constraint conditionally, you could create an organization policy like the following:

    name: organizations/ORG_ID/policies/custom.dontgrantStorageRoles
    spec:
      rules:
      - condition:
          expression: "resource.matchTag('ORG_ID/environment', 'dev')"
        enforce: true
      - enforce: false

This organization policy prevents roles that start with `roles/storage.` from being granted on any resource that also has the tag `environment=dev` .

## What's next

  - Learn more about [Organization Policy Service](https://docs.cloud.google.com/organization-policy/overview) .
  - Learn more about how to [create and manage organization policies](https://docs.cloud.google.com/organization-policy/create-organization-policies) .
  - See the full list of managed [organization policy constraints](https://docs.cloud.google.com/organization-policy/reference/org-policy-constraints) .
