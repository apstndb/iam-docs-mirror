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
<td>Gemini Data Analytics Admin
<p>( <code>roles/ geminidataanalytics.admin</code> )</p>
<p>Admin role for Gemini Data Analytics</p></td>
<td><p><code>geminidataanalytics.*</code></p>
<ul>
<li><code>geminidataanalytics. dataAgents. chat</code></li>
<li><code>geminidataanalytics. dataAgents. create</code></li>
<li><code>geminidataanalytics. dataAgents. delete</code></li>
<li><code>geminidataanalytics. dataAgents. get</code></li>
<li><code>geminidataanalytics. dataAgents. getIamPolicy</code></li>
<li><code>geminidataanalytics. dataAgents. list</code></li>
<li><code>geminidataanalytics. dataAgents. setIamPolicy</code></li>
<li><code>geminidataanalytics. dataAgents. update</code></li>
<li><code>geminidataanalytics. locations. chat</code></li>
<li><code>geminidataanalytics. locations. get</code></li>
<li><code>geminidataanalytics. locations. list</code></li>
<li><code>geminidataanalytics. locations. useDataEngineeringAgent</code></li>
<li><code>geminidataanalytics. operations. cancel</code></li>
<li><code>geminidataanalytics. operations. delete</code></li>
<li><code>geminidataanalytics. operations. get</code></li>
<li><code>geminidataanalytics. operations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Gemini Data Analytics Viewer
<p>( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p>Viewer role for Gemini Data Analytics</p></td>
<td><p><code>geminidataanalytics. dataAgents. chat</code></p>
<p><code>geminidataanalytics. dataAgents. get</code></p>
<p><code>geminidataanalytics. dataAgents. getIamPolicy</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p>
<p><code>geminidataanalytics. locations.*</code></p>
<ul>
<li><code>geminidataanalytics. locations. chat</code></li>
<li><code>geminidataanalytics. locations. get</code></li>
<li><code>geminidataanalytics. locations. list</code></li>
<li><code>geminidataanalytics. locations. useDataEngineeringAgent</code></li>
</ul>
<p><code>geminidataanalytics. operations. get</code></p>
<p><code>geminidataanalytics. operations. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Data Analytics Data Agent Creator
<p>( <code>roles/ geminidataanalytics.dataAgentCreator</code> )</p>
<p>Create access to Gemini Data Analytics resources.</p></td>
<td><p><code>geminidataanalytics. dataAgents. create</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>geminidataanalytics. operations. get</code></p></td>
</tr>
<tr class="even">
<td>Gemini Data Analytics Data Agent Editor
<p>( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p>Chat and Edit access to Gemini Data Analytics resources.</p></td>
<td><p><code>geminidataanalytics. dataAgents. chat</code></p>
<p><code>geminidataanalytics. dataAgents. get</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p>
<p><code>geminidataanalytics. dataAgents. update</code></p>
<p><code>geminidataanalytics. operations. get</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Data Analytics Data Agent Owner
<p>( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p>Full access to existing Gemini Data Analytics resources.</p></td>
<td><p><code>geminidataanalytics. dataAgents. chat</code></p>
<p><code>geminidataanalytics. dataAgents. delete</code></p>
<p><code>geminidataanalytics. dataAgents. get</code></p>
<p><code>geminidataanalytics. dataAgents. getIamPolicy</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p>
<p><code>geminidataanalytics. dataAgents. setIamPolicy</code></p>
<p><code>geminidataanalytics. dataAgents. update</code></p>
<p><code>geminidataanalytics. locations. get</code></p>
<p><code>geminidataanalytics. locations. list</code></p>
<p><code>geminidataanalytics. operations.*</code></p>
<ul>
<li><code>geminidataanalytics. operations. cancel</code></li>
<li><code>geminidataanalytics. operations. delete</code></li>
<li><code>geminidataanalytics. operations. get</code></li>
<li><code>geminidataanalytics. operations. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Gemini Data Analytics Stateless Chat User
<p>( <code>roles/ geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p>Stateless access to Gemini Data Analytics chat.</p></td>
<td><p><code>geminidataanalytics. locations. chat</code></p>
<p><code>geminidataanalytics. locations. useDataEngineeringAgent</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Data Analytics Data Agent User
<p>( <code>roles/ geminidataanalytics.dataAgentUser</code> )</p>
<p>Chat and View access to Gemini Data Analytics resources.</p></td>
<td><p><code>geminidataanalytics. dataAgents. chat</code></p>
<p><code>geminidataanalytics. dataAgents. get</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p></td>
</tr>
<tr class="even">
<td>Gemini Data Analytics Data Agent Viewer
<p>( <code>roles/ geminidataanalytics.dataAgentViewer</code> )</p>
<p>Readonly access to Gemini Data Analytics resources.</p></td>
<td><p><code>geminidataanalytics. dataAgents. get</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Data Analytics Query Data User <sup>Beta</sup>
<p>( <code>roles/ geminidataanalytics.queryDataUser</code> )</p>
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
<td><code>geminidataanalytics. dataAgents. chat</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code>roles/ geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. dataAgents. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code>roles/ geminidataanalytics.dataAgentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. dataAgents. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. dataAgents. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code>roles/ geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentViewer">Gemini Data Analytics Data Agent Viewer</a> ( <code>roles/ geminidataanalytics.dataAgentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. dataAgents. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. dataAgents. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentUser">Gemini Data Analytics Data Agent User</a> ( <code>roles/ geminidataanalytics.dataAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentViewer">Gemini Data Analytics Data Agent Viewer</a> ( <code>roles/ geminidataanalytics.dataAgentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. dataAgents. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. dataAgents. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. locations. chat</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code>roles/ geminidataanalytics.dataAgentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentStatelessUser">Gemini Data Analytics Stateless Chat User</a> ( <code>roles/ geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. locations. useDataEngineeringAgent</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentStatelessUser">Gemini Data Analytics Stateless Chat User</a> ( <code>roles/ geminidataanalytics.dataAgentStatelessUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminidataanalytics. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentCreator">Gemini Data Analytics Data Agent Creator</a> ( <code>roles/ geminidataanalytics.dataAgentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentEditor">Gemini Data Analytics Data Agent Editor</a> ( <code>roles/ geminidataanalytics.dataAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminidataanalytics. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.dataAgentOwner">Gemini Data Analytics Data Agent Owner</a> ( <code>roles/ geminidataanalytics.dataAgentOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
