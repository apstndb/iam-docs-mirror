---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/translationhub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub
title: Translation Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Translation Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Translation Hub roles

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
<td><h4 id="translationhub.admin" class="role-title add-link" data-text="Translation Hub Admin Beta" tabindex="-1">Translation Hub Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p>Admin of Translation Hub</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  create</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  delete</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">translationhub.*</code></p>
<ul>
<li><code dir="ltr" translate="no">translationhub.portals.create</code></li>
<li><code dir="ltr" translate="no">translationhub.portals.delete</code></li>
<li><code dir="ltr" translate="no">translationhub.portals.get</code></li>
<li><code dir="ltr" translate="no">translationhub.portals.list</code></li>
<li><code dir="ltr" translate="no">translationhub.portals.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="translationhub.viewer" class="role-title add-link" data-text="Translation Hub Viewer Beta" tabindex="-1">Translation Hub Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  translationhub.viewer</code> )</p>
<p>Viewer role for Translation Hub</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.get</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="translationhub.portalUser" class="role-title add-link" data-text="Translation Hub Portal User Beta" tabindex="-1">Translation Hub Portal User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p>
<p>Portal user of Translation Hub</p></td>
<td><p><code dir="ltr" translate="no">automl.models.get</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.models.predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  predict</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.get</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaries.  predict</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.get</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.list</code></p></td>
</tr>
</tbody>
</table>

## Translation Hub permissions

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
<td><h4 id="translationhub.portals.create" class="permission-name add-link" data-text="translationhub.portals.create" tabindex="-1"><code dir="ltr" translate="no">translationhub.portals.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="translationhub.portals.delete" class="permission-name add-link" data-text="translationhub.portals.delete" tabindex="-1"><code dir="ltr" translate="no">translationhub.portals.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="translationhub.portals.get" class="permission-name add-link" data-text="translationhub.portals.get" tabindex="-1"><code dir="ltr" translate="no">translationhub.portals.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="translationhub.portals.list" class="permission-name add-link" data-text="translationhub.portals.list" tabindex="-1"><code dir="ltr" translate="no">translationhub.portals.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.portalUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="translationhub.portals.update" class="permission-name add-link" data-text="translationhub.portals.update" tabindex="-1"><code dir="ltr" translate="no">translationhub.portals.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  translationhub.admin</code> )</p></td>
</tr>
</tbody>
</table>
