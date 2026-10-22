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

  // The following is a list of mutually exclusive fields. At most one of the
  // fields will be set in a response:
  "googleCloudResource": string
  // End of mutually exclusive fields.
}
```

| Fields                                                                                                                                  |                                                                                                                                                                |
|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Descriptor for the workload. The following is a list of mutually exclusive fields. At most one of the fields will be set in a response: |                                                                                                                                                                |
| `googleCloudResource`                                                                                                                   | `string` Optional. A single workload operating on Google Cloud. For example: `//compute.googleapis.com/projects/123/uid/zones/us-central1-a/instances/12345` . |
| End of mutually exclusive fields.                                                                                                       |                                                                                                                                                                |
