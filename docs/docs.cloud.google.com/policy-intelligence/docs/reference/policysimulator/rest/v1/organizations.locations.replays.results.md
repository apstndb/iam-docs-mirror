---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results
title: 'REST Resource: organizations.locations.replays.results'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [Resource: ReplayResult](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results#ReplayResult)
  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results#ReplayResult.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results#METHODS_SUMMARY)

## Resource: ReplayResult

The result of replaying a single access tuple against a simulated state.

**JSON representation**

```
{
  "name": string,
  "parent": string,
  "accessTuple": {
    object (AccessTuple)
  },
  "lastSeenDate": {
    object (Date)
  },

  // Union field result can be only one of the following:
  "diff": {
    object (ReplayDiff)
  },
  "error": {
    object (Status)
  }
  // End of list of possible types for union field result.
}
```

| Fields                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                                                                                                      | `string` The resource name of the `ReplayResult` , in the following format: `{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}/results/{replay-result-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) . Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36/results/1234` |
| `parent`                                                                                                    | `string` The [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) that the access tuple was included in.                                                                                                                                                                                                                                                                                                                                                      |
| `accessTuple`                                                                                               | `object ( `[`AccessTuple`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.AccessTuple)` )` The access tuple that was replayed. This field includes information about the principal, resource, and permission that were involved in the access attempt.                                                                                                                                                                                                |
| `lastSeenDate`                                                                                              | `object ( `[`Date`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Date)` )` The latest date this access tuple was seen in the logs.                                                                                                                                                                                                                                                                                                                                                       |
| Union field `result` . The result of replaying the access tuple. `result` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `diff`                                                                                                      | `object ( `[`ReplayDiff`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.results#ReplayResult.ReplayDiff)` )` The difference between the principal's access under the current (baseline) policies and the principal's access under the proposed (simulated) policies. This field is only included for access tuples that were successfully replayed and had different results under the current policies and the proposed policies.                                        |
| `error`                                                                                                     | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsResponse#Status)` )` The error that caused the access tuple replay to fail. This field is only included for access tuples that were not replayed successfully.                                                                                                                                                                                                                                          |

| Methods                                                                                                                                         |                                                                                                                                                                        |
|-------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`list`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list) | Lists the results of running a [`Replay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays#Replay) . |
