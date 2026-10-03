---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mediaasset
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mediaasset
title: Media Asset roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Media Asset. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Media Asset roles

Media Asset offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Media Asset Service Agent
<p>( <code>roles/ mediaasset.serviceAgent</code> )</p>
<p>Downloads and uploads media files from and to customer Cloud Storage buckets.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>transcoder.jobs.create</code></p>
<p><code>transcoder.jobs.delete</code></p>
<p><code>transcoder.jobs.get</code></p></td>
</tr>
</tbody>
</table>

## Media Asset permissions

There are no IAM permissions for this service.
