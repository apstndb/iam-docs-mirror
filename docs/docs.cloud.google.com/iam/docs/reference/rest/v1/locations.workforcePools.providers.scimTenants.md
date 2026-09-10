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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;baseUri&quot;: string,&quot;state&quot;: enum (State),&quot;description&quot;: string,&quot;displayName&quot;: string,&quot;claimMapping&quot;: {string: string,...},&quot;purgeTime&quot;: string,&quot;serviceAgent&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. Gemini Enterprise only. The resource name of the SCIM Tenant.

Format: `locations/{location}/workforcePools/{workforcePool}/providers/ {workforcePoolProvider}/scimTenants/{scim_tenant}`

`baseUri`

`string`

Output only. Gemini Enterprise only. Represents the base URI as defined in [RFC 7644, Section 1.3](https://datatracker.ietf.org/doc/html/rfc7644#section-1.3) . Clients must use this as the root address for managing resources under the tenant.

Format: [https://iamscim.googleapis.com/{version}/{tenantId}/](https://iamscim.googleapis.com/%7Bversion%7D/%7BtenantId%7D/)

`state`

` enum ( State  ` )

Output only. Gemini Enterprise only. The state of the tenant.

`description`

`string`

Optional. Gemini Enterprise only. The description of the SCIM tenant.

Cannot exceed 256 characters.

`displayName`

`string`

Optional. Gemini Enterprise only. The display name of the SCIM tenant.

Cannot exceed 32 characters.

`claimMapping`

`map (key: string, value: string)`

Required. Immutable. Gemini Enterprise only. Maps SCIM attributes to Google attributes.

This mapping is used to associate the attributes synced via SCIM with the Google Cloud attributes used in IAM policies for Workforce Identity Federation. SCIM-managed user and group attributes are mapped to `google.subject` and `google.group` respectively.

Each key must be a string specifying the Google Cloud IAM attribute to map to. The supported keys are as follows:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.

  - `google.group` : Group the authenticating user belongs to. You can grant group access to resources using an IAM `principalSet` binding; access applies to all members of the group.

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) expression that maps SCIM user or group attribute to the normalized attribute specified by the corresponding map key.

Example: To map the SCIM user's `externalId` to `google.subject` and the SCIM group's `externalId` to `google.group` :

    {
      "google.subject": "user.externalId",
      "google.group": "group.externalId"
    }

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`purgeTime`

` string ( Timestamp  ` format)

Output only. Gemini Enterprise only. The timestamp that represents the time when the SCIM tenant is purged.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`serviceAgent`

`string`

Output only. Service Agent created by SCIM Tenant API. SCIM tokens created under this tenant will be attached to this service agent.

## State

Gemini Enterprise only. The current state of the SCIM tenant.

Enums

`STATE_UNSPECIFIED`

Gemini Enterprise only. State unspecified.

`ACTIVE`

Gemini Enterprise only. The tenant is active and may be used to provision users and groups.

`DELETED`

Gemini Enterprise only. The tenant is soft-deleted. Soft-deleted tenants are permanently deleted after approximately 30 days.

## Methods

### `            create           `

Gemini Enterprise only.

### `            delete           `

Gemini Enterprise only.

### `            get           `

Gemini Enterprise only.

### `            list           `

Gemini Enterprise only.

### `            patch           `

Gemini Enterprise only.

### `            undelete           `

Gemini Enterprise only.
