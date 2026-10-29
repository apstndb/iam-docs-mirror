---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/wiz
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/wiz
title: Wiz roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Wiz. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Wiz roles

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
<td>Wiz Cloud Inventory Viewer
<p>( <code>roles/ wiz.cloudInventoryViewer</code> )</p>
<p>Provides broad read-only access to discover, list, and read resource metadata and configuration across Google Cloud. Intended for automated cloud asset discovery and inventory, configuration analysis, and building a unified security view of cloud infrastructure.</p></td>
<td><p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>agentregistry.locations.list</code></p>
<p><code>aiplatform.agents.get</code></p>
<p><code>aiplatform.agents.list</code></p>
<p><code>aiplatform. batchPredictionJobs. list</code></p>
<p><code>aiplatform.cacheConfigs.get</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform. datasetVersions. list</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform. deploymentResourcePools. list</code></p>
<p><code>aiplatform. endpoints. getIamPolicy</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform.featureGroups.list</code></p>
<p><code>aiplatform. featureOnlineStores. list</code></p>
<p><code>aiplatform.featureViews.list</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.indexEndpoints.get</code></p>
<p><code>aiplatform.indexEndpoints.list</code></p>
<p><code>aiplatform.indexes.list</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. list</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform.nasJobs.list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform. notebookRuntimes. list</code></p>
<p><code>aiplatform. persistentResources. list</code></p>
<p><code>aiplatform.pipelineJobs.list</code></p>
<p><code>aiplatform.ragCorpora.list</code></p>
<p><code>aiplatform.ragFiles.list</code></p>
<p><code>aiplatform. reasoningEngines. list</code></p>
<p><code>aiplatform.schedules.list</code></p>
<p><code>aiplatform. specialistPools. list</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>analyticshub. subscriptions. list</code></p>
<p><code>apigateway.apiconfigs.get</code></p>
<p><code>apigateway.apiconfigs.list</code></p>
<p><code>apigateway.gateways.list</code></p>
<p><code>apigee.deployments.list</code></p>
<p><code>apigee. envgroupattachments. list</code></p>
<p><code>apigee.envgroups.list</code></p>
<p><code>apigee.environments.get</code></p>
<p><code>apigee.environments.list</code></p>
<p><code>apigee.organizations.get</code></p>
<p><code>apigee.organizations.list</code></p>
<p><code>apigee.proxies.list</code></p>
<p><code>apigee.proxyrevisions.get</code></p>
<p><code>apigee.proxyrevisions.list</code></p>
<p><code>apihub.apiHubInstances.get</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apiOperations.list</code></p>
<p><code>apihub.apis.get</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.dependencies.list</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub.externalApis.list</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub.specs.get</code></p>
<p><code>apihub.specs.list</code></p>
<p><code>apihub.versions.get</code></p>
<p><code>apihub.versions.list</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.locations.list</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>artifactregistry.locations.*</code></p>
<ul>
<li><code>artifactregistry.locations.get</code></li>
<li><code>artifactregistry. locations. list</code></li>
</ul>
<p><code>artifactregistry.packages.get</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. getIamPolicy</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry.versions.get</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. dataSourceReferences. list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>baremetalsolution. instances. list</code></p>
<p><code>bigquery.connections.list</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.transfers.get</code></p>
<p><code>bigtable.backups.list</code></p>
<p><code>bigtable.clusters.list</code></p>
<p><code>bigtable. instances. getIamPolicy</code></p>
<p><code>bigtable.instances.list</code></p>
<p><code>bigtable.tables.get</code></p>
<p><code>bigtable.tables.getIamPolicy</code></p>
<p><code>bigtable.tables.list</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. locations. list</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig. clients. listWithSecrets</code></p>
<p><code>cloud.locations.get</code></p>
<p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.connections.list</code></p>
<p><code>cloudbuild.workerpools.list</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions. functions. sourceCodeGet</code></p>
<p><code>cloudkms. cryptoKeyVersions. list</code></p>
<p><code>cloudkms. cryptoKeys. getIamPolicy</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms.importJobs.list</code></p>
<p><code>cloudkms.keyRings.getIamPolicy</code></p>
<p><code>cloudkms.keyRings.list</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>cloudscheduler.jobs.list</code></p>
<p><code>cloudscheduler.locations.list</code></p>
<p><code>cloudsecurityscanner. scans. list</code></p>
<p><code>cloudsql.backupRuns.list</code></p>
<p><code>cloudsql.databases.list</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>cloudsql.users.get</code></p>
<p><code>cloudsql.users.list</code></p>
<p><code>cloudtasks.locations.list</code></p>
<p><code>cloudtasks.queues.list</code></p>
<p><code>cloudtranslate. customModels. list</code></p>
<p><code>cloudtranslate.datasets.list</code></p>
<p><code>cloudtranslate.glossaries.list</code></p>
<p><code>cloudtranslate.locations.list</code></p>
<p><code>composer.environments.list</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.commitments.list</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.getIamPolicy</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectGroups. list</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute.nodeTemplates.list</code></p>
<p><code>compute. orgVmExtensionPolicies. list</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reservations.list</code></p>
<p><code>compute.resourcePolicies.get</code></p>
<p><code>compute. resourcePolicies. getIamPolicy</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. vmExtensionPolicies. list</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors. eventSubscriptions. list</code></p>
<p><code>connectors.locations.list</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>container. clusterRoleBindings. get</code></p>
<p><code>container. clusterRoleBindings. list</code></p>
<p><code>container.clusterRoles.get</code></p>
<p><code>container.clusterRoles.list</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.configMaps.get</code></p>
<p><code>container.configMaps.list</code></p>
<p><code>container. controllerRevisions. list</code></p>
<p><code>container.cronJobs.get</code></p>
<p><code>container.cronJobs.list</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container.daemonSets.get</code></p>
<p><code>container.daemonSets.list</code></p>
<p><code>container.deployments.get</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.endpoints.list</code></p>
<p><code>container.ingresses.get</code></p>
<p><code>container.ingresses.list</code></p>
<p><code>container.jobs.get</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container.namespaces.get</code></p>
<p><code>container.namespaces.list</code></p>
<p><code>container.networkPolicies.list</code></p>
<p><code>container.nodes.list</code></p>
<p><code>container. persistentVolumeClaims. list</code></p>
<p><code>container. persistentVolumes. list</code></p>
<p><code>container.pods.get</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.replicaSets.get</code></p>
<p><code>container.replicaSets.list</code></p>
<p><code>container.roleBindings.get</code></p>
<p><code>container.roleBindings.list</code></p>
<p><code>container.roles.get</code></p>
<p><code>container.roles.list</code></p>
<p><code>container.secrets.get</code></p>
<p><code>container.secrets.list</code></p>
<p><code>container.serviceAccounts.get</code></p>
<p><code>container.serviceAccounts.list</code></p>
<p><code>container.services.get</code></p>
<p><code>container.services.list</code></p>
<p><code>container.statefulSets.get</code></p>
<p><code>container.statefulSets.list</code></p>
<p><code>container.storageClasses.list</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. validatingWebhookConfigurations. list</code></p>
<p><code>dataflow.jobs.get</code></p>
<p><code>dataflow.jobs.list</code></p>
<p><code>dataform.config.get</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.releaseConfigs.list</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform.workflowConfigs.list</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion.locations.list</code></p>
<p><code>datamigration. connectionprofiles. list</code></p>
<p><code>datamigration.locations.list</code></p>
<p><code>datamigration. migrationjobs. list</code></p>
<p><code>datamigration. privateconnections. list</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.entities.list</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex.lakes.list</code></p>
<p><code>dataplex.locations.list</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>dataproc. autoscalingPolicies. list</code></p>
<p><code>dataproc.batches.list</code></p>
<p><code>dataproc.clusters.getIamPolicy</code></p>
<p><code>dataproc.clusters.list</code></p>
<p><code>dataproc.sessionTemplates.list</code></p>
<p><code>dataproc. workflowTemplates. list</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastream. connectionProfiles. list</code></p>
<p><code>datastream.locations.list</code></p>
<p><code>datastream. privateConnections. list</code></p>
<p><code>datastream.streams.list</code></p>
<p><code>developerconnect. accountConnectors. list</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect. locations. list</code></p>
<p><code>developerconnect.users.list</code></p>
<p><code>dialogflow.agents.get</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.encryptionspec.get</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow. securitySettings. get</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>discoveryengine.agents.get</code></p>
<p><code>discoveryengine.agents.list</code></p>
<p><code>discoveryengine.assistants.get</code></p>
<p><code>discoveryengine. assistants. list</code></p>
<p><code>discoveryengine. dataStores. list</code></p>
<p><code>discoveryengine.documents.list</code></p>
<p><code>discoveryengine.engines.list</code></p>
<p><code>dlp.connections.list</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.storedInfoTypes.list</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.responsePolicies.get</code></p>
<p><code>dns.responsePolicies.list</code></p>
<p><code>dns.responsePolicyRules.get</code></p>
<p><code>dns.responsePolicyRules.list</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>eventarc. channelConnections. get</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleChannelConfigs. get</code></p>
<p><code>eventarc.locations.list</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>file.backups.list</code></p>
<p><code>file.instances.list</code></p>
<p><code>file.locations.list</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations. list</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebaserules.rulesets.get</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>ftp.locations.list</code></p>
<p><code>ftp.servers.list</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup.backups.list</code></p>
<p><code>gkebackup.restorePlans.list</code></p>
<p><code>healthcare.consentStores.list</code></p>
<p><code>healthcare.consents.list</code></p>
<p><code>healthcare.datasets.list</code></p>
<p><code>healthcare.dicomStores.list</code></p>
<p><code>healthcare.fhirStores.list</code></p>
<p><code>healthcare.hl7V2Stores.list</code></p>
<p><code>healthcare.locations.list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iap.tunnelDestGroups.list</code></p>
<p><code>iap.web.getIamPolicy</code></p>
<p><code>ids.endpoints.list</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>looker.instances.get</code></p>
<p><code>looker.instances.list</code></p>
<p><code>looker.locations.list</code></p>
<p><code>lustre.instances.list</code></p>
<p><code>lustre.locations.list</code></p>
<p><code>managedidentities.backups.list</code></p>
<p><code>managedidentities.domains.list</code></p>
<p><code>managedidentities. peerings. list</code></p>
<p><code>managedidentities. sqlintegrations. list</code></p>
<p><code>memcache.instances.list</code></p>
<p><code>memcache.locations.list</code></p>
<p><code>memorystore.instances.list</code></p>
<p><code>memorystore.locations.*</code></p>
<ul>
<li><code>memorystore.locations.get</code></li>
<li><code>memorystore.locations.list</code></li>
</ul>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore.locations.list</code></p>
<p><code>metastore.services.list</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>netapp.activeDirectories.list</code></p>
<p><code>netapp.backupPolicies.list</code></p>
<p><code>netapp.backupVaults.list</code></p>
<p><code>netapp.backups.list</code></p>
<p><code>netapp.hostGroups.list</code></p>
<p><code>netapp.kmsConfigs.get</code></p>
<p><code>netapp.kmsConfigs.list</code></p>
<p><code>netapp.locations.list</code></p>
<p><code>netapp.replications.list</code></p>
<p><code>netapp.snapshots.list</code></p>
<p><code>netapp.storagePools.list</code></p>
<p><code>netapp.volumes.list</code></p>
<p><code>networkconnectivity. groups. list</code></p>
<p><code>networkconnectivity.hubs.list</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. locations. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. list</code></p>
<p><code>networkconnectivity. serviceConnectionPolicies. list</code></p>
<p><code>networkconnectivity. spokes. list</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs. list</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. backendAuthenticationConfigs. list</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity. interceptDeploymentGroups. list</code></p>
<p><code>networksecurity. interceptEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. interceptEndpointGroups. list</code></p>
<p><code>networksecurity.locations.list</code></p>
<p><code>networksecurity. mirroringDeploymentGroups. list</code></p>
<p><code>networksecurity. mirroringEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. mirroringEndpointGroups. list</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. lbRouteExtensions. list</code></p>
<p><code>networkservices. lbTrafficExtensions. list</code></p>
<p><code>networkservices.locations.list</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices. serviceBindings. list</code></p>
<p><code>networkservices. serviceLbPolicies. list</code></p>
<p><code>networkservices.tcpRoutes.list</code></p>
<p><code>networkservices.tlsRoutes.list</code></p>
<p><code>networkservices. wasmPlugins. list</code></p>
<p><code>notebooks. instances. getIamPolicy</code></p>
<p><code>notebooks.instances.list</code></p>
<p><code>notebooks.locations.list</code></p>
<p><code>notebooks. runtimes. getIamPolicy</code></p>
<p><code>notebooks.runtimes.list</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.locations.list</code></p>
<p><code>oracledatabase. autonomousDatabases. list</code></p>
<p><code>oracledatabase.locations.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>osconfig.patchDeployments.list</code></p>
<p><code>parametermanager. locations. list</code></p>
<p><code>parametermanager. parameters. list</code></p>
<p><code>policyanalyzer. serviceAccountKeyLastAuthenticationActivities. query</code></p>
<p><code>policyanalyzer. serviceAccountLastAuthenticationActivities. query</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.locations.list</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub. subscriptions. getIamPolicy</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>recaptchaenterprise.keys.list</code></p>
<p><code>recommender. iamPolicyInsights. list</code></p>
<p><code>recommender. iamPolicyRecommendations. get</code></p>
<p><code>recommender. iamPolicyRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountInsights. list</code></p>
<p><code>redis.backupCollections.list</code></p>
<p><code>redis.backups.list</code></p>
<p><code>redis.clusters.list</code></p>
<p><code>redis.instances.list</code></p>
<p><code>redis.locations.list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>run.executions.get</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.revisions.get</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>secretmanager. secrets. getIamPolicy</code></p>
<p><code>secretmanager.secrets.list</code></p>
<p><code>secretmanager.versions.list</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory. locations. list</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>servicemanagement.services.get</code></p>
<p><code>servicemanagement. services. list</code></p>
<p><code>serviceusage. catalogs. listMembers</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.listApis</code></p>
<p><code>serviceusage. services. listDependentServices</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>spanner.backupSchedules.list</code></p>
<p><code>spanner.backups.list</code></p>
<p><code>spanner.databases.getIamPolicy</code></p>
<p><code>spanner.databases.list</code></p>
<p><code>spanner.instances.getIamPolicy</code></p>
<p><code>spanner.instances.list</code></p>
<p><code>speech.customClasses.list</code></p>
<p><code>speech.locations.list</code></p>
<p><code>speech.phraseSets.list</code></p>
<p><code>speech.recognizers.list</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storageinsights. datasetConfigs. list</code></p>
<p><code>storageinsights.locations.list</code></p>
<p><code>storagetransfer. agentpools. list</code></p>
<p><code>storagetransfer.jobs.list</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch.indexes.list</code></p>
<p><code>vectorsearch.locations.list</code></p>
<p><code>vmmigration. datacenterConnectors. list</code></p>
<p><code>vmmigration.imageImports.list</code></p>
<p><code>vmmigration.locations.list</code></p>
<p><code>vmmigration.sources.list</code></p>
<p><code>vpcaccess.connectors.list</code></p>
<p><code>vpcaccess.locations.list</code></p>
<p><code>workflows.locations.list</code></p>
<p><code>workflows.workflows.list</code></p>
<p><code>workloadmanager. evaluations. list</code></p>
<p><code>workloadmanager.locations.list</code></p>
<p><code>workstations. workstationClusters. list</code></p>
<p><code>workstations. workstationConfigs. list</code></p>
<p><code>workstations. workstations. getIamPolicy</code></p>
<p><code>workstations.workstations.list</code></p></td>
</tr>
<tr class="even">
<td>Wiz Data Security Manager
<p>( <code>roles/ wiz.dataSecurityScanner</code> )</p>
<p>Provides access to manage dedicated inventory buckets, configure Storage Insights reporting, and trigger security scans across cloud databases and storage systems. Intended for orchestrating automated data discovery and data classification campaigns.</p></td>
<td><p><code>alloydb.backups.create</code></p>
<p><code>alloydb.backups.delete</code></p>
<p><code>alloydb.backups.get</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb.clusters.get</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>cloudsql.backupRuns.create</code></p>
<p><code>cloudsql.backupRuns.delete</code></p>
<p><code>cloudsql.backupRuns.get</code></p>
<p><code>cloudsql.backupRuns.list</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage. buckets. getObjectInsights</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storageinsights. reportConfigs. update</code></p></td>
</tr>
<tr class="odd">
<td>Wiz Forensics Responder
<p>( <code>roles/ wiz.forensicsResponder</code> )</p>
<p>Provides administrative capabilities to create, label, analyze, and safely delete Compute Engine snapshots.</p></td>
<td><p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.snapshots.create</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.useReadOnly</code></p></td>
</tr>
<tr class="even">
<td>Wiz Serverless &amp; Container Image Registry Scanner
<p>( <code>roles/ wiz.serverlessImageRegistryScanner</code> )</p>
<p>Provides read and download access to Artifact Registry repositories, Cloud Storage objects, Cloud Run revisions, and Cloud Functions source code to scan serverless and container workloads.</p></td>
<td><p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudfunctions. functions. sourceCodeGet</code></p>
<p><code>run.revisions.get</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Wiz Workload Scanner
<p>( <code>roles/ wiz.workloadScanner</code> )</p>
<p>Provides read-only access to disks, images, and snapshots for agentless workload scanning. Intended for automated vulnerability management, malware detection, and secrets scanning.</p></td>
<td><p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToEncrypt</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Wiz permissions

There are no IAM permissions for this service.
