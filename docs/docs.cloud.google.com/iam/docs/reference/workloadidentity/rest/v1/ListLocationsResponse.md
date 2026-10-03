---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse
title: ListLocationsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/ListLocationsResponse#SCHEMA_REPRESENTATION)

The response message for [`Locations.ListLocations`](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/projects.locations/list#google.cloud.location.Locations.ListLocations) .

**JSON representation**

```
{
  "locations": [
    {
      object (Location)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                                                                         |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `locations[]`   | `object ( `[`Location`](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations#Location)` )` A list of locations that matches the specified filter in the request. |
| `nextPageToken` | `string` The standard List next-page token.                                                                                                                                                             |
