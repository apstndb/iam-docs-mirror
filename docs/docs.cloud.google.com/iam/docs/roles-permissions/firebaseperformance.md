---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance
title: Firebase Performance Monitoring roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Performance Monitoring. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Performance Monitoring roles

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
<td>Firebase Performance Reporting Admin
<p>( <code>roles/ firebaseperformance.admin</code> )</p>
<p>Full access to firebaseperformance resources.</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseperformance.*</code></p>
<ul>
<li><code>firebaseperformance. config. update</code></li>
<li><code>firebaseperformance.data.get</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Performance Reporting Viewer
<p>( <code>roles/ firebaseperformance.viewer</code> )</p>
<p>Read-only access to firebaseperformance resources.</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseperformance.data.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Performance Monitoring permissions

| Permission                            | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|---------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `firebaseperformance. config. update` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebase Performance Reporting Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin) ( `roles/ firebaseperformance.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Quality Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin) ( `roles/ firebase.qualityAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `firebaseperformance.data.get`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebase Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer) ( `roles/ firebase.viewer` ) [Firebase Performance Reporting Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin) ( `roles/ firebaseperformance.admin` ) [Firebase Performance Reporting Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer) ( `roles/ firebaseperformance.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Quality Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin) ( `roles/ firebase.qualityAdmin` ) [Firebase Quality Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer) ( `roles/ firebase.qualityViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
