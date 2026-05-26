---
name: documents/docs.cloud.google.com/iam/docs/conditions-resource-attributes
uri: https://docs.cloud.google.com/iam/docs/conditions-resource-attributes
title: Resource attributes for IAM Conditions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This topic contains a list of values that can be used for [resource attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource) in a condition, including string values for resource service, resource type, and the format for resource name strings.

You can use resource attributes to change the scope of the grant provided by a role binding. When a role contains permissions that apply to different kinds of resources, a condition can grant a subset of the role's permissions based on the resource service, resource type, and resource name.

Resource attributes are available for the Google Cloud services and resource types that are listed on this page. Other services and resource types do not recognize resource attributes.

For more information about Identity and Access Management (IAM) Conditions, see the following:

  - [Conditions overview](https://docs.cloud.google.com/iam/docs/conditions-overview)
  - [Managing conditional role bindings](https://docs.cloud.google.com/iam/docs/managing-conditional-policies)

<span id="resource_service_values"></span>

## Resource service values

The following table lists the values that the resource service attribute can contain.

Resource service value

REST reference

`apigee.googleapis.com`

[API reference](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest)

`apihub.googleapis.com`

[API reference](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest)

`backupdr.googleapis.com`

[API reference](https://docs.cloud.google.com/backup-disaster-recovery/docs/reference/rest)

`bigquery.googleapis.com`

[API reference](https://docs.cloud.google.com/bigquery/docs/reference/rest)

`bigqueryreservation.googleapis.com`

[API reference](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest)

`bigtableadmin.googleapis.com`

[API reference](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest)

`binaryauthorization.googleapis.com`

[API reference](https://docs.cloud.google.com/binary-authorization/docs/reference/rest)

`ces.googleapis.com`

[API reference](https://docs.cloud.google.com/customer-engagement-ai/conversational-agents/ps/reference/rest)

`clouddeploy.googleapis.com`

[API reference](https://docs.cloud.google.com/deploy/docs/api/reference/rest)

`cloudkms.googleapis.com`

[API reference](https://docs.cloud.google.com/kms/docs/reference/rest)

`cloudresourcemanager.googleapis.com`

[API reference](https://docs.cloud.google.com/resource-manager/reference/rest)

`compute.googleapis.com`

[API reference](https://docs.cloud.google.com/compute/docs/reference/rest/v1)

`container.googleapis.com`

[API reference](https://docs.cloud.google.com/kubernetes-engine/docs/reference/rest)

`connectors.googleapis.com`

[API reference](https://docs.cloud.google.com/integration-connectors/docs/reference/rest)

`dataform.googleapis.com`

[API reference](https://docs.cloud.google.com/dataform/reference/rest)

`dns.googleapis.com`

[API reference](https://docs.cloud.google.com/dns/docs/reference/rest/v1)

`firestore.googleapis.com`

[API reference](https://docs.cloud.google.com/firestore/docs/reference/rest)

`iap.googleapis.com`

[API reference](https://docs.cloud.google.com/iap/docs/reference/rest)

`integrations.googleapis.com`

[API reference](https://docs.cloud.google.com/application-integration/docs/reference/rest)

`logging.googleapis.com`

[API reference](https://docs.cloud.google.com/logging/docs/reference/rest)

`managedkafka.googleapis.com`

[API reference](https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest)

`networksecurity.googleapis.com`

[API reference](https://docs.cloud.google.com/firewall/docs/reference/network-security/rest)

`parametermanager.googleapis.com`

[API reference](https://docs.cloud.google.com/secret-manager/parameter-manager/docs/reference/rest)

`pubsublite.googleapis.com`

[API reference](https://docs.cloud.google.com/pubsub/lite/docs/reference/rest)

`secretmanager.googleapis.com`

[API reference](https://docs.cloud.google.com/secret-manager/docs/reference/rest)

`spanner.googleapis.com`

[API reference](https://docs.cloud.google.com/spanner/docs/reference/rest)

`sqladmin.googleapis.com`

[API reference](https://docs.cloud.google.com/sql/docs/mysql/admin-api)

`storage.googleapis.com`

[API reference](https://docs.cloud.google.com/storage/docs/json_api)

<span id="resource_type_values"></span>

## Resource type values

The following table lists the values that the resource type attribute can contain.

Resource type value

Reference

`apigee.googleapis.com/ApiProduct`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts)

`apigee.googleapis.com/ApiProductAttribute`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts.attributes)

`apigee.googleapis.com/Cache`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.caches)

`apigee.googleapis.com/Developer`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers)

`apigee.googleapis.com/DeveloperApp`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers.apps)

`apigee.googleapis.com/DeveloperAppAttribute`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers.apps.attributes)

`apigee.googleapis.com/DeveloperAttribute`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers/attributes)

`apigee.googleapis.com/Export`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.analytics.exports)

`apigee.googleapis.com/FlowHook`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.flowhooks)

`apigee.googleapis.com/KeyStore`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.keystores)

`apigee.googleapis.com/KeyStoreAlias`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.keystores.aliases)

`apigee.googleapis.com/KeyValueEntry`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps.entries)

`apigee.googleapis.com/KeyValueMap`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps)

`apigee.googleapis.com/Proxy`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/ApiProxy)

`apigee.googleapis.com/ProxyRevision`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/ApiProxyRevision)

`apigee.googleapis.com/Query`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.queries)

`apigee.googleapis.com/RatePlan`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts.rateplans)

`apigee.googleapis.com/Reference`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.references)

`apigee.googleapis.com/SharedFlow`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/SharedFlow)

`apigee.googleapis.com/SharedFlowRevision`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/SharedFlowRevision)

`apigee.googleapis.com/TargetServer`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.targetservers)

`apigee.googleapis.com/TraceSession`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.apis.revisions.debugsessions)

`apihub.googleapis.com/Api`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis)

`apihub.googleapis.com/Deployment`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.deployments)

`apihub.googleapis.com/Version`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions)

`apihub.googleapis.com/Spec`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.specs)

`apihub.googleapis.com/ApiOperation`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.operations)

`apihub.googleapis.com/Definition`

[Read more](https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.definitions)

`backupdr.googleapis.com/BackupVaults`

[Read more](https://docs.cloud.google.com/backup-disaster-recovery/docs/concepts/backup-vault)

`bigquery.googleapis.com/Dataset`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/datasets)

`bigquery.googleapis.com/Model`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/models)

`bigquery.googleapis.com/Routine`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/routines)

`bigquery.googleapis.com/Table`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/tables)

`bigqueryreservation.googleapis.com/Assignment`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.reservations.assignments)

`bigqueryreservation.googleapis.com/BiReservation`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/BiReservation)

`bigqueryreservation.googleapis.com/CapacityCommitment`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.capacityCommitments)

`bigqueryreservation.googleapis.com/Location`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations)

`bigqueryreservation.googleapis.com/Reservation`

[Read more](https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.reservations)

`bigtableadmin.googleapis.com/AppProfile`

[Read more](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.appProfiles)

`bigtableadmin.googleapis.com/Backup`

[Read more](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.clusters.backups)

`bigtableadmin.googleapis.com/Cluster`

[Read more](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.clusters)

`bigtableadmin.googleapis.com/Instance`

[Read more](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances)

`bigtableadmin.googleapis.com/Table`

[Read more](https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.tables)

`binaryauthorization.googleapis.com/Attestor`

[Read more](https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1/projects.attestors)

`binaryauthorization.googleapis.com/ContinuousValidationConfig`

[Read more](https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1alpha2/projects.continuousValidationConfig)

`binaryauthorization.googleapis.com/Policy`

[Read more](https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1/projects.policy)

`ces.googleapis.com/App`

[Read more](https://docs.cloud.google.com/customer-engagement-ai/conversational-agents/ps/reference/rest/v1/projects.locations.apps)

`ces.googleapis.com/Operation`

[Read more](https://docs.cloud.google.com/customer-engagement-ai/conversational-agents/ps/reference/rest/v1/projects.locations.operations)

`cloud.googleapis.com/Location` <sup>1</sup>

[Read more](https://docs.cloud.google.com/kms/docs/reference/rest/v1/projects.locations)

`cloudkms.googleapis.com/CryptoKey`

[Read more](https://docs.cloud.google.com/kms/docs/object-hierarchy#key)

`cloudkms.googleapis.com/CryptoKeyVersion`

[Read more](https://docs.cloud.google.com/kms/docs/object-hierarchy#key_version)

`cloudkms.googleapis.com/KeyRing`

[Read more](https://docs.cloud.google.com/kms/docs/object-hierarchy#key_ring)

`cloudresourcemanager.googleapis.com/Project` <sup>2</sup>

[Read more](https://docs.cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy#projects)

`compute.googleapis.com/BackendService`

[Read more](https://docs.cloud.google.com/load-balancing/docs/backend-service)

`compute.googleapis.com/Disk`

[Read more](https://docs.cloud.google.com/compute/docs/disks#pdspecs)

`compute.googleapis.com/Firewall`

[Read more](https://docs.cloud.google.com/vpc/docs/firewalls)

`compute.googleapis.com/ForwardingRule`

[Read more](https://docs.cloud.google.com/load-balancing/docs/forwarding-rule-concepts)

`compute.googleapis.com/GlobalForwardingRule`

[Read more](https://docs.cloud.google.com/load-balancing/docs/forwarding-rule-concepts)

`compute.googleapis.com/Image`

[Read more](https://docs.cloud.google.com/compute/docs/images)

`compute.googleapis.com/Instance`

[Read more](https://docs.cloud.google.com/compute/docs/instances)

`compute.googleapis.com/InstanceTemplate`

[Read more](https://docs.cloud.google.com/compute/docs/instance-templates)

`compute.googleapis.com/Snapshot`

[Read more](https://docs.cloud.google.com/compute/docs/disks/create-snapshots)

`compute.googleapis.com/TargetHttpProxy`

[Read more](https://docs.cloud.google.com/load-balancing/docs/target-proxies)

`compute.googleapis.com/TargetHttpsProxy`

[Read more](https://docs.cloud.google.com/load-balancing/docs/target-proxies)

`compute.googleapis.com/TargetSslProxy`

[Read more](https://docs.cloud.google.com/load-balancing/docs/target-proxies)

`compute.googleapis.com/TargetTcpProxy`

[Read more](https://docs.cloud.google.com/load-balancing/docs/target-proxies)

`connectors.googleapis.com/Connection`

[Read more](https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections)

`connectors.googleapis.com/ConnectionSchemaMetadata`

[Read more](https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections.connectionSchemaMetadata)

`connectors.googleapis.com/EndpointAttachment`

[Read more](https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.endpointAttachments)

`connectors.googleapis.com/EventSubscription`

[Read more](https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections.eventSubscriptions)

`connectors.googleapis.com/ManagedZone`

[Read more](https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.global.managedZones)

`container.googleapis.com/Cluster`

[Read more](https://docs.cloud.google.com/kubernetes-engine/docs/reference/rest/v1/projects.zones.clusters)

`dataform.googleapis.com/CompilationResult`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.compilationResults)

`dataform.googleapis.com/Location`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations)

`dataform.googleapis.com/ReleaseConfig`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.releaseConfigs)

`dataform.googleapis.com/Repository`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories)

`dataform.googleapis.com/WorkflowConfig`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workflowConfigs)

`dataform.googleapis.com/WorkflowInvocation`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workflowInvocations)

`dataform.googleapis.com/Workspace`

[Read more](https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workspaces)

`dns.googleapis.com/ResourceRecordSet`

[Read more](https://docs.cloud.google.com/dns/docs/reference/rest/v1/resourceRecordSets)

`firestore.googleapis.com/Database`

[Read more](https://docs.cloud.google.com/firestore/docs/reference/rest/v1/projects.databases)

`iap.googleapis.com/Tunnel`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/TunnelInstance`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/TunnelZone`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/Web`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/WebService`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/WebServiceVersion`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`iap.googleapis.com/WebType`

[Read more](https://docs.cloud.google.com/iap/docs/managing-access#resources_and_permissions)

`integrations.googleapis.com/AuthConfig`

[Read more](https://docs.cloud.google.com/application-integration/docs/reference/rest/v1/projects.locations.authConfigs)

`integrations.googleapis.com/Execution`

[Read more](https://docs.cloud.google.com/application-integration/docs/reference/rest/v1/projects.locations.integrations.executions)

`integrations.googleapis.com/Integration`

[Read more](https://docs.cloud.google.com/application-integration/docs/reference/rest/v1/projects.locations.integrations)

`integrations.googleapis.com/IntegrationVersion`

[Read more](https://docs.cloud.google.com/application-integration/docs/reference/rest/v1/projects.locations.integrations.versions)

`integrations.googleapis.com/Location`

n/a

`integrations.googleapis.com/Suspension`

[Read more](https://docs.cloud.google.com/application-integration/docs/reference/rest/v1/projects.locations.integrations.executions.suspensions)

`logging.googleapis.com/LogBucket`

[Read more](https://docs.cloud.google.com/logging/docs/reference/v2/rest/v2/projects.locations.buckets)

`logging.googleapis.com/LogView`

[Read more](https://docs.cloud.google.com/logging/docs/reference/v2/rest/v2/projects.locations.buckets.views)

`managedkafka.googleapis.com/Cluster`

[Read more](https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters)

`managedkafka.googleapis.com/ConsumerGroup`

[Read more](https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters.consumerGroups)

`managedkafka.googleapis.com/Operation`

[Read more](https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.operations)

`managedkafka.googleapis.com/Topic`

[Read more](https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters.topics)

`networksecurity.googleapis.com/AddressGroup`

[Read more](https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/projects.locations.addressGroups)

`networksecurity.googleapis.com/InterceptDeployment`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptDeployments)

`networksecurity.googleapis.com/InterceptDeploymentGroup`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptDeploymentGroups)

`networksecurity.googleapis.com/InterceptEndpointGroup`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptEndpointGroups)

`networksecurity.googleapis.com/InterceptEndpointGroupAssociation`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptEndpointGroupAssociations)

`networksecurity.googleapis.com/MirroringDeployment`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringDeployments)

`networksecurity.googleapis.com/MirroringDeploymentGroup`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringDeploymentGroups)

`networksecurity.googleapis.com/MirroringEndpointGroup`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringEndpointGroups)

`networksecurity.googleapis.com/MirroringEndpointGroupAssociation`

[Read more](https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringEndpointGroupAssociations)

`networksecurity.googleapis.com/SecurityProfile`

[Read more](https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/organizations.locations.securityProfiles)

`networksecurity.googleapis.com/SecurityProfileGroup`

[Read more](https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/organizations.locations.securityProfileGroups)

`parametermanager.googleapis.com/Parameter`

[Read more](https://docs.cloud.google.com/secret-manager/parameter-manager/docs/reference/rest/v1/projects.locations.parameters)

`parametermanager.googleapis.com/ParameterVersion`

[Read more](https://docs.cloud.google.com/secret-manager/parameter-manager/docs/reference/rest/v1/projects.locations.parameters.versions)

`pubsublite.googleapis.com/Location`

[Read more](https://docs.cloud.google.com/pubsub/lite/docs/reference/rest)

`pubsublite.googleapis.com/Subscription`

[Read more](https://docs.cloud.google.com/pubsub/lite/docs/reference/rest/v1/admin.projects.locations.subscriptions)

`pubsublite.googleapis.com/Topic`

[Read more](https://docs.cloud.google.com/pubsub/lite/docs/reference/rest/v1/admin.projects.locations.topics)

`secretmanager.googleapis.com/Secret`

[Read more](https://docs.cloud.google.com/secret-manager/docs/reference/rest/v1/projects.secrets)

`secretmanager.googleapis.com/SecretVersion`

[Read more](https://docs.cloud.google.com/secret-manager/docs/reference/rest/v1/projects.secrets.versions)

`spanner.googleapis.com/Backup`

[Read more](https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances.backups)

`spanner.googleapis.com/Database`

[Read more](https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances.databases)

`spanner.googleapis.com/Instance`

[Read more](https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances)

`sqladmin.googleapis.com/BackupRun`

[Read more](https://docs.cloud.google.com/sql/docs/mysql/admin-api/rest/v1/backupRuns)

`sqladmin.googleapis.com/Instance`

[Read more](https://docs.cloud.google.com/sql/docs/mysql/admin-api/rest/v1/instances)

`storage.googleapis.com/Bucket`

[Read more](https://docs.cloud.google.com/storage/docs/buckets)

`storage.googleapis.com/ManagedFolder`

[Read more](https://docs.cloud.google.com/storage/docs/managed-folders)

`storage.googleapis.com/Object`

[Read more](https://docs.cloud.google.com/storage/docs/objects)

<sup>1</sup> Cloud Key Management Service uses this resource type as the parent of [key ring](https://docs.cloud.google.com/kms/docs/object-hierarchy#key_ring) resources.

<sup>2</sup> Apigee uses this resource type as the parent of any resource that belongs to an Apigee organization.

<span id="resource_name_format"></span>

## Resource name format

The following table lists the format of each type of resource name attribute.

> **Note:** Ensure that you use the correct identifier for your project. Project IDs are alphanumeric, and project numbers are numeric. You can't substitute the project ID for the project number, or the project number for the project ID. For more information, see [Creating and managing projects](https://docs.cloud.google.com/resource-manager/docs/creating-managing-projects#before_you_begin) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Resource reference</th>
<th>Resource name format template</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts.attributes">API product attributes</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apiproducts/         product-id        /attributes/         attribute-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts">API products</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apiproducts/         product-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/ApiProxy">API proxies</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apis/         proxy-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps.entries">API proxy key-value map entries</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /api/         proxy-id        /keyvaluemaps/         keyvaluemap-id        /entries/         entry-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps">API proxy key-value maps</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apis/         proxy-id        /keyvaluemaps/         key-value-map-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/ApiProxyRevision">API proxy revisions</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apis/         proxy-id        /revisions/         revision-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.caches">caches</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /caches/         cache-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers.apps.attributes">developer app attributes</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /developers/         developer-id        /apps/         app-id        /attributes/         attribute-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers.apps">developer apps</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /developers/         developer-id        /apps/         app-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers/attributes">developer attributes</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /developers/         developer-id        /attributes/         attribute-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.developers">developers</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /developers/         developer-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps.entries">environment key-value map entries</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /keyvaluemaps/         keyvaluemap-id        /entries/         entry-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.keyvaluemaps">environment key-value maps</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment        /keyvaluemaps/         key-value-map-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.analytics.exports">exports</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /analytics/exports/         export-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.flowhooks">flow hooks</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /flowhooks/         flowhook-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.keystores.aliases">keystore aliases</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /keystores/         keystore-id        /aliases/         alias-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.keystores">keystores</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /keystores/         keystore-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.queries">queries</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /queries/         query-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.apiproducts.rateplans">rate plans</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /apiproducts/         product-id        /rateplans/         rate-plan-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.references">references</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /references/         reference-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/SharedFlowRevision">shared flow revisions</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /sharedflows/         shared-flow-id        /revisions/         revision-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/SharedFlow">shared flows</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /sharedflows/         shared-flow-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.targetservers">target servers</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /targetservers/         targetserver-id       </code></td>
</tr>
<tr class="even">
<td>Apigee <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apigee/rest/v1/organizations.environments.apis.revisions.debugsessions">trace (debug) sessions</a></td>
<td><code dir="ltr" translate="no">organizations/         organization-name        /environments/         environment-id        /apis/         proxy-id        /revisions/         revision-id        /debugsessions/         session-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis">apis</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apis/         api-id       </code></td>
</tr>
<tr class="even">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.deployments">deployments</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deployments/         deployment-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions">versions</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apis/         api-id        /versions/         version-id       </code></td>
</tr>
<tr class="even">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.specs">specs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apis/         api-id        /versions/         version-id        /specs/         spec-id       </code></td>
</tr>
<tr class="odd">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.operations">operations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apis/         api-id        /versions/         version-id        /operations/         operation-id       </code></td>
</tr>
<tr class="even">
<td>Apigee API Hub <a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apihub/rest/v1/projects.locations.apis.versions.definitions">definitions</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apis/         api-id        /versions/         version-id        /definitions/         definition-id       </code></td>
</tr>
<tr class="odd">
<td>Backup and DR Service <a href="https://docs.cloud.google.com/backup-disaster-recovery/docs/concepts/backup-vault">backupVaults</a> science</td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /backupVaults/         backup-vault-id       </code></td>
</tr>
<tr class="even">
<td>BigQuery <a href="https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/datasets">datasets</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /datasets/         dataset-id       </code></td>
</tr>
<tr class="odd">
<td>BigQuery <a href="https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/models">models</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /datasets/         dataset-id        /models/         model-id       </code></td>
</tr>
<tr class="even">
<td>BigQuery <a href="https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/routines">routines</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /datasets/         dataset-id        /routines/         routine-id       </code></td>
</tr>
<tr class="odd">
<td>BigQuery <a href="https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/tables">tables</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /datasets/         dataset-id        /tables/         table-id       </code></td>
</tr>
<tr class="even">
<td>BigQuery Reservation API <a href="https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.reservations.assignments">assignments</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /reservations/         reservation-id        /assignments/         assignment-id       </code></td>
</tr>
<tr class="odd">
<td>BigQuery Reservation API <a href="https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/BiReservation">BI reservations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /biReservation</code></td>
</tr>
<tr class="even">
<td>BigQuery Reservation API <a href="https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.capacityCommitments">capacity commitments</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /capacityCommitments/         capacity-commitment-id       </code></td>
</tr>
<tr class="odd">
<td>BigQuery Reservation API <a href="https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations">locations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id       </code></td>
</tr>
<tr class="even">
<td>BigQuery Reservation API <a href="https://docs.cloud.google.com/bigquery/docs/reference/reservations/rest/v1/projects.locations.reservations">reservations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /reservations/         reservation-id       </code></td>
</tr>
<tr class="odd">
<td>Binary Authorization <a href="https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1/projects.attestors">attestors</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /attestors/         attestor-id       </code></td>
</tr>
<tr class="even">
<td>Binary Authorization <a href="https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1alpha2/projects.continuousValidationConfig">continuous validation configs</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /continuousValidationConfig</code></td>
</tr>
<tr class="odd">
<td>Binary Authorization <a href="https://docs.cloud.google.com/binary-authorization/docs/reference/rest/v1/projects.policy">policies</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /policy</code></td>
</tr>
<tr class="even">
<td>Customer Experience Agent Studio <a href="https://docs.cloud.google.com/customer-engagement-ai/conversational-agents/ps/reference/rest/v1/projects.locations.apps">apps</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /apps/         app-id       </code></td>
</tr>
<tr class="odd">
<td>Customer Experience Agent Studio <a href="https://docs.cloud.google.com/customer-engagement-ai/conversational-agents/ps/reference/rest/v1/projects.locations.operations">operations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /operations/         operation-id       </code></td>
</tr>
<tr class="even">
<td>Bigtable <a href="https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.appProfiles">appProfiles</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /appProfiles/         appProfile-id       </code></td>
</tr>
<tr class="odd">
<td>Bigtable <a href="https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.clusters.backups">backups</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /clusters/         cluster-id        /backups/         backup-id       </code></td>
</tr>
<tr class="even">
<td>Bigtable <a href="https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.clusters">clusters</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /clusters/         cluster-id       </code></td>
</tr>
<tr class="odd">
<td>Bigtable <a href="https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances">instances</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id       </code></td>
</tr>
<tr class="even">
<td>Bigtable <a href="https://docs.cloud.google.com/bigtable/docs/reference/admin/rest/v2/projects.instances.tables">tables</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /tables/         table-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines.automationRuns">automation runs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id        /automationRuns/         automation-run-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines.automations">automations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id        /automations/         automation-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.customTargetTypes">custom target types</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /customTargetTypes/         custom-target-type-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines">delivery pipelines</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines.releases.rollouts.jobRuns">job runs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id        /releases/         release-id        /rollouts/         rollout-id        /jobRuns/         job-run-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines.releases">releases</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id        /releases/         release-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.deliveryPipelines.releases.rollouts">rollouts</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /deliveryPipelines/         delivery-pipeline-id        /releases/         release-id        /rollouts/         rollout-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Deploy <a href="https://docs.cloud.google.com/deploy/docs/api/reference/rest/v1/projects.locations.targets">targets</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /targets/         target-id       </code></td>
</tr>
<tr class="odd">
<td>Firestore <a href="https://docs.cloud.google.com/firestore/docs/reference/rest/v1/projects.databases">databases</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /databases/         database-id       </code></td>
</tr>
<tr class="even">
<td>Cloud NGFW <a href="https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/projects.locations.addressGroups">address groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /addressGroups/         address-group-name       </code><br />
<code dir="ltr" translate="no">organizations/         organization-id        /locations/         location        /addressGroups/         address-group-name       </code></td>
</tr>
<tr class="odd">
<td>Cloud NGFW <a href="https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/projects.locations.securityProfileGroups">security profile groups</a> <sup>1</sup></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /securityProfileGroups/         security-profile-group-id       </code></td>
</tr>
<tr class="even">
<td>Cloud NGFW <a href="https://docs.cloud.google.com/firewall/docs/reference/network-security/rest/v1/projects.locations.securityProfiles">security profiles</a> <sup>1</sup></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /securityProfiles/         security-profile-id       </code></td>
</tr>
<tr class="odd">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptDeploymentGroups">intercept deployment groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /interceptDeploymentGroups/         intercept-deployment-group-id       </code></td>
</tr>
<tr class="even">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptDeployments">intercept deployments</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /interceptDeployments/         intercept-deployment-id       </code></td>
</tr>
<tr class="odd">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptEndpointGroupAssociations">intercept endpoint group associations</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /interceptEndpointGroupAssociations/         intercept-endpoint-group-association-id       </code></td>
</tr>
<tr class="even">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.interceptEndpointGroups">intercept endpoint groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /interceptEndpoints/         intercept-endpoint-group-id       </code></td>
</tr>
<tr class="odd">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringDeploymentGroups">mirroring deployment groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /mirroringDeploymentGroups/         mirroring-deployment-group-id       </code></td>
</tr>
<tr class="even">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringDeployments">mirroring deployments</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /mirroringDeployments/         mirroring-deployment-id       </code></td>
</tr>
<tr class="odd">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringEndpointGroupAssociations">mirroring endpoint group associations</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /mirroringEndpointGroupAssociations/         mirroring-endpoint-group-association-id       </code></td>
</tr>
<tr class="even">
<td>Network Security Integration <a href="https://docs.cloud.google.com/network-security-integration/docs/reference/rest/v1/projects.locations.mirroringEndpointGroups">mirroring endpoint groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /mirroringEndpoints/         mirroring-endpoint-group-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Key Management Service <a href="https://docs.cloud.google.com/kms/docs/reference/rest/v1/projects.locations.keyRings.cryptoKeys">crypto keys</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /keyRings/         keyring-id        /cryptoKeys/         cryptokey-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Key Management Service <a href="https://docs.cloud.google.com/kms/docs/reference/rest/v1/projects.locations.keyRings.cryptoKeys.cryptoKeyVersions">crypto key versions</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /keyRings/         keyring-id        /cryptoKeys/         cryptokey-id        /cryptoKeyVersions/         cryptokeyversion-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Key Management Service <a href="https://docs.cloud.google.com/kms/docs/reference/rest/v1/projects.locations.keyRings">key rings</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /keyRings/         keyring-id       </code></td>
</tr>
<tr class="even">
<td>Cloud Logging <a href="https://docs.cloud.google.com/logging/docs/reference/v2/rest/v2/projects.locations.buckets">log buckets</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /buckets/         bucket-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Logging <a href="https://docs.cloud.google.com/logging/docs/reference/v2/rest/v2/projects.locations.buckets.views">log views</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location-id        /buckets/         bucket-id        /views/         view-id       </code></td>
</tr>
<tr class="even">
<td>Spanner <a href="https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances.backups">backups</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /backups/         backup-id       </code></td>
</tr>
<tr class="odd">
<td>Spanner <a href="https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances.databases">databases</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /databases/         database-id       </code></td>
</tr>
<tr class="even">
<td>Spanner <a href="https://docs.cloud.google.com/spanner/docs/reference/rest/v1/projects.instances">instances</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud SQL <a href="https://docs.cloud.google.com/sql/docs/mysql/admin-api/rest/v1/backupRuns">backup runs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id        /backupRuns/         backup-id       </code></td>
</tr>
<tr class="even">
<td>Cloud SQL <a href="https://docs.cloud.google.com/sql/docs/mysql/admin-api/rest/v1/instances">instances</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /instances/         instance-id       </code></td>
</tr>
<tr class="odd">
<td>Cloud Storage <a href="https://docs.cloud.google.com/storage/docs/json_api/v1/buckets">buckets</a> <sup>2</sup></td>
<td><code dir="ltr" translate="no">projects/_/buckets/         bucket-name       </code></td>
</tr>
<tr class="even">
<td>Cloud Storage <a href="https://docs.cloud.google.com/storage/docs/json_api/v1/managedFolder">managed folders</a> <sup>2, 3</sup></td>
<td><code dir="ltr" translate="no">projects/_/buckets/         bucket-name        /managedFolders/         managed-folder-name       </code></td>
</tr>
<tr class="odd">
<td>Cloud Storage <a href="https://docs.cloud.google.com/storage/docs/json_api/v1/objects">objects</a> <sup>2, 4</sup></td>
<td><code dir="ltr" translate="no">projects/_/buckets/         bucket-name        /objects/         object-name       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/backendServices">global backend services</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/backendServices/         backend-service-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/backendServices">regional backend services</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /regions/         region-id        /backendServices/         backend-service-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/firewalls">firewalls</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/firewalls/         firewall-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/globalForwardingRules">global forwarding rules</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/forwardingRules/         forwarding-rule-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/forwardingRules">regional forwarding rules</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /regions/         region-id        /forwardingRules/         forwarding-rule-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/images">images</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/images/         image-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/instanceTemplates">instance templates</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/instanceTemplates/         instance-template-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/instances">instances</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /zones/         zone-id        /instances/         instance-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/regionDisks">regional persistent disks</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /regions/         region-id        /disks/         disk-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/disks">zonal persistent disks</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /zones/         zone-id        /disks/         disk-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/snapshots">snapshots</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/snapshots/         snapshot-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/targetHttpProxies">global target HTTP proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/targetHttpProxies/         target-http-proxy-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/regionTargetHttpProxies">regional target HTTP proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /regions/         region-id        /targetHttpProxies/         target-http-proxy-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/targetHttpsProxies">global target HTTPS proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/targetHttpsProxies/         target-https-proxy-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/regionTargetHttpsProxies">regional target HTTPS proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /regions/         region-id        /targetHttpsProxies/         target-https-proxy-id       </code></td>
</tr>
<tr class="odd">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/targetSslProxies">target SSL proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/targetSslProxies/         target-ssl-proxy-id       </code></td>
</tr>
<tr class="even">
<td>Compute Engine <a href="https://docs.cloud.google.com/compute/docs/reference/rest/v1/targetTcpProxies">target TCP proxies</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /global/targetTcpProxies/         target-tcp-proxy-id       </code></td>
</tr>
<tr class="odd">
<td>Google Kubernetes Engine <a href="https://docs.cloud.google.com/kubernetes-engine/docs/reference/rest/v1/projects.zones.clusters">zonal clusters</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /zones/         zone        /clusters/         cluster-id       </code></td>
</tr>
<tr class="even">
<td>Google Kubernetes Engine <a href="https://docs.cloud.google.com/kubernetes-engine/docs/reference/rest/v1/projects.locations.clusters">regional clusters</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /clusters/         cluster-id       </code></td>
</tr>
<tr class="odd">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.compilationResults">compilation results</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository        /compilationResults/         compilation-result       </code></td>
</tr>
<tr class="even">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations">locations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location       </code></td>
</tr>
<tr class="odd">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.releaseConfigs">release configs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository        /releaseConfigs/         release-config       </code></td>
</tr>
<tr class="even">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories">repositories</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository       </code></td>
</tr>
<tr class="odd">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workflowConfigs">workflow configs</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository        /workflowConfigs/         workflow-config       </code></td>
</tr>
<tr class="even">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workflowInvocations">workflow invocations</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository        /workflowInvocations/         workflow-invocation       </code></td>
</tr>
<tr class="odd">
<td>Dataform <a href="https://docs.cloud.google.com/dataform/reference/rest/v1beta1/projects.locations.repositories.workspaces">workspaces</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /repositories/         repository        /workspaces/         workspace       </code></td>
</tr>
<tr class="even">
<td>Cloud DNS <a href="https://docs.cloud.google.com/dns/docs/reference/rest/v1/resourceRecordSets">resource record sets</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /managedZones/         zone-id        /rrsets/         rrset-name        /         rrset-type       </code></td>
</tr>
<tr class="odd">
<td>Integration Connectors <a href="https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections">connections</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /connections/         connection-name       </code></td>
</tr>
<tr class="even">
<td>Integration Connectors <a href="https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections.connectionSchemaMetadata">connection schema metadata</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /connections/         connection-name        /connectionSchemaMetadata</code></td>
</tr>
<tr class="odd">
<td>Integration Connectors <a href="https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.endpointAttachments">endpoint attachments</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /endpointAttachments/         endpoint-attachment-name       </code></td>
</tr>
<tr class="even">
<td>Integration Connectors <a href="https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.connections.eventSubscriptions">event subscriptions</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/         location        /eventSubscriptions/         event-subscription-name       </code></td>
</tr>
<tr class="odd">
<td>Integration Connectors <a href="https://docs.cloud.google.com/integration-connectors/docs/reference/rest/v1/projects.locations.global.managedZones">managed zones</a></td>
<td><code dir="ltr" translate="no">projects/         project-id        /locations/global/managedZones/         managed-zone-name       </code></td>
</tr>
<tr class="even">
<td>Google Cloud Managed Service for Apache Kafka <a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters">clusters</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /clusters/         cluster-name       </code></td>
</tr>
<tr class="odd">
<td>Google Cloud Managed Service for Apache Kafka <a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters.consumerGroups">consumer groups</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /clusters/         cluster-name        /consumerGroups/         consumer-group       </code></td>
</tr>
<tr class="even">
<td>Google Cloud Managed Service for Apache Kafka <a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.operations">operations</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /operations/         operation       </code></td>
</tr>
<tr class="odd">
<td>Google Cloud Managed Service for Apache Kafka <a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/reference/rest/v1/projects.locations.clusters.topics">topics</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /clusters/         cluster-name        /topics/         topic-name       </code></td>
</tr>
<tr class="even">
<td>Parameter Manager <a href="https://docs.cloud.google.com/secret-manager/parameter-manager/docs/reference/rest/v1/projects.locations.parameters">parameters</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /parameters/         parameter-id       </code></td>
</tr>
<tr class="odd">
<td>Parameter Manager <a href="https://docs.cloud.google.com/secret-manager/parameter-manager/docs/reference/rest/v1/projects.locations.parameters.versions">parameter versions</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /parameters/         parameter-id        /versions/version-id</code></td>
</tr>
<tr class="even">
<td>Pub/Sub Lite <a href="https://docs.cloud.google.com/pubsub/lite/docs/reference/rest">locations</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location       </code></td>
</tr>
<tr class="odd">
<td>Pub/Sub Lite <a href="https://docs.cloud.google.com/pubsub/lite/docs/reference/rest/v1/admin.projects.locations.subscriptions">subscriptions</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /subscriptions/         subscription-id       </code></td>
</tr>
<tr class="even">
<td>Pub/Sub Lite <a href="https://docs.cloud.google.com/pubsub/lite/docs/reference/rest/v1/admin.projects.locations.topics">topics</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /locations/         location        /topics/         topic-id       </code></td>
</tr>
<tr class="odd">
<td>Resource Manager <a href="https://docs.cloud.google.com/resource-manager/reference/rest/v3/organizations">organizations</a> <sup>5</sup></td>
<td><code dir="ltr" translate="no">organizations/         organization-name       </code></td>
</tr>
<tr class="even">
<td>Secret Manager <a href="https://docs.cloud.google.com/secret-manager/docs/reference/rest/v1/projects.secrets">secrets</a></td>
<td><code dir="ltr" translate="no">projects/         project-number        /secrets/         secret-id       </code></td>
</tr>
<tr class="odd">
<td>Secret Manager <a href="https://docs.cloud.google.com/secret-manager/docs/reference/rest/v1/projects.secrets.versions">secret versions</a> <sup>6</sup></td>
<td><code dir="ltr" translate="no">projects/         project-number        /secrets/         secret-id        /versions/         secret-version       </code></td>
</tr>
</tbody>
</table>

<sup>1</sup> IAM Conditions only supports project-level Cloud NGFW resources. Organization-level Cloud NGFW resources are not supported.

<sup>2</sup> For Cloud Storage, resource names contain an underscore ( `_` ) rather than a project ID. You *cannot* replace the underscore with a project ID, project name, or project number.

<sup>3</sup> Use the entire managed folder name, including forward slashes. In Cloud Storage, these characters are [part of the managed folder name](https://docs.cloud.google.com/storage/docs/managed-folders#managed_folder_names) , not path separators.

<sup>4</sup> Use the entire object name, including forward slashes. In Cloud Storage, these characters are [part of the object name](https://docs.cloud.google.com/storage/docs/objects#naming) , not path separators.

<sup>5</sup> Apigee uses this format when you list any type of resource that belongs to an Apigee organization.

<sup>6</sup> If a condition evaluates the resource name for a secret version, the secret version in the request must exactly match the secret version in the condition for the condition to be satisfied. For example, if the version in the condition is `latest` , only a request with the version `latest` satisfies the condition; a request with the version `3` does not satisfy the condition, even if `3` is the latest version.

## Resource tags

You can attach [tags](https://docs.cloud.google.com/iam/docs/tags-access-control) to organizations, projects, and folders. Any Google Cloud resource can inherit tags from these higher-level resources.

You can use a few different types of identifiers to refer to tag keys and values:

  - A *permanent ID* , which is globally unique and can never be reused. For example, a tag key could have the permanent ID `tagKeys/123456789012` , and a tag value could have the permanent ID `tagValues/567890123456` .
  - A *short name* . The short name for each key must be unique within the project or organization under which the key is defined, and the short name for each value must be unique for its associated key. For example, a tag key could have the short name `env` , and a tag value could have the short name `prod` .
  - A *namespaced name* , which adds your organization's numeric ID or project's ID to the short name of a tag key. For example, a tag key created for an organization could have the namespaced name `123456789012/env` . To learn how to get your organization ID, see [Getting your organization resource ID](https://docs.cloud.google.com/resource-manager/docs/creating-managing-organization#retrieving_your_organization_id) . A tag key created for a project could have the namespaced name `myproject/env` . To learn how to get your project ID, see [Identifying projects](https://docs.cloud.google.com/resource-manager/docs/creating-managing-projects#identifying_projects) .

The specific identifiers depend on the tag keys and values that you have created for your organization. To learn how to list the tag keys and values that are available to you, see [Listing tag keys](https://docs.cloud.google.com/resource-manager/docs/tags/tags-creating-and-managing#listing_keys) and [Listing tag values](https://docs.cloud.google.com/resource-manager/docs/tags/tags-creating-and-managing#listing_values) .
