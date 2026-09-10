---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager
title: Secure Source Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Secure Source Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Secure Source Manager roles

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
<td><h4 id="securesourcemanager.admin" class="role-title add-link" data-text="Secure Source Manager Admin" tabindex="-1">Secure Source Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p>Full access to all Secure Source Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  linkDeveloperConnect</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.issues.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  resolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  unresolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  merge</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  approvePullRequests</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  writeIssues</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  writePullRequests</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  createAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  deleteAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.editor" class="role-title add-link" data-text="Securesourcemanager Editor" tabindex="-1">Securesourcemanager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p>Editor role for securesourcemanager</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  create</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  linkDeveloperConnect</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.issues.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  resolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  unresolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  merge</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  approvePullRequests</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  update</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  writeIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  writePullRequests</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  createAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  deleteAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.viewer" class="role-title add-link" data-text="Securesourcemanager Viewer" tabindex="-1">Securesourcemanager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p>Viewer role for securesourcemanager</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.issues.get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.developerConnectLinker" class="role-title add-link" data-text="Secure Source Manager Developer Connect Linker" tabindex="-1">Secure Source Manager Developer Connect Linker</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p>A Developer Connect Linker can link a Secure Source Manager instance to Developer Connect.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  linkDeveloperConnect</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instanceAccessor" class="role-title add-link" data-text="Secure Source Manager Instance Accessor" tabindex="-1">Secure Source Manager Instance Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p>An instance accessor can access an instance, but not necessarily create resources in the instance.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instanceManager" class="role-title add-link" data-text="Secure Source Manager Instance Manager" tabindex="-1">Secure Source Manager Instance Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p>Read-write access to all Secure Source Manager resources (full control except for the ability to modify permissions).</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  createAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  deleteAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instanceOwner" class="role-title add-link" data-text="Secure Source Manager Instance Owner" tabindex="-1">Secure Source Manager Instance Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p>Full control over Secure Source Manager instances, including listing, creating, and deleting them. Also enables instance user management.</p></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  linkDeveloperConnect</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  instances.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  createAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  deleteAny</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instanceRepositoryCreator" class="role-title add-link" data-text="Secure Source Manager Instance Repository Creator" tabindex="-1">Secure Source Manager Instance Repository Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p>An instance repository creator can connect to a Cloud Git instance via IAP (HTTPS) and create repositories in the instance.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repoAdmin" class="role-title add-link" data-text="Secure Source Manager Repository Admin" tabindex="-1">Secure Source Manager Repository Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p>A repoAdmin has the ability to CRUD a repository and its children as well as assign users to a repository. They can also set, get, or check IAM policies on the repository.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  branchRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  hooks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.issues.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  resolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  unresolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  merge</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  approvePullRequests</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  update</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  writeIssues</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  repositories.  writePullRequests</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repoCreator" class="role-title add-link" data-text="Secure Source Manager Repository Creator" tabindex="-1">Secure Source Manager Repository Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.repoCreator</code> )</p>
<p>A repoCreator has access to create repostiory in a project, the creator will then become the repoAdmin on this repository.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  create</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repoPullRequestApprover" class="role-title add-link" data-text="Secure Source Manager Repository Pull Request Approver" tabindex="-1">Secure Source Manager Repository Pull Request Approver</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.repoPullRequestApprover</code> )</p>
<p>A pull request approver can approve pull requests in a repository.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  approvePullRequests</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repoReader" class="role-title add-link" data-text="Secure Source Manager Repository Reader" tabindex="-1">Secure Source Manager Repository Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p>A repoReader has read access to a particular repository, including its child components. They cannot create repositories, and do not manage IAM policies on the repository.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.issues.get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repoWriter" class="role-title add-link" data-text="Secure Source Manager Repository Writer" tabindex="-1">Secure Source Manager Repository Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p>
<p>A repoWriter has read/write access to a particular repository, including its child components. They cannot create repositories, and do not manage IAM policies on the repository.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.issues.get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  issues.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  delete</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  resolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  unresolve</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  prcomments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  close</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  create</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  merge</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  open</code></li>
<li><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  writeIssues</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  writePullRequests</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.sshKeyUser" class="role-title add-link" data-text="Secure Source Manager SSH Key User" tabindex="-1">Secure Source Manager SSH Key User</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p>
<p>An sshKeyUser can create SSH keys for themselves and list/delete SSH keys they own.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p></td>
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
<td><h4 id="securesourcemanager.serviceAgent" class="role-title add-link" data-text="Secure Source Manager Service Agent" tabindex="-1">Secure Source Manager Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securesourcemanager.serviceAgent</code> )</p>
<p>Gives Secure Source Manager service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Secure Source Manager permissions

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
<td><h4 id="securesourcemanager.branchRules.create" class="permission-name add-link" data-text="securesourcemanager.branchRules.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  branchRules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.branchRules.delete" class="permission-name add-link" data-text="securesourcemanager.branchRules.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  branchRules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.branchRules.get" class="permission-name add-link" data-text="securesourcemanager.branchRules.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  branchRules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.branchRules.list" class="permission-name add-link" data-text="securesourcemanager.branchRules.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.branchRules.update" class="permission-name add-link" data-text="securesourcemanager.branchRules.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  branchRules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.hooks.create" class="permission-name add-link" data-text="securesourcemanager.hooks.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  hooks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.hooks.delete" class="permission-name add-link" data-text="securesourcemanager.hooks.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  hooks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.hooks.get" class="permission-name add-link" data-text="securesourcemanager.hooks.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.hooks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.hooks.list" class="permission-name add-link" data-text="securesourcemanager.hooks.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.hooks.update" class="permission-name add-link" data-text="securesourcemanager.hooks.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  hooks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instances.access" class="permission-name add-link" data-text="securesourcemanager.instances.access" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instances.create" class="permission-name add-link" data-text="securesourcemanager.instances.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instances.createRepository" class="permission-name add-link" data-text="securesourcemanager.instances.createRepository" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  createRepository</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instances.delete" class="permission-name add-link" data-text="securesourcemanager.instances.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instances.get" class="permission-name add-link" data-text="securesourcemanager.instances.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instances.getIamPolicy" class="permission-name add-link" data-text="securesourcemanager.instances.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instances.linkDeveloperConnect" class="permission-name add-link" data-text="securesourcemanager.instances.linkDeveloperConnect" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  linkDeveloperConnect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.instances.list" class="permission-name add-link" data-text="securesourcemanager.instances.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.instances.setIamPolicy" class="permission-name add-link" data-text="securesourcemanager.instances.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  instances.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issuecomments.create" class="permission-name add-link" data-text="securesourcemanager.issuecomments.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issuecomments.delete" class="permission-name add-link" data-text="securesourcemanager.issuecomments.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issuecomments.get" class="permission-name add-link" data-text="securesourcemanager.issuecomments.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issuecomments.list" class="permission-name add-link" data-text="securesourcemanager.issuecomments.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issuecomments.update" class="permission-name add-link" data-text="securesourcemanager.issuecomments.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issues.close" class="permission-name add-link" data-text="securesourcemanager.issues.close" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  close</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issues.create" class="permission-name add-link" data-text="securesourcemanager.issues.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issues.delete" class="permission-name add-link" data-text="securesourcemanager.issues.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issues.get" class="permission-name add-link" data-text="securesourcemanager.issues.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.issues.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issues.list" class="permission-name add-link" data-text="securesourcemanager.issues.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.issues.open" class="permission-name add-link" data-text="securesourcemanager.issues.open" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  open</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.issues.update" class="permission-name add-link" data-text="securesourcemanager.issues.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  issues.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.locations.get" class="permission-name add-link" data-text="securesourcemanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.locations.list" class="permission-name add-link" data-text="securesourcemanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.operations.cancel" class="permission-name add-link" data-text="securesourcemanager.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.operations.delete" class="permission-name add-link" data-text="securesourcemanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.operations.get" class="permission-name add-link" data-text="securesourcemanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.operations.list" class="permission-name add-link" data-text="securesourcemanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.prcomments.create" class="permission-name add-link" data-text="securesourcemanager.prcomments.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.prcomments.delete" class="permission-name add-link" data-text="securesourcemanager.prcomments.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.prcomments.get" class="permission-name add-link" data-text="securesourcemanager.prcomments.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.prcomments.list" class="permission-name add-link" data-text="securesourcemanager.prcomments.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.prcomments.resolve" class="permission-name add-link" data-text="securesourcemanager.prcomments.resolve" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  resolve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.prcomments.unresolve" class="permission-name add-link" data-text="securesourcemanager.prcomments.unresolve" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  unresolve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.prcomments.update" class="permission-name add-link" data-text="securesourcemanager.prcomments.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  prcomments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.pullRequests.close" class="permission-name add-link" data-text="securesourcemanager.pullRequests.close" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  close</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.pullRequests.create" class="permission-name add-link" data-text="securesourcemanager.pullRequests.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.pullRequests.get" class="permission-name add-link" data-text="securesourcemanager.pullRequests.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.pullRequests.list" class="permission-name add-link" data-text="securesourcemanager.pullRequests.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.pullRequests.listFileDiffs" class="permission-name add-link" data-text="securesourcemanager.pullRequests.listFileDiffs" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  listFileDiffs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.pullRequests.merge" class="permission-name add-link" data-text="securesourcemanager.pullRequests.merge" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  merge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.pullRequests.open" class="permission-name add-link" data-text="securesourcemanager.pullRequests.open" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  open</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.pullRequests.update" class="permission-name add-link" data-text="securesourcemanager.pullRequests.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.approvePullRequests" class="permission-name add-link" data-text="securesourcemanager.repositories.approvePullRequests" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  approvePullRequests</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoPullRequestApprover</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.create" class="permission-name add-link" data-text="securesourcemanager.repositories.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.delete" class="permission-name add-link" data-text="securesourcemanager.repositories.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.fetch" class="permission-name add-link" data-text="securesourcemanager.repositories.fetch" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.get" class="permission-name add-link" data-text="securesourcemanager.repositories.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.getIamPolicy" class="permission-name add-link" data-text="securesourcemanager.repositories.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.list" class="permission-name add-link" data-text="securesourcemanager.repositories.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.push" class="permission-name add-link" data-text="securesourcemanager.repositories.push" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  push</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.readIssues" class="permission-name add-link" data-text="securesourcemanager.repositories.readIssues" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  readIssues</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.readPullRequests" class="permission-name add-link" data-text="securesourcemanager.repositories.readPullRequests" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  readPullRequests</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.setIamPolicy" class="permission-name add-link" data-text="securesourcemanager.repositories.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.update" class="permission-name add-link" data-text="securesourcemanager.repositories.update" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.repositories.writeIssues" class="permission-name add-link" data-text="securesourcemanager.repositories.writeIssues" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  writeIssues</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.repositories.writePullRequests" class="permission-name add-link" data-text="securesourcemanager.repositories.writePullRequests" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  repositories.  writePullRequests</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.repoWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.sshkeys.create" class="permission-name add-link" data-text="securesourcemanager.sshkeys.create" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.sshkeys.createAny" class="permission-name add-link" data-text="securesourcemanager.sshkeys.createAny" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  createAny</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.sshkeys.delete" class="permission-name add-link" data-text="securesourcemanager.sshkeys.delete" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.sshkeys.deleteAny" class="permission-name add-link" data-text="securesourcemanager.sshkeys.deleteAny" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  deleteAny</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.sshkeys.get" class="permission-name add-link" data-text="securesourcemanager.sshkeys.get" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securesourcemanager.sshkeys.list" class="permission-name add-link" data-text="securesourcemanager.sshkeys.list" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.sshKeyUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securesourcemanager.sshkeys.listAny" class="permission-name add-link" data-text="securesourcemanager.sshkeys.listAny" tabindex="-1"><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  listAny</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.instanceOwner</code> )</p></td>
</tr>
</tbody>
</table>
