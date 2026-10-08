---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/assuredoss
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss
title: Assured Open Source Software roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Assured Open Source Software. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Assured Open Source Software roles

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
<td>Assured OSS Admin
<p>( <code>roles/ assuredoss.admin</code> )</p>
<p>Access to use Assured OSS and manage configuration.</p></td>
<td><p><code>artifactregistry. attachments. get</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry. mavenartifacts.*</code></p>
<ul>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
</ul>
<p><code>artifactregistry.npmpackages.*</code></p>
<ul>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. projectconfigs. get</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.rules.get</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.*</code></p>
<ul>
<li><code>assuredoss.config.get</code></li>
<li><code>assuredoss.customers.create</code></li>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
<li><code>assuredoss.operations.cancel</code></li>
<li><code>assuredoss.operations.delete</code></li>
<li><code>assuredoss.operations.get</code></li>
<li><code>assuredoss.operations.list</code></li>
</ul>
<p><code>iam.serviceAccountKeys.create</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.listRevisions</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>resourcemanager. organizations. get</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Assured OSS Editor
<p>( <code>roles/ assuredoss.editor</code> )</p>
<p>Editor role for Assured OSS</p></td>
<td><p><code>assuredoss.config.get</code></p>
<p><code>assuredoss.locations.*</code></p>
<ul>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
</ul>
<p><code>assuredoss.metadata.*</code></p>
<ul>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
</ul>
<p><code>assuredoss.operations.get</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Assured OSS Viewer
<p>( <code>roles/ assuredoss.viewer</code> )</p>
<p>Viewer role for Assured OSS</p></td>
<td><p><code>assuredoss.config.get</code></p>
<p><code>assuredoss.locations.*</code></p>
<ul>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
</ul>
<p><code>assuredoss.metadata.*</code></p>
<ul>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
</ul>
<p><code>assuredoss.operations.get</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Assured OSS Project Admin <sup>Beta</sup>
<p>( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p>Access to use Assured OSS and manage configuration.</p></td>
<td><p><code>artifactregistry. attachments. get</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry. mavenartifacts.*</code></p>
<ul>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
</ul>
<p><code>artifactregistry.npmpackages.*</code></p>
<ul>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. projectconfigs. get</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.rules.get</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.*</code></p>
<ul>
<li><code>assuredoss.config.get</code></li>
<li><code>assuredoss.customers.create</code></li>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
<li><code>assuredoss.operations.cancel</code></li>
<li><code>assuredoss.operations.delete</code></li>
<li><code>assuredoss.operations.get</code></li>
<li><code>assuredoss.operations.list</code></li>
</ul>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.listRevisions</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>resourcemanager. organizations. get</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Assured OSS Reader
<p>( <code>roles/ assuredoss.reader</code> )</p>
<p>Access to use Assured OSS and view Assured OSS configuration.</p></td>
<td><p><code>artifactregistry. attachments. get</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry. mavenartifacts.*</code></p>
<ul>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
</ul>
<p><code>artifactregistry.npmpackages.*</code></p>
<ul>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. projectconfigs. get</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.rules.get</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.config.get</code></p>
<p><code>assuredoss.locations.*</code></p>
<ul>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
</ul>
<p><code>assuredoss.metadata.*</code></p>
<ul>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
</ul>
<p><code>assuredoss.operations.get</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.listRevisions</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>resourcemanager. organizations. get</code></p>
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
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Assured OSS User
<p>( <code>roles/ assuredoss.user</code> )</p>
<p>Access to use Assured OSS.</p></td>
<td><p><code>artifactregistry. attachments. get</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages.*</code></p>
<ul>
<li><code>artifactregistry. dockerimages. get</code></li>
<li><code>artifactregistry. dockerimages. list</code></li>
</ul>
<p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry.files.get</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry. mavenartifacts.*</code></p>
<ul>
<li><code>artifactregistry. mavenartifacts. get</code></li>
<li><code>artifactregistry. mavenartifacts. list</code></li>
</ul>
<p><code>artifactregistry.npmpackages.*</code></p>
<ul>
<li><code>artifactregistry. npmpackages. get</code></li>
<li><code>artifactregistry. npmpackages. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. projectconfigs. get</code></p>
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. exportArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.rules.get</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.locations.*</code></p>
<ul>
<li><code>assuredoss.locations.get</code></li>
<li><code>assuredoss.locations.list</code></li>
</ul>
<p><code>assuredoss.metadata.*</code></p>
<ul>
<li><code>assuredoss.metadata.get</code></li>
<li><code>assuredoss.metadata.list</code></li>
</ul>
<p><code>assuredoss.operations.get</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Assured Open Source Software permissions

| Permission                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `assuredoss.config.get`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                                                                                                                                                               |
| `assuredoss.customers.create`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `assuredoss.locations.get`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `assuredoss.locations.list`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) |
| `assuredoss.metadata.get`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `assuredoss.metadata.list`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) |
| `assuredoss.operations.cancel` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `assuredoss.operations.delete` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `assuredoss.operations.get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `assuredoss.operations.list`   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Assured OSS Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin) ( `roles/ assuredoss.admin` ) [Assured OSS Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor) ( `roles/ assuredoss.editor` ) [Assured OSS Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer) ( `roles/ assuredoss.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Assured OSS Project Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin) ( `roles/ assuredoss.projectAdmin` ) [Assured OSS Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader) ( `roles/ assuredoss.reader` ) [Assured OSS User](https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user) ( `roles/ assuredoss.user` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) |
