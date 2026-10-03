---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone
title: Secured Landing Zone roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Secured Landing Zone. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Secured Landing Zone roles

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
<td>Secured Landing Zone Admin <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.admin</code> )</p>
<p>Admin role for Secured Landing Zone</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securedlandingzone.*</code></p>
<ul>
<li><code>securedlandingzone. operations. get</code></li>
<li><code>securedlandingzone. overwatches. activate</code></li>
<li><code>securedlandingzone. overwatches. create</code></li>
<li><code>securedlandingzone. overwatches. delete</code></li>
<li><code>securedlandingzone. overwatches. get</code></li>
<li><code>securedlandingzone. overwatches. list</code></li>
<li><code>securedlandingzone. overwatches. suspend</code></li>
<li><code>securedlandingzone. overwatches. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Secured Landing Zone Viewer <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.viewer</code> )</p>
<p>Viewer role for Secured Landing Zone</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securedlandingzone. operations. get</code></p>
<p><code>securedlandingzone. overwatches. get</code></p>
<p><code>securedlandingzone. overwatches. list</code></p></td>
</tr>
<tr class="odd">
<td>SLZ BQDW Blueprint Organization Level Remediator <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Access to modify (remediate) resources in SLZ BQDW Blueprint at Organization.</p></td>
<td><p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. update</code></p></td>
</tr>
<tr class="even">
<td>SLZ BQDW Blueprint Project Level Remediator <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p>Access to modify (remediate) resources in SLZ BQDW Blueprint at Project.</p></td>
<td><p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.datasets.setIamPolicy</code></p>
<p><code>bigquery.datasets.update</code></p>
<p><code>cloudkms.cryptoKeys.get</code></p>
<p><code>cloudkms. cryptoKeys. getIamPolicy</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms. cryptoKeys. setIamPolicy</code></p>
<p><code>cloudkms.cryptoKeys.update</code></p>
<p><code>cloudkms.keyRings.getIamPolicy</code></p>
<p><code>cloudkms.keyRings.setIamPolicy</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub.topics.setIamPolicy</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>resourcemanager. projects. update</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.buckets.update</code></p></td>
</tr>
<tr class="odd">
<td>Overwatch Activator <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.overwatchActivator</code> )</p>
<p>This role can activate or suspend Overwatches</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securedlandingzone. overwatches. activate</code></p>
<p><code>securedlandingzone. overwatches. suspend</code></p></td>
</tr>
<tr class="even">
<td>Overwatch Admin <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.overwatchAdmin</code> )</p>
<p>Full access to Overwatches</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securedlandingzone.*</code></p>
<ul>
<li><code>securedlandingzone. operations. get</code></li>
<li><code>securedlandingzone. overwatches. activate</code></li>
<li><code>securedlandingzone. overwatches. create</code></li>
<li><code>securedlandingzone. overwatches. delete</code></li>
<li><code>securedlandingzone. overwatches. get</code></li>
<li><code>securedlandingzone. overwatches. list</code></li>
<li><code>securedlandingzone. overwatches. suspend</code></li>
<li><code>securedlandingzone. overwatches. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Overwatch Viewer <sup>Beta</sup>
<p>( <code>roles/ securedlandingzone.overwatchViewer</code> )</p>
<p>This role can view all properties of Overwatches</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securedlandingzone. operations. get</code></p>
<p><code>securedlandingzone. overwatches. get</code></p>
<p><code>securedlandingzone. overwatches. list</code></p></td>
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
<td>Secured Landing Zone Service Agent
<p>( <code>roles/ securedlandingzone.serviceAgent</code> )</p>
<p>Grants Secured Landing Zone service account permissions to manage resources in the customer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset. assets. exportOrgPolicy</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.feeds.create</code></p>
<p><code>cloudasset.feeds.delete</code></p>
<p><code>cloudasset.feeds.update</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub. topics. detachSubscription</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.setIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>securitycenter. assetsecuritymarks. update</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>securitycenter.findings.update</code></p>
<p><code>securitycenter.sources.list</code></p>
<p><code>securitycenter.sources.update</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Secured Landing Zone permissions

| Permission                                  | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `securedlandingzone. operations. get`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Secured Landing Zone Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.viewer) ( `roles/ securedlandingzone.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Overwatch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer) ( `roles/ securedlandingzone.overwatchViewer` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `securedlandingzone. overwatches. activate` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Overwatch Activator](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator) ( `roles/ securedlandingzone.overwatchActivator` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `securedlandingzone. overwatches. create`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `securedlandingzone. overwatches. delete`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `securedlandingzone. overwatches. get`      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Secured Landing Zone Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.viewer) ( `roles/ securedlandingzone.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Overwatch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer) ( `roles/ securedlandingzone.overwatchViewer` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `securedlandingzone. overwatches. list`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Secured Landing Zone Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.viewer) ( `roles/ securedlandingzone.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Overwatch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer) ( `roles/ securedlandingzone.overwatchViewer` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `securedlandingzone. overwatches. suspend`  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Overwatch Activator](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator) ( `roles/ securedlandingzone.overwatchActivator` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `securedlandingzone. overwatches. update`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Secured Landing Zone Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin) ( `roles/ securedlandingzone.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Overwatch Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin) ( `roles/ securedlandingzone.overwatchAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
