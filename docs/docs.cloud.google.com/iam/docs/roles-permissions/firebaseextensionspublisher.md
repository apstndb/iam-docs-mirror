---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher
title: Firebase Extensions Publisher roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Extensions Publisher. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Extensions Publisher roles

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
<td>Firebaseextensionspublisher Admin <sup>Beta</sup>
<p>( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p>Admin role for firebaseextensionspublisher</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseextensionspublisher.*</code></p>
<ul>
<li><code>firebaseextensionspublisher. extensions. create</code></li>
<li><code>firebaseextensionspublisher. extensions. delete</code></li>
<li><code>firebaseextensionspublisher. extensions. get</code></li>
<li><code>firebaseextensionspublisher. extensions. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebaseextensionspublisher Viewer <sup>Beta</sup>
<p>( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p>Viewer role for firebaseextensionspublisher</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseextensionspublisher. extensions. get</code></p>
<p><code>firebaseextensionspublisher. extensions. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Extensions Publisher - Extensions Admin <sup>Beta</sup>
<p>( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p>Fully manage Firebase Extensions</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseextensionspublisher.*</code></p>
<ul>
<li><code>firebaseextensionspublisher. extensions. create</code></li>
<li><code>firebaseextensionspublisher. extensions. delete</code></li>
<li><code>firebaseextensionspublisher. extensions. get</code></li>
<li><code>firebaseextensionspublisher. extensions. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Extensions Publisher - Extensions Viewer <sup>Beta</sup>
<p>( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p>View Firebase Extensions</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseextensionspublisher. extensions. get</code></p>
<p><code>firebaseextensionspublisher. extensions. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Extensions Publisher permissions

| Permission                                        | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `firebaseextensionspublisher. extensions. create` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebaseextensionspublisher Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin) ( `roles/ firebaseextensionspublisher.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Extensions Publisher - Extensions Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin) ( `roles/ firebaseextensionspublisher.extensionsAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `firebaseextensionspublisher. extensions. delete` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebaseextensionspublisher Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin) ( `roles/ firebaseextensionspublisher.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Extensions Publisher - Extensions Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin) ( `roles/ firebaseextensionspublisher.extensionsAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `firebaseextensionspublisher. extensions. get`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebase Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer) ( `roles/ firebase.viewer` ) [Firebaseextensionspublisher Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin) ( `roles/ firebaseextensionspublisher.admin` ) [Firebaseextensionspublisher Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer) ( `roles/ firebaseextensionspublisher.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Extensions Publisher - Extensions Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin) ( `roles/ firebaseextensionspublisher.extensionsAdmin` ) [Firebase Extensions Publisher - Extensions Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer) ( `roles/ firebaseextensionspublisher.extensionsViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `firebaseextensionspublisher. extensions. list`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebase Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer) ( `roles/ firebase.viewer` ) [Firebaseextensionspublisher Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin) ( `roles/ firebaseextensionspublisher.admin` ) [Firebaseextensionspublisher Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer) ( `roles/ firebaseextensionspublisher.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Firebase Extensions Publisher - Extensions Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin) ( `roles/ firebaseextensionspublisher.extensionsAdmin` ) [Firebase Extensions Publisher - Extensions Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer) ( `roles/ firebaseextensionspublisher.extensionsViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
