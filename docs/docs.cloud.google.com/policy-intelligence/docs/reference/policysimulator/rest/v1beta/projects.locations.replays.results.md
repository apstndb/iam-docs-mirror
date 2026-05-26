---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays.results
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays.results
title: 'REST Resource: projects.locations.replays.results'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [Resource: ReplayResult](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays.results#ReplayResult)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays.results#ReplayResult.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays.results#METHODS_SUMMARY)

## Resource: ReplayResult

The result of replaying a single access tuple against a simulated state.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;parent&quot;: string,&quot;accessTuple&quot;: {object (AccessTuple)},&quot;lastSeenDate&quot;: {object (Date)},// Union field result can be only one of the following:&quot;diff&quot;: {object (ReplayDiff)},&quot;error&quot;: {object (Status)}// End of list of possible types for union field result.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The resource name of the `ReplayResult` , in the following format:

`{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}/results/{replay-result-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the `  Replay  ` .

Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36/results/1234`

`parent`

`string`

The `  Replay  ` that the access tuple was included in.

`accessTuple`

` object ( AccessTuple  ` )

The access tuple that was replayed. This field includes information about the principal, resource, and permission that were involved in the access attempt.

`lastSeenDate`

` object ( Date  ` )

The latest date this access tuple was seen in the logs.

Union field `result` . The result of replaying the access tuple. `result` can be only one of the following:

`diff`

` object ( ReplayDiff  ` )

The difference between the principal's access under the current (baseline) policies and the principal's access under the proposed (simulated) policies.

This field is only included for access tuples that were successfully replayed and had different results under the current policies and the proposed policies.

`error`

` object ( Status  ` )

The error that caused the access tuple replay to fail.

This field is only included for access tuples that were not replayed successfully.

## Methods

### `            list           `

Lists the results of running a `  Replay  ` .
