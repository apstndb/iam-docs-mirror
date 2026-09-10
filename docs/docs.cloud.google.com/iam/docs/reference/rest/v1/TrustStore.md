---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore
title: TrustStore
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#SCHEMA_REPRESENTATION)
  - [TrustAnchor](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#TrustAnchor)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#TrustAnchor.SCHEMA_REPRESENTATION)
  - [IntermediateCA](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#IntermediateCA)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore#IntermediateCA.SCHEMA_REPRESENTATION)

Trust store that contains trust anchors and optional intermediate CAs used in PKI to build a trust chain(trust hierarchy) and verify a client's identity.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;trustAnchors&quot;: [{object (TrustAnchor)}],&quot;intermediateCas&quot;: [{object (IntermediateCA)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`trustAnchors[]`

` object ( TrustAnchor  ` )

Required. List of trust anchors to be used while performing validation against a given TrustStore. The incoming end entity's certificate must be in the trust chain of one of the trust anchors here.

`intermediateCas[]`

` object ( IntermediateCA  ` )

Optional. Set of intermediate CA certificates used for building the trust chain to the trust anchor. Important: Intermediate CAs are only supported for X.509 federation.

## TrustAnchor

Represents a root of trust.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field kind can be only one of the following:&quot;pemCertificate&quot;: string// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `kind` .

`kind` can be only one of the following:

`pemCertificate`

`string`

PEM certificate of the PKI used for validation. Must only contain one ca certificate (either root or intermediate cert).

## IntermediateCA

Intermediate CA certificates used for building the trust chain to trust anchor

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field kind can be only one of the following:&quot;pemCertificate&quot;: string// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `kind` .

`kind` can be only one of the following:

`pemCertificate`

`string`

PEM certificate of the PKI used for validation. Must only contain one ca certificate.
