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

An IAM Unified Access Policy resource.

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
<p>Identifier. The resource name of the Unified Access Policy.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>folders/{folderId}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the Unified Access Policy.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the Unified Access Policy. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the Unified Access Policy. This description can be a maximum of 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User-defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations.</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the Unified Access Policy was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the Unified Access Policy was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>details</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails"><code>AccessPolicyDetails</code></a><code> )</code></p>
<p>Optional. The details for the Unified Access Policy.</p></td>
</tr>
</tbody>
</table>

### AccessPolicyDetails

Unified Access Policy details.

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

| Fields    |                                                                                                                                                                                                                   |
|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]` | `object ( `[`AccessPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule)` )` Required. A list of Unified Access Policy rules. |

### AccessPolicyRule

Unified Access Policy rule that determines the behavior of the policy.

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
<p>Required. The principals to include in the rule. This field can contain the following values:</p>
<ul>
<li><p><code>principal://goog/subject/{email_id}</code> : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, <code>principal://goog/subject/alice@example.com</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}</code> : A Google Cloud service account. For example, <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com</code> .</p></li>
<li><p><code>principalSet://goog/group/{groupId}</code> : A Google group. For example, <code>principalSet://goog/group/admins@example.com</code> .</p></li>
<li><p><code>principalSet://goog/cloudIdentityCustomerId/{customerId}</code> : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code> .</p></li>
<li><p><code>principalSet://goog/public:all</code> : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in. This value is only supported in rules with the <code>DENY</code> effect.</p></li>
<li><p><code>principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workforce identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{groupId}</code> : All workforce identities in a group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All workforce identities with a specific attribute value.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*</code> : All identities in a workforce identity pool.</p></li>
<li><p><code>principal://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workload identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/group/{groupId}</code> : A workload identity pool group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All identities in a workload identity pool with a certain attribute.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/*</code> : All identities in a workload identity pool.</p></li>
<li><p><code>principal://{trust_domain}/{agent_resource_path}/{agent_id}</code> : A single, specific agent identity.</p></li>
<li><p><code>principalSet://{trust_domain}/*</code> : All agent identities that belong to a particular trust domain.</p></li>
<li><p><code>principalSet://{trust_domain}/attribute.{attribute_name}/{attribute_value}</code> : All agents with a particular attribute.</p></li>
</ul>
<p>If an identifier that was previously used in a rule is soft deleted, then a <code>deleted</code> prefix is automatically added to the identifier. Users can't add new identifiers with this syntax.</p>
<ul>
<li><p><code>deleted:principal://goog/subject/{email_id}?uid={uid}</code> : A specific Google Account that was deleted recently. For example, <code>deleted:principal://goog/subject/alice@example.com?uid=1234567890</code> . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.</p></li>
<li><p><code>deleted:principalSet://goog/group/{groupId}?uid={uid}</code> : A Google group that was deleted recently. For example, <code>deleted:principalSet://goog/group/admins@example.com?uid=1234567890</code> . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}</code> : A Google Cloud service account that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890</code> . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A workforce identity that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code> . If the workforce identity is undeleted, this identifier reverts to the standard identifier for a workforce identity.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>excludedPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The principals to exclude from the rule, even if they are listed in the <code>principals</code> . For example, you could add a Google group to the <code>principals</code> , then exclude specific users who belong to that group.</p></td>
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
 &quot;iam.googleapis.com&quot;: {
  &quot;expression&quot;: {cel_expression}
 }
}</code></pre>
<p>Each rule is evaluated independently. If this rule does not apply to a request, other rules might still apply. The following keys are supported:</p>
<ul>
<li><p><code>eventarc.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate resource fields.</p></li>
<li><p><code>iam.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> and combine them using boolean and logical operators. Other functions and operators are not supported.</p></li>
<li><p><code>iap.googleapis.com</code> : Can use <code>CEL</code> functions and <a href="https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern/policies/cel-attributes-uap">attributes</a> that evaluate destination resources for requests that use the <code>iap.googleapis.com/resources.egressViaIAP</code> permission.</p></li>
</ul>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. Customer-specified description of the rule. This description can be a maximum of 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>effect</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Effect"><code>Effect</code></a><code> )</code></p>
<p>Required. The effect of the rule.</p></td>
</tr>
</tbody>
</table>

### Effect

An effect to describe how the rule affects access.

| Enums                |                                                     |
|----------------------|-----------------------------------------------------|
| `EFFECT_UNSPECIFIED` | The effect is unspecified.                          |
| `DENY`               | The rule will deny access if it evaluates to true.  |
| `ALLOW`              | The rule will grant access if it evaluates to true. |

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
<p>Optional. The permissions to include in the rule. Rules with the <code>ALLOW</code> effect grant the specified permissions. Rules with the <code>DENY</code> effect deny the specified permissions.</p>
<p>The following formats are supported:</p>
<ul>
<li>Individual permissions: Individual permissions use the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. For example, <code>eventarc.googleapis.com/messageBuses.publish</code> .</li>
<li>Roles: Only supported in rules with the <code>ALLOW</code> effect. Roles use the format <code>role:{role_name}</code> . For example, <code>role:roles/logging.logsViewer</code> . If you include a role name in a rule, then the rule includes all of the permissions in that role.</li>
<li>Permission groups: Sets of permissions, such as <code>aiplatform.googleapis.com/*.*</code> . Permission groups are sets of permissions that match a specified pattern. There are some restrictions on the permission groups you can reference and the permissions included in those groups. For more information, see <a href="https://docs.cloud.google.com/iam/help/uap/permission-groups">Permission groups</a> .</li>
</ul>
<p>An empty list doesn't match any <code>permissions</code> .</p></td>
</tr>
<tr class="even">
<td><code>excludedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Specifies the permissions to exclude from the rule. If a permission appears in <code>permissions</code> <em>and</em> in <code>excludedPermissions</code> , then it will <em>not</em> be subject to the rule effect.</p>
<p>The excluded permissions can be specified using the same syntax as <code>permissions</code> .</p></td>
</tr>
</tbody>
</table>

| Methods                                                                                                                                      |                                                                                                                       |
|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create)                             | Creates a Unified Access Policy, and returns a long running operation.                                                |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete)                             | Deletes a Unified Access Policy.                                                                                      |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get)                                   | Gets a Unified Access Policy.                                                                                         |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list)                                 | Lists Unified Access Policies.                                                                                        |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/patch)                               | Updates a Unified Access Policy.                                                                                      |
| [`searchPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/searchPolicyBindings) | Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy. |
