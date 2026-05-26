---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot
title: 'Method: iam.troubleshoot'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.HTTP_TEMPLATE)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.TroubleshootIamPolicyResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#body.aspect)
  - [AccessTuple](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessTuple)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessTuple.SCHEMA_REPRESENTATION)
  - [AccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessState)
  - [ExplainedPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#ExplainedPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#ExplainedPolicy.SCHEMA_REPRESENTATION)
  - [BindingExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#BindingExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#BindingExplanation.SCHEMA_REPRESENTATION)
  - [RolePermission](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#RolePermission)
  - [HeuristicRelevance](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#HeuristicRelevance)
  - [AnnotatedMembership](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AnnotatedMembership)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AnnotatedMembership.SCHEMA_REPRESENTATION)
  - [Membership](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#Membership)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#try-it)

Checks whether a member has a specific permission for a specific resource, and explains why the member does or does not have that permission.

### HTTP request

`POST https://policytroubleshooter.googleapis.com/v1beta/iam:troubleshoot`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessTuple&quot;: {object (AccessTuple)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessTuple`

` object ( AccessTuple  ` )

The information to use for checking whether a member has a permission for a resource.

### Response body

Response for `  iam.troubleshoot  ` .

If successful, the response body contains data with the following structure:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;access&quot;: enum (AccessState),&quot;explainedPolicies&quot;: [{object (ExplainedPolicy)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`access`

` enum ( AccessState  ` )

Indicates whether the member has the specified permission for the specified resource, based on evaluating all of the applicable policies.

`explainedPolicies[]`

` object ( ExplainedPolicy  ` )

List of IAM policies that were evaluated to check the member's permissions, with annotations to indicate how each policy contributed to the final result.

The list of policies can include the policy for the resource itself. It can also include policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project.

To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## AccessTuple

Information about the member, resource, and permission to check.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;principal&quot;: string,
  &quot;fullResourceName&quot;: string,
  &quot;permission&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principal`

`string`

Required. The member, or principal, whose access you want to check, in the form of the email address that represents that member. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` .

The member must be a Google Account or a service account. Other types of members are not supported.

`fullResourceName`

`string`

Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`permission`

`string`

Required. The IAM permission to check for the specified member and resource.

For a complete list of IAM permissions, see <https://cloud.google.com/iam/help/permissions/reference> .

For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .

## AccessState

Whether a member has a permission for a resource.

Enums

`ACCESS_STATE_UNSPECIFIED`

Reserved for future use.

`GRANTED`

The member has the permission.

`NOT_GRANTED`

The member does not have the permission.

`UNKNOWN_CONDITIONAL`

The member has the permission only if a condition expression evaluates to `true` .

`UNKNOWN_INFO_DENIED`

The sender of the request does not have access to all of the policies that Policy Troubleshooter needs to evaluate.

## ExplainedPolicy

Details about how a specific IAM `  Policy  ` contributed to the access check.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;access&quot;: enum (AccessState),&quot;fullResourceName&quot;: string,&quot;policy&quot;: {object (Policy)},&quot;bindingExplanations&quot;: [{object (BindingExplanation)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`access`

` enum ( AccessState  ` )

Indicates whether *this policy* provides the specified permission to the specified member for the specified resource.

This field does *not* indicate whether the member actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the member actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[IamChecker.TroubleshootIamPolicyResponse\].

`fullResourceName`

`string`

The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

If the sender of the request does not have access to the policy, this field is omitted.

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`policy`

` object ( Policy  ` )

The IAM policy attached to the resource.

If the sender of the request does not have access to the policy, this field is empty.

`bindingExplanations[]`

` object ( BindingExplanation  ` )

Details about how each binding in the policy affects the member's ability, or inability, to use the permission for the resource.

If the sender of the request does not have access to the policy, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall determination in the \[TroubleshootIamPolicyResponse\]\[IamChecker.TroubleshootIamPolicyResponse\].

If the sender of the request does not have access to the policy, this field is omitted.

## BindingExplanation

Details about how a binding in a policy affects a member's ability to use a permission.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;access&quot;: enum (AccessState),&quot;role&quot;: string,&quot;rolePermission&quot;: enum (RolePermission),&quot;rolePermissionRelevance&quot;: enum (HeuristicRelevance),&quot;memberships&quot;: {string: {object (AnnotatedMembership)},...},&quot;relevance&quot;: enum (HeuristicRelevance),&quot;condition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`access`

` enum ( AccessState  ` )

Indicates whether *this binding* provides the specified permission to the specified member for the specified resource.

This field does *not* indicate whether the member actually has the permission for the resource. There might be another binding that overrides this binding. To determine whether the member actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[IamChecker.TroubleshootIamPolicyResponse\].

`role`

`string`

The role that this binding grants. For example, `roles/compute.serviceAgent` .

For a complete list of predefined IAM roles, as well as the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .

`rolePermission`

` enum ( RolePermission  ` )

Indicates whether the role granted by this binding contains the specified permission.

`rolePermissionRelevance`

` enum ( HeuristicRelevance  ` )

The relevance of the permission's existence, or nonexistence, in the role to the overall determination for the entire policy.

`memberships`

` map (key: string, value: object ( AnnotatedMembership  ` ))

Indicates whether each member in the binding includes the member specified in the request, either directly or indirectly. Each key identifies a member in the binding, and each value indicates whether the member in the binding includes the member in the request.

For example, suppose that a binding includes the following members:

  - `user:alice@example.com`
  - `group:product-eng@example.com`

You want to troubleshoot access for `user:bob@example.com` . This user is a member of the group `group:product-eng@example.com` .

For the first member in the binding, the key is `user:alice@example.com` , and the `membership` field in the value is set to `MEMBERSHIP_NOT_INCLUDED` .

For the second member in the binding, the key is `group:product-eng@example.com` , and the `membership` field in the value is set to `MEMBERSHIP_INCLUDED` .

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this binding to the overall determination for the entire policy.

`condition`

` object ( Expr  ` )

A condition expression that prevents access unless the expression evaluates to `true` .

To learn about IAM Conditions, see <https://cloud.google.com/iam/help/conditions/overview> .

## RolePermission

Whether a role includes a specific permission.

Enums

`ROLE_PERMISSION_UNSPECIFIED`

Reserved for future use.

`ROLE_PERMISSION_INCLUDED`

The permission is included in the role.

`ROLE_PERMISSION_NOT_INCLUDED`

The permission is not included in the role.

`ROLE_PERMISSION_UNKNOWN_INFO_DENIED`

The sender of the request is not allowed to access the binding.

## HeuristicRelevance

The extent to which a single data point contributes to an overall determination.

Enums

`HEURISTIC_RELEVANCE_UNSPECIFIED`

Reserved for future use.

`NORMAL`

The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination.

`HIGH`

The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.

## AnnotatedMembership

Details about whether the binding includes the member.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;membership&quot;: enum (Membership),&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`membership`

` enum ( Membership  ` )

Indicates whether the binding includes the member.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the member's status to the overall determination for the binding.

## Membership

Whether the binding includes the member.

Enums

`MEMBERSHIP_UNSPECIFIED`

Reserved for future use.

`MEMBERSHIP_INCLUDED`

The binding includes the member. The member can be included directly or indirectly. For example:

  - A member is included directly if that member is listed in the binding.
  - A member is included indirectly if that member is in a Google group or G Suite domain that is listed in the binding.

`MEMBERSHIP_NOT_INCLUDED`

The binding does not include the member.

`MEMBERSHIP_UNKNOWN_INFO_DENIED`

The sender of the request is not allowed to access the binding.

`MEMBERSHIP_UNKNOWN_UNSUPPORTED`

The member is an unsupported type. Only Google Accounts and service accounts are supported.
