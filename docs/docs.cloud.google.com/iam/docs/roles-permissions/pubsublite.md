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
<td>Pub/Sub Lite Admin
<p>( <code>roles/ pubsublite.admin</code> )</p>
<p>Full access to topics, subscriptions and reservations.</p></td>
<td><p><code>pubsublite.*</code></p>
<ul>
<li><code>pubsublite. locations. openKafkaStream</code></li>
<li><code>pubsublite.operations.get</code></li>
<li><code>pubsublite.operations.list</code></li>
<li><code>pubsublite. reservations. attachTopic</code></li>
<li><code>pubsublite.reservations.create</code></li>
<li><code>pubsublite.reservations.delete</code></li>
<li><code>pubsublite.reservations.get</code></li>
<li><code>pubsublite.reservations.list</code></li>
<li><code>pubsublite. reservations. listTopics</code></li>
<li><code>pubsublite.reservations.update</code></li>
<li><code>pubsublite. subscriptions. create</code></li>
<li><code>pubsublite. subscriptions. delete</code></li>
<li><code>pubsublite.subscriptions.get</code></li>
<li><code>pubsublite. subscriptions. getCursor</code></li>
<li><code>pubsublite.subscriptions.list</code></li>
<li><code>pubsublite.subscriptions.seek</code></li>
<li><code>pubsublite. subscriptions. setCursor</code></li>
<li><code>pubsublite. subscriptions. subscribe</code></li>
<li><code>pubsublite. subscriptions. update</code></li>
<li><code>pubsublite. topics. computeHeadCursor</code></li>
<li><code>pubsublite. topics. computeMessageStats</code></li>
<li><code>pubsublite. topics. computeTimeCursor</code></li>
<li><code>pubsublite.topics.create</code></li>
<li><code>pubsublite.topics.delete</code></li>
<li><code>pubsublite.topics.get</code></li>
<li><code>pubsublite. topics. getPartitions</code></li>
<li><code>pubsublite.topics.list</code></li>
<li><code>pubsublite. topics. listSubscriptions</code></li>
<li><code>pubsublite.topics.publish</code></li>
<li><code>pubsublite.topics.subscribe</code></li>
<li><code>pubsublite.topics.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Pub/Sub Lite Editor
<p>( <code>roles/ pubsublite.editor</code> )</p>
<p>Modify topics, subscriptions and reservations, publish and consume messages.</p></td>
<td><p><code>pubsublite.*</code></p>
<ul>
<li><code>pubsublite. locations. openKafkaStream</code></li>
<li><code>pubsublite.operations.get</code></li>
<li><code>pubsublite.operations.list</code></li>
<li><code>pubsublite. reservations. attachTopic</code></li>
<li><code>pubsublite.reservations.create</code></li>
<li><code>pubsublite.reservations.delete</code></li>
<li><code>pubsublite.reservations.get</code></li>
<li><code>pubsublite.reservations.list</code></li>
<li><code>pubsublite. reservations. listTopics</code></li>
<li><code>pubsublite.reservations.update</code></li>
<li><code>pubsublite. subscriptions. create</code></li>
<li><code>pubsublite. subscriptions. delete</code></li>
<li><code>pubsublite.subscriptions.get</code></li>
<li><code>pubsublite. subscriptions. getCursor</code></li>
<li><code>pubsublite.subscriptions.list</code></li>
<li><code>pubsublite.subscriptions.seek</code></li>
<li><code>pubsublite. subscriptions. setCursor</code></li>
<li><code>pubsublite. subscriptions. subscribe</code></li>
<li><code>pubsublite. subscriptions. update</code></li>
<li><code>pubsublite. topics. computeHeadCursor</code></li>
<li><code>pubsublite. topics. computeMessageStats</code></li>
<li><code>pubsublite. topics. computeTimeCursor</code></li>
<li><code>pubsublite.topics.create</code></li>
<li><code>pubsublite.topics.delete</code></li>
<li><code>pubsublite.topics.get</code></li>
<li><code>pubsublite. topics. getPartitions</code></li>
<li><code>pubsublite.topics.list</code></li>
<li><code>pubsublite. topics. listSubscriptions</code></li>
<li><code>pubsublite.topics.publish</code></li>
<li><code>pubsublite.topics.subscribe</code></li>
<li><code>pubsublite.topics.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Pub/Sub Lite Viewer
<p>( <code>roles/ pubsublite.viewer</code> )</p>
<p>View topics, subscriptions and reservations.</p></td>
<td><p><code>pubsublite.operations.*</code></p>
<ul>
<li><code>pubsublite.operations.get</code></li>
<li><code>pubsublite.operations.list</code></li>
</ul>
<p><code>pubsublite.reservations.get</code></p>
<p><code>pubsublite.reservations.list</code></p>
<p><code>pubsublite. reservations. listTopics</code></p>
<p><code>pubsublite.subscriptions.get</code></p>
<p><code>pubsublite. subscriptions. getCursor</code></p>
<p><code>pubsublite.subscriptions.list</code></p>
<p><code>pubsublite.topics.get</code></p>
<p><code>pubsublite. topics. getPartitions</code></p>
<p><code>pubsublite.topics.list</code></p>
<p><code>pubsublite. topics. listSubscriptions</code></p></td>
</tr>
<tr class="even">
<td>Pub/Sub Lite Publisher
<p>( <code>roles/ pubsublite.publisher</code> )</p>
<p>Publish messages to a topic.</p></td>
<td><p><code>pubsublite. locations. openKafkaStream</code></p>
<p><code>pubsublite. topics. getPartitions</code></p>
<p><code>pubsublite.topics.publish</code></p></td>
</tr>
<tr class="odd">
<td>Pub/Sub Lite Subscriber
<p>( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Subscribe to and read messages from a topic.</p></td>
<td><p><code>pubsublite. locations. openKafkaStream</code></p>
<p><code>pubsublite.operations.get</code></p>
<p><code>pubsublite. subscriptions. getCursor</code></p>
<p><code>pubsublite.subscriptions.seek</code></p>
<p><code>pubsublite. subscriptions. setCursor</code></p>
<p><code>pubsublite. subscriptions. subscribe</code></p>
<p><code>pubsublite. topics. computeHeadCursor</code></p>
<p><code>pubsublite. topics. computeMessageStats</code></p>
<p><code>pubsublite. topics. computeTimeCursor</code></p>
<p><code>pubsublite. topics. getPartitions</code></p>
<p><code>pubsublite.topics.subscribe</code></p></td>
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
<td>Pub/Sub Lite Service Agent
<p>( <code>roles/ pubsublite.serviceAgent</code> )</p>
<p>Grants Pub/Sub Lite Service Agent access to project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>pubsub.topics.publish</code></p>
<p><code>pubsublite.subscriptions.get</code></p>
<p><code>pubsublite. subscriptions. getCursor</code></p>
<p><code>pubsublite. subscriptions. setCursor</code></p>
<p><code>pubsublite. subscriptions. subscribe</code></p>
<p><code>pubsublite. topics. computeHeadCursor</code></p>
<p><code>pubsublite. topics. getPartitions</code></p>
<p><code>pubsublite.topics.publish</code></p>
<p><code>pubsublite.topics.subscribe</code></p></td>
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
<td><code>pubsublite. locations. openKafkaStream</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code>roles/ pubsublite.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. reservations. attachTopic</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.reservations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.reservations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.reservations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.reservations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite. reservations. listTopics</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.reservations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite. subscriptions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. subscriptions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.subscriptions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>pubsublite. subscriptions. getCursor</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>pubsublite.subscriptions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.subscriptions.seek</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite. subscriptions. setCursor</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>pubsublite. subscriptions. subscribe</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>pubsublite. subscriptions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. topics. computeHeadCursor</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>pubsublite. topics. computeMessageStats</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. topics. computeTimeCursor</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.topics.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite.topics.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.topics.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. topics. getPartitions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code>roles/ pubsublite.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>pubsublite.topics.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>pubsublite. topics. listSubscriptions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.viewer">Pub/Sub Lite Viewer</a> ( <code>roles/ pubsublite.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>pubsublite.topics.publish</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.publisher">Pub/Sub Lite Publisher</a> ( <code>roles/ pubsublite.publisher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a> ( <code>roles/ contentwarehouse.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>pubsublite.topics.subscribe</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.subscriber">Pub/Sub Lite Subscriber</a> ( <code>roles/ pubsublite.subscriber</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a> ( <code>roles/ pubsublite.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>pubsublite.topics.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.admin">Pub/Sub Lite Admin</a> ( <code>roles/ pubsublite.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.editor">Pub/Sub Lite Editor</a> ( <code>roles/ pubsublite.editor</code> )</p></td>
</tr>
</tbody>
</table>
