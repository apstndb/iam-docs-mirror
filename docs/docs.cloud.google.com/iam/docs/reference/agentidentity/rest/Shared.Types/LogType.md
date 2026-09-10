---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/LogType
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/LogType
title: LogType
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

The list of valid permission types for which logging can be configured. Admin writes are always logged, and are not configurable.

Enums

`LOG_TYPE_UNSPECIFIED`

Default case. Should never be this.

`ADMIN_READ`

Admin reads. Example: CloudIAM getIamPolicy

`DATA_WRITE`

Data writes. Example: CloudSQL Users create

`DATA_READ`

Data reads. Example: CloudSQL Users list
