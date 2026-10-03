---
name: documents/docs.cloud.google.com/iam/docs/service-agents
uri: https://docs.cloud.google.com/iam/docs/service-agents
title: Service agents
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Some Google Cloud services have [*service agents*](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) that allow the service to access your resources. If an API requires a service agent, then Google Cloud creates the service agent at some point after you activate and use the API. You might see evidence of these service agents in several different places, including a project's [allow policy](https://docs.cloud.google.com/iam/docs/allow-policies) and [audit log entries](https://docs.cloud.google.com/iam/docs/audit-logging) for various services. For more information about when Google Cloud creates service agents, see [Service agent creation](https://docs.cloud.google.com/iam/docs/service-account-types#creation) .

If you manage your allow policies with a declarative framework or a policies-as-code system, you might want to create and grant roles to a service agent before you use the service it belongs to. In these cases, after you [identify the service agent](https://docs.cloud.google.com/iam/docs/create-service-agents#identify-agents) you need to create, you can [trigger service agent creation](https://docs.cloud.google.com/iam/docs/create-service-agents#create) yourself without using the service.

This page provides details about the service agents for all services that are publicly available, including the following:

- The domain name used in the service agent's email address.

- The role that the service agent is granted on the project.

  When the service agent is created, Google Cloud grants this role automatically.

> **Warning:** Do not grant service agent roles to any principals except service agents. Some service agent roles contain very powerful permissions, and the permissions within these roles can change without notice. Instead, choose a different [predefined role](https://docs.cloud.google.com/iam/docs/roles-permissions) , or create a [custom role](https://docs.cloud.google.com/iam/docs/understanding-custom-roles) with the permissions you need.

Google Cloud can introduce new service agents at any time, both for existing services and for new services. Both the creation time and the email address format for service agents are subject to change.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Service agent</th>
<th>Role</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>AI Platform Custom Code Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-cc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a><br />
( <code>roles/aiplatform.customCodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>AI Platform Example Store Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-es.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AI Platform Fine Tuning Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-ft.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code>roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>AI Platform Infra Spanner Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-is.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AI Platform Private Instance (PIE) Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-pie.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code>roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>AI Platform Rapid Eval Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-eval.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.rapidevalServiceAgent">Vertex AI Rapid Eval Service Agent</a><br />
( <code>roles/aiplatform.rapidevalServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>AI Platform Reasoning Engine Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-re.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a><br />
( <code>roles/aiplatform.reasoningEngineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>AI Platform Resource Identity Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-ri-aiplatform.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AI Platform Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code>roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>API Hub Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>apihub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apihub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a><br />
( <code>roles/apihub.runtimeProjectServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>API Keys Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>apikeys.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apikeys.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>APIM Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>apim.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apim.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.apiDiscoveryServiceAgent">APIM API Discovery Service Agent</a><br />
( <code>roles/apim.apiDiscoveryServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>ASM Mesh Control Plane Service Account Service agent for <code>meshconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-meshcontrolplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a><br />
( <code>roles/meshcontrolplane.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>ASM Mesh Data Plane Service Account Service agent for <code>meshconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-meshdataplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a><br />
( <code>roles/meshdataplane.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Access Approval Service Agent Service agent for <code>accessapproval.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>service-p </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code>service-f </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-o </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Ads Data Hub Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>adsdatahub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-adsdatahub.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Agent Gateway Service Account Service agent for <code>networkservices.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-agentgateway.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentgateway#agentgateway.serviceAgent">Agent Gateway Service Agent</a><br />
( <code>roles/agentgateway.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Agent Registry Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>agentregistry.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-agentregistry.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AlloyDB Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>alloydb.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-alloydb.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.serviceAgent">AlloyDB Service Agent</a><br />
( <code>roles/alloydb.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>AlloyDB Service Agent Service agent for <code>alloydb.googleapis.com</code> .
<p><code>c- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-alloydb.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Analytics Hub Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>analyticshub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-analyticshub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.serviceAgent">Analytics Hub Service Agent</a><br />
( <code>roles/analyticshub.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Audit Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>anthosaudit.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthosaudit.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a><br />
( <code>roles/anthosaudit.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Anthos Config Management Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>anthosconfigmanagement.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthosconfigmanagement.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a><br />
( <code>roles/anthosconfigmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Identity Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>anthosidentityservice.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthosidentityservice.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a><br />
( <code>roles/anthosidentityservice.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Anthos Multi-Cloud Container Service Agent Service agent for <code>gkemulticloud.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkemulticloudcontainer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a><br />
( <code>roles/gkemulticloud.containerServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Multi-Cloud Control Plane Machine Service Agent Service agent for <code>gkemulticloud.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkemulticloudcpmachine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a><br />
( <code>roles/gkemulticloud.controlPlaneMachineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Anthos Multi-Cloud Node Pool Machine Service Agent Service agent for <code>gkemulticloud.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkemulticloudnpmachine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a><br />
( <code>roles/gkemulticloud.nodePoolMachineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Multi-Cloud Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gkemulticloud.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkemulticloud.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a><br />
( <code>roles/gkemulticloud.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Anthos Policy Controller Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>anthospolicycontroller.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthospolicycontroller.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a><br />
( <code>roles/anthospolicycontroller.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>anthos.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthos.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a><br />
( <code>roles/anthos.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Anthos Service Mesh Service Account Service agent for <code>meshconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-servicemesh.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a><br />
( <code>roles/anthosservicemesh.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Anthos Support Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>connectgateway.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-anthossupport.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a><br />
( <code>roles/anthossupport.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Apigee Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>apigee.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apigee.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a><br />
( <code>roles/apigee.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Apigee Service Agent Service agent for <code>apigee.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apigee.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a><br />
( <code>roles/apigee.coreServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>App Development Experience Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>appdevelopmentexperience.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-appdevexperience.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a><br />
( <code>roles/appdevelopmentexperience.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>App Engine Flexible Environment Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>appengineflex.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gae-api-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a><br />
( <code>roles/appengineflex.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>App Engine Standard Environment Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>appenginestandard.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-gae-service.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a><br />
( <code>roles/appengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>App Hub Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>apphub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apphub.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>App Optimize Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>appoptimize.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-appoptimize.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Application Integration Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>integrations.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-integrations.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a><br />
( <code>roles/integrations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Artifact Registry Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>artifactregistry.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-artifactregistry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a><br />
( <code>roles/artifactregistry.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Assured OSS Service Agent Service agent for <code>assuredoss.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-assuredoss.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Assured Workloads Monitoring Service Agent Service agent for <code>assuredworkloads.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dbmonitoring.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.monitoringServiceAgent">Assured Workloads Monitoring Service Agent</a><br />
( <code>roles/assuredworkloads.monitoringServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Assured Workloads Monitoring Service Agent Service agent for <code>assuredworkloads.googleapis.com</code> .
<p><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-dbmonitoring.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Assured Workloads Service Agent Service agent for <code>assuredworkloads.googleapis.com</code> .
<p><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-assuredworkloads.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>AssuredWorkloads Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>assuredworkloads.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-assuredworkloads.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a><br />
( <code>roles/assuredworkloads.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Attack Surface Management Service Agent Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-asm-hpsa.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Audit Manager Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>auditmanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-audit-manager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a><br />
( <code>roles/auditmanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Audit Manager Service Agent Service agent for <code>auditmanager.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-audit-manager.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-audit-manager.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Auto Annotate Service Account Service agent for <code>storage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-autoannotate.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>AutoML Recommendations Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>recommendationengine.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-recommendationengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a><br />
( <code>roles/automlrecommendations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Backup and DR Runner Service Agent Service agent for <code>backupdr.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-backupdr-run.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Backup and DR Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>backupdr.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-backupdr.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a><br />
( <code>roles/backupdr.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Backup and DR Vault Service Agent Service agent for <code>backupdr.googleapis.com</code> .
<p><code>vault- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-backupdr-pr.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Backup for GKE Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gkebackup.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkebackup.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a><br />
( <code>roles/gkebackup.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Bare Metal Solution Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>baremetalsolution.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bms.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.serviceAgent">Bare Metal Solution Service Agent</a><br />
( <code>roles/baremetalsolution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Batch Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>batch.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudbatch.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a><br />
( <code>roles/batch.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Big Query Service Agent Service agent for <code>bigquery.googleapis.com</code> .
<p><code>bq- </code><var translate="no"> PROJECT_NUMBER </var><code> @bigquery-encryption.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigLake Iceberg Rest Catalog API Service Agent Service agent for <code>biglake.googleapis.com</code> .
<p><code>blirc- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-biglakerestcatalog.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>BigLake Identity Federation Service Agent Service agent for <code>biglake.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-biglakeidentityfed.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery Connected Sheets Service Agent Service agent for <code>bigquery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-connectedsheets.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.connectedSheetsServiceAgent">Connected Sheets Service Agent</a><br />
( <code>roles/bigquery.connectedSheetsServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>BigQuery Connection Delegation Service Agent Service agent for <code>bigqueryconnection.googleapis.com</code> .
<ul>
<li><code>bqcx- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-bigquery-condel.iam.gserviceaccount.com</code></li>
<li><code>connection- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-bigquery-condel.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery Connection Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>bigqueryconnection.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigqueryconnection.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a><br />
( <code>roles/bigqueryconnection.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>BigQuery Continuous Query Service Agent Service agent for <code>bigquery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigquerytardis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery#bigquerycontinuousquery.serviceAgent">BigQuery Continuous Query Service Agent</a><br />
( <code>roles/bigquerycontinuousquery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>BigQuery Data Transfer Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>bigquerydatatransfer.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigquerydatatransfer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a><br />
( <code>roles/bigquerydatatransfer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>BigQuery Migration Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>bigquerymigration.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bqms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery Omni Service Agent Service agent for <code>bigquery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-prod-bigqueryomni.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryomni#bigqueryomni.serviceAgent">BigQuery Omni Service Agent</a><br />
( <code>roles/bigqueryomni.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>BigQuery Resource Identity Service Account Service agent for <code>bigquery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigqueryri.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>BigQuery Spark Connection Delegate Service Agent Service agent for <code>bigqueryconnection.googleapis.com</code> .
<p><code>bqcx- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-bigquery-consp.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>BigQuery Spark Service Agent Service agent for <code>bigquery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigqueryspark.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark#bigqueryspark.serviceAgent">BigQuery Spark Service Agent</a><br />
( <code>roles/bigqueryspark.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>binaryauthorization.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-binaryauthorization.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a><br />
( <code>roles/binaryauthorization.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Blockchain Node Engine Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>blockchainnodeengine.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bne.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.serviceAgent">Blockchain Node Engine Service Agent</a><br />
( <code>roles/blockchainnodeengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Bundles Service Agent Service agent for <code>integrations.googleapis.com</code> .
<p><code>b </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-bundles.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Business AI Code Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>businessaicode.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-businessaicode.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.serviceAgent">Business AI Code Service Agent</a><br />
( <code>roles/businessaicode.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Chronicle Organization Service Account Service agent for <code>chronicle.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-chronicle-org.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Chronicle Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>chronicle.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-chronicle.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a><br />
( <code>roles/chronicle.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Chronicle Soar Service Agent Service agent for <code>chronicle.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-chronicle-soar.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud AI Platform Notebooks Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>notebooks.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-notebooks.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a><br />
( <code>roles/notebooks.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud AI Platform Notebooks VM Service Account Service agent for <code>notebooks.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-notebooks-vm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a><br />
( <code>roles/aiplatform.notebookServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud API Gateway Management Plane Service Account Service agent for <code>apigateway.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apigateway-mgmt.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a><br />
( <code>roles/apigateway_management.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud API Gateway Service Account Service agent for <code>apigateway.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-apigateway.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a><br />
( <code>roles/apigateway.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Asset Effective Policy Service Agent Service agent for <code>cloudasset.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-effectivepolicy.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Asset Other Cloud Config Service Agent Service agent for <code>cloudasset.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-othercloudcfg.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Asset Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudasset.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudasset.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a><br />
( <code>roles/cloudasset.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Bigtable Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>bigtableadmin.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-bigtable.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Build Service Agent Service agent for <code>cloudbuild.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudbuild.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a><br />
( <code>roles/cloudbuild.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Certificate Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>certificatemanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-certificatemanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.serviceAgent">Certificate Manager Service Agent</a><br />
( <code>roles/certificatemanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Composer Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>composer.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloudcomposer-accounts.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a><br />
( <code>roles/composer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Controls Partner Service Agent Service agent for <code>cloudcontrolspartner.googleapis.com</code> .
<p><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-cloudcontrolspartner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud DNS Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dns.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dns.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.serviceAgent">Cloud DNS Service Agent</a><br />
( <code>roles/dns.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Data Fusion Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datafusion.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datafusion.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a><br />
( <code>roles/datafusion.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Data Loss Prevention Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dlp.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @dlp-api.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a><br />
( <code>roles/dlp.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Database Migration Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datamigration.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datamigration.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a><br />
( <code>roles/datamigration.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Dataflow Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataflow.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @dataflow-service-producer-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a><br />
( <code>roles/dataflow.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Dataplex Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataplex.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dataplex.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a><br />
( <code>roles/dataplex.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Datastream Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datastream.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datastream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a><br />
( <code>roles/datastream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Deploy Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>clouddeploy.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-clouddeploy.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a><br />
( <code>roles/clouddeploy.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Endpoints Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>endpoints.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-endpoints.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a><br />
( <code>roles/endpoints.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud File Storage Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>file.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloud-filer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a><br />
( <code>roles/file.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Firestore Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firestore.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firestore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a><br />
( <code>roles/firestore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Healthcare Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>healthcare.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-healthcare.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a><br />
( <code>roles/healthcare.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Identity Platform Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>identitytoolkit.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-identitytoolkit.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a><br />
( <code>roles/identitytoolkit.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud KMS Organization Service Agent Service agent for <code>cloudkms.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-cloudkms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud KMS Service Agent Service agent for <code>cloudkms.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudkms.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a><br />
( <code>roles/cloudkms.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Logging Service Account Service agent for <code>logging.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.serviceAgent">Cloud Logging Service Agent</a><br />
( <code>roles/logging.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Logging Service Agent Service agent for <code>logging.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Managed Identities Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>managedidentities.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-mi.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a><br />
( <code>roles/managedidentities.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Memorystore Memcache Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>memcache.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloud-memcache-sa.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a><br />
( <code>roles/memcache.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Memorystore Redis Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>redis.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloud-redis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a><br />
( <code>roles/redis.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Migration Center Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>migrationcenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-migcenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.serviceAgent">Migration Center Service Agent</a><br />
( <code>roles/migrationcenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Network Management Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>networkmanagement.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-networkmanagement.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.serviceAgent">GCP Network Management Service Agent</a><br />
( <code>roles/networkmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Notebook Security Scanner Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>notebooksecurityscanner.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-notebooksecurityscanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Notebook Security Scanner Service Agent Service agent for <code>notebooksecurityscanner.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-nss-hpsa.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-nss-hpsa.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Observability Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>observability.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-observability.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.serviceAgent">Observability Service Agent</a><br />
( <code>roles/observability.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Observability Service Account Service agent for <code>observability.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-observability.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-observability.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Optimization Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>routeoptimization.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-routeoptim.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a><br />
( <code>roles/routeoptimization.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Pub/Sub Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>pubsub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-pubsub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a><br />
( <code>roles/pubsub.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Resource Manager Service Agent Service agent for <code>cloudresourcemanager.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-cloudresourcemanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Cloud Risk Manager Service Agent Service agent for <code>dlp.googleapis.com</code> .
<p><code>organizations- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-riskmanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud SQL Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>sqladmin.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.serviceAgent">Cloud SQL Service Agent</a><br />
( <code>roles/cloudsql.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud SQL Service Agent Service agent for <code>sqladmin.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>p </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code>f </code><var translate="no"> FOLDER_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>o </code><var translate="no"> ORGANIZATION_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Scheduler Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudscheduler.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudscheduler.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a><br />
( <code>roles/cloudscheduler.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Security Command Center Bulk Export Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-scc-bulk-export.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Security Command Center Notification Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-scc-notification.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationServiceAgent">Security Center Notification Service Agent</a><br />
( <code>roles/securitycenter.notificationServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Security Command Center Notification Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-scc-notification.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Security Command Center Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-securitycenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a><br />
( <code>roles/securitycenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Security Command Center Service Agent Service agent for <code>securitycenter.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @security-center-api.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @security-center-api.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Security Compliance Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudsecuritycompliance.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-csc-hpsa.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a><br />
( <code>roles/cloudsecuritycompliance.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Security Compliance Service Agent Service agent for <code>cloudsecuritycompliance.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-csc-hpsa.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Spanner Production Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>spanner.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-spanner.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a><br />
( <code>roles/spanner.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Storage for Firebase Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebasestorage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebasestorage.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a><br />
( <code>roles/firebasestorage.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Tasks Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudtasks.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudtasks.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a><br />
( <code>roles/cloudtasks.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Trace Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudtrace.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloud-trace.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Cloud Translation Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>translate.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-translation.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a><br />
( <code>roles/cloudtranslate.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud VM Migration Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>vmmigration.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vmmigration.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.serviceAgent">VM Migration Service Agent</a><br />
( <code>roles/vmmigration.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Web Security Scanner Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>websecurityscanner.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-websecurityscanner.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#websecurityscanner.serviceAgent">Cloud Web Security Scanner Service Agent</a><br />
( <code>roles/websecurityscanner.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cloud Workflows Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>workflows.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-workflows.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a><br />
( <code>roles/workflows.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Cloud Workstations Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>workstations.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-workstations.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a><br />
( <code>roles/workstations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Cluster Director Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>hypercomputecluster.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-hypercomputecluster.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a><br />
( <code>roles/hypercomputecluster.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Compute Engine Service Agent Service agent for <code>compute.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @compute-system.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a><br />
( <code>roles/compute.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Compute Usage Export Service Agent Service agent for <code>compute.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-compute-usage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Config Delivery Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>configdelivery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-configdelivery.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a><br />
( <code>roles/configdelivery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Connectors Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>connectors.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-connectors.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a><br />
( <code>roles/connectors.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Contact Center AI Insights Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>contactcenterinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-contactcenterinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a><br />
( <code>roles/contactcenterinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Contact Center AI Insights Service Account for CMEK (prod) Service agent for <code>contactcenterinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ccinsights-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Contact Center AI Platform Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>contactcenteraiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ccaip.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Contact Center AI shared Service Account for CMEK (prod) Service agent for <code>contactcenterinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ccai-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Contact Center Insights Resource Identity (prod) Service agent for <code>contactcenterinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-ri-contactcenterinsights.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Container Analysis Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>containeranalysis.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @container-analysis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a><br />
( <code>roles/containeranalysis.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Container Scanning Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>containerscanning.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-containerscanning.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a><br />
( <code>roles/containerscanning.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Container Security Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>containersecurity.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-containersec.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Container Threat Detection Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>containerthreatdetection.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ktd-control.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a><br />
( <code>roles/containerthreatdetection.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Container Threat Detection Service Agent Service agent for <code>containerthreatdetection.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ktd-hpsa.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-ktd-hpsa.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Content Warehouse Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>contentwarehouse.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloud-cw.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a><br />
( <code>roles/contentwarehouse.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Customer Engagement Suite Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>ces.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ces.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a><br />
( <code>roles/ces.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Data Connectors Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataconnectors.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dataconnectors.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.serviceAgent">Data Connectors Service Agent</a><br />
( <code>roles/dataconnectors.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Data Lineage Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datalineage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datalineage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Data Pipelines Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datapipelines.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datapipelines.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a><br />
( <code>roles/datapipelines.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Data Studio CMEK Service Account Service agent for <code>datastudio.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datastudio-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Data Studio Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>datastudio.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-datastudio.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.serviceAgent">Data Studio Service Agent</a><br />
( <code>roles/datastudio.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Database Insights Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>databaseinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dbinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a><br />
( <code>roles/databaseinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Dataform Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dataform.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a><br />
( <code>roles/dataform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Dataplex Cmek Service Agent Service agent for <code>dataplex.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-dataplex-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Dataplex Service Agent Service agent for <code>dataplex.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-dataplex.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>metastore.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-metastore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a><br />
( <code>roles/metastore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Deprecated Monitoring Service Account Service agent for <code>monitoring.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-monitoring.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Design Center Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>designcenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-designcenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a><br />
( <code>roles/designcenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Developer Connect Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>developerconnect.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-devconnect.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a><br />
( <code>roles/developerconnect.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Device Run Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>devicerun.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-devicerun.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.serviceAgent">Device Run Service Agent</a><br />
( <code>roles/devicerun.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Dialogflow Service Account for CMEK (prod) Service agent for <code>dialogflow.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dialogflow-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Dialogflow Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dialogflow.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dialogflow.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a><br />
( <code>roles/dialogflow.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Discovery Engine Customer Service Agent Service agent for <code>discoveryengine.googleapis.com</code> .
<p><code>service-workspace-C </code><var translate="no"> GOOGLE_WORKSPACE_CUSTOMER_ID </var><code> @gcp-sa-discoveryengine.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Discovery Engine Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>discoveryengine.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-discoveryengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a><br />
( <code>roles/discoveryengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Document AI Warehouse CMEK Infra Spanner Service Account Service agent for <code>contentwarehouse.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloud-cw-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>DocumentAI Core Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>documentai.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-prod-dai-core.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a><br />
( <code>roles/documentaicore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Edge Container Cluster Service Agent Service agent for <code>edgecontainer.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-edgecontainercluster.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a><br />
( <code>roles/edgecontainer.clusterServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Edge Container GCR Service Agent Service agent for <code>edgecontainer.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-edgecontainergcr.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Edge Container Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>edgecontainer.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-edgecontainer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a><br />
( <code>roles/edgecontainer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Enterprise Knowledge Graph Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>enterpriseknowledgegraph.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloud-ekg.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a><br />
( <code>roles/enterpriseknowledgegraph.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Eventarc Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>eventarc.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-eventarc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a><br />
( <code>roles/eventarc.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>External Key Management Service Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudkms.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ekms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>FTP Service Agent Service agent for <code>ftp.googleapis.com</code> .
<p><code>p- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-ftp.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Firebase AI Logic Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebasevertexai.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebasevertexai.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase AI Logic Service Agent</a><br />
( <code>roles/firebaseml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Firebase App Check Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebaseappcheck.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebaseappcheck.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappcheck#firebaseappcheck.serviceAgent">Firebase App Check Service Agent</a><br />
( <code>roles/firebaseappcheck.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Firebase App Hosting Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebaseapphosting.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebaseapphosting.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a><br />
( <code>roles/firebaseapphosting.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Firebase Crashlytics Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebasecrashlytics.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-crashlytics.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.serviceAgent">Firebase Crashlytics Service Agent</a><br />
( <code>roles/firebasecrashlytics.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Firebase Data Connect Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebasedataconnect.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebasedataconnect.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a><br />
( <code>roles/firebasedataconnect.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Firebase Extensions Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebaseextensions.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebasemods.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a><br />
( <code>roles/firebasemods.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Firebase Machine Learning Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebaseml.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebaseml.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase AI Logic Service Agent</a><br />
( <code>roles/firebaseml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Firebase Management Service Agent Service agent for <code>firebase.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebase.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a><br />
( <code>roles/firebase.managementServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Firebase Realtime Database Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebasedatabase.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firebasedatabase.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.serviceAgent">Firebase Realtime Database Service Agent</a><br />
( <code>roles/firebasedatabase.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Firebase Rules Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firebaserules.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @firebase-rules.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a><br />
( <code>roles/firebaserules.system</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Firewall Insights Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>firewallinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-firewallinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firewallinsights#firewallinsights.serviceAgent">Cloud Firewall Insights Service Agent</a><br />
( <code>roles/firewallinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>G Suite Add-ons Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gsuiteaddons.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gsuiteaddons.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>GCS Malware Scanning Service Account Service agent for <code>storage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gcs-malware.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>GCS Search Service Account Service agent for <code>storage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-storage-search.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>GKE Dataplane V2 Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gkedataplanev2.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkedataplanev2.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>GKE Hub API Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gkehub.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkehub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a><br />
( <code>roles/gkehub.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Gemini Code Assist Management Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>geminicodeassistmanagement.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-geminicodeassistmp.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a><br />
( <code>roles/geminicodeassistmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Gemini Data Analytics Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>geminidataanalytics.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-geminidataanalytics.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Gemini for Google Cloud Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudaicompanion.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-cloudaicompanion.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a><br />
( <code>roles/cloudaicompanion.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Generative Language Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>generativelanguage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-generativelanguage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Generative Language Service Agent Service agent for <code>generativelanguage.googleapis.com</code> .
<p><code>p- </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-generativelanguage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Gke On-Prem Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>gkeonprem.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkeonprem.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a><br />
( <code>roles/gkeonprem.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Google APIs Service Agent Service agent used internally by Google Cloud.
<p><var translate="no">PROJECT_NUMBER </var><code> @cloudservices.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a><br />
( <code>roles/editor</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Cloud Dataproc Resource Manager Node Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataprocrm.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dataprocrmnode.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a><br />
( <code>roles/dataprocrm.nodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Google Cloud Dataproc Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>dataproc.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @dataproc-accounts.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a><br />
( <code>roles/dataproc.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Cloud Functions Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>cloudfunctions.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcf-admin-robot.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a><br />
( <code>roles/cloudfunctions.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Google Cloud ML Engine Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>ml.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloud-ml.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a><br />
( <code>roles/ml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Cloud NetApp Volumes Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>netapp.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-netapp.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Google Cloud Network Security Authz Service Account Service agent for <code>networksecurity.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ns-authz.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.authzServiceAgent">Network Security Authz Service Agent</a><br />
( <code>roles/networksecurity.authzServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Cloud OS Config Rollout Service Agent Service agent for <code>osconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a><br />
( <code>roles/osconfig.rolloutServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Google Cloud OS Config Rollout Service Agent Service agent for <code>osconfig.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Google Cloud OS Config Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>osconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-osconfig.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a><br />
( <code>roles/osconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Google Cloud OS Config Service Agent Service agent for <code>osconfig.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-osconfig.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-osconfig.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Google Cloud Run AI Bundle Service Agent Service agent for <code>run.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-run-ai.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Google Cloud Run Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>run.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @serverless-robot-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a><br />
( <code>roles/run.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Cloud Service Extensions Service Account Service agent for <code>networkservices.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-dep.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Google Container Registry Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>containerregistry.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @containerregistry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a><br />
( <code>roles/containerregistry.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Google Storage Service Agent Service agent for <code>storage.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gs-project-accounts.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>IAP Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>iap.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-iap.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Identity Pool Resource Identity Service agent for <code>iam.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-ri-identitypool.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Infra Spanner Production Service Account Service agent for <code>spanner.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-global-spanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Infrastructure Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>config.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-config.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a><br />
( <code>roles/cloudconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Integrated Vulnerability Scanner Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ivs.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Internal Cloud Firestore Spanner Service Agent Service agent for <code>firestore.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-fs-spanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>KRM API Hosting Service Account Service agent for <code>krmapihosting.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-krmapihosting.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a><br />
( <code>roles/krmapihosting.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>KRM API Hosting Service Account Service agent for <code>krmapihosting.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-krmapihosting-dataplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a><br />
( <code>roles/krmapihosting.anthosApiEndpointServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Kubernetes Engine Node Service Agent Service agent for <code>container.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-gkenode.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a><br />
( <code>roles/container.defaultNodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Kubernetes Engine Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>container.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @container-engine-robot.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a><br />
( <code>roles/container.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Legacy Cloud Build service account Service agent for <code>cloudbuild.googleapis.com</code> .
<p><var translate="no">PROJECT_NUMBER </var><code> @cloudbuild.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a><br />
( <code>roles/cloudbuild.builds.builder</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Livestream Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>livestream.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-livestream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a><br />
( <code>roles/livestream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Logging Service Agent Service agent for <code>logging.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>p </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code>f </code><var translate="no"> FOLDER_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>o </code><var translate="no"> ORGANIZATION_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Looker Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>looker.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-looker.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a><br />
( <code>roles/looker.restrictedServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Lustre Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>lustre.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-lustre.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Managed Flink Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>managedflink.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-managedflink.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a><br />
( <code>roles/managedflink.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Managed Kafka Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>managedkafka.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-managedkafka.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a><br />
( <code>roles/managedkafka.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Memorystore Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>memorystore.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-memorystore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a><br />
( <code>roles/memorystore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Mesh Config Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>meshconfig.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-meshconfig.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshconfig.serviceAgent">Mesh Config Service Agent</a><br />
( <code>roles/meshconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Model Armor Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>modelarmor.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-modelarmor.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a><br />
( <code>roles/modelarmor.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Monitoring Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>monitoring.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-monitoring-notification.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a><br />
( <code>roles/monitoring.notificationServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Multi Cluster Ingress Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>multiclusteringress.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-multiclusteringress.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a><br />
( <code>roles/multiclusteringress.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Multi cluster metering Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>multiclustermetering.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-mcmetering.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a><br />
( <code>roles/multiclustermetering.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Multi-cluster Service Discovery Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>multiclusterservicediscovery.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-mcsd.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a><br />
( <code>roles/multiclusterservicediscovery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Network Actions Service Account Service agent for <code>networkservices.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-networkactions.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#networkactions.serviceAgent">Network Actions Service Agent</a><br />
( <code>roles/networkactions.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Network Connectivity Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>networkconnectivity.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-networkconnectivity.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a><br />
( <code>roles/networkconnectivity.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Network Security Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>networksecurity.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-networksecurity.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>On-Demand Scanning Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>ondemandscanning.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-ondemandscanning.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>oracledatabase.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-oci.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a><br />
( <code>roles/oci.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Parallelstore Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>parallelstore.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-parallelstore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a><br />
( <code>roles/parallelstore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Parameter Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>parametermanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-pm.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Playbook Runner Service Agent Service agent for <code>integrations.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>p </code><var translate="no"> PROJECT_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code>f </code><var translate="no"> FOLDER_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>o </code><var translate="no"> ORGANIZATION_NUMBER </var><code> - </code><var translate="no"> IDENTIFIER </var><code> @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Policy Remediator Service Agent (prod) Service agent for <code>policyremediator.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-v1-remediator.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Private CA Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>privateca.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-privateca.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Privileged Access Manager Service Agent Service agent for <code>privilegedaccessmanager.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Progressive Rollout Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>progressiverollout.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-progrollout.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/progressiverollout#progressiverollout.serviceAgent">Progressive Rollout Service Agent</a><br />
( <code>roles/progressiverollout.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Progressive Rollout Service Agent Service agent for <code>progressiverollout.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code>service-folder- </code><var translate="no"> FOLDER_NUMBER </var><code> @gcp-sa-progrollout.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-progrollout.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td>Pub/Sub Lite Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>pubsublite.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-pubsublite.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a><br />
( <code>roles/pubsublite.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Rapid Migration Assessment Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>rapidmigrationassessment.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-rma.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a><br />
( <code>roles/rapidmigrationassessment.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>remotebuildexecution.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-rbe.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Remote Build Execution Service Agent Service agent for <code>remotebuildexecution.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @remotebuildexecution.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a><br />
( <code>roles/remotebuildexecution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Service Agent Service agent for <code>remotebuildexecution.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-remotebuild.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a><br />
( <code>roles/remotebuildexecution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Retail Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>retail.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-retail.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a><br />
( <code>roles/retail.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>SCC CMEK Spanner Service Agent (PROD) Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service-org- </code><var translate="no"> ORGANIZATION_NUMBER </var><code> @gcp-sa-sccspanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>SaaS Service Management Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>saasservicemgmt.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-saasservicemgmt.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a><br />
( <code>roles/saasservicemgmt.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Secret Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>secretmanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-secretmanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Secure Source Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>securesourcemanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-sourcemanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a><br />
( <code>roles/securesourcemanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Secure Web Proxy Service Account Service agent for <code>networkservices.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-securewebproxy.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Serverless Integrations Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>runapps.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-runapps.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a><br />
( <code>roles/runapps.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Serverless VPC Access Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>vpcaccess.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vpcaccess.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a><br />
( <code>roles/vpcaccess.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Service Agent Manager Service agent used internally by Google Cloud.
<p><code>service-agent-manager@system.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Service Consumer Management Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>serviceconsumermanagement.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @service-consumer-management.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Service Directory Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>servicedirectory.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-servicedirectory.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a><br />
( <code>roles/servicedirectory.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Service Networking Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>servicenetworking.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @service-networking.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a><br />
( <code>roles/servicenetworking.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Skill Registry Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-skills.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Spectrum SAS Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>sasportal.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-spectrumsas.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a><br />
( <code>roles/spectrumsas.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Speech-to-Text Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>speech.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-speech.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a><br />
( <code>roles/speech.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Storage Insights Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>storageinsights.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-storageinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.serviceAgent">StorageInsights Service Agent</a><br />
( <code>roles/storageinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Storage Transfer Service Service Agent Service agent for <code>storagetransfer.googleapis.com</code> .
<p><code>project- </code><var translate="no"> PROJECT_NUMBER </var><code> @storage-transfer-service.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Stream Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>stream.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-stream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a><br />
( <code>roles/stream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>TPU Service Agent <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>tpu.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @cloud-tpu.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a><br />
( <code>roles/tpu.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>TPU Service Agent (v2) Service agent for <code>tpu.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-tpu.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a><br />
( <code>roles/cloudtpu.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Transcoder Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>transcoder.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-transcoder.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a><br />
( <code>roles/transcoder.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Transfer Appliance Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>transferappliance.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-transferappliance.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>VMwareEngine Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>vmwareengine.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vmwareengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a><br />
( <code>roles/vmwareengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vector Search Cmek Service Account Service agent for <code>vectorsearch.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vs-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Vector Search Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>vectorsearch.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vectorsearch.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a><br />
( <code>roles/vectorsearch.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Agent Sandbox Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-sandbox.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a><br />
( <code>roles/aiplatform.agentSandboxServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Vertex AI Ancillary Secure Fine Tuning Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-shtune.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a><br />
( <code>roles/aiplatform.user</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Batch Prediction Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-bp.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a><br />
( <code>roles/aiplatform.batchPredictionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Vertex AI Colab Service Account Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-nb.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabServiceAgent">Vertex AI Colab Service Agent</a><br />
( <code>roles/aiplatform.colabServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Extension Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-ex.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a><br />
( <code>roles/aiplatform.extensionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Vertex AI Extension Service Agent for Custom Code Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-ex-cc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a><br />
( <code>roles/aiplatform.extensionCustomCodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Logging Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-logging.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Vertex AI Managed OSS Fine Tuning Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-moss-ft.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a><br />
( <code>roles/aiplatform.tuningServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Model Monitoring Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-mm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a><br />
( <code>roles/aiplatform.modelMonitoringServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Vertex AI Notebook Service Account Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-aiplatform-vm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a><br />
( <code>roles/aiplatform.notebookServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Online Prediction Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-op.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a><br />
( <code>roles/aiplatform.onlinePredictionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Vertex AI Secure Fine Tuning Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-tune.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a><br />
( <code>roles/aiplatform.tuningServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Session Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-session.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Vertex AI Telemetry Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-telemetry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a><br />
( <code>roles/aiplatform.telemetryServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Vertex AI Training Cluster Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-vtc.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td>Vertex Agent Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-agent.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Vertex RAG Data Service Agent Service agent for <code>aiplatform.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-vertex-rag.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a><br />
( <code>roles/aiplatform.ragServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Virtual Machine Threat Detection Service Account Service agent for <code>securitycenter.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-scc-vmtd.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td>Vision AI Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>visionai.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-visionai.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a><br />
( <code>roles/visionai.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td>Workload Manager Service Account <a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code>workloadmanager.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-workloadmanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a><br />
( <code>roles/workloadmanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td>Workstations VM Default Service Account Service agent for <code>workstations.googleapis.com</code> .
<p><code>service- </code><var translate="no"> PROJECT_NUMBER </var><code> @gcp-sa-workstationsvm.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
</tbody>
</table>
