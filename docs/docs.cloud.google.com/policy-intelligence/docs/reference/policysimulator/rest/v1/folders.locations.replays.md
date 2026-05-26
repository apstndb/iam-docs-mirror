---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays
title: 'REST Resource: folders.locations.replays'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [Resource: Replay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.SCHEMA_REPRESENTATION)
      - [State](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.State)
      - [ReplayConfig](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.ReplayConfig)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.ReplayConfig.SCHEMA_REPRESENTATION)
      - [LogSource](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.LogSource)
      - [ResultsSummary](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.ResultsSummary)
          - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay.ResultsSummary.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#METHODS_SUMMARY)

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

### State

The current state of the `  Replay  ` .

Enums

`STATE_UNSPECIFIED`

Default value. This value is unused.

`PENDING`

The `Replay` has not started yet.

`RUNNING`

The `Replay` is currently running.

`SUCCEEDED`

The `Replay` has successfully completed.

`FAILED`

The `Replay` has finished with an error.

### ReplayConfig

The configuration used for a `  Replay  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyOverlay&quot;: {string: {object (Policy)},...},&quot;logSource&quot;: enum (LogSource)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyOverlay`

`map (key: string, value: object ( Policy` ))

A mapping of the resources that you want to simulate policies for and the policies that you want to simulate.

Keys are the full resource names for the resources. For example, `//cloudresourcemanager.googleapis.com/projects/my-project` . For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

Values are `Policy` objects representing the policies that you want to simulate.

Replays automatically take into account any IAM policies inherited through the resource hierarchy, and any policies set on descendant resources. You do not need to include these policies in the policy overlay.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`logSource`

` enum ( LogSource  ` )

The logs to use as input for the `  Replay  ` .

### LogSource

The source of the logs to use for a `  Replay  ` .

Enums

`LOG_SOURCE_UNSPECIFIED`

An unspecified log source. If the log source is unspecified, the `  Replay  ` defaults to using `RECENT_ACCESSES` .

`RECENT_ACCESSES`

All access logs from the last 90 days. These logs may not include logs from the most recent 7 days.

### ResultsSummary

Summary statistics about the replayed log entries.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;logCount&quot;: integer,&quot;unchangedCount&quot;: integer,&quot;differenceCount&quot;: integer,&quot;errorCount&quot;: integer,&quot;oldestDate&quot;: {object (Date)},&quot;newestDate&quot;: {object (Date)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`logCount`

`integer`

The total number of log entries replayed.

`unchangedCount`

`integer`

The number of replayed log entries with no difference between baseline and simulated policies.

`differenceCount`

`integer`

The number of replayed log entries with a difference between baseline and simulated policies.

`errorCount`

`integer`

The number of log entries that could not be replayed.

`oldestDate`

` object ( Date  ` )

The date of the oldest log entry replayed.

`newestDate`

` object ( Date  ` )

The date of the newest log entry replayed.

## Methods

### `            create           `

Creates and starts a `  Replay  ` using the given `  ReplayConfig  ` .

### `            get           `

Gets the specified `  Replay  ` .
