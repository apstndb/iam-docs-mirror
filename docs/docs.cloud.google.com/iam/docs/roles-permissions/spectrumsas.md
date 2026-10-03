---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas
title: Spectrum Access System (SAS) roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Spectrum Access System (SAS). To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Spectrum Access System (SAS) roles

Spectrum Access System (SAS) offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Spectrum SAS Service Agent
<p>( <code>roles/ spectrumsas.serviceAgent</code> )</p>
<p>Gives Spectrum SAS Service Account access to enable analytics on behalf of users.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.attach</code></p>
<p><code>pubsub.schemas.commit</code></p>
<p><code>pubsub.schemas.create</code></p>
<p><code>pubsub.schemas.delete</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.listRevisions</code></p>
<p><code>pubsub.schemas.rollback</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.create</code></p>
<p><code>pubsub.snapshots.delete</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub.snapshots.seek</code></p>
<p><code>pubsub.snapshots.update</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub. topics. detachSubscription</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p></td>
</tr>
</tbody>
</table>

## Spectrum Access System (SAS) permissions

There are no IAM permissions for this service.
