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
- [Try it!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#try-it)

Checks whether a member has a specific permission for a specific resource, and explains why the member does or does not have that permission.

### HTTP request

`POST https://policytroubleshooter.googleapis.com/v1beta/iam:troubleshoot`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "accessTuple": {
    object (AccessTuple)
  }
}
```

| Fields        |                                                                                                                                                                                                                                                      |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessTuple` | `object ( `[`AccessTuple`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessTuple)` )` The information to use for checking whether a member has a permission for a resource. |

### Response body

Response for [`iam.troubleshoot`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#google.cloud.policytroubleshooter.v1beta.IamChecker.TroubleshootIamPolicy) .

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "access": enum (AccessState),
  "explainedPolicies": [
    {
      object (ExplainedPolicy)
    }
  ]
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `access`              | `enum ( `[`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessState)` )` Indicates whether the member has the specified permission for the specified resource, based on evaluating all of the applicable policies.                                                                                                                                                                                                                                                                                                                                                                |
| `explainedPolicies[]` | `object ( `[`ExplainedPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#ExplainedPolicy)` )` List of IAM policies that were evaluated to check the member's permissions, with annotations to indicate how each policy contributed to the final result. The list of policies can include the policy for the resource itself. It can also include policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project. To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> . |

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## AccessTuple

Information about the member, resource, and permission to check.

**JSON representation**

```
{
  "principal": string,
  "fullResourceName": string,
  "permission": string
}
```

| Fields             |                                                                                                                                                                                                                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal`        | `string` Required. The member, or principal, whose access you want to check, in the form of the email address that represents that member. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` . The member must be a Google Account or a service account. Other types of members are not supported. |
| `fullResourceName` | `string` Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                  |
| `permission`       | `string` Required. The IAM permission to check for the specified member and resource. For a complete list of IAM permissions, see <https://cloud.google.com/iam/help/permissions/reference> . For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .        |

## AccessState

Whether a member has a permission for a resource.

| Enums                      |                                                                                                                     |
|----------------------------|---------------------------------------------------------------------------------------------------------------------|
| `ACCESS_STATE_UNSPECIFIED` | Reserved for future use.                                                                                            |
| `GRANTED`                  | The member has the permission.                                                                                      |
| `NOT_GRANTED`              | The member does not have the permission.                                                                            |
| `UNKNOWN_CONDITIONAL`      | The member has the permission only if a condition expression evaluates to `true` .                                  |
| `UNKNOWN_INFO_DENIED`      | The sender of the request does not have access to all of the policies that Policy Troubleshooter needs to evaluate. |

## ExplainedPolicy

Details about how a specific IAM [`Policy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/Policy) contributed to the access check.

**JSON representation**

```
{
  "access": enum (AccessState),
  "fullResourceName": string,
  "policy": {
    object (Policy)
  },
  "bindingExplanations": [
    {
      object (BindingExplanation)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `access`                | `enum ( `[`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessState)` )` Indicates whether *this policy* provides the specified permission to the specified member for the specified resource. This field does *not* indicate whether the member actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the member actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[IamChecker.TroubleshootIamPolicyResponse\]. |
| `fullResourceName`      | `string` The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . If the sender of the request does not have access to the policy, this field is omitted. For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                                                                                              |
| `policy`                | `object ( `[`Policy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/Policy)` )` The IAM policy attached to the resource. If the sender of the request does not have access to the policy, this field is empty.                                                                                                                                                                                                                                                                                                                                               |
| `bindingExplanations[]` | `object ( `[`BindingExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#BindingExplanation)` )` Details about how each binding in the policy affects the member's ability, or inability, to use the permission for the resource. If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                  |
| `relevance`             | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#HeuristicRelevance)` )` The relevance of this policy to the overall determination in the \[TroubleshootIamPolicyResponse\]\[IamChecker.TroubleshootIamPolicyResponse\]. If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                     |

## BindingExplanation

Details about how a binding in a policy affects a member's ability to use a permission.

**JSON representation**

```
{
  "access": enum (AccessState),
  "role": string,
  "rolePermission": enum (RolePermission),
  "rolePermissionRelevance": enum (HeuristicRelevance),
  "memberships": {
    string: {
      object (AnnotatedMembership)
    },
    ...
  },
  "relevance": enum (HeuristicRelevance),
  "condition": {
    object (Expr)
  }
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>access</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AccessState"><code>AccessState</code></a><code> )</code></p>
<p>Indicates whether <em>this binding</em> provides the specified permission to the specified member for the specified resource.</p>
<p>This field does <em>not</em> indicate whether the member actually has the permission for the resource. There might be another binding that overrides this binding. To determine whether the member actually has the permission, use the <code>access</code> field in the [TroubleshootIamPolicyResponse][IamChecker.TroubleshootIamPolicyResponse].</p></td>
</tr>
<tr class="even">
<td><code>role</code></td>
<td><p><code>string</code></p>
<p>The role that this binding grants. For example, <code>roles/compute.serviceAgent</code> .</p>
<p>For a complete list of predefined IAM roles, as well as the permissions in each role, see <a href="https://cloud.google.com/iam/help/roles/reference">https://cloud.google.com/iam/help/roles/reference</a> .</p></td>
</tr>
<tr class="odd">
<td><code>rolePermission</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#RolePermission"><code>RolePermission</code></a><code> )</code></p>
<p>Indicates whether the role granted by this binding contains the specified permission.</p></td>
</tr>
<tr class="even">
<td><code>rolePermissionRelevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of the permission's existence, or nonexistence, in the role to the overall determination for the entire policy.</p></td>
</tr>
<tr class="odd">
<td><code>memberships</code></td>
<td><p><code>map (key: string, value: object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#AnnotatedMembership"><code>AnnotatedMembership</code></a><code> ))</code></p>
<p>Indicates whether each member in the binding includes the member specified in the request, either directly or indirectly. Each key identifies a member in the binding, and each value indicates whether the member in the binding includes the member in the request.</p>
<p>For example, suppose that a binding includes the following members:</p>
<ul>
<li><code>user:alice@example.com</code></li>
<li><code>group:product-eng@example.com</code></li>
</ul>
<p>You want to troubleshoot access for <code>user:bob@example.com</code> . This user is a member of the group <code>group:product-eng@example.com</code> .</p>
<p>For the first member in the binding, the key is <code>user:alice@example.com</code> , and the <code>membership</code> field in the value is set to <code>MEMBERSHIP_NOT_INCLUDED</code> .</p>
<p>For the second member in the binding, the key is <code>group:product-eng@example.com</code> , and the <code>membership</code> field in the value is set to <code>MEMBERSHIP_INCLUDED</code> .</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>relevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of this binding to the overall determination for the entire policy.</p></td>
</tr>
<tr class="odd">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/Expr"><code>Expr</code></a><code> )</code></p>
<p>A condition expression that prevents access unless the expression evaluates to <code>true</code> .</p>
<p>To learn about IAM Conditions, see <a href="https://cloud.google.com/iam/help/conditions/overview">https://cloud.google.com/iam/help/conditions/overview</a> .</p></td>
</tr>
</tbody>
</table>

## RolePermission

Whether a role includes a specific permission.

| Enums                                 |                                                                 |
|---------------------------------------|-----------------------------------------------------------------|
| `ROLE_PERMISSION_UNSPECIFIED`         | Reserved for future use.                                        |
| `ROLE_PERMISSION_INCLUDED`            | The permission is included in the role.                         |
| `ROLE_PERMISSION_NOT_INCLUDED`        | The permission is not included in the role.                     |
| `ROLE_PERMISSION_UNKNOWN_INFO_DENIED` | The sender of the request is not allowed to access the binding. |

## HeuristicRelevance

The extent to which a single data point contributes to an overall determination.

| Enums                             |                                                                                                                             |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| `HEURISTIC_RELEVANCE_UNSPECIFIED` | Reserved for future use.                                                                                                    |
| `NORMAL`                          | The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination. |
| `HIGH`                            | The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.    |

## AnnotatedMembership

Details about whether the binding includes the member.

**JSON representation**

```
{
  "membership": enum (Membership),
  "relevance": enum (HeuristicRelevance)
}
```

| Fields       |                                                                                                                                                                                                                                                               |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `membership` | `enum ( `[`Membership`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#Membership)` )` Indicates whether the binding includes the member.                                                 |
| `relevance`  | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v1beta/iam/troubleshoot#HeuristicRelevance)` )` The relevance of the member's status to the overall determination for the binding. |

## Membership

Whether the binding includes the member.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>MEMBERSHIP_UNSPECIFIED</code></td>
<td>Reserved for future use.</td>
</tr>
<tr class="even">
<td><code>MEMBERSHIP_INCLUDED</code></td>
<td><p>The binding includes the member. The member can be included directly or indirectly. For example:</p>
<ul>
<li>A member is included directly if that member is listed in the binding.</li>
<li>A member is included indirectly if that member is in a Google group or G Suite domain that is listed in the binding.</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>MEMBERSHIP_NOT_INCLUDED</code></td>
<td>The binding does not include the member.</td>
</tr>
<tr class="even">
<td><code>MEMBERSHIP_UNKNOWN_INFO_DENIED</code></td>
<td>The sender of the request is not allowed to access the binding.</td>
</tr>
<tr class="odd">
<td><code>MEMBERSHIP_UNKNOWN_UNSUPPORTED</code></td>
<td>The member is an unsupported type. Only Google Accounts and service accounts are supported.</td>
</tr>
</tbody>
</table>
