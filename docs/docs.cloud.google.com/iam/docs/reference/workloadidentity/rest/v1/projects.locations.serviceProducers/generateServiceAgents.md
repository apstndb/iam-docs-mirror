---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents
title: 'Method: projects.locations.serviceProducers.generateServiceAgents'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#body.aspect)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations.serviceProducers/generateServiceAgents#try-it)

Creates all service agents for a given resource, location and service producer.

### HTTP request

`POST https://workloadidentity.googleapis.com/v1/{parent=projects/*/locations/*/serviceProducers/*}:generateServiceAgents`

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
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Required. The parent resource. The <code>location</code> for the parent resource must be <code>global</code> .</p>
<p>Examples:</p>
<ul>
<li>projects/1234/locations/global/serviceProducers/bigquery.googleapis.com</li>
<li>folders/2344/locations/global/serviceProducers/vertexai.googleapis.com</li>
<li>organizations/3344/locations/global/serviceProducers/iam.googleapis.com</li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations#Operation) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
