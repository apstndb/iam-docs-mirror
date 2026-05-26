---
name: documents/docs.cloud.google.com/iam/docs/principal-access-boundary-policies
uri: https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies
title: Principal access boundary policies
description: An overview of how principal access boundary policies help you control what resources your principals can access.
data_source: docs.cloud.google.com
---

Principal access boundary (PAB) policies let you define the resources that principals can access.

For example, you can use principal access boundary policies to prevent your principals from accessing resources in other organizations, which can help prevent phishing attacks or data exfiltration.

To learn about the other types of access control policies that Identity and Access Management (IAM) offers, see [Policy types](https://docs.cloud.google.com/iam/docs/policy-types) .

## How principal access boundary policies work

By default, principals are eligible to access any Google Cloud resource. This means that if a principal has a permission on the resource and isn't denied that permission, then they can use that permission to access the resource.

With principal access boundary policies, you can define the resources that a principal is eligible to access. If a principal access boundary policy makes a principal ineligible to access a resource, then their access to that resource is limited, regardless of the roles they've been granted.

When principals try to access resources that they aren't eligible to access, principal access boundary policies can block some, but not all, Identity and Access Management (IAM) permissions. To learn more about which permissions are blocked, see [Permissions that principal access boundary can block](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#blocked-permissions) .

Principal access boundary policies are made up of [principal access boundary rules](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#policy-structure) . Each principal access boundary rule defines a set of resources that the affected principals are eligible to access. You can create up to 1000 principal access boundary policies in your organization.

After you create a principal access boundary policy, you create a [policy binding](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#binding) to apply the policy to a set of principals.

A principal can be subject to one or more principal access boundary policies. Each principal is only eligible to access the resources listed in those policies. For all other resources, the principal's access to that resource is limited, even if you grant roles to the principal on that resource.

Because principal access boundary policies are associated with principals and not with resources, you can use them to prevent principals from accessing resources that you don't own. For example, consider the following scenario:

![Principal access boundary policy preventing access to a resource](https://docs.cloud.google.com/static/iam/img/pab-access-attempt-example.svg)

![Principal access boundary policy preventing access to a resource](https://docs.cloud.google.com/static/iam/img/pab-access-attempt-example.svg)

  - The principal Tal ( `tal@example.com` ) is part of the Google Workspace organization `example.com` .
  - Tal is granted the Storage Admin ( `roles/storage.admin` ) role on a Cloud Storage bucket in a different organization, `cymbalgroup.com` . This role contains the `storage.objects.get` permission, which is required to view objects in the bucket.
  - There are no deny policies in `cymbalgroup.com` that prevent Tal from using the `storage.objects.get` permission.

With just allow and deny policies, `example.com` can't prevent Tal from viewing objects in this external bucket. No `example.com` principals have permission to edit the bucket's allow policy, so they can't revoke Tal's role. They also don't have permission to create any deny policies in `cymbalgroup.com` , so they can't use a deny policy to prevent Tal from accessing the bucket.

However, with principal access boundary policies, `example.com` administrators can ensure that Tal can't view objects in the `cymbalgroup.com` bucket, or any bucket outside of `example.com` . To do this, the administrators can create a principal access boundary policy saying that `example.com` principals are only eligible to access resources in `example.com` . Then, they can create a policy binding to attach this policy to all principals in the organization `example.com` . With such a policy in place, Tal won't be able to view objects in the `cymbalgroup.com` bucket, even though they're granted the Storage Admin role on the bucket.

<span id="fail-open"></span>

### Fail-closed evaluation

Principal access boundary policies fail closed. This means that, if IAM can't evaluate a principal access boundary policy when [evaluating a principal's access](https://docs.cloud.google.com/iam/docs/policy-types#evaluation) , then IAM prevents the principal from accessing the resource.

The most common reason that IAM isn't able to evaluate principal access boundary policies is that a principal's details are still propagating through the system. This is most likely to occur for newly created users. To resolve this issue, have the new principal wait and try to access the resource again later.

## Permissions that principal access boundary policies block

When principals try to access a resource that they aren't eligible to access, principal access boundary policies prevent them from using some, but not all, Identity and Access Management (IAM) permissions to access the resource.

If a principal access boundary policy blocks a permission, then IAM *enforces* principal access boundary policies for that permission. In other words, it prevents any principals that aren't eligible to access a resource from using that permission to access the resource.

If a principal access boundary policy doesn't block a permission, then principal access boundary policies have no effect on whether principals can use the permission.

For example, imagine that a principal, Lee ( `lee@example.com` ), is granted the Dataflow Developer role ( `roles/dataflow.developer` ). This role includes the `dataflow.jobs.snapshot` permission, which lets Lee take snapshots of Dataflow jobs. Lee is also subject to a principal access boundary policy that makes them ineligible to access resources outside of `example.com` . However, if principal access boundary policies don't block the `dataflow.jobs.snapshot` permission, then Lee can still take snapshots of Dataflow jobs in organizations outside of `example.com` .

The permissions that a principal access boundary policy blocks depends on the principal access boundary enforcement version.

### Principal access boundary enforcement versions

Each principal access boundary policy specifies an *enforcement version* , which identifies a predefined list of IAM permissions that the principal access boundary policy can block. You specify the enforcement version when you create or update a principal access boundary policy. If you don't specify an enforcement version, IAM uses the latest enforcement version, and will continue to use that version until you update it.

Periodically, IAM adds new principal access boundary enforcement versions that can block additional permissions. Each new version can also block all of the permissions in the previous version.

To block the permissions in a new enforcement version, you must update your principal access boundary policies to use the new version. If you want the enforcement version to update automatically as new versions are released, you can use the value `latest` when creating the policy. However, we don't recommend using this value, because it might cause principals to lose access to resources unexpectedly.

> **Note:** It can take up to 4 weeks for a new version to become the default enforcement version. The default enforcement version is used for new policies that don't specify a version number and for policies that use the value `latest` .

For a full list of the permissions that each enforcement version blocks, see [Permissions that principal access boundary policies block](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions) .

### Default enforcement version

The default enforcement version is used for the following principal access boundary policies:

  - New policies that don't specify a version number
  - Policies that use the value `latest` for the version

To learn which enforcement version is the default, see [Permissions that principal access boundary policies block](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions) .

## Bind principal access boundary policies to principal sets

To bind a principal access boundary policy to a principal set, you create a *policy binding* that specifies both the principal access boundary policy that you want to enforce and the principal set that you want to enforce it for. After you bind the policy to a principal set, the principals in that principal set can access only the resources that are included in the principal access boundary policy's rules.

You can bind a principal access boundary policy to any number of principal sets. Each principal set can have up to 10 principal access boundary policies bound to it.

You can only create bindings for existing principal access boundary policies. Trying to create a binding for a deleted principal access boundary policy will fail. If you recently deleted a principal access boundary policy, you can sometimes successfully create a binding, but the binding won't have any effect. IAM cleans up these bindings automatically.

To learn how to manage principal access boundary policies, see [Create and apply principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create) .

### Supported principal sets

The following table lists the types of principal sets that you can bind principal access boundary policies to. Each row contains the following:

  - The type of principal set
  - The principals in that type of principal set
  - The format of IDs for that type of principal set
  - The Resource Manager resource (project, folder, or organization) that parents policy bindings for that type of principal set

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal set</th>
<th>Details</th>
<th>Policy bindings' parent resource</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Workforce identity pool</td>
<td><p>Contains all identities in the specified <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pools">workforce identity pool</a> .</p>
<p>Format: <code dir="ltr" translate="no">//iam.googleapis.com/locations/global/workforcePools/          WORKFORCE_POOL_ID        </code></p></td>
<td>The organization that contains the workforce identity pool</td>
</tr>
<tr class="even">
<td>Workload identity pool</td>
<td><p>Contains all identities in the specified <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#pools">workload identity pool</a> .</p>
<p>Format: <code dir="ltr" translate="no">//iam.googleapis.com/projects/          PROJECT_NUMBER         /locations/global/workloadIdentityPools/          WORKLOAD_POOL_ID        </code></p></td>
<td>The project that contains the workload identity pool</td>
</tr>
<tr class="odd">
<td>Google Workspace domain</td>
<td><p>Contains all identities in the specified <a href="https://docs.cloud.google.com/iam/docs/principals-overview#domains">Google Workspace domain</a> .</p>
<p>Format: <code dir="ltr" translate="no">//iam.googleapis.com/locations/global/workspace/          CUSTOMER_ID        </code></p>
<p>You can find your customer ID by using the following methods:</p>
<ul>
<li>Use the <a href="https://docs.cloud.google.com/sdk/gcloud/reference/organizations/describe"><code dir="ltr" translate="no">gcloud organizations describe</code> command</a> . Your workspace ID is in the <code dir="ltr" translate="no">directoryCustomerId</code> field in the response.</li>
<li>Use the <a href="https://docs.cloud.google.com/resource-manager/reference/rest/v3/organizations/get"><code dir="ltr" translate="no">organizations.get</code> method</a> in the Cloud Resource Manager API. You workspace ID is in the <code dir="ltr" translate="no">directoryCustomerId</code> field in the response.</li>
<li><a href="https://support.google.com/cloudidentity/answer/10070793">View your customer ID in the Admin console</a> . This method requires <a href="https://support.google.com/a/answer/2405986">the Google Workspace super admin role</a> .</li>
</ul></td>
<td>The organization that's associated with the Google Workspace domain</td>
</tr>
<tr class="even">
<td>Project's principal set</td>
<td><p>Contains all service accounts, workload identity pools, and agent identities in the specified project.</p>
<p>Format: <code dir="ltr" translate="no">//cloudresourcemanager.googleapis.com/  projects/           PROJECT_ID        </code></p></td>
<td>The project</td>
</tr>
<tr class="odd">
<td>Folder's principal set</td>
<td><p>Contains all service accounts, all workload identity pools, and all agent identities in any project in the specified folder.</p>
<p>Format: <code dir="ltr" translate="no">//cloudresourcemanager.googleapis.com/  folders/           FOLDER_ID        </code></p></td>
<td>The folder</td>
</tr>
<tr class="even">
<td>Organization's principal set</td>
<td><p>Contains the following identities:</p>
<ul>
<li>All identities in all domains associated with your Google Workspace customer ID</li>
<li>All workforce identity pools in your organization</li>
<li>All service accounts, workload identity pools, and agent identities in any project in the organization</li>
</ul>
<p>Format: <code dir="ltr" translate="no">//cloudresourcemanager.googleapis.com/  organizations/           ORGANIZATION_ID        </code></p></td>
<td>The organization</td>
</tr>
</tbody>
</table>

### Conditional policy bindings for principal access boundary policies

You can use condition expressions in policy bindings for principal access boundary policies to further refine which principals the policy applies to.

Condition expressions for policy bindings consist of one or more statements joined by up to 10 logical operators ( `&&` , `||` , or `!` ). Each statement expresses an attribute-based control rule that applies to the policy binding, and ultimately determines whether the policy applies.

You can use the `principal.type` and `principal.subject` attributes in conditions for policy bindings. No other attributes are supported in conditions for policy bindings.

  - The `principal.type` attribute indicates what type of principal is in the request—for example, service accounts, or identities in a workload identity pool. You can use conditions with this attribute to control which types of principals a principal access boundary policy applies to.
    
    For example, if you add the following condition expression to a binding for a principal access boundary policy, then the policy only applies to service accounts:
    
        principal.type == 'iam.googleapis.com/ServiceAccount'

  - The `principal.subject` attribute indicates the identity of the principal in the request—for example, `cruz@example.com` . You can use conditions with this attribute to control exactly which principals are subject to a principal access boundary policy.
    
    For example, if you add the following condition expression to a binding for a principal access boundary policy, then the policy won't apply for the user `special-admin@example.com` :
    
        principal.subject != 'special-admin@example.com'

To learn more about the values that you can use for these conditions, see the [conditions attribute reference](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principals) .

#### Example: Use conditions to reduce the resources that a principal is eligible to access

One of the ways that you can use conditions in principal access boundary policy bindings is to reduce the resources that a single principal is eligible to access.

Imagine that you have a service account, `dev-project-service-account` , with the email address `dev-project-service-account@dev-project.iam.gserviceaccount.com` . This service account is subject to a principal access boundary policy that makes principals eligible to access all resources in the organization `example.com` . This policy is attached to the `example.com` organization's principal set.

You decide that you don't want `dev-project-service-account` to be eligible to access all resources in `example.com` —you only want it to be eligible to access resources in `dev-project` . However, you don't want to change the resources that other principals in the `example.com` principal set are eligible to access.

To make this change, you follow the procedure to [reduce the resources that principals are eligible to access](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#reduce-eligibility) , but you add a condition to the policy binding instead of deleting it:

1.  You confirm that the only principal access boundary policy that `dev-project-service-account` is subject to is the policy that makes principals eligible to access all resources in `example.com` .

2.  You [create a new principal access boundary policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create) that makes principals eligible to access resources in `dev-project` and attach it to the principal set for `dev-project` . You use the following [condition](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#conditions) in the policy binding to ensure that the policy is only enforced for `dev-project-service-account` :
    
        "condition": {
          "title": "Only dev-project-service-account",
          "expression": "principal.type == 'iam.googleapis.com/ServiceAccount' && principal.subject == 'dev-project-service-account@dev-project.iam.gserviceaccount.com'"
        }

3.  You exempt `dev-project-service-account` from the principal access boundary policy that makes principals eligible to access all resources in `example.com` . To do this, you add the following condition to the policy binding that attaches that principal access boundary policy to the organization's principal set:
    
        "condition": {
          "title": "Exempt dev-project-service-account",
          "expression": "principal.subject != 'dev-project-service-account@dev-project.iam.gserviceaccount.com' || principal.type != 'iam.googleapis.com/ServiceAccount'"
        }
    
    To learn how to update existing principal access boundary policies, see [Edit principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit) .

After you add this condition to the policy binding, `dev-project-service-account` is no longer eligible to access all resources in `example.com` —instead, it's only eligible to access resources in `dev-project` .

### Cross-organization policy bindings

You can't create a *cross-organization policy binding* for a principal access boundary policy. A cross-organization policy binding is a policy binding that binds a policy in one organization to a principal set in another organization.

IAM periodically deletes any existing cross-organization policy bindings. Cross-organization policy bindings can occur when you [move a project](https://docs.cloud.google.com/resource-manager/docs/project-migration) from one organization to another. For example, consider the following situation:

  - You have a project, `example-project` , in the organization `example.com` .
  - You want principals in `example-project` to be eligible to access resources in `example.com` . To do this, you create a principal access boundary policy in `example.com` that makes principals eligible to access resources in `example.com` and bind that policy to the principal set for `example-project` .
  - You move `example-project` from `example.com` to `cymbalgroup.com` .

In this situation, moving the project would create a cross-organization policy binding. This is because the principal access boundary policy in `example.com` would be bound to a principal set in `cymbalgroup.com` . If you don't delete the binding manually, IAM would eventually delete it automatically. Deleting this binding helps ensure that `cymbalgroup.com` administrators have access to all principal access boundary policies bound to their principals.

## Policy interactions

IAM evaluates each principal access boundary policy in combination with your allow and deny policies, and with your other principal access boundary policies. All of these policies are used to determine whether a principal can access a resource.

### Interaction with other policy types

When a principal tries to access a resource, IAM evaluates all relevant principal access boundary, allow, and deny policies to see if the principal is allowed to access the resource. If any one of these policies indicates that the principal shouldn't be able to access the resource, IAM prevents access.

As a result, if a principal access boundary policy would prevent a principal from accessing a resource, then IAM prevents them from accessing that resource, regardless of the allow and deny policies attached to the resource.

Additionally, principal access boundary policies alone don't give principals access to resources. While principal access boundary policies can make a principal *eligible* to access a resource, only allow policies can actually grant the principal access to the resource.

To learn more about IAM policy evaluation, see [Policy evaluation](https://docs.cloud.google.com/iam/docs/policy-types#evaluation) .

### Interaction between principal access boundary policies

If any principal access boundary policy makes a principal eligible to access a resource, then the principal is eligible to access that resource, regardless of the other principal access boundary policies the principal is subject to. As a result, if a principal is already subject to a principal access boundary policy, then you can't add principal access boundary policies to reduce a principal's access.

For example, imagine that a principal, Dana ( `dana@example.com` ), is subject to a single principal access boundary policy, `prod-projects-policy` . This policy makes principals eligible to access resources in `prod-project` . Dana is subject to this policy because it's bound to their organization's principal set.

You create a new principal access boundary policy, `dev-staging-projects-policy` , that makes principals eligible to access resources in `dev-project` and `staging-project` , and then bind it to the organization's principal set.

As a result of these principal access boundary policies, Dana is eligible to access resources in `dev-project` , `staging-project` , and `prod-project` .

If you want to reduce the resources that Dana is eligible to access, you need to modify or remove the principal access boundary policies that Dana is subject to.

For example, you could edit `dev-staging-projects-policy` so that it doesn't make principals eligible to access resources in `dev-project` . Then, Dana would only be eligible to access resources in `staging-project` and `prod-project` .

Alternatively, you could remove `prod-projects-policy` by deleting the policy binding that binds it to the organization's principal set. Then, Dana would only be eligible to access resources in `dev-project` and `staging-project` .

> **Important:** If you remove a principal access boundary policy to reduce a principal's access, ensure that the principal is always subject to at least one principal access boundary policy. If a principal isn't subject to any principal access boundary policies, then the principal is eligible to access all Google Cloud resources. To learn how to safely reduce a principal's access, see [Reduce the resources that principals are eligible to access](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#reduce-eligibility) .

However, these changes don't just affect Dana—they also affect the other principals that are subject to the modified principal access boundary policies and bindings. If you want to reduce the resources that a single principal is eligible to access, use [conditional policy bindings](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#use-conditions-reduce-eligibility) .

### Policy inheritance

Principal access boundary policies are attached to principal sets, not Resource Manager resources. As a result, they aren't inherited through the [resource hierarchy](https://docs.cloud.google.com/iam/docs/resource-hierarchy-access-control) in the same way that allow and deny policies are.

However, principal sets for Resource Manager parent resources—that is, folders and organizations—always include all of the principals in their descendants' principal sets. So, for example, if a principal is included in a project's principal set, it is also included in the principal sets of any parent folders or organizations.

For example, consider an organization, `example.com` . This organization is associated with the domain `example.com` , and has the following Resource Manager resources:

![Resource hierarchy for example.com](https://docs.cloud.google.com/static/iam/img/pab-sample-resource-hierarchy.svg)

![Resource hierarchy for example.com](https://docs.cloud.google.com/static/iam/img/pab-sample-resource-hierarchy.svg)

  - An organization, `example.com`
  - A project, `project-1` , that's a child of the organization
  - A folder, `folder-a` , that's a child of the organization
  - Two projects, `project-2` and `project-3` , that are children of `folder-a`

These resources' principal sets contain the following identities:

| Principal set                   | Google Workspace identities in the `example.com` domain | Workforce identity federation pools in `example.com` | Service accounts and workload identity pools in `project-1` | Service accounts and workload identity pools in `project-2` | Service accounts and workload identity pools in `project-3` |
| ------------------------------- | :-----------------------------------------------------: | :--------------------------------------------------: | :---------------------------------------------------------: | :---------------------------------------------------------: | :---------------------------------------------------------: |
| Principal set for `example.com` |                                                         |                                                      |                                                             |                                                             |                                                             |
| Principal set for `folder-a`    |                                                         |                                                      |                                                             |                                                             |                                                             |
| Principal set for `project-1`   |                                                         |                                                      |                                                             |                                                             |                                                             |
| Principal set for `project-2`   |                                                         |                                                      |                                                             |                                                             |                                                             |
| Principal set for `project-3`   |                                                         |                                                      |                                                             |                                                             |                                                             |

As a result, the following principals are affected by the following principal access boundary policies:

  - A Google Workspace identity in the `example.com` domain is in the principal set for `example.com` and will be affected by principal access boundary policies bound to that principal set.

  - A service account in `project-1` is in the principal sets for `project-1` and `example.com` and will be affected by principal access boundary policies bound to either of those principal sets.

  - A service account in `project-3` is in the principal sets for `project-3` , `folder-a` , and `example.com` , and will be affected by principal access boundary policies bound to any of those principal sets.

## Principal access boundary policies and cached resources

Certain Google Cloud services cache publicly visible resources. For example, Cloud Storage [caches objects that are publicly readable](https://docs.cloud.google.com/storage/docs/caching#built-in_caching_for) .

Whether principal access boundary can prevent ineligible principals from viewing a publicly visible resource depends on whether the resource is cached:

  - If the resource is cached, then principal access boundary can't prevent principals from viewing the resource
  - If the resource isn't cached, then principal access boundary prevents ineligible principals from viewing the resource

In all cases, principal access boundary policies prevent ineligible principals from modifying or deleting publicly visible resources.

## Structure of a principal access boundary policy

A principal access boundary policy is a collection of metadata and principal access boundary policy details. The metadata provides information like the policy name and when the policy was created. The policy details define what the policy does—for example, the resources that affected principals are eligible to access.

For example, the following principal access boundary policy makes the principals who are subject to the policy eligible to access the resources in the organization with the ID `0123456789012` .

    {
      "name": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-policy",
      "uid": "puid_0123456789012345678",
      "etag": "W/\"Gh/PcTdJD/AWHUhPW45kdw==\"",
      "displayName": "Example policy",
      "annotations": {
        "example-key": "example-value"
      },
      "createTime": "2024-01-02T15:01:23Z",
      "updateTime": "2024-01-02T15:01:23Z",
      "details": {
        "rules": [
          {
            "description": "Example principal access boundary policy rule",
            "resources": [
              "//cloudresourcemanager.googleapis.com/organizations/0123456789012"
            ],
            "effect": "ALLOW"
          }
        ],
        "enforcementVersion": "1"
      }
    }

The following sections describe the fields in a principal access boundary policy's metadata and details.

### Metadata

Principal access boundary policies contain the following metadata:

  - `name` : The name of the principal access boundary policy. This name has the format ` organizations/ ORGANIZATION_ID /locations/global/principalAccessBoundaryPolicies/ PAB_POLICY_ID  ` , where `  ORGANIZATION_ID  ` is the numeric ID of the organization where the principal access boundary policy was created and `  PAB_POLICY_ID  ` is the principal access boundary policy's alphanumeric ID.
  - `uid` : A unique ID assigned to the principal access boundary policy.
  - `etag` : An identifier for the policy's current state. This value changes when you update the policy. To prevent conflicting updates, the `etag` value must match the value that is stored in IAM. If the `etag` values don't match, the request fails.
  - `displayName` : A human-readable name for the principal access boundary policy.
  - `annotations` : Optional. A list of user-defined key-value pairs. You can use these annotations to add extra metadata to the policy—for example, who created the policy, or whether the policy was deployed by an automated pipeline. For more information about annotations, see [Annotations](https://google.aip.dev/148#annotations) .
  - `createTime` : The time when the principal access boundary policy was created.
  - `updateTime` : The time when the principal access boundary policy was last updated.

### Details

Each principal access boundary policy contains a `details` field. This field contains the principal access boundary rules and enforcement version:

  - `rules` : A list of principal access boundary rules, which define the resources that affected principals are eligible to access. Each rule contains the following fields:
    
      - `description` : A human-readable description for the rule.
    
      - `resources` : A list of Resource Manager resources (projects, folders, and organizations) that you want principals to be eligible to access. Any principal that is subject to this policy is eligible to access these resources.
        
        Each principal access boundary policy can reference a maximum of 500 resources across all rules in the policy.
    
      - `effect` : The relationship that principals have with the resources listed in the `resources` field. The only effect that you can specify in principal access boundary rules is `"ALLOW"` . This relationship makes the principals eligible to access the resources listed in the rule.

  - `enforcementVersion` : The enforcement version that IAM uses when enforcing the policy. The principal access boundary policy version determines which permissions the principal access boundary policy can block.
    
    For more information about principal access boundary policy versions, see [Principal access boundary enforcement versions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#versions) on this page.

## Structure of a policy binding

A policy binding for a principal access boundary policy contains the name of a policy, the name of the principal set to bind the policy to, and metadata describing the policy binding. It can also contain conditions that modify the exact principals that the policy applies to.

For example, the following policy binding binds the policy `example-policy` to all principals in the `example.com` organization, which has the ID `0123456789012` . The policy binding also contains a condition that prevents the policy from being enforced for the principal `super-admin@example.com` .

    {
      "name": "organizations/0123456789012/locations/global/policyBindings/example-policy-binding",
      "uid": "buid_01234567890123456789", 
      "etag": "W/\"cRMdDXbT82aLuZlvoL9Gqg==\"",
      "displayName": "Example policy binding",
      "annotations": {
        "example-key": "example-value"
      },
      "target": {
        "principalSet": "//cloudresourcemanager.googleapis.com/organizations/0123456789012"
      },
      "policyKind": "PRINCIPAL_ACCESS_BOUNDARY",
      "policy": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-policy",
      "policyUid": "puid_0123456789012345678",
      "condition": {
        "title": "Exempt principal",
        "description": "Don't enforce the policy for super-admin@example.com",
        "expression": "principal.subject != 'super-admin@example.com'"
      },
      "createTime": "2024-01-02T17:00:16Z",
      "updateTime": "2024-01-02T17:00:16Z"
    }

Each policy binding contains the following fields:

  - `name` : The name of the policy binding. This name has the format `  RESOURCE_TYPE / RESOURCE_ID /locations/global/policyBindings/ BINDING_ID  ` , where `  RESOURCE_TYPE/ RESOURCE_ID  ` is the type and ID of the policy binding's parent resource and `  BINDING_ID  ` is the policy binding's alphanumeric ID.

  - `uid` : A unique ID assigned to the policy binding.

  - `etag` : An identifier for the policy's current state. This value changes when you update the policy. To prevent conflicting updates, the `etag` value must match the value that is stored in IAM. If the `etag` values don't match, the request fails.

  - `displayName` : A human-readable name for the policy binding.

  - `annotations` : Optional. A list of user-defined key-value pairs. You can use these annotations to add extra metadata to the policy binding—for example, who created the policy binding, or whether the policy binding was deployed by an automated pipeline. For more information about annotations, see [Annotations](https://google.aip.dev/148#annotations) .

  - `target` : The principal set to bind the policy to. The value has the format `{"principalSet": PRINCIPAL_SET }` , where `  PRINCIPAL_SET  ` is the ID of the principal set that you want to bind the policy to.
    
    Each target can have up to 10 policies bound to it.

  - `policyKind` : The type of policy that the policy binding references. For policy bindings for principal access boundary policies, this value is always `PRINCIPAL_ACCESS_BOUNDARY` .

  - `policy` : The principal access boundary policy to bind to the target principal set.

  - `policyUid` : A unique ID assigned to the principal access boundary policy referenced in the `policy` field.

  - `condition` : Optional. A logic expression that affects which principals IAM enforces the policy for. If the condition evaluates to true or cannot be evaluated, Identity and Access Management enforces the policy for the principal making the request. If the condition evaluates to false, Identity and Access Management doesn't enforce the policy for the principal. For more information, see [Principal access boundary and conditions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#conditions) on this page.

  - `createTime` : The time when the policy binding was created.

  - `updateTime` : The time when the policy binding was last updated.

## Use cases

The following are common situations where you might want to use principal access boundary policies, and examples of the principal access boundary policies and policy bindings that you might create in each situation. To learn how to create principal access boundary policies and bind them to principal sets, see [Create and apply principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create) .

### Make principals eligible to access resources in your organization

You can use a principal access boundary policy to make principals in your organization eligible to access resources within your organization. If this is the only principal access boundary policy that the principals in your organization are subject to, then the principal access boundary policy will also make the principals in your organization ineligible to access resources outside of your organization.

For example, imagine that you want to make all principals in the organization `example.com` eligible to access resources within `example.com` and ineligible to access resources in other organizations. The principals that are in `example.com` include all identities in the `example.com` domain, all workforce identity pools in `example.com` , and all service accounts and workload identity pools in any project in `example.com` .

You don't have any principal access boundary policies that apply to any of the principals in your organization. As a result, all principals are eligible to access all resources.

To make principals eligible to access resources in `example.com` and ineligible to access resources outside of `example.com` , you create a principal access boundary policy that makes principals eligible to access resources in `example.com` :

    {
      "name": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-org-only",
      "displayName": "Boundary for principals in example.org",
      "details": {
        "rules": [
          {
            "description": "Principals are only eligible to access resources in example.org",
            "resources": [
                "//cloudresourcemanager.googleapis.com/organizations/0123456789012"
            ],
            "effect": "ALLOW"
          }
        ],
        "enforcementVersion": "1"
      }
    }

Then, you create a policy binding to bind this policy to the organization principal set:

    {
      "name": "organizations/0123456789012/locations/global/policyBindings/example-org-only-binding",
      "displayName": "Bind policy to all principals in example.com",
      "target": {
        "principalSet": "//cloudresourcemanager.googleapis.com/organizations/0123456789012"
      },
      "policyKind": "PRINCIPAL_ACCESS_BOUNDARY",
      "policy": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-org-only"
    }

When bound to the organization principal set, this policy makes all principals in `example.com` eligible to access resources in `example.com` . Because this is the only principal access boundary policy that these principals are subject to, the policy also makes the principals in `example.com` ineligible to access resources outside of your organization. This means that they can't use permissions that are [blocked by the principal access boundary policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#blocked-permissions) to access resources outside of `example.com` , even if they have those permissions on those resources.

### Make service accounts eligible to access resources in a single project

You can create a principal access boundary policy to make the service accounts in a specific project eligible to access resources within that project.

If this is the only principal access boundary policy that the service accounts are subject to, then the service accounts will *only* be eligible to access resources within that project.

For example, imagine that you have a project, `example-dev` , with the project number `901234567890` . You want to ensure that the service accounts in `example-dev` are only eligible to access resources in `example-dev` .

You have a principal access boundary policy that makes all principals in your organization, including the service accounts in `example-dev` , eligible to access resources in `example.com` . To see what this type of policy looks like, see [Make principals eligible to access resources in your organization](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#use-case-org-only) .

To make the service accounts in `example-dev` ineligible to access resources outside of `example-dev` , you first create a principal access boundary policy that makes principals eligible to access resources in `example-dev`

    {
      "name": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-dev-only",
      "displayName": "Boundary for principals in example-dev",
      "details": {
        "rules": [
          {
            "description": "Principals are only eligible to access resources in example-dev",
            "resources": [
              "//cloudresourcemanager.googleapis.com/projects/example-dev"
            ],
            "effect": "ALLOW"
          }
        ],
        "enforcementVersion": "1"
      }
    }

Then, you create a policy binding to bind this policy to all principals in `example-dev` , and add a condition so that the policy binding only applies for service accounts:

    {
      "name": "organizations/0123456789012/locations/global/policyBindings/example-dev-only-binding",
      "displayName": "Bind policy to all service accounts in example-dev",
      "target": {
        "principalSet": "//cloudresourcemanager.googleapis.com/projects/example-dev"
      },
      "policyKind": "PRINCIPAL_ACCESS_BOUNDARY",
      "policy": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-dev-only",
      "condition": {
        "title": "Only service accounts",
        "description": "Only enforce the policy if the principal in the request is a service account",
        "expression": "principal.type == 'iam.googleapis.com/ServiceAccount'"
      }
    }

However, this policy on its own doesn't change the resources that the service accounts are eligible to access. This is because there's an existing principal access boundary policy that makes all principals in `example.com` eligible to access all resources in `example.com` . Principal access boundary policies are [additive](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#policy-intersection) , so the service accounts in `example-dev` are still eligible to access all resources in `example.com` .

To ensure that service accounts in `example-dev` are *only* eligible to access resources in `example-dev` , you need to add a condition to the policy binding for the existing principal access boundary policy that prevents it from being enforced for the service accounts, including the [default service accounts](https://docs.cloud.google.com/iam/docs/service-account-types#default) , in `example-dev` :

    {
      "name": "organizations/0123456789012/locations/global/policyBindings/example-org-only-binding",
      "displayName": "Bind policy to all principals in example.com",
      "target": {
        "principalSet": "//cloudresourcemanager.googleapis.com/organizations/0123456789012"
      },
      "policyKind": "PRINCIPAL_ACCESS_BOUNDARY",
      "policy": "organizations/0123456789012/locations/global/principalAccessBoundaryPolicies/example-org-only",
      "condition": {
        "title": "Exempt example-dev service accounts",
        "description": "Don't enforce the policy for service accounts in the example-dev project",
        "expression": "principal.type != 'iam.googleapis.com/ServiceAccount' || !principal.subject.endsWith('@example-dev.iam.gserviceaccount.com') || !principal.subject == 'example-dev@appspot.gserviceaccount.com || !principal.subject == '901234567890-compute@developer.gserviceaccount.com'"
      }
    }

Now, the service accounts in `example-dev` are only eligible to access resources in `example-dev` . They're prevented from using permissions that are [blocked by the principal access boundary policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#blocked-permissions) to access resources outside of `example-dev` , even if they have those permission on those resources.

Later, if you want to increase the resources that these service accounts are eligible to access, you can add additional resources to the `example-dev-only` policy or create an additional principal access boundary policy and bind it to the service accounts.

## What's next

  - Learn how to [create and apply principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create) .
  - Review the [permission each principal access boundary policy enforcement version blocks](https://docs.cloud.google.com/iam/docs/pab-blocked-permissions) .
