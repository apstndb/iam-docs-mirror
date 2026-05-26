---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays
title: 'REST Resource: organizations.locations.replays'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [Resource: Replay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays#Replay)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays#Replay.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays#METHODS_SUMMARY)

## Resource: Replay

A resource describing a `Replay` , or simulation.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;state&quot;: enum (State),&quot;config&quot;: {object (ReplayConfig)},&quot;resultsSummary&quot;: {object (ResultsSummary)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. The resource name of the `Replay` , which has the following format:

`{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the Replay.

Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36`

`state`

` enum ( State  ` )

Output only. The current state of the `Replay` .

`config`

` object ( ReplayConfig  ` )

Required. The configuration used for the `Replay` .

`resultsSummary`

` object ( ResultsSummary  ` )

Output only. Summary statistics about the replayed log entries.

## Methods

### `            create           `

Creates and starts a `  Replay  ` using the given `  ReplayConfig  ` .

### `            get           `

Gets the specified `  Replay  ` .

### `            list           `

Lists each `  Replay  ` in a project, folder, or organization.
