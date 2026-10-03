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
<td>Dataform Admin
<p>( <code>roles/ dataform.admin</code> )</p>
<p>Full access to all Dataform resources.</p></td>
<td><p><code>dataform.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
<li><code>dataform.config.get</code></li>
<li><code>dataform.config.update</code></li>
<li><code>dataform.folders.addContents</code></li>
<li><code>dataform.folders.create</code></li>
<li><code>dataform.folders.delete</code></li>
<li><code>dataform.folders.deleteTree</code></li>
<li><code>dataform.folders.get</code></li>
<li><code>dataform.folders.getIamPolicy</code></li>
<li><code>dataform.folders.move</code></li>
<li><code>dataform.folders.queryContents</code></li>
<li><code>dataform.folders.setIamPolicy</code></li>
<li><code>dataform.folders.update</code></li>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
<li><code>dataform.operations.cancel</code></li>
<li><code>dataform.operations.delete</code></li>
<li><code>dataform.operations.get</code></li>
<li><code>dataform.operations.list</code></li>
<li><code>dataform.releaseConfigs.create</code></li>
<li><code>dataform.releaseConfigs.delete</code></li>
<li><code>dataform.releaseConfigs.get</code></li>
<li><code>dataform.releaseConfigs.list</code></li>
<li><code>dataform.releaseConfigs.update</code></li>
<li><code>dataform.repositories.commit</code></li>
<li><code>dataform. repositories. computeAccessTokenStatus</code></li>
<li><code>dataform.repositories.create</code></li>
<li><code>dataform. repositories. createTagBinding</code></li>
<li><code>dataform.repositories.delete</code></li>
<li><code>dataform. repositories. deleteTagBinding</code></li>
<li><code>dataform. repositories. fetchHistory</code></li>
<li><code>dataform. repositories. fetchRemoteBranches</code></li>
<li><code>dataform.repositories.get</code></li>
<li><code>dataform. repositories. getIamPolicy</code></li>
<li><code>dataform.repositories.list</code></li>
<li><code>dataform. repositories. listEffectiveTags</code></li>
<li><code>dataform. repositories. listTagBindings</code></li>
<li><code>dataform.repositories.move</code></li>
<li><code>dataform. repositories. queryDirectoryContents</code></li>
<li><code>dataform.repositories.readFile</code></li>
<li><code>dataform. repositories. scheduleRelease</code></li>
<li><code>dataform. repositories. scheduleWorkflow</code></li>
<li><code>dataform. repositories. setIamPolicy</code></li>
<li><code>dataform.repositories.update</code></li>
<li><code>dataform.teamFolders.create</code></li>
<li><code>dataform.teamFolders.delete</code></li>
<li><code>dataform. teamFolders. deleteTree</code></li>
<li><code>dataform.teamFolders.get</code></li>
<li><code>dataform. teamFolders. getIamPolicy</code></li>
<li><code>dataform. teamFolders. setIamPolicy</code></li>
<li><code>dataform.teamFolders.update</code></li>
<li><code>dataform. workflowConfigs. create</code></li>
<li><code>dataform. workflowConfigs. delete</code></li>
<li><code>dataform.workflowConfigs.get</code></li>
<li><code>dataform.workflowConfigs.list</code></li>
<li><code>dataform. workflowConfigs. update</code></li>
<li><code>dataform. workflowInvocations. cancel</code></li>
<li><code>dataform. workflowInvocations. create</code></li>
<li><code>dataform. workflowInvocations. delete</code></li>
<li><code>dataform. workflowInvocations. get</code></li>
<li><code>dataform. workflowInvocations. list</code></li>
<li><code>dataform. workflowInvocations. query</code></li>
<li><code>dataform.workspaces.commit</code></li>
<li><code>dataform.workspaces.create</code></li>
<li><code>dataform.workspaces.delete</code></li>
<li><code>dataform. workspaces. fetchFileDiff</code></li>
<li><code>dataform. workspaces. fetchFileGitStatuses</code></li>
<li><code>dataform. workspaces. fetchGitAheadBehind</code></li>
<li><code>dataform.workspaces.get</code></li>
<li><code>dataform. workspaces. getIamPolicy</code></li>
<li><code>dataform. workspaces. installNpmPackages</code></li>
<li><code>dataform.workspaces.list</code></li>
<li><code>dataform. workspaces. makeDirectory</code></li>
<li><code>dataform. workspaces. moveDirectory</code></li>
<li><code>dataform.workspaces.moveFile</code></li>
<li><code>dataform.workspaces.pull</code></li>
<li><code>dataform.workspaces.push</code></li>
<li><code>dataform. workspaces. queryDirectoryContents</code></li>
<li><code>dataform.workspaces.readFile</code></li>
<li><code>dataform. workspaces. removeDirectory</code></li>
<li><code>dataform.workspaces.removeFile</code></li>
<li><code>dataform.workspaces.reset</code></li>
<li><code>dataform. workspaces. searchFiles</code></li>
<li><code>dataform. workspaces. setIamPolicy</code></li>
<li><code>dataform.workspaces.writeFile</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataform Editor
<p>( <code>roles/ dataform.editor</code> )</p>
<p>Edit access to Workspaces and Read-only access to Repositories.</p></td>
<td><p><code>dataform.commentThreads.get</code></p>
<p><code>dataform.commentThreads.list</code></p>
<p><code>dataform.comments.get</code></p>
<p><code>dataform.comments.list</code></p>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.config.get</code></p>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.releaseConfigs.get</code></p>
<p><code>dataform.releaseConfigs.list</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform.workflowConfigs.get</code></p>
<p><code>dataform.workflowConfigs.list</code></p>
<p><code>dataform.workflowInvocations.*</code></p>
<ul>
<li><code>dataform. workflowInvocations. cancel</code></li>
<li><code>dataform. workflowInvocations. create</code></li>
<li><code>dataform. workflowInvocations. delete</code></li>
<li><code>dataform. workflowInvocations. get</code></li>
<li><code>dataform. workflowInvocations. list</code></li>
<li><code>dataform. workflowInvocations. query</code></li>
</ul>
<p><code>dataform.workspaces.commit</code></p>
<p><code>dataform.workspaces.create</code></p>
<p><code>dataform.workspaces.delete</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform. workspaces. installNpmPackages</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. makeDirectory</code></p>
<p><code>dataform. workspaces. moveDirectory</code></p>
<p><code>dataform.workspaces.moveFile</code></p>
<p><code>dataform.workspaces.pull</code></p>
<p><code>dataform.workspaces.push</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. removeDirectory</code></p>
<p><code>dataform.workspaces.removeFile</code></p>
<p><code>dataform.workspaces.reset</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>dataform.workspaces.writeFile</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataform Viewer
<p>( <code>roles/ dataform.viewer</code> )</p>
<p>Read-only access to all Dataform resources.</p></td>
<td><p><code>dataform.commentThreads.get</code></p>
<p><code>dataform.commentThreads.list</code></p>
<p><code>dataform.comments.get</code></p>
<p><code>dataform.comments.list</code></p>
<p><code>dataform. compilationResults. get</code></p>
<p><code>dataform. compilationResults. list</code></p>
<p><code>dataform. compilationResults. query</code></p>
<p><code>dataform.config.get</code></p>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.releaseConfigs.get</code></p>
<p><code>dataform.releaseConfigs.list</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform.workflowConfigs.get</code></p>
<p><code>dataform.workflowConfigs.list</code></p>
<p><code>dataform. workflowInvocations. get</code></p>
<p><code>dataform. workflowInvocations. list</code></p>
<p><code>dataform. workflowInvocations. query</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Code Commenter <sup>Beta</sup>
<p>( <code>roles/ dataform.codeCommenter</code> )</p>
<p>Permissions to comment, at the repository level. Grants CRUD access over commentThread and comment resources.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.get</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Code Creator
<p>( <code>roles/ dataform.codeCreator</code> )</p>
<p>Access only to private and shared code resources. The permissions in the Code Creator let you create and list code in Dataform, and access only the code that you created and code that was explicitly shared with you.</p></td>
<td><p><code>dataform.commentThreads.get</code></p>
<p><code>dataform.commentThreads.list</code></p>
<p><code>dataform.comments.get</code></p>
<p><code>dataform.comments.list</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Code Editor
<p>( <code>roles/ dataform.codeEditor</code> )</p>
<p>Edit access code resources.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.addContents</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.repositories.commit</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.workspaces.commit</code></p>
<p><code>dataform.workspaces.create</code></p>
<p><code>dataform.workspaces.delete</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform. workspaces. installNpmPackages</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. makeDirectory</code></p>
<p><code>dataform. workspaces. moveDirectory</code></p>
<p><code>dataform.workspaces.moveFile</code></p>
<p><code>dataform.workspaces.pull</code></p>
<p><code>dataform.workspaces.push</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. removeDirectory</code></p>
<p><code>dataform.workspaces.removeFile</code></p>
<p><code>dataform.workspaces.reset</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>dataform.workspaces.writeFile</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Code Owner
<p>( <code>roles/ dataform.codeOwner</code> )</p>
<p>Full access to code resources.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.*</code></p>
<ul>
<li><code>dataform.folders.addContents</code></li>
<li><code>dataform.folders.create</code></li>
<li><code>dataform.folders.delete</code></li>
<li><code>dataform.folders.deleteTree</code></li>
<li><code>dataform.folders.get</code></li>
<li><code>dataform.folders.getIamPolicy</code></li>
<li><code>dataform.folders.move</code></li>
<li><code>dataform.folders.queryContents</code></li>
<li><code>dataform.folders.setIamPolicy</code></li>
<li><code>dataform.folders.update</code></li>
</ul>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.repositories.commit</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform.repositories.delete</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform.repositories.move</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform. repositories. setIamPolicy</code></p>
<p><code>dataform.repositories.update</code></p>
<p><code>dataform.workspaces.*</code></p>
<ul>
<li><code>dataform.workspaces.commit</code></li>
<li><code>dataform.workspaces.create</code></li>
<li><code>dataform.workspaces.delete</code></li>
<li><code>dataform. workspaces. fetchFileDiff</code></li>
<li><code>dataform. workspaces. fetchFileGitStatuses</code></li>
<li><code>dataform. workspaces. fetchGitAheadBehind</code></li>
<li><code>dataform.workspaces.get</code></li>
<li><code>dataform. workspaces. getIamPolicy</code></li>
<li><code>dataform. workspaces. installNpmPackages</code></li>
<li><code>dataform.workspaces.list</code></li>
<li><code>dataform. workspaces. makeDirectory</code></li>
<li><code>dataform. workspaces. moveDirectory</code></li>
<li><code>dataform.workspaces.moveFile</code></li>
<li><code>dataform.workspaces.pull</code></li>
<li><code>dataform.workspaces.push</code></li>
<li><code>dataform. workspaces. queryDirectoryContents</code></li>
<li><code>dataform.workspaces.readFile</code></li>
<li><code>dataform. workspaces. removeDirectory</code></li>
<li><code>dataform.workspaces.removeFile</code></li>
<li><code>dataform.workspaces.reset</code></li>
<li><code>dataform. workspaces. searchFiles</code></li>
<li><code>dataform. workspaces. setIamPolicy</code></li>
<li><code>dataform.workspaces.writeFile</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Code Scheduler <sup>Beta</sup>
<p>( <code>roles/ dataform.codeScheduler</code> )</p>
<p>Access for scheduling workflows and releases.</p></td>
<td><p><code>dataform.releaseConfigs.create</code></p>
<p><code>dataform. workflowConfigs. create</code></p></td>
</tr>
<tr class="odd">
<td>Code Viewer
<p>( <code>roles/ dataform.codeViewer</code> )</p>
<p>Read-only access to all code resources.</p></td>
<td><p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Team Folder Commenter <sup>Beta</sup>
<p>( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p>View and comment access to a team folder and its contents.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Team Folder Contributor
<p>( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p>Edit access to a team folder and its contents.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.addContents</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.repositories.commit</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform.teamFolders.update</code></p>
<p><code>dataform.workspaces.commit</code></p>
<p><code>dataform.workspaces.create</code></p>
<p><code>dataform.workspaces.delete</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform. workspaces. installNpmPackages</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. makeDirectory</code></p>
<p><code>dataform. workspaces. moveDirectory</code></p>
<p><code>dataform.workspaces.moveFile</code></p>
<p><code>dataform.workspaces.pull</code></p>
<p><code>dataform.workspaces.push</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. removeDirectory</code></p>
<p><code>dataform.workspaces.removeFile</code></p>
<p><code>dataform.workspaces.reset</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>dataform.workspaces.writeFile</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Team Folder Creator
<p>( <code>roles/ dataform.teamFolderCreator</code> )</p>
<p>Access to create new team folders.</p></td>
<td><p><code>dataform.teamFolders.create</code></p></td>
</tr>
<tr class="odd">
<td>Team Folder Owner
<p>( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p>Full access to a team folder and its contents. Can share the team folder and its contents.</p></td>
<td><p><code>dataform.commentThreads.*</code></p>
<ul>
<li><code>dataform.commentThreads.create</code></li>
<li><code>dataform.commentThreads.delete</code></li>
<li><code>dataform.commentThreads.get</code></li>
<li><code>dataform.commentThreads.list</code></li>
<li><code>dataform.commentThreads.update</code></li>
</ul>
<p><code>dataform.comments.*</code></p>
<ul>
<li><code>dataform.comments.create</code></li>
<li><code>dataform.comments.delete</code></li>
<li><code>dataform.comments.get</code></li>
<li><code>dataform.comments.list</code></li>
<li><code>dataform.comments.update</code></li>
</ul>
<p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.*</code></p>
<ul>
<li><code>dataform.folders.addContents</code></li>
<li><code>dataform.folders.create</code></li>
<li><code>dataform.folders.delete</code></li>
<li><code>dataform.folders.deleteTree</code></li>
<li><code>dataform.folders.get</code></li>
<li><code>dataform.folders.getIamPolicy</code></li>
<li><code>dataform.folders.move</code></li>
<li><code>dataform.folders.queryContents</code></li>
<li><code>dataform.folders.setIamPolicy</code></li>
<li><code>dataform.folders.update</code></li>
</ul>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.operations.get</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.repositories.commit</code></p>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform.repositories.delete</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform.repositories.move</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform. repositories. setIamPolicy</code></p>
<p><code>dataform.repositories.update</code></p>
<p><code>dataform.teamFolders.delete</code></p>
<p><code>dataform. teamFolders. deleteTree</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform. teamFolders. setIamPolicy</code></p>
<p><code>dataform.teamFolders.update</code></p>
<p><code>dataform.workspaces.*</code></p>
<ul>
<li><code>dataform.workspaces.commit</code></li>
<li><code>dataform.workspaces.create</code></li>
<li><code>dataform.workspaces.delete</code></li>
<li><code>dataform. workspaces. fetchFileDiff</code></li>
<li><code>dataform. workspaces. fetchFileGitStatuses</code></li>
<li><code>dataform. workspaces. fetchGitAheadBehind</code></li>
<li><code>dataform.workspaces.get</code></li>
<li><code>dataform. workspaces. getIamPolicy</code></li>
<li><code>dataform. workspaces. installNpmPackages</code></li>
<li><code>dataform.workspaces.list</code></li>
<li><code>dataform. workspaces. makeDirectory</code></li>
<li><code>dataform. workspaces. moveDirectory</code></li>
<li><code>dataform.workspaces.moveFile</code></li>
<li><code>dataform.workspaces.pull</code></li>
<li><code>dataform.workspaces.push</code></li>
<li><code>dataform. workspaces. queryDirectoryContents</code></li>
<li><code>dataform.workspaces.readFile</code></li>
<li><code>dataform. workspaces. removeDirectory</code></li>
<li><code>dataform.workspaces.removeFile</code></li>
<li><code>dataform.workspaces.reset</code></li>
<li><code>dataform. workspaces. searchFiles</code></li>
<li><code>dataform. workspaces. setIamPolicy</code></li>
<li><code>dataform.workspaces.writeFile</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Team Folder Viewer
<p>( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p>View access to a team folder and its contents.</p></td>
<td><p><code>dataform.compilationResults.*</code></p>
<ul>
<li><code>dataform. compilationResults. create</code></li>
<li><code>dataform. compilationResults. get</code></li>
<li><code>dataform. compilationResults. list</code></li>
<li><code>dataform. compilationResults. query</code></li>
</ul>
<p><code>dataform.folders.get</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.queryContents</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform. repositories. computeAccessTokenStatus</code></p>
<p><code>dataform. repositories. fetchHistory</code></p>
<p><code>dataform. repositories. fetchRemoteBranches</code></p>
<p><code>dataform.repositories.get</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>dataform. repositories. queryDirectoryContents</code></p>
<p><code>dataform.repositories.readFile</code></p>
<p><code>dataform.teamFolders.get</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform. workspaces. fetchFileDiff</code></p>
<p><code>dataform. workspaces. fetchFileGitStatuses</code></p>
<p><code>dataform. workspaces. fetchGitAheadBehind</code></p>
<p><code>dataform.workspaces.get</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. queryDirectoryContents</code></p>
<p><code>dataform.workspaces.readFile</code></p>
<p><code>dataform. workspaces. searchFiles</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Dataform Service Agent
<p>( <code>roles/ dataform.serviceAgent</code> )</p>
<p>Gives permission for the Dataform API to access a secret from Secret Manager</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>dataform. compilationResults. create</code></p>
<p><code>dataform. workflowInvocations. create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>dataform.commentThreads.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.commentThreads.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.commentThreads.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.commentThreads.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.commentThreads.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.comments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.comments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.comments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.comments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.comments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. compilationResults. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code>roles/ dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. compilationResults. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. compilationResults. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. compilationResults. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.config.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.config.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.folders.addContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.folders.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.folders.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.folders.deleteTree</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.folders.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.folders.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.folders.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.folders.queryContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.folders.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.folders.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.releaseConfigs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeScheduler">Code Scheduler</a> ( <code>roles/ dataform.codeScheduler</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.releaseConfigs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.releaseConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.releaseConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.releaseConfigs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.repositories.commit</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. computeAccessTokenStatus</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.repositories.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.repositories.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. repositories. fetchHistory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. fetchRemoteBranches</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.repositories.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.repositories.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. repositories. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.repositories.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. repositories. queryDirectoryContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.repositories.readFile</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. repositories. scheduleRelease</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. repositories. scheduleWorkflow</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. repositories. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.repositories.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.teamFolders.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCreator">Team Folder Creator</a> ( <code>roles/ dataform.teamFolderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.teamFolders.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. teamFolders. deleteTree</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.teamFolders.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. teamFolders. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. teamFolders. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.teamFolders.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workflowConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeScheduler">Code Scheduler</a> ( <code>roles/ dataform.codeScheduler</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workflowConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.workflowConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workflowConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workflowConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workflowInvocations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workflowInvocations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code>roles/ dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workflowInvocations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workflowInvocations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workflowInvocations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workflowInvocations. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.commit</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.workspaces.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. fetchFileDiff</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workspaces. fetchFileGitStatuses</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. fetchGitAheadBehind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workspaces. installNpmPackages</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.workspaces.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workspaces. makeDirectory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. moveDirectory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.moveFile</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.workspaces.pull</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.push</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. queryDirectoryContents</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.readFile</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. removeDirectory</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.removeFile</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform.workspaces.reset</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform. workspaces. searchFiles</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dataform. workspaces. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dataform.workspaces.writeFile</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
