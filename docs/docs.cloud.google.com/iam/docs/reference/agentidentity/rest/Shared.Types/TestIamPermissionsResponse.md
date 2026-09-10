---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse
title: TestIamPermissionsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/Shared.Types/TestIamPermissionsResponse#SCHEMA_REPRESENTATION)

Response message for `authProviders.testIamPermissions` method.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;permissions&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`permissions[]`

`string`

A subset of `TestPermissionsRequest.permissions` that the caller is allowed.
