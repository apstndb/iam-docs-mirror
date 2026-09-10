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
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.locations.workloadIdentityPools/getAllowedLocations#try-it)

Returns the trust boundary info for a given workload identity pool.

### HTTP request

`GET https://iamcredentials.googleapis.com/v1/{name=projects/*/locations/*/workloadIdentityPools/*}/allowedLocations`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. Resource name of workload identity pool.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.workloadIdentityPools.get`

### Request body

The request body must be empty.

### Response body

Represents a list of allowed locations for given workload identity pool.

If successful, the response body contains data with the following structure:

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
  &quot;locations&quot;: [
    string
  ],
  &quot;encodedLocations&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`locations[]`

`string`

Output only. The human readable trust boundary locations. For example, \["us-central1", "europe-west1"\]

`encodedLocations`

`string`

Output only. The hex encoded bitmap of the trust boundary locations
