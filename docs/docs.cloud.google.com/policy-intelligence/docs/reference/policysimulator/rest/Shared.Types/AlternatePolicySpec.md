---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec
title: AlternatePolicySpec
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec#SCHEMA_REPRESENTATION)

Similar to PolicySpec but with an extra 'launch' field for launch reference. The PolicySpec here is specific for dry-run.

**JSON representation**

```
{
  "launch": string,
  "spec": {
    object (PolicySpec)
  }
}
```

| Fields   |                                                                                                                                                                                                               |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `launch` | `string` Reference to the launch that will be used while audit logging and to control the launch. Should be set only in the alternate policy.                                                                 |
| `spec`   | `object ( `[`PolicySpec`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec)` )` Specify constraint for configurations of Google Cloud resources. |
