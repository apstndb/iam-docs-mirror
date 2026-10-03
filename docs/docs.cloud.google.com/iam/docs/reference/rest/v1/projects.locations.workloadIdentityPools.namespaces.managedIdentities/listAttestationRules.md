---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules
title: 'Method: projects.locations.workloadIdentityPools.namespaces.managedIdentities.listAttestationRules'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.ListAttestationRulesResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/listAttestationRules#try-it)

List all [`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule) on a [`WorkloadIdentityPoolManagedIdentity`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#WorkloadIdentityPoolManagedIdentity) .

### HTTP request

`GET https://iam.googleapis.com/v1/{resource=projects/*/locations/*/workloadIdentityPools/*/namespaces/*/managedIdentities/*}:listAttestationRules`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                  |
|------------|------------------------------------------------------------------------------------------------------------------|
| `resource` | `string` Required. The resource name of the managed identity or namespace resource to list attestation rules of. |

### Query parameters

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameters</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>filter</code></td>
<td><p><code>string</code></p>
<p>Optional. A query filter. Supports the following function:</p>
<ul>
<li><code>container_ids()</code> : Returns only the AttestationRules under the specific container ids. The function expects a comma-delimited list with only project numbers and must use the format <code>projects/&lt;project-number&gt;</code> . For example: <code>container_ids(projects/&lt;project-number-1&gt;, projects/&lt;project-number-2&gt;,...)</code> .</li>
</ul></td>
</tr>
<tr class="even">
<td><code>pageSize</code></td>
<td><p><code>integer</code></p>
<p>Optional. The maximum number of AttestationRules to return. If unspecified, at most 50 AttestationRules are returned. The maximum value is 100; values above 100 are truncated to 100.</p></td>
</tr>
<tr class="odd">
<td><code>pageToken</code></td>
<td><p><code>string</code></p>
<p>Optional. A page token, received from a previous <code>keys.list</code> call. Provide this to retrieve the subsequent page.</p></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

Response message for managedIdentities.listAttestationRules.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "attestationRules": [
    {
      object (AttestationRule)
    }
  ],
  "nextPageToken": string
}
```

| Fields               |                                                                                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `attestationRules[]` | `object ( `[`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule)` )` A list of AttestationRules.         |
| `nextPageToken`      | `string` Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages. |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `resource` resource:

- `CALLBACK`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
