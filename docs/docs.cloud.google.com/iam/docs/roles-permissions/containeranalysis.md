---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis
title: Artifact Analysis roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Artifact Analysis. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Artifact Analysis roles

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
<td><h4 id="containeranalysis.admin" class="role-title add-link" data-text="Container Analysis Admin" tabindex="-1">Container Analysis Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p>Access to all Container Analysis resources.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.update</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.editor" class="role-title add-link" data-text="Container Analysis Editor" tabindex="-1">Container Analysis Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p>Editor role for Container Analysis</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  listOccurrences</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.update</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.viewer" class="role-title add-link" data-text="Container Analysis Viewer" tabindex="-1">Container Analysis Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p>Viewer role for Container Analysis</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.attacher" class="role-title add-link" data-text="Container Analysis Notes Attacher" tabindex="-1">Container Analysis Notes Attacher</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.notes.attacher</code> )</p>
<p>Can attach Container Analysis Occurrences to Notes.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.editor" class="role-title add-link" data-text="Container Analysis Notes Editor" tabindex="-1">Container Analysis Notes Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p>Can edit Container Analysis Notes.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.occurrences.viewer" class="role-title add-link" data-text="Container Analysis Occurrences for Notes Viewer" tabindex="-1">Container Analysis Occurrences for Notes Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.notes.occurrences.viewer</code> )</p>
<p>Can view all Container Analysis Occurrences attached to a Note.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  listOccurrences</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.viewer" class="role-title add-link" data-text="Container Analysis Notes Viewer" tabindex="-1">Container Analysis Notes Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.notes.viewer</code> )</p>
<p>Can view Container Analysis Notes.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.occurrences.editor" class="role-title add-link" data-text="Container Analysis Occurrences Editor" tabindex="-1">Container Analysis Occurrences Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p>Can edit Container Analysis Occurrences.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.occurrences.viewer" class="role-title add-link" data-text="Container Analysis Occurrences Viewer" tabindex="-1">Container Analysis Occurrences Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.occurrences.viewer</code> )</p>
<p>Can view Container Analysis Occurrences.</p></td>
<td><p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="containeranalysis.ServiceAgent" class="role-title add-link" data-text="Container Analysis Service Agent" tabindex="-1">Container Analysis Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</p>
<p>Gives Container Analysis API the access it needs to function</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.attach</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.commit</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.create</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.rollback</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.create</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.update</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Artifact Analysis permissions

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
<td><h4 id="containeranalysis.notes.attachOccurrence" class="permission-name add-link" data-text="containeranalysis.notes.attachOccurrence" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  notes.  attachOccurrence</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.attacher">Container Analysis Notes Attacher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.attacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.create" class="permission-name add-link" data-text="containeranalysis.notes.create" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.notes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.delete" class="permission-name add-link" data-text="containeranalysis.notes.delete" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.notes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.get" class="permission-name add-link" data-text="containeranalysis.notes.get" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.notes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.attacher">Container Analysis Notes Attacher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.attacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.occurrences.viewer">Container Analysis Occurrences for Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.getIamPolicy" class="permission-name add-link" data-text="containeranalysis.notes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.list" class="permission-name add-link" data-text="containeranalysis.notes.list" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.notes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.listOccurrences" class="permission-name add-link" data-text="containeranalysis.notes.listOccurrences" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  notes.  listOccurrences</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.occurrences.viewer">Container Analysis Occurrences for Notes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.occurrences.viewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.notes.setIamPolicy" class="permission-name add-link" data-text="containeranalysis.notes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  notes.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.notes.update" class="permission-name add-link" data-text="containeranalysis.notes.update" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.notes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.notes.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.occurrences.create" class="permission-name add-link" data-text="containeranalysis.occurrences.create" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.occurrences.delete" class="permission-name add-link" data-text="containeranalysis.occurrences.delete" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.occurrences.get" class="permission-name add-link" data-text="containeranalysis.occurrences.get" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAgent">Developer Connect Insights Config Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.occurrences.getIamPolicy" class="permission-name add-link" data-text="containeranalysis.occurrences.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.occurrences.list" class="permission-name add-link" data-text="containeranalysis.occurrences.list" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAgent">Developer Connect Insights Config Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="containeranalysis.occurrences.setIamPolicy" class="permission-name add-link" data-text="containeranalysis.occurrences.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="containeranalysis.occurrences.update" class="permission-name add-link" data-text="containeranalysis.occurrences.update" tabindex="-1"><code dir="ltr" translate="no">containeranalysis.  occurrences.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.occurrences.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
