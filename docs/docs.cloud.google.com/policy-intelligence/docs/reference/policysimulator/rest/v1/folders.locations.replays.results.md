---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results
title: 'REST Resource: folders.locations.replays.results'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [Resource: ReplayResult](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.SCHEMA_REPRESENTATION)
      - [ReplayDiff](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ReplayDiff)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ReplayDiff.SCHEMA_REPRESENTATION)
      - [AccessStateDiff](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessStateDiff)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessStateDiff.SCHEMA_REPRESENTATION)
      - [ExplainedAccess](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedAccess)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedAccess.SCHEMA_REPRESENTATION)
      - [AccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState)
      - [ExplainedPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedPolicy)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedPolicy.SCHEMA_REPRESENTATION)
      - [BindingExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.BindingExplanation)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.BindingExplanation.SCHEMA_REPRESENTATION)
      - [RolePermission](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.RolePermission)
      - [HeuristicRelevance](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.HeuristicRelevance)
      - [AccessChangeType](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessChangeType)
      - [AccessTuple](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessTuple)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessTuple.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#METHODS_SUMMARY)

## Resource: ReplayResult

The result of replaying a single access tuple against a simulated state.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;parent&quot;: string,&quot;accessTuple&quot;: {object (AccessTuple)},&quot;lastSeenDate&quot;: {object (Date)},// Union field result can be only one of the following:&quot;diff&quot;: {object (ReplayDiff)},&quot;error&quot;: {object (Status)}// End of list of possible types for union field result.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The resource name of the `ReplayResult` , in the following format:

`{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}/results/{replay-result-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the `  Replay  ` .

Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36/results/1234`

`parent`

`string`

The `  Replay  ` that the access tuple was included in.

`accessTuple`

` object ( AccessTuple  ` )

The access tuple that was replayed. This field includes information about the principal, resource, and permission that were involved in the access attempt.

`lastSeenDate`

` object ( Date  ` )

The latest date this access tuple was seen in the logs.

Union field `result` . The result of replaying the access tuple. `result` can be only one of the following:

`diff`

` object ( ReplayDiff  ` )

The difference between the principal's access under the current (baseline) policies and the principal's access under the proposed (simulated) policies.

This field is only included for access tuples that were successfully replayed and had different results under the current policies and the proposed policies.

`error`

` object ( Status  ` )

The error that caused the access tuple replay to fail.

This field is only included for access tuples that were not replayed successfully.

### ReplayDiff

The difference between the results of evaluating an access tuple under the current (baseline) policies and under the proposed (simulated) policies. This difference explains how a principal's access could change if the proposed policies were applied.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessDiff&quot;: {object (AccessStateDiff)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessDiff`

` object ( AccessStateDiff  ` )

A summary and comparison of the principal's access under the current (baseline) policies and the proposed (simulated) policies for a single access tuple.

The evaluation of the principal's access is reported in the `  AccessState  ` field.

### AccessStateDiff

A summary and comparison of the principal's access under the current (baseline) policies and the proposed (simulated) policies for a single access tuple.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;baseline&quot;: {object (ExplainedAccess)},&quot;simulated&quot;: {object (ExplainedAccess)},&quot;accessChange&quot;: enum (AccessChangeType)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`baseline`

` object ( ExplainedAccess  ` )

The results of evaluating the access tuple under the current (baseline) policies.

If the `  AccessState  ` couldn't be fully evaluated, this field explains why.

`simulated`

` object ( ExplainedAccess  ` )

The results of evaluating the access tuple under the proposed (simulated) policies.

If the AccessState couldn't be fully evaluated, this field explains why.

`accessChange`

` enum ( AccessChangeType  ` )

How the principal's access, specified in the AccessState field, changed between the current (baseline) policies and proposed (simulated) policies.

### ExplainedAccess

Details about how a set of policies, listed in `  ExplainedPolicy  ` , resulted in a certain `  AccessState  ` when replaying an access tuple.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessState&quot;: enum (AccessState),&quot;policies&quot;: [{object (ExplainedPolicy)}],&quot;errors&quot;: [{object (Status)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessState`

` enum ( AccessState  ` )

Whether the principal in the access tuple has permission to access the resource in the access tuple under the given policies.

`policies[]`

` object ( ExplainedPolicy  ` )

If the `  AccessState  ` is `UNKNOWN` , this field contains the policies that led to that result.

If the `AccessState` is `GRANTED` or `NOT_GRANTED` , this field is omitted.

`errors[]`

` object ( Status  ` )

If the `  AccessState  ` is `UNKNOWN` , this field contains a list of errors explaining why the result is `UNKNOWN` .

If the `AccessState` is `GRANTED` or `NOT_GRANTED` , this field is omitted.

### AccessState

Whether a principal has a permission for a resource.

Enums

`ACCESS_STATE_UNSPECIFIED`

Default value. This value is unused.

`GRANTED`

The principal has the permission.

`NOT_GRANTED`

The principal does not have the permission.

`UNKNOWN_CONDITIONAL`

The principal has the permission only if a condition expression evaluates to `true` .

`UNKNOWN_INFO_DENIED`

The user who created the `  Replay  ` does not have access to all of the policies that Policy Simulator needs to evaluate.

### ExplainedPolicy

Details about how a specific IAM `Policy` contributed to the access check.

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

Indicates whether *this policy* provides the specified permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse\].

`fullResourceName`

`string`

The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

If the user who created the `  Replay  ` does not have access to the policy, this field is omitted.

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`policy`

`object ( Policy` )

The IAM policy attached to the resource.

If the user who created the `  Replay  ` does not have access to the policy, this field is empty.

`bindingExplanations[]`

` object ( BindingExplanation  ` )

Details about how each binding in the policy affects the principal's ability, or inability, to use the permission for the resource.

If the user who created the `  Replay  ` does not have access to the policy, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall determination in the \[TroubleshootIamPolicyResponse\]\[google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse\].

If the user who created the `  Replay  ` does not have access to the policy, this field is omitted.

### BindingExplanation

Details about how a binding in a policy affects a principal's ability to use a permission.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;access&quot;: enum (AccessState),&quot;role&quot;: string,&quot;rolePermission&quot;: enum (RolePermission),&quot;rolePermissionRelevance&quot;: enum (HeuristicRelevance),&quot;memberships&quot;: {string: {&quot;membership&quot;: enum,&quot;relevance&quot;: enum (HeuristicRelevance)},...},&quot;relevance&quot;: enum (HeuristicRelevance),&quot;condition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`access`

` enum ( AccessState  ` )

Required. Indicates whether *this binding* provides the specified permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another binding that overrides this binding. To determine whether the principal actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse\].

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

`memberships[]`

`map (key: string, value: object)`

Indicates whether each principal in the binding includes the principal specified in the request, either directly or indirectly. Each key identifies a principal in the binding, and each value indicates whether the principal in the binding includes the principal in the request.

For example, suppose that a binding includes the following principals:

  - `user:alice@example.com`
  - `group:product-eng@example.com`

The principal in the replayed access tuple is `user:bob@example.com` . This user is a principal of the group `group:product-eng@example.com` .

For the first principal in the binding, the key is `user:alice@example.com` , and the `membership` field in the value is set to `MEMBERSHIP_NOT_INCLUDED` .

For the second principal in the binding, the key is `group:product-eng@example.com` , and the `membership` field in the value is set to `MEMBERSHIP_INCLUDED` .

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`memberships[].membership`

`enum`

Indicates whether the binding includes the principal.

Valid values of this enum field are:

`MEMBERSHIP_UNSPECIFIED`

,

`MEMBERSHIP_INCLUDED`

,

`MEMBERSHIP_NOT_INCLUDED`

,

`MEMBERSHIP_UNKNOWN_INFO_DENIED`

,

`MEMBERSHIP_UNKNOWN_UNSUPPORTED`

`memberships[].relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the principal's status to the overall determination for the binding.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this binding to the overall determination for the entire policy.

`condition`

` object ( Expr  ` )

A condition expression that prevents this binding from granting access unless the expression evaluates to `true` .

To learn about IAM Conditions, see <https://cloud.google.com/iam/docs/conditions-overview> .

### RolePermission

Whether a role includes a specific permission.

Enums

`ROLE_PERMISSION_UNSPECIFIED`

Default value. This value is unused.

`ROLE_PERMISSION_INCLUDED`

The permission is included in the role.

`ROLE_PERMISSION_NOT_INCLUDED`

The permission is not included in the role.

`ROLE_PERMISSION_UNKNOWN_INFO_DENIED`

The user who created the `  Replay  ` is not allowed to access the binding.

### HeuristicRelevance

The extent to which a single data point, such as the existence of a binding or whether a binding includes a specific principal, contributes to an overall determination.

Enums

`HEURISTIC_RELEVANCE_UNSPECIFIED`

Default value. This value is unused.

`NORMAL`

The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination.

`HIGH`

The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.

### AccessChangeType

How the principal's access, specified in the AccessState field, changed between the current (baseline) policies and proposed (simulated) policies.

Enums

`ACCESS_CHANGE_TYPE_UNSPECIFIED`

Default value. This value is unused.

`NO_CHANGE`

The principal's access did not change. This includes the case where both baseline and simulated are UNKNOWN, but the unknown information is equivalent.

`UNKNOWN_CHANGE`

The principal's access under both the current policies and the proposed policies is `UNKNOWN` , but the unknown information differs between them.

`ACCESS_REVOKED`

The principal had access under the current policies ( `GRANTED` ), but will no longer have access after the proposed changes ( `NOT_GRANTED` ).

`ACCESS_GAINED`

The principal did not have access under the current policies ( `NOT_GRANTED` ), but will have access after the proposed changes ( `GRANTED` ).

`ACCESS_MAYBE_REVOKED`

This result can occur for the following reasons:

  - The principal had access under the current policies ( `GRANTED` ), but their access after the proposed changes is `UNKNOWN` .

  - The principal's access under the current policies is `UNKNOWN` , but they will not have access after the proposed changes ( `NOT_GRANTED` ).

`ACCESS_MAYBE_GAINED`

This result can occur for the following reasons:

  - The principal did not have access under the current policies ( `NOT_GRANTED` ), but their access after the proposed changes is `UNKNOWN` .

  - The principal's access under the current policies is `UNKNOWN` , but they will have access after the proposed changes ( `GRANTED` ).

### AccessTuple

Information about the principal, resource, and permission to check.

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

Required. The principal whose access you want to check, in the form of the email address that represents that principal. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` .

The principal must be a Google Account or a service account. Other types of principals are not supported.

`fullResourceName`

`string`

Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`permission`

`string`

Required. The IAM permission to check for the specified principal and resource.

For a complete list of IAM permissions, see <https://cloud.google.com/iam/help/permissions/reference> .

For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .

## Methods

### `            list           `

Lists the results of running a `  Replay  ` .
