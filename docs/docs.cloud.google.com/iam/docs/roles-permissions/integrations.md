---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/integrations
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/integrations
title: Cloud Integrations roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Integrations. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Integrations roles

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
<td>Integrations Admin
<p>( <code>roles/ integrations.admin</code> )</p>
<p>Admin role for integrations</p></td>
<td><p><code>integrations.*</code></p>
<ul>
<li><code>integrations. apigeeAuthConfigs. create</code></li>
<li><code>integrations. apigeeAuthConfigs. delete</code></li>
<li><code>integrations. apigeeAuthConfigs. get</code></li>
<li><code>integrations. apigeeAuthConfigs. list</code></li>
<li><code>integrations. apigeeAuthConfigs. update</code></li>
<li><code>integrations. apigeeCertificates. create</code></li>
<li><code>integrations. apigeeCertificates. delete</code></li>
<li><code>integrations. apigeeCertificates. get</code></li>
<li><code>integrations. apigeeCertificates. list</code></li>
<li><code>integrations. apigeeCertificates. update</code></li>
<li><code>integrations. apigeeExecutions. list</code></li>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
<li><code>integrations. apigeeSfdcChannels. create</code></li>
<li><code>integrations. apigeeSfdcChannels. delete</code></li>
<li><code>integrations. apigeeSfdcChannels. get</code></li>
<li><code>integrations. apigeeSfdcChannels. list</code></li>
<li><code>integrations. apigeeSfdcChannels. update</code></li>
<li><code>integrations. apigeeSfdcInstances. create</code></li>
<li><code>integrations. apigeeSfdcInstances. delete</code></li>
<li><code>integrations. apigeeSfdcInstances. get</code></li>
<li><code>integrations. apigeeSfdcInstances. list</code></li>
<li><code>integrations. apigeeSfdcInstances. update</code></li>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
<li><code>integrations. authConfigs. create</code></li>
<li><code>integrations. authConfigs. delete</code></li>
<li><code>integrations.authConfigs.get</code></li>
<li><code>integrations.authConfigs.list</code></li>
<li><code>integrations. authConfigs. update</code></li>
<li><code>integrations. certificates. create</code></li>
<li><code>integrations. certificates. delete</code></li>
<li><code>integrations.certificates.get</code></li>
<li><code>integrations.certificates.list</code></li>
<li><code>integrations. certificates. update</code></li>
<li><code>integrations.executions.cancel</code></li>
<li><code>integrations.executions.get</code></li>
<li><code>integrations.executions.list</code></li>
<li><code>integrations.executions.replay</code></li>
<li><code>integrations. integrationVersions. create</code></li>
<li><code>integrations. integrationVersions. delete</code></li>
<li><code>integrations. integrationVersions. deploy</code></li>
<li><code>integrations. integrationVersions. get</code></li>
<li><code>integrations. integrationVersions. invoke</code></li>
<li><code>integrations. integrationVersions. list</code></li>
<li><code>integrations. integrationVersions. update</code></li>
<li><code>integrations. integrations. create</code></li>
<li><code>integrations. integrations. delete</code></li>
<li><code>integrations. integrations. deploy</code></li>
<li><code>integrations. integrations. generateOpenApiSpec</code></li>
<li><code>integrations.integrations.get</code></li>
<li><code>integrations. integrations. invoke</code></li>
<li><code>integrations.integrations.list</code></li>
<li><code>integrations. integrations. update</code></li>
<li><code>integrations. securityAuthConfigs. create</code></li>
<li><code>integrations. securityAuthConfigs. delete</code></li>
<li><code>integrations. securityAuthConfigs. get</code></li>
<li><code>integrations. securityAuthConfigs. list</code></li>
<li><code>integrations. securityAuthConfigs. update</code></li>
<li><code>integrations. securityExecutions. cancel</code></li>
<li><code>integrations. securityExecutions. get</code></li>
<li><code>integrations. securityExecutions. list</code></li>
<li><code>integrations. securityIntegTempVers. create</code></li>
<li><code>integrations. securityIntegTempVers. get</code></li>
<li><code>integrations. securityIntegTempVers. list</code></li>
<li><code>integrations. securityIntegrationVers. create</code></li>
<li><code>integrations. securityIntegrationVers. delete</code></li>
<li><code>integrations. securityIntegrationVers. deploy</code></li>
<li><code>integrations. securityIntegrationVers. get</code></li>
<li><code>integrations. securityIntegrationVers. list</code></li>
<li><code>integrations. securityIntegrationVers. update</code></li>
<li><code>integrations. securityIntegrations. invoke</code></li>
<li><code>integrations. securityIntegrations. list</code></li>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
<li><code>integrations.templates.create</code></li>
<li><code>integrations.templates.delete</code></li>
<li><code>integrations.templates.get</code></li>
<li><code>integrations.templates.list</code></li>
<li><code>integrations.templates.share</code></li>
<li><code>integrations.templates.unshare</code></li>
<li><code>integrations.templates.update</code></li>
<li><code>integrations.templates.use</code></li>
<li><code>integrations.testCases.create</code></li>
<li><code>integrations.testCases.delete</code></li>
<li><code>integrations.testCases.get</code></li>
<li><code>integrations.testCases.invoke</code></li>
<li><code>integrations.testCases.list</code></li>
<li><code>integrations.testCases.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Integrations Viewer
<p>( <code>roles/ integrations.viewer</code> )</p>
<p>Viewer role for integrations</p></td>
<td><p><code>integrations. apigeeAuthConfigs. get</code></p>
<p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeCertificates. get</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. apigeeSfdcChannels. get</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcInstances. get</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations. apigeeSuspensions. list</code></p>
<p><code>integrations.authConfigs.get</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations.certificates.get</code></p>
<p><code>integrations.certificates.list</code></p>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrations. generateOpenApiSpec</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. securityAuthConfigs. get</code></p>
<p><code>integrations. securityAuthConfigs. list</code></p>
<p><code>integrations. securityExecutions. get</code></p>
<p><code>integrations. securityExecutions. list</code></p>
<p><code>integrations. securityIntegTempVers. get</code></p>
<p><code>integrations. securityIntegTempVers. list</code></p>
<p><code>integrations. securityIntegrationVers. get</code></p>
<p><code>integrations. securityIntegrationVers. list</code></p>
<p><code>integrations. securityIntegrations. list</code></p>
<p><code>integrations.sfdcChannels.get</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations.sfdcInstances.get</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>integrations.suspensions.list</code></p>
<p><code>integrations.templates.get</code></p>
<p><code>integrations.templates.list</code></p>
<p><code>integrations.templates.share</code></p>
<p><code>integrations.templates.unshare</code></p>
<p><code>integrations.templates.use</code></p>
<p><code>integrations.testCases.get</code></p>
<p><code>integrations.testCases.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Apigee Integration Admin
<p>( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p>A user that has full access to all Apigee integrations.</p></td>
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
<p><code>connectors.entityTypes.list</code></p>
<p><code>integrations. apigeeAuthConfigs.*</code></p>
<ul>
<li><code>integrations. apigeeAuthConfigs. create</code></li>
<li><code>integrations. apigeeAuthConfigs. delete</code></li>
<li><code>integrations. apigeeAuthConfigs. get</code></li>
<li><code>integrations. apigeeAuthConfigs. list</code></li>
<li><code>integrations. apigeeAuthConfigs. update</code></li>
</ul>
<p><code>integrations. apigeeCertificates.*</code></p>
<ul>
<li><code>integrations. apigeeCertificates. create</code></li>
<li><code>integrations. apigeeCertificates. delete</code></li>
<li><code>integrations. apigeeCertificates. get</code></li>
<li><code>integrations. apigeeCertificates. list</code></li>
<li><code>integrations. apigeeCertificates. update</code></li>
</ul>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
</ul>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations. apigeeSfdcChannels.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcChannels. create</code></li>
<li><code>integrations. apigeeSfdcChannels. delete</code></li>
<li><code>integrations. apigeeSfdcChannels. get</code></li>
<li><code>integrations. apigeeSfdcChannels. list</code></li>
<li><code>integrations. apigeeSfdcChannels. update</code></li>
</ul>
<p><code>integrations. apigeeSfdcInstances.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcInstances. create</code></li>
<li><code>integrations. apigeeSfdcInstances. delete</code></li>
<li><code>integrations. apigeeSfdcInstances. get</code></li>
<li><code>integrations. apigeeSfdcInstances. list</code></li>
<li><code>integrations. apigeeSfdcInstances. update</code></li>
</ul>
<p><code>integrations. apigeeSuspensions.*</code></p>
<ul>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
</ul>
<p><code>integrations.authConfigs.*</code></p>
<ul>
<li><code>integrations. authConfigs. create</code></li>
<li><code>integrations. authConfigs. delete</code></li>
<li><code>integrations.authConfigs.get</code></li>
<li><code>integrations.authConfigs.list</code></li>
<li><code>integrations. authConfigs. update</code></li>
</ul>
<p><code>integrations.certificates.*</code></p>
<ul>
<li><code>integrations. certificates. create</code></li>
<li><code>integrations. certificates. delete</code></li>
<li><code>integrations.certificates.get</code></li>
<li><code>integrations.certificates.list</code></li>
<li><code>integrations. certificates. update</code></li>
</ul>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. create</code></p>
<p><code>integrations. integrationVersions. delete</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrationVersions. update</code></p>
<p><code>integrations. integrations. create</code></p>
<p><code>integrations. integrations. delete</code></p>
<p><code>integrations. integrations. deploy</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. integrations. update</code></p>
<p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>integrations.suspensions.*</code></p>
<ul>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Apigee Integration Deployer
<p>( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p>A developer that can deploy/undeploy Apigee integrations to the integration runtime.</p></td>
<td><p><code>integrations. apigeeIntegrationVers. deploy</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrations. deploy</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Apigee Integration Editor
<p>( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p>A developer that can list, create and update Apigee integrations.</p></td>
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
<p><code>connectors.entityTypes.list</code></p>
<p><code>integrations. apigeeAuthConfigs. create</code></p>
<p><code>integrations. apigeeAuthConfigs. get</code></p>
<p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeAuthConfigs. update</code></p>
<p><code>integrations. apigeeCertificates. create</code></p>
<p><code>integrations. apigeeCertificates. get</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeCertificates. update</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
</ul>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations. apigeeSfdcChannels. create</code></p>
<p><code>integrations. apigeeSfdcChannels. get</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcChannels. update</code></p>
<p><code>integrations. apigeeSfdcInstances. create</code></p>
<p><code>integrations. apigeeSfdcInstances. get</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations. apigeeSfdcInstances. update</code></p>
<p><code>integrations. authConfigs. create</code></p>
<p><code>integrations.authConfigs.get</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations. authConfigs. update</code></p>
<p><code>integrations.certificates.get</code></p>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. create</code></p>
<p><code>integrations. integrationVersions. delete</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrationVersions. update</code></p>
<p><code>integrations. integrations. create</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. integrations. update</code></p>
<p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Apigee Integration Invoker
<p>( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p>A role that can invoke Apigee integrations.</p></td>
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
<p><code>connectors.entityTypes.list</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. invoke</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Apigee Integration Viewer
<p>( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p>A developer that can list and view Apigee integrations.</p></td>
<td><p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations.authConfigs.get</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations.certificates.get</code></p>
<p><code>integrations.certificates.list</code></p>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Apigee Integration Approver
<p>( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p>A role that can approve / reject Apigee integrations that contain a suspension/wait task.</p></td>
<td><p><code>integrations. apigeeSuspensions.*</code></p>
<ul>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
</ul>
<p><code>integrations.suspensions.*</code></p>
<ul>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Certificate Viewer
<p>( <code>roles/ integrations.certificateViewer</code> )</p>
<p>A developer that can list and view Certificates.</p></td>
<td><p><code>integrations.certificates.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Integration Admin
<p>( <code>roles/ integrations.integrationAdmin</code> )</p>
<p>A user that has full access (CRUD) to all integrations.</p></td>
<td><p><code>integrations. apigeeAuthConfigs.*</code></p>
<ul>
<li><code>integrations. apigeeAuthConfigs. create</code></li>
<li><code>integrations. apigeeAuthConfigs. delete</code></li>
<li><code>integrations. apigeeAuthConfigs. get</code></li>
<li><code>integrations. apigeeAuthConfigs. list</code></li>
<li><code>integrations. apigeeAuthConfigs. update</code></li>
</ul>
<p><code>integrations. apigeeCertificates.*</code></p>
<ul>
<li><code>integrations. apigeeCertificates. create</code></li>
<li><code>integrations. apigeeCertificates. delete</code></li>
<li><code>integrations. apigeeCertificates. get</code></li>
<li><code>integrations. apigeeCertificates. list</code></li>
<li><code>integrations. apigeeCertificates. update</code></li>
</ul>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
</ul>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations. apigeeSfdcChannels.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcChannels. create</code></li>
<li><code>integrations. apigeeSfdcChannels. delete</code></li>
<li><code>integrations. apigeeSfdcChannels. get</code></li>
<li><code>integrations. apigeeSfdcChannels. list</code></li>
<li><code>integrations. apigeeSfdcChannels. update</code></li>
</ul>
<p><code>integrations. apigeeSfdcInstances.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcInstances. create</code></li>
<li><code>integrations. apigeeSfdcInstances. delete</code></li>
<li><code>integrations. apigeeSfdcInstances. get</code></li>
<li><code>integrations. apigeeSfdcInstances. list</code></li>
<li><code>integrations. apigeeSfdcInstances. update</code></li>
</ul>
<p><code>integrations. apigeeSuspensions.*</code></p>
<ul>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
</ul>
<p><code>integrations.authConfigs.*</code></p>
<ul>
<li><code>integrations. authConfigs. create</code></li>
<li><code>integrations. authConfigs. delete</code></li>
<li><code>integrations.authConfigs.get</code></li>
<li><code>integrations.authConfigs.list</code></li>
<li><code>integrations. authConfigs. update</code></li>
</ul>
<p><code>integrations.certificates.*</code></p>
<ul>
<li><code>integrations. certificates. create</code></li>
<li><code>integrations. certificates. delete</code></li>
<li><code>integrations.certificates.get</code></li>
<li><code>integrations.certificates.list</code></li>
<li><code>integrations. certificates. update</code></li>
</ul>
<p><code>integrations.executions.*</code></p>
<ul>
<li><code>integrations.executions.cancel</code></li>
<li><code>integrations.executions.get</code></li>
<li><code>integrations.executions.list</code></li>
<li><code>integrations.executions.replay</code></li>
</ul>
<p><code>integrations. integrationVersions. create</code></p>
<p><code>integrations. integrationVersions. delete</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrationVersions. update</code></p>
<p><code>integrations.integrations.*</code></p>
<ul>
<li><code>integrations. integrations. create</code></li>
<li><code>integrations. integrations. delete</code></li>
<li><code>integrations. integrations. deploy</code></li>
<li><code>integrations. integrations. generateOpenApiSpec</code></li>
<li><code>integrations.integrations.get</code></li>
<li><code>integrations. integrations. invoke</code></li>
<li><code>integrations.integrations.list</code></li>
<li><code>integrations. integrations. update</code></li>
</ul>
<p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>integrations.suspensions.*</code></p>
<ul>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
</ul>
<p><code>integrations.templates.*</code></p>
<ul>
<li><code>integrations.templates.create</code></li>
<li><code>integrations.templates.delete</code></li>
<li><code>integrations.templates.get</code></li>
<li><code>integrations.templates.list</code></li>
<li><code>integrations.templates.share</code></li>
<li><code>integrations.templates.unshare</code></li>
<li><code>integrations.templates.update</code></li>
<li><code>integrations.templates.use</code></li>
</ul>
<p><code>integrations.testCases.*</code></p>
<ul>
<li><code>integrations.testCases.create</code></li>
<li><code>integrations.testCases.delete</code></li>
<li><code>integrations.testCases.get</code></li>
<li><code>integrations.testCases.invoke</code></li>
<li><code>integrations.testCases.list</code></li>
<li><code>integrations.testCases.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Integration Deployer
<p>( <code>roles/ integrations.integrationDeployer</code> )</p>
<p>A developer that can deploy/undeploy integrations to the integration runtime.</p></td>
<td><p><code>integrations. apigeeIntegrationVers. deploy</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrations. deploy</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Integration Editor
<p>( <code>roles/ integrations.integrationEditor</code> )</p>
<p>A developer that can list, create and update integrations.</p></td>
<td><p><code>integrations. apigeeAuthConfigs. create</code></p>
<p><code>integrations. apigeeAuthConfigs. get</code></p>
<p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeAuthConfigs. update</code></p>
<p><code>integrations. apigeeCertificates. create</code></p>
<p><code>integrations. apigeeCertificates. get</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeCertificates. update</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
</ul>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations. apigeeSfdcChannels. create</code></p>
<p><code>integrations. apigeeSfdcChannels. get</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcChannels. update</code></p>
<p><code>integrations. apigeeSfdcInstances. create</code></p>
<p><code>integrations. apigeeSfdcInstances. get</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations. apigeeSfdcInstances. update</code></p>
<p><code>integrations. authConfigs. create</code></p>
<p><code>integrations.authConfigs.get</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations. authConfigs. update</code></p>
<p><code>integrations.certificates.get</code></p>
<p><code>integrations.executions.*</code></p>
<ul>
<li><code>integrations.executions.cancel</code></li>
<li><code>integrations.executions.get</code></li>
<li><code>integrations.executions.list</code></li>
<li><code>integrations.executions.replay</code></li>
</ul>
<p><code>integrations. integrationVersions. create</code></p>
<p><code>integrations. integrationVersions. delete</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrationVersions. update</code></p>
<p><code>integrations. integrations. create</code></p>
<p><code>integrations. integrations. generateOpenApiSpec</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. integrations. update</code></p>
<p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>integrations.templates.*</code></p>
<ul>
<li><code>integrations.templates.create</code></li>
<li><code>integrations.templates.delete</code></li>
<li><code>integrations.templates.get</code></li>
<li><code>integrations.templates.list</code></li>
<li><code>integrations.templates.share</code></li>
<li><code>integrations.templates.unshare</code></li>
<li><code>integrations.templates.update</code></li>
<li><code>integrations.templates.use</code></li>
</ul>
<p><code>integrations.testCases.*</code></p>
<ul>
<li><code>integrations.testCases.create</code></li>
<li><code>integrations.testCases.delete</code></li>
<li><code>integrations.testCases.get</code></li>
<li><code>integrations.testCases.invoke</code></li>
<li><code>integrations.testCases.list</code></li>
<li><code>integrations.testCases.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Integration Invoker
<p>( <code>roles/ integrations.integrationInvoker</code> )</p>
<p>A role that can invoke integrations.</p></td>
<td><p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations.executions.*</code></p>
<ul>
<li><code>integrations.executions.cancel</code></li>
<li><code>integrations.executions.get</code></li>
<li><code>integrations.executions.list</code></li>
<li><code>integrations.executions.replay</code></li>
</ul>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. invoke</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations.testCases.get</code></p>
<p><code>integrations.testCases.invoke</code></p>
<p><code>integrations.testCases.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Integration Viewer
<p>( <code>roles/ integrations.integrationViewer</code> )</p>
<p>A developer that can list and view integrations.</p></td>
<td><p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeIntegrationVers. get</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations.authConfigs.get</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations.certificates.get</code></p>
<p><code>integrations.certificates.list</code></p>
<p><code>integrations.executions.get</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrations. generateOpenApiSpec</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>integrations.templates.get</code></p>
<p><code>integrations.templates.list</code></p>
<p><code>integrations.testCases.get</code></p>
<p><code>integrations.testCases.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Security Integration Admin <sup>Beta</sup>
<p>( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p>A user that has full access to all Security integrations.</p></td>
<td><p><code>integrations. securityAuthConfigs.*</code></p>
<ul>
<li><code>integrations. securityAuthConfigs. create</code></li>
<li><code>integrations. securityAuthConfigs. delete</code></li>
<li><code>integrations. securityAuthConfigs. get</code></li>
<li><code>integrations. securityAuthConfigs. list</code></li>
<li><code>integrations. securityAuthConfigs. update</code></li>
</ul>
<p><code>integrations. securityExecutions.*</code></p>
<ul>
<li><code>integrations. securityExecutions. cancel</code></li>
<li><code>integrations. securityExecutions. get</code></li>
<li><code>integrations. securityExecutions. list</code></li>
</ul>
<p><code>integrations. securityIntegTempVers.*</code></p>
<ul>
<li><code>integrations. securityIntegTempVers. create</code></li>
<li><code>integrations. securityIntegTempVers. get</code></li>
<li><code>integrations. securityIntegTempVers. list</code></li>
</ul>
<p><code>integrations. securityIntegrationVers.*</code></p>
<ul>
<li><code>integrations. securityIntegrationVers. create</code></li>
<li><code>integrations. securityIntegrationVers. delete</code></li>
<li><code>integrations. securityIntegrationVers. deploy</code></li>
<li><code>integrations. securityIntegrationVers. get</code></li>
<li><code>integrations. securityIntegrationVers. list</code></li>
<li><code>integrations. securityIntegrationVers. update</code></li>
</ul>
<p><code>integrations. securityIntegrations.*</code></p>
<ul>
<li><code>integrations. securityIntegrations. invoke</code></li>
<li><code>integrations. securityIntegrations. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Application Integration SFDC Instance Admin
<p>( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p>A user that has full access (CRUD) to all SFDC instances.</p></td>
<td><p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Integration SFDC Instance Editor
<p>( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p>A developer that can list, create and update integrations.</p></td>
<td><p><code>integrations. sfdcChannels. create</code></p>
<p><code>integrations.sfdcChannels.get</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations. sfdcChannels. update</code></p>
<p><code>integrations. sfdcInstances. create</code></p>
<p><code>integrations.sfdcInstances.get</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>integrations. sfdcInstances. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Integration SFDC Instance Viewer
<p>( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p>A developer that can list and view SFDC instances.</p></td>
<td><p><code>integrations.sfdcChannels.get</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations.sfdcInstances.get</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Integration Approver
<p>( <code>roles/ integrations.suspensionResolver</code> )</p>
<p>A role that can resolve suspended integrations.</p></td>
<td><p><code>integrations. apigeeSuspensions.*</code></p>
<ul>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
</ul>
<p><code>integrations.suspensions.*</code></p>
<ul>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Application Integration Service Agent
<p>( <code>roles/ integrations.serviceAgent</code> )</p>
<p>Service agent that grants access to execute an integration.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudfunctions. functions. invoke</code></p>
<p><code>cloudscheduler.jobs.create</code></p>
<p><code>cloudscheduler.jobs.delete</code></p>
<p><code>cloudscheduler.jobs.enable</code></p>
<p><code>cloudscheduler.jobs.fullView</code></p>
<p><code>cloudscheduler.jobs.get</code></p>
<p><code>cloudscheduler.jobs.pause</code></p>
<p><code>cloudscheduler.jobs.run</code></p>
<p><code>cloudscheduler.jobs.update</code></p>
<p><code>cloudscheduler.locations.*</code></p>
<ul>
<li><code>cloudscheduler.locations.get</code></li>
<li><code>cloudscheduler.locations.list</code></li>
</ul>
<p><code>connectors.actions.*</code></p>
<ul>
<li><code>connectors.actions.execute</code></li>
<li><code>connectors.actions.list</code></li>
</ul>
<p><code>connectors. connections. executeSqlQuery</code></p>
<p><code>connectors.connections.get</code></p>
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
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>integrations. apigeeAuthConfigs.*</code></p>
<ul>
<li><code>integrations. apigeeAuthConfigs. create</code></li>
<li><code>integrations. apigeeAuthConfigs. delete</code></li>
<li><code>integrations. apigeeAuthConfigs. get</code></li>
<li><code>integrations. apigeeAuthConfigs. list</code></li>
<li><code>integrations. apigeeAuthConfigs. update</code></li>
</ul>
<p><code>integrations. apigeeCertificates.*</code></p>
<ul>
<li><code>integrations. apigeeCertificates. create</code></li>
<li><code>integrations. apigeeCertificates. delete</code></li>
<li><code>integrations. apigeeCertificates. get</code></li>
<li><code>integrations. apigeeCertificates. list</code></li>
<li><code>integrations. apigeeCertificates. update</code></li>
</ul>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrationVers. create</code></li>
<li><code>integrations. apigeeIntegrationVers. delete</code></li>
<li><code>integrations. apigeeIntegrationVers. deploy</code></li>
<li><code>integrations. apigeeIntegrationVers. get</code></li>
<li><code>integrations. apigeeIntegrationVers. list</code></li>
<li><code>integrations. apigeeIntegrationVers. update</code></li>
</ul>
<p><code>integrations. apigeeIntegrations.*</code></p>
<ul>
<li><code>integrations. apigeeIntegrations. invoke</code></li>
<li><code>integrations. apigeeIntegrations. list</code></li>
</ul>
<p><code>integrations. apigeeSfdcChannels.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcChannels. create</code></li>
<li><code>integrations. apigeeSfdcChannels. delete</code></li>
<li><code>integrations. apigeeSfdcChannels. get</code></li>
<li><code>integrations. apigeeSfdcChannels. list</code></li>
<li><code>integrations. apigeeSfdcChannels. update</code></li>
</ul>
<p><code>integrations. apigeeSfdcInstances.*</code></p>
<ul>
<li><code>integrations. apigeeSfdcInstances. create</code></li>
<li><code>integrations. apigeeSfdcInstances. delete</code></li>
<li><code>integrations. apigeeSfdcInstances. get</code></li>
<li><code>integrations. apigeeSfdcInstances. list</code></li>
<li><code>integrations. apigeeSfdcInstances. update</code></li>
</ul>
<p><code>integrations. apigeeSuspensions.*</code></p>
<ul>
<li><code>integrations. apigeeSuspensions. lift</code></li>
<li><code>integrations. apigeeSuspensions. list</code></li>
<li><code>integrations. apigeeSuspensions. resolve</code></li>
</ul>
<p><code>integrations.authConfigs.*</code></p>
<ul>
<li><code>integrations. authConfigs. create</code></li>
<li><code>integrations. authConfigs. delete</code></li>
<li><code>integrations.authConfigs.get</code></li>
<li><code>integrations.authConfigs.list</code></li>
<li><code>integrations. authConfigs. update</code></li>
</ul>
<p><code>integrations.certificates.*</code></p>
<ul>
<li><code>integrations. certificates. create</code></li>
<li><code>integrations. certificates. delete</code></li>
<li><code>integrations.certificates.get</code></li>
<li><code>integrations.certificates.list</code></li>
<li><code>integrations. certificates. update</code></li>
</ul>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. create</code></p>
<p><code>integrations. integrationVersions. delete</code></p>
<p><code>integrations. integrationVersions. deploy</code></p>
<p><code>integrations. integrationVersions. get</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations. integrationVersions. update</code></p>
<p><code>integrations. integrations. create</code></p>
<p><code>integrations. integrations. delete</code></p>
<p><code>integrations. integrations. deploy</code></p>
<p><code>integrations.integrations.get</code></p>
<p><code>integrations. integrations. invoke</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. integrations. update</code></p>
<p><code>integrations.sfdcChannels.*</code></p>
<ul>
<li><code>integrations. sfdcChannels. create</code></li>
<li><code>integrations. sfdcChannels. delete</code></li>
<li><code>integrations.sfdcChannels.get</code></li>
<li><code>integrations.sfdcChannels.list</code></li>
<li><code>integrations. sfdcChannels. update</code></li>
</ul>
<p><code>integrations.sfdcInstances.*</code></p>
<ul>
<li><code>integrations. sfdcInstances. create</code></li>
<li><code>integrations. sfdcInstances. delete</code></li>
<li><code>integrations.sfdcInstances.get</code></li>
<li><code>integrations. sfdcInstances. list</code></li>
<li><code>integrations. sfdcInstances. update</code></li>
</ul>
<p><code>integrations.suspensions.*</code></p>
<ul>
<li><code>integrations.suspensions.lift</code></li>
<li><code>integrations.suspensions.list</code></li>
<li><code>integrations. suspensions. resolve</code></li>
</ul>
<p><code>pubsub. messageTransforms. validate</code></p>
<p><code>pubsub.schemas.attach</code></p>
<p><code>pubsub.schemas.create</code></p>
<p><code>pubsub.schemas.delete</code></p>
<p><code>pubsub.schemas.get</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.validate</code></p>
<p><code>pubsub.snapshots.create</code></p>
<p><code>pubsub.snapshots.delete</code></p>
<p><code>pubsub.snapshots.get</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub.snapshots.seek</code></p>
<p><code>pubsub.snapshots.update</code></p>
<p><code>pubsub.subscriptions.consume</code></p>
<p><code>pubsub.subscriptions.create</code></p>
<p><code>pubsub.subscriptions.delete</code></p>
<p><code>pubsub.subscriptions.get</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub.subscriptions.update</code></p>
<p><code>pubsub. topics. attachSubscription</code></p>
<p><code>pubsub.topics.create</code></p>
<p><code>pubsub.topics.delete</code></p>
<p><code>pubsub. topics. detachSubscription</code></p>
<p><code>pubsub.topics.get</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>pubsub.topics.update</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>run.jobs.run</code></p>
<p><code>run.routes.invoke</code></p>
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
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Cloud Integrations permissions

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
<td><code>integrations. apigeeAuthConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeAuthConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeAuthConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeAuthConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeAuthConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeCertificates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeCertificates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeCertificates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeCertificates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeCertificates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeExecutions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeIntegrationVers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeIntegrationVers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeIntegrationVers. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeIntegrationVers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeIntegrationVers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeIntegrationVers. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeIntegrations. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeIntegrations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSfdcChannels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSfdcChannels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSfdcChannels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSfdcChannels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSfdcChannels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSfdcInstances. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSfdcInstances. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSfdcInstances. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSfdcInstances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSfdcInstances. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSuspensions. lift</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. apigeeSuspensions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. apigeeSuspensions. resolve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. authConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. authConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.authConfigs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.authConfigs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. authConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. certificates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. certificates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.certificates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.certificateViewer">Certificate Viewer</a> ( <code>roles/ integrations.certificateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.certificates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. certificates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.executions.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.executions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.executions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.executions.replay</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. integrationVersions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. integrationVersions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrationVersions. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. integrationVersions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrationVersions. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. integrationVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrationVersions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. integrations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. integrations. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrations. generateOpenApiSpec</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
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
<td><code>integrations.integrations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrations. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.integrations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. integrations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. securityAuthConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityAuthConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityAuthConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityAuthConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityAuthConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityExecutions. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.integrationExecutorServiceAgent">Security Center Integration Executor Service Agent</a> ( <code>roles/ securitycenter.integrationExecutorServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. securityExecutions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityExecutions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.integrationExecutorServiceAgent">Security Center Integration Executor Service Agent</a> ( <code>roles/ securitycenter.integrationExecutorServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegTempVers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityIntegTempVers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegTempVers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityIntegrationVers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegrationVers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityIntegrationVers. deploy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegrationVers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityIntegrationVers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegrationVers. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. securityIntegrations. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.integrationExecutorServiceAgent">Security Center Integration Executor Service Agent</a> ( <code>roles/ securitycenter.integrationExecutorServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. securityIntegrations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.securityIntegrationAdmin">Security Integration Admin</a> ( <code>roles/ integrations.securityIntegrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations. sfdcChannels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. sfdcChannels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.sfdcChannels.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.sfdcChannels.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. sfdcChannels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. sfdcInstances. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. sfdcInstances. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.sfdcInstances.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. sfdcInstances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations. sfdcInstances. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.suspensions.lift</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.suspensions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations. suspensions. resolve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.templates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.templates.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.templates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.templates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.templates.share</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.templates.unshare</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.templates.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.templates.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.testCases.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>integrations.testCases.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>integrations.testCases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.testCases.invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>integrations.testCases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>integrations.testCases.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
