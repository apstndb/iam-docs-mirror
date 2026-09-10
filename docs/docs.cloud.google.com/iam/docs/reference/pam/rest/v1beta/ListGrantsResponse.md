---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse
title: ListGrantsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/ListGrantsResponse#SCHEMA_REPRESENTATION)

Message for response to listing grants.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;grants&quot;: [{object (Grant)}],&quot;nextPageToken&quot;: string,&quot;unreachable&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`grants[]`

` object ( Grant  ` )

The list of grants.

`nextPageToken`

`string`

A token identifying a page of results the server should return.

`unreachable[]`

`string`

Locations that could not be reached.
