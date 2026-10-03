---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/axt
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/axt
title: Access Transparency roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Access Transparency. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Access Transparency roles

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
<td>Access Transparency Admin
<p>( <code>roles/ axt.admin</code> )</p>
<p>Enable Access Transparency for Organization</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>axt.*</code></p>
<ul>
<li><code>axt.labels.get</code></li>
<li><code>axt.labels.set</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Access Transparency permissions

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
<td><code>axt.labels.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code>roles/ axt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>axt.labels.set</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code>roles/ axt.admin</code> )</p></td>
</tr>
</tbody>
</table>
