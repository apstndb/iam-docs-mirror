---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/saasconfig
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig
title: SaaS Config API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for SaaS Config API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## SaaS Config API roles

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
<td><h4 id="saasconfig.viewer" class="role-title add-link" data-text="SaaS Config Viewer Beta" tabindex="-1">SaaS Config Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  saasconfig.viewer</code> )</p>
<p>Read access to SaaS Config resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">saasconfig.  featureFlagsConfigs.  get</code></p></td>
</tr>
</tbody>
</table>

## SaaS Config API permissions

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
<td><h4 id="saasconfig.featureFlagsConfigs.get" class="permission-name add-link" data-text="saasconfig.featureFlagsConfigs.get" tabindex="-1"><code dir="ltr" translate="no">saasconfig.  featureFlagsConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer">SaaS Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
