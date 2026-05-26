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
<td><h4 id="connectors.admin" class="role-title add-link" data-text="Connector Admin" tabindex="-1">Connector Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p>Full access to all resources of Connectors Service.</p></td>
<td><p><code dir="ltr" translate="no">connectors.actions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.actions.execute</code></li>
<li><code dir="ltr" translate="no">connectors.actions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.connections.create</code></p>
<p><code dir="ltr" translate="no">connectors.connections.delete</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  executeSqlQuery</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  generateOpenAPISpec</code></p>
<p><code dir="ltr" translate="no">connectors.connections.get</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getConnectionSchemaMetadata</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getRuntimeActionSchema</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getRuntimeEntitySchema</code></p>
<p><code dir="ltr" translate="no">connectors.connections.list</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.connections.update</code></p>
<p><code dir="ltr" translate="no">connectors.connectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.connectors.get</code></li>
<li><code dir="ltr" translate="no">connectors.connectors.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.customConnectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.entities.create</code></li>
<li><code dir="ltr" translate="no">connectors.entities.delete</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  deleteEntitiesWithConditions</code></li>
<li><code dir="ltr" translate="no">connectors.entities.get</code></li>
<li><code dir="ltr" translate="no">connectors.entities.list</code></li>
<li><code dir="ltr" translate="no">connectors.entities.update</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  updateEntitiesWithConditions</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.eventtypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.eventtypes.get</code></li>
<li><code dir="ltr" translate="no">connectors.eventtypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.managedZones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.managedZones.create</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.delete</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.get</code></li>
<li><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.list</code></li>
<li><code dir="ltr" translate="no">connectors.  managedZones.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.operations.cancel</code></li>
<li><code dir="ltr" translate="no">connectors.operations.delete</code></li>
<li><code dir="ltr" translate="no">connectors.operations.get</code></li>
<li><code dir="ltr" translate="no">connectors.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.providers.get</code></li>
<li><code dir="ltr" translate="no">connectors.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.regionalSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  regionalSettings.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  regionalSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.runtimeconfig.get</code></p>
<p><code dir="ltr" translate="no">connectors.  schemaMetadata.  refresh</code></p>
<p><code dir="ltr" translate="no">connectors.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.settings.get</code></li>
<li><code dir="ltr" translate="no">connectors.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.versions.get</code></li>
<li><code dir="ltr" translate="no">connectors.versions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.viewer" class="role-title add-link" data-text="Connectors Viewer" tabindex="-1">Connectors Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p>Read-only access to Connectors all resources.</p></td>
<td><p><code dir="ltr" translate="no">connectors.  connections.  generateOpenAPISpec</code></p>
<p><code dir="ltr" translate="no">connectors.connections.get</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getConnectionSchemaMetadata</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getRuntimeActionSchema</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getRuntimeEntitySchema</code></p>
<p><code dir="ltr" translate="no">connectors.connections.list</code></p>
<p><code dir="ltr" translate="no">connectors.connectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.connectors.get</code></li>
<li><code dir="ltr" translate="no">connectors.connectors.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.eventtypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.eventtypes.get</code></li>
<li><code dir="ltr" translate="no">connectors.eventtypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.managedZones.get</code></p>
<p><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.managedZones.list</code></p>
<p><code dir="ltr" translate="no">connectors.operations.get</code></p>
<p><code dir="ltr" translate="no">connectors.operations.list</code></p>
<p><code dir="ltr" translate="no">connectors.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.providers.get</code></li>
<li><code dir="ltr" translate="no">connectors.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  regionalSettings.  get</code></p>
<p><code dir="ltr" translate="no">connectors.runtimeconfig.get</code></p>
<p><code dir="ltr" translate="no">connectors.settings.get</code></p>
<p><code dir="ltr" translate="no">connectors.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.versions.get</code></li>
<li><code dir="ltr" translate="no">connectors.versions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectorAdmin" class="role-title add-link" data-text="Custom Connectors Admin" tabindex="-1">Custom Connectors Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p>Custom Connector is a global resource which creates custom connector within the given target project. This role grants Admin access to Custom Connector resources</p></td>
<td><p><code dir="ltr" translate="no">connectors.  customConnectorVersions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectorVersions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.customConnectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  customConnectors.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectorViewer" class="role-title add-link" data-text="Custom Connector Viewer" tabindex="-1">Custom Connector Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p>Custom Connector is a global resource which creates custom connector within the given target project. This role grants Read-only access to Custom Connector &amp; Custom Connector Version resources.</p></td>
<td><p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></p>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.endpointAttachmentAdmin" class="role-title add-link" data-text="Connectors Endpoint Attachment Admin" tabindex="-1">Connectors Endpoint Attachment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p>Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Admin access to Connectors Endpoint Attachment resources.</p></td>
<td><p><code dir="ltr" translate="no">connectors.  endpointAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.  endpointAttachments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.endpointAttachmentViewer" class="role-title add-link" data-text="Connectors Endpoint Attachment Viewer" tabindex="-1">Connectors Endpoint Attachment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p>Endpoint Attachment is a regional resource which creates PSC connection endpoint for the given PSC Service Attachment. This role grants Read-only access to Connectors Endpoint Attachment resources</p></td>
<td><p><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></p>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.eventSubscriptionAdmin" class="role-title add-link" data-text="Connectors Event Subscriptions Admin" tabindex="-1">Connectors Event Subscriptions Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p>
<p>Event Subscription is a regional resource which creates subscriptions on events for a given connection within the given target project. This role grants Admin access to Connectors Subscription resources</p></td>
<td><p><code dir="ltr" translate="no">connectors.  eventSubscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  create</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  delete</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></li>
<li><code dir="ltr" translate="no">connectors.  eventSubscriptions.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.eventSubscriptionViewer" class="role-title add-link" data-text="Connectors Event Subscriptions Viewer" tabindex="-1">Connectors Event Subscriptions Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.eventSubscriptionViewer</code> )</p>
<p>Event Subscription is a regional resource which creates subscriptions on events for a given connection within the given target project. This role grants Read-only access to Event Subscription resources.</p></td>
<td><p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.invoker" class="role-title add-link" data-text="Connector Invoker" tabindex="-1">Connector Invoker</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p>Full Access to invoke all operations on Connections.</p></td>
<td><p><code dir="ltr" translate="no">connectors.actions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.actions.execute</code></li>
<li><code dir="ltr" translate="no">connectors.actions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  connections.  executeSqlQuery</code></p>
<p><code dir="ltr" translate="no">connectors.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.entities.create</code></li>
<li><code dir="ltr" translate="no">connectors.entities.delete</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  deleteEntitiesWithConditions</code></li>
<li><code dir="ltr" translate="no">connectors.entities.get</code></li>
<li><code dir="ltr" translate="no">connectors.entities.list</code></li>
<li><code dir="ltr" translate="no">connectors.entities.update</code></li>
<li><code dir="ltr" translate="no">connectors.  entities.  updateEntitiesWithConditions</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.listener" class="role-title add-link" data-text="Connector Event Listener" tabindex="-1">Connector Event Listener</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.listener</code> )</p>
<p>Full Access to listen events by connections.</p></td>
<td><p><code dir="ltr" translate="no">connectors.  connections.  listenEvent</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.managedZoneAdmin" class="role-title add-link" data-text="Connectors Managed Zone Admin" tabindex="-1">Connectors Managed Zone Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p>Managed Zone is a global resource which creates Cloud DNS Peering Zone with the given target project. This role grants Admin access to Connectors Managed Zone resources</p></td>
<td><p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.managedZones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.managedZones.create</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.delete</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.get</code></li>
<li><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.list</code></li>
<li><code dir="ltr" translate="no">connectors.  managedZones.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">connectors.managedZones.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.managedZoneViewer" class="role-title add-link" data-text="Connectors Managed Zone Viewer" tabindex="-1">Connectors Managed Zone Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p>Managed Zone is a global resource which creates Cloud DNS Peering Zone with the given target project. This role grants Read-only access to Connectors Managed Zone resources.</p></td>
<td><p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.managedZones.get</code></p>
<p><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.managedZones.list</code></p></td>
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
<td><h4 id="connectors.serviceAgent" class="role-title add-link" data-text="Connectors Platform Service Agent" tabindex="-1">Connectors Platform Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</p>
<p>Grants Connectors Platform service account to manage customer resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">connectors.actions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.actions.execute</code></li>
<li><code dir="ltr" translate="no">connectors.actions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.connections.get</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getConnectionSchemaMetadata</code></p>
<p><code dir="ltr" translate="no">connectors.connections.list</code></p>
<p><code dir="ltr" translate="no">connectors.connectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.connectors.get</code></li>
<li><code dir="ltr" translate="no">connectors.connectors.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></p>
<p><code dir="ltr" translate="no">connectors.entities.get</code></p>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.eventtypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.eventtypes.get</code></li>
<li><code dir="ltr" translate="no">connectors.eventtypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.locations.get</code></li>
<li><code dir="ltr" translate="no">connectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.managedZones.get</code></p>
<p><code dir="ltr" translate="no">connectors.managedZones.list</code></p>
<p><code dir="ltr" translate="no">connectors.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">connectors.providers.get</code></li>
<li><code dir="ltr" translate="no">connectors.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">connectors.runtimeconfig.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  implicitDelegation</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p></td>
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
<td><h4 id="connectors.actions.execute" class="permission-name add-link" data-text="connectors.actions.execute" tabindex="-1"><code dir="ltr" translate="no">connectors.actions.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.actions.list" class="permission-name add-link" data-text="connectors.actions.list" tabindex="-1"><code dir="ltr" translate="no">connectors.actions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.create" class="permission-name add-link" data-text="connectors.connections.create" tabindex="-1"><code dir="ltr" translate="no">connectors.connections.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.delete" class="permission-name add-link" data-text="connectors.connections.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.connections.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.executeSqlQuery" class="permission-name add-link" data-text="connectors.connections.executeSqlQuery" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  executeSqlQuery</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.generateOpenAPISpec" class="permission-name add-link" data-text="connectors.connections.generateOpenAPISpec" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  generateOpenAPISpec</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.get" class="permission-name add-link" data-text="connectors.connections.get" tabindex="-1"><code dir="ltr" translate="no">connectors.connections.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.getConnectionSchemaMetadata" class="permission-name add-link" data-text="connectors.connections.getConnectionSchemaMetadata" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  getConnectionSchemaMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.getIamPolicy" class="permission-name add-link" data-text="connectors.connections.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.getRuntimeActionSchema" class="permission-name add-link" data-text="connectors.connections.getRuntimeActionSchema" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  getRuntimeActionSchema</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.getRuntimeEntitySchema" class="permission-name add-link" data-text="connectors.connections.getRuntimeEntitySchema" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  getRuntimeEntitySchema</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.list" class="permission-name add-link" data-text="connectors.connections.list" tabindex="-1"><code dir="ltr" translate="no">connectors.connections.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.listenEvent" class="permission-name add-link" data-text="connectors.connections.listenEvent" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  listenEvent</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.listener">Connector Event Listener</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.listener</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connections.setIamPolicy" class="permission-name add-link" data-text="connectors.connections.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  connections.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connections.update" class="permission-name add-link" data-text="connectors.connections.update" tabindex="-1"><code dir="ltr" translate="no">connectors.connections.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.connectors.get" class="permission-name add-link" data-text="connectors.connectors.get" tabindex="-1"><code dir="ltr" translate="no">connectors.connectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.connectors.list" class="permission-name add-link" data-text="connectors.connectors.list" tabindex="-1"><code dir="ltr" translate="no">connectors.connectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectorVersions.create" class="permission-name add-link" data-text="connectors.customConnectorVersions.create" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectorVersions.delete" class="permission-name add-link" data-text="connectors.customConnectorVersions.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectorVersions.get" class="permission-name add-link" data-text="connectors.customConnectorVersions.get" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectorVersions.getIamPolicy" class="permission-name add-link" data-text="connectors.customConnectorVersions.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectorVersions.list" class="permission-name add-link" data-text="connectors.customConnectorVersions.list" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectorVersions.setIamPolicy" class="permission-name add-link" data-text="connectors.customConnectorVersions.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectorVersions.update" class="permission-name add-link" data-text="connectors.customConnectorVersions.update" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectorVersions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectors.create" class="permission-name add-link" data-text="connectors.customConnectors.create" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectors.delete" class="permission-name add-link" data-text="connectors.customConnectors.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectors.get" class="permission-name add-link" data-text="connectors.customConnectors.get" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectors.getIamPolicy" class="permission-name add-link" data-text="connectors.customConnectors.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectors.list" class="permission-name add-link" data-text="connectors.customConnectors.list" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.customConnectors.setIamPolicy" class="permission-name add-link" data-text="connectors.customConnectors.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.customConnectors.update" class="permission-name add-link" data-text="connectors.customConnectors.update" tabindex="-1"><code dir="ltr" translate="no">connectors.  customConnectors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.endpointAttachments.create" class="permission-name add-link" data-text="connectors.endpointAttachments.create" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.endpointAttachments.delete" class="permission-name add-link" data-text="connectors.endpointAttachments.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.endpointAttachments.get" class="permission-name add-link" data-text="connectors.endpointAttachments.get" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.endpointAttachments.getIamPolicy" class="permission-name add-link" data-text="connectors.endpointAttachments.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.endpointAttachments.list" class="permission-name add-link" data-text="connectors.endpointAttachments.list" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.endpointAttachments.setIamPolicy" class="permission-name add-link" data-text="connectors.endpointAttachments.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.endpointAttachments.update" class="permission-name add-link" data-text="connectors.endpointAttachments.update" tabindex="-1"><code dir="ltr" translate="no">connectors.  endpointAttachments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.entities.create" class="permission-name add-link" data-text="connectors.entities.create" tabindex="-1"><code dir="ltr" translate="no">connectors.entities.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.entities.delete" class="permission-name add-link" data-text="connectors.entities.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.entities.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.entities.deleteEntitiesWithConditions" class="permission-name add-link" data-text="connectors.entities.deleteEntitiesWithConditions" tabindex="-1"><code dir="ltr" translate="no">connectors.  entities.  deleteEntitiesWithConditions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.entities.get" class="permission-name add-link" data-text="connectors.entities.get" tabindex="-1"><code dir="ltr" translate="no">connectors.entities.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.entities.list" class="permission-name add-link" data-text="connectors.entities.list" tabindex="-1"><code dir="ltr" translate="no">connectors.entities.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.entities.update" class="permission-name add-link" data-text="connectors.entities.update" tabindex="-1"><code dir="ltr" translate="no">connectors.entities.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.entities.updateEntitiesWithConditions" class="permission-name add-link" data-text="connectors.entities.updateEntitiesWithConditions" tabindex="-1"><code dir="ltr" translate="no">connectors.  entities.  updateEntitiesWithConditions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.entityTypes.list" class="permission-name add-link" data-text="connectors.entityTypes.list" tabindex="-1"><code dir="ltr" translate="no">connectors.entityTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.invoker">Connector Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.eventSubscriptions.create" class="permission-name add-link" data-text="connectors.eventSubscriptions.create" tabindex="-1"><code dir="ltr" translate="no">connectors.  eventSubscriptions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.eventSubscriptions.delete" class="permission-name add-link" data-text="connectors.eventSubscriptions.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.  eventSubscriptions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.eventSubscriptions.get" class="permission-name add-link" data-text="connectors.eventSubscriptions.get" tabindex="-1"><code dir="ltr" translate="no">connectors.  eventSubscriptions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionViewer">Connectors Event Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.eventSubscriptions.list" class="permission-name add-link" data-text="connectors.eventSubscriptions.list" tabindex="-1"><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionViewer">Connectors Event Subscriptions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.eventSubscriptions.update" class="permission-name add-link" data-text="connectors.eventSubscriptions.update" tabindex="-1"><code dir="ltr" translate="no">connectors.  eventSubscriptions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.eventSubscriptionAdmin">Connectors Event Subscriptions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.eventSubscriptionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.eventtypes.get" class="permission-name add-link" data-text="connectors.eventtypes.get" tabindex="-1"><code dir="ltr" translate="no">connectors.eventtypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.eventtypes.list" class="permission-name add-link" data-text="connectors.eventtypes.list" tabindex="-1"><code dir="ltr" translate="no">connectors.eventtypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.locations.get" class="permission-name add-link" data-text="connectors.locations.get" tabindex="-1"><code dir="ltr" translate="no">connectors.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.locations.list" class="permission-name add-link" data-text="connectors.locations.list" tabindex="-1"><code dir="ltr" translate="no">connectors.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorAdmin">Custom Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.customConnectorViewer">Custom Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.customConnectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentAdmin">Connectors Endpoint Attachment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.endpointAttachmentViewer">Connectors Endpoint Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.endpointAttachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.managedZones.create" class="permission-name add-link" data-text="connectors.managedZones.create" tabindex="-1"><code dir="ltr" translate="no">connectors.managedZones.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.managedZones.delete" class="permission-name add-link" data-text="connectors.managedZones.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.managedZones.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.managedZones.get" class="permission-name add-link" data-text="connectors.managedZones.get" tabindex="-1"><code dir="ltr" translate="no">connectors.managedZones.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.managedZones.getIamPolicy" class="permission-name add-link" data-text="connectors.managedZones.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.managedZones.list" class="permission-name add-link" data-text="connectors.managedZones.list" tabindex="-1"><code dir="ltr" translate="no">connectors.managedZones.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneViewer">Connectors Managed Zone Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.managedZones.setIamPolicy" class="permission-name add-link" data-text="connectors.managedZones.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">connectors.  managedZones.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.managedZones.update" class="permission-name add-link" data-text="connectors.managedZones.update" tabindex="-1"><code dir="ltr" translate="no">connectors.managedZones.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.managedZoneAdmin">Connectors Managed Zone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.managedZoneAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.operations.cancel" class="permission-name add-link" data-text="connectors.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">connectors.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.operations.delete" class="permission-name add-link" data-text="connectors.operations.delete" tabindex="-1"><code dir="ltr" translate="no">connectors.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.operations.get" class="permission-name add-link" data-text="connectors.operations.get" tabindex="-1"><code dir="ltr" translate="no">connectors.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.operations.list" class="permission-name add-link" data-text="connectors.operations.list" tabindex="-1"><code dir="ltr" translate="no">connectors.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.providers.get" class="permission-name add-link" data-text="connectors.providers.get" tabindex="-1"><code dir="ltr" translate="no">connectors.providers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.providers.list" class="permission-name add-link" data-text="connectors.providers.list" tabindex="-1"><code dir="ltr" translate="no">connectors.providers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.regionalSettings.get" class="permission-name add-link" data-text="connectors.regionalSettings.get" tabindex="-1"><code dir="ltr" translate="no">connectors.  regionalSettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.regionalSettings.update" class="permission-name add-link" data-text="connectors.regionalSettings.update" tabindex="-1"><code dir="ltr" translate="no">connectors.  regionalSettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.runtimeconfig.get" class="permission-name add-link" data-text="connectors.runtimeconfig.get" tabindex="-1"><code dir="ltr" translate="no">connectors.runtimeconfig.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.schemaMetadata.refresh" class="permission-name add-link" data-text="connectors.schemaMetadata.refresh" tabindex="-1"><code dir="ltr" translate="no">connectors.  schemaMetadata.  refresh</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.settings.get" class="permission-name add-link" data-text="connectors.settings.get" tabindex="-1"><code dir="ltr" translate="no">connectors.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors.settings.update" class="permission-name add-link" data-text="connectors.settings.update" tabindex="-1"><code dir="ltr" translate="no">connectors.settings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="connectors.versions.get" class="permission-name add-link" data-text="connectors.versions.get" tabindex="-1"><code dir="ltr" translate="no">connectors.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="connectors.versions.list" class="permission-name add-link" data-text="connectors.versions.list" tabindex="-1"><code dir="ltr" translate="no">connectors.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
