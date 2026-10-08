---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager
title: Access Context Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Access Context Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Access Context Manager roles

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
<td>Access Context Manager Admin
<p>( <code>roles/ accesscontextmanager.admin</code> )</p>
<p>Admin role for Access Context Manager</p></td>
<td><p><code>accesscontextmanager.*</code></p>
<ul>
<li><code>accesscontextmanager. accessLevels. create</code></li>
<li><code>accesscontextmanager. accessLevels. delete</code></li>
<li><code>accesscontextmanager. accessLevels. get</code></li>
<li><code>accesscontextmanager. accessLevels. list</code></li>
<li><code>accesscontextmanager. accessLevels. replaceAll</code></li>
<li><code>accesscontextmanager. accessLevels. update</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. create</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. delete</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. get</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. list</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. update</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. create</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. delete</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. get</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. list</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. update</code></li>
<li><code>accesscontextmanager. policies. create</code></li>
<li><code>accesscontextmanager. policies. delete</code></li>
<li><code>accesscontextmanager. policies. get</code></li>
<li><code>accesscontextmanager. policies. getIamPolicy</code></li>
<li><code>accesscontextmanager. policies. list</code></li>
<li><code>accesscontextmanager. policies. setIamPolicy</code></li>
<li><code>accesscontextmanager. policies. update</code></li>
<li><code>accesscontextmanager. servicePerimeters. commit</code></li>
<li><code>accesscontextmanager. servicePerimeters. create</code></li>
<li><code>accesscontextmanager. servicePerimeters. delete</code></li>
<li><code>accesscontextmanager. servicePerimeters. get</code></li>
<li><code>accesscontextmanager. servicePerimeters. list</code></li>
<li><code>accesscontextmanager. servicePerimeters. replaceAll</code></li>
<li><code>accesscontextmanager. servicePerimeters. update</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Context Manager Editor
<p>( <code>roles/ accesscontextmanager.editor</code> )</p>
<p>Editor role for Access Context Manager</p></td>
<td><p><code>accesscontextmanager. accessLevels.*</code></p>
<ul>
<li><code>accesscontextmanager. accessLevels. create</code></li>
<li><code>accesscontextmanager. accessLevels. delete</code></li>
<li><code>accesscontextmanager. accessLevels. get</code></li>
<li><code>accesscontextmanager. accessLevels. list</code></li>
<li><code>accesscontextmanager. accessLevels. replaceAll</code></li>
<li><code>accesscontextmanager. accessLevels. update</code></li>
</ul>
<p><code>accesscontextmanager. authorizedOrgsDescs.*</code></p>
<ul>
<li><code>accesscontextmanager. authorizedOrgsDescs. create</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. delete</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. get</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. list</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. update</code></li>
</ul>
<p><code>accesscontextmanager. gcpUserAccessBindings.*</code></p>
<ul>
<li><code>accesscontextmanager. gcpUserAccessBindings. create</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. delete</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. get</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. list</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. update</code></li>
</ul>
<p><code>accesscontextmanager. policies. create</code></p>
<p><code>accesscontextmanager. policies. delete</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. policies. update</code></p>
<p><code>accesscontextmanager. servicePerimeters.*</code></p>
<ul>
<li><code>accesscontextmanager. servicePerimeters. commit</code></li>
<li><code>accesscontextmanager. servicePerimeters. create</code></li>
<li><code>accesscontextmanager. servicePerimeters. delete</code></li>
<li><code>accesscontextmanager. servicePerimeters. get</code></li>
<li><code>accesscontextmanager. servicePerimeters. list</code></li>
<li><code>accesscontextmanager. servicePerimeters. replaceAll</code></li>
<li><code>accesscontextmanager. servicePerimeters. update</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Access Context Manager Admin
<p>( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p>Full access to policies, access levels, access zones and authorized orgs descs.</p></td>
<td><p><code>accesscontextmanager. accessLevels.*</code></p>
<ul>
<li><code>accesscontextmanager. accessLevels. create</code></li>
<li><code>accesscontextmanager. accessLevels. delete</code></li>
<li><code>accesscontextmanager. accessLevels. get</code></li>
<li><code>accesscontextmanager. accessLevels. list</code></li>
<li><code>accesscontextmanager. accessLevels. replaceAll</code></li>
<li><code>accesscontextmanager. accessLevels. update</code></li>
</ul>
<p><code>accesscontextmanager. authorizedOrgsDescs.*</code></p>
<ul>
<li><code>accesscontextmanager. authorizedOrgsDescs. create</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. delete</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. get</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. list</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. update</code></li>
</ul>
<p><code>accesscontextmanager. policies.*</code></p>
<ul>
<li><code>accesscontextmanager. policies. create</code></li>
<li><code>accesscontextmanager. policies. delete</code></li>
<li><code>accesscontextmanager. policies. get</code></li>
<li><code>accesscontextmanager. policies. getIamPolicy</code></li>
<li><code>accesscontextmanager. policies. list</code></li>
<li><code>accesscontextmanager. policies. setIamPolicy</code></li>
<li><code>accesscontextmanager. policies. update</code></li>
</ul>
<p><code>accesscontextmanager. servicePerimeters.*</code></p>
<ul>
<li><code>accesscontextmanager. servicePerimeters. commit</code></li>
<li><code>accesscontextmanager. servicePerimeters. create</code></li>
<li><code>accesscontextmanager. servicePerimeters. delete</code></li>
<li><code>accesscontextmanager. servicePerimeters. get</code></li>
<li><code>accesscontextmanager. servicePerimeters. list</code></li>
<li><code>accesscontextmanager. servicePerimeters. replaceAll</code></li>
<li><code>accesscontextmanager. servicePerimeters. update</code></li>
</ul>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Context Manager Viewer
<p>( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p>Viewer role for Access Context Manager</p></td>
<td><p><code>accesscontextmanager. accessLevels. get</code></p>
<p><code>accesscontextmanager. accessLevels. list</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. get</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. list</code></p>
<p><code>accesscontextmanager. gcpUserAccessBindings. get</code></p>
<p><code>accesscontextmanager. gcpUserAccessBindings. list</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Access Binding Admin
<p>( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p>
<p>Create, edit, and change Cloud access bindings.</p></td>
<td><p><code>accesscontextmanager. gcpUserAccessBindings.*</code></p>
<ul>
<li><code>accesscontextmanager. gcpUserAccessBindings. create</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. delete</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. get</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. list</code></li>
<li><code>accesscontextmanager. gcpUserAccessBindings. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Access Binding Reader
<p>( <code>roles/ accesscontextmanager.gcpAccessReader</code> )</p>
<p>Read access to Cloud access bindings.</p></td>
<td><p><code>accesscontextmanager. gcpUserAccessBindings. get</code></p>
<p><code>accesscontextmanager. gcpUserAccessBindings. list</code></p></td>
</tr>
<tr class="odd">
<td>Access Context Manager Editor
<p>( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Edit access to policies. Create, edit, and change access levels, access zones and authorized orgs descs.</p></td>
<td><p><code>accesscontextmanager. accessLevels.*</code></p>
<ul>
<li><code>accesscontextmanager. accessLevels. create</code></li>
<li><code>accesscontextmanager. accessLevels. delete</code></li>
<li><code>accesscontextmanager. accessLevels. get</code></li>
<li><code>accesscontextmanager. accessLevels. list</code></li>
<li><code>accesscontextmanager. accessLevels. replaceAll</code></li>
<li><code>accesscontextmanager. accessLevels. update</code></li>
</ul>
<p><code>accesscontextmanager. authorizedOrgsDescs.*</code></p>
<ul>
<li><code>accesscontextmanager. authorizedOrgsDescs. create</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. delete</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. get</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. list</code></li>
<li><code>accesscontextmanager. authorizedOrgsDescs. update</code></li>
</ul>
<p><code>accesscontextmanager. policies. create</code></p>
<p><code>accesscontextmanager. policies. delete</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. policies. update</code></p>
<p><code>accesscontextmanager. servicePerimeters.*</code></p>
<ul>
<li><code>accesscontextmanager. servicePerimeters. commit</code></li>
<li><code>accesscontextmanager. servicePerimeters. create</code></li>
<li><code>accesscontextmanager. servicePerimeters. delete</code></li>
<li><code>accesscontextmanager. servicePerimeters. get</code></li>
<li><code>accesscontextmanager. servicePerimeters. list</code></li>
<li><code>accesscontextmanager. servicePerimeters. replaceAll</code></li>
<li><code>accesscontextmanager. servicePerimeters. update</code></li>
</ul>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Context Manager Reader
<p>( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p>Read access to policies, access levels, access zones and authorized orgs descs.</p></td>
<td><p><code>accesscontextmanager. accessLevels. get</code></p>
<p><code>accesscontextmanager. accessLevels. list</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. get</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. list</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>VPC Service Controls Troubleshooter Viewer
<p>( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p></td>
<td><p><code>accesscontextmanager. accessLevels. get</code></p>
<p><code>accesscontextmanager. accessLevels. list</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. get</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. list</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>iam.roles.get</code></p>
<p><code>logging.exclusions.get</code></p>
<p><code>logging.exclusions.list</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logMetrics.get</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.sinks.get</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>logging.usage.get</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Access Context Manager permissions

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
<td><code>accesscontextmanager. accessLevels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. accessLevels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. accessLevels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. accessLevels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. accessLevels. replaceAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. accessLevels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. authorizedOrgsDescs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. authorizedOrgsDescs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. authorizedOrgsDescs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. authorizedOrgsDescs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. authorizedOrgsDescs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. gcpUserAccessBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. gcpUserAccessBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. gcpUserAccessBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessReader">Cloud Access Binding Reader</a> ( <code>roles/ accesscontextmanager.gcpAccessReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. gcpUserAccessBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessReader">Cloud Access Binding Reader</a> ( <code>roles/ accesscontextmanager.gcpAccessReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. gcpUserAccessBindings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code>roles/ accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. policies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. policies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. policies. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. policies. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. policies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. policies. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. policies. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. servicePerimeters. commit</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. servicePerimeters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. servicePerimeters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. servicePerimeters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. servicePerimeters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Access Context Manager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwOrgRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accesscontextmanager. servicePerimeters. replaceAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>accesscontextmanager. servicePerimeters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
