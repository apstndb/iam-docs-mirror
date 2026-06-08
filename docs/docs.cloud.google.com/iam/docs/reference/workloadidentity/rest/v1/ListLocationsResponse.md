---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse
title: ListLocationsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse#SCHEMA_REPRESENTATION)

The response message for `  Locations.ListLocations  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;locations&quot;: [{object (Location)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`locations[]`

` object ( Location  ` )

A list of locations that matches the specified filter in the request.

`nextPageToken`

`string`

The standard List next-page token.
