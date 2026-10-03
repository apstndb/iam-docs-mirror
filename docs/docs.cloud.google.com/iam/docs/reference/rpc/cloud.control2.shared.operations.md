---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations
title: Package cloud.control2.shared.operations
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`ReconciliationOperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations#cloud.control2.shared.operations.ReconciliationOperationMetadata) (message)
- [`ReconciliationOperationMetadata.ExclusiveRepairActionFlag`](https://docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations#cloud.control2.shared.operations.ReconciliationOperationMetadata.ExclusiveRepairActionFlag) (enum)

## ReconciliationOperationMetadata

Operation metadata returned by the CLH during resource state reconciliation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>delete_resource </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>bool</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>DEPRECATED. Use exclusive_action instead.</p></td>
</tr>
<tr class="even">
<td><code>exclusive_action</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations#cloud.control2.shared.operations.ReconciliationOperationMetadata.ExclusiveRepairActionFlag"><code>ExclusiveRepairActionFlag</code></a></p>
<p>Excluisive action returned by the CLH.</p></td>
</tr>
</tbody>
</table>

## ExclusiveRepairActionFlag

Some action that should be performed externally in order to complete this repair. These actions are exclusive meaning only one of them can be selected. If in the future there actions that can be applied in combination, we will add an InclusiveRepairActionFlag enum and an inclusive_actions repeated field.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>UNKNOWN_REPAIR_ACTION</code></td>
<td>Unknown repair action.</td>
</tr>
<tr class="even">
<td><code>DELETE</code></td>
<td><p>The resource has to be deleted. When using this bit, the CLH should fail the operation. DEPRECATED. Instead use DELETE_RESOURCE OperationSignal in SideChannel.</p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><code>RETRY</code></td>
<td>This resource could not be repaired but the repair should be tried again at a later time. This can happen if there is a dependency that needs to be resolved first- e.g. if a parent resource must be repaired before a child resource.</td>
</tr>
</tbody>
</table>
