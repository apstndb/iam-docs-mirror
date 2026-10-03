---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse
title: ListReplaysResponse
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/ListReplaysResponse#SCHEMA_REPRESENTATION)

Response message for [`Simulator.ListReplays`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/projects.locations.replays/list#google.cloud.policysimulator.v1beta.Simulator.ListReplays) .

**JSON representation**

```
{
  "replays": [
    {
      object (Replay)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                                                                                                                                                                                         |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `replays[]`     | `object ( `[`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay)` )` The list of [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/folders.locations.replays#Replay) objects. |
| `nextPageToken` | `string` A token that you can use to retrieve the next page of results. If this field is omitted, there are no subsequent pages.                                                                                                                                                                                        |
