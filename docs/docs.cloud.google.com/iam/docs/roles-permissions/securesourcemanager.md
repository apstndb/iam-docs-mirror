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
<td>Secure Source Manager Admin
<p>( <code>roles/ securesourcemanager.admin</code> )</p>
<p>Full access to all Secure Source Manager resources.</p></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager.*</code></p>
<ul>
<li><code>securesourcemanager. branchRules. create</code></li>
<li><code>securesourcemanager. branchRules. delete</code></li>
<li><code>securesourcemanager. branchRules. get</code></li>
<li><code>securesourcemanager. branchRules. list</code></li>
<li><code>securesourcemanager. branchRules. update</code></li>
<li><code>securesourcemanager. hooks. create</code></li>
<li><code>securesourcemanager. hooks. delete</code></li>
<li><code>securesourcemanager.hooks.get</code></li>
<li><code>securesourcemanager.hooks.list</code></li>
<li><code>securesourcemanager. hooks. update</code></li>
<li><code>securesourcemanager. instances. access</code></li>
<li><code>securesourcemanager. instances. create</code></li>
<li><code>securesourcemanager. instances. createRepository</code></li>
<li><code>securesourcemanager. instances. delete</code></li>
<li><code>securesourcemanager. instances. get</code></li>
<li><code>securesourcemanager. instances. getIamPolicy</code></li>
<li><code>securesourcemanager. instances. linkDeveloperConnect</code></li>
<li><code>securesourcemanager. instances. list</code></li>
<li><code>securesourcemanager. instances. setIamPolicy</code></li>
<li><code>securesourcemanager. issuecomments. create</code></li>
<li><code>securesourcemanager. issuecomments. delete</code></li>
<li><code>securesourcemanager. issuecomments. get</code></li>
<li><code>securesourcemanager. issuecomments. list</code></li>
<li><code>securesourcemanager. issuecomments. update</code></li>
<li><code>securesourcemanager. issues. close</code></li>
<li><code>securesourcemanager. issues. create</code></li>
<li><code>securesourcemanager. issues. delete</code></li>
<li><code>securesourcemanager.issues.get</code></li>
<li><code>securesourcemanager. issues. list</code></li>
<li><code>securesourcemanager. issues. open</code></li>
<li><code>securesourcemanager. issues. update</code></li>
<li><code>securesourcemanager. locations. get</code></li>
<li><code>securesourcemanager. locations. list</code></li>
<li><code>securesourcemanager. operations. cancel</code></li>
<li><code>securesourcemanager. operations. delete</code></li>
<li><code>securesourcemanager. operations. get</code></li>
<li><code>securesourcemanager. operations. list</code></li>
<li><code>securesourcemanager. prcomments. create</code></li>
<li><code>securesourcemanager. prcomments. delete</code></li>
<li><code>securesourcemanager. prcomments. get</code></li>
<li><code>securesourcemanager. prcomments. list</code></li>
<li><code>securesourcemanager. prcomments. resolve</code></li>
<li><code>securesourcemanager. prcomments. unresolve</code></li>
<li><code>securesourcemanager. prcomments. update</code></li>
<li><code>securesourcemanager. pullRequests. close</code></li>
<li><code>securesourcemanager. pullRequests. create</code></li>
<li><code>securesourcemanager. pullRequests. get</code></li>
<li><code>securesourcemanager. pullRequests. list</code></li>
<li><code>securesourcemanager. pullRequests. listFileDiffs</code></li>
<li><code>securesourcemanager. pullRequests. merge</code></li>
<li><code>securesourcemanager. pullRequests. open</code></li>
<li><code>securesourcemanager. pullRequests. update</code></li>
<li><code>securesourcemanager. repositories. approvePullRequests</code></li>
<li><code>securesourcemanager. repositories. create</code></li>
<li><code>securesourcemanager. repositories. delete</code></li>
<li><code>securesourcemanager. repositories. fetch</code></li>
<li><code>securesourcemanager. repositories. get</code></li>
<li><code>securesourcemanager. repositories. getIamPolicy</code></li>
<li><code>securesourcemanager. repositories. list</code></li>
<li><code>securesourcemanager. repositories. push</code></li>
<li><code>securesourcemanager. repositories. readIssues</code></li>
<li><code>securesourcemanager. repositories. readPullRequests</code></li>
<li><code>securesourcemanager. repositories. setIamPolicy</code></li>
<li><code>securesourcemanager. repositories. update</code></li>
<li><code>securesourcemanager. repositories. writeIssues</code></li>
<li><code>securesourcemanager. repositories. writePullRequests</code></li>
<li><code>securesourcemanager. sshkeys. create</code></li>
<li><code>securesourcemanager. sshkeys. createAny</code></li>
<li><code>securesourcemanager. sshkeys. delete</code></li>
<li><code>securesourcemanager. sshkeys. deleteAny</code></li>
<li><code>securesourcemanager. sshkeys. get</code></li>
<li><code>securesourcemanager. sshkeys. list</code></li>
<li><code>securesourcemanager. sshkeys. listAny</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Securesourcemanager Editor
<p>( <code>roles/ securesourcemanager.editor</code> )</p>
<p>Editor role for securesourcemanager</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. branchRules.*</code></p>
<ul>
<li><code>securesourcemanager. branchRules. create</code></li>
<li><code>securesourcemanager. branchRules. delete</code></li>
<li><code>securesourcemanager. branchRules. get</code></li>
<li><code>securesourcemanager. branchRules. list</code></li>
<li><code>securesourcemanager. branchRules. update</code></li>
</ul>
<p><code>securesourcemanager.hooks.*</code></p>
<ul>
<li><code>securesourcemanager. hooks. create</code></li>
<li><code>securesourcemanager. hooks. delete</code></li>
<li><code>securesourcemanager.hooks.get</code></li>
<li><code>securesourcemanager.hooks.list</code></li>
<li><code>securesourcemanager. hooks. update</code></li>
</ul>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. instances. create</code></p>
<p><code>securesourcemanager. instances. createRepository</code></p>
<p><code>securesourcemanager. instances. delete</code></p>
<p><code>securesourcemanager. instances. get</code></p>
<p><code>securesourcemanager. instances. getIamPolicy</code></p>
<p><code>securesourcemanager. instances. linkDeveloperConnect</code></p>
<p><code>securesourcemanager. instances. list</code></p>
<p><code>securesourcemanager. issuecomments.*</code></p>
<ul>
<li><code>securesourcemanager. issuecomments. create</code></li>
<li><code>securesourcemanager. issuecomments. delete</code></li>
<li><code>securesourcemanager. issuecomments. get</code></li>
<li><code>securesourcemanager. issuecomments. list</code></li>
<li><code>securesourcemanager. issuecomments. update</code></li>
</ul>
<p><code>securesourcemanager.issues.*</code></p>
<ul>
<li><code>securesourcemanager. issues. close</code></li>
<li><code>securesourcemanager. issues. create</code></li>
<li><code>securesourcemanager. issues. delete</code></li>
<li><code>securesourcemanager.issues.get</code></li>
<li><code>securesourcemanager. issues. list</code></li>
<li><code>securesourcemanager. issues. open</code></li>
<li><code>securesourcemanager. issues. update</code></li>
</ul>
<p><code>securesourcemanager. locations.*</code></p>
<ul>
<li><code>securesourcemanager. locations. get</code></li>
<li><code>securesourcemanager. locations. list</code></li>
</ul>
<p><code>securesourcemanager. operations.*</code></p>
<ul>
<li><code>securesourcemanager. operations. cancel</code></li>
<li><code>securesourcemanager. operations. delete</code></li>
<li><code>securesourcemanager. operations. get</code></li>
<li><code>securesourcemanager. operations. list</code></li>
</ul>
<p><code>securesourcemanager. prcomments.*</code></p>
<ul>
<li><code>securesourcemanager. prcomments. create</code></li>
<li><code>securesourcemanager. prcomments. delete</code></li>
<li><code>securesourcemanager. prcomments. get</code></li>
<li><code>securesourcemanager. prcomments. list</code></li>
<li><code>securesourcemanager. prcomments. resolve</code></li>
<li><code>securesourcemanager. prcomments. unresolve</code></li>
<li><code>securesourcemanager. prcomments. update</code></li>
</ul>
<p><code>securesourcemanager. pullRequests.*</code></p>
<ul>
<li><code>securesourcemanager. pullRequests. close</code></li>
<li><code>securesourcemanager. pullRequests. create</code></li>
<li><code>securesourcemanager. pullRequests. get</code></li>
<li><code>securesourcemanager. pullRequests. list</code></li>
<li><code>securesourcemanager. pullRequests. listFileDiffs</code></li>
<li><code>securesourcemanager. pullRequests. merge</code></li>
<li><code>securesourcemanager. pullRequests. open</code></li>
<li><code>securesourcemanager. pullRequests. update</code></li>
</ul>
<p><code>securesourcemanager. repositories. approvePullRequests</code></p>
<p><code>securesourcemanager. repositories. create</code></p>
<p><code>securesourcemanager. repositories. delete</code></p>
<p><code>securesourcemanager. repositories. fetch</code></p>
<p><code>securesourcemanager. repositories. get</code></p>
<p><code>securesourcemanager. repositories. getIamPolicy</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. push</code></p>
<p><code>securesourcemanager. repositories. readIssues</code></p>
<p><code>securesourcemanager. repositories. readPullRequests</code></p>
<p><code>securesourcemanager. repositories. update</code></p>
<p><code>securesourcemanager. repositories. writeIssues</code></p>
<p><code>securesourcemanager. repositories. writePullRequests</code></p>
<p><code>securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code>securesourcemanager. sshkeys. create</code></li>
<li><code>securesourcemanager. sshkeys. createAny</code></li>
<li><code>securesourcemanager. sshkeys. delete</code></li>
<li><code>securesourcemanager. sshkeys. deleteAny</code></li>
<li><code>securesourcemanager. sshkeys. get</code></li>
<li><code>securesourcemanager. sshkeys. list</code></li>
<li><code>securesourcemanager. sshkeys. listAny</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Securesourcemanager Viewer
<p>( <code>roles/ securesourcemanager.viewer</code> )</p>
<p>Viewer role for securesourcemanager</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. branchRules. get</code></p>
<p><code>securesourcemanager. branchRules. list</code></p>
<p><code>securesourcemanager.hooks.get</code></p>
<p><code>securesourcemanager.hooks.list</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. instances. get</code></p>
<p><code>securesourcemanager. instances. getIamPolicy</code></p>
<p><code>securesourcemanager. instances. list</code></p>
<p><code>securesourcemanager. issuecomments. get</code></p>
<p><code>securesourcemanager. issuecomments. list</code></p>
<p><code>securesourcemanager.issues.get</code></p>
<p><code>securesourcemanager. issues. list</code></p>
<p><code>securesourcemanager. locations.*</code></p>
<ul>
<li><code>securesourcemanager. locations. get</code></li>
<li><code>securesourcemanager. locations. list</code></li>
</ul>
<p><code>securesourcemanager. operations. get</code></p>
<p><code>securesourcemanager. operations. list</code></p>
<p><code>securesourcemanager. prcomments. get</code></p>
<p><code>securesourcemanager. prcomments. list</code></p>
<p><code>securesourcemanager. pullRequests. get</code></p>
<p><code>securesourcemanager. pullRequests. list</code></p>
<p><code>securesourcemanager. pullRequests. listFileDiffs</code></p>
<p><code>securesourcemanager. repositories. fetch</code></p>
<p><code>securesourcemanager. repositories. get</code></p>
<p><code>securesourcemanager. repositories. getIamPolicy</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. readIssues</code></p>
<p><code>securesourcemanager. repositories. readPullRequests</code></p>
<p><code>securesourcemanager. sshkeys. get</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p>
<p><code>securesourcemanager. sshkeys. listAny</code></p></td>
</tr>
<tr class="even">
<td>Secure Source Manager Developer Connect Linker
<p>( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p>A Developer Connect Linker can link a Secure Source Manager instance to Developer Connect.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. instances. linkDeveloperConnect</code></p>
<p><code>securesourcemanager. operations. get</code></p>
<p><code>securesourcemanager. repositories. fetch</code></p>
<p><code>securesourcemanager. repositories. get</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. push</code></p></td>
</tr>
<tr class="odd">
<td>Secure Source Manager Instance Accessor
<p>( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p>An instance accessor can access an instance, but not necessarily create resources in the instance.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. sshkeys. create</code></p>
<p><code>securesourcemanager. sshkeys. delete</code></p>
<p><code>securesourcemanager. sshkeys. get</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p></td>
</tr>
<tr class="even">
<td>Secure Source Manager Instance Manager
<p>( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p>Read-write access to all Secure Source Manager resources (full control except for the ability to modify permissions).</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. instances. createRepository</code></p>
<p><code>securesourcemanager. instances. delete</code></p>
<p><code>securesourcemanager. instances. get</code></p>
<p><code>securesourcemanager. instances. list</code></p>
<p><code>securesourcemanager. locations.*</code></p>
<ul>
<li><code>securesourcemanager. locations. get</code></li>
<li><code>securesourcemanager. locations. list</code></li>
</ul>
<p><code>securesourcemanager. operations.*</code></p>
<ul>
<li><code>securesourcemanager. operations. cancel</code></li>
<li><code>securesourcemanager. operations. delete</code></li>
<li><code>securesourcemanager. operations. get</code></li>
<li><code>securesourcemanager. operations. list</code></li>
</ul>
<p><code>securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code>securesourcemanager. sshkeys. create</code></li>
<li><code>securesourcemanager. sshkeys. createAny</code></li>
<li><code>securesourcemanager. sshkeys. delete</code></li>
<li><code>securesourcemanager. sshkeys. deleteAny</code></li>
<li><code>securesourcemanager. sshkeys. get</code></li>
<li><code>securesourcemanager. sshkeys. list</code></li>
<li><code>securesourcemanager. sshkeys. listAny</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Secure Source Manager Instance Owner
<p>( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p>Full control over Secure Source Manager instances, including listing, creating, and deleting them. Also enables instance user management.</p></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. instances.*</code></p>
<ul>
<li><code>securesourcemanager. instances. access</code></li>
<li><code>securesourcemanager. instances. create</code></li>
<li><code>securesourcemanager. instances. createRepository</code></li>
<li><code>securesourcemanager. instances. delete</code></li>
<li><code>securesourcemanager. instances. get</code></li>
<li><code>securesourcemanager. instances. getIamPolicy</code></li>
<li><code>securesourcemanager. instances. linkDeveloperConnect</code></li>
<li><code>securesourcemanager. instances. list</code></li>
<li><code>securesourcemanager. instances. setIamPolicy</code></li>
</ul>
<p><code>securesourcemanager. locations.*</code></p>
<ul>
<li><code>securesourcemanager. locations. get</code></li>
<li><code>securesourcemanager. locations. list</code></li>
</ul>
<p><code>securesourcemanager. operations.*</code></p>
<ul>
<li><code>securesourcemanager. operations. cancel</code></li>
<li><code>securesourcemanager. operations. delete</code></li>
<li><code>securesourcemanager. operations. get</code></li>
<li><code>securesourcemanager. operations. list</code></li>
</ul>
<p><code>securesourcemanager.sshkeys.*</code></p>
<ul>
<li><code>securesourcemanager. sshkeys. create</code></li>
<li><code>securesourcemanager. sshkeys. createAny</code></li>
<li><code>securesourcemanager. sshkeys. delete</code></li>
<li><code>securesourcemanager. sshkeys. deleteAny</code></li>
<li><code>securesourcemanager. sshkeys. get</code></li>
<li><code>securesourcemanager. sshkeys. list</code></li>
<li><code>securesourcemanager. sshkeys. listAny</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Secure Source Manager Instance Repository Creator
<p>( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p>An instance repository creator can connect to a Cloud Git instance via IAP (HTTPS) and create repositories in the instance.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>securesourcemanager. instances. createRepository</code></p>
<p><code>securesourcemanager. sshkeys. create</code></p>
<p><code>securesourcemanager. sshkeys. delete</code></p>
<p><code>securesourcemanager. sshkeys. get</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p></td>
</tr>
<tr class="odd">
<td>Secure Source Manager Repository Admin
<p>( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p>A repoAdmin has the ability to CRUD a repository and its children as well as assign users to a repository. They can also set, get, or check IAM policies on the repository.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. branchRules.*</code></p>
<ul>
<li><code>securesourcemanager. branchRules. create</code></li>
<li><code>securesourcemanager. branchRules. delete</code></li>
<li><code>securesourcemanager. branchRules. get</code></li>
<li><code>securesourcemanager. branchRules. list</code></li>
<li><code>securesourcemanager. branchRules. update</code></li>
</ul>
<p><code>securesourcemanager.hooks.*</code></p>
<ul>
<li><code>securesourcemanager. hooks. create</code></li>
<li><code>securesourcemanager. hooks. delete</code></li>
<li><code>securesourcemanager.hooks.get</code></li>
<li><code>securesourcemanager.hooks.list</code></li>
<li><code>securesourcemanager. hooks. update</code></li>
</ul>
<p><code>securesourcemanager. issuecomments.*</code></p>
<ul>
<li><code>securesourcemanager. issuecomments. create</code></li>
<li><code>securesourcemanager. issuecomments. delete</code></li>
<li><code>securesourcemanager. issuecomments. get</code></li>
<li><code>securesourcemanager. issuecomments. list</code></li>
<li><code>securesourcemanager. issuecomments. update</code></li>
</ul>
<p><code>securesourcemanager.issues.*</code></p>
<ul>
<li><code>securesourcemanager. issues. close</code></li>
<li><code>securesourcemanager. issues. create</code></li>
<li><code>securesourcemanager. issues. delete</code></li>
<li><code>securesourcemanager.issues.get</code></li>
<li><code>securesourcemanager. issues. list</code></li>
<li><code>securesourcemanager. issues. open</code></li>
<li><code>securesourcemanager. issues. update</code></li>
</ul>
<p><code>securesourcemanager. prcomments.*</code></p>
<ul>
<li><code>securesourcemanager. prcomments. create</code></li>
<li><code>securesourcemanager. prcomments. delete</code></li>
<li><code>securesourcemanager. prcomments. get</code></li>
<li><code>securesourcemanager. prcomments. list</code></li>
<li><code>securesourcemanager. prcomments. resolve</code></li>
<li><code>securesourcemanager. prcomments. unresolve</code></li>
<li><code>securesourcemanager. prcomments. update</code></li>
</ul>
<p><code>securesourcemanager. pullRequests.*</code></p>
<ul>
<li><code>securesourcemanager. pullRequests. close</code></li>
<li><code>securesourcemanager. pullRequests. create</code></li>
<li><code>securesourcemanager. pullRequests. get</code></li>
<li><code>securesourcemanager. pullRequests. list</code></li>
<li><code>securesourcemanager. pullRequests. listFileDiffs</code></li>
<li><code>securesourcemanager. pullRequests. merge</code></li>
<li><code>securesourcemanager. pullRequests. open</code></li>
<li><code>securesourcemanager. pullRequests. update</code></li>
</ul>
<p><code>securesourcemanager. repositories.*</code></p>
<ul>
<li><code>securesourcemanager. repositories. approvePullRequests</code></li>
<li><code>securesourcemanager. repositories. create</code></li>
<li><code>securesourcemanager. repositories. delete</code></li>
<li><code>securesourcemanager. repositories. fetch</code></li>
<li><code>securesourcemanager. repositories. get</code></li>
<li><code>securesourcemanager. repositories. getIamPolicy</code></li>
<li><code>securesourcemanager. repositories. list</code></li>
<li><code>securesourcemanager. repositories. push</code></li>
<li><code>securesourcemanager. repositories. readIssues</code></li>
<li><code>securesourcemanager. repositories. readPullRequests</code></li>
<li><code>securesourcemanager. repositories. setIamPolicy</code></li>
<li><code>securesourcemanager. repositories. update</code></li>
<li><code>securesourcemanager. repositories. writeIssues</code></li>
<li><code>securesourcemanager. repositories. writePullRequests</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Secure Source Manager Repository Creator
<p>( <code>roles/ securesourcemanager.repoCreator</code> )</p>
<p>A repoCreator has access to create repostiory in a project, the creator will then become the repoAdmin on this repository.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. repositories. create</code></p></td>
</tr>
<tr class="odd">
<td>Secure Source Manager Repository Pull Request Approver
<p>( <code>roles/ securesourcemanager.repoPullRequestApprover</code> )</p>
<p>A pull request approver can approve pull requests in a repository.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. repositories. approvePullRequests</code></p></td>
</tr>
<tr class="even">
<td>Secure Source Manager Repository Reader
<p>( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p>A repoReader has read access to a particular repository, including its child components. They cannot create repositories, and do not manage IAM policies on the repository.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. branchRules. get</code></p>
<p><code>securesourcemanager. branchRules. list</code></p>
<p><code>securesourcemanager.hooks.get</code></p>
<p><code>securesourcemanager.hooks.list</code></p>
<p><code>securesourcemanager. issuecomments. get</code></p>
<p><code>securesourcemanager. issuecomments. list</code></p>
<p><code>securesourcemanager.issues.get</code></p>
<p><code>securesourcemanager. issues. list</code></p>
<p><code>securesourcemanager. prcomments. get</code></p>
<p><code>securesourcemanager. prcomments. list</code></p>
<p><code>securesourcemanager. pullRequests. get</code></p>
<p><code>securesourcemanager. pullRequests. list</code></p>
<p><code>securesourcemanager. pullRequests. listFileDiffs</code></p>
<p><code>securesourcemanager. repositories. fetch</code></p>
<p><code>securesourcemanager. repositories. get</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. readIssues</code></p>
<p><code>securesourcemanager. repositories. readPullRequests</code></p></td>
</tr>
<tr class="odd">
<td>Secure Source Manager Repository Writer
<p>( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p>A repoWriter has read/write access to a particular repository, including its child components. They cannot create repositories, and do not manage IAM policies on the repository.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. branchRules. get</code></p>
<p><code>securesourcemanager. branchRules. list</code></p>
<p><code>securesourcemanager.hooks.get</code></p>
<p><code>securesourcemanager.hooks.list</code></p>
<p><code>securesourcemanager. issuecomments.*</code></p>
<ul>
<li><code>securesourcemanager. issuecomments. create</code></li>
<li><code>securesourcemanager. issuecomments. delete</code></li>
<li><code>securesourcemanager. issuecomments. get</code></li>
<li><code>securesourcemanager. issuecomments. list</code></li>
<li><code>securesourcemanager. issuecomments. update</code></li>
</ul>
<p><code>securesourcemanager.issues.*</code></p>
<ul>
<li><code>securesourcemanager. issues. close</code></li>
<li><code>securesourcemanager. issues. create</code></li>
<li><code>securesourcemanager. issues. delete</code></li>
<li><code>securesourcemanager.issues.get</code></li>
<li><code>securesourcemanager. issues. list</code></li>
<li><code>securesourcemanager. issues. open</code></li>
<li><code>securesourcemanager. issues. update</code></li>
</ul>
<p><code>securesourcemanager. prcomments.*</code></p>
<ul>
<li><code>securesourcemanager. prcomments. create</code></li>
<li><code>securesourcemanager. prcomments. delete</code></li>
<li><code>securesourcemanager. prcomments. get</code></li>
<li><code>securesourcemanager. prcomments. list</code></li>
<li><code>securesourcemanager. prcomments. resolve</code></li>
<li><code>securesourcemanager. prcomments. unresolve</code></li>
<li><code>securesourcemanager. prcomments. update</code></li>
</ul>
<p><code>securesourcemanager. pullRequests.*</code></p>
<ul>
<li><code>securesourcemanager. pullRequests. close</code></li>
<li><code>securesourcemanager. pullRequests. create</code></li>
<li><code>securesourcemanager. pullRequests. get</code></li>
<li><code>securesourcemanager. pullRequests. list</code></li>
<li><code>securesourcemanager. pullRequests. listFileDiffs</code></li>
<li><code>securesourcemanager. pullRequests. merge</code></li>
<li><code>securesourcemanager. pullRequests. open</code></li>
<li><code>securesourcemanager. pullRequests. update</code></li>
</ul>
<p><code>securesourcemanager. repositories. fetch</code></p>
<p><code>securesourcemanager. repositories. get</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. push</code></p>
<p><code>securesourcemanager. repositories. readIssues</code></p>
<p><code>securesourcemanager. repositories. readPullRequests</code></p>
<p><code>securesourcemanager. repositories. writeIssues</code></p>
<p><code>securesourcemanager. repositories. writePullRequests</code></p></td>
</tr>
<tr class="even">
<td>Secure Source Manager SSH Key User
<p>( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p>An sshKeyUser can create SSH keys for themselves and list/delete SSH keys they own.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securesourcemanager. sshkeys. create</code></p>
<p><code>securesourcemanager. sshkeys. delete</code></p>
<p><code>securesourcemanager. sshkeys. get</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p></td>
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
<td>Secure Source Manager Service Agent
<p>( <code>roles/ securesourcemanager.serviceAgent</code> )</p>
<p>Gives Secure Source Manager service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>iam.serviceAccounts.signJwt</code></p>
<p><code>securesourcemanager. instances. access</code></p>
<p><code>serviceusage.services.use</code></p></td>
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
<td><code>securesourcemanager. branchRules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. branchRules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. branchRules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. branchRules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. branchRules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. hooks. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. hooks. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager.hooks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager.hooks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. hooks. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. instances. access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a> ( <code>roles/ securesourcemanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. instances. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. instances. createRepository</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. instances. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. instances. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. instances. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. instances. linkDeveloperConnect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. instances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. instances. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. issuecomments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issuecomments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. issuecomments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issuecomments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. issuecomments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issues. close</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. issues. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issues. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager.issues.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issues. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. issues. open</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. issues. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. prcomments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. prcomments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. prcomments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. prcomments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. prcomments. resolve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. prcomments. unresolve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. prcomments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. pullRequests. close</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. pullRequests. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. pullRequests. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. pullRequests. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. pullRequests. listFileDiffs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. pullRequests. merge</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. pullRequests. open</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. pullRequests. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. approvePullRequests</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code>roles/ securesourcemanager.repoPullRequestApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code>roles/ securesourcemanager.repoCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. push</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. readIssues</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. readPullRequests</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. repositories. writeIssues</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. repositories. writePullRequests</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. sshkeys. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. sshkeys. createAny</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. sshkeys. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. sshkeys. deleteAny</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. sshkeys. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>securesourcemanager. sshkeys. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securesourcemanager. sshkeys. listAny</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
