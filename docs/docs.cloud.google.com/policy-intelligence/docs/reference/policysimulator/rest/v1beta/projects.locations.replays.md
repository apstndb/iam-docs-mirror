---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays
title: 'REST Resource: projects.locations.replays'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [Resource: Replay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays#Replay)
  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays#Replay.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays#METHODS_SUMMARY)

## Resource: Replay

A resource describing a `Replay` , or simulation.

**JSON representation**

```
{
  "name": string,
  "state": enum (State),
  "config": {
    object (ReplayConfig)
  },
  "resultsSummary": {
    object (ResultsSummary)
  }
}
```

| Fields           |                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`           | `string` Output only. The resource name of the `Replay` , which has the following format: `{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the Replay. Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36` |
| `state`          | `enum ( `[`State`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay.State)` )` Output only. The current state of the `Replay` .                                                                                                                                                                         |
| `config`         | `object ( `[`ReplayConfig`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay.ReplayConfig)` )` Required. The configuration used for the `Replay` .                                                                                                                                                      |
| `resultsSummary` | `object ( `[`ResultsSummary`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay.ResultsSummary)` )` Output only. Summary statistics about the replayed log entries.                                                                                                                                      |

| Methods                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                               |
|--------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays/create) | Creates and starts a [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay) using the given [`ReplayConfig`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay.ReplayConfig) . |
| [`get`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays/get)       | Gets the specified [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay) .                                                                                                                                                                                |
| [`list`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays/list)     | Lists each [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay) in a project, folder, or organization.                                                                                                                                                   |
