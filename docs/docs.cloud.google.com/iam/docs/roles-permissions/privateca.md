---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/privateca
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/privateca
title: Certificate Authority Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Certificate Authority Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Certificate Authority Service roles

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
<td>CA Service Admin
<p>( <code>roles/ privateca.admin</code> )</p>
<p>Full access to all CA Service resources.</p></td>
<td><p><code>privateca.*</code></p>
<ul>
<li><code>privateca.caPools.create</code></li>
<li><code>privateca. caPools. createTagBinding</code></li>
<li><code>privateca.caPools.delete</code></li>
<li><code>privateca. caPools. deleteTagBinding</code></li>
<li><code>privateca.caPools.get</code></li>
<li><code>privateca.caPools.getIamPolicy</code></li>
<li><code>privateca.caPools.list</code></li>
<li><code>privateca. caPools. listEffectiveTags</code></li>
<li><code>privateca. caPools. listTagBindings</code></li>
<li><code>privateca.caPools.setIamPolicy</code></li>
<li><code>privateca.caPools.update</code></li>
<li><code>privateca.caPools.use</code></li>
<li><code>privateca. certificateAuthorities. create</code></li>
<li><code>privateca. certificateAuthorities. delete</code></li>
<li><code>privateca. certificateAuthorities. get</code></li>
<li><code>privateca. certificateAuthorities. getIamPolicy</code></li>
<li><code>privateca. certificateAuthorities. list</code></li>
<li><code>privateca. certificateAuthorities. setIamPolicy</code></li>
<li><code>privateca. certificateAuthorities. update</code></li>
<li><code>privateca. certificateRevocationLists. create</code></li>
<li><code>privateca. certificateRevocationLists. get</code></li>
<li><code>privateca. certificateRevocationLists. getIamPolicy</code></li>
<li><code>privateca. certificateRevocationLists. list</code></li>
<li><code>privateca. certificateRevocationLists. setIamPolicy</code></li>
<li><code>privateca. certificateRevocationLists. update</code></li>
<li><code>privateca. certificateTemplates. create</code></li>
<li><code>privateca. certificateTemplates. createTagBinding</code></li>
<li><code>privateca. certificateTemplates. delete</code></li>
<li><code>privateca. certificateTemplates. deleteTagBinding</code></li>
<li><code>privateca. certificateTemplates. get</code></li>
<li><code>privateca. certificateTemplates. getIamPolicy</code></li>
<li><code>privateca. certificateTemplates. list</code></li>
<li><code>privateca. certificateTemplates. listEffectiveTags</code></li>
<li><code>privateca. certificateTemplates. listTagBindings</code></li>
<li><code>privateca. certificateTemplates. setIamPolicy</code></li>
<li><code>privateca. certificateTemplates. update</code></li>
<li><code>privateca. certificateTemplates. use</code></li>
<li><code>privateca.certificates.create</code></li>
<li><code>privateca. certificates. createForSelf</code></li>
<li><code>privateca.certificates.get</code></li>
<li><code>privateca. certificates. getIamPolicy</code></li>
<li><code>privateca.certificates.list</code></li>
<li><code>privateca. certificates. setIamPolicy</code></li>
<li><code>privateca.certificates.update</code></li>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
<li><code>privateca.operations.cancel</code></li>
<li><code>privateca.operations.delete</code></li>
<li><code>privateca.operations.get</code></li>
<li><code>privateca.operations.list</code></li>
<li><code>privateca. reusableConfigs. create</code></li>
<li><code>privateca. reusableConfigs. delete</code></li>
<li><code>privateca.reusableConfigs.get</code></li>
<li><code>privateca. reusableConfigs. getIamPolicy</code></li>
<li><code>privateca.reusableConfigs.list</code></li>
<li><code>privateca. reusableConfigs. setIamPolicy</code></li>
<li><code>privateca. reusableConfigs. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.create</code></p></td>
</tr>
<tr class="even">
<td>CA Service Editor
<p>( <code>roles/ privateca.editor</code> )</p>
<p>Editor role for CA Service</p></td>
<td><p><code>privateca.caPools.create</code></p>
<p><code>privateca.caPools.delete</code></p>
<p><code>privateca.caPools.get</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca.caPools.update</code></p>
<p><code>privateca.caPools.use</code></p>
<p><code>privateca. certificateAuthorities. create</code></p>
<p><code>privateca. certificateAuthorities. delete</code></p>
<p><code>privateca. certificateAuthorities. get</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateAuthorities. update</code></p>
<p><code>privateca. certificateRevocationLists. create</code></p>
<p><code>privateca. certificateRevocationLists. get</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateRevocationLists. update</code></p>
<p><code>privateca. certificateTemplates. create</code></p>
<p><code>privateca. certificateTemplates. delete</code></p>
<p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. update</code></p>
<p><code>privateca. certificateTemplates. use</code></p>
<p><code>privateca.certificates.create</code></p>
<p><code>privateca. certificates. createForSelf</code></p>
<p><code>privateca.certificates.get</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.certificates.update</code></p>
<p><code>privateca.locations.*</code></p>
<ul>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
</ul>
<p><code>privateca.operations.*</code></p>
<ul>
<li><code>privateca.operations.cancel</code></li>
<li><code>privateca.operations.delete</code></li>
<li><code>privateca.operations.get</code></li>
<li><code>privateca.operations.list</code></li>
</ul>
<p><code>privateca. reusableConfigs. create</code></p>
<p><code>privateca. reusableConfigs. delete</code></p>
<p><code>privateca.reusableConfigs.get</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>privateca. reusableConfigs. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CA Service Viewer
<p>( <code>roles/ privateca.viewer</code> )</p>
<p>Viewer role for CA Service</p></td>
<td><p><code>privateca.caPools.get</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateAuthorities. get</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateRevocationLists. get</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. use</code></p>
<p><code>privateca.certificates.get</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.locations.*</code></p>
<ul>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
</ul>
<p><code>privateca.operations.get</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca.reusableConfigs.get</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>CA Service Auditor
<p>( <code>roles/ privateca.auditor</code> )</p>
<p>Read-only access to all CA Service resources.</p></td>
<td><p><code>privateca.caPools.get</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. certificateAuthorities. get</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateRevocationLists. get</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca.certificates.get</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.locations.*</code></p>
<ul>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
</ul>
<p><code>privateca.operations.get</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca.reusableConfigs.get</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CA Service Operation Manager
<p>( <code>roles/ privateca.caManager</code> )</p>
<p>Create and manage CAs, revoke certificates, create certificates templates, and read-only access for CA Service resources.</p></td>
<td><p><code>privateca.caPools.create</code></p>
<p><code>privateca. caPools. createTagBinding</code></p>
<p><code>privateca.caPools.delete</code></p>
<p><code>privateca. caPools. deleteTagBinding</code></p>
<p><code>privateca.caPools.get</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca.caPools.update</code></p>
<p><code>privateca. certificateAuthorities. create</code></p>
<p><code>privateca. certificateAuthorities. delete</code></p>
<p><code>privateca. certificateAuthorities. get</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateAuthorities. update</code></p>
<p><code>privateca. certificateRevocationLists. get</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateRevocationLists. update</code></p>
<p><code>privateca. certificateTemplates. create</code></p>
<p><code>privateca. certificateTemplates. createTagBinding</code></p>
<p><code>privateca. certificateTemplates. delete</code></p>
<p><code>privateca. certificateTemplates. deleteTagBinding</code></p>
<p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. update</code></p>
<p><code>privateca.certificates.get</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.certificates.update</code></p>
<p><code>privateca.locations.*</code></p>
<ul>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
</ul>
<p><code>privateca.operations.get</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca. reusableConfigs. create</code></p>
<p><code>privateca. reusableConfigs. delete</code></p>
<p><code>privateca.reusableConfigs.get</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>privateca. reusableConfigs. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.buckets.create</code></p></td>
</tr>
<tr class="even">
<td>CA Service Certificate Manager
<p>( <code>roles/ privateca.certificateManager</code> )</p>
<p>Create certificates and read-only access for CA Service resources.</p></td>
<td><p><code>privateca.caPools.get</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateAuthorities. get</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateRevocationLists. get</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>privateca.certificates.create</code></p>
<p><code>privateca.certificates.get</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.locations.*</code></p>
<ul>
<li><code>privateca.locations.get</code></li>
<li><code>privateca.locations.list</code></li>
</ul>
<p><code>privateca.operations.get</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca.reusableConfigs.get</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>CA Service Certificate Requester
<p>( <code>roles/ privateca.certificateRequester</code> )</p>
<p>Request certificates from CA Service.</p></td>
<td><p><code>privateca.certificates.create</code></p></td>
</tr>
<tr class="even">
<td>CA Service Pool Reader
<p>( <code>roles/ privateca.poolReader</code> )</p>
<p>Read CA Pools in CA Service.</p></td>
<td><p><code>privateca.caPools.get</code></p></td>
</tr>
<tr class="odd">
<td>CA Service Certificate Template User
<p>( <code>roles/ privateca.templateUser</code> )</p>
<p>Read, list and use certificate templates.</p></td>
<td><p><code>privateca. certificateTemplates. get</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. use</code></p></td>
</tr>
<tr class="even">
<td>CA Service Workload Certificate Requester
<p>( <code>roles/ privateca.workloadCertificateRequester</code> )</p>
<p>Request certificates from CA Service with caller's identity.</p></td>
<td><p><code>privateca. certificates. createForSelf</code></p></td>
</tr>
</tbody>
</table>

## Certificate Authority Service permissions

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
<td><code>privateca.caPools.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. caPools. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.caPools.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. caPools. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.caPools.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.poolReader">CA Service Pool Reader</a> ( <code>roles/ privateca.poolReader</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>privateca.caPools.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.caPools.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. caPools. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. caPools. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.caPools.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.caPools.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.caPools.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateAuthorities. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateAuthorities. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateAuthorities. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateAuthorities. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateAuthorities. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateAuthorities. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateAuthorities. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateRevocationLists. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateRevocationLists. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateRevocationLists. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateRevocationLists. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateRevocationLists. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateRevocationLists. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.templateUser">CA Service Certificate Template User</a> ( <code>roles/ privateca.templateUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.templateUser">CA Service Certificate Template User</a> ( <code>roles/ privateca.templateUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. certificateTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificateTemplates. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.templateUser">CA Service Certificate Template User</a> ( <code>roles/ privateca.templateUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.certificates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateRequester">CA Service Certificate Requester</a> ( <code>roles/ privateca.certificateRequester</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificates. createForSelf</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.workloadCertificateRequester">CA Service Workload Certificate Requester</a> ( <code>roles/ privateca.workloadCertificateRequester</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.certificates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. certificates. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.certificates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>privateca. certificates. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.certificates.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. reusableConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. reusableConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.reusableConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. reusableConfigs. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca.reusableConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p></td>
</tr>
<tr class="even">
<td><code>privateca. reusableConfigs. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>privateca. reusableConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p></td>
</tr>
</tbody>
</table>
