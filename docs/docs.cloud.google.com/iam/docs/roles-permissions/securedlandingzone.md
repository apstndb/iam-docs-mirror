---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone
title: Secured Landing Zone roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Secured Landing Zone. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Secured Landing Zone roles

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
<td><h4 id="securedlandingzone.bqdwOrgRemediator" class="role-title add-link" data-text="SLZ BQDW Blueprint Organization Level Remediator Beta" tabindex="-1">SLZ BQDW Blueprint Organization Level Remediator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Access to modify (remediate) resources in SLZ BQDW Blueprint at Organization.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.bqdwProjectRemediator" class="role-title add-link" data-text="SLZ BQDW Blueprint Project Level Remediator Beta" tabindex="-1">SLZ BQDW Blueprint Project Level Remediator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Access to modify (remediate) resources in SLZ BQDW Blueprint at Project.</p></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.update</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.update</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  update</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securedlandingzone.overwatchActivator" class="role-title add-link" data-text="Overwatch Activator Beta" tabindex="-1">Overwatch Activator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.overwatchActivator</code> )</p>
<p>This role can activate or suspend Overwatches</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  activate</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  suspend</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.overwatchAdmin" class="role-title add-link" data-text="Overwatch Admin Beta" tabindex="-1">Overwatch Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p>Full access to Overwatches</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securedlandingzone.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  activate</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  create</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  delete</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  get</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  list</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  suspend</code></li>
<li><code dir="ltr" translate="no">securedlandingzone.  overwatches.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securedlandingzone.overwatchViewer" class="role-title add-link" data-text="Overwatch Viewer Beta" tabindex="-1">Overwatch Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p>
<p>This role can view all properties of Overwatches</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  operations.  get</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  get</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  list</code></p></td>
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
<td><h4 id="securedlandingzone.serviceAgent" class="role-title add-link" data-text="Secured Landing Zone Service Agent" tabindex="-1">Secured Landing Zone Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</p>
<p>Grants Secured Landing Zone service account permissions to manage resources in the customer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.delete</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.update</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.update</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.update</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Secured Landing Zone permissions

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
<td><h4 id="securedlandingzone.operations.get" class="permission-name add-link" data-text="securedlandingzone.operations.get" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.overwatches.activate" class="permission-name add-link" data-text="securedlandingzone.overwatches.activate" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  activate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securedlandingzone.overwatches.create" class="permission-name add-link" data-text="securedlandingzone.overwatches.create" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.overwatches.delete" class="permission-name add-link" data-text="securedlandingzone.overwatches.delete" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securedlandingzone.overwatches.get" class="permission-name add-link" data-text="securedlandingzone.overwatches.get" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.overwatches.list" class="permission-name add-link" data-text="securedlandingzone.overwatches.list" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securedlandingzone.overwatches.suspend" class="permission-name add-link" data-text="securedlandingzone.overwatches.suspend" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  suspend</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securedlandingzone.overwatches.update" class="permission-name add-link" data-text="securedlandingzone.overwatches.update" tabindex="-1"><code dir="ltr" translate="no">securedlandingzone.  overwatches.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.overwatchAdmin</code> )</p></td>
</tr>
</tbody>
</table>
