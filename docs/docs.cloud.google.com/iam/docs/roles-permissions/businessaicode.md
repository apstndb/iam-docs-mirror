---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/businessaicode
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode
title: Business AI Code roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Business AI Code. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Business AI Code roles

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
<td><h4 id="businessaicode.user" class="role-title add-link" data-text="User role for Business AI Code API Beta" tabindex="-1">User role for Business AI Code API <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  businessaicode.user</code> )</p>
<p>A user who can use Business AI Code API</p></td>
<td><p><code dir="ltr" translate="no">businessaicode.*</code></p>
<ul>
<li><code dir="ltr" translate="no">businessaicode.  locations.  generateContent</code></li>
<li><code dir="ltr" translate="no">businessaicode.  locations.  queryConfiguration</code></li>
<li><code dir="ltr" translate="no">businessaicode.  locations.  sendTelemetry</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  exportMetrics</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  queryEffectiveSetting</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  queryEffectiveSettingBindings</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  licenses.  selfAssign</code></p></td>
</tr>
</tbody>
</table>

## Business AI Code permissions

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
<td><h4 id="businessaicode.locations.generateContent" class="permission-name add-link" data-text="businessaicode.locations.generateContent" tabindex="-1"><code dir="ltr" translate="no">businessaicode.  locations.  generateContent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user">User role for Business AI Code API</a> ( <code class="role-name" dir="ltr" translate="no">roles/  businessaicode.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="businessaicode.locations.queryConfiguration" class="permission-name add-link" data-text="businessaicode.locations.queryConfiguration" tabindex="-1"><code dir="ltr" translate="no">businessaicode.  locations.  queryConfiguration</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user">User role for Business AI Code API</a> ( <code class="role-name" dir="ltr" translate="no">roles/  businessaicode.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="businessaicode.locations.sendTelemetry" class="permission-name add-link" data-text="businessaicode.locations.sendTelemetry" tabindex="-1"><code dir="ltr" translate="no">businessaicode.  locations.  sendTelemetry</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.user">User role for Business AI Code API</a> ( <code class="role-name" dir="ltr" translate="no">roles/  businessaicode.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.podcastApiUser</code> )</p></td>
</tr>
</tbody>
</table>
