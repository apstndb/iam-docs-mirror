---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData
title: KeyData
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData#SCHEMA_REPRESENTATION)
  - [KeyFormat](https://docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData#KeyFormat)
  - [KeySpec](https://docs.cloud.google.com/iam/docs/reference/rest/v1/KeyData#KeySpec)

Represents a public key data along with its format.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;format&quot;: enum (KeyFormat),&quot;notBeforeTime&quot;: string,&quot;notAfterTime&quot;: string,&quot;key&quot;: string,&quot;keySpec&quot;: enum (KeySpec)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`format`

` enum ( KeyFormat  ` )

Output only. The format of the key.

`notBeforeTime`

` string ( Timestamp  ` format)

Output only. Earliest timestamp when this key is valid. Attempts to use this key before this time will fail. Only present if the key data represents a X.509 certificate.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`notAfterTime`

` string ( Timestamp  ` format)

Output only. Latest timestamp when this key is valid. Attempts to use this key after this time will fail. Only present if the key data represents a X.509 certificate.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`key`

`string`

Output only. The key data. The format of the key is represented by the `  format  ` field.

`keySpec`

` enum ( KeySpec  ` )

Required. The specifications for the key.

## KeyFormat

The supported formats for the public key.

Enums

`KEY_FORMAT_UNSPECIFIED`

No format has been specified. This is an invalid format and must not be used.

`RSA_X509_PEM`

A RSA public key wrapped in an X.509v3 certificate ( [RFC5280](https://www.ietf.org/rfc/rfc5280.txt) ), encoded in base64, and wrapped in [public certificate label](https://datatracker.ietf.org/doc/html/rfc7468#section-5.1) .

## KeySpec

Allowed list of specifications for the key.

Enums

`KEY_SPEC_UNSPECIFIED`

No key specification specified.

`RSA_2048`

A 2048 bit RSA key.

`RSA_3072`

A 3072 bit RSA key.

`RSA_4096`

A 4096 bit RSA key.
