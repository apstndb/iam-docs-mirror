---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies
title: 'REST Resource: organizations.locations.principalAccessBoundaryPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: PrincipalAccessBoundaryPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicy)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicy.SCHEMA_REPRESENTATION)
- [PrincipalAccessBoundaryPolicyDetails](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyDetails)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyDetails.SCHEMA_REPRESENTATION)
- [PrincipalAccessBoundaryPolicyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyRule)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyRule.SCHEMA_REPRESENTATION)
- [Effect](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#Effect)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#METHODS_SUMMARY)

## Resource: PrincipalAccessBoundaryPolicy

An IAM principal access boundary policy resource.

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
    object (PrincipalAccessBoundaryPolicyDetails)
  }
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | `string` Identifier. The resource name of the principal access boundary policy. The following format is supported: `organizations/{organizationId}/locations/{location}/principalAccessBoundaryPolicies/{policyId}`                                                                                                                                                                                                                                              |
| `uid`         | `string` Output only. The globally unique ID of the principal access boundary policy.                                                                                                                                                                                                                                                                                                                                                                            |
| `etag`        | `string` Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.                                                                                                                                                                                                                                                                                                                                   |
| `displayName` | `string` Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.                                                                                                                                                                                                                                                                                                                                         |
| `annotations` | `map (key: string, value: string)` Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                                   |
| `createTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the principal access boundary policy was created. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .               |
| `updateTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the principal access boundary policy was most recently updated. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `details`     | `object ( `[`PrincipalAccessBoundaryPolicyDetails`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyDetails)` )` Optional. The details for the principal access boundary policy.                                                                                                                                                                                   |

## PrincipalAccessBoundaryPolicyDetails

Principal access boundary policy details

**JSON representation**

```
{
  "rules": [
    {
      object (PrincipalAccessBoundaryPolicyRule)
    }
  ],
  "enforcementVersion": string
}
```

| Fields               |                                                                                                                                                                                                                                                                                                                         |
|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]`            | `object ( `[`PrincipalAccessBoundaryPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyRule)` )` Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500. |
| `enforcementVersion` | `string` Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.                                                       |

## PrincipalAccessBoundaryPolicyRule

Principal access boundary policy rule that defines the resource boundary.

**JSON representation**

```
{
  "description": string,
  "resources": [
    string
  ],
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
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>resources[]</code></td>
<td><p><code>string</code></p>
<p>Required. A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.</p>
<p>The following resource types are supported:</p>
<ul>
<li>Organizations, such as <code>//cloudresourcemanager.googleapis.com/organizations/123</code> .</li>
<li>Folders, such as <code>//cloudresourcemanager.googleapis.com/folders/123</code> .</li>
<li>Projects, such as <code>//cloudresourcemanager.googleapis.com/projects/123</code> or <code>//cloudresourcemanager.googleapis.com/projects/my-project-id</code> .</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>effect</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies#Effect"><code>Effect</code></a><code> )</code></p>
<p>Required. The access relationship of principals to the resources in this rule.</p></td>
</tr>
</tbody>
</table>

## Effect

An effect to describe the access relationship.

| Enums                |                                              |
|----------------------|----------------------------------------------|
| `EFFECT_UNSPECIFIED` | Effect unspecified.                          |
| `ALLOW`              | Allows access to the resources in this rule. |

| Methods                                                                                                                                                         |                                                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/create)                             | Creates a principal access boundary policy, and returns a long running operation.                                     |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete)                             | Deletes a principal access boundary policy.                                                                           |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/get)                                   | Gets a principal access boundary policy.                                                                              |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list)                                 | Lists principal access boundary policies.                                                                             |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/patch)                               | Updates a principal access boundary policy.                                                                           |
| [`searchPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings) | Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy. |
