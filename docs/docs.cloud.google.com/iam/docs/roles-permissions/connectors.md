---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/connectors
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/connectors
title: Connectors roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Connectors. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Connectors roles

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
<td>Connector Admin
<p>( <code>roles/ connectors.admin</code> )</p>
<p>Full access to all resources of Connectors Service.</p></td>
<td><p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors.connections.create</code></p>
<p><code>connectors.connections.delete</code></p>
<p><code>connectors. connections. executeSqlQuery</code></p>
<p><code>connectors. connections. generateOpenAPISpec</code></p>
<p><code>connectors.connections.get</code></p>
<p><code>connectors. connections. getConnectionSchemaMetadata</code></p>
<p><code>connectors. connections. getIamPolicy</code></p>
<p><code>connectors. connections. getRuntimeActionSchema</code></p>
<p><code>connectors. connections. getRuntimeEntitySchema</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors. connections. setIamPolicy</code></p>
<p><code>connectors.connections.update</code></p>
<p><code>connectors.connectors.*</code></p>
<ul>
<li><code>connectors.connectors.get</code></li>
<li><code>connectors.connectors.list</code></li>
</ul>
<p><code>connectors. customConnectorVersions.*</code></p>
<ul>
<li><code>connectors. customConnectorVersions. create</code></li>
<li><code>connectors. customConnectorVersions. delete</code></li>
<li><code>connectors. customConnectorVersions. get</code></li>
<li><code>connectors. customConnectorVersions. getIamPolicy</code></li>
<li><code>connectors. customConnectorVersions. list</code></li>
<li><code>connectors. customConnectorVersions. setIamPolicy</code></li>
<li><code>connectors. customConnectorVersions. update</code></li>
</ul>
<p><code>connectors.customConnectors.*</code></p>
<ul>
<li><code>connectors. customConnectors. create</code></li>
<li><code>connectors. customConnectors. delete</code></li>
<li><code>connectors. customConnectors. get</code></li>
<li><code>connectors. customConnectors. getIamPolicy</code></li>
<li><code>connectors. customConnectors. list</code></li>
<li><code>connectors. customConnectors. setIamPolicy</code></li>
<li><code>connectors. customConnectors. update</code></li>
</ul>
<p><code>connectors. endpointAttachments.*</code></p>
<ul>
<li><code>connectors. endpointAttachments. create</code></li>
<li><code>connectors. endpointAttachments. delete</code></li>
<li><code>connectors. endpointAttachments. get</code></li>
<li><code>connectors. endpointAttachments. getIamPolicy</code></li>
<li><code>connectors. endpointAttachments. list</code></li>
<li><code>connectors. endpointAttachments. setIamPolicy</code></li>
<li><code>connectors. endpointAttachments. update</code></li>
</ul>
<p><code>connectors.entities.*</code></p>
<ul>
<li><code>connectors.entities.create</code></li>
<li><code>connectors.entities.delete</code></li>
<li><code>connectors. entities. deleteEntitiesWithConditions</code></li>
<li><code>connectors.entities.get</code></li>
<li><code>connectors.entities.list</code></li>
<li><code>connectors.entities.update</code></li>
<li><code>connectors. entities. updateEntitiesWithConditions</code></li>
</ul>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors. eventSubscriptions.*</code></p>
<ul>
<li><code>connectors. eventSubscriptions. create</code></li>
<li><code>connectors. eventSubscriptions. delete</code></li>
<li><code>connectors. eventSubscriptions. get</code></li>
<li><code>connectors. eventSubscriptions. list</code></li>
<li><code>connectors. eventSubscriptions. update</code></li>
</ul>
<p><code>connectors.eventtypes.*</code></p>
<ul>
<li><code>connectors.eventtypes.get</code></li>
<li><code>connectors.eventtypes.list</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.*</code></p>
<ul>
<li><code>connectors.managedZones.create</code></li>
<li><code>connectors.managedZones.delete</code></li>
<li><code>connectors.managedZones.get</code></li>
<li><code>connectors. managedZones. getIamPolicy</code></li>
<li><code>connectors.managedZones.list</code></li>
<li><code>connectors. managedZones. setIamPolicy</code></li>
<li><code>connectors.managedZones.update</code></li>
</ul>
<p><code>connectors.operations.*</code></p>
<ul>
<li><code>connectors.operations.cancel</code></li>
<li><code>connectors.operations.delete</code></li>
<li><code>connectors.operations.get</code></li>
<li><code>connectors.operations.list</code></li>
</ul>
<p><code>connectors.providers.*</code></p>
<ul>
<li><code>connectors.providers.get</code></li>
<li><code>connectors.providers.list</code></li>
</ul>
<p><code>connectors.regionalSettings.*</code></p>
<ul>
<li><code>connectors. regionalSettings. get</code></li>
<li><code>connectors. regionalSettings. update</code></li>
</ul>
<p><code>connectors.runtimeconfig.get</code></p>
<p><code>connectors. schemaMetadata. refresh</code></p>
<p><code>connectors.settings.*</code></p>
<ul>
<li><code>connectors.settings.get</code></li>
<li><code>connectors.settings.update</code></li>
</ul>
<p><code>connectors.versions.*</code></p>
<ul>
<li><code>connectors.versions.get</code></li>
<li><code>connectors.versions.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>secretmanager. secrets. getIamPolicy</code></p></td>
</tr>
<tr class="even">
<td>Connectors Editor
<p>( <code>roles/ connectors.editor</code> )</p>
<p>Editor role for connectors</p></td>
<td><p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors.connections.create</code></p>
<p><code>connectors.connections.delete</code></p>
<p><code>connectors. connections. executeSqlQuery</code></p>
<p><code>connectors. connections. generateOpenAPISpec</code></p>
<p><code>connectors.connections.get</code></p>
<p><code>connectors. connections. getConnectionSchemaMetadata</code></p>
<p><code>connectors. connections. getIamPolicy</code></p>
<p><code>connectors. connections. getRuntimeActionSchema</code></p>
<p><code>connectors. connections. getRuntimeEntitySchema</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors. connections. listenEvent</code></p>
<p><code>connectors.connections.update</code></p>
<p><code>connectors.connectors.*</code></p>
<ul>
<li><code>connectors.connectors.get</code></li>
<li><code>connectors.connectors.list</code></li>
</ul>
<p><code>connectors. customConnectorVersions. create</code></p>
<p><code>connectors. customConnectorVersions. delete</code></p>
<p><code>connectors. customConnectorVersions. get</code></p>
<p><code>connectors. customConnectorVersions. getIamPolicy</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectorVersions. update</code></p>
<p><code>connectors. customConnectors. create</code></p>
<p><code>connectors. customConnectors. delete</code></p>
<p><code>connectors. customConnectors. get</code></p>
<p><code>connectors. customConnectors. getIamPolicy</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. customConnectors. update</code></p>
<p><code>connectors. endpointAttachments. create</code></p>
<p><code>connectors. endpointAttachments. delete</code></p>
<p><code>connectors. endpointAttachments. get</code></p>
<p><code>connectors. endpointAttachments. getIamPolicy</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors. endpointAttachments. update</code></p>
<p><code>connectors.entities.*</code></p>
<ul>
<li><code>connectors.entities.create</code></li>
<li><code>connectors.entities.delete</code></li>
<li><code>connectors. entities. deleteEntitiesWithConditions</code></li>
<li><code>connectors.entities.get</code></li>
<li><code>connectors.entities.list</code></li>
<li><code>connectors.entities.update</code></li>
<li><code>connectors. entities. updateEntitiesWithConditions</code></li>
</ul>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors. eventSubscriptions.*</code></p>
<ul>
<li><code>connectors. eventSubscriptions. create</code></li>
<li><code>connectors. eventSubscriptions. delete</code></li>
<li><code>connectors. eventSubscriptions. get</code></li>
<li><code>connectors. eventSubscriptions. list</code></li>
<li><code>connectors. eventSubscriptions. update</code></li>
</ul>
<p><code>connectors.eventtypes.*</code></p>
<ul>
<li><code>connectors.eventtypes.get</code></li>
<li><code>connectors.eventtypes.list</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.create</code></p>
<p><code>connectors.managedZones.delete</code></p>
<p><code>connectors.managedZones.get</code></p>
<p><code>connectors. managedZones. getIamPolicy</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>connectors.managedZones.update</code></p>
<p><code>connectors.operations.*</code></p>
<ul>
<li><code>connectors.operations.cancel</code></li>
<li><code>connectors.operations.delete</code></li>
<li><code>connectors.operations.get</code></li>
<li><code>connectors.operations.list</code></li>
</ul>
<p><code>connectors.providers.*</code></p>
<ul>
<li><code>connectors.providers.get</code></li>
<li><code>connectors.providers.list</code></li>
</ul>
<p><code>connectors.regionalSettings.*</code></p>
<ul>
<li><code>connectors. regionalSettings. get</code></li>
<li><code>connectors. regionalSettings. update</code></li>
</ul>
<p><code>connectors.runtimeconfig.get</code></p>
<p><code>connectors. schemaMetadata. refresh</code></p>
<p><code>connectors.settings.*</code></p>
<ul>
<li><code>connectors.settings.get</code></li>
<li><code>connectors.settings.update</code></li>
</ul>
<p><code>connectors.versions.*</code></p>
<ul>
<li><code>connectors.versions.get</code></li>
<li><code>connectors.versions.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Connectors Viewer
<p>( <code>roles/ connectors.viewer</code> )</p>
<p>Read-only access to Connectors all resources.</p></td>
<td><p><code>connectors. connections. generateOpenAPISpec</code></p>
<p><code>connectors.connections.get</code></p>
<p><code>connectors. connections. getConnectionSchemaMetadata</code></p>
<p><code>connectors. connections. getIamPolicy</code></p>
<p><code>connectors. connections. getRuntimeActionSchema</code></p>
<p><code>connectors. connections. getRuntimeEntitySchema</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors.connectors.*</code></p>
<ul>
<li><code>connectors.connectors.get</code></li>
<li><code>connectors.connectors.list</code></li>
</ul>
<p><code>connectors. customConnectorVersions. get</code></p>
<p><code>connectors. customConnectorVersions. getIamPolicy</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectors. get</code></p>
<p><code>connectors. customConnectors. getIamPolicy</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. endpointAttachments. get</code></p>
<p><code>connectors. endpointAttachments. getIamPolicy</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors. eventSubscriptions. get</code></p>
<p><code>connectors. eventSubscriptions. list</code></p>
<p><code>connectors.eventtypes.*</code></p>
<ul>
<li><code>connectors.eventtypes.get</code></li>
<li><code>connectors.eventtypes.list</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.get</code></p>
<p><code>connectors. managedZones. getIamPolicy</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>connectors.operations.get</code></p>
<p><code>connectors.operations.list</code></p>
<p><code>connectors.providers.*</code></p>
<ul>
<li><code>connectors.providers.get</code></li>
<li><code>connectors.providers.list</code></li>
</ul>
<p><code>connectors. regionalSettings. get</code></p>
<p><code>connectors.runtimeconfig.get</code></p>
<p><code>connectors.settings.get</code></p>
<p><code>connectors.versions.*</code></p>
<ul>
<li><code>connectors.versions.get</code></li>
<li><code>connectors.versions.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Custom Connectors Admin
<p>( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p>Custom Connector is a global resource which creates custom connector within the given target project. This role grants Admin access to Custom Connector resources</p></td>
<td><p><code>connectors. customConnectorVersions.*</code></p>
<ul>
<li><code>connectors. customConnectorVersions. create</code></li>
<li><code>connectors. customConnectorVersions. delete</code></li>
<li><code>connectors. customConnectorVersions. get</code></li>
<li><code>connectors. customConnectorVersions. getIamPolicy</code></li>
<li><code>connectors. customConnectorVersions. list</code></li>
<li><code>connectors. customConnectorVersions. setIamPolicy</code></li>
<li><code>connectors. customConnectorVersions. update</code></li>
</ul>
<p><code>connectors.customConnectors.*</code></p>
<ul>
<li><code>connectors. customConnectors. create</code></li>
<li><code>connectors. customConnectors. delete</code></li>
<li><code>connectors. customConnectors. get</code></li>
<li><code>connectors. customConnectors. getIamPolicy</code></li>
<li><code>connectors. customConnectors. list</code></li>
<li><code>connectors. customConnectors. setIamPolicy</code></li>
<li><code>connectors. customConnectors. update</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Custom Connector Viewer
<p>( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p>Custom Connector is a global resource which creates custom connector within the given target project. This role grants Read-only access to Custom Connector &amp; Custom Connector Version resources.</p></td>
<td><p><code>connectors. customConnectorVersions. get</code></p>
<p><code>connectors. customConnectorVersions. getIamPolicy</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectors. get</code></p>
<p><code>connectors. customConnectors. getIamPolicy</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Connectors Endpoint Attachment Admin
<p>( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p>Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Admin access to Connectors Endpoint Attachment resources.</p></td>
<td><p><code>connectors. endpointAttachments.*</code></p>
<ul>
<li><code>connectors. endpointAttachments. create</code></li>
<li><code>connectors. endpointAttachments. delete</code></li>
<li><code>connectors. endpointAttachments. get</code></li>
<li><code>connectors. endpointAttachments. getIamPolicy</code></li>
<li><code>connectors. endpointAttachments. list</code></li>
<li><code>connectors. endpointAttachments. setIamPolicy</code></li>
<li><code>connectors. endpointAttachments. update</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Connectors Endpoint Attachment Viewer
<p>( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p>Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Read-only access to Connectors Endpoint Attachment resources</p></td>
<td><p><code>connectors. endpointAttachments. get</code></p>
<p><code>connectors. endpointAttachments. getIamPolicy</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Connectors Event Subscriptions Admin
<p>( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p>
<p>Event Subscription is a regional resource which creates subscriptions on events for a given connection within the given target project. This role grants Admin access to Connectors Subscription resources</p></td>
<td><p><code>connectors. eventSubscriptions.*</code></p>
<ul>
<li><code>connectors. eventSubscriptions. create</code></li>
<li><code>connectors. eventSubscriptions. delete</code></li>
<li><code>connectors. eventSubscriptions. get</code></li>
<li><code>connectors. eventSubscriptions. list</code></li>
<li><code>connectors. eventSubscriptions. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Connectors Event Subscriptions Viewer
<p>( <code>roles/ connectors.eventSubscriptionViewer</code> )</p>
<p>Event Subscription is a regional resource which creates subscriptions on events for a given connection within the given target project. This role grants Read-only access to Event Subscription resources.</p></td>
<td><p><code>connectors. eventSubscriptions. get</code></p>
<p><code>connectors. eventSubscriptions. list</code></p></td>
</tr>
<tr class="even">
<td>Connector Invoker
<p>( <code>roles/ connectors.invoker</code> )</p>
<p>Full Access to invoke all operations on Connections.</p></td>
<td><p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors. connections. executeSqlQuery</code></p>
<p><code>connectors.entities.*</code></p>
<ul>
<li><code>connectors.entities.create</code></li>
<li><code>connectors.entities.delete</code></li>
<li><code>connectors. entities. deleteEntitiesWithConditions</code></li>
<li><code>connectors.entities.get</code></li>
<li><code>connectors.entities.list</code></li>
<li><code>connectors.entities.update</code></li>
<li><code>connectors. entities. updateEntitiesWithConditions</code></li>
</ul>
<p><code>connectors.entityTypes.list</code></p></td>
</tr>
<tr class="odd">
<td>Connector Event Listener
<p>( <code>roles/ connectors.listener</code> )</p>
<p>Full Access to listen events by connections.</p></td>
<td><p><code>connectors. connections. listenEvent</code></p></td>
</tr>
<tr class="even">
<td>Connectors Managed Zone Admin
<p>( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p>Managed Zone is a global resource which creates Cloud DNS Peering Zone with the given target project. This role grants Admin access to Connectors Managed Zone resources</p></td>
<td><p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.*</code></p>
<ul>
<li><code>connectors.managedZones.create</code></li>
<li><code>connectors.managedZones.delete</code></li>
<li><code>connectors.managedZones.get</code></li>
<li><code>connectors. managedZones. getIamPolicy</code></li>
<li><code>connectors.managedZones.list</code></li>
<li><code>connectors. managedZones. setIamPolicy</code></li>
<li><code>connectors.managedZones.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Connectors Managed Zone Viewer
<p>( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p>Managed Zone is a global resource which creates Cloud DNS Peering Zone with the given target project. This role grants Read-only access to Connectors Managed Zone resources.</p></td>
<td><p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.get</code></p>
<p><code>connectors. managedZones. getIamPolicy</code></p>
<p><code>connectors.managedZones.list</code></p></td>
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
<td>Connectors Platform Service Agent
<p>( <code>roles/ connectors.serviceAgent</code> )</p>
<p>Grants Connectors Platform service account to manage customer resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors.connections.get</code></p>
<p><code>connectors. connections. getConnectionSchemaMetadata</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors.connectors.*</code></p>
<ul>
<li><code>connectors.connectors.get</code></li>
<li><code>connectors.connectors.list</code></li>
</ul>
<p><code>connectors. customConnectorVersions. get</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectors. get</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. endpointAttachments. get</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors.entities.get</code></p>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors. eventSubscriptions. get</code></p>
<p><code>connectors. eventSubscriptions. list</code></p>
<p><code>connectors.eventtypes.*</code></p>
<ul>
<li><code>connectors.eventtypes.get</code></li>
<li><code>connectors.eventtypes.list</code></li>
</ul>
<p><code>connectors.locations.*</code></p>
<ul>
<li><code>connectors.locations.get</code></li>
<li><code>connectors.locations.list</code></li>
</ul>
<p><code>connectors.managedZones.get</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>connectors.providers.*</code></p>
<ul>
<li><code>connectors.providers.get</code></li>
<li><code>connectors.providers.list</code></li>
</ul>
<p><code>connectors.runtimeconfig.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam. serviceAccounts. implicitDelegation</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p></td>
</tr>
</tbody>
</table>

## Connectors permissions

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
<td><code>connectors.actions.execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.actions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.connections.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.connections.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. connections. executeSqlQuery</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. connections. generateOpenAPISpec</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.connections.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. connections. getConnectionSchemaMetadata</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. connections. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. connections. getRuntimeActionSchema</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. connections. getRuntimeEntitySchema</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.connections.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. connections. listenEvent</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.listener">Connector Event Listener</a> ( <code>roles/ connectors.listener</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. connections. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.connections.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.connectors.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.connectors.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectorVersions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectorVersions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectorVersions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectorVersions. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectorVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectorVersions. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectorVersions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectors. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectors. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectors. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. customConnectors. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. customConnectors. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. endpointAttachments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. endpointAttachments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. endpointAttachments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. endpointAttachments. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. endpointAttachments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. endpointAttachments. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. endpointAttachments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.entities.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.entities.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. entities. deleteEntitiesWithConditions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.entities.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.entities.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.entities.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. entities. updateEntitiesWithConditions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.entityTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code>roles/ connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. eventSubscriptions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. eventSubscriptions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors. eventSubscriptions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionViewer">Connectors Event Subscriptions Viewer</a> ( <code>roles/ connectors.eventSubscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. eventSubscriptions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionViewer">Connectors Event Subscriptions Viewer</a> ( <code>roles/ connectors.eventSubscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. eventSubscriptions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code>roles/ connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.eventtypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.eventtypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code>roles/ connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code>roles/ connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code>roles/ connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code>roles/ connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.managedZones.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.managedZones.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.managedZones.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. managedZones. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.managedZones.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code>roles/ connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. managedZones. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.managedZones.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code>roles/ connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.providers.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.providers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>connectors. regionalSettings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors. regionalSettings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.runtimeconfig.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors. schemaMetadata. refresh</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.settings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>connectors.settings.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>connectors.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>connectors.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
