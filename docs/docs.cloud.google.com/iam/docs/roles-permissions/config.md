---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/config
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/config
title: Infrastructure Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Infrastructure Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Infrastructure Manager roles

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
<td><h4 id="config.admin" class="role-title add-link" data-text="Cloud Infrastructure Manager Admin" tabindex="-1">Cloud Infrastructure Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p>Full access to Cloud Infrastructure Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.artifacts.import</code></li>
<li><code dir="ltr" translate="no">config.automigrationconfig.get</code></li>
<li><code dir="ltr" translate="no">config.  automigrationconfig.  update</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  get</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></li>
<li><code dir="ltr" translate="no">config.deploymentgroups.create</code></li>
<li><code dir="ltr" translate="no">config.deploymentgroups.delete</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgroups.  deprovision</code></li>
<li><code dir="ltr" translate="no">config.deploymentgroups.get</code></li>
<li><code dir="ltr" translate="no">config.deploymentgroups.list</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgroups.  provision</code></li>
<li><code dir="ltr" translate="no">config.deploymentgroups.update</code></li>
<li><code dir="ltr" translate="no">config.deployments.create</code></li>
<li><code dir="ltr" translate="no">config.deployments.delete</code></li>
<li><code dir="ltr" translate="no">config.deployments.deleteState</code></li>
<li><code dir="ltr" translate="no">config.deployments.get</code></li>
<li><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">config.deployments.getLock</code></li>
<li><code dir="ltr" translate="no">config.deployments.getState</code></li>
<li><code dir="ltr" translate="no">config.deployments.list</code></li>
<li><code dir="ltr" translate="no">config.deployments.lock</code></li>
<li><code dir="ltr" translate="no">config.  deployments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">config.deployments.unlock</code></li>
<li><code dir="ltr" translate="no">config.deployments.update</code></li>
<li><code dir="ltr" translate="no">config.deployments.updateState</code></li>
<li><code dir="ltr" translate="no">config.locations.get</code></li>
<li><code dir="ltr" translate="no">config.locations.list</code></li>
<li><code dir="ltr" translate="no">config.operations.cancel</code></li>
<li><code dir="ltr" translate="no">config.operations.delete</code></li>
<li><code dir="ltr" translate="no">config.operations.get</code></li>
<li><code dir="ltr" translate="no">config.operations.list</code></li>
<li><code dir="ltr" translate="no">config.previews.create</code></li>
<li><code dir="ltr" translate="no">config.previews.delete</code></li>
<li><code dir="ltr" translate="no">config.previews.export</code></li>
<li><code dir="ltr" translate="no">config.previews.get</code></li>
<li><code dir="ltr" translate="no">config.previews.list</code></li>
<li><code dir="ltr" translate="no">config.previews.upload</code></li>
<li><code dir="ltr" translate="no">config.resourcechanges.get</code></li>
<li><code dir="ltr" translate="no">config.resourcechanges.list</code></li>
<li><code dir="ltr" translate="no">config.resourcedrifts.get</code></li>
<li><code dir="ltr" translate="no">config.resourcedrifts.list</code></li>
<li><code dir="ltr" translate="no">config.resources.get</code></li>
<li><code dir="ltr" translate="no">config.resources.list</code></li>
<li><code dir="ltr" translate="no">config.revisions.get</code></li>
<li><code dir="ltr" translate="no">config.revisions.getState</code></li>
<li><code dir="ltr" translate="no">config.revisions.list</code></li>
<li><code dir="ltr" translate="no">config.terraformversions.get</code></li>
<li><code dir="ltr" translate="no">config.terraformversions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="config.editor" class="role-title add-link" data-text="Cloud Infrastructure Manager Editor" tabindex="-1">Cloud Infrastructure Manager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Edit access to Cloud Infrastructure Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">config.artifacts.import</code></p>
<p><code dir="ltr" translate="no">config.automigrationconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.automigrationconfig.get</code></li>
<li><code dir="ltr" translate="no">config.  automigrationconfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">config.  deploymentgrouprevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  get</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.deploymentgroups.create</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.delete</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.get</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.list</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.update</code></p>
<p><code dir="ltr" translate="no">config.deployments.create</code></p>
<p><code dir="ltr" translate="no">config.deployments.delete</code></p>
<p><code dir="ltr" translate="no">config.deployments.get</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.deployments.update</code></p>
<p><code dir="ltr" translate="no">config.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.locations.get</code></li>
<li><code dir="ltr" translate="no">config.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.operations.cancel</code></li>
<li><code dir="ltr" translate="no">config.operations.delete</code></li>
<li><code dir="ltr" translate="no">config.operations.get</code></li>
<li><code dir="ltr" translate="no">config.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.previews.create</code></p>
<p><code dir="ltr" translate="no">config.previews.delete</code></p>
<p><code dir="ltr" translate="no">config.previews.get</code></p>
<p><code dir="ltr" translate="no">config.previews.list</code></p>
<p><code dir="ltr" translate="no">config.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.resources.get</code></li>
<li><code dir="ltr" translate="no">config.resources.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.revisions.get</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">config.terraformversions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.terraformversions.get</code></li>
<li><code dir="ltr" translate="no">config.terraformversions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="config.viewer" class="role-title add-link" data-text="Cloud Infrastructure Manager Viewer" tabindex="-1">Cloud Infrastructure Manager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p>Read-only access to Cloud Infrastructure Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">config.automigrationconfig.get</code></p>
<p><code dir="ltr" translate="no">config.  deploymentgrouprevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  get</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.deploymentgroups.get</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.list</code></p>
<p><code dir="ltr" translate="no">config.deployments.get</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.locations.get</code></li>
<li><code dir="ltr" translate="no">config.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.operations.get</code></p>
<p><code dir="ltr" translate="no">config.operations.list</code></p>
<p><code dir="ltr" translate="no">config.previews.get</code></p>
<p><code dir="ltr" translate="no">config.previews.list</code></p>
<p><code dir="ltr" translate="no">config.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.resources.get</code></li>
<li><code dir="ltr" translate="no">config.resources.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.revisions.get</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">config.terraformversions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.terraformversions.get</code></li>
<li><code dir="ltr" translate="no">config.terraformversions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="config.agent" class="role-title add-link" data-text="Cloud Infrastructure Manager Agent" tabindex="-1">Cloud Infrastructure Manager Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Required permissions to make Cloud Infrastructure Manager work with the user-specified service account.</p></td>
<td><p><code dir="ltr" translate="no">cloudbuild.connections.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.  repositories.  accessReadToken</code></p>
<p><code dir="ltr" translate="no">cloudbuild.repositories.list</code></p>
<p><code dir="ltr" translate="no">cloudquotas.quotas.get</code></p>
<p><code dir="ltr" translate="no">config.artifacts.import</code></p>
<p><code dir="ltr" translate="no">config.deployments.deleteState</code></p>
<p><code dir="ltr" translate="no">config.deployments.getLock</code></p>
<p><code dir="ltr" translate="no">config.deployments.getState</code></p>
<p><code dir="ltr" translate="no">config.deployments.updateState</code></p>
<p><code dir="ltr" translate="no">config.previews.upload</code></p>
<p><code dir="ltr" translate="no">config.revisions.getState</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Infrastructure Manager permissions

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
<td><h4 id="config.artifacts.import" class="permission-name add-link" data-text="config.artifacts.import" tabindex="-1"><code dir="ltr" translate="no">config.artifacts.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.automigrationconfig.get" class="permission-name add-link" data-text="config.automigrationconfig.get" tabindex="-1"><code dir="ltr" translate="no">config.automigrationconfig.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="config.automigrationconfig.update" class="permission-name add-link" data-text="config.automigrationconfig.update" tabindex="-1"><code dir="ltr" translate="no">config.  automigrationconfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="config.deploymentgrouprevisions.get" class="permission-name add-link" data-text="config.deploymentgrouprevisions.get" tabindex="-1"><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deploymentgrouprevisions.list" class="permission-name add-link" data-text="config.deploymentgrouprevisions.list" tabindex="-1"><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deploymentgroups.create" class="permission-name add-link" data-text="config.deploymentgroups.create" tabindex="-1"><code dir="ltr" translate="no">config.deploymentgroups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deploymentgroups.delete" class="permission-name add-link" data-text="config.deploymentgroups.delete" tabindex="-1"><code dir="ltr" translate="no">config.deploymentgroups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deploymentgroups.deprovision" class="permission-name add-link" data-text="config.deploymentgroups.deprovision" tabindex="-1"><code dir="ltr" translate="no">config.  deploymentgroups.  deprovision</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deploymentgroups.get" class="permission-name add-link" data-text="config.deploymentgroups.get" tabindex="-1"><code dir="ltr" translate="no">config.deploymentgroups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deploymentgroups.list" class="permission-name add-link" data-text="config.deploymentgroups.list" tabindex="-1"><code dir="ltr" translate="no">config.deploymentgroups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deploymentgroups.provision" class="permission-name add-link" data-text="config.deploymentgroups.provision" tabindex="-1"><code dir="ltr" translate="no">config.  deploymentgroups.  provision</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deploymentgroups.update" class="permission-name add-link" data-text="config.deploymentgroups.update" tabindex="-1"><code dir="ltr" translate="no">config.deploymentgroups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.create" class="permission-name add-link" data-text="config.deployments.create" tabindex="-1"><code dir="ltr" translate="no">config.deployments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.delete" class="permission-name add-link" data-text="config.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">config.deployments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.deleteState" class="permission-name add-link" data-text="config.deployments.deleteState" tabindex="-1"><code dir="ltr" translate="no">config.deployments.deleteState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.get" class="permission-name add-link" data-text="config.deployments.get" tabindex="-1"><code dir="ltr" translate="no">config.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.getIamPolicy" class="permission-name add-link" data-text="config.deployments.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.getLock" class="permission-name add-link" data-text="config.deployments.getLock" tabindex="-1"><code dir="ltr" translate="no">config.deployments.getLock</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.getState" class="permission-name add-link" data-text="config.deployments.getState" tabindex="-1"><code dir="ltr" translate="no">config.deployments.getState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.list" class="permission-name add-link" data-text="config.deployments.list" tabindex="-1"><code dir="ltr" translate="no">config.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.lock" class="permission-name add-link" data-text="config.deployments.lock" tabindex="-1"><code dir="ltr" translate="no">config.deployments.lock</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.setIamPolicy" class="permission-name add-link" data-text="config.deployments.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">config.  deployments.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.unlock" class="permission-name add-link" data-text="config.deployments.unlock" tabindex="-1"><code dir="ltr" translate="no">config.deployments.unlock</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.deployments.update" class="permission-name add-link" data-text="config.deployments.update" tabindex="-1"><code dir="ltr" translate="no">config.deployments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.deployments.updateState" class="permission-name add-link" data-text="config.deployments.updateState" tabindex="-1"><code dir="ltr" translate="no">config.deployments.updateState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.locations.get" class="permission-name add-link" data-text="config.locations.get" tabindex="-1"><code dir="ltr" translate="no">config.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.locations.list" class="permission-name add-link" data-text="config.locations.list" tabindex="-1"><code dir="ltr" translate="no">config.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.operations.cancel" class="permission-name add-link" data-text="config.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">config.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.operations.delete" class="permission-name add-link" data-text="config.operations.delete" tabindex="-1"><code dir="ltr" translate="no">config.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.operations.get" class="permission-name add-link" data-text="config.operations.get" tabindex="-1"><code dir="ltr" translate="no">config.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.operations.list" class="permission-name add-link" data-text="config.operations.list" tabindex="-1"><code dir="ltr" translate="no">config.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.previews.create" class="permission-name add-link" data-text="config.previews.create" tabindex="-1"><code dir="ltr" translate="no">config.previews.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.previews.delete" class="permission-name add-link" data-text="config.previews.delete" tabindex="-1"><code dir="ltr" translate="no">config.previews.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.previews.export" class="permission-name add-link" data-text="config.previews.export" tabindex="-1"><code dir="ltr" translate="no">config.previews.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.previews.get" class="permission-name add-link" data-text="config.previews.get" tabindex="-1"><code dir="ltr" translate="no">config.previews.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.previews.list" class="permission-name add-link" data-text="config.previews.list" tabindex="-1"><code dir="ltr" translate="no">config.previews.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.previews.upload" class="permission-name add-link" data-text="config.previews.upload" tabindex="-1"><code dir="ltr" translate="no">config.previews.upload</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.resourcechanges.get" class="permission-name add-link" data-text="config.resourcechanges.get" tabindex="-1"><code dir="ltr" translate="no">config.resourcechanges.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="config.resourcechanges.list" class="permission-name add-link" data-text="config.resourcechanges.list" tabindex="-1"><code dir="ltr" translate="no">config.resourcechanges.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="config.resourcedrifts.get" class="permission-name add-link" data-text="config.resourcedrifts.get" tabindex="-1"><code dir="ltr" translate="no">config.resourcedrifts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="config.resourcedrifts.list" class="permission-name add-link" data-text="config.resourcedrifts.list" tabindex="-1"><code dir="ltr" translate="no">config.resourcedrifts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="config.resources.get" class="permission-name add-link" data-text="config.resources.get" tabindex="-1"><code dir="ltr" translate="no">config.resources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.resources.list" class="permission-name add-link" data-text="config.resources.list" tabindex="-1"><code dir="ltr" translate="no">config.resources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.revisions.get" class="permission-name add-link" data-text="config.revisions.get" tabindex="-1"><code dir="ltr" translate="no">config.revisions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.revisions.getState" class="permission-name add-link" data-text="config.revisions.getState" tabindex="-1"><code dir="ltr" translate="no">config.revisions.getState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.revisions.list" class="permission-name add-link" data-text="config.revisions.list" tabindex="-1"><code dir="ltr" translate="no">config.revisions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="config.terraformversions.get" class="permission-name add-link" data-text="config.terraformversions.get" tabindex="-1"><code dir="ltr" translate="no">config.terraformversions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="config.terraformversions.list" class="permission-name add-link" data-text="config.terraformversions.list" tabindex="-1"><code dir="ltr" translate="no">config.terraformversions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
