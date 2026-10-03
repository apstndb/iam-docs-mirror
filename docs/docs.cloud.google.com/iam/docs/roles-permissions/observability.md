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
<td>Observability Admin <sup>Beta</sup>
<p>( <code>roles/ observability.admin</code> )</p>
<p>Full access to Observability resources.</p></td>
<td><p><code>observability.*</code></p>
<ul>
<li><code>observability. analyticsViews. create</code></li>
<li><code>observability. analyticsViews. delete</code></li>
<li><code>observability. analyticsViews. get</code></li>
<li><code>observability. analyticsViews. list</code></li>
<li><code>observability. analyticsViews. update</code></li>
<li><code>observability.buckets.create</code></li>
<li><code>observability.buckets.delete</code></li>
<li><code>observability.buckets.get</code></li>
<li><code>observability.buckets.list</code></li>
<li><code>observability.buckets.undelete</code></li>
<li><code>observability.buckets.update</code></li>
<li><code>observability.datasets.create</code></li>
<li><code>observability.datasets.delete</code></li>
<li><code>observability.datasets.get</code></li>
<li><code>observability.datasets.list</code></li>
<li><code>observability. datasets. undelete</code></li>
<li><code>observability.datasets.update</code></li>
<li><code>observability.links.create</code></li>
<li><code>observability.links.delete</code></li>
<li><code>observability.links.get</code></li>
<li><code>observability.links.list</code></li>
<li><code>observability.links.update</code></li>
<li><code>observability.locations.get</code></li>
<li><code>observability.locations.list</code></li>
<li><code>observability. operations. cancel</code></li>
<li><code>observability. operations. delete</code></li>
<li><code>observability.operations.get</code></li>
<li><code>observability.operations.list</code></li>
<li><code>observability.scopes.get</code></li>
<li><code>observability.scopes.update</code></li>
<li><code>observability.settings.get</code></li>
<li><code>observability.settings.update</code></li>
<li><code>observability. traceScopes. create</code></li>
<li><code>observability. traceScopes. delete</code></li>
<li><code>observability.traceScopes.get</code></li>
<li><code>observability.traceScopes.list</code></li>
<li><code>observability. traceScopes. update</code></li>
<li><code>observability.views.access</code></li>
<li><code>observability.views.create</code></li>
<li><code>observability.views.delete</code></li>
<li><code>observability.views.get</code></li>
<li><code>observability.views.list</code></li>
<li><code>observability.views.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Observability Editor <sup>Beta</sup>
<p>( <code>roles/ observability.editor</code> )</p>
<p>Edit access to Observability resources.</p></td>
<td><p><code>observability.analyticsViews.*</code></p>
<ul>
<li><code>observability. analyticsViews. create</code></li>
<li><code>observability. analyticsViews. delete</code></li>
<li><code>observability. analyticsViews. get</code></li>
<li><code>observability. analyticsViews. list</code></li>
<li><code>observability. analyticsViews. update</code></li>
</ul>
<p><code>observability.buckets.create</code></p>
<p><code>observability.buckets.get</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.buckets.update</code></p>
<p><code>observability.datasets.create</code></p>
<p><code>observability.datasets.get</code></p>
<p><code>observability.datasets.list</code></p>
<p><code>observability.datasets.update</code></p>
<p><code>observability.links.*</code></p>
<ul>
<li><code>observability.links.create</code></li>
<li><code>observability.links.delete</code></li>
<li><code>observability.links.get</code></li>
<li><code>observability.links.list</code></li>
<li><code>observability.links.update</code></li>
</ul>
<p><code>observability.locations.*</code></p>
<ul>
<li><code>observability.locations.get</code></li>
<li><code>observability.locations.list</code></li>
</ul>
<p><code>observability.operations.*</code></p>
<ul>
<li><code>observability. operations. cancel</code></li>
<li><code>observability. operations. delete</code></li>
<li><code>observability.operations.get</code></li>
<li><code>observability.operations.list</code></li>
</ul>
<p><code>observability.scopes.*</code></p>
<ul>
<li><code>observability.scopes.get</code></li>
<li><code>observability.scopes.update</code></li>
</ul>
<p><code>observability.settings.*</code></p>
<ul>
<li><code>observability.settings.get</code></li>
<li><code>observability.settings.update</code></li>
</ul>
<p><code>observability.traceScopes.*</code></p>
<ul>
<li><code>observability. traceScopes. create</code></li>
<li><code>observability. traceScopes. delete</code></li>
<li><code>observability.traceScopes.get</code></li>
<li><code>observability.traceScopes.list</code></li>
<li><code>observability. traceScopes. update</code></li>
</ul>
<p><code>observability.views.create</code></p>
<p><code>observability.views.delete</code></p>
<p><code>observability.views.get</code></p>
<p><code>observability.views.list</code></p>
<p><code>observability.views.update</code></p></td>
</tr>
<tr class="odd">
<td>Observability Viewer <sup>Beta</sup>
<p>( <code>roles/ observability.viewer</code> )</p>
<p>Read only access to Observability resources.</p></td>
<td><p><code>observability. analyticsViews. get</code></p>
<p><code>observability. analyticsViews. list</code></p>
<p><code>observability.buckets.get</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.datasets.get</code></p>
<p><code>observability.datasets.list</code></p>
<p><code>observability.links.get</code></p>
<p><code>observability.links.list</code></p>
<p><code>observability.locations.*</code></p>
<ul>
<li><code>observability.locations.get</code></li>
<li><code>observability.locations.list</code></li>
</ul>
<p><code>observability.operations.get</code></p>
<p><code>observability.operations.list</code></p>
<p><code>observability.scopes.get</code></p>
<p><code>observability.settings.get</code></p>
<p><code>observability.traceScopes.get</code></p>
<p><code>observability.traceScopes.list</code></p>
<p><code>observability.views.get</code></p>
<p><code>observability.views.list</code></p></td>
</tr>
<tr class="even">
<td>Observability Analytics User <sup>Beta</sup>
<p>( <code>roles/ observability.analyticsUser</code> )</p>
<p>Grants permissions to use Cloud Observability Analytics.</p></td>
<td><p><code>logging.queries.getShared</code></p>
<p><code>logging.queries.listShared</code></p>
<p><code>logging.queries.usePrivate</code></p>
<p><code>observability.analyticsViews.*</code></p>
<ul>
<li><code>observability. analyticsViews. create</code></li>
<li><code>observability. analyticsViews. delete</code></li>
<li><code>observability. analyticsViews. get</code></li>
<li><code>observability. analyticsViews. list</code></li>
<li><code>observability. analyticsViews. update</code></li>
</ul>
<p><code>observability.buckets.get</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.datasets.get</code></p>
<p><code>observability.datasets.list</code></p>
<p><code>observability.links.get</code></p>
<p><code>observability.links.list</code></p>
<p><code>observability.locations.*</code></p>
<ul>
<li><code>observability.locations.get</code></li>
<li><code>observability.locations.list</code></li>
</ul>
<p><code>observability.operations.get</code></p>
<p><code>observability.operations.list</code></p>
<p><code>observability.scopes.get</code></p>
<p><code>observability.settings.get</code></p>
<p><code>observability.traceScopes.get</code></p>
<p><code>observability.traceScopes.list</code></p>
<p><code>observability.views.get</code></p>
<p><code>observability.views.list</code></p></td>
</tr>
<tr class="odd">
<td>Observability Scopes Editor <sup>Beta</sup>
<p>( <code>roles/ observability.scopesEditor</code> )</p>
<p>Grants permission to view and edit Observability, Logging, Trace, and Monitoring scopes</p></td>
<td><p><code>logging.logScopes.*</code></p>
<ul>
<li><code>logging.logScopes.create</code></li>
<li><code>logging.logScopes.delete</code></li>
<li><code>logging.logScopes.get</code></li>
<li><code>logging.logScopes.list</code></li>
<li><code>logging.logScopes.update</code></li>
</ul>
<p><code>monitoring.metricsScopes.link</code></p>
<p><code>observability.scopes.*</code></p>
<ul>
<li><code>observability.scopes.get</code></li>
<li><code>observability.scopes.update</code></li>
</ul>
<p><code>observability.traceScopes.*</code></p>
<ul>
<li><code>observability. traceScopes. create</code></li>
<li><code>observability. traceScopes. delete</code></li>
<li><code>observability.traceScopes.get</code></li>
<li><code>observability.traceScopes.list</code></li>
<li><code>observability. traceScopes. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Observability View Accessor <sup>Beta</sup>
<p>( <code>roles/ observability.viewAccessor</code> )</p>
<p>Read only access to data defined by an Observability View.</p></td>
<td><p><code>observability.views.access</code></p></td>
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
<td>Observability Service Agent
<p>( <code>roles/ observability.serviceAgent</code> )</p>
<p>Grants Observability service account the ability to list, create and link datasets in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.link</code></p></td>
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
<td><code>observability. analyticsViews. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability. analyticsViews. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability. analyticsViews. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability. analyticsViews. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability. analyticsViews. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.buckets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.buckets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.buckets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.buckets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.buckets.undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.buckets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.datasets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.datasets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.datasets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.datasets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability. datasets. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.datasets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.links.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>observability.links.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>observability.links.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>observability.links.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>observability.links.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>observability.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>observability.scopes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code>roles/ logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.privateLogViewer">Private Logs Viewer</a> ( <code>roles/ logging.privateLogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.viewer">Logs Viewer</a> ( <code>roles/ logging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code>roles/ logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code>roles/ telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code>roles/ telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>observability.scopes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.settings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.settings.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability. traceScopes. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability. traceScopes. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.traceScopes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.traceScopes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability. traceScopes. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.views.access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewAccessor">Observability View Accessor</a> ( <code>roles/ observability.viewAccessor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>observability.views.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.views.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.views.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>observability.views.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.viewer">Observability Viewer</a> ( <code>roles/ observability.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.analyticsUser">Observability Analytics User</a> ( <code>roles/ observability.analyticsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>observability.views.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.admin">Observability Admin</a> ( <code>roles/ observability.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.editor">Observability Editor</a> ( <code>roles/ observability.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
