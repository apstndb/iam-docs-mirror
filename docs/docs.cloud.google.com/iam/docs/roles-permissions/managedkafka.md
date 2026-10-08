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
<td>Managed Kafka Admin
<p>( <code>roles/ managedkafka.admin</code> )</p>
<p>Full access to Managed Kafka resources.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.*</code></p>
<ul>
<li><code>managedkafka.acls.create</code></li>
<li><code>managedkafka.acls.delete</code></li>
<li><code>managedkafka.acls.get</code></li>
<li><code>managedkafka.acls.list</code></li>
<li><code>managedkafka.acls.update</code></li>
<li><code>managedkafka. acls. updateEntries</code></li>
<li><code>managedkafka. clusters. attachConnectCluster</code></li>
<li><code>managedkafka.clusters.connect</code></li>
<li><code>managedkafka.clusters.create</code></li>
<li><code>managedkafka.clusters.delete</code></li>
<li><code>managedkafka.clusters.get</code></li>
<li><code>managedkafka.clusters.list</code></li>
<li><code>managedkafka.clusters.update</code></li>
<li><code>managedkafka.config.delete</code></li>
<li><code>managedkafka.config.get</code></li>
<li><code>managedkafka.config.update</code></li>
<li><code>managedkafka. connectClusters. create</code></li>
<li><code>managedkafka. connectClusters. delete</code></li>
<li><code>managedkafka. connectClusters. get</code></li>
<li><code>managedkafka. connectClusters. list</code></li>
<li><code>managedkafka. connectClusters. update</code></li>
<li><code>managedkafka.connectors.create</code></li>
<li><code>managedkafka.connectors.delete</code></li>
<li><code>managedkafka.connectors.get</code></li>
<li><code>managedkafka.connectors.list</code></li>
<li><code>managedkafka.connectors.pause</code></li>
<li><code>managedkafka. connectors. restart</code></li>
<li><code>managedkafka.connectors.resume</code></li>
<li><code>managedkafka.connectors.stop</code></li>
<li><code>managedkafka.connectors.update</code></li>
<li><code>managedkafka. consumerGroups. delete</code></li>
<li><code>managedkafka. consumerGroups. get</code></li>
<li><code>managedkafka. consumerGroups. list</code></li>
<li><code>managedkafka. consumerGroups. update</code></li>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
<li><code>managedkafka.mode.delete</code></li>
<li><code>managedkafka.mode.get</code></li>
<li><code>managedkafka.mode.update</code></li>
<li><code>managedkafka.operations.cancel</code></li>
<li><code>managedkafka.operations.delete</code></li>
<li><code>managedkafka.operations.get</code></li>
<li><code>managedkafka.operations.list</code></li>
<li><code>managedkafka. schemaRegistries. create</code></li>
<li><code>managedkafka. schemaRegistries. delete</code></li>
<li><code>managedkafka. schemaRegistries. get</code></li>
<li><code>managedkafka. schemaRegistries. list</code></li>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
<li><code>managedkafka.subjects.delete</code></li>
<li><code>managedkafka.subjects.list</code></li>
<li><code>managedkafka.subjects.lookup</code></li>
<li><code>managedkafka.topics.create</code></li>
<li><code>managedkafka.topics.delete</code></li>
<li><code>managedkafka.topics.get</code></li>
<li><code>managedkafka.topics.list</code></li>
<li><code>managedkafka.topics.update</code></li>
<li><code>managedkafka. versions. checkCompatibility</code></li>
<li><code>managedkafka.versions.create</code></li>
<li><code>managedkafka.versions.delete</code></li>
<li><code>managedkafka.versions.get</code></li>
<li><code>managedkafka.versions.list</code></li>
<li><code>managedkafka. versions. referencedby</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Managed Kafka Viewer
<p>( <code>roles/ managedkafka.viewer</code> )</p>
<p>Readonly access to Managed Kafka resources.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka. consumerGroups. get</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.get</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Managed Kafka ACL Editor
<p>( <code>roles/ managedkafka.aclEditor</code> )</p>
<p>Read and write access to Managed Kafka ACL resources.</p></td>
<td><p><code>managedkafka.acls.*</code></p>
<ul>
<li><code>managedkafka.acls.create</code></li>
<li><code>managedkafka.acls.delete</code></li>
<li><code>managedkafka.acls.get</code></li>
<li><code>managedkafka.acls.list</code></li>
<li><code>managedkafka.acls.update</code></li>
<li><code>managedkafka. acls. updateEntries</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Managed Kafka ACL Viewer
<p>( <code>roles/ managedkafka.aclViewer</code> )</p>
<p>Readonly access to Managed Kafka ACL resources.</p></td>
<td><p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p></td>
</tr>
<tr class="odd">
<td>Managed Kafka Client
<p>( <code>roles/ managedkafka.client</code> )</p>
<p>Provides access to connect to the Kafka servers in a cluster, i.e. provides Kafka data plane access. Intended for, e.g., producers and consumers.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka. clusters. attachConnectCluster</code></p>
<p><code>managedkafka.clusters.connect</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka.consumerGroups.*</code></p>
<ul>
<li><code>managedkafka. consumerGroups. delete</code></li>
<li><code>managedkafka. consumerGroups. get</code></li>
<li><code>managedkafka. consumerGroups. list</code></li>
<li><code>managedkafka. consumerGroups. update</code></li>
</ul>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.*</code></p>
<ul>
<li><code>managedkafka.topics.create</code></li>
<li><code>managedkafka.topics.delete</code></li>
<li><code>managedkafka.topics.get</code></li>
<li><code>managedkafka.topics.list</code></li>
<li><code>managedkafka.topics.update</code></li>
</ul>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Managed Kafka Cluster Editor
<p>( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p>Provides read and write access to Kafka clusters. Intended for, e.g., IT Departments that provision Kafka clusters, but need not be able to read or modify topics or consumer groups.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.create</code></p>
<p><code>managedkafka.clusters.delete</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.clusters.update</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka. consumerGroups. get</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.get</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Managed Kafka Connect Cluster Editor <sup>Beta</sup>
<p>( <code>roles/ managedkafka.connectClusterEditor</code> )</p>
<p>Provides read and write access to Kafka Connect clusters. Intended for, e.g., IT Departments that provision Kafka Connect clusters, but need not be able to read or modify connectors.</p></td>
<td><p><code>managedkafka.connectClusters.*</code></p>
<ul>
<li><code>managedkafka. connectClusters. create</code></li>
<li><code>managedkafka. connectClusters. delete</code></li>
<li><code>managedkafka. connectClusters. get</code></li>
<li><code>managedkafka. connectClusters. list</code></li>
<li><code>managedkafka. connectClusters. update</code></li>
</ul>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p></td>
</tr>
<tr class="even">
<td>Managed Kafka Connector Editor <sup>Beta</sup>
<p>( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p>Provides read and write access to connectors. Intended for, e.g., developers who configure and operate connectors.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.*</code></p>
<ul>
<li><code>managedkafka.connectors.create</code></li>
<li><code>managedkafka.connectors.delete</code></li>
<li><code>managedkafka.connectors.get</code></li>
<li><code>managedkafka.connectors.list</code></li>
<li><code>managedkafka.connectors.pause</code></li>
<li><code>managedkafka. connectors. restart</code></li>
<li><code>managedkafka.connectors.resume</code></li>
<li><code>managedkafka.connectors.stop</code></li>
<li><code>managedkafka.connectors.update</code></li>
</ul>
<p><code>managedkafka. consumerGroups. get</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.get</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Managed Kafka Consumer Group Editor
<p>( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p>Provides read and write access to consumer group metadata. Intended for, e.g., developers who configure consumer groups.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka.consumerGroups.*</code></p>
<ul>
<li><code>managedkafka. consumerGroups. delete</code></li>
<li><code>managedkafka. consumerGroups. get</code></li>
<li><code>managedkafka. consumerGroups. list</code></li>
<li><code>managedkafka. consumerGroups. update</code></li>
</ul>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.get</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Schema Registry Admin <sup>Beta</sup>
<p>( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p>Full access to schemas, schema versions and configs</p></td>
<td><p><code>managedkafka.config.*</code></p>
<ul>
<li><code>managedkafka.config.delete</code></li>
<li><code>managedkafka.config.get</code></li>
<li><code>managedkafka.config.update</code></li>
</ul>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.mode.*</code></p>
<ul>
<li><code>managedkafka.mode.delete</code></li>
<li><code>managedkafka.mode.get</code></li>
<li><code>managedkafka.mode.update</code></li>
</ul>
<p><code>managedkafka. schemaRegistries.*</code></p>
<ul>
<li><code>managedkafka. schemaRegistries. create</code></li>
<li><code>managedkafka. schemaRegistries. delete</code></li>
<li><code>managedkafka. schemaRegistries. get</code></li>
<li><code>managedkafka. schemaRegistries. list</code></li>
</ul>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.*</code></p>
<ul>
<li><code>managedkafka.subjects.delete</code></li>
<li><code>managedkafka.subjects.list</code></li>
<li><code>managedkafka.subjects.lookup</code></li>
</ul>
<p><code>managedkafka.versions.*</code></p>
<ul>
<li><code>managedkafka. versions. checkCompatibility</code></li>
<li><code>managedkafka.versions.create</code></li>
<li><code>managedkafka.versions.delete</code></li>
<li><code>managedkafka.versions.get</code></li>
<li><code>managedkafka.versions.list</code></li>
<li><code>managedkafka. versions. referencedby</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Schema Registry Editor <sup>Beta</sup>
<p>( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p>View and edit schemas and schema versions</p></td>
<td><p><code>managedkafka.config.get</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka. schemaRegistries.*</code></p>
<ul>
<li><code>managedkafka. schemaRegistries. create</code></li>
<li><code>managedkafka. schemaRegistries. delete</code></li>
<li><code>managedkafka. schemaRegistries. get</code></li>
<li><code>managedkafka. schemaRegistries. list</code></li>
</ul>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.*</code></p>
<ul>
<li><code>managedkafka.subjects.delete</code></li>
<li><code>managedkafka.subjects.list</code></li>
<li><code>managedkafka.subjects.lookup</code></li>
</ul>
<p><code>managedkafka.versions.*</code></p>
<ul>
<li><code>managedkafka. versions. checkCompatibility</code></li>
<li><code>managedkafka.versions.create</code></li>
<li><code>managedkafka.versions.delete</code></li>
<li><code>managedkafka.versions.get</code></li>
<li><code>managedkafka.versions.list</code></li>
<li><code>managedkafka. versions. referencedby</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Schema Registry Viewer <sup>Beta</sup>
<p>( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p>View schemas and schema versions</p></td>
<td><p><code>managedkafka.config.get</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p></td>
</tr>
<tr class="odd">
<td>Managed Kafka Topic Editor
<p>( <code>roles/ managedkafka.topicEditor</code> )</p>
<p>Provides read and write access to topic metadata. Intended for, e.g., developers who configure topics.</p></td>
<td><p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>managedkafka.acls.get</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.get</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka.config.get</code></p>
<p><code>managedkafka. connectClusters. get</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.get</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka. consumerGroups. get</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.*</code></p>
<ul>
<li><code>managedkafka.contexts.get</code></li>
<li><code>managedkafka.contexts.list</code></li>
</ul>
<p><code>managedkafka.locations.*</code></p>
<ul>
<li><code>managedkafka.locations.get</code></li>
<li><code>managedkafka.locations.list</code></li>
</ul>
<p><code>managedkafka.mode.get</code></p>
<p><code>managedkafka.operations.get</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. get</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.schemas.*</code></p>
<ul>
<li><code>managedkafka.schemas.get</code></li>
<li><code>managedkafka. schemas. listSubjects</code></li>
<li><code>managedkafka.schemas.listTypes</code></li>
<li><code>managedkafka. schemas. listVersions</code></li>
</ul>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.subjects.lookup</code></p>
<p><code>managedkafka.topics.*</code></p>
<ul>
<li><code>managedkafka.topics.create</code></li>
<li><code>managedkafka.topics.delete</code></li>
<li><code>managedkafka.topics.get</code></li>
<li><code>managedkafka.topics.list</code></li>
<li><code>managedkafka.topics.update</code></li>
</ul>
<p><code>managedkafka. versions. checkCompatibility</code></p>
<p><code>managedkafka.versions.get</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>managedkafka. versions. referencedby</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
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
<td>Managed Kafka Service Agent
<p>( <code>roles/ managedkafka.serviceAgent</code> )</p>
<p>Gives Managed Kafka Service Agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.forwardingRules.create</code></p>
<p><code>compute.forwardingRules.delete</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. forwardingRules. pscCreate</code></p>
<p><code>compute. forwardingRules. pscDelete</code></p>
<p><code>compute. networkAttachments. create</code></p>
<p><code>compute. networkAttachments. delete</code></p>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>dns.changes.create</code></p>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. bindPrivateDNSZone</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>dns.resourceRecordSets.create</code></p>
<p><code>dns.resourceRecordSets.delete</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.resourceRecordSets.update</code></p>
<p><code>managedkafka.clusters.connect</code></p>
<p><code>privateca.caPools.get</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p></td>
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
<td><code>managedkafka.acls.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.acls.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.acls.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclViewer">Managed Kafka ACL Viewer</a> ( <code>roles/ managedkafka.aclViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.acls.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclViewer">Managed Kafka ACL Viewer</a> ( <code>roles/ managedkafka.aclViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.acls.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. acls. updateEntries</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.aclEditor">Managed Kafka ACL Editor</a> ( <code>roles/ managedkafka.aclEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. clusters. attachConnectCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.clusters.connect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>managedkafka.clusters.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.clusters.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.clusters.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>managedkafka.clusters.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>managedkafka.clusters.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>managedkafka.config.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.config.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.config.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. connectClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. connectClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. connectClusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. connectClusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. connectClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.connectors.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.connectors.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.connectors.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.connectors.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectClusterEditor">Managed Kafka Connect Cluster Editor</a> ( <code>roles/ managedkafka.connectClusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.connectors.pause</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. connectors. restart</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.connectors.resume</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.connectors.stop</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.connectors.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. consumerGroups. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. consumerGroups. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. consumerGroups. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. consumerGroups. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.contexts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.contexts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.mode.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.mode.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.mode.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. schemaRegistries. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. schemaRegistries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. schemaRegistries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. schemaRegistries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.schemas.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. schemas. listSubjects</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.schemas.listTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. schemas. listVersions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.subjects.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.subjects.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.subjects.lookup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.topics.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.topics.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.topics.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.topics.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.topics.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka. versions. checkCompatibility</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.versions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.versions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>managedkafka.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>managedkafka. versions. referencedby</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryAdmin">Schema Registry Admin</a> ( <code>roles/ managedkafka.schemaRegistryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryEditor">Schema Registry Editor</a> ( <code>roles/ managedkafka.schemaRegistryEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.schemaRegistryViewer">Schema Registry Viewer</a> ( <code>roles/ managedkafka.schemaRegistryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p></td>
</tr>
</tbody>
</table>
