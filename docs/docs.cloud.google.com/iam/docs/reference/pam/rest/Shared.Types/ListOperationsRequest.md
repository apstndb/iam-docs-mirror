---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListOperationsRequest
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListOperationsRequest
title: ListOperationsRequest
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/Shared.Types/ListOperationsRequest#SCHEMA_REPRESENTATION)

The request message for `Operations.ListOperations` .

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
  &quot;name&quot;: string,
  &quot;filter&quot;: string,
  &quot;pageSize&quot;: integer,
  &quot;pageToken&quot;: string,
  &quot;returnPartialSuccess&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The name of the operation's parent resource.

`filter`

`string`

The standard list filter.

`pageSize`

`integer`

The standard list page size.

`pageToken`

`string`

The standard list page token.

`returnPartialSuccess`

`boolean`

When set to \`true\`, reachable operations are returned normally and unreachable ones are listed in the \`ListOperationsResponse.unreachable\` field.

This is only supported for cross-collection reads. For example, when `parent` is set to `"projects/example/locations/-"` .

By default, this field isn't supported and might result in an \`UNIMPLEMENTED\` error if not explicitly supported by the service.
