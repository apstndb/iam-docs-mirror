---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse
title: ListRolesResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse#SCHEMA_REPRESENTATION)

The response containing the roles defined under a resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;roles&quot;: [{object (Role)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`roles[]`

` object ( Role  ` )

The Roles defined on this resource.

`nextPageToken`

`string`

To retrieve the next page of results, set `ListRolesRequest.page_token` to this value.
