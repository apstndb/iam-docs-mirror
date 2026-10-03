---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule
title: AttestationRule
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule#SCHEMA_REPRESENTATION)

Defines which workloads can receive an identity within a pool. When an AttestationRule is defined under a managed identity, matching workloads may receive that identity.

**JSON representation**

```
{

  // Union field workload_descriptor can be only one of the following:
  "googleCloudResource": string
  // End of list of possible types for union field workload_descriptor.
}
```

| Fields                                                                                                                   |                                                                                                                                                                |
|--------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `workload_descriptor` . Descriptor for the workload. `workload_descriptor` can be only one of the following: |                                                                                                                                                                |
| `googleCloudResource`                                                                                                    | `string` Optional. A single workload operating on Google Cloud. For example: `//compute.googleapis.com/projects/123/uid/zones/us-central1-a/instances/12345` . |
