---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants
title: 'REST Resource: locations.workforcePools.providers.scimTenants'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkforcePoolProviderScimTenant](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#WorkforcePoolProviderScimTenant)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#WorkforcePoolProviderScimTenant.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#State)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#METHODS_SUMMARY)

## Resource: WorkforcePoolProviderScimTenant

Gemini Enterprise only. Represents a SCIM tenant. Used for provisioning and managing identity data (such as Users and Groups) in cross-domain environments.

**JSON representation**

```
{
  "name": string,
  "baseUri": string,
  "state": enum (State),
  "description": string,
  "displayName": string,
  "claimMapping": {
    string: string,
    ...
  },
  "purgeTime": string,
  "serviceAgent": string
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
<p>Identifier. Gemini Enterprise only. The resource name of the SCIM Tenant.</p>
<p>Format: <code>locations/{location}/workforcePools/{workforcePool}/providers/ {workforcePoolProvider}/scimTenants/{scim_tenant}</code></p></td>
</tr>
<tr class="even">
<td><code>baseUri</code></td>
<td><p><code>string</code></p>
<p>Output only. Gemini Enterprise only. Represents the base URI as defined in <a href="https://datatracker.ietf.org/doc/html/rfc7644#section-1.3">RFC 7644, Section 1.3</a> . Clients must use this as the root address for managing resources under the tenant.</p>
<p>Format: <a href="https://iamscim.googleapis.com/%7Bversion%7D/%7BtenantId%7D/">https://iamscim.googleapis.com/{version}/{tenantId}/</a></p></td>
</tr>
<tr class="odd">
<td><code>state</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants#State"><code>State</code></a><code> )</code></p>
<p>Output only. Gemini Enterprise only. The state of the tenant.</p></td>
</tr>
<tr class="even">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. Gemini Enterprise only. The description of the SCIM tenant.</p>
<p>Cannot exceed 256 characters.</p></td>
</tr>
<tr class="odd">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. Gemini Enterprise only. The display name of the SCIM tenant.</p>
<p>Cannot exceed 32 characters.</p></td>
</tr>
<tr class="even">
<td><code>claimMapping</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Required. Immutable. Gemini Enterprise only. Maps SCIM attributes to Google attributes.</p>
<p>This mapping is used to associate the attributes synced via SCIM with the Google Cloud attributes used in IAM policies for Workforce Identity Federation. SCIM-managed user and group attributes are mapped to <code>google.subject</code> and <code>google.group</code> respectively.</p>
<p>Each key must be a string specifying the Google Cloud IAM attribute to map to. The supported keys are as follows:</p>
<ul>
<li><p><code>google.subject</code> : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.</p></li>
<li><p><code>google.group</code> : Group the authenticating user belongs to. You can grant group access to resources using an IAM <code>principalSet</code> binding; access applies to all members of the group.</p></li>
</ul>
<p>Each value must be a <a href="https://opensource.google/projects/cel">Common Expression Language</a> expression that maps SCIM user or group attribute to the normalized attribute specified by the corresponding map key.</p>
<p>Example: To map the SCIM user's <code>externalId</code> to <code>google.subject</code> and the SCIM group's <code>externalId</code> to <code>google.group</code> :</p>
<pre data-fenced=""><code>{
  &quot;google.subject&quot;: &quot;user.externalId&quot;,
  &quot;google.group&quot;: &quot;group.externalId&quot;
}</code></pre>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>purgeTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Gemini Enterprise only. The timestamp that represents the time when the SCIM tenant is purged.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>serviceAgent</code></td>
<td><p><code>string</code></p>
<p>Output only. Service Agent created by SCIM Tenant API. SCIM tokens created under this tenant will be attached to this service agent.</p></td>
</tr>
</tbody>
</table>

## State

Gemini Enterprise only. The current state of the SCIM tenant.

| Enums               |                                                                                                                               |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | Gemini Enterprise only. State unspecified.                                                                                    |
| `ACTIVE`            | Gemini Enterprise only. The tenant is active and may be used to provision users and groups.                                   |
| `DELETED`           | Gemini Enterprise only. The tenant is soft-deleted. Soft-deleted tenants are permanently deleted after approximately 30 days. |

| Methods                                                                                                                        |                         |
|--------------------------------------------------------------------------------------------------------------------------------|-------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/create)     | Gemini Enterprise only. |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/delete)     | Gemini Enterprise only. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/get)           | Gemini Enterprise only. |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list)         | Gemini Enterprise only. |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/patch)       | Gemini Enterprise only. |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/undelete) | Gemini Enterprise only. |
