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

**JSON representation**

```
{
  "name": string,
  "parent": string,
  "accessTuple": {
    object (AccessTuple)
  },
  "lastSeenDate": {
    object (Date)
  },

  // Union field result can be only one of the following:
  "diff": {
    object (ReplayDiff)
  },
  "error": {
    object (Status)
  }
  // End of list of possible types for union field result.
}
```

| Fields                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                                                                                                      | `string` The resource name of the `ReplayResult` , in the following format: `{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}/results/{replay-result-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) . Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36/results/1234` |
| `parent`                                                                                                    | `string` The [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) that the access tuple was included in.                                                                                                                                                                                                                                                                                                                                                      |
| `accessTuple`                                                                                               | `object ( `[`AccessTuple`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessTuple)` )` The access tuple that was replayed. This field includes information about the principal, resource, and permission that were involved in the access attempt.                                                                                                                                                                                                |
| `lastSeenDate`                                                                                              | `object ( `[`Date`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Date)` )` The latest date this access tuple was seen in the logs.                                                                                                                                                                                                                                                                                                                                                       |
| Union field `result` . The result of replaying the access tuple. `result` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `diff`                                                                                                      | `object ( `[`ReplayDiff`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ReplayDiff)` )` The difference between the principal's access under the current (baseline) policies and the principal's access under the proposed (simulated) policies. This field is only included for access tuples that were successfully replayed and had different results under the current policies and the proposed policies.                                        |
| `error`                                                                                                     | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsResponse#Status)` )` The error that caused the access tuple replay to fail. This field is only included for access tuples that were not replayed successfully.                                                                                                                                                                                                                                          |

### ReplayDiff

The difference between the results of evaluating an access tuple under the current (baseline) policies and under the proposed (simulated) policies. This difference explains how a principal's access could change if the proposed policies were applied.

**JSON representation**

```
{
  "accessDiff": {
    object (AccessStateDiff)
  }
}
```

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessDiff` | `object ( `[`AccessStateDiff`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessStateDiff)` )` A summary and comparison of the principal's access under the current (baseline) policies and the proposed (simulated) policies for a single access tuple. The evaluation of the principal's access is reported in the [`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState) field. |

### AccessStateDiff

A summary and comparison of the principal's access under the current (baseline) policies and the proposed (simulated) policies for a single access tuple.

**JSON representation**

```
{
  "baseline": {
    object (ExplainedAccess)
  },
  "simulated": {
    object (ExplainedAccess)
  },
  "accessChange": enum (AccessChangeType)
}
```

| Fields         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `baseline`     | `object ( `[`ExplainedAccess`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedAccess)` )` The results of evaluating the access tuple under the current (baseline) policies. If the [`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState) couldn't be fully evaluated, this field explains why. |
| `simulated`    | `object ( `[`ExplainedAccess`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedAccess)` )` The results of evaluating the access tuple under the proposed (simulated) policies. If the AccessState couldn't be fully evaluated, this field explains why.                                                                                                                                                        |
| `accessChange` | `enum ( `[`AccessChangeType`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessChangeType)` )` How the principal's access, specified in the AccessState field, changed between the current (baseline) policies and proposed (simulated) policies.                                                                                                                                                                  |

### ExplainedAccess

Details about how a set of policies, listed in [`ExplainedPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedPolicy) , resulted in a certain [`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState) when replaying an access tuple.

**JSON representation**

```
{
  "accessState": enum (AccessState),
  "policies": [
    {
      object (ExplainedPolicy)
    }
  ],
  "errors": [
    {
      object (Status)
    }
  ]
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessState` | `enum ( `[`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState)` )` Whether the principal in the access tuple has permission to access the resource in the access tuple under the given policies.                                                                                                                                                                                                              |
| `policies[]`  | `object ( `[`ExplainedPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ExplainedPolicy)` )` If the [`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState) is `UNKNOWN` , this field contains the policies that led to that result. If the `AccessState` is `GRANTED` or `NOT_GRANTED` , this field is omitted. |
| `errors[]`    | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsResponse#Status)` )` If the [`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState) is `UNKNOWN` , this field contains a list of errors explaining why the result is `UNKNOWN` . If the `AccessState` is `GRANTED` or `NOT_GRANTED` , this field is omitted.             |

### AccessState

Whether a principal has a permission for a resource.

| Enums                      |                                                                                                                                                                                                                                                     |
|----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ACCESS_STATE_UNSPECIFIED` | Default value. This value is unused.                                                                                                                                                                                                                |
| `GRANTED`                  | The principal has the permission.                                                                                                                                                                                                                   |
| `NOT_GRANTED`              | The principal does not have the permission.                                                                                                                                                                                                         |
| `UNKNOWN_CONDITIONAL`      | The principal has the permission only if a condition expression evaluates to `true` .                                                                                                                                                               |
| `UNKNOWN_INFO_DENIED`      | The user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) does not have access to all of the policies that Policy Simulator needs to evaluate. |

### ExplainedPolicy

Details about how a specific IAM `Policy` contributed to the access check.

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

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `access`                | `enum ( `[`AccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState)` )` Indicates whether *this policy* provides the specified permission to the specified principal for the specified resource. This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `access` field in the \[TroubleshootIamPolicyResponse\]\[google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse\]. |
| `fullResourceName`      | `string` The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . If the user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) does not have access to the policy, this field is omitted. For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                 |
| `policy`                | `object ( ``Policy`` )` The IAM policy attached to the resource. If the user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) does not have access to the policy, this field is empty.                                                                                                                                                                                                                                                                                                                                                                                    |
| `bindingExplanations[]` | `object ( `[`BindingExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.BindingExplanation)` )` Details about how each binding in the policy affects the principal's ability, or inability, to use the permission for the resource. If the user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) does not have access to the policy, this field is omitted.                                                                                                             |
| `relevance`             | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.HeuristicRelevance)` )` The relevance of this policy to the overall determination in the \[TroubleshootIamPolicyResponse\]\[google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse\]. If the user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) does not have access to the policy, this field is omitted.                                                                         |

### BindingExplanation

Details about how a binding in a policy affects a principal's ability to use a permission.

**JSON representation**

```
{
  "access": enum (AccessState),
  "role": string,
  "rolePermission": enum (RolePermission),
  "rolePermissionRelevance": enum (HeuristicRelevance),
  "memberships": {
    string: {
      "membership": enum,
      "relevance": enum (HeuristicRelevance)
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
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessState"><code>AccessState</code></a><code> )</code></p>
<p>Required. Indicates whether <em>this binding</em> provides the specified permission to the specified principal for the specified resource.</p>
<p>This field does <em>not</em> indicate whether the principal actually has the permission for the resource. There might be another binding that overrides this binding. To determine whether the principal actually has the permission, use the <code>access</code> field in the [TroubleshootIamPolicyResponse][google.cloud.policytroubleshooter.v3.TroubleshootIamPolicyResponse].</p></td>
</tr>
<tr class="even">
<td><code>role</code></td>
<td><p><code>string</code></p>
<p>The role that this binding grants. For example, <code>roles/compute.serviceAgent</code> .</p>
<p>For a complete list of predefined IAM roles, as well as the permissions in each role, see <a href="https://cloud.google.com/iam/help/roles/reference">https://cloud.google.com/iam/help/roles/reference</a> .</p></td>
</tr>
<tr class="odd">
<td><code>rolePermission</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.RolePermission"><code>RolePermission</code></a><code> )</code></p>
<p>Indicates whether the role granted by this binding contains the specified permission.</p></td>
</tr>
<tr class="even">
<td><code>rolePermissionRelevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of the permission's existence, or nonexistence, in the role to the overall determination for the entire policy.</p></td>
</tr>
<tr class="odd">
<td><code>memberships[]</code></td>
<td><p><code>map (key: string, value: object)</code></p>
<p>Indicates whether each principal in the binding includes the principal specified in the request, either directly or indirectly. Each key identifies a principal in the binding, and each value indicates whether the principal in the binding includes the principal in the request.</p>
<p>For example, suppose that a binding includes the following principals:</p>
<ul>
<li><code>user:alice@example.com</code></li>
<li><code>group:product-eng@example.com</code></li>
</ul>
<p>The principal in the replayed access tuple is <code>user:bob@example.com</code> . This user is a principal of the group <code>group:product-eng@example.com</code> .</p>
<p>For the first principal in the binding, the key is <code>user:alice@example.com</code> , and the <code>membership</code> field in the value is set to <code>MEMBERSHIP_NOT_INCLUDED</code> .</p>
<p>For the second principal in the binding, the key is <code>group:product-eng@example.com</code> , and the <code>membership</code> field in the value is set to <code>MEMBERSHIP_INCLUDED</code> .</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>memberships[].membership</code></td>
<td><p><code>enum</code></p>
<p>Indicates whether the binding includes the principal.</p>
<p>Valid values of this enum field are:</p>
<p><code>MEMBERSHIP_UNSPECIFIED</code></p>
<p>,</p>
<p><code>MEMBERSHIP_INCLUDED</code></p>
<p>,</p>
<p><code>MEMBERSHIP_NOT_INCLUDED</code></p>
<p>,</p>
<p><code>MEMBERSHIP_UNKNOWN_INFO_DENIED</code></p>
<p>,</p>
<p><code>MEMBERSHIP_UNKNOWN_UNSUPPORTED</code></p></td>
</tr>
<tr class="odd">
<td><code>memberships[].relevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of the principal's status to the overall determination for the binding.</p></td>
</tr>
<tr class="even">
<td><code>relevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of this binding to the overall determination for the entire policy.</p></td>
</tr>
<tr class="odd">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Expr"><code>Expr</code></a><code> )</code></p>
<p>A condition expression that prevents this binding from granting access unless the expression evaluates to <code>true</code> .</p>
<p>To learn about IAM Conditions, see <a href="https://cloud.google.com/iam/docs/conditions-overview">https://cloud.google.com/iam/docs/conditions-overview</a> .</p></td>
</tr>
</tbody>
</table>

### RolePermission

Whether a role includes a specific permission.

| Enums                                 |                                                                                                                                                                                                      |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ROLE_PERMISSION_UNSPECIFIED`         | Default value. This value is unused.                                                                                                                                                                 |
| `ROLE_PERMISSION_INCLUDED`            | The permission is included in the role.                                                                                                                                                              |
| `ROLE_PERMISSION_NOT_INCLUDED`        | The permission is not included in the role.                                                                                                                                                          |
| `ROLE_PERMISSION_UNKNOWN_INFO_DENIED` | The user who created the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) is not allowed to access the binding. |

### HeuristicRelevance

The extent to which a single data point, such as the existence of a binding or whether a binding includes a specific principal, contributes to an overall determination.

| Enums                             |                                                                                                                             |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| `HEURISTIC_RELEVANCE_UNSPECIFIED` | Default value. This value is unused.                                                                                        |
| `NORMAL`                          | The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination. |
| `HIGH`                            | The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.    |

### AccessChangeType

How the principal's access, specified in the AccessState field, changed between the current (baseline) policies and proposed (simulated) policies.

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
<td><code>ACCESS_CHANGE_TYPE_UNSPECIFIED</code></td>
<td>Default value. This value is unused.</td>
</tr>
<tr class="even">
<td><code>NO_CHANGE</code></td>
<td>The principal's access did not change. This includes the case where both baseline and simulated are UNKNOWN, but the unknown information is equivalent.</td>
</tr>
<tr class="odd">
<td><code>UNKNOWN_CHANGE</code></td>
<td>The principal's access under both the current policies and the proposed policies is <code>UNKNOWN</code> , but the unknown information differs between them.</td>
</tr>
<tr class="even">
<td><code>ACCESS_REVOKED</code></td>
<td>The principal had access under the current policies ( <code>GRANTED</code> ), but will no longer have access after the proposed changes ( <code>NOT_GRANTED</code> ).</td>
</tr>
<tr class="odd">
<td><code>ACCESS_GAINED</code></td>
<td>The principal did not have access under the current policies ( <code>NOT_GRANTED</code> ), but will have access after the proposed changes ( <code>GRANTED</code> ).</td>
</tr>
<tr class="even">
<td><code>ACCESS_MAYBE_REVOKED</code></td>
<td><p>This result can occur for the following reasons:</p>
<ul>
<li><p>The principal had access under the current policies ( <code>GRANTED</code> ), but their access after the proposed changes is <code>UNKNOWN</code> .</p></li>
<li><p>The principal's access under the current policies is <code>UNKNOWN</code> , but they will not have access after the proposed changes ( <code>NOT_GRANTED</code> ).</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>ACCESS_MAYBE_GAINED</code></td>
<td><p>This result can occur for the following reasons:</p>
<ul>
<li><p>The principal did not have access under the current policies ( <code>NOT_GRANTED</code> ), but their access after the proposed changes is <code>UNKNOWN</code> .</p></li>
<li><p>The principal's access under the current policies is <code>UNKNOWN</code> , but they will have access after the proposed changes ( <code>GRANTED</code> ).</p></li>
</ul></td>
</tr>
</tbody>
</table>

### AccessTuple

Information about the principal, resource, and permission to check.

**JSON representation**

```
{
  "principal": string,
  "fullResourceName": string,
  "permission": string
}
```

| Fields             |                                                                                                                                                                                                                                                                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal`        | `string` Required. The principal whose access you want to check, in the form of the email address that represents that principal. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` . The principal must be a Google Account or a service account. Other types of principals are not supported. |
| `fullResourceName` | `string` Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .               |
| `permission`       | `string` Required. The IAM permission to check for the specified principal and resource. For a complete list of IAM permissions, see <https://cloud.google.com/iam/help/permissions/reference> . For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .  |

| Methods                                                                                                                                   |                                                                                                                                                                        |
|-------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`list`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results/list) | Lists the results of running a [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) . |
