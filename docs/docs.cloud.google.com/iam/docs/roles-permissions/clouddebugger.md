---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger
title: Cloud Debugger roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Debugger. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Debugger roles

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
<td><h4 id="clouddebugger.agent" class="role-title add-link" data-text="Cloud Debugger Agent Beta" tabindex="-1">Cloud Debugger Agent <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  clouddebugger.agent</code> )</p>
<p>Provides permissions to register the debug target, read active breakpoints, and report breakpoint results.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  listActive</code></p>
<p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  update</code></p>
<p><code dir="ltr" translate="no">clouddebugger.debuggees.create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddebugger.user" class="role-title add-link" data-text="Cloud Debugger User Beta" tabindex="-1">Cloud Debugger User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p>
<p>Provides permissions to create, view, list, and delete breakpoints (snapshots &amp; logpoints) as well as list debug targets (debuggees).</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  create</code></p>
<p><code dir="ltr" translate="no">clouddebugger.  breakpoints.  delete</code></p>
<p><code dir="ltr" translate="no">clouddebugger.breakpoints.get</code></p>
<p><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.debuggees.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Debugger permissions

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
<td><h4 id="clouddebugger.breakpoints.create" class="permission-name add-link" data-text="clouddebugger.breakpoints.create" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.  breakpoints.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.user">Cloud Debugger User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddebugger.breakpoints.delete" class="permission-name add-link" data-text="clouddebugger.breakpoints.delete" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.  breakpoints.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.user">Cloud Debugger User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddebugger.breakpoints.get" class="permission-name add-link" data-text="clouddebugger.breakpoints.get" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.breakpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.user">Cloud Debugger User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddebugger.breakpoints.list" class="permission-name add-link" data-text="clouddebugger.breakpoints.list" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.agent">Cloud Debugger Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.user">Cloud Debugger User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="clouddebugger.breakpoints.listActive" class="permission-name add-link" data-text="clouddebugger.breakpoints.listActive" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.  breakpoints.  listActive</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.agent">Cloud Debugger Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="clouddebugger.breakpoints.update" class="permission-name add-link" data-text="clouddebugger.breakpoints.update" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.  breakpoints.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.agent">Cloud Debugger Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="clouddebugger.debuggees.create" class="permission-name add-link" data-text="clouddebugger.debuggees.create" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.debuggees.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.agent">Cloud Debugger Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="clouddebugger.debuggees.list" class="permission-name add-link" data-text="clouddebugger.debuggees.list" tabindex="-1"><code dir="ltr" translate="no">clouddebugger.debuggees.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddebugger#clouddebugger.user">Cloud Debugger User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddebugger.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
</tbody>
</table>
