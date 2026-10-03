---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebasemods
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods
title: Firebase Mods roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Mods. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Mods roles

Firebase Mods offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Firebase Extensions API Service Agent
<p>( <code>roles/ firebasemods.serviceAgent</code> )</p>
<p>Grants Firebase Extensions API Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>appengine.applications.get</code></p>
<p><code>artifactregistry. packages. delete</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions. functions. setIamPolicy</code></p>
<p><code>cloudtasks.locations.*</code></p>
<ul>
<li><code>cloudtasks.locations.get</code></li>
<li><code>cloudtasks.locations.list</code></li>
</ul>
<p><code>cloudtasks.queues.*</code></p>
<ul>
<li><code>cloudtasks.queues.create</code></li>
<li><code>cloudtasks.queues.delete</code></li>
<li><code>cloudtasks.queues.get</code></li>
<li><code>cloudtasks.queues.getIamPolicy</code></li>
<li><code>cloudtasks.queues.list</code></li>
<li><code>cloudtasks.queues.pause</code></li>
<li><code>cloudtasks.queues.purge</code></li>
<li><code>cloudtasks.queues.resume</code></li>
<li><code>cloudtasks.queues.setIamPolicy</code></li>
<li><code>cloudtasks.queues.update</code></li>
</ul>
<p><code>cloudtasks.tasks.create</code></p>
<p><code>cloudtasks.tasks.fullView</code></p>
<p><code>deploymentmanager. compositeTypes.*</code></p>
<ul>
<li><code>deploymentmanager. compositeTypes. create</code></li>
<li><code>deploymentmanager. compositeTypes. delete</code></li>
<li><code>deploymentmanager. compositeTypes. get</code></li>
<li><code>deploymentmanager. compositeTypes. list</code></li>
<li><code>deploymentmanager. compositeTypes. update</code></li>
</ul>
<p><code>deploymentmanager. deployments. cancelPreview</code></p>
<p><code>deploymentmanager. deployments. create</code></p>
<p><code>deploymentmanager. deployments. delete</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. deployments. stop</code></p>
<p><code>deploymentmanager. deployments. update</code></p>
<p><code>deploymentmanager.manifests.*</code></p>
<ul>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
</ul>
<p><code>deploymentmanager.operations.*</code></p>
<ul>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
</ul>
<p><code>deploymentmanager.resources.*</code></p>
<ul>
<li><code>deploymentmanager. resources. get</code></li>
<li><code>deploymentmanager. resources. list</code></li>
</ul>
<p><code>deploymentmanager. typeProviders.*</code></p>
<ul>
<li><code>deploymentmanager. typeProviders. create</code></li>
<li><code>deploymentmanager. typeProviders. delete</code></li>
<li><code>deploymentmanager. typeProviders. get</code></li>
<li><code>deploymentmanager. typeProviders. getType</code></li>
<li><code>deploymentmanager. typeProviders. list</code></li>
<li><code>deploymentmanager. typeProviders. listTypes</code></li>
<li><code>deploymentmanager. typeProviders. update</code></li>
</ul>
<p><code>deploymentmanager.types.*</code></p>
<ul>
<li><code>deploymentmanager.types.create</code></li>
<li><code>deploymentmanager.types.delete</code></li>
<li><code>deploymentmanager.types.get</code></li>
<li><code>deploymentmanager.types.list</code></li>
<li><code>deploymentmanager.types.update</code></li>
</ul>
<p><code>eventarc.channels.create</code></p>
<p><code>eventarc.channels.delete</code></p>
<p><code>eventarc.channels.get</code></p>
<p><code>eventarc.channels.setIamPolicy</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. updateLiens</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.setIamPolicy</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Firebase Mods permissions

There are no IAM permissions for this service.
