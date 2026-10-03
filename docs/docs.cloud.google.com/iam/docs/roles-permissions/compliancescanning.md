---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning
title: Compliance Scanning roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Compliance Scanning. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Compliance Scanning roles

Compliance Scanning offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Compliance Scanning Service Agent
<p>( <code>roles/ compliancescanning.serviceAgent</code> )</p>
<p>Gives Compliance Scanning the access it needs to analyze containers and VMs for compliance and create occurrences using the Container Analysis API</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. dockerimages.*</code></p>
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
<p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. pythonpackages.*</code></p>
<ul>
<li><code>artifactregistry. pythonpackages. get</code></li>
<li><code>artifactregistry. pythonpackages. list</code></li>
</ul>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>artifactregistry. repositories. readViaVirtualRepository</code></p>
<p><code>artifactregistry.tags.get</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>containeranalysis. notes. attachOccurrence</code></p>
<p><code>containeranalysis.notes.create</code></p>
<p><code>containeranalysis.notes.delete</code></p>
<p><code>containeranalysis.notes.get</code></p>
<p><code>containeranalysis.notes.list</code></p>
<p><code>containeranalysis.notes.update</code></p>
<p><code>containeranalysis. occurrences. create</code></p>
<p><code>containeranalysis. occurrences. delete</code></p>
<p><code>containeranalysis. occurrences. get</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>containeranalysis. occurrences. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Compliance Scanning permissions

There are no IAM permissions for this service.
