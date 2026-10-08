---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/fpnv
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv
title: Firebase Phone Number Verification roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Phone Number Verification. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Phone Number Verification roles

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Role</th>
<th>Permissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Firebase Phone Number Verification Admin <sup>Beta</sup>
<p>( <code>roles/ fpnv.admin</code> )</p>
<p>Full access to FPNV resources.</p></td>
<td><p><code>fpnv.*</code></p>
<ul>
<li><code>fpnv. phoneNumberTokens. fetchDigitalCredentialPayload</code></li>
<li><code>fpnv. phoneNumberTokens. generateTestNumberToken</code></li>
<li><code>fpnv. phoneNumberTokens. mintPhoneNumberToken</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Firebase Phone Number Verification permissions

| Permission                                               | Included in roles                                                                                                                                                                                                                                                                                                            |
|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `fpnv. phoneNumberTokens. fetchDigitalCredentialPayload` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Firebase Phone Number Verification Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin) ( `roles/ fpnv.admin` ) |
| `fpnv. phoneNumberTokens. generateTestNumberToken`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Firebase Phone Number Verification Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin) ( `roles/ fpnv.admin` ) |
| `fpnv. phoneNumberTokens. mintPhoneNumberToken`          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Firebase Phone Number Verification Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin) ( `roles/ fpnv.admin` ) |
