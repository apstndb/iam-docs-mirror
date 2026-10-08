---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking
title: Subscription Linking roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Subscription Linking. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Subscription Linking roles

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
<td>Subscription Linking Admin
<p>( <code>roles/ readerrevenuesubscriptionlinking.admin</code> )</p>
<p>Full access to publication reader resources</p></td>
<td><p><code>readerrevenuesubscriptionlinking.*</code></p>
<ul>
<li><code>readerrevenuesubscriptionlinking. readerEntitlements. get</code></li>
<li><code>readerrevenuesubscriptionlinking. readerEntitlements. update</code></li>
<li><code>readerrevenuesubscriptionlinking. readers. delete</code></li>
<li><code>readerrevenuesubscriptionlinking. readers. get</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Subscription Linking Viewer
<p>( <code>roles/ readerrevenuesubscriptionlinking.viewer</code> )</p>
<p>This role can view all publication reader resources</p></td>
<td><p><code>readerrevenuesubscriptionlinking. readerEntitlements. get</code></p>
<p><code>readerrevenuesubscriptionlinking. readers. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Subscription Linking Entitlements Viewer
<p>( <code>roles/ readerrevenuesubscriptionlinking.entitlementsViewer</code> )</p>
<p>This role can view all publication reader entitlements</p></td>
<td><p><code>readerrevenuesubscriptionlinking. readerEntitlements. get</code></p></td>
</tr>
</tbody>
</table>

## Subscription Linking permissions

| Permission                                                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `readerrevenuesubscriptionlinking. readerEntitlements. get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Subscription Linking Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin) ( `roles/ readerrevenuesubscriptionlinking.admin` ) [Subscription Linking Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer) ( `roles/ readerrevenuesubscriptionlinking.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Subscription Linking Entitlements Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.entitlementsViewer) ( `roles/ readerrevenuesubscriptionlinking.entitlementsViewer` ) |
| `readerrevenuesubscriptionlinking. readerEntitlements. update` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Subscription Linking Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin) ( `roles/ readerrevenuesubscriptionlinking.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `readerrevenuesubscriptionlinking. readers. delete`            | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Subscription Linking Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin) ( `roles/ readerrevenuesubscriptionlinking.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `readerrevenuesubscriptionlinking. readers. get`               | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Subscription Linking Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin) ( `roles/ readerrevenuesubscriptionlinking.admin` ) [Subscription Linking Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer) ( `roles/ readerrevenuesubscriptionlinking.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                            |
