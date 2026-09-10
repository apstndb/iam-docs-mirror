---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/ciem
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/ciem
title: Cloud Infrastructure Entitlement Management (CIEM) roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Infrastructure Entitlement Management (CIEM). To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Infrastructure Entitlement Management (CIEM) roles

Cloud Infrastructure Entitlement Management (CIEM) offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="ciem.serviceAgent" class="role-title add-link" data-text="CIEM Service Agent" tabindex="-1">CIEM Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  ciem.serviceAgent</code> )</p>
<p>Gives CIEM Service Account permission to access GCP resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Infrastructure Entitlement Management (CIEM) permissions

There are no IAM permissions for this service.
