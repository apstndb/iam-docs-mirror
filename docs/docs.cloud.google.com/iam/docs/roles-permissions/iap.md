---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/iap
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/iap
title: Identity-Aware Proxy roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Identity-Aware Proxy. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Identity-Aware Proxy roles

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
<td><h4 id="iap.admin" class="role-title add-link" data-text="IAP Policy Admin" tabindex="-1">IAP Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p>Provides full access to Identity-Aware Proxy resources.</p></td>
<td><p><code dir="ltr" translate="no">iap.tunnel.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.tunnel.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.tunnel.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.tunnelLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.  tunnelLocations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.  tunnelLocations.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.tunnelZones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.tunnelZones.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.tunnelZones.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.web.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.web.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webServices.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iap.editor" class="role-title add-link" data-text="IAP Policy Editor" tabindex="-1">IAP Policy Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p>Editor role for IAP</p></td>
<td><p><code dir="ltr" translate="no">iap.projects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.projects.getSettings</code></li>
<li><code dir="ltr" translate="no">iap.projects.updateSettings</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.create</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.delete</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.get</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.update</code></p>
<p><code dir="ltr" translate="no">iap.web.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.web.updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getSettings</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webServices.updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.updateSettings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.egressor" class="role-title add-link" data-text="IAP-secured Egressor Beta" tabindex="-1">IAP-secured Egressor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iap.egressor</code> )</p>
<p>Egress to resources via Identity-Aware Proxy</p></td>
<td><p><code dir="ltr" translate="no">iap.  webServiceVersions.  egressViaIAP</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iap.httpsResourceAccessor" class="role-title add-link" data-text="IAP-secured Web App User" tabindex="-1">IAP-secured Web App User</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.httpsResourceAccessor</code> )</p>
<p>Provides permission to access HTTPS resources which use Identity-Aware Proxy.</p></td>
<td><p><code dir="ltr" translate="no">iap.  webServiceVersions.  accessViaIAP</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelResourceAccessor" class="role-title add-link" data-text="IAP-secured Tunnel User" tabindex="-1">IAP-secured Tunnel User</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.tunnelResourceAccessor</code> )</p>
<p>Access Tunnel resources which use Identity-Aware Proxy</p></td>
<td><p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  accessViaIAP</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  accessViaIAP</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iap.viewer" class="role-title add-link" data-text="IAP Policy Viewer" tabindex="-1">IAP Policy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p>Viewer role for IAP</p></td>
<td><p><code dir="ltr" translate="no">iap.projects.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.get</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p>
<p><code dir="ltr" translate="no">iap.web.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getSettings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.remediatorUser" class="role-title add-link" data-text="IAP-secured Resource Remediator User Beta" tabindex="-1">IAP-secured Resource Remediator User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iap.remediatorUser</code> )</p>
<p>Remediate IAP resource</p></td>
<td><p><code dir="ltr" translate="no">iap.tunnelDestGroups.remediate</code></p>
<p><code dir="ltr" translate="no">iap.tunnelinstances.remediate</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  remediate</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iap.settingsAdmin" class="role-title add-link" data-text="IAP Settings Admin" tabindex="-1">IAP Settings Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p>
<p>Administrator of IAP Settings.</p></td>
<td><p><code dir="ltr" translate="no">iap.projects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.projects.getSettings</code></li>
<li><code dir="ltr" translate="no">iap.projects.updateSettings</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.web.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.web.updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getSettings</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webServices.updateSettings</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getSettings</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.updateSettings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroupEditor" class="role-title add-link" data-text="IAP-secured Tunnel Destination Group Editor" tabindex="-1">IAP-secured Tunnel Destination Group Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p>
<p>Edit Tunnel Destination Group resources which use Identity-Aware Proxy</p></td>
<td><p><code dir="ltr" translate="no">iap.tunnelDestGroups.create</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.delete</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.get</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelDestGroupViewer" class="role-title add-link" data-text="IAP-secured Tunnel Destination Group Viewer" tabindex="-1">IAP-secured Tunnel Destination Group Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iap.tunnelDestGroupViewer</code> )</p>
<p>View Tunnel Destination Group resources which use Identity-Aware Proxy</p></td>
<td><p><code dir="ltr" translate="no">iap.tunnelDestGroups.get</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p></td>
</tr>
</tbody>
</table>

## Identity-Aware Proxy permissions

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
<td><h4 id="iap.projects.getSettings" class="permission-name add-link" data-text="iap.projects.getSettings" tabindex="-1"><code dir="ltr" translate="no">iap.projects.getSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.projects.updateSettings" class="permission-name add-link" data-text="iap.projects.updateSettings" tabindex="-1"><code dir="ltr" translate="no">iap.projects.updateSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnel.getIamPolicy" class="permission-name add-link" data-text="iap.tunnel.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.tunnel.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnel.setIamPolicy" class="permission-name add-link" data-text="iap.tunnel.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.tunnel.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroups.accessViaIAP" class="permission-name add-link" data-text="iap.tunnelDestGroups.accessViaIAP" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelDestGroups.  accessViaIAP</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelResourceAccessor">IAP-secured Tunnel User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelResourceAccessor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelDestGroups.create" class="permission-name add-link" data-text="iap.tunnelDestGroups.create" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupEditor">IAP-secured Tunnel Destination Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroups.delete" class="permission-name add-link" data-text="iap.tunnelDestGroups.delete" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupEditor">IAP-secured Tunnel Destination Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelDestGroups.get" class="permission-name add-link" data-text="iap.tunnelDestGroups.get" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupEditor">IAP-secured Tunnel Destination Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupViewer">IAP-secured Tunnel Destination Group Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroups.getIamPolicy" class="permission-name add-link" data-text="iap.tunnelDestGroups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelDestGroups.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelDestGroups.list" class="permission-name add-link" data-text="iap.tunnelDestGroups.list" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupEditor">IAP-secured Tunnel Destination Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupViewer">IAP-secured Tunnel Destination Group Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroups.remediate" class="permission-name add-link" data-text="iap.tunnelDestGroups.remediate" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.remediate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.remediatorUser">IAP-secured Resource Remediator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.remediatorUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelDestGroups.setIamPolicy" class="permission-name add-link" data-text="iap.tunnelDestGroups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelDestGroups.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelDestGroups.update" class="permission-name add-link" data-text="iap.tunnelDestGroups.update" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelDestGroups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelDestGroupEditor">IAP-secured Tunnel Destination Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelDestGroupEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelInstances.accessViaIAP" class="permission-name add-link" data-text="iap.tunnelInstances.accessViaIAP" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelInstances.  accessViaIAP</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.tunnelResourceAccessor">IAP-secured Tunnel User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.tunnelResourceAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelInstances.getIamPolicy" class="permission-name add-link" data-text="iap.tunnelInstances.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelInstances.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelInstances.setIamPolicy" class="permission-name add-link" data-text="iap.tunnelInstances.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelInstances.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelLocations.getIamPolicy" class="permission-name add-link" data-text="iap.tunnelLocations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelLocations.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelLocations.setIamPolicy" class="permission-name add-link" data-text="iap.tunnelLocations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  tunnelLocations.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelZones.getIamPolicy" class="permission-name add-link" data-text="iap.tunnelZones.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelZones.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.tunnelZones.setIamPolicy" class="permission-name add-link" data-text="iap.tunnelZones.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelZones.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.tunnelinstances.remediate" class="permission-name add-link" data-text="iap.tunnelinstances.remediate" tabindex="-1"><code dir="ltr" translate="no">iap.tunnelinstances.remediate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.remediatorUser">IAP-secured Resource Remediator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.remediatorUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.web.getIamPolicy" class="permission-name add-link" data-text="iap.web.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.web.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.web.getSettings" class="permission-name add-link" data-text="iap.web.getSettings" tabindex="-1"><code dir="ltr" translate="no">iap.web.getSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.web.setIamPolicy" class="permission-name add-link" data-text="iap.web.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.web.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.web.updateSettings" class="permission-name add-link" data-text="iap.web.updateSettings" tabindex="-1"><code dir="ltr" translate="no">iap.web.updateSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServiceVersions.accessViaIAP" class="permission-name add-link" data-text="iap.webServiceVersions.accessViaIAP" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  accessViaIAP</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.httpsResourceAccessor">IAP-secured Web App User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.httpsResourceAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webServiceVersions.egressViaIAP" class="permission-name add-link" data-text="iap.webServiceVersions.egressViaIAP" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  egressViaIAP</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.egressor">IAP-secured Egressor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.egressor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServiceVersions.getIamPolicy" class="permission-name add-link" data-text="iap.webServiceVersions.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webServiceVersions.getSettings" class="permission-name add-link" data-text="iap.webServiceVersions.getSettings" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  getSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServiceVersions.remediate" class="permission-name add-link" data-text="iap.webServiceVersions.remediate" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  remediate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.remediatorUser">IAP-secured Resource Remediator User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.remediatorUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webServiceVersions.setIamPolicy" class="permission-name add-link" data-text="iap.webServiceVersions.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServiceVersions.updateSettings" class="permission-name add-link" data-text="iap.webServiceVersions.updateSettings" tabindex="-1"><code dir="ltr" translate="no">iap.  webServiceVersions.  updateSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webServices.getIamPolicy" class="permission-name add-link" data-text="iap.webServices.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.webServices.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServices.getSettings" class="permission-name add-link" data-text="iap.webServices.getSettings" tabindex="-1"><code dir="ltr" translate="no">iap.webServices.getSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webServices.setIamPolicy" class="permission-name add-link" data-text="iap.webServices.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.webServices.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webServices.updateSettings" class="permission-name add-link" data-text="iap.webServices.updateSettings" tabindex="-1"><code dir="ltr" translate="no">iap.webServices.updateSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webTypes.getIamPolicy" class="permission-name add-link" data-text="iap.webTypes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.webTypes.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webTypes.getSettings" class="permission-name add-link" data-text="iap.webTypes.getSettings" tabindex="-1"><code dir="ltr" translate="no">iap.webTypes.getSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iap.webTypes.setIamPolicy" class="permission-name add-link" data-text="iap.webTypes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iap.webTypes.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.admin">IAP Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iap.webTypes.updateSettings" class="permission-name add-link" data-text="iap.webTypes.updateSettings" tabindex="-1"><code dir="ltr" translate="no">iap.webTypes.updateSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.settingsAdmin">IAP Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iap.settingsAdmin</code> )</p></td>
</tr>
</tbody>
</table>
