---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies
title: 'REST Resource: folders.locations.accessPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: AccessPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.SCHEMA_REPRESENTATION)
  - [AccessPolicyDetails](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails)
    - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails.SCHEMA_REPRESENTATION)
  - [AccessPolicyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule)
    - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule.SCHEMA_REPRESENTATION)
  - [Effect](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Effect)
  - [Operation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Operation)
    - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Operation.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#METHODS_SUMMARY)

## Resource: AccessPolicy

An IAM access policy resource.

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "etag": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "createTime": string,
  "updateTime": string,
  "details": {
    object (AccessPolicyDetails)
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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Identifier. The resource name of the access policy.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>folders/{folderId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/accessPolicies/{policyId}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the access policy.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the access policy. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the access policy. Must be less than or equal to 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the access policy was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the access policy was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>details</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails"><code>AccessPolicyDetails</code></a><code> )</code></p>
<p>Optional. The details for the access policy.</p></td>
</tr>
</tbody>
</table>

### AccessPolicyDetails

Access policy details.

**JSON representation**

```
{
  "rules": [
    {
      object (AccessPolicyRule)
    }
  ]
}
```

| Fields    |                                                                                                                                                                                                           |
|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]` | `object ( `[`AccessPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule)` )` Required. A list of access policy rules. |

### AccessPolicyRule

Access Policy Rule that determines the behavior of the policy.

**JSON representation**

```
{
  "principals": [
    string
  ],
  "excludedPrincipals": [
    string
  ],
  "operation": {
    object (Operation)
  },
  "conditions": {
    string: {
      object (Expr)
    },
    ...
  },
  "description": string,
  "effect": enum (Effect)
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
<td><code>principals[]</code></td>
<td><p><code>string</code></p>
<p>Required. The identities for which this rule's effect governs using one or more permissions on Google Cloud resources. This field can contain the following values:</p>
<ul>
<li><p><code>principal://goog/subject/{email_id}</code> : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, <code>principal://goog/subject/alice@example.com</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}</code> : A Google Cloud service account. For example, <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com</code> .</p></li>
<li><p><code>principalSet://goog/group/{groupId}</code> : A Google group. For example, <code>principalSet://goog/group/admins@example.com</code> .</p></li>
<li><p><code>principalSet://goog/cloudIdentityCustomerId/{customerId}</code> : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code> .</p></li>
</ul>
<p>If an identifier that was previously set on a policy is soft deleted, then calls to read that policy will return the identifier with a deleted prefix. Users cannot set identifiers with this syntax.</p>
<ul>
<li><p><code>deleted:principal://goog/subject/{email_id}?uid={uid}</code> : A specific Google Account that was deleted recently. For example, <code>deleted:principal://goog/subject/alice@example.com?uid=1234567890</code> . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.</p></li>
<li><p><code>deleted:principalSet://goog/group/{groupId}?uid={uid}</code> : A Google group that was deleted recently. For example, <code>deleted:principalSet://goog/group/admins@example.com?uid=1234567890</code> . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}</code> : A Google Cloud service account that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890</code> . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>excludedPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The identities that are excluded from the access policy rule, even if they are listed in the <code>principals</code> . For example, you could add a Google group to the <code>principals</code> , then exclude specific users who belong to that group.</p></td>
</tr>
<tr class="odd">
<td><code>operation</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Operation"><code>Operation</code></a><code> )</code></p>
<p>Required. Attributes that are used to determine whether this rule applies to a request.</p></td>
</tr>
<tr class="even">
<td><code>conditions</code></td>
<td><p><code>map (key: string, value: object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Expr"><code>Expr</code></a><code> ))</code></p>
<p>Optional. The conditions that determine whether this rule applies to a request. Conditions are identified by their key, which is the FQDN of the service that they are relevant to. For example:</p>
<pre data-fenced=""><code>&quot;conditions&quot;: {
 &quot;iam.googleapis.com&quot;: &lt;cel expression&gt;
}</code></pre>
<p>Each rule is evaluated independently. If this rule does not apply to a request, other rules might still apply. Currently supported keys are as follows:</p>
<ul>
<li><p><code>eventarc.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate resource fields.</p></li>
<li><p><code>iam.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> and combine them using boolean and logical operators. Other functions and operators are not supported.</p></li>
</ul>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. Customer specified description of the rule. Must be less than or equal to 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>effect</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Effect"><code>Effect</code></a><code> )</code></p>
<p>Required. The effect of the rule.</p></td>
</tr>
</tbody>
</table>

### Effect

An effect to describe the access relationship.

| Enums                |                                                       |
|----------------------|-------------------------------------------------------|
| `EFFECT_UNSPECIFIED` | The effect is unspecified.                            |
| `DENY`               | The policy will deny access if it evaluates to true.  |
| `ALLOW`              | The policy will grant access if it evaluates to true. |

### Operation

Attributes that are used to determine whether this rule applies to a request.

**JSON representation**

```
{
  "permissions": [
    string
  ],
  "excludedPermissions": [
    string
  ]
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
<td><code>permissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The permissions that are explicitly affected by this rule. Each permission uses the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. Currently supported permissions are as follows:</p>
<ul>
<li><code>eventarc.googleapis.com/messageBuses.publish</code> .</li>
</ul></td>
</tr>
<tr class="even">
<td><code>excludedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Specifies the permissions that this rule excludes from the set of affected permissions given by <code>permissions</code> . If a permission appears in <code>permissions</code> <em>and</em> in <code>excludedPermissions</code> then it will <em>not</em> be subject to the policy effect.</p>
<p>The excluded permissions can be specified using the same syntax as <code>permissions</code> .</p></td>
</tr>
</tbody>
</table>

| Methods                                                                                                                                      |                                                                                                                       |
|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create)                             | Creates an access policy, and returns a long running operation.                                                       |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete)                             | Deletes an access policy.                                                                                             |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get)                                   | Gets an access policy.                                                                                                |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list)                                 | Lists access policies.                                                                                                |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/patch)                               | Updates an access policy.                                                                                             |
| [`searchPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/searchPolicyBindings) | Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy. |
