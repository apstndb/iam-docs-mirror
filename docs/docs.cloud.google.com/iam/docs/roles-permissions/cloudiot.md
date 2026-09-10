---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudiot
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudiot
title: Cloud IoT roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud IoT. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud IoT roles

Cloud IoT offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="cloudiot.serviceAgent" class="role-title add-link" data-text="Cloud IoT Core Service Agent" tabindex="-1">Cloud IoT Core Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudiot.serviceAgent</code> )</p>
<p>Grants the ability to manage Cloud IoT Core resources, including publishing data to Cloud Pub/Sub and writing device activity logs to Stackdriver. Warning: If this role is removed from the Cloud IoT service account, Cloud IoT Core will be unable to publish data or write device activity logs.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p></td>
</tr>
</tbody>
</table>

## Cloud IoT permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="cloudiottoken.tokensettings.get" class="permission-name add-link" data-text="cloudiottoken.tokensettings.get" tabindex="-1"><code dir="ltr" translate="no">cloudiottoken.  tokensettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudiottoken.tokensettings.update" class="permission-name add-link" data-text="cloudiottoken.tokensettings.update" tabindex="-1"><code dir="ltr" translate="no">cloudiottoken.  tokensettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p></td>
</tr>
</tbody>
</table>
