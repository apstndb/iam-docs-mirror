---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/pubsublite
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite
title: Pub/Sub Lite roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Pub/Sub Lite. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Pub/Sub Lite roles

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
<td><h4 id="pubsublite.admin" class="role-title add-link" data-text="Pub/Sub Lite Admin" tabindex="-1">Pub/Sub Lite Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p>Full access to topics, subscriptions and reservations.</p></td>
<td><p><code dir="ltr" translate="no">pubsublite.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsublite.  locations.  openKafkaStream</code></li>
<li><code dir="ltr" translate="no">pubsublite.operations.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.operations.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  reservations.  attachTopic</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.create</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  reservations.  listTopics</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.update</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.seek</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  setCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  subscribe</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  update</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeHeadCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeMessageStats</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeTimeCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.create</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  listSubscriptions</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.publish</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.subscribe</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.editor" class="role-title add-link" data-text="Pub/Sub Lite Editor" tabindex="-1">Pub/Sub Lite Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p>Modify topics, subscriptions and reservations, publish and consume messages.</p></td>
<td><p><code dir="ltr" translate="no">pubsublite.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsublite.  locations.  openKafkaStream</code></li>
<li><code dir="ltr" translate="no">pubsublite.operations.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.operations.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  reservations.  attachTopic</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.create</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  reservations.  listTopics</code></li>
<li><code dir="ltr" translate="no">pubsublite.reservations.update</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  create</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.subscriptions.seek</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  setCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  subscribe</code></li>
<li><code dir="ltr" translate="no">pubsublite.  subscriptions.  update</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeHeadCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeMessageStats</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  computeTimeCursor</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.create</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.delete</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.list</code></li>
<li><code dir="ltr" translate="no">pubsublite.  topics.  listSubscriptions</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.publish</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.subscribe</code></li>
<li><code dir="ltr" translate="no">pubsublite.topics.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.viewer" class="role-title add-link" data-text="Pub/Sub Lite Viewer" tabindex="-1">Pub/Sub Lite Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p>View topics, subscriptions and reservations.</p></td>
<td><p><code dir="ltr" translate="no">pubsublite.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsublite.operations.get</code></li>
<li><code dir="ltr" translate="no">pubsublite.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">pubsublite.reservations.get</code></p>
<p><code dir="ltr" translate="no">pubsublite.reservations.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.  reservations.  listTopics</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  listSubscriptions</code></p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.publisher" class="role-title add-link" data-text="Pub/Sub Lite Publisher" tabindex="-1">Pub/Sub Lite Publisher</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.publisher</code> )</p>
<p>Publish messages to a topic.</p></td>
<td><p><code dir="ltr" translate="no">pubsublite.  locations.  openKafkaStream</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.publish</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriber" class="role-title add-link" data-text="Pub/Sub Lite Subscriber" tabindex="-1">Pub/Sub Lite Subscriber</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Subscribe to and read messages from a topic.</p></td>
<td><p><code dir="ltr" translate="no">pubsublite.  locations.  openKafkaStream</code></p>
<p><code dir="ltr" translate="no">pubsublite.operations.get</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.seek</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  setCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  subscribe</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  computeHeadCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  computeMessageStats</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  computeTimeCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.subscribe</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="pubsublite.serviceAgent" class="role-title add-link" data-text="Pub/Sub Lite Service Agent" tabindex="-1">Pub/Sub Lite Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</p>
<p>Grants Pub/Sub Lite Service Agent access to project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  setCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  subscriptions.  subscribe</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  computeHeadCursor</code></p>
<p><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.subscribe</code></p></td>
</tr>
</tbody>
</table>

## Pub/Sub Lite permissions

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
<td><h4 id="pubsublite.locations.openKafkaStream" class="permission-name add-link" data-text="pubsublite.locations.openKafkaStream" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  locations.  openKafkaStream</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.operations.get" class="permission-name add-link" data-text="pubsublite.operations.get" tabindex="-1"><code dir="ltr" translate="no">pubsublite.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.operations.list" class="permission-name add-link" data-text="pubsublite.operations.list" tabindex="-1"><code dir="ltr" translate="no">pubsublite.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.reservations.attachTopic" class="permission-name add-link" data-text="pubsublite.reservations.attachTopic" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  reservations.  attachTopic</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.reservations.create" class="permission-name add-link" data-text="pubsublite.reservations.create" tabindex="-1"><code dir="ltr" translate="no">pubsublite.reservations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.reservations.delete" class="permission-name add-link" data-text="pubsublite.reservations.delete" tabindex="-1"><code dir="ltr" translate="no">pubsublite.reservations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.reservations.get" class="permission-name add-link" data-text="pubsublite.reservations.get" tabindex="-1"><code dir="ltr" translate="no">pubsublite.reservations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.reservations.list" class="permission-name add-link" data-text="pubsublite.reservations.list" tabindex="-1"><code dir="ltr" translate="no">pubsublite.reservations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.reservations.listTopics" class="permission-name add-link" data-text="pubsublite.reservations.listTopics" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  reservations.  listTopics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.reservations.update" class="permission-name add-link" data-text="pubsublite.reservations.update" tabindex="-1"><code dir="ltr" translate="no">pubsublite.reservations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriptions.create" class="permission-name add-link" data-text="pubsublite.subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.subscriptions.delete" class="permission-name add-link" data-text="pubsublite.subscriptions.delete" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriptions.get" class="permission-name add-link" data-text="pubsublite.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">pubsublite.subscriptions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.subscriptions.getCursor" class="permission-name add-link" data-text="pubsublite.subscriptions.getCursor" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  getCursor</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriptions.list" class="permission-name add-link" data-text="pubsublite.subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.subscriptions.seek" class="permission-name add-link" data-text="pubsublite.subscriptions.seek" tabindex="-1"><code dir="ltr" translate="no">pubsublite.subscriptions.seek</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriptions.setCursor" class="permission-name add-link" data-text="pubsublite.subscriptions.setCursor" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  setCursor</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.subscriptions.subscribe" class="permission-name add-link" data-text="pubsublite.subscriptions.subscribe" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  subscribe</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.subscriptions.update" class="permission-name add-link" data-text="pubsublite.subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  subscriptions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.computeHeadCursor" class="permission-name add-link" data-text="pubsublite.topics.computeHeadCursor" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  topics.  computeHeadCursor</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.computeMessageStats" class="permission-name add-link" data-text="pubsublite.topics.computeMessageStats" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  topics.  computeMessageStats</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.computeTimeCursor" class="permission-name add-link" data-text="pubsublite.topics.computeTimeCursor" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  topics.  computeTimeCursor</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.create" class="permission-name add-link" data-text="pubsublite.topics.create" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.delete" class="permission-name add-link" data-text="pubsublite.topics.delete" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.get" class="permission-name add-link" data-text="pubsublite.topics.get" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.getPartitions" class="permission-name add-link" data-text="pubsublite.topics.getPartitions" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  topics.  getPartitions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.list" class="permission-name add-link" data-text="pubsublite.topics.list" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.listSubscriptions" class="permission-name add-link" data-text="pubsublite.topics.listSubscriptions" tabindex="-1"><code dir="ltr" translate="no">pubsublite.  topics.  listSubscriptions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.publish" class="permission-name add-link" data-text="pubsublite.topics.publish" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.publish</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="pubsublite.topics.subscribe" class="permission-name add-link" data-text="pubsublite.topics.subscribe" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.subscribe</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="pubsublite.topics.update" class="permission-name add-link" data-text="pubsublite.topics.update" tabindex="-1"><code dir="ltr" translate="no">pubsublite.topics.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsublite.editor</code> )</p></td>
</tr>
</tbody>
</table>
