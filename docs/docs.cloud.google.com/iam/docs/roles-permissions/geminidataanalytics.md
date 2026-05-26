---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics
title: Gemini Data Analytics roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Gemini Data Analytics. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Gemini Data Analytics roles

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
<td><h4 id="geminidataanalytics.dataAgentCreator" class="role-title add-link" data-text="Gemini Data Analytics Data Agent Creator" tabindex="-1">Gemini Data Analytics Data Agent Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentCreator</code> )</p>
<p>Create access to Gemini Data Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  create</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  chat</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  operations.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgentEditor" class="role-title add-link" data-text="Gemini Data Analytics Data Agent Editor" tabindex="-1">Gemini Data Analytics Data Agent Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p>Chat and Edit access to Gemini Data Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  chat</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  get</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  update</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  operations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.dataAgentOwner" class="role-title add-link" data-text="Gemini Data Analytics Data Agent Owner" tabindex="-1">Gemini Data Analytics Data Agent Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p>Full access to existing Gemini Data Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  chat</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  delete</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  get</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  update</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  get</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">geminidataanalytics.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">geminidataanalytics.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">geminidataanalytics.  operations.  get</code></li>
<li><code dir="ltr" translate="no">geminidataanalytics.  operations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgentStatelessUser" class="role-title add-link" data-text="Gemini Data Analytics Stateless Chat User" tabindex="-1">Gemini Data Analytics Stateless Chat User</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p>Stateless access to Gemini Data Analytics chat.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  locations.  chat</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  useDataEngineeringAgent</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.dataAgentUser" class="role-title add-link" data-text="Gemini Data Analytics Data Agent User" tabindex="-1">Gemini Data Analytics Data Agent User</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentUser</code> )</p>
<p>Chat and View access to Gemini Data Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  chat</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  get</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgentViewer" class="role-title add-link" data-text="Gemini Data Analytics Data Agent Viewer" tabindex="-1">Gemini Data Analytics Data Agent Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentViewer</code> )</p>
<p>Readonly access to Gemini Data Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  get</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.queryDataUser" class="role-title add-link" data-text="Gemini Data Analytics Query Data User Beta" tabindex="-1">Gemini Data Analytics Query Data User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  geminidataanalytics.queryDataUser</code> )</p>
<p>Access to use Gemini Data Analytics query data.</p></td>
<td></td>
</tr>
</tbody>
</table>

## Gemini Data Analytics permissions

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
<td><h4 id="geminidataanalytics.dataAgents.chat" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.chat" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  chat</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgents.create" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.create" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.dataAgents.delete" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.delete" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgents.get" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.get" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentViewer">Gemini Data Analytics Data Agent Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.dataAgents.getIamPolicy" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgents.list" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.list" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentViewer">Gemini Data Analytics Data Agent Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.dataAgents.setIamPolicy" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.dataAgents.update" class="permission-name add-link" data-text="geminidataanalytics.dataAgents.update" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.locations.chat" class="permission-name add-link" data-text="geminidataanalytics.locations.chat" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  locations.  chat</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentStatelessUser">Gemini Data Analytics Stateless Chat User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.locations.get" class="permission-name add-link" data-text="geminidataanalytics.locations.get" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.locations.list" class="permission-name add-link" data-text="geminidataanalytics.locations.list" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.locations.useDataEngineeringAgent" class="permission-name add-link" data-text="geminidataanalytics.locations.useDataEngineeringAgent" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  locations.  useDataEngineeringAgent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentStatelessUser">Gemini Data Analytics Stateless Chat User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.operations.cancel" class="permission-name add-link" data-text="geminidataanalytics.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.operations.delete" class="permission-name add-link" data-text="geminidataanalytics.operations.delete" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="geminidataanalytics.operations.get" class="permission-name add-link" data-text="geminidataanalytics.operations.get" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="geminidataanalytics.operations.list" class="permission-name add-link" data-text="geminidataanalytics.operations.list" tabindex="-1"><code dir="ltr" translate="no">geminidataanalytics.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
