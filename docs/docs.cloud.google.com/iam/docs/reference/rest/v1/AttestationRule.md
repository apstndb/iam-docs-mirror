---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule
title: AttestationRule
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule#SCHEMA_REPRESENTATION)

Defines which workloads can receive an identity within a pool. When an AttestationRule is defined under a managed identity, matching workloads may receive that identity.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field workload_descriptor can be only one of the following:&quot;googleCloudResource&quot;: string// End of list of possible types for union field workload_descriptor.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `workload_descriptor` . Descriptor for the workload. `workload_descriptor` can be only one of the following:

`googleCloudResource`

`string`

Optional. A single workload operating on Google Cloud. For example: `//compute.googleapis.com/projects/123/uid/zones/us-central1-a/instances/12345` .
