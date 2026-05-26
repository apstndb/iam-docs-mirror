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
<td><h4 id="firebasemods.serviceAgent" class="role-title add-link" data-text="Firebase Extensions API Service Agent" tabindex="-1">Firebase Extensions API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</p>
<p>Grants Firebase Extensions API Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  packages.  delete</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudtasks.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtasks.queues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.queues.create</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.delete</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.pause</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.purge</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.resume</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtasks.tasks.create</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  cancelPreview</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  stop</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.manifests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  getType</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  listTypes</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.types.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.types.create</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.delete</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.list</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.types.update</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.channels.create</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Firebase Mods permissions

There are no IAM permissions for this service.
