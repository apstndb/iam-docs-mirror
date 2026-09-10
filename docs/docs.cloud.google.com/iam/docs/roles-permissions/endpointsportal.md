---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/endpointsportal
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/endpointsportal
title: Cloud Endpoints Portal roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Endpoints Portal. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Endpoints Portal roles

Cloud Endpoints Portal offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="endpointsportal.serviceAgent" class="role-title add-link" data-text="Endpoints Portal Service Agent" tabindex="-1">Endpoints Portal Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  endpointsportal.serviceAgent</code> )</p>
<p>Can access information about Endpoints services for consumer portal management, and can read Source Repositories for consumer portal custom content.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  list</code></p>
<p><code dir="ltr" translate="no">source.repos.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Endpoints Portal permissions

There are no IAM permissions for this service.
