---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools
title: 'REST Resource: projects.locations.workloadIdentityPools'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkloadIdentityPool](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#State)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#METHODS_SUMMARY)

## Resource: WorkloadIdentityPool

Represents a collection of external workload identities. You can define IAM policies to grant these identities access to Google Cloud resources.

**JSON representation**

```
{
  "name": string,
  "displayName": string,
  "description": string,
  "state": enum (State),
  "disabled": boolean,
  "expireTime": string
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | `string` Output only. The resource name of the pool.                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `displayName` | `string` A display name for the pool. Cannot exceed 32 characters.                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `description` | `string` A description of the pool. Cannot exceed 256 characters.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `state`       | `enum ( `[`State`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#State)` )` Output only. The state of the pool.                                                                                                                                                                                                                                                                                                            |
| `disabled`    | `boolean` Whether the pool is disabled. You cannot use a disabled pool to exchange tokens, or use existing tokens to access resources. If the pool is re-enabled, existing tokens grant access again.                                                                                                                                                                                                                                                                              |
| `expireTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. Time after which the workload identity pool will be permanently purged and cannot be recovered. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |

## State

The current state of the pool.

| Enums               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `ACTIVE`            | The pool is active, and may be used in Google Cloud policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `DELETED`           | The pool is soft-deleted. Soft-deleted pools are permanently deleted after approximately 30 days. You can restore a soft-deleted pool using [`workloadIdentityPools.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/undelete#google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPool) . You cannot reuse the ID of a soft-deleted pool until it is permanently deleted. While a pool is deleted, you cannot use it to exchange tokens, or use existing tokens to access resources. If the pool is undeleted, existing tokens grant access again. |

| Methods                                                                                                                      |                                                                                                                                                                                                                      |
|------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/create)     | Creates a new [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .                                                 |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/delete)     | Deletes a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .                                                     |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/get)           | Gets an individual [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .                                            |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/list)         | Lists all non-deleted [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) s in a project.                           |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/patch)       | Updates an existing [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .                                           |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools/undelete) | Undeletes a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools#WorkloadIdentityPool) , as long as it was deleted fewer than 30 days ago. |
