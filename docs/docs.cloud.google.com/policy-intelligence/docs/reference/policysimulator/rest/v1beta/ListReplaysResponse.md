---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse
title: ListReplaysResponse
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse#SCHEMA_REPRESENTATION)

Response message for `  Simulator.ListReplays  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;replays&quot;: [{object (Replay)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`replays[]`

` object ( Replay  ` )

The list of `  Replay  ` objects.

`nextPageToken`

`string`

A token that you can use to retrieve the next page of results. If this field is omitted, there are no subsequent pages.
