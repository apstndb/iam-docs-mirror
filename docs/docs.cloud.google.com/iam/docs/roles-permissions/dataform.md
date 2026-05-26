---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataform
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataform
title: Dataform roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dataform. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dataform roles

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
<td><h4 id="dataform.admin" class="role-title add-link" data-text="Dataform Admin" tabindex="-1">Dataform Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p>Full access to all Dataform resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
<li><code dir="ltr" translate="no">dataform.config.get</code></li>
<li><code dir="ltr" translate="no">dataform.config.update</code></li>
<li><code dir="ltr" translate="no">dataform.folders.addContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.create</code></li>
<li><code dir="ltr" translate="no">dataform.folders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.folders.deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.folders.get</code></li>
<li><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.move</code></li>
<li><code dir="ltr" translate="no">dataform.folders.queryContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.update</code></li>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
<li><code dir="ltr" translate="no">dataform.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dataform.operations.delete</code></li>
<li><code dir="ltr" translate="no">dataform.operations.get</code></li>
<li><code dir="ltr" translate="no">dataform.operations.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.create</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.delete</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.releaseConfigs.update</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.commit</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.create</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.get</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.list</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.move</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleRelease</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  scheduleWorkflow</code></li>
<li><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.repositories.update</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.create</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.get</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.teamFolders.update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></li>
<li><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowConfigs.  update</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.commit</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.create</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.get</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.pull</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.push</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.reset</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.editor" class="role-title add-link" data-text="Dataform Editor" tabindex="-1">Dataform Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p>Edit access to Workspaces and Read-only access to Repositories.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.get</code></p>
<p><code dir="ltr" translate="no">dataform.commentThreads.list</code></p>
<p><code dir="ltr" translate="no">dataform.comments.get</code></p>
<p><code dir="ltr" translate="no">dataform.comments.list</code></p>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.config.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.workflowInvocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.workspaces.commit</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.create</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.pull</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.push</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.reset</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.viewer" class="role-title add-link" data-text="Dataform Viewer" tabindex="-1">Dataform Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p>Read-only access to all Dataform resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.get</code></p>
<p><code dir="ltr" translate="no">dataform.commentThreads.list</code></p>
<p><code dir="ltr" translate="no">dataform.comments.get</code></p>
<p><code dir="ltr" translate="no">dataform.comments.list</code></p>
<p><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></p>
<p><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></p>
<p><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></p>
<p><code dir="ltr" translate="no">dataform.config.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.codeCommenter" class="role-title add-link" data-text="Code Commenter Beta" tabindex="-1">Code Commenter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p>Permissions to comment, at the repository level. Grants CRUD access over commentThread and comment resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.get</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.codeCreator" class="role-title add-link" data-text="Code Creator" tabindex="-1">Code Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p>Access only to private and shared code resources. The permissions in the Code Creator let you create and list code in Dataform, and access only the code that you created and code that was explicitly shared with you.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.get</code></p>
<p><code dir="ltr" translate="no">dataform.commentThreads.list</code></p>
<p><code dir="ltr" translate="no">dataform.comments.get</code></p>
<p><code dir="ltr" translate="no">dataform.comments.list</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.codeEditor" class="role-title add-link" data-text="Code Editor" tabindex="-1">Code Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p>Edit access code resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.addContents</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.commit</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.commit</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.create</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.pull</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.push</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.reset</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.codeOwner" class="role-title add-link" data-text="Code Owner" tabindex="-1">Code Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p>Full access to code resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.folders.addContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.create</code></li>
<li><code dir="ltr" translate="no">dataform.folders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.folders.deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.folders.get</code></li>
<li><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.move</code></li>
<li><code dir="ltr" translate="no">dataform.folders.queryContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.commit</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.move</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.update</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.workspaces.commit</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.create</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.get</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.pull</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.push</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.reset</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.codeScheduler" class="role-title add-link" data-text="Code Scheduler Beta" tabindex="-1">Code Scheduler <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeScheduler</code> )</p>
<p>Access for scheduling workflows and releases.</p></td>
<td><p><code dir="ltr" translate="no">dataform.releaseConfigs.create</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowConfigs.  create</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.codeViewer" class="role-title add-link" data-text="Code Viewer" tabindex="-1">Code Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p>Read-only access to all code resources.</p></td>
<td><p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolderCommenter" class="role-title add-link" data-text="Team Folder Commenter Beta" tabindex="-1">Team Folder Commenter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p>View and comment access to a team folder and its contents.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.teamFolderContributor" class="role-title add-link" data-text="Team Folder Contributor" tabindex="-1">Team Folder Contributor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p>Edit access to a team folder and its contents.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.addContents</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.commit</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.update</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.commit</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.create</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.pull</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.push</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.reset</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolderCreator" class="role-title add-link" data-text="Team Folder Creator" tabindex="-1">Team Folder Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.teamFolderCreator</code> )</p>
<p>Access to create new team folders.</p></td>
<td><p><code dir="ltr" translate="no">dataform.teamFolders.create</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.teamFolderOwner" class="role-title add-link" data-text="Team Folder Owner" tabindex="-1">Team Folder Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p>Full access to a team folder and its contents. Can share the team folder and its contents.</p></td>
<td><p><code dir="ltr" translate="no">dataform.commentThreads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.commentThreads.create</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.delete</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.get</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.list</code></li>
<li><code dir="ltr" translate="no">dataform.commentThreads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.comments.create</code></li>
<li><code dir="ltr" translate="no">dataform.comments.delete</code></li>
<li><code dir="ltr" translate="no">dataform.comments.get</code></li>
<li><code dir="ltr" translate="no">dataform.comments.list</code></li>
<li><code dir="ltr" translate="no">dataform.comments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.folders.addContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.create</code></li>
<li><code dir="ltr" translate="no">dataform.folders.delete</code></li>
<li><code dir="ltr" translate="no">dataform.folders.deleteTree</code></li>
<li><code dir="ltr" translate="no">dataform.folders.get</code></li>
<li><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.move</code></li>
<li><code dir="ltr" translate="no">dataform.folders.queryContents</code></li>
<li><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.folders.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.operations.get</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.commit</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.move</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.update</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.delete</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  deleteTree</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.update</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.workspaces.commit</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.create</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.get</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.list</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.pull</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.push</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.readFile</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.reset</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></li>
<li><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolderViewer" class="role-title add-link" data-text="Team Folder Viewer" tabindex="-1">Team Folder Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p>View access to a team folder and its contents.</p></td>
<td><p><code dir="ltr" translate="no">dataform.compilationResults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></li>
<li><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.get</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.queryContents</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.get</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.teamFolders.get</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.get</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.readFile</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></p>
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
<td><h4 id="dataform.serviceAgent" class="role-title add-link" data-text="Dataform Service Agent" tabindex="-1">Dataform Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataform.serviceAgent</code> )</p>
<p>Gives permission for the Dataform API to access a secret from Secret Manager</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Dataform permissions

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
<td><h4 id="dataform.commentThreads.create" class="permission-name add-link" data-text="dataform.commentThreads.create" tabindex="-1"><code dir="ltr" translate="no">dataform.commentThreads.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.commentThreads.delete" class="permission-name add-link" data-text="dataform.commentThreads.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.commentThreads.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.commentThreads.get" class="permission-name add-link" data-text="dataform.commentThreads.get" tabindex="-1"><code dir="ltr" translate="no">dataform.commentThreads.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.commentThreads.list" class="permission-name add-link" data-text="dataform.commentThreads.list" tabindex="-1"><code dir="ltr" translate="no">dataform.commentThreads.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.commentThreads.update" class="permission-name add-link" data-text="dataform.commentThreads.update" tabindex="-1"><code dir="ltr" translate="no">dataform.commentThreads.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.comments.create" class="permission-name add-link" data-text="dataform.comments.create" tabindex="-1"><code dir="ltr" translate="no">dataform.comments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.comments.delete" class="permission-name add-link" data-text="dataform.comments.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.comments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.comments.get" class="permission-name add-link" data-text="dataform.comments.get" tabindex="-1"><code dir="ltr" translate="no">dataform.comments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.comments.list" class="permission-name add-link" data-text="dataform.comments.list" tabindex="-1"><code dir="ltr" translate="no">dataform.comments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.comments.update" class="permission-name add-link" data-text="dataform.comments.update" tabindex="-1"><code dir="ltr" translate="no">dataform.comments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.compilationResults.create" class="permission-name add-link" data-text="dataform.compilationResults.create" tabindex="-1"><code dir="ltr" translate="no">dataform.  compilationResults.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.compilationResults.get" class="permission-name add-link" data-text="dataform.compilationResults.get" tabindex="-1"><code dir="ltr" translate="no">dataform.  compilationResults.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.compilationResults.list" class="permission-name add-link" data-text="dataform.compilationResults.list" tabindex="-1"><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.compilationResults.query" class="permission-name add-link" data-text="dataform.compilationResults.query" tabindex="-1"><code dir="ltr" translate="no">dataform.  compilationResults.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.config.get" class="permission-name add-link" data-text="dataform.config.get" tabindex="-1"><code dir="ltr" translate="no">dataform.config.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.config.update" class="permission-name add-link" data-text="dataform.config.update" tabindex="-1"><code dir="ltr" translate="no">dataform.config.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.folders.addContents" class="permission-name add-link" data-text="dataform.folders.addContents" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.addContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.folders.create" class="permission-name add-link" data-text="dataform.folders.create" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.folders.delete" class="permission-name add-link" data-text="dataform.folders.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.folders.deleteTree" class="permission-name add-link" data-text="dataform.folders.deleteTree" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.deleteTree</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.folders.get" class="permission-name add-link" data-text="dataform.folders.get" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.folders.getIamPolicy" class="permission-name add-link" data-text="dataform.folders.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.folders.move" class="permission-name add-link" data-text="dataform.folders.move" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.folders.queryContents" class="permission-name add-link" data-text="dataform.folders.queryContents" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.queryContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.folders.setIamPolicy" class="permission-name add-link" data-text="dataform.folders.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.folders.update" class="permission-name add-link" data-text="dataform.folders.update" tabindex="-1"><code dir="ltr" translate="no">dataform.folders.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.locations.get" class="permission-name add-link" data-text="dataform.locations.get" tabindex="-1"><code dir="ltr" translate="no">dataform.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.locations.list" class="permission-name add-link" data-text="dataform.locations.list" tabindex="-1"><code dir="ltr" translate="no">dataform.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.operations.cancel" class="permission-name add-link" data-text="dataform.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">dataform.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.operations.delete" class="permission-name add-link" data-text="dataform.operations.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.operations.get" class="permission-name add-link" data-text="dataform.operations.get" tabindex="-1"><code dir="ltr" translate="no">dataform.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.operations.list" class="permission-name add-link" data-text="dataform.operations.list" tabindex="-1"><code dir="ltr" translate="no">dataform.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.releaseConfigs.create" class="permission-name add-link" data-text="dataform.releaseConfigs.create" tabindex="-1"><code dir="ltr" translate="no">dataform.releaseConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeScheduler">Code Scheduler</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeScheduler</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.releaseConfigs.delete" class="permission-name add-link" data-text="dataform.releaseConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.releaseConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.releaseConfigs.get" class="permission-name add-link" data-text="dataform.releaseConfigs.get" tabindex="-1"><code dir="ltr" translate="no">dataform.releaseConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.releaseConfigs.list" class="permission-name add-link" data-text="dataform.releaseConfigs.list" tabindex="-1"><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.releaseConfigs.update" class="permission-name add-link" data-text="dataform.releaseConfigs.update" tabindex="-1"><code dir="ltr" translate="no">dataform.releaseConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.commit" class="permission-name add-link" data-text="dataform.repositories.commit" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.commit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.computeAccessTokenStatus" class="permission-name add-link" data-text="dataform.repositories.computeAccessTokenStatus" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  computeAccessTokenStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.create" class="permission-name add-link" data-text="dataform.repositories.create" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.delete" class="permission-name add-link" data-text="dataform.repositories.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.fetchHistory" class="permission-name add-link" data-text="dataform.repositories.fetchHistory" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  fetchHistory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.fetchRemoteBranches" class="permission-name add-link" data-text="dataform.repositories.fetchRemoteBranches" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  fetchRemoteBranches</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.get" class="permission-name add-link" data-text="dataform.repositories.get" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.getIamPolicy" class="permission-name add-link" data-text="dataform.repositories.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.list" class="permission-name add-link" data-text="dataform.repositories.list" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.move" class="permission-name add-link" data-text="dataform.repositories.move" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.queryDirectoryContents" class="permission-name add-link" data-text="dataform.repositories.queryDirectoryContents" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  queryDirectoryContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.readFile" class="permission-name add-link" data-text="dataform.repositories.readFile" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.readFile</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.scheduleRelease" class="permission-name add-link" data-text="dataform.repositories.scheduleRelease" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  scheduleRelease</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.scheduleWorkflow" class="permission-name add-link" data-text="dataform.repositories.scheduleWorkflow" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  scheduleWorkflow</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.repositories.setIamPolicy" class="permission-name add-link" data-text="dataform.repositories.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.repositories.update" class="permission-name add-link" data-text="dataform.repositories.update" tabindex="-1"><code dir="ltr" translate="no">dataform.repositories.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolders.create" class="permission-name add-link" data-text="dataform.teamFolders.create" tabindex="-1"><code dir="ltr" translate="no">dataform.teamFolders.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCreator">Team Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.teamFolders.delete" class="permission-name add-link" data-text="dataform.teamFolders.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.teamFolders.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolders.deleteTree" class="permission-name add-link" data-text="dataform.teamFolders.deleteTree" tabindex="-1"><code dir="ltr" translate="no">dataform.  teamFolders.  deleteTree</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.teamFolders.get" class="permission-name add-link" data-text="dataform.teamFolders.get" tabindex="-1"><code dir="ltr" translate="no">dataform.teamFolders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolders.getIamPolicy" class="permission-name add-link" data-text="dataform.teamFolders.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.teamFolders.setIamPolicy" class="permission-name add-link" data-text="dataform.teamFolders.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.teamFolders.update" class="permission-name add-link" data-text="dataform.teamFolders.update" tabindex="-1"><code dir="ltr" translate="no">dataform.teamFolders.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowConfigs.create" class="permission-name add-link" data-text="dataform.workflowConfigs.create" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeScheduler">Code Scheduler</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeScheduler</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workflowConfigs.delete" class="permission-name add-link" data-text="dataform.workflowConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowConfigs.get" class="permission-name add-link" data-text="dataform.workflowConfigs.get" tabindex="-1"><code dir="ltr" translate="no">dataform.workflowConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workflowConfigs.list" class="permission-name add-link" data-text="dataform.workflowConfigs.list" tabindex="-1"><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowConfigs.update" class="permission-name add-link" data-text="dataform.workflowConfigs.update" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workflowInvocations.cancel" class="permission-name add-link" data-text="dataform.workflowInvocations.cancel" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowInvocations.create" class="permission-name add-link" data-text="dataform.workflowInvocations.create" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workflowInvocations.delete" class="permission-name add-link" data-text="dataform.workflowInvocations.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowInvocations.get" class="permission-name add-link" data-text="dataform.workflowInvocations.get" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workflowInvocations.list" class="permission-name add-link" data-text="dataform.workflowInvocations.list" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workflowInvocations.query" class="permission-name add-link" data-text="dataform.workflowInvocations.query" tabindex="-1"><code dir="ltr" translate="no">dataform.  workflowInvocations.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.commit" class="permission-name add-link" data-text="dataform.workspaces.commit" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.commit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.create" class="permission-name add-link" data-text="dataform.workspaces.create" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.delete" class="permission-name add-link" data-text="dataform.workspaces.delete" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.fetchFileDiff" class="permission-name add-link" data-text="dataform.workspaces.fetchFileDiff" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileDiff</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.fetchFileGitStatuses" class="permission-name add-link" data-text="dataform.workspaces.fetchFileGitStatuses" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  fetchFileGitStatuses</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.fetchGitAheadBehind" class="permission-name add-link" data-text="dataform.workspaces.fetchGitAheadBehind" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  fetchGitAheadBehind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.get" class="permission-name add-link" data-text="dataform.workspaces.get" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.getIamPolicy" class="permission-name add-link" data-text="dataform.workspaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.installNpmPackages" class="permission-name add-link" data-text="dataform.workspaces.installNpmPackages" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  installNpmPackages</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.list" class="permission-name add-link" data-text="dataform.workspaces.list" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.makeDirectory" class="permission-name add-link" data-text="dataform.workspaces.makeDirectory" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  makeDirectory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.moveDirectory" class="permission-name add-link" data-text="dataform.workspaces.moveDirectory" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  moveDirectory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.moveFile" class="permission-name add-link" data-text="dataform.workspaces.moveFile" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.moveFile</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.pull" class="permission-name add-link" data-text="dataform.workspaces.pull" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.pull</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.push" class="permission-name add-link" data-text="dataform.workspaces.push" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.push</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.queryDirectoryContents" class="permission-name add-link" data-text="dataform.workspaces.queryDirectoryContents" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  queryDirectoryContents</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.readFile" class="permission-name add-link" data-text="dataform.workspaces.readFile" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.readFile</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.removeDirectory" class="permission-name add-link" data-text="dataform.workspaces.removeDirectory" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  removeDirectory</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.removeFile" class="permission-name add-link" data-text="dataform.workspaces.removeFile" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.removeFile</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.reset" class="permission-name add-link" data-text="dataform.workspaces.reset" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.reset</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.searchFiles" class="permission-name add-link" data-text="dataform.workspaces.searchFiles" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  searchFiles</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dataform.workspaces.setIamPolicy" class="permission-name add-link" data-text="dataform.workspaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataform.workspaces.writeFile" class="permission-name add-link" data-text="dataform.workspaces.writeFile" tabindex="-1"><code dir="ltr" translate="no">dataform.workspaces.writeFile</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
