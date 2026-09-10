---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/cloud.control2.shared.operations
title: Package cloud.control2.shared.operations
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  ReconciliationOperationMetadata  ` (message)
  - `  ReconciliationOperationMetadata.ExclusiveRepairActionFlag  ` (enum)

## ReconciliationOperationMetadata

Operation metadata returned by the CLH during resource state reconciliation.

Fields

` delete_resource (deprecated)  `

`bool`

> This item is deprecated\!

DEPRECATED. Use exclusive\_action instead.

`exclusive_action`

`  ExclusiveRepairActionFlag  `

Excluisive action returned by the CLH.

## ExclusiveRepairActionFlag

Some action that should be performed externally in order to complete this repair. These actions are exclusive meaning only one of them can be selected. If in the future there actions that can be applied in combination, we will add an InclusiveRepairActionFlag enum and an inclusive\_actions repeated field.

Enums

`UNKNOWN_REPAIR_ACTION`

Unknown repair action.

`DELETE`

The resource has to be deleted. When using this bit, the CLH should fail the operation. DEPRECATED. Instead use DELETE\_RESOURCE OperationSignal in SideChannel.

> This item is deprecated\!

`RETRY`

This resource could not be repaired but the repair should be tried again at a later time. This can happen if there is a dependency that needs to be resolved first- e.g. if a parent resource must be repaired before a child resource.
