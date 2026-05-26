---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/endpoints
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints
title: Cloud Endpoints roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Endpoints. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Endpoints roles

Cloud Endpoints offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="endpoints.serviceAgent" class="role-title add-link" data-text="Cloud Endpoints Service Agent" tabindex="-1">Cloud Endpoints Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  endpoints.serviceAgent</code> )</p>
<p>Gives the Cloud Endpoints service account access to Endpoints services and the ability to act as a service controller.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">servicemanagement.  services.  check</code></p>
<p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  quota</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p></td>
</tr>
</tbody>
</table>

## Cloud Endpoints permissions

There are no IAM permissions for this service.
