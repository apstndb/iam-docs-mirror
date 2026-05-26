---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/ListPolicyBindingsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/ListPolicyBindingsResponse
title: ListPolicyBindingsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/ListPolicyBindingsResponse#SCHEMA_REPRESENTATION)

Response message for ListPolicyBindings method.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyBindings&quot;: [{object (PolicyBinding)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyBindings[]`

` object ( PolicyBinding  ` )

The policy bindings from the specified parent.

`nextPageToken`

`string`

Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.
