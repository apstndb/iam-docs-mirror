---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights
title: Timeseries Insights API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Timeseries Insights API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Timeseries Insights API roles

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
<td><h4 id="timeseriesinsights.admin" class="role-title add-link" data-text="Timeseriesinsights Admin Beta" tabindex="-1">Timeseriesinsights Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p>Admin role for timeseriesinsights</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  create</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  delete</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  update</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.viewer" class="role-title add-link" data-text="Timeseriesinsights Viewer Beta" tabindex="-1">Timeseriesinsights Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p>Viewer role for timeseriesinsights</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="timeseriesinsights.datasetsEditor" class="role-title add-link" data-text="Timeseries Insights DataSet Editor Beta" tabindex="-1">Timeseries Insights DataSet Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p>Edit access to DataSets.</p></td>
<td><p><code dir="ltr" translate="no">timeseriesinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  create</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  delete</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  update</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.datasetsOwner" class="role-title add-link" data-text="Timeseries Insights DataSet Owner Beta" tabindex="-1">Timeseries Insights DataSet Owner <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p>Full access to DataSets.</p></td>
<td><p><code dir="ltr" translate="no">timeseriesinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  create</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  delete</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  datasets.  update</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="timeseriesinsights.datasetsViewer" class="role-title add-link" data-text="Timeseries Insights DataSet Viewer Beta" tabindex="-1">Timeseries Insights DataSet Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p>
<p>Read-only access (List and Query) to DataSets.</p></td>
<td><p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></li>
<li><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Timeseries Insights API permissions

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
<td><h4 id="timeseriesinsights.datasets.create" class="permission-name add-link" data-text="timeseriesinsights.datasets.create" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.datasets.delete" class="permission-name add-link" data-text="timeseriesinsights.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="timeseriesinsights.datasets.evaluate" class="permission-name add-link" data-text="timeseriesinsights.datasets.evaluate" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  evaluate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsViewer">Timeseries Insights DataSet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.datasets.list" class="permission-name add-link" data-text="timeseriesinsights.datasets.list" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsViewer">Timeseries Insights DataSet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="timeseriesinsights.datasets.query" class="permission-name add-link" data-text="timeseriesinsights.datasets.query" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsViewer">Timeseries Insights DataSet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.datasets.update" class="permission-name add-link" data-text="timeseriesinsights.datasets.update" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  datasets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="timeseriesinsights.locations.get" class="permission-name add-link" data-text="timeseriesinsights.locations.get" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsViewer">Timeseries Insights DataSet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="timeseriesinsights.locations.list" class="permission-name add-link" data-text="timeseriesinsights.locations.list" tabindex="-1"><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.admin">Timeseriesinsights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.viewer">Timeseriesinsights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsEditor">Timeseries Insights DataSet Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsOwner">Timeseries Insights DataSet Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/timeseriesinsights#timeseriesinsights.datasetsViewer">Timeseries Insights DataSet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  timeseriesinsights.datasetsViewer</code> )</p></td>
</tr>
</tbody>
</table>
