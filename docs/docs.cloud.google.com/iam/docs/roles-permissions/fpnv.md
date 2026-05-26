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
<td><h4 id="fpnv.admin" class="role-title add-link" data-text="Firebase Phone Number Verification Admin Beta" tabindex="-1">Firebase Phone Number Verification Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  fpnv.admin</code> )</p>
<p>Full access to FPNV resources.</p></td>
<td><p><code dir="ltr" translate="no">fpnv.*</code></p>
<ul>
<li><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  fetchDigitalCredentialPayload</code></li>
<li><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  generateTestNumberToken</code></li>
<li><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  mintPhoneNumberToken</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Firebase Phone Number Verification permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="fpnv.phoneNumberTokens.fetchDigitalCredentialPayload" class="permission-name add-link" data-text="fpnv.phoneNumberTokens.fetchDigitalCredentialPayload" tabindex="-1"><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  fetchDigitalCredentialPayload</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin">Firebase Phone Number Verification Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fpnv.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="fpnv.phoneNumberTokens.generateTestNumberToken" class="permission-name add-link" data-text="fpnv.phoneNumberTokens.generateTestNumberToken" tabindex="-1"><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  generateTestNumberToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin">Firebase Phone Number Verification Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fpnv.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="fpnv.phoneNumberTokens.mintPhoneNumberToken" class="permission-name add-link" data-text="fpnv.phoneNumberTokens.mintPhoneNumberToken" tabindex="-1"><code dir="ltr" translate="no">fpnv.  phoneNumberTokens.  mintPhoneNumberToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fpnv#fpnv.admin">Firebase Phone Number Verification Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fpnv.admin</code> )</p></td>
</tr>
</tbody>
</table>
