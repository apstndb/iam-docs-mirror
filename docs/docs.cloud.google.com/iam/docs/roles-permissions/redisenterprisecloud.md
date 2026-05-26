---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud
title: Redis Enterprise Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Redis Enterprise Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Redis Enterprise Cloud roles

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
<td><h4 id="redisenterprisecloud.admin" class="role-title add-link" data-text="Redis Enterprise Cloud Admin Beta" tabindex="-1">Redis Enterprise Cloud Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p>This role is managed by Redis Labs, not Google.</p></td>
<td><p><code dir="ltr" translate="no">gcp.redisenterprise.com/*</code></p>
<ul>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  create</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  delete</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  get</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  list</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  update</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  get</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  list</code></li>
<li><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="redisenterprisecloud.viewer" class="role-title add-link" data-text="Redis Enterprise Cloud Viewer Beta" tabindex="-1">Redis Enterprise Cloud Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p>This role is managed by Redis Labs, not Google.</p></td>
<td><p><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  get</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  list</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  get</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Redis Enterprise Cloud permissions

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
<td><h4 id="gcp.redisenterprise.com_databases.create" class="permission-name add-link" data-text="gcp.redisenterprise.com/databases.create" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gcp.redisenterprise.com_databases.delete" class="permission-name add-link" data-text="gcp.redisenterprise.com/databases.delete" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gcp.redisenterprise.com_databases.get" class="permission-name add-link" data-text="gcp.redisenterprise.com/databases.get" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gcp.redisenterprise.com_databases.list" class="permission-name add-link" data-text="gcp.redisenterprise.com/databases.list" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gcp.redisenterprise.com_databases.update" class="permission-name add-link" data-text="gcp.redisenterprise.com/databases.update" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gcp.redisenterprise.com_subscriptions.create" class="permission-name add-link" data-text="gcp.redisenterprise.com/subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gcp.redisenterprise.com_subscriptions.delete" class="permission-name add-link" data-text="gcp.redisenterprise.com/subscriptions.delete" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gcp.redisenterprise.com_subscriptions.get" class="permission-name add-link" data-text="gcp.redisenterprise.com/subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gcp.redisenterprise.com_subscriptions.list" class="permission-name add-link" data-text="gcp.redisenterprise.com/subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gcp.redisenterprise.com_subscriptions.update" class="permission-name add-link" data-text="gcp.redisenterprise.com/subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  redisenterprisecloud.admin</code> )</p></td>
</tr>
</tbody>
</table>
