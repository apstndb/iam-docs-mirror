---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/managedkafka
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka
title: Google Cloud Managed Service for Apache Kafka roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud Managed Service for Apache Kafka. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud Managed Service for Apache Kafka roles

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
<td><h4 id="managedkafka.admin" class="role-title add-link" data-text="Managed Kafka Admin" tabindex="-1">Managed Kafka Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p>Full access to Managed Kafka resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.acls.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.  acls.  updateEntries</code></li>
<li><code dir="ltr" translate="no">managedkafka.  clusters.  attachConnectCluster</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.connect</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.clusters.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.config.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.config.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.config.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  create</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  update</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.pause</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectors.  restart</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.resume</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.stop</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  update</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.mode.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.mode.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.mode.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.operations.cancel</code></li>
<li><code dir="ltr" translate="no">managedkafka.operations.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.operations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.operations.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  create</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.viewer" class="role-title add-link" data-text="Managed Kafka Viewer" tabindex="-1">Managed Kafka Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p>Readonly access to Managed Kafka resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.aclEditor" class="role-title add-link" data-text="Managed Kafka ACL Editor" tabindex="-1">Managed Kafka ACL Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p>
<p>Read and write access to Managed Kafka ACL resources.</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.acls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.acls.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.acls.update</code></li>
<li><code dir="ltr" translate="no">managedkafka.  acls.  updateEntries</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.aclViewer" class="role-title add-link" data-text="Managed Kafka ACL Viewer" tabindex="-1">Managed Kafka ACL Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.aclViewer</code> )</p>
<p>Readonly access to Managed Kafka ACL resources.</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.client" class="role-title add-link" data-text="Managed Kafka Client" tabindex="-1">Managed Kafka Client</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p>Provides access to connect to the Kafka servers in a cluster, i.e. provides Kafka data plane access. Intended for, e.g., producers and consumers.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  clusters.  attachConnectCluster</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.connect</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.consumerGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.topics.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.clusterEditor" class="role-title add-link" data-text="Managed Kafka Cluster Editor" tabindex="-1">Managed Kafka Cluster Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p>Provides read and write access to Kafka clusters. Intended for, e.g., IT Departments that provision Kafka clusters, but need not be able to read or modify topics or consumer groups.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.create</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.delete</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.update</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectClusterEditor" class="role-title add-link" data-text="Managed Kafka Connect Cluster Editor Beta" tabindex="-1">Managed Kafka Connect Cluster Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p>
<p>Provides read and write access to Kafka Connect clusters. Intended for, e.g., IT Departments that provision Kafka Connect clusters, but need not be able to read or modify connectors.</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.connectClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  create</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectorEditor" class="role-title add-link" data-text="Managed Kafka Connector Editor Beta" tabindex="-1">Managed Kafka Connector Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p>Provides read and write access to connectors. Intended for, e.g., developers who configure and operate connectors.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.connectors.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.pause</code></li>
<li><code dir="ltr" translate="no">managedkafka.  connectors.  restart</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.resume</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.stop</code></li>
<li><code dir="ltr" translate="no">managedkafka.connectors.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.consumerGroupEditor" class="role-title add-link" data-text="Managed Kafka Consumer Group Editor" tabindex="-1">Managed Kafka Consumer Group Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p>Provides read and write access to consumer group metadata. Intended for, e.g., developers who configure consumer groups.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.consumerGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  consumerGroups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemaRegistryAdmin" class="role-title add-link" data-text="Schema Registry Admin Beta" tabindex="-1">Schema Registry Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p>Full access to schemas, schema versions and configs</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.config.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.config.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.config.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.mode.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.mode.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.mode.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  create</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.subjects.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.schemaRegistryEditor" class="role-title add-link" data-text="Schema Registry Editor Beta" tabindex="-1">Schema Registry Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p>View and edit schemas and schema versions</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  create</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.subjects.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.versions.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemaRegistryViewer" class="role-title add-link" data-text="Schema Registry Viewer Beta" tabindex="-1">Schema Registry Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p>View schemas and schema versions</p></td>
<td><p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.topicEditor" class="role-title add-link" data-text="Managed Kafka Topic Editor" tabindex="-1">Managed Kafka Topic Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p>
<p>Provides read and write access to topic metadata. Intended for, e.g., developers who configure topics.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.config.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.contexts.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.contexts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.locations.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.mode.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.schemas.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></li>
<li><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></li>
<li><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedkafka.topics.create</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.delete</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.get</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.list</code></li>
<li><code dir="ltr" translate="no">managedkafka.topics.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
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
<td><h4 id="managedkafka.serviceAgent" class="role-title add-link" data-text="Managed Kafka Service Agent" tabindex="-1">Managed Kafka Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  managedkafka.serviceAgent</code> )</p>
<p>Gives Managed Kafka Service Agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">dns.changes.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.connect</code></p>
<p><code dir="ltr" translate="no">privateca.caPools.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud Managed Service for Apache Kafka permissions

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
<td><h4 id="managedkafka.acls.create" class="permission-name add-link" data-text="managedkafka.acls.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.acls.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.acls.delete" class="permission-name add-link" data-text="managedkafka.acls.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.acls.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.acls.get" class="permission-name add-link" data-text="managedkafka.acls.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.acls.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclViewer">Managed Kafka ACL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.acls.list" class="permission-name add-link" data-text="managedkafka.acls.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.acls.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclViewer">Managed Kafka ACL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.acls.update" class="permission-name add-link" data-text="managedkafka.acls.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.acls.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.acls.updateEntries" class="permission-name add-link" data-text="managedkafka.acls.updateEntries" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  acls.  updateEntries</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.clusters.attachConnectCluster" class="permission-name add-link" data-text="managedkafka.clusters.attachConnectCluster" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  clusters.  attachConnectCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.clusters.connect" class="permission-name add-link" data-text="managedkafka.clusters.connect" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.clusters.create" class="permission-name add-link" data-text="managedkafka.clusters.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.clusters.delete" class="permission-name add-link" data-text="managedkafka.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.clusters.get" class="permission-name add-link" data-text="managedkafka.clusters.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.clusters.list" class="permission-name add-link" data-text="managedkafka.clusters.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.clusters.update" class="permission-name add-link" data-text="managedkafka.clusters.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.clusters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.config.delete" class="permission-name add-link" data-text="managedkafka.config.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.config.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.config.get" class="permission-name add-link" data-text="managedkafka.config.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.config.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.config.update" class="permission-name add-link" data-text="managedkafka.config.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.config.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectClusters.create" class="permission-name add-link" data-text="managedkafka.connectClusters.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectClusters.delete" class="permission-name add-link" data-text="managedkafka.connectClusters.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectClusters.get" class="permission-name add-link" data-text="managedkafka.connectClusters.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectClusters.list" class="permission-name add-link" data-text="managedkafka.connectClusters.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectClusters.update" class="permission-name add-link" data-text="managedkafka.connectClusters.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectors.create" class="permission-name add-link" data-text="managedkafka.connectors.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectors.delete" class="permission-name add-link" data-text="managedkafka.connectors.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectors.get" class="permission-name add-link" data-text="managedkafka.connectors.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectors.list" class="permission-name add-link" data-text="managedkafka.connectors.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectors.pause" class="permission-name add-link" data-text="managedkafka.connectors.pause" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectors.restart" class="permission-name add-link" data-text="managedkafka.connectors.restart" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  connectors.  restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectors.resume" class="permission-name add-link" data-text="managedkafka.connectors.resume" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.connectors.stop" class="permission-name add-link" data-text="managedkafka.connectors.stop" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.connectors.update" class="permission-name add-link" data-text="managedkafka.connectors.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.connectors.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.consumerGroups.delete" class="permission-name add-link" data-text="managedkafka.consumerGroups.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  consumerGroups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.consumerGroups.get" class="permission-name add-link" data-text="managedkafka.consumerGroups.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  consumerGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.consumerGroups.list" class="permission-name add-link" data-text="managedkafka.consumerGroups.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.consumerGroups.update" class="permission-name add-link" data-text="managedkafka.consumerGroups.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  consumerGroups.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.contexts.get" class="permission-name add-link" data-text="managedkafka.contexts.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.contexts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.contexts.list" class="permission-name add-link" data-text="managedkafka.contexts.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.contexts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.locations.get" class="permission-name add-link" data-text="managedkafka.locations.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.locations.list" class="permission-name add-link" data-text="managedkafka.locations.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.mode.delete" class="permission-name add-link" data-text="managedkafka.mode.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.mode.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.mode.get" class="permission-name add-link" data-text="managedkafka.mode.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.mode.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.mode.update" class="permission-name add-link" data-text="managedkafka.mode.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.mode.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.operations.cancel" class="permission-name add-link" data-text="managedkafka.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">managedkafka.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.operations.delete" class="permission-name add-link" data-text="managedkafka.operations.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.operations.get" class="permission-name add-link" data-text="managedkafka.operations.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.operations.list" class="permission-name add-link" data-text="managedkafka.operations.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemaRegistries.create" class="permission-name add-link" data-text="managedkafka.schemaRegistries.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.schemaRegistries.delete" class="permission-name add-link" data-text="managedkafka.schemaRegistries.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemaRegistries.get" class="permission-name add-link" data-text="managedkafka.schemaRegistries.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.schemaRegistries.list" class="permission-name add-link" data-text="managedkafka.schemaRegistries.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemas.get" class="permission-name add-link" data-text="managedkafka.schemas.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.schemas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.schemas.listSubjects" class="permission-name add-link" data-text="managedkafka.schemas.listSubjects" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemas.  listSubjects</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.schemas.listTypes" class="permission-name add-link" data-text="managedkafka.schemas.listTypes" tabindex="-1"><code dir="ltr" translate="no">managedkafka.schemas.listTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.schemas.listVersions" class="permission-name add-link" data-text="managedkafka.schemas.listVersions" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  schemas.  listVersions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.subjects.delete" class="permission-name add-link" data-text="managedkafka.subjects.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.subjects.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.subjects.list" class="permission-name add-link" data-text="managedkafka.subjects.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.subjects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.subjects.lookup" class="permission-name add-link" data-text="managedkafka.subjects.lookup" tabindex="-1"><code dir="ltr" translate="no">managedkafka.subjects.lookup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.topics.create" class="permission-name add-link" data-text="managedkafka.topics.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.topics.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.topics.delete" class="permission-name add-link" data-text="managedkafka.topics.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.topics.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.topics.get" class="permission-name add-link" data-text="managedkafka.topics.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.topics.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.topics.list" class="permission-name add-link" data-text="managedkafka.topics.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.topics.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.topics.update" class="permission-name add-link" data-text="managedkafka.topics.update" tabindex="-1"><code dir="ltr" translate="no">managedkafka.topics.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.versions.checkCompatibility" class="permission-name add-link" data-text="managedkafka.versions.checkCompatibility" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  versions.  checkCompatibility</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.versions.create" class="permission-name add-link" data-text="managedkafka.versions.create" tabindex="-1"><code dir="ltr" translate="no">managedkafka.versions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.versions.delete" class="permission-name add-link" data-text="managedkafka.versions.delete" tabindex="-1"><code dir="ltr" translate="no">managedkafka.versions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.versions.get" class="permission-name add-link" data-text="managedkafka.versions.get" tabindex="-1"><code dir="ltr" translate="no">managedkafka.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedkafka.versions.list" class="permission-name add-link" data-text="managedkafka.versions.list" tabindex="-1"><code dir="ltr" translate="no">managedkafka.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedkafka.versions.referencedby" class="permission-name add-link" data-text="managedkafka.versions.referencedby" tabindex="-1"><code dir="ltr" translate="no">managedkafka.  versions.  referencedby</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.topicEditor</code> )</p></td>
</tr>
</tbody>
</table>
