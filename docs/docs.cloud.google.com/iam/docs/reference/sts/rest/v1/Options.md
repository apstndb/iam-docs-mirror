---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Options
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Options
title: Options
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Options#SCHEMA_REPRESENTATION)

An `Options` object configures features that the Security Token Service supports, but that are not supported by standard OAuth 2.0 token exchange endpoints, as defined in <https://tools.ietf.org/html/rfc8693> .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessBoundary&quot;: {object (AccessBoundary)},&quot;userProject&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessBoundary`

` object ( AccessBoundary  ` )

An access boundary that defines the upper bound of permissions the credential may have.

The value should be a JSON object of `  AccessBoundary  ` .

The access boundary can include up to 10 rules. The size of the parameter value should not exceed 2048 characters.

`userProject`

`string`

A Google project used for quota and billing purposes when the credential is used to access Google APIs. The provided project overrides the project bound to the credential. The value must be a project number or a project ID. Example: `my-sample-project-191923` .

The maximum length is 32 characters.
