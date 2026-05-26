---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse
title: ListReplayResultsResponse
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse#SCHEMA_REPRESENTATION)

Response message for `  Simulator.ListReplayResults  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;replayResults&quot;: [{object (ReplayResult)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`replayResults[]`

` object ( ReplayResult  ` )

The results of running a `  Replay  ` .

`nextPageToken`

`string`

A token that you can use to retrieve the next page of `  ReplayResult  ` objects. If this field is omitted, there are no subsequent pages.
