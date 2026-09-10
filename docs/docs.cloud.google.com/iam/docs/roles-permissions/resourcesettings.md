---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings
title: Resource Settings roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Resource Settings. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Resource Settings roles

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
<td><h4 id="resourcesettings.admin" class="role-title add-link" data-text="Resource Settings Administrator" tabindex="-1">Resource Settings Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcesettings.admin</code> )</p>
<p>Provides admin capabilities to set Resource Setting Values on resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcesettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcesettings.settings.get</code></li>
<li><code dir="ltr" translate="no">resourcesettings.settings.list</code></li>
<li><code dir="ltr" translate="no">resourcesettings.  settings.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="resourcesettings.viewer" class="role-title add-link" data-text="Resource Settings Viewer" tabindex="-1">Resource Settings Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  resourcesettings.viewer</code> )</p>
<p>Provides capabilities to view Resource Settings and Resource Setting Values on resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcesettings.settings.get</code></p>
<p><code dir="ltr" translate="no">resourcesettings.settings.list</code></p></td>
</tr>
</tbody>
</table>

## Resource Settings permissions

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
<td><h4 id="resourcesettings.settings.get" class="permission-name add-link" data-text="resourcesettings.settings.get" tabindex="-1"><code dir="ltr" translate="no">resourcesettings.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin">Resource Settings Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcesettings.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.viewer">Resource Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcesettings.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="resourcesettings.settings.list" class="permission-name add-link" data-text="resourcesettings.settings.list" tabindex="-1"><code dir="ltr" translate="no">resourcesettings.settings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin">Resource Settings Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcesettings.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.viewer">Resource Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcesettings.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="resourcesettings.settings.update" class="permission-name add-link" data-text="resourcesettings.settings.update" tabindex="-1"><code dir="ltr" translate="no">resourcesettings.  settings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin">Resource Settings Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcesettings.admin</code> )</p></td>
</tr>
</tbody>
</table>
