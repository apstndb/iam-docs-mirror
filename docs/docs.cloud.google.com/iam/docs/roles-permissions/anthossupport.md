---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/anthossupport
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport
title: Anthos Support roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Anthos Support. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Anthos Support roles

Anthos Support offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Anthos Support Service Agent
<p>( <code>roles/ anthossupport.serviceAgent</code> )</p>
<p>Gives the Anthos Support Service Agent access to Cloud Platform resource.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>gkehub.features.get</code></p>
<p><code>gkehub.features.getIamPolicy</code></p>
<p><code>gkehub.features.list</code></p>
<p><code>gkehub.fleet.get</code></p>
<p><code>gkehub.fleet.getFreeTrial</code></p>
<p><code>gkehub. gateway. generateCredentials</code></p>
<p><code>gkehub.gateway.get</code></p>
<p><code>gkehub.locations.*</code></p>
<ul>
<li><code>gkehub.locations.get</code></li>
<li><code>gkehub.locations.list</code></li>
</ul>
<p><code>gkehub.membershipbindings.get</code></p>
<p><code>gkehub.membershipbindings.list</code></p>
<p><code>gkehub.membershipfeatures.get</code></p>
<p><code>gkehub.membershipfeatures.list</code></p>
<p><code>gkehub. memberships. generateConnectManifest</code></p>
<p><code>gkehub.memberships.get</code></p>
<p><code>gkehub. memberships. getIamPolicy</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>gkehub.namespaces.get</code></p>
<p><code>gkehub.namespaces.list</code></p>
<p><code>gkehub.operations.get</code></p>
<p><code>gkehub.operations.list</code></p>
<p><code>gkehub.rbacrolebindings.get</code></p>
<p><code>gkehub.rbacrolebindings.list</code></p>
<p><code>gkehub.scopes.get</code></p>
<p><code>gkehub.scopes.list</code></p>
<p><code>gkehub. scopes. listBoundMemberships</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Anthos Support permissions

There are no IAM permissions for this service.
