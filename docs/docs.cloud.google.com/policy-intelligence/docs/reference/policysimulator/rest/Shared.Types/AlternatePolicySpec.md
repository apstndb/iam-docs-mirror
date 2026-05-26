---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec
title: AlternatePolicySpec
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec#SCHEMA_REPRESENTATION)

Similar to PolicySpec but with an extra 'launch' field for launch reference. The PolicySpec here is specific for dry-run.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;launch&quot;: string,&quot;spec&quot;: {object (PolicySpec)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`launch`

`string`

Reference to the launch that will be used while audit logging and to control the launch. Should be set only in the alternate policy.

`spec`

` object ( PolicySpec  ` )

Specify constraint for configurations of Google Cloud resources.
