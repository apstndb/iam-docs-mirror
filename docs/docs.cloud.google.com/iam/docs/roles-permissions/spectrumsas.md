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
<td><h4 id="spectrumsas.serviceAgent" class="role-title add-link" data-text="Spectrum SAS Service Agent" tabindex="-1">Spectrum SAS Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  spectrumsas.serviceAgent</code> )</p>
<p>Gives Spectrum SAS Service Account access to enable analytics on behalf of users.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.attach</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.commit</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.create</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.rollback</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.create</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.update</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
</tbody>
</table>

## Spectrum Access System (SAS) permissions

There are no IAM permissions for this service.
