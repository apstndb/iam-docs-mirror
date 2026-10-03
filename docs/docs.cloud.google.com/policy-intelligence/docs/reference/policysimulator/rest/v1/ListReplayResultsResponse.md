---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse
title: ListReplayResultsResponse
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/ListReplayResultsResponse#SCHEMA_REPRESENTATION)

Response message for [`Simulator.ListReplayResults`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/projects.locations.replays.results/list#google.cloud.policysimulator.v1.Simulator.ListReplayResults) .

**JSON representation**

```
{
  "replayResults": [
    {
      object (ReplayResult)
    }
  ],
  "nextPageToken": string
}
```

| Fields            |                                                                                                                                                                                                                                                                                                                                           |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `replayResults[]` | `object ( `[`ReplayResult`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult)` )` The results of running a [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) . |
| `nextPageToken`   | `string` A token that you can use to retrieve the next page of [`ReplayResult`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult) objects. If this field is omitted, there are no subsequent pages.                                                |
