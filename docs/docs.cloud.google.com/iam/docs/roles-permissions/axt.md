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
<td><h4 id="axt.admin" class="role-title add-link" data-text="Access Transparency Admin" tabindex="-1">Access Transparency Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  axt.admin</code> )</p>
<p>Enable Access Transparency for Organization</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">axt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">axt.labels.get</code></li>
<li><code dir="ltr" translate="no">axt.labels.set</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="axt.labels.get" class="permission-name add-link" data-text="axt.labels.get" tabindex="-1"><code dir="ltr" translate="no">axt.labels.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  axt.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="axt.labels.set" class="permission-name add-link" data-text="axt.labels.set" tabindex="-1"><code dir="ltr" translate="no">axt.labels.set</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  axt.admin</code> )</p></td>
</tr>
</tbody>
</table>
