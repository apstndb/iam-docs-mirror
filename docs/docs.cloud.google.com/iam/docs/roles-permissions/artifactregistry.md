---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry
title: Artifact Registry roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Artifact Registry. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Artifact Registry roles

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
<td><h4 id="artifactregistry.admin" class="role-title add-link" data-text="Artifact Registry Administrator" tabindex="-1">Artifact Registry Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p>Administrator access to create and manage repositories.</p>
<blockquote>
<strong>Warning:</strong> Granting the <code dir="ltr" translate="no">artifactregistry.repositories.create</code> permission to end users through the <code dir="ltr" translate="no">roles/artifactregistry.admin</code> role is highly privileged. Do not grant this role to lower-trust users.
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.packages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.editor" class="role-title add-link" data-text="Artifactregistry Editor" tabindex="-1">Artifactregistry Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p>Editor role for Artifact Registry</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.packages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createOnPush</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repoAdmin" class="role-title add-link" data-text="Artifact Registry Repository Administrator" tabindex="-1">Artifact Registry Repository Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p>Access to manage artifacts in repositories.</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.packages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.viewer" class="role-title add-link" data-text="Artifactregistry Viewer" tabindex="-1">Artifactregistry Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p>Viewer role for Artifact Registry</p></td>
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
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.attachmentReader" class="role-title add-link" data-text="Artifact Registry Attachment Reader" tabindex="-1">Artifact Registry Attachment Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.attachmentReader</code> )</p>
<p>Access to read attachments from a repository</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.attachmentWriter" class="role-title add-link" data-text="Artifact Registry Attachment Writer" tabindex="-1">Artifact Registry Attachment Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p>Access to write attachments to a repository</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.upload</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.containerRegistryMigrationAdmin" class="role-title add-link" data-text="Container Registry -&gt; Artifact Registry Migration Admin" tabindex="-1">Container Registry -&gt; Artifact Registry Migration Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p>Access to run migration tooling to migrate from Container Registry to Artifact Registry</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  projectsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.createOnPushRepoAdmin" class="role-title add-link" data-text="Artifact Registry Create-on-Push Repository Administrator" tabindex="-1">Artifact Registry Create-on-Push Repository Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p>Access to manage artifacts in repositories, as well as create new repositories on push</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.files.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.files.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  files.  download</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.update</code></li>
<li><code dir="ltr" translate="no">artifactregistry.files.upload</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.packages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.packages.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createOnPush</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.rules.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.rules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.tags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.tags.create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.tags.update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.versions.list</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.createOnPushWriter" class="role-title add-link" data-text="Artifact Registry Create-on-Push Writer" tabindex="-1">Artifact Registry Create-on-Push Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p>Access to read and write repository items, as well as create new repositories on push</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.upload</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createOnPush</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.reader" class="role-title add-link" data-text="Artifact Registry Reader" tabindex="-1">Artifact Registry Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p>Access to read repository items.</p></td>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.writer" class="role-title add-link" data-text="Artifact Registry Writer" tabindex="-1">Artifact Registry Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p>Access to read and write repository items.</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.upload</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></p>
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
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.update</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
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
<td><h4 id="artifactregistry.serviceAgent" class="role-title add-link" data-text="Artifact Registry Service Agent" tabindex="-1">Artifact Registry Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  artifactregistry.serviceAgent</code> )</p>
<p>Gives the Artifact Registry service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p></td>
</tr>
</tbody>
</table>

## Artifact Registry permissions

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
<td><h4 id="artifactregistry.aptartifacts.create" class="permission-name add-link" data-text="artifactregistry.aptartifacts.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  aptartifacts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.attachments.create" class="permission-name add-link" data-text="artifactregistry.attachments.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  attachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.attachments.delete" class="permission-name add-link" data-text="artifactregistry.attachments.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  attachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.attachments.get" class="permission-name add-link" data-text="artifactregistry.attachments.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentReader">Artifact Registry Attachment Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.attachments.list" class="permission-name add-link" data-text="artifactregistry.attachments.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentReader">Artifact Registry Attachment Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.dockerimages.get" class="permission-name add-link" data-text="artifactregistry.dockerimages.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.controlPlaneMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.nodePoolMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.dockerimages.list" class="permission-name add-link" data-text="artifactregistry.dockerimages.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.files.delete" class="permission-name add-link" data-text="artifactregistry.files.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.files.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.files.download" class="permission-name add-link" data-text="artifactregistry.files.download" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  files.  download</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentReader">Artifact Registry Attachment Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkactions#networkactions.serviceAgent">Network Actions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkactions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.files.get" class="permission-name add-link" data-text="artifactregistry.files.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.files.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.files.list" class="permission-name add-link" data-text="artifactregistry.files.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.files.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.files.update" class="permission-name add-link" data-text="artifactregistry.files.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.files.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.files.upload" class="permission-name add-link" data-text="artifactregistry.files.upload" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.files.upload</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.attachmentWriter">Artifact Registry Attachment Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.attachmentWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.kfpartifacts.create" class="permission-name add-link" data-text="artifactregistry.kfpartifacts.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  kfpartifacts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.locations.get" class="permission-name add-link" data-text="artifactregistry.locations.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.locations.list" class="permission-name add-link" data-text="artifactregistry.locations.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.mavenartifacts.get" class="permission-name add-link" data-text="artifactregistry.mavenartifacts.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.mavenartifacts.list" class="permission-name add-link" data-text="artifactregistry.mavenartifacts.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.npmpackages.get" class="permission-name add-link" data-text="artifactregistry.npmpackages.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.npmpackages.list" class="permission-name add-link" data-text="artifactregistry.npmpackages.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.packages.delete" class="permission-name add-link" data-text="artifactregistry.packages.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.packages.get" class="permission-name add-link" data-text="artifactregistry.packages.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.packages.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.packages.list" class="permission-name add-link" data-text="artifactregistry.packages.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.packages.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.packages.update" class="permission-name add-link" data-text="artifactregistry.packages.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  packages.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.projectconfigs.get" class="permission-name add-link" data-text="artifactregistry.projectconfigs.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.projectconfigs.update" class="permission-name add-link" data-text="artifactregistry.projectconfigs.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.projectsettings.get" class="permission-name add-link" data-text="artifactregistry.projectsettings.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.projectsettings.update" class="permission-name add-link" data-text="artifactregistry.projectsettings.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  projectsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.pythonpackages.get" class="permission-name add-link" data-text="artifactregistry.pythonpackages.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.pythonpackages.list" class="permission-name add-link" data-text="artifactregistry.pythonpackages.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.create" class="permission-name add-link" data-text="artifactregistry.repositories.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.createOnPush" class="permission-name add-link" data-text="artifactregistry.repositories.createOnPush" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  createOnPush</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.createTagBinding" class="permission-name add-link" data-text="artifactregistry.repositories.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.delete" class="permission-name add-link" data-text="artifactregistry.repositories.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.deleteArtifacts" class="permission-name add-link" data-text="artifactregistry.repositories.deleteArtifacts" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.deleteTagBinding" class="permission-name add-link" data-text="artifactregistry.repositories.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.downloadArtifacts" class="permission-name add-link" data-text="artifactregistry.repositories.downloadArtifacts" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.agentSandboxServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.controlPlaneMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.nodePoolMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkactions#networkactions.serviceAgent">Network Actions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkactions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.exportArtifacts" class="permission-name add-link" data-text="artifactregistry.repositories.exportArtifacts" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.get" class="permission-name add-link" data-text="artifactregistry.repositories.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.controlPlaneMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.nodePoolMachineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.getIamPolicy" class="permission-name add-link" data-text="artifactregistry.repositories.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.list" class="permission-name add-link" data-text="artifactregistry.repositories.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.listEffectiveTags" class="permission-name add-link" data-text="artifactregistry.repositories.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.listTagBindings" class="permission-name add-link" data-text="artifactregistry.repositories.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.readViaVirtualRepository" class="permission-name add-link" data-text="artifactregistry.repositories.readViaVirtualRepository" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.setIamPolicy" class="permission-name add-link" data-text="artifactregistry.repositories.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.repositories.update" class="permission-name add-link" data-text="artifactregistry.repositories.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.repositories.uploadArtifacts" class="permission-name add-link" data-text="artifactregistry.repositories.uploadArtifacts" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.builder">Cloud Run Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.rules.create" class="permission-name add-link" data-text="artifactregistry.rules.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.rules.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.rules.delete" class="permission-name add-link" data-text="artifactregistry.rules.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.rules.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.rules.get" class="permission-name add-link" data-text="artifactregistry.rules.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.rules.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.rules.list" class="permission-name add-link" data-text="artifactregistry.rules.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.rules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.rules.update" class="permission-name add-link" data-text="artifactregistry.rules.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.rules.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.tags.create" class="permission-name add-link" data-text="artifactregistry.tags.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.tags.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.tags.delete" class="permission-name add-link" data-text="artifactregistry.tags.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.tags.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.tags.get" class="permission-name add-link" data-text="artifactregistry.tags.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.tags.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.tags.list" class="permission-name add-link" data-text="artifactregistry.tags.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.tags.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.tags.update" class="permission-name add-link" data-text="artifactregistry.tags.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.tags.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.versions.delete" class="permission-name add-link" data-text="artifactregistry.versions.delete" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  versions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.versions.get" class="permission-name add-link" data-text="artifactregistry.versions.get" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.versions.list" class="permission-name add-link" data-text="artifactregistry.versions.list" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="artifactregistry.versions.update" class="permission-name add-link" data-text="artifactregistry.versions.update" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  versions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="artifactregistry.yumartifacts.create" class="permission-name add-link" data-text="artifactregistry.yumartifacts.create" tabindex="-1"><code dir="ltr" translate="no">artifactregistry.  yumartifacts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
