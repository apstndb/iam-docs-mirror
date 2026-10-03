---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsRequest
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsRequest
title: ListOperationsRequest
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsRequest#SCHEMA_REPRESENTATION)

The request message for [`Operations.ListOperations`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/operations/list#google.longrunning.Operations.ListOperations) .

**JSON representation**

```
{
  "name": string,
  "filter": string,
  "pageSize": integer,
  "pageToken": string,
  "returnPartialSuccess": boolean
}
```

| Fields                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                 | `string` The name of the operation's parent resource.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `filter`               | `string` The standard list filter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `pageSize`             | `integer` The standard list page size.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `pageToken`            | `string` The standard list page token.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `returnPartialSuccess` | `boolean` When set to `true` , operations that are reachable are returned as normal, and those that are unreachable are returned in the [`ListOperationsResponse.unreachable`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsResponse#FIELDS.unreachable) field. This can only be `true` when reading across collections. For example, when `parent` is set to `"projects/example/locations/-"` . This field is not supported by default and will result in an `UNIMPLEMENTED` error if set unless explicitly documented otherwise in service or product specific documentation. |
