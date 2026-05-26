---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/MethodType
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/MethodType
title: MethodType
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

The operation for which this constraint will be applied. To apply this constraint only when creating new resources, the `methodTypes` should be `CREATE` only. To apply this constraint when creating or deleting resources, the `methodTypes` should be `CREATE` and `DELETE` .

`UPDATE` only custom constraints are not supported. Use `CREATE` or `CREATE, UPDATE` .

Enums

`METHOD_TYPE_UNSPECIFIED`

This is only used for distinguishing unset values and should never be used. Results in an error.

`CREATE`

Constraint applied when creating the resource.

`UPDATE`

Constraint applied when updating the resource.

`DELETE`

Constraint applied when deleting the resource. Not currently supported.

`REMOVE_GRANT`

Constraint applied when removing an IAM grant.

`GOVERN_TAGS`

Constraint applied when enforcing forced tagging.
