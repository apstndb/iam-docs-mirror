---
name: documents/docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations
uri: https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations
title: 'Method: projects.locations.workloadIdentityPools.getAllowedLocations'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#body.WorkloadIdentityPoolAllowedLocations.SCHEMA_REPRESENTATION)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#try-it)

Returns the trust boundary info for a given workload identity pool.

### HTTP request

`GET https://iamcredentials.googleapis.com/v1/{name=projects/*/locations/*/workloadIdentityPools/*}/allowedLocations`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Required. Resource name of workload identity pool.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.workloadIdentityPools.get</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

Represents a list of allowed locations for given workload identity pool.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "locations": [
    string
  ],
  "encodedLocations": string
}
```

| Fields             |                                                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------------------------|
| `locations[]`      | `string` Output only. The human readable trust boundary locations. For example, \["us-central1", "europe-west1"\] |
| `encodedLocations` | `string` Output only. The hex encoded bitmap of the trust boundary locations                                      |
