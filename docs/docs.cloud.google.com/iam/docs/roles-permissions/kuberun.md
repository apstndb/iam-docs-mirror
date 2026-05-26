---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/kuberun
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun
title: Knative serving roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Knative serving. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Knative serving roles

Knative serving offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="kuberun.eventsControlPlaneServiceAgent" class="role-title add-link" data-text="KubeRun Events Control Plane Service Agent" tabindex="-1">KubeRun Events Control Plane Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  kuberun.eventsControlPlaneServiceAgent</code> )</p>
<p>Service account role used to setup authentication for the control plane used by KubeRun Events.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudscheduler.jobs.create</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.delete</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.create</code></p>
<p><code dir="ltr" translate="no">logging.sinks.delete</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="kuberun.eventsDataPlaneServiceAgent" class="role-title add-link" data-text="KubeRun Events Data Plane Service Agent" tabindex="-1">KubeRun Events Data Plane Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  kuberun.eventsDataPlaneServiceAgent</code> )</p>
<p>Service account role used to setup authentication for the data plane used by KubeRun Events.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudtrace.traces.patch</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Knative serving permissions

There are no IAM permissions for this service.
