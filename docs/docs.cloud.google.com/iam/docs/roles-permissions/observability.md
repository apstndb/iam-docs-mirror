---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/observability
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/observability
title: Google Cloud Observability roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud Observability. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud Observability roles

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
<td><h4 id="observability.admin" class="role-title add-link" data-text="Observability Admin Beta" tabindex="-1">Observability Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p>Full access to Observability resources.</p></td>
<td><p><code dir="ltr" translate="no">observability.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  create</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  delete</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  get</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  update</code></li>
<li><code dir="ltr" translate="no">observability.buckets.create</code></li>
<li><code dir="ltr" translate="no">observability.buckets.delete</code></li>
<li><code dir="ltr" translate="no">observability.buckets.get</code></li>
<li><code dir="ltr" translate="no">observability.buckets.list</code></li>
<li><code dir="ltr" translate="no">observability.buckets.undelete</code></li>
<li><code dir="ltr" translate="no">observability.buckets.update</code></li>
<li><code dir="ltr" translate="no">observability.datasets.create</code></li>
<li><code dir="ltr" translate="no">observability.datasets.delete</code></li>
<li><code dir="ltr" translate="no">observability.datasets.get</code></li>
<li><code dir="ltr" translate="no">observability.datasets.list</code></li>
<li><code dir="ltr" translate="no">observability.  datasets.  undelete</code></li>
<li><code dir="ltr" translate="no">observability.datasets.update</code></li>
<li><code dir="ltr" translate="no">observability.links.create</code></li>
<li><code dir="ltr" translate="no">observability.links.delete</code></li>
<li><code dir="ltr" translate="no">observability.links.get</code></li>
<li><code dir="ltr" translate="no">observability.links.list</code></li>
<li><code dir="ltr" translate="no">observability.links.update</code></li>
<li><code dir="ltr" translate="no">observability.locations.get</code></li>
<li><code dir="ltr" translate="no">observability.locations.list</code></li>
<li><code dir="ltr" translate="no">observability.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">observability.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">observability.operations.get</code></li>
<li><code dir="ltr" translate="no">observability.operations.list</code></li>
<li><code dir="ltr" translate="no">observability.scopes.get</code></li>
<li><code dir="ltr" translate="no">observability.scopes.update</code></li>
<li><code dir="ltr" translate="no">observability.settings.get</code></li>
<li><code dir="ltr" translate="no">observability.settings.update</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  create</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  update</code></li>
<li><code dir="ltr" translate="no">observability.views.access</code></li>
<li><code dir="ltr" translate="no">observability.views.create</code></li>
<li><code dir="ltr" translate="no">observability.views.delete</code></li>
<li><code dir="ltr" translate="no">observability.views.get</code></li>
<li><code dir="ltr" translate="no">observability.views.list</code></li>
<li><code dir="ltr" translate="no">observability.views.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="observability.editor" class="role-title add-link" data-text="Observability Editor Beta" tabindex="-1">Observability Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p>Edit access to Observability resources.</p></td>
<td><p><code dir="ltr" translate="no">observability.analyticsViews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  create</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  delete</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  get</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.buckets.create</code></p>
<p><code dir="ltr" translate="no">observability.buckets.get</code></p>
<p><code dir="ltr" translate="no">observability.buckets.list</code></p>
<p><code dir="ltr" translate="no">observability.buckets.update</code></p>
<p><code dir="ltr" translate="no">observability.datasets.create</code></p>
<p><code dir="ltr" translate="no">observability.datasets.get</code></p>
<p><code dir="ltr" translate="no">observability.datasets.list</code></p>
<p><code dir="ltr" translate="no">observability.datasets.update</code></p>
<p><code dir="ltr" translate="no">observability.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.links.create</code></li>
<li><code dir="ltr" translate="no">observability.links.delete</code></li>
<li><code dir="ltr" translate="no">observability.links.get</code></li>
<li><code dir="ltr" translate="no">observability.links.list</code></li>
<li><code dir="ltr" translate="no">observability.links.update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.locations.get</code></li>
<li><code dir="ltr" translate="no">observability.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">observability.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">observability.operations.get</code></li>
<li><code dir="ltr" translate="no">observability.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.scopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.scopes.get</code></li>
<li><code dir="ltr" translate="no">observability.scopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.settings.get</code></li>
<li><code dir="ltr" translate="no">observability.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.traceScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  traceScopes.  create</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.views.create</code></p>
<p><code dir="ltr" translate="no">observability.views.delete</code></p>
<p><code dir="ltr" translate="no">observability.views.get</code></p>
<p><code dir="ltr" translate="no">observability.views.list</code></p>
<p><code dir="ltr" translate="no">observability.views.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.viewer" class="role-title add-link" data-text="Observability Viewer Beta" tabindex="-1">Observability Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p>Read only access to Observability resources.</p></td>
<td><p><code dir="ltr" translate="no">observability.  analyticsViews.  get</code></p>
<p><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></p>
<p><code dir="ltr" translate="no">observability.buckets.get</code></p>
<p><code dir="ltr" translate="no">observability.buckets.list</code></p>
<p><code dir="ltr" translate="no">observability.datasets.get</code></p>
<p><code dir="ltr" translate="no">observability.datasets.list</code></p>
<p><code dir="ltr" translate="no">observability.links.get</code></p>
<p><code dir="ltr" translate="no">observability.links.list</code></p>
<p><code dir="ltr" translate="no">observability.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.locations.get</code></li>
<li><code dir="ltr" translate="no">observability.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.operations.get</code></p>
<p><code dir="ltr" translate="no">observability.operations.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">observability.settings.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">observability.views.get</code></p>
<p><code dir="ltr" translate="no">observability.views.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="observability.analyticsUser" class="role-title add-link" data-text="Observability Analytics User Beta" tabindex="-1">Observability Analytics User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p>
<p>Grants permissions to use Cloud Observability Analytics.</p></td>
<td><p><code dir="ltr" translate="no">logging.queries.getShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.listShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">observability.analyticsViews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  create</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  delete</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  get</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></li>
<li><code dir="ltr" translate="no">observability.  analyticsViews.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.buckets.get</code></p>
<p><code dir="ltr" translate="no">observability.buckets.list</code></p>
<p><code dir="ltr" translate="no">observability.datasets.get</code></p>
<p><code dir="ltr" translate="no">observability.datasets.list</code></p>
<p><code dir="ltr" translate="no">observability.links.get</code></p>
<p><code dir="ltr" translate="no">observability.links.list</code></p>
<p><code dir="ltr" translate="no">observability.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.locations.get</code></li>
<li><code dir="ltr" translate="no">observability.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.operations.get</code></p>
<p><code dir="ltr" translate="no">observability.operations.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">observability.settings.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.get</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">observability.views.get</code></p>
<p><code dir="ltr" translate="no">observability.views.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.scopesEditor" class="role-title add-link" data-text="Observability Scopes Editor Beta" tabindex="-1">Observability Scopes Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p>
<p>Grants permission to view and edit Observability, Logging, Trace, and Monitoring scopes</p></td>
<td><p><code dir="ltr" translate="no">logging.logScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.logScopes.create</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.delete</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.get</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.list</code></li>
<li><code dir="ltr" translate="no">logging.logScopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.metricsScopes.link</code></p>
<p><code dir="ltr" translate="no">observability.scopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.scopes.get</code></li>
<li><code dir="ltr" translate="no">observability.scopes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">observability.traceScopes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">observability.  traceScopes.  create</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.get</code></li>
<li><code dir="ltr" translate="no">observability.traceScopes.list</code></li>
<li><code dir="ltr" translate="no">observability.  traceScopes.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="observability.viewAccessor" class="role-title add-link" data-text="Observability View Accessor Beta" tabindex="-1">Observability View Accessor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  observability.viewAccessor</code> )</p>
<p>Read only access to data defined by an Observability View.</p></td>
<td><p><code dir="ltr" translate="no">observability.views.access</code></p></td>
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
<td><h4 id="observability.serviceAgent" class="role-title add-link" data-text="Observability Service Agent" tabindex="-1">Observability Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  observability.serviceAgent</code> )</p>
<p>Grants Observability service account the ability to list, create and link datasets in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.link</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud Observability permissions

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
<td><h4 id="observability.analyticsViews.create" class="permission-name add-link" data-text="observability.analyticsViews.create" tabindex="-1"><code dir="ltr" translate="no">observability.  analyticsViews.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.analyticsViews.delete" class="permission-name add-link" data-text="observability.analyticsViews.delete" tabindex="-1"><code dir="ltr" translate="no">observability.  analyticsViews.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.analyticsViews.get" class="permission-name add-link" data-text="observability.analyticsViews.get" tabindex="-1"><code dir="ltr" translate="no">observability.  analyticsViews.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.analyticsViews.list" class="permission-name add-link" data-text="observability.analyticsViews.list" tabindex="-1"><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.analyticsViews.update" class="permission-name add-link" data-text="observability.analyticsViews.update" tabindex="-1"><code dir="ltr" translate="no">observability.  analyticsViews.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.buckets.create" class="permission-name add-link" data-text="observability.buckets.create" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.buckets.delete" class="permission-name add-link" data-text="observability.buckets.delete" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.buckets.get" class="permission-name add-link" data-text="observability.buckets.get" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.buckets.list" class="permission-name add-link" data-text="observability.buckets.list" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.buckets.undelete" class="permission-name add-link" data-text="observability.buckets.undelete" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.buckets.update" class="permission-name add-link" data-text="observability.buckets.update" tabindex="-1"><code dir="ltr" translate="no">observability.buckets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.datasets.create" class="permission-name add-link" data-text="observability.datasets.create" tabindex="-1"><code dir="ltr" translate="no">observability.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.datasets.delete" class="permission-name add-link" data-text="observability.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">observability.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.datasets.get" class="permission-name add-link" data-text="observability.datasets.get" tabindex="-1"><code dir="ltr" translate="no">observability.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.datasets.list" class="permission-name add-link" data-text="observability.datasets.list" tabindex="-1"><code dir="ltr" translate="no">observability.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.datasets.undelete" class="permission-name add-link" data-text="observability.datasets.undelete" tabindex="-1"><code dir="ltr" translate="no">observability.  datasets.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.datasets.update" class="permission-name add-link" data-text="observability.datasets.update" tabindex="-1"><code dir="ltr" translate="no">observability.datasets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.links.create" class="permission-name add-link" data-text="observability.links.create" tabindex="-1"><code dir="ltr" translate="no">observability.links.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.links.delete" class="permission-name add-link" data-text="observability.links.delete" tabindex="-1"><code dir="ltr" translate="no">observability.links.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.links.get" class="permission-name add-link" data-text="observability.links.get" tabindex="-1"><code dir="ltr" translate="no">observability.links.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.links.list" class="permission-name add-link" data-text="observability.links.list" tabindex="-1"><code dir="ltr" translate="no">observability.links.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="observability.links.update" class="permission-name add-link" data-text="observability.links.update" tabindex="-1"><code dir="ltr" translate="no">observability.links.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.locations.get" class="permission-name add-link" data-text="observability.locations.get" tabindex="-1"><code dir="ltr" translate="no">observability.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.locations.list" class="permission-name add-link" data-text="observability.locations.list" tabindex="-1"><code dir="ltr" translate="no">observability.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.operations.cancel" class="permission-name add-link" data-text="observability.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">observability.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.operations.delete" class="permission-name add-link" data-text="observability.operations.delete" tabindex="-1"><code dir="ltr" translate="no">observability.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.operations.get" class="permission-name add-link" data-text="observability.operations.get" tabindex="-1"><code dir="ltr" translate="no">observability.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.operations.list" class="permission-name add-link" data-text="observability.operations.list" tabindex="-1"><code dir="ltr" translate="no">observability.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.scopes.get" class="permission-name add-link" data-text="observability.scopes.get" tabindex="-1"><code dir="ltr" translate="no">observability.scopes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.privateLogViewer">Private Logs Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.privateLogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.viewer">Logs Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="observability.scopes.update" class="permission-name add-link" data-text="observability.scopes.update" tabindex="-1"><code dir="ltr" translate="no">observability.scopes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.settings.get" class="permission-name add-link" data-text="observability.settings.get" tabindex="-1"><code dir="ltr" translate="no">observability.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.settings.update" class="permission-name add-link" data-text="observability.settings.update" tabindex="-1"><code dir="ltr" translate="no">observability.settings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.traceScopes.create" class="permission-name add-link" data-text="observability.traceScopes.create" tabindex="-1"><code dir="ltr" translate="no">observability.  traceScopes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.traceScopes.delete" class="permission-name add-link" data-text="observability.traceScopes.delete" tabindex="-1"><code dir="ltr" translate="no">observability.  traceScopes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.traceScopes.get" class="permission-name add-link" data-text="observability.traceScopes.get" tabindex="-1"><code dir="ltr" translate="no">observability.traceScopes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.traceScopes.list" class="permission-name add-link" data-text="observability.traceScopes.list" tabindex="-1"><code dir="ltr" translate="no">observability.traceScopes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.traceScopes.update" class="permission-name add-link" data-text="observability.traceScopes.update" tabindex="-1"><code dir="ltr" translate="no">observability.  traceScopes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.scopesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.views.access" class="permission-name add-link" data-text="observability.views.access" tabindex="-1"><code dir="ltr" translate="no">observability.views.access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewAccessor">Observability View Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewAccessor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="observability.views.create" class="permission-name add-link" data-text="observability.views.create" tabindex="-1"><code dir="ltr" translate="no">observability.views.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.views.delete" class="permission-name add-link" data-text="observability.views.delete" tabindex="-1"><code dir="ltr" translate="no">observability.views.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.views.get" class="permission-name add-link" data-text="observability.views.get" tabindex="-1"><code dir="ltr" translate="no">observability.views.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="observability.views.list" class="permission-name add-link" data-text="observability.views.list" tabindex="-1"><code dir="ltr" translate="no">observability.views.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.analyticsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="observability.views.update" class="permission-name add-link" data-text="observability.views.update" tabindex="-1"><code dir="ltr" translate="no">observability.views.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  observability.editor</code> )</p></td>
</tr>
</tbody>
</table>
