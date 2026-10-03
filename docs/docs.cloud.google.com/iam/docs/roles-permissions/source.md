---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/source
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/source
title: Cloud Source Repositories roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Source Repositories. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Source Repositories roles

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
<td>Source Repository Administrator
<p>( <code>roles/ source.admin</code> )</p>
<p>Provides permissions to create, update, delete, list, clone, fetch, and browse repositories. Also provides permissions to read and change IAM policies.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Repository</li>
</ul></td>
<td><p><code>source.*</code></p>
<ul>
<li><code>source.repos.create</code></li>
<li><code>source.repos.delete</code></li>
<li><code>source.repos.get</code></li>
<li><code>source.repos.getIamPolicy</code></li>
<li><code>source.repos.getProjectConfig</code></li>
<li><code>source.repos.list</code></li>
<li><code>source.repos.setIamPolicy</code></li>
<li><code>source.repos.update</code></li>
<li><code>source. repos. updateProjectConfig</code></li>
<li><code>source.repos.updateRepoConfig</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Source Editor
<p>( <code>roles/ source.editor</code> )</p>
<p>Editor role for source</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>source.repos.get</code></p>
<p><code>source.repos.getIamPolicy</code></p>
<p><code>source.repos.list</code></p>
<p><code>source.repos.update</code></p></td>
</tr>
<tr class="odd">
<td>Source Viewer
<p>( <code>roles/ source.viewer</code> )</p>
<p>Viewer role for source</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>source.repos.get</code></p>
<p><code>source.repos.getIamPolicy</code></p>
<p><code>source.repos.list</code></p></td>
</tr>
<tr class="even">
<td>Source Repository Reader
<p>( <code>roles/ source.reader</code> )</p>
<p>Provides permissions to list, clone, fetch, and browse repositories.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Repository</li>
</ul></td>
<td><p><code>source.repos.get</code></p>
<p><code>source.repos.list</code></p></td>
</tr>
<tr class="odd">
<td>Source Repository Writer
<p>( <code>roles/ source.writer</code> )</p>
<p>Provides permissions to list, clone, fetch, browse, and update repositories.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Repository</li>
</ul></td>
<td><p><code>source.repos.get</code></p>
<p><code>source.repos.list</code></p>
<p><code>source.repos.update</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Cloud Source Repositories Service Agent
<p>( <code>roles/ sourcerepo.serviceAgent</code> )</p>
<p>Allow Cloud Source Repositories to integrate with other Cloud services.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>pubsub.topics.publish</code></p></td>
</tr>
</tbody>
</table>

## Cloud Source Repositories permissions

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
<td><code>source.repos.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>source.repos.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><code>source.repos.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code>roles/ run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code>roles/ source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.reader">Source Repository Reader</a> ( <code>roles/ source.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.writer">Source Repository Writer</a> ( <code>roles/ source.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpointsportal#endpointsportal.serviceAgent">Endpoints Portal Service Agent</a> ( <code>roles/ endpointsportal.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>source.repos.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code>roles/ source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>source.repos.getProjectConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>source.repos.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code>roles/ source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.reader">Source Repository Reader</a> ( <code>roles/ source.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.writer">Source Repository Writer</a> ( <code>roles/ source.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>source.repos.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>source.repos.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.writer">Source Repository Writer</a> ( <code>roles/ source.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>source. repos. updateProjectConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>source.repos.updateRepoConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.admin">Source Repository Administrator</a> ( <code>roles/ source.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
</tbody>
</table>
