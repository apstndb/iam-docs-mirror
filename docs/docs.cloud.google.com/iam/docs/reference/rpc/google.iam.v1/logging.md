---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1/logging
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v1/logging
title: Package google.iam.v1.logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  AuditData  ` (message)

## AuditData

Audit log information specific to Cloud IAM. This message is serialized as an `Any` type in the `ServiceData` message of an `AuditLog` message.

Fields

`policy_delta`

`  PolicyDelta  `

Policy delta between the original policy and the newly set policy.
