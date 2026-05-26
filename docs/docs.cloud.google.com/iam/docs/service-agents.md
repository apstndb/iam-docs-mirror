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
<td><h4 id="ai-platform-custom-code-service-agent" class="service-agent-name add-link" data-text="AI Platform Custom Code Service Agent" tabindex="-1">AI Platform Custom Code Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-cc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.customCodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="ai-platform-example-store-service-agent" class="service-agent-name add-link" data-text="AI Platform Example Store Service Agent" tabindex="-1">AI Platform Example Store Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-es.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="ai-platform-fine-tuning-service-agent" class="service-agent-name add-link" data-text="AI Platform Fine Tuning Service Agent" tabindex="-1">AI Platform Fine Tuning Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-ft.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="ai-platform-infra-spanner-service-agent" class="service-agent-name add-link" data-text="AI Platform Infra Spanner Service Agent" tabindex="-1">AI Platform Infra Spanner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-is.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="ai-platform-private-instance-(pie)-service-agent" class="service-agent-name add-link" data-text="AI Platform Private Instance (PIE) Service Agent" tabindex="-1">AI Platform Private Instance (PIE) Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-pie.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="ai-platform-rapid-eval-service-agent" class="service-agent-name add-link" data-text="AI Platform Rapid Eval Service Agent" tabindex="-1">AI Platform Rapid Eval Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-eval.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.rapidevalServiceAgent">Vertex AI Rapid Eval Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.rapidevalServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="ai-platform-reasoning-engine-service-agent" class="service-agent-name add-link" data-text="AI Platform Reasoning Engine Service Agent" tabindex="-1">AI Platform Reasoning Engine Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-re.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.reasoningEngineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="ai-platform-resource-identity" class="service-agent-name add-link" data-text="AI Platform Resource Identity" tabindex="-1">AI Platform Resource Identity</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-ri-aiplatform.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="ai-platform-service-agent" class="service-agent-name add-link" data-text="AI Platform Service Agent" tabindex="-1">AI Platform Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="api-hub-service-account" class="service-agent-name add-link" data-text="API Hub Service Account" tabindex="-1">API Hub Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apihub.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apihub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apihub.runtimeProjectServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="api-keys-service-account" class="service-agent-name add-link" data-text="API Keys Service Account" tabindex="-1">API Keys Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apikeys.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apikeys.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="apim-service-account" class="service-agent-name add-link" data-text="APIM Service Account" tabindex="-1">APIM Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apim.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apim.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.apiDiscoveryServiceAgent">APIM API Discovery Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apim.apiDiscoveryServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="asm-mesh-control-plane-service-account" class="service-agent-name add-link" data-text="ASM Mesh Control Plane Service Account" tabindex="-1">ASM Mesh Control Plane Service Account</h4>
Service agent for <code dir="ltr" translate="no">meshconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-meshcontrolplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a><br />
( <code dir="ltr" translate="no">roles/meshcontrolplane.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="asm-mesh-data-plane-service-account" class="service-agent-name add-link" data-text="ASM Mesh Data Plane Service Account" tabindex="-1">ASM Mesh Data Plane Service Account</h4>
Service agent for <code dir="ltr" translate="no">meshconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-meshdataplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a><br />
( <code dir="ltr" translate="no">roles/meshdataplane.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="access-approval-service-agent" class="service-agent-name add-link" data-text="Access Approval Service Agent" tabindex="-1">Access Approval Service Agent</h4>
Service agent for <code dir="ltr" translate="no">accessapproval.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">service-p            PROJECT_NUMBER           @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-f            FOLDER_NUMBER           @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-o            ORGANIZATION_NUMBER           @gcp-sa-accessapproval.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="ads-data-hub-service-account" class="service-agent-name add-link" data-text="Ads Data Hub Service Account" tabindex="-1">Ads Data Hub Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">adsdatahub.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-adsdatahub.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="agent-gateway-service-account" class="service-agent-name add-link" data-text="Agent Gateway Service Account" tabindex="-1">Agent Gateway Service Account</h4>
Service agent for <code dir="ltr" translate="no">networkservices.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-agentgateway.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentgateway#agentgateway.serviceAgent">Agent Gateway Service Agent</a><br />
( <code dir="ltr" translate="no">roles/agentgateway.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb-service-account" class="service-agent-name add-link" data-text="AlloyDB Service Account" tabindex="-1">AlloyDB Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">alloydb.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-alloydb.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.serviceAgent">AlloyDB Service Agent</a><br />
( <code dir="ltr" translate="no">roles/alloydb.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb-service-agent" class="service-agent-name add-link" data-text="AlloyDB Service Agent" tabindex="-1">AlloyDB Service Agent</h4>
Service agent for <code dir="ltr" translate="no">alloydb.googleapis.com</code> .
<p><code dir="ltr" translate="no">c-           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-alloydb.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="anthos-audit-service-account" class="service-agent-name add-link" data-text="Anthos Audit Service Account" tabindex="-1">Anthos Audit Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">anthosaudit.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthosaudit.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit#anthosaudit.serviceAgent">Anthos Audit Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthosaudit.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="anthos-config-management-service-account" class="service-agent-name add-link" data-text="Anthos Config Management Service Account" tabindex="-1">Anthos Config Management Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">anthosconfigmanagement.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthosconfigmanagement.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosconfigmanagement#anthosconfigmanagement.serviceAgent">Anthos Config Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthosconfigmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="anthos-identity-service-account" class="service-agent-name add-link" data-text="Anthos Identity Service Account" tabindex="-1">Anthos Identity Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">anthosidentityservice.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthosidentityservice.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice#anthosidentityservice.serviceAgent">Anthos Identity Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthosidentityservice.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="anthos-multi-cloud-container-service-agent" class="service-agent-name add-link" data-text="Anthos Multi-Cloud Container Service Agent" tabindex="-1">Anthos Multi-Cloud Container Service Agent</h4>
Service agent for <code dir="ltr" translate="no">gkemulticloud.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkemulticloudcontainer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkemulticloud.containerServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="anthos-multi-cloud-control-plane-machine-service-agent" class="service-agent-name add-link" data-text="Anthos Multi-Cloud Control Plane Machine Service Agent" tabindex="-1">Anthos Multi-Cloud Control Plane Machine Service Agent</h4>
Service agent for <code dir="ltr" translate="no">gkemulticloud.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkemulticloudcpmachine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.controlPlaneMachineServiceAgent">Anthos Multi-Cloud Control Plane Machine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkemulticloud.controlPlaneMachineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="anthos-multi-cloud-node-pool-machine-service-agent" class="service-agent-name add-link" data-text="Anthos Multi-Cloud Node Pool Machine Service Agent" tabindex="-1">Anthos Multi-Cloud Node Pool Machine Service Agent</h4>
Service agent for <code dir="ltr" translate="no">gkemulticloud.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkemulticloudnpmachine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.nodePoolMachineServiceAgent">Anthos Multi-Cloud Node Pool Machine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkemulticloud.nodePoolMachineServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="anthos-multi-cloud-service-agent" class="service-agent-name add-link" data-text="Anthos Multi-Cloud Service Agent" tabindex="-1">Anthos Multi-Cloud Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gkemulticloud.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkemulticloud.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkemulticloud.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="anthos-policy-controller-service-account" class="service-agent-name add-link" data-text="Anthos Policy Controller Service Account" tabindex="-1">Anthos Policy Controller Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">anthospolicycontroller.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthospolicycontroller.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthospolicycontroller#anthospolicycontroller.serviceAgent">Anthos Policy Controller Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthospolicycontroller.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="anthos-service-account" class="service-agent-name add-link" data-text="Anthos Service Account" tabindex="-1">Anthos Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">anthos.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthos.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthos#anthos.serviceAgent">Anthos Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthos.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="anthos-service-mesh-service-account" class="service-agent-name add-link" data-text="Anthos Service Mesh Service Account" tabindex="-1">Anthos Service Mesh Service Account</h4>
Service agent for <code dir="ltr" translate="no">meshconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-servicemesh.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthosservicemesh.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="anthos-support-service-account" class="service-agent-name add-link" data-text="Anthos Support Service Account" tabindex="-1">Anthos Support Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">connectgateway.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-anthossupport.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a><br />
( <code dir="ltr" translate="no">roles/anthossupport.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="apigee-registry-service-account" class="service-agent-name add-link" data-text="Apigee Registry Service Account" tabindex="-1">Apigee Registry Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apigeeregistry.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apigeeregistry.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="apigee-service-agent" class="service-agent-name add-link" data-text="Apigee Service Agent" tabindex="-1">Apigee Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apigee.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apigee.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apigee.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="apigee-service-agent-project" class="service-agent-name add-link" data-text="Apigee Service Agent" tabindex="-1">Apigee Service Agent</h4>
Service agent for <code dir="ltr" translate="no">apigee.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apigee.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apigee.coreServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="app-development-experience-service-account" class="service-agent-name add-link" data-text="App Development Experience Service Account" tabindex="-1">App Development Experience Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">appdevelopmentexperience.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-appdevexperience.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience#appdevelopmentexperience.serviceAgent">App Development Experience Service Agent</a><br />
( <code dir="ltr" translate="no">roles/appdevelopmentexperience.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="app-engine-flexible-environment-service-agent" class="service-agent-name add-link" data-text="App Engine Flexible Environment Service Agent" tabindex="-1">App Engine Flexible Environment Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">appengineflex.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gae-api-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a><br />
( <code dir="ltr" translate="no">roles/appengineflex.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="app-engine-standard-environment-service-agent" class="service-agent-name add-link" data-text="App Engine Standard Environment Service Agent" tabindex="-1">App Engine Standard Environment Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">appenginestandard.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-gae-service.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a><br />
( <code dir="ltr" translate="no">roles/appengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="app-hub-service-account" class="service-agent-name add-link" data-text="App Hub Service Account" tabindex="-1">App Hub Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">apphub.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apphub.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="app-optimize-service-agent" class="service-agent-name add-link" data-text="App Optimize Service Agent" tabindex="-1">App Optimize Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">appoptimize.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-appoptimize.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="application-integration-service-agent" class="service-agent-name add-link" data-text="Application Integration Service Agent" tabindex="-1">Application Integration Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">integrations.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-integrations.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a><br />
( <code dir="ltr" translate="no">roles/integrations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="artifact-registry-service-agent" class="service-agent-name add-link" data-text="Artifact Registry Service Agent" tabindex="-1">Artifact Registry Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">artifactregistry.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-artifactregistry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.serviceAgent">Artifact Registry Service Agent</a><br />
( <code dir="ltr" translate="no">roles/artifactregistry.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="assured-oss-service-agent" class="service-agent-name add-link" data-text="Assured OSS Service Agent" tabindex="-1">Assured OSS Service Agent</h4>
Service agent for <code dir="ltr" translate="no">assuredoss.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-assuredoss.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="assured-workloads-service-agent" class="service-agent-name add-link" data-text="Assured Workloads Service Agent" tabindex="-1">Assured Workloads Service Agent</h4>
Service agent for <code dir="ltr" translate="no">assuredworkloads.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-folder-           FOLDER_NUMBER          @gcp-sa-assuredworkloads.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="assuredworkloads-service-account" class="service-agent-name add-link" data-text="AssuredWorkloads Service Account" tabindex="-1">AssuredWorkloads Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">assuredworkloads.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-assuredworkloads.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.serviceAgent">Assured Workloads Service Agent</a><br />
( <code dir="ltr" translate="no">roles/assuredworkloads.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="attack-surface-management-service-agent" class="service-agent-name add-link" data-text="Attack Surface Management Service Agent" tabindex="-1">Attack Surface Management Service Agent</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-asm-hpsa.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="audit-manager-service-agent" class="service-agent-name add-link" data-text="Audit Manager Service Agent" tabindex="-1">Audit Manager Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">auditmanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-audit-manager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a><br />
( <code dir="ltr" translate="no">roles/auditmanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="audit-manager-service-agent-folder-organization" class="service-agent-name add-link" data-text="Audit Manager Service Agent" tabindex="-1">Audit Manager Service Agent</h4>
Service agent for <code dir="ltr" translate="no">auditmanager.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-audit-manager.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-audit-manager.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="auto-annotate-service-account" class="service-agent-name add-link" data-text="Auto Annotate Service Account" tabindex="-1">Auto Annotate Service Account</h4>
Service agent for <code dir="ltr" translate="no">storage.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-autoannotate.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="automl-recommendations-service-account" class="service-agent-name add-link" data-text="AutoML Recommendations Service Account" tabindex="-1">AutoML Recommendations Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">recommendationengine.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-recommendationengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a><br />
( <code dir="ltr" translate="no">roles/automlrecommendations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="automl-service-agent" class="service-agent-name add-link" data-text="AutoML Service Agent" tabindex="-1">AutoML Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">automl.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-automl.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.serviceAgent">AutoML Service Agent</a><br />
( <code dir="ltr" translate="no">roles/automl.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="backup-and-dr-runner-service-agent" class="service-agent-name add-link" data-text="Backup and DR Runner Service Agent" tabindex="-1">Backup and DR Runner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">backupdr.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-backupdr-run.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="backup-and-dr-service-agent" class="service-agent-name add-link" data-text="Backup and DR Service Agent" tabindex="-1">Backup and DR Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">backupdr.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-backupdr.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a><br />
( <code dir="ltr" translate="no">roles/backupdr.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="backup-and-dr-vault-service-agent" class="service-agent-name add-link" data-text="Backup and DR Vault Service Agent" tabindex="-1">Backup and DR Vault Service Agent</h4>
Service agent for <code dir="ltr" translate="no">backupdr.googleapis.com</code> .
<p><code dir="ltr" translate="no">vault-           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-backupdr-pr.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="backup-for-gke-service-account" class="service-agent-name add-link" data-text="Backup for GKE Service Account" tabindex="-1">Backup for GKE Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gkebackup.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkebackup.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkebackup.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="bare-metal-solution-service-account" class="service-agent-name add-link" data-text="Bare Metal Solution Service Account" tabindex="-1">Bare Metal Solution Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">baremetalsolution.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bms.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.serviceAgent">Bare Metal Solution Service Agent</a><br />
( <code dir="ltr" translate="no">roles/baremetalsolution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="batch-service-account" class="service-agent-name add-link" data-text="Batch Service Account" tabindex="-1">Batch Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">batch.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudbatch.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a><br />
( <code dir="ltr" translate="no">roles/batch.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="big-query-service-agent" class="service-agent-name add-link" data-text="Big Query Service Agent" tabindex="-1">Big Query Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">bq-           PROJECT_NUMBER          @bigquery-encryption.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="biglake-iceberg-rest-catalog-api-service-agent" class="service-agent-name add-link" data-text="BigLake Iceberg Rest Catalog API Service Agent" tabindex="-1">BigLake Iceberg Rest Catalog API Service Agent</h4>
Service agent for <code dir="ltr" translate="no">biglake.googleapis.com</code> .
<p><code dir="ltr" translate="no">blirc-           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-biglakerestcatalog.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="bigquery-connected-sheets-service-agent" class="service-agent-name add-link" data-text="BigQuery Connected Sheets Service Agent" tabindex="-1">BigQuery Connected Sheets Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-connectedsheets.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.connectedSheetsServiceAgent">Connected Sheets Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigquery.connectedSheetsServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquery-connection-delegation-service-agent" class="service-agent-name add-link" data-text="BigQuery Connection Delegation Service Agent" tabindex="-1">BigQuery Connection Delegation Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigqueryconnection.googleapis.com</code> .
<ul>
<li><code dir="ltr" translate="no">bqcx-            PROJECT_NUMBER           -            IDENTIFIER           @gcp-sa-bigquery-condel.iam.gserviceaccount.com</code></li>
<li><code dir="ltr" translate="no">connection-            PROJECT_NUMBER           -            IDENTIFIER           @gcp-sa-bigquery-condel.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="bigquery-connection-service-agent" class="service-agent-name add-link" data-text="BigQuery Connection Service Agent" tabindex="-1">BigQuery Connection Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">bigqueryconnection.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigqueryconnection.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigqueryconnection.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquery-continuous-query-service-agent" class="service-agent-name add-link" data-text="BigQuery Continuous Query Service Agent" tabindex="-1">BigQuery Continuous Query Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigquerytardis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery#bigquerycontinuousquery.serviceAgent">BigQuery Continuous Query Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigquerycontinuousquery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquery-data-transfer-service-agent" class="service-agent-name add-link" data-text="BigQuery Data Transfer Service Agent" tabindex="-1">BigQuery Data Transfer Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">bigquerydatatransfer.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigquerydatatransfer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigquerydatatransfer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquery-migration-service-agent" class="service-agent-name add-link" data-text="BigQuery Migration Service Agent" tabindex="-1">BigQuery Migration Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">bigquerymigration.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bqms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="bigquery-omni-service-agent" class="service-agent-name add-link" data-text="BigQuery Omni Service Agent" tabindex="-1">BigQuery Omni Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-prod-bigqueryomni.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryomni#bigqueryomni.serviceAgent">BigQuery Omni Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigqueryomni.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquery-resource-identity-service-account" class="service-agent-name add-link" data-text="BigQuery Resource Identity Service Account" tabindex="-1">BigQuery Resource Identity Service Account</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigqueryri.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="bigquery-spark-connection-delegate-service-agent" class="service-agent-name add-link" data-text="BigQuery Spark Connection Delegate Service Agent" tabindex="-1">BigQuery Spark Connection Delegate Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigqueryconnection.googleapis.com</code> .
<p><code dir="ltr" translate="no">bqcx-           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-bigquery-consp.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="bigquery-spark-service-agent" class="service-agent-name add-link" data-text="BigQuery Spark Service Agent" tabindex="-1">BigQuery Spark Service Agent</h4>
Service agent for <code dir="ltr" translate="no">bigquery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigqueryspark.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark#bigqueryspark.serviceAgent">BigQuery Spark Service Agent</a><br />
( <code dir="ltr" translate="no">roles/bigqueryspark.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="binary-authorization-service-agent" class="service-agent-name add-link" data-text="Binary Authorization Service Agent" tabindex="-1">Binary Authorization Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">binaryauthorization.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-binaryauthorization.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a><br />
( <code dir="ltr" translate="no">roles/binaryauthorization.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchain-node-engine-service-account" class="service-agent-name add-link" data-text="Blockchain Node Engine Service Account" tabindex="-1">Blockchain Node Engine Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">blockchainnodeengine.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bne.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.serviceAgent">Blockchain Node Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/blockchainnodeengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="bundles-service-agent" class="service-agent-name add-link" data-text="Bundles Service Agent" tabindex="-1">Bundles Service Agent</h4>
Service agent for <code dir="ltr" translate="no">integrations.googleapis.com</code> .
<p><code dir="ltr" translate="no">b           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-bundles.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="chronicle-organization-service-account" class="service-agent-name add-link" data-text="Chronicle Organization Service Account" tabindex="-1">Chronicle Organization Service Account</h4>
Service agent for <code dir="ltr" translate="no">chronicle.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-chronicle-org.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="chronicle-service-account" class="service-agent-name add-link" data-text="Chronicle Service Account" tabindex="-1">Chronicle Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">chronicle.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-chronicle.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a><br />
( <code dir="ltr" translate="no">roles/chronicle.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="chronicle-soar-service-agent" class="service-agent-name add-link" data-text="Chronicle Soar Service Agent" tabindex="-1">Chronicle Soar Service Agent</h4>
Service agent for <code dir="ltr" translate="no">chronicle.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-chronicle-soar.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-ai-platform-notebooks-service-account" class="service-agent-name add-link" data-text="Cloud AI Platform Notebooks Service Account" tabindex="-1">Cloud AI Platform Notebooks Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">notebooks.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-notebooks.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a><br />
( <code dir="ltr" translate="no">roles/notebooks.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-ai-platform-notebooks-vm-service-account" class="service-agent-name add-link" data-text="Cloud AI Platform Notebooks VM Service Account" tabindex="-1">Cloud AI Platform Notebooks VM Service Account</h4>
Service agent for <code dir="ltr" translate="no">notebooks.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-notebooks-vm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.notebookServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-api-gateway-management-plane-service-account" class="service-agent-name add-link" data-text="Cloud API Gateway Management Plane Service Account" tabindex="-1">Cloud API Gateway Management Plane Service Account</h4>
Service agent for <code dir="ltr" translate="no">apigateway.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apigateway-mgmt.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apigateway_management.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-api-gateway-service-account" class="service-agent-name add-link" data-text="Cloud API Gateway Service Account" tabindex="-1">Cloud API Gateway Service Account</h4>
Service agent for <code dir="ltr" translate="no">apigateway.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-apigateway.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a><br />
( <code dir="ltr" translate="no">roles/apigateway.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-asset-effective-policy-service-agent" class="service-agent-name add-link" data-text="Cloud Asset Effective Policy Service Agent" tabindex="-1">Cloud Asset Effective Policy Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudasset.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-effectivepolicy.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-asset-other-cloud-config-service-agent" class="service-agent-name add-link" data-text="Cloud Asset Other Cloud Config Service Agent" tabindex="-1">Cloud Asset Other Cloud Config Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudasset.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-othercloudcfg.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-asset-service-agent" class="service-agent-name add-link" data-text="Cloud Asset Service Agent" tabindex="-1">Cloud Asset Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudasset.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudasset.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.serviceAgent">Cloud Asset Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudasset.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-bigtable-service-agent" class="service-agent-name add-link" data-text="Cloud Bigtable Service Agent" tabindex="-1">Cloud Bigtable Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">bigtableadmin.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-bigtable.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-build-service-agent" class="service-agent-name add-link" data-text="Cloud Build Service Agent" tabindex="-1">Cloud Build Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudbuild.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudbuild.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudbuild.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-certificate-manager-service-account" class="service-agent-name add-link" data-text="Cloud Certificate Manager Service Account" tabindex="-1">Cloud Certificate Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">certificatemanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-certificatemanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.serviceAgent">Certificate Manager Service Agent</a><br />
( <code dir="ltr" translate="no">roles/certificatemanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-composer-service-agent" class="service-agent-name add-link" data-text="Cloud Composer Service Agent" tabindex="-1">Cloud Composer Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">composer.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloudcomposer-accounts.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/composer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-controls-partner-service-agent" class="service-agent-name add-link" data-text="Cloud Controls Partner Service Agent" tabindex="-1">Cloud Controls Partner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudcontrolspartner.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-folder-           FOLDER_NUMBER          @gcp-sa-cloudcontrolspartner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-dns-service-account" class="service-agent-name add-link" data-text="Cloud DNS Service Account" tabindex="-1">Cloud DNS Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dns.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dns.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.serviceAgent">Cloud DNS Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dns.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-data-fusion-service-account" class="service-agent-name add-link" data-text="Cloud Data Fusion Service Account" tabindex="-1">Cloud Data Fusion Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datafusion.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datafusion.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datafusion.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-data-loss-prevention-service-agent" class="service-agent-name add-link" data-text="Cloud Data Loss Prevention Service Agent" tabindex="-1">Cloud Data Loss Prevention Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dlp.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @dlp-api.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dlp.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-database-migration-service-account" class="service-agent-name add-link" data-text="Cloud Database Migration Service Account" tabindex="-1">Cloud Database Migration Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datamigration.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datamigration.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datamigration.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-dataflow-service-account" class="service-agent-name add-link" data-text="Cloud Dataflow Service Account" tabindex="-1">Cloud Dataflow Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataflow.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @dataflow-service-producer-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataflow.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-dataplex-service-account" class="service-agent-name add-link" data-text="Cloud Dataplex Service Account" tabindex="-1">Cloud Dataplex Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataplex.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dataplex.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataplex.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-datastream-service-account" class="service-agent-name add-link" data-text="Cloud Datastream Service Account" tabindex="-1">Cloud Datastream Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datastream.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datastream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datastream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-deploy-service-account" class="service-agent-name add-link" data-text="Cloud Deploy Service Account" tabindex="-1">Cloud Deploy Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">clouddeploy.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-clouddeploy.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a><br />
( <code dir="ltr" translate="no">roles/clouddeploy.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-endpoints-service-agent" class="service-agent-name add-link" data-text="Cloud Endpoints Service Agent" tabindex="-1">Cloud Endpoints Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">endpoints.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-endpoints.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a><br />
( <code dir="ltr" translate="no">roles/endpoints.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-file-storage-service-account" class="service-agent-name add-link" data-text="Cloud File Storage Service Account" tabindex="-1">Cloud File Storage Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">file.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloud-filer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a><br />
( <code dir="ltr" translate="no">roles/file.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-firestore-service-agent" class="service-agent-name add-link" data-text="Cloud Firestore Service Agent" tabindex="-1">Cloud Firestore Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firestore.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firestore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#firestore.serviceAgent">Firestore Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firestore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-healthcare-service-agent" class="service-agent-name add-link" data-text="Cloud Healthcare Service Agent" tabindex="-1">Cloud Healthcare Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">healthcare.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-healthcare.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a><br />
( <code dir="ltr" translate="no">roles/healthcare.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-identity-platform-service-agent" class="service-agent-name add-link" data-text="Cloud Identity Platform Service Agent" tabindex="-1">Cloud Identity Platform Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">identitytoolkit.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-identitytoolkit.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a><br />
( <code dir="ltr" translate="no">roles/identitytoolkit.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-kms-organization-service-agent" class="service-agent-name add-link" data-text="Cloud KMS Organization Service Agent" tabindex="-1">Cloud KMS Organization Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudkms.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-cloudkms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-kms-service-agent" class="service-agent-name add-link" data-text="Cloud KMS Service Agent" tabindex="-1">Cloud KMS Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudkms.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudkms.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.serviceAgent">Cloud KMS Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudkms.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-logging-service-account" class="service-agent-name add-link" data-text="Cloud Logging Service Account" tabindex="-1">Cloud Logging Service Account</h4>
Service agent for <code dir="ltr" translate="no">logging.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-logging.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.serviceAgent">Cloud Logging Service Agent</a><br />
( <code dir="ltr" translate="no">roles/logging.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-logging-service-agent" class="service-agent-name add-link" data-text="Cloud Logging Service Agent" tabindex="-1">Cloud Logging Service Agent</h4>
Service agent for <code dir="ltr" translate="no">logging.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-managed-identities-service-agent" class="service-agent-name add-link" data-text="Cloud Managed Identities Service Agent" tabindex="-1">Cloud Managed Identities Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">managedidentities.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-mi.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a><br />
( <code dir="ltr" translate="no">roles/managedidentities.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-memorystore-memcache-service-agent" class="service-agent-name add-link" data-text="Cloud Memorystore Memcache Service Agent" tabindex="-1">Cloud Memorystore Memcache Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">memcache.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloud-memcache-sa.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a><br />
( <code dir="ltr" translate="no">roles/memcache.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-memorystore-redis-service-agent" class="service-agent-name add-link" data-text="Cloud Memorystore Redis Service Agent" tabindex="-1">Cloud Memorystore Redis Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">redis.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloud-redis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a><br />
( <code dir="ltr" translate="no">roles/redis.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-migration-center-service-account" class="service-agent-name add-link" data-text="Cloud Migration Center Service Account" tabindex="-1">Cloud Migration Center Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">migrationcenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-migcenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.serviceAgent">Migration Center Service Agent</a><br />
( <code dir="ltr" translate="no">roles/migrationcenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-network-management-service-account" class="service-agent-name add-link" data-text="Cloud Network Management Service Account" tabindex="-1">Cloud Network Management Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">networkmanagement.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-networkmanagement.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.serviceAgent">GCP Network Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/networkmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-notebook-security-scanner-service-agent" class="service-agent-name add-link" data-text="Cloud Notebook Security Scanner Service Agent" tabindex="-1">Cloud Notebook Security Scanner Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">notebooksecurityscanner.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-notebooksecurityscanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-notebook-security-scanner-service-agent-gcp-sa-nss-hpsa" class="service-agent-name add-link" data-text="Cloud Notebook Security Scanner Service Agent" tabindex="-1">Cloud Notebook Security Scanner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">notebooksecurityscanner.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">service-            PROJECT_NUMBER           @gcp-sa-nss-hpsa.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-nss-hpsa.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-observability-service-account" class="service-agent-name add-link" data-text="Cloud Observability Service Account" tabindex="-1">Cloud Observability Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">observability.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-observability.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.serviceAgent">Observability Service Agent</a><br />
( <code dir="ltr" translate="no">roles/observability.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-observability-service-account-folder-organization" class="service-agent-name add-link" data-text="Cloud Observability Service Account" tabindex="-1">Cloud Observability Service Account</h4>
Service agent for <code dir="ltr" translate="no">observability.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-observability.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-observability.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-optimization-service-agent" class="service-agent-name add-link" data-text="Cloud Optimization Service Agent" tabindex="-1">Cloud Optimization Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudoptimization.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudoptim.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudoptimization#cloudoptimization.serviceAgent">Cloud Optimization Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudoptimization.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-optimization-service-agent-gcp-sa-routeoptim" class="service-agent-name add-link" data-text="Cloud Optimization Service Agent" tabindex="-1">Cloud Optimization Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">routeoptimization.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-routeoptim.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.serviceAgent">Route Optimization Service Agent</a><br />
( <code dir="ltr" translate="no">roles/routeoptimization.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-pub/sub-service-account" class="service-agent-name add-link" data-text="Cloud Pub/Sub Service Account" tabindex="-1">Cloud Pub/Sub Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">pubsub.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-pubsub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a><br />
( <code dir="ltr" translate="no">roles/pubsub.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-resource-manager-service-agent" class="service-agent-name add-link" data-text="Cloud Resource Manager Service Agent" tabindex="-1">Cloud Resource Manager Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-cloudresourcemanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="cloud-risk-manager-service-agent" class="service-agent-name add-link" data-text="Cloud Risk Manager Service Agent" tabindex="-1">Cloud Risk Manager Service Agent</h4>
Service agent for <code dir="ltr" translate="no">dlp.googleapis.com</code> .
<p><code dir="ltr" translate="no">organizations-           ORGANIZATION_NUMBER          @gcp-sa-riskmanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-sql-service-account" class="service-agent-name add-link" data-text="Cloud SQL Service Account" tabindex="-1">Cloud SQL Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">sqladmin.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.serviceAgent">Cloud SQL Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudsql.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-sql-service-agent" class="service-agent-name add-link" data-text="Cloud SQL Service Agent" tabindex="-1">Cloud SQL Service Agent</h4>
Service agent for <code dir="ltr" translate="no">sqladmin.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">p            PROJECT_NUMBER           -            IDENTIFIER           @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">f            FOLDER_NUMBER           -            IDENTIFIER           @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">o            ORGANIZATION_NUMBER           -            IDENTIFIER           @gcp-sa-cloud-sql.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-scheduler-service-account" class="service-agent-name add-link" data-text="Cloud Scheduler Service Account" tabindex="-1">Cloud Scheduler Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudscheduler.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudscheduler.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudscheduler.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-security-command-center-bulk-export-service-account" class="service-agent-name add-link" data-text="Cloud Security Command Center Bulk Export Service Account" tabindex="-1">Cloud Security Command Center Bulk Export Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-scc-bulk-export.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-security-command-center-notification-service-account" class="service-agent-name add-link" data-text="Cloud Security Command Center Notification Service Account" tabindex="-1">Cloud Security Command Center Notification Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-scc-notification.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationServiceAgent">Security Center Notification Service Agent</a><br />
( <code dir="ltr" translate="no">roles/securitycenter.notificationServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-security-command-center-notification-service-account-organization" class="service-agent-name add-link" data-text="Cloud Security Command Center Notification Service Account" tabindex="-1">Cloud Security Command Center Notification Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-scc-notification.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-security-command-center-service-account" class="service-agent-name add-link" data-text="Cloud Security Command Center Service Account" tabindex="-1">Cloud Security Command Center Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-securitycenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a><br />
( <code dir="ltr" translate="no">roles/securitycenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-security-command-center-service-agent" class="service-agent-name add-link" data-text="Cloud Security Command Center Service Agent" tabindex="-1">Cloud Security Command Center Service Agent</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @security-center-api.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-security-compliance-service-agent" class="service-agent-name add-link" data-text="Cloud Security Compliance Service Agent" tabindex="-1">Cloud Security Compliance Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudsecuritycompliance.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-csc-hpsa.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudsecuritycompliance.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-security-compliance-service-agent-organization" class="service-agent-name add-link" data-text="Cloud Security Compliance Service Agent" tabindex="-1">Cloud Security Compliance Service Agent</h4>
Service agent for <code dir="ltr" translate="no">cloudsecuritycompliance.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-csc-hpsa.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-spanner-production-service-account" class="service-agent-name add-link" data-text="Cloud Spanner Production Service Account" tabindex="-1">Cloud Spanner Production Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">spanner.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-spanner.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/spanner.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-storage-for-firebase-service-agent" class="service-agent-name add-link" data-text="Cloud Storage for Firebase Service Agent" tabindex="-1">Cloud Storage for Firebase Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebasestorage.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebasestorage.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.serviceAgent">Cloud Storage for Firebase Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebasestorage.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-tasks-service-account" class="service-agent-name add-link" data-text="Cloud Tasks Service Account" tabindex="-1">Cloud Tasks Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudtasks.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudtasks.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudtasks.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-trace-service-account" class="service-agent-name add-link" data-text="Cloud Trace Service Account" tabindex="-1">Cloud Trace Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudtrace.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloud-trace.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="cloud-translation-service-agent" class="service-agent-name add-link" data-text="Cloud Translation Service Agent" tabindex="-1">Cloud Translation Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">translate.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-translation.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.serviceAgent">Cloud Translation API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudtranslate.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-vm-migration-service-account" class="service-agent-name add-link" data-text="Cloud VM Migration Service Account" tabindex="-1">Cloud VM Migration Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">vmmigration.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vmmigration.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.serviceAgent">VM Migration Service Agent</a><br />
( <code dir="ltr" translate="no">roles/vmmigration.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-web-security-scanner-service-agent" class="service-agent-name add-link" data-text="Cloud Web Security Scanner Service Agent" tabindex="-1">Cloud Web Security Scanner Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">websecurityscanner.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-websecurityscanner.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#websecurityscanner.serviceAgent">Cloud Web Security Scanner Service Agent</a><br />
( <code dir="ltr" translate="no">roles/websecurityscanner.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud-workflows-service-agent" class="service-agent-name add-link" data-text="Cloud Workflows Service Agent" tabindex="-1">Cloud Workflows Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">workflows.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-workflows.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a><br />
( <code dir="ltr" translate="no">roles/workflows.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud-workstations-service-agent" class="service-agent-name add-link" data-text="Cloud Workstations Service Agent" tabindex="-1">Cloud Workstations Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">workstations.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-workstations.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a><br />
( <code dir="ltr" translate="no">roles/workstations.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="cluster-director-service-agent" class="service-agent-name add-link" data-text="Cluster Director Service Agent" tabindex="-1">Cluster Director Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">hypercomputecluster.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-hypercomputecluster.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a><br />
( <code dir="ltr" translate="no">roles/hypercomputecluster.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="compute-engine-service-agent" class="service-agent-name add-link" data-text="Compute Engine Service Agent" tabindex="-1">Compute Engine Service Agent</h4>
Service agent for <code dir="ltr" translate="no">compute.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @compute-system.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/compute.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="compute-usage-export-service-agent" class="service-agent-name add-link" data-text="Compute Usage Export Service Agent" tabindex="-1">Compute Usage Export Service Agent</h4>
Service agent for <code dir="ltr" translate="no">compute.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-compute-usage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="config-delivery-service-account" class="service-agent-name add-link" data-text="Config Delivery Service Account" tabindex="-1">Config Delivery Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">configdelivery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-configdelivery.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a><br />
( <code dir="ltr" translate="no">roles/configdelivery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="connectors-service-account" class="service-agent-name add-link" data-text="Connectors Service Account" tabindex="-1">Connectors Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">connectors.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-connectors.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a><br />
( <code dir="ltr" translate="no">roles/connectors.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="contact-center-ai-insights-service-account" class="service-agent-name add-link" data-text="Contact Center AI Insights Service Account" tabindex="-1">Contact Center AI Insights Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">contactcenterinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-contactcenterinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a><br />
( <code dir="ltr" translate="no">roles/contactcenterinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="contact-center-ai-insights-service-account-for-cmek-(prod)" class="service-agent-name add-link" data-text="Contact Center AI Insights Service Account for CMEK (prod)" tabindex="-1">Contact Center AI Insights Service Account for CMEK (prod)</h4>
Service agent for <code dir="ltr" translate="no">contactcenterinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ccinsights-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="contact-center-ai-platform-service-account" class="service-agent-name add-link" data-text="Contact Center AI Platform Service Account" tabindex="-1">Contact Center AI Platform Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">contactcenteraiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ccaip.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="contact-center-ai-shared-service-account-for-cmek-(prod)" class="service-agent-name add-link" data-text="Contact Center AI shared Service Account for CMEK (prod)" tabindex="-1">Contact Center AI shared Service Account for CMEK (prod)</h4>
Service agent for <code dir="ltr" translate="no">contactcenterinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ccai-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="contact-center-insights-resource-identity-(prod)" class="service-agent-name add-link" data-text="Contact Center Insights Resource Identity (prod)" tabindex="-1">Contact Center Insights Resource Identity (prod)</h4>
Service agent for <code dir="ltr" translate="no">contactcenterinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-ri-contactcenterinsights.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="container-analysis-service-agent" class="service-agent-name add-link" data-text="Container Analysis Service Agent" tabindex="-1">Container Analysis Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">containeranalysis.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @container-analysis.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a><br />
( <code dir="ltr" translate="no">roles/containeranalysis.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="container-scanning-service-agent" class="service-agent-name add-link" data-text="Container Scanning Service Agent" tabindex="-1">Container Scanning Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">containerscanning.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-containerscanning.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a><br />
( <code dir="ltr" translate="no">roles/containerscanning.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="container-security-service-agent" class="service-agent-name add-link" data-text="Container Security Service Agent" tabindex="-1">Container Security Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">containersecurity.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-containersec.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="container-threat-detection-service-agent" class="service-agent-name add-link" data-text="Container Threat Detection Service Agent" tabindex="-1">Container Threat Detection Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">containerthreatdetection.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ktd-control.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a><br />
( <code dir="ltr" translate="no">roles/containerthreatdetection.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="container-threat-detection-service-agent-gcp-sa-ktd-hpsa" class="service-agent-name add-link" data-text="Container Threat Detection Service Agent" tabindex="-1">Container Threat Detection Service Agent</h4>
Service agent for <code dir="ltr" translate="no">containerthreatdetection.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">service-            PROJECT_NUMBER           @gcp-sa-ktd-hpsa.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-ktd-hpsa.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="content-warehouse-service-account" class="service-agent-name add-link" data-text="Content Warehouse Service Account" tabindex="-1">Content Warehouse Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">contentwarehouse.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloud-cw.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.serviceAgent">Content Warehouse Service Agent</a><br />
( <code dir="ltr" translate="no">roles/contentwarehouse.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="customer-engagement-suite-service-account" class="service-agent-name add-link" data-text="Customer Engagement Suite Service Account" tabindex="-1">Customer Engagement Suite Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">ces.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ces.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a><br />
( <code dir="ltr" translate="no">roles/ces.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="data-connectors-service-account" class="service-agent-name add-link" data-text="Data Connectors Service Account" tabindex="-1">Data Connectors Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataconnectors.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dataconnectors.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.serviceAgent">Data Connectors Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataconnectors.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="data-labeling-service-account" class="service-agent-name add-link" data-text="Data Labeling Service Account" tabindex="-1">Data Labeling Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datalabeling.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datalabeling.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datalabeling.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="data-pipelines-service-agent" class="service-agent-name add-link" data-text="Data Pipelines Service Agent" tabindex="-1">Data Pipelines Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datapipelines.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datapipelines.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datapipelines.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="data-studio-cmek-service-account" class="service-agent-name add-link" data-text="Data Studio CMEK Service Account" tabindex="-1">Data Studio CMEK Service Account</h4>
Service agent for <code dir="ltr" translate="no">datastudio.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datastudio-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="data-studio-service-account" class="service-agent-name add-link" data-text="Data Studio Service Account" tabindex="-1">Data Studio Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">datastudio.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-datastudio.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.serviceAgent">Data Studio Service Agent</a><br />
( <code dir="ltr" translate="no">roles/datastudio.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="dataform-service-account" class="service-agent-name add-link" data-text="Dataform Service Account" tabindex="-1">Dataform Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dataform.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataform.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataplex-cmek-service-agent" class="service-agent-name add-link" data-text="Dataplex Cmek Service Agent" tabindex="-1">Dataplex Cmek Service Agent</h4>
Service agent for <code dir="ltr" translate="no">dataplex.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-dataplex-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="dataplex-service-agent" class="service-agent-name add-link" data-text="Dataplex Service Agent" tabindex="-1">Dataplex Service Agent</h4>
Service agent for <code dir="ltr" translate="no">dataplex.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-dataplex.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="dataproc-metastore-service-account" class="service-agent-name add-link" data-text="Dataproc Metastore Service Account" tabindex="-1">Dataproc Metastore Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">metastore.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-metastore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a><br />
( <code dir="ltr" translate="no">roles/metastore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="deprecated-monitoring-service-account" class="service-agent-name add-link" data-text="Deprecated Monitoring Service Account" tabindex="-1">Deprecated Monitoring Service Account</h4>
Service agent for <code dir="ltr" translate="no">monitoring.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-monitoring.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="design-center-service-account" class="service-agent-name add-link" data-text="Design Center Service Account" tabindex="-1">Design Center Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">designcenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-designcenter.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a><br />
( <code dir="ltr" translate="no">roles/designcenter.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="developer-connect-service-account" class="service-agent-name add-link" data-text="Developer Connect Service Account" tabindex="-1">Developer Connect Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">developerconnect.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-devconnect.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a><br />
( <code dir="ltr" translate="no">roles/developerconnect.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="dialogflow-service-account-for-cmek-(prod)" class="service-agent-name add-link" data-text="Dialogflow Service Account for CMEK (prod)" tabindex="-1">Dialogflow Service Account for CMEK (prod)</h4>
Service agent for <code dir="ltr" translate="no">dialogflow.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dialogflow-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="dialogflow-service-agent" class="service-agent-name add-link" data-text="Dialogflow Service Agent" tabindex="-1">Dialogflow Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dialogflow.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dialogflow.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dialogflow.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="discovery-engine-service-account" class="service-agent-name add-link" data-text="Discovery Engine Service Account" tabindex="-1">Discovery Engine Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">discoveryengine.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-discoveryengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/discoveryengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="document-ai-warehouse-cmek-infra-spanner-service-account" class="service-agent-name add-link" data-text="Document AI Warehouse CMEK Infra Spanner Service Account" tabindex="-1">Document AI Warehouse CMEK Infra Spanner Service Account</h4>
Service agent for <code dir="ltr" translate="no">contentwarehouse.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloud-cw-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="documentai-core-service-agent" class="service-agent-name add-link" data-text="DocumentAI Core Service Agent" tabindex="-1">DocumentAI Core Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">documentai.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-prod-dai-core.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentaicore.serviceAgent">DocumentAI Core Service Agent</a><br />
( <code dir="ltr" translate="no">roles/documentaicore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="edge-container-cluster-service-agent" class="service-agent-name add-link" data-text="Edge Container Cluster Service Agent" tabindex="-1">Edge Container Cluster Service Agent</h4>
Service agent for <code dir="ltr" translate="no">edgecontainer.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-edgecontainercluster.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a><br />
( <code dir="ltr" translate="no">roles/edgecontainer.clusterServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="edge-container-gcr-service-agent" class="service-agent-name add-link" data-text="Edge Container GCR Service Agent" tabindex="-1">Edge Container GCR Service Agent</h4>
Service agent for <code dir="ltr" translate="no">edgecontainer.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-edgecontainergcr.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="edge-container-service-agent" class="service-agent-name add-link" data-text="Edge Container Service Agent" tabindex="-1">Edge Container Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">edgecontainer.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-edgecontainer.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.serviceAgent">Edge Container Service Agent</a><br />
( <code dir="ltr" translate="no">roles/edgecontainer.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="enterprise-knowledge-graph-service-agent" class="service-agent-name add-link" data-text="Enterprise Knowledge Graph Service Agent" tabindex="-1">Enterprise Knowledge Graph Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">enterpriseknowledgegraph.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloud-ekg.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a><br />
( <code dir="ltr" translate="no">roles/enterpriseknowledgegraph.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="eventarc-service-agent" class="service-agent-name add-link" data-text="Eventarc Service Agent" tabindex="-1">Eventarc Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">eventarc.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-eventarc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a><br />
( <code dir="ltr" translate="no">roles/eventarc.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="external-key-management-service-service-account" class="service-agent-name add-link" data-text="External Key Management Service Service Account" tabindex="-1">External Key Management Service Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudkms.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ekms.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="firebase-ai-logic-service-account" class="service-agent-name add-link" data-text="Firebase AI Logic Service Account" tabindex="-1">Firebase AI Logic Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebasevertexai.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebasevertexai.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase Machine Learning Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebaseml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase-app-check-service-account" class="service-agent-name add-link" data-text="Firebase App Check Service Account" tabindex="-1">Firebase App Check Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebaseappcheck.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebaseappcheck.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappcheck#firebaseappcheck.serviceAgent">Firebase App Check Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebaseappcheck.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase-app-hosting-service-account" class="service-agent-name add-link" data-text="Firebase App Hosting Service Account" tabindex="-1">Firebase App Hosting Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebaseapphosting.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebaseapphosting.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebaseapphosting.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase-crashlytics-service-agent" class="service-agent-name add-link" data-text="Firebase Crashlytics Service Agent" tabindex="-1">Firebase Crashlytics Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebasecrashlytics.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-crashlytics.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.serviceAgent">Firebase Crashlytics Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebasecrashlytics.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase-data-connect-service-account" class="service-agent-name add-link" data-text="Firebase Data Connect Service Account" tabindex="-1">Firebase Data Connect Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebasedataconnect.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebasedataconnect.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebasedataconnect.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase-extensions-service-agent" class="service-agent-name add-link" data-text="Firebase Extensions Service Agent" tabindex="-1">Firebase Extensions Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebaseextensions.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebasemods.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebasemods.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase-machine-learning-service-account" class="service-agent-name add-link" data-text="Firebase Machine Learning Service Account" tabindex="-1">Firebase Machine Learning Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebaseml.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebaseml.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.serviceAgent">Firebase Machine Learning Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebaseml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase-management-service-agent" class="service-agent-name add-link" data-text="Firebase Management Service Agent" tabindex="-1">Firebase Management Service Agent</h4>
Service agent for <code dir="ltr" translate="no">firebase.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebase.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebase.managementServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="firebase-realtime-database-service-agent" class="service-agent-name add-link" data-text="Firebase Realtime Database Service Agent" tabindex="-1">Firebase Realtime Database Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebasedatabase.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firebasedatabase.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.serviceAgent">Firebase Realtime Database Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firebasedatabase.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebase-rules-service-agent" class="service-agent-name add-link" data-text="Firebase Rules Service Agent" tabindex="-1">Firebase Rules Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firebaserules.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @firebase-rules.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a><br />
( <code dir="ltr" translate="no">roles/firebaserules.system</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="firewall-insights-service-account" class="service-agent-name add-link" data-text="Firewall Insights Service Account" tabindex="-1">Firewall Insights Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">firewallinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-firewallinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firewallinsights#firewallinsights.serviceAgent">Cloud Firewall Insights Service Agent</a><br />
( <code dir="ltr" translate="no">roles/firewallinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="g-suite-add-ons-service-account" class="service-agent-name add-link" data-text="G Suite Add-ons Service Account" tabindex="-1">G Suite Add-ons Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gsuiteaddons.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gsuiteaddons.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="gcs-search-service-account" class="service-agent-name add-link" data-text="GCS Search Service Account" tabindex="-1">GCS Search Service Account</h4>
Service agent for <code dir="ltr" translate="no">storage.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-storage-search.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="gke-dataplane-v2-service-account" class="service-agent-name add-link" data-text="GKE Dataplane V2 Service Account" tabindex="-1">GKE Dataplane V2 Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gkedataplanev2.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkedataplanev2.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="gke-hub-api-service-account" class="service-agent-name add-link" data-text="GKE Hub API Service Account" tabindex="-1">GKE Hub API Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gkehub.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkehub.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkehub.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="gemini-code-assist-management-service-agent" class="service-agent-name add-link" data-text="Gemini Code Assist Management Service Agent" tabindex="-1">Gemini Code Assist Management Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">geminicodeassistmanagement.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-geminicodeassistmp.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/geminicodeassistmanagement.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="gemini-data-analytics-service-account" class="service-agent-name add-link" data-text="Gemini Data Analytics Service Account" tabindex="-1">Gemini Data Analytics Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">geminidataanalytics.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-geminidataanalytics.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="gemini-for-google-cloud-service-agent" class="service-agent-name add-link" data-text="Gemini for Google Cloud Service Agent" tabindex="-1">Gemini for Google Cloud Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudaicompanion.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-cloudaicompanion.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudaicompanion.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="generative-language-service-agent" class="service-agent-name add-link" data-text="Generative Language Service Agent" tabindex="-1">Generative Language Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">generativelanguage.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-generativelanguage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="generative-language-service-agent-project" class="service-agent-name add-link" data-text="Generative Language Service Agent" tabindex="-1">Generative Language Service Agent</h4>
Service agent for <code dir="ltr" translate="no">generativelanguage.googleapis.com</code> .
<p><code dir="ltr" translate="no">p-           PROJECT_NUMBER          -           IDENTIFIER          @gcp-sa-generativelanguage.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="gke-on-prem-service-account" class="service-agent-name add-link" data-text="Gke On-Prem Service Account" tabindex="-1">Gke On-Prem Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">gkeonprem.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkeonprem.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.serviceAgent">GKE On-Prem Service Agent</a><br />
( <code dir="ltr" translate="no">roles/gkeonprem.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="google-apis-service-agent" class="service-agent-name add-link" data-text="Google APIs Service Agent" tabindex="-1">Google APIs Service Agent</h4>
Service agent used internally by Google Cloud.
<p><code dir="ltr" translate="no">          PROJECT_NUMBER          @cloudservices.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a><br />
( <code dir="ltr" translate="no">roles/editor</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-dataproc-resource-manager-node-service-agent" class="service-agent-name add-link" data-text="Google Cloud Dataproc Resource Manager Node Service Agent" tabindex="-1">Google Cloud Dataproc Resource Manager Node Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataprocrm.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dataprocrmnode.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataprocrm.nodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-dataproc-service-agent" class="service-agent-name add-link" data-text="Google Cloud Dataproc Service Agent" tabindex="-1">Google Cloud Dataproc Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">dataproc.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @dataproc-accounts.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a><br />
( <code dir="ltr" translate="no">roles/dataproc.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-functions-service-agent" class="service-agent-name add-link" data-text="Google Cloud Functions Service Agent" tabindex="-1">Google Cloud Functions Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">cloudfunctions.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcf-admin-robot.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudfunctions.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-ml-engine-service-agent" class="service-agent-name add-link" data-text="Google Cloud ML Engine Service Agent" tabindex="-1">Google Cloud ML Engine Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">ml.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloud-ml.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a><br />
( <code dir="ltr" translate="no">roles/ml.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-netapp-volumes-service-account" class="service-agent-name add-link" data-text="Google Cloud NetApp Volumes Service Account" tabindex="-1">Google Cloud NetApp Volumes Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">netapp.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-netapp.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-network-security-authz-service-account" class="service-agent-name add-link" data-text="Google Cloud Network Security Authz Service Account" tabindex="-1">Google Cloud Network Security Authz Service Account</h4>
Service agent for <code dir="ltr" translate="no">networksecurity.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ns-authz.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.authzServiceAgent">Network Security Authz Service Agent</a><br />
( <code dir="ltr" translate="no">roles/networksecurity.authzServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-os-config-rollout-service-agent" class="service-agent-name add-link" data-text="Google Cloud OS Config Rollout Service Agent" tabindex="-1">Google Cloud OS Config Rollout Service Agent</h4>
Service agent for <code dir="ltr" translate="no">osconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a><br />
( <code dir="ltr" translate="no">roles/osconfig.rolloutServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-os-config-rollout-service-agent-folder-organization" class="service-agent-name add-link" data-text="Google Cloud OS Config Rollout Service Agent" tabindex="-1">Google Cloud OS Config Rollout Service Agent</h4>
Service agent for <code dir="ltr" translate="no">osconfig.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-osconfig-rollout.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-os-config-service-agent" class="service-agent-name add-link" data-text="Google Cloud OS Config Service Agent" tabindex="-1">Google Cloud OS Config Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">osconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-osconfig.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a><br />
( <code dir="ltr" translate="no">roles/osconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-os-config-service-agent-folder-organization" class="service-agent-name add-link" data-text="Google Cloud OS Config Service Agent" tabindex="-1">Google Cloud OS Config Service Agent</h4>
Service agent for <code dir="ltr" translate="no">osconfig.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-osconfig.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-osconfig.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-run-ai-bundle-service-agent" class="service-agent-name add-link" data-text="Google Cloud Run AI Bundle Service Agent" tabindex="-1">Google Cloud Run AI Bundle Service Agent</h4>
Service agent for <code dir="ltr" translate="no">run.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-run-ai.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="google-cloud-run-service-agent" class="service-agent-name add-link" data-text="Google Cloud Run Service Agent" tabindex="-1">Google Cloud Run Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">run.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @serverless-robot-prod.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a><br />
( <code dir="ltr" translate="no">roles/run.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-cloud-service-extensions-service-account" class="service-agent-name add-link" data-text="Google Cloud Service Extensions Service Account" tabindex="-1">Google Cloud Service Extensions Service Account</h4>
Service agent for <code dir="ltr" translate="no">networkservices.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-dep.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="google-container-registry-service-agent" class="service-agent-name add-link" data-text="Google Container Registry Service Agent" tabindex="-1">Google Container Registry Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">containerregistry.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @containerregistry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerregistry#containerregistry.ServiceAgent">Container Registry Service Agent</a><br />
( <code dir="ltr" translate="no">roles/containerregistry.ServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="google-storage-service-agent" class="service-agent-name add-link" data-text="Google Storage Service Agent" tabindex="-1">Google Storage Service Agent</h4>
Service agent for <code dir="ltr" translate="no">storage.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gs-project-accounts.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="iap-service-account" class="service-agent-name add-link" data-text="IAP Service Account" tabindex="-1">IAP Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">iap.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-iap.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="identity-pool-resource-identity" class="service-agent-name add-link" data-text="Identity Pool Resource Identity" tabindex="-1">Identity Pool Resource Identity</h4>
Service agent for <code dir="ltr" translate="no">iam.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-ri-identitypool.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="infra-spanner-production-service-account" class="service-agent-name add-link" data-text="Infra Spanner Production Service Account" tabindex="-1">Infra Spanner Production Service Account</h4>
Service agent for <code dir="ltr" translate="no">spanner.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-global-spanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="infrastructure-manager-service-account" class="service-agent-name add-link" data-text="Infrastructure Manager Service Account" tabindex="-1">Infrastructure Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">config.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-config.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="integrated-vulnerability-scanner-service-account" class="service-agent-name add-link" data-text="Integrated Vulnerability Scanner Service Account" tabindex="-1">Integrated Vulnerability Scanner Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ivs.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="internal-cloud-firestore-spanner-service-agent" class="service-agent-name add-link" data-text="Internal Cloud Firestore Spanner Service Agent" tabindex="-1">Internal Cloud Firestore Spanner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">firestore.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-fs-spanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="krm-api-hosting-service-account" class="service-agent-name add-link" data-text="KRM API Hosting Service Account" tabindex="-1">KRM API Hosting Service Account</h4>
Service agent for <code dir="ltr" translate="no">krmapihosting.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-krmapihosting.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a><br />
( <code dir="ltr" translate="no">roles/krmapihosting.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="krm-api-hosting-service-account-gcp-sa-krmapihosting-dataplane" class="service-agent-name add-link" data-text="KRM API Hosting Service Account" tabindex="-1">KRM API Hosting Service Account</h4>
Service agent for <code dir="ltr" translate="no">krmapihosting.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-krmapihosting-dataplane.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a><br />
( <code dir="ltr" translate="no">roles/krmapihosting.anthosApiEndpointServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="kubernetes-engine-node-service-agent" class="service-agent-name add-link" data-text="Kubernetes Engine Node Service Agent" tabindex="-1">Kubernetes Engine Node Service Agent</h4>
Service agent for <code dir="ltr" translate="no">container.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-gkenode.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a><br />
( <code dir="ltr" translate="no">roles/container.defaultNodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="kubernetes-engine-service-agent" class="service-agent-name add-link" data-text="Kubernetes Engine Service Agent" tabindex="-1">Kubernetes Engine Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">container.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @container-engine-robot.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/container.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="legacy-cloud-build-service-account" class="service-agent-name add-link" data-text="Legacy Cloud Build service account" tabindex="-1">Legacy Cloud Build service account</h4>
Service agent for <code dir="ltr" translate="no">cloudbuild.googleapis.com</code> .
<p><code dir="ltr" translate="no">          PROJECT_NUMBER          @cloudbuild.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a><br />
( <code dir="ltr" translate="no">roles/cloudbuild.builds.builder</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream-service-account" class="service-agent-name add-link" data-text="Livestream Service Account" tabindex="-1">Livestream Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">livestream.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-livestream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.serviceAgent">Live Stream Service Agent</a><br />
( <code dir="ltr" translate="no">roles/livestream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="logging-service-agent" class="service-agent-name add-link" data-text="Logging Service Agent" tabindex="-1">Logging Service Agent</h4>
Service agent for <code dir="ltr" translate="no">logging.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">p            PROJECT_NUMBER           -            IDENTIFIER           @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">f            FOLDER_NUMBER           -            IDENTIFIER           @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">o            ORGANIZATION_NUMBER           -            IDENTIFIER           @gcp-sa-logging.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="looker-service-account" class="service-agent-name add-link" data-text="Looker Service Account" tabindex="-1">Looker Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">looker.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-looker.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a><br />
( <code dir="ltr" translate="no">roles/looker.restrictedServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="lustre-service-agent" class="service-agent-name add-link" data-text="Lustre Service Agent" tabindex="-1">Lustre Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">lustre.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-lustre.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="managed-flink-service-agent" class="service-agent-name add-link" data-text="Managed Flink Service Agent" tabindex="-1">Managed Flink Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">managedflink.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-managedflink.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a><br />
( <code dir="ltr" translate="no">roles/managedflink.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="managed-kafka-service-account" class="service-agent-name add-link" data-text="Managed Kafka Service Account" tabindex="-1">Managed Kafka Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">managedkafka.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-managedkafka.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a><br />
( <code dir="ltr" translate="no">roles/managedkafka.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="memorystore-service-agent" class="service-agent-name add-link" data-text="Memorystore Service Agent" tabindex="-1">Memorystore Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">memorystore.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-memorystore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a><br />
( <code dir="ltr" translate="no">roles/memorystore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="mesh-config-service-account" class="service-agent-name add-link" data-text="Mesh Config Service Account" tabindex="-1">Mesh Config Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">meshconfig.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-meshconfig.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshconfig.serviceAgent">Mesh Config Service Agent</a><br />
( <code dir="ltr" translate="no">roles/meshconfig.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="model-armor-service-account" class="service-agent-name add-link" data-text="Model Armor Service Account" tabindex="-1">Model Armor Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">modelarmor.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-modelarmor.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a><br />
( <code dir="ltr" translate="no">roles/modelarmor.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="monitoring-service-account" class="service-agent-name add-link" data-text="Monitoring Service Account" tabindex="-1">Monitoring Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">monitoring.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-monitoring-notification.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a><br />
( <code dir="ltr" translate="no">roles/monitoring.notificationServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="multi-cluster-ingress-service-account" class="service-agent-name add-link" data-text="Multi Cluster Ingress Service Account" tabindex="-1">Multi Cluster Ingress Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">multiclusteringress.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-multiclusteringress.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress#multiclusteringress.serviceAgent">Multi Cluster Ingress Service Agent</a><br />
( <code dir="ltr" translate="no">roles/multiclusteringress.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="multi-cluster-metering-service-account" class="service-agent-name add-link" data-text="Multi cluster metering Service Account" tabindex="-1">Multi cluster metering Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">multiclustermetering.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-mcmetering.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclustermetering#multiclustermetering.serviceAgent">Multi-cluster metering Service Agent</a><br />
( <code dir="ltr" translate="no">roles/multiclustermetering.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="multi-cluster-service-discovery-service-account" class="service-agent-name add-link" data-text="Multi-cluster Service Discovery Service Account" tabindex="-1">Multi-cluster Service Discovery Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">multiclusterservicediscovery.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-mcsd.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a><br />
( <code dir="ltr" translate="no">roles/multiclusterservicediscovery.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="network-actions-service-account" class="service-agent-name add-link" data-text="Network Actions Service Account" tabindex="-1">Network Actions Service Account</h4>
Service agent for <code dir="ltr" translate="no">networkservices.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-networkactions.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkactions#networkactions.serviceAgent">Network Actions Service Agent</a><br />
( <code dir="ltr" translate="no">roles/networkactions.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="network-connectivity-service-account" class="service-agent-name add-link" data-text="Network Connectivity Service Account" tabindex="-1">Network Connectivity Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">networkconnectivity.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-networkconnectivity.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a><br />
( <code dir="ltr" translate="no">roles/networkconnectivity.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="network-security-service-account" class="service-agent-name add-link" data-text="Network Security Service Account" tabindex="-1">Network Security Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">networksecurity.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-networksecurity.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="on-demand-scanning-service-account" class="service-agent-name add-link" data-text="On-Demand Scanning Service Account" tabindex="-1">On-Demand Scanning Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">ondemandscanning.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-ondemandscanning.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="oracle-database@google-cloud-service-account" class="service-agent-name add-link" data-text="Oracle Database@Google Cloud Service Account" tabindex="-1">Oracle Database@Google Cloud Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">oracledatabase.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-oci.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a><br />
( <code dir="ltr" translate="no">roles/oci.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore-service-agent" class="service-agent-name add-link" data-text="Parallelstore Service Agent" tabindex="-1">Parallelstore Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">parallelstore.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-parallelstore.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a><br />
( <code dir="ltr" translate="no">roles/parallelstore.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="parameter-manager-service-account" class="service-agent-name add-link" data-text="Parameter Manager Service Account" tabindex="-1">Parameter Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">parametermanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-pm.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="playbook-runner-service-agent" class="service-agent-name add-link" data-text="Playbook Runner Service Agent" tabindex="-1">Playbook Runner Service Agent</h4>
Service agent for <code dir="ltr" translate="no">integrations.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">p            PROJECT_NUMBER           -            IDENTIFIER           @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">f            FOLDER_NUMBER           -            IDENTIFIER           @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">o            ORGANIZATION_NUMBER           -            IDENTIFIER           @gcp-sa-playbooks.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="policy-remediator-service-agent-(prod)" class="service-agent-name add-link" data-text="Policy Remediator Service Agent (prod)" tabindex="-1">Policy Remediator Service Agent (prod)</h4>
Service agent for <code dir="ltr" translate="no">policyremediator.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-v1-remediator.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="private-ca-service-account" class="service-agent-name add-link" data-text="Private CA Service Account" tabindex="-1">Private CA Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">privateca.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-privateca.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="privileged-access-manager-service-agent" class="service-agent-name add-link" data-text="Privileged Access Manager Service Agent" tabindex="-1">Privileged Access Manager Service Agent</h4>
Service agent for <code dir="ltr" translate="no">privilegedaccessmanager.googleapis.com</code> .
<p>For the project:</p>
<ul>
<li><code dir="ltr" translate="no">service-            PROJECT_NUMBER           @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul>
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-pam.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="progressive-rollout-service-agent" class="service-agent-name add-link" data-text="Progressive Rollout Service Agent" tabindex="-1">Progressive Rollout Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">progressiverollout.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-progrollout.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/progressiverollout#progressiverollout.serviceAgent">Progressive Rollout Service Agent</a><br />
( <code dir="ltr" translate="no">roles/progressiverollout.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="progressive-rollout-service-agent-folder-organization" class="service-agent-name add-link" data-text="Progressive Rollout Service Agent" tabindex="-1">Progressive Rollout Service Agent</h4>
Service agent for <code dir="ltr" translate="no">progressiverollout.googleapis.com</code> .
<p>For the folder:</p>
<ul>
<li><code dir="ltr" translate="no">service-folder-            FOLDER_NUMBER           @gcp-sa-progrollout.iam.gserviceaccount.com</code></li>
</ul>
<p>For the organization:</p>
<ul>
<li><code dir="ltr" translate="no">service-org-            ORGANIZATION_NUMBER           @gcp-sa-progrollout.iam.gserviceaccount.com</code></li>
</ul></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="pub/sub-lite-service-account" class="service-agent-name add-link" data-text="Pub/Sub Lite Service Account" tabindex="-1">Pub/Sub Lite Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">pubsublite.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-pubsublite.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsublite#pubsublite.serviceAgent">Pub/Sub Lite Service Agent</a><br />
( <code dir="ltr" translate="no">roles/pubsublite.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="rapid-migration-assessment-service-account" class="service-agent-name add-link" data-text="Rapid Migration Assessment Service Account" tabindex="-1">Rapid Migration Assessment Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">rapidmigrationassessment.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-rma.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a><br />
( <code dir="ltr" translate="no">roles/rapidmigrationassessment.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="remote-build-execution-service-agent" class="service-agent-name add-link" data-text="Remote Build Execution Service Agent" tabindex="-1">Remote Build Execution Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">remotebuildexecution.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-rbe.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="remote-build-execution-service-agent-remotebuildexecution" class="service-agent-name add-link" data-text="Remote Build Execution Service Agent" tabindex="-1">Remote Build Execution Service Agent</h4>
Service agent for <code dir="ltr" translate="no">remotebuildexecution.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @remotebuildexecution.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a><br />
( <code dir="ltr" translate="no">roles/remotebuildexecution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="remote-build-execution-service-agent-gcp-sa-remotebuild" class="service-agent-name add-link" data-text="Remote Build Execution Service Agent" tabindex="-1">Remote Build Execution Service Agent</h4>
Service agent for <code dir="ltr" translate="no">remotebuildexecution.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-remotebuild.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a><br />
( <code dir="ltr" translate="no">roles/remotebuildexecution.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail-service-account" class="service-agent-name add-link" data-text="Retail Service Account" tabindex="-1">Retail Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">retail.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-retail.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a><br />
( <code dir="ltr" translate="no">roles/retail.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="scc-cmek-spanner-service-agent-(prod)" class="service-agent-name add-link" data-text="SCC CMEK Spanner Service Agent (PROD)" tabindex="-1">SCC CMEK Spanner Service Agent (PROD)</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-org-           ORGANIZATION_NUMBER          @gcp-sa-sccspanner.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="saas-service-management-service-account" class="service-agent-name add-link" data-text="SaaS Service Management Service Account" tabindex="-1">SaaS Service Management Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">saasservicemgmt.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-saasservicemgmt.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a><br />
( <code dir="ltr" translate="no">roles/saasservicemgmt.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="secret-manager-service-account" class="service-agent-name add-link" data-text="Secret Manager Service Account" tabindex="-1">Secret Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">secretmanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-secretmanager.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="secure-source-manager-service-account" class="service-agent-name add-link" data-text="Secure Source Manager Service Account" tabindex="-1">Secure Source Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">securesourcemanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-sourcemanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a><br />
( <code dir="ltr" translate="no">roles/securesourcemanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="secure-web-proxy-service-account" class="service-agent-name add-link" data-text="Secure Web Proxy Service Account" tabindex="-1">Secure Web Proxy Service Account</h4>
Service agent for <code dir="ltr" translate="no">networkservices.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-securewebproxy.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="serverless-integrations-service-account" class="service-agent-name add-link" data-text="Serverless Integrations Service Account" tabindex="-1">Serverless Integrations Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">runapps.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-runapps.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a><br />
( <code dir="ltr" translate="no">roles/runapps.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="serverless-vpc-access-service-agent" class="service-agent-name add-link" data-text="Serverless VPC Access Service Agent" tabindex="-1">Serverless VPC Access Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">vpcaccess.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vpcaccess.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a><br />
( <code dir="ltr" translate="no">roles/vpcaccess.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="service-agent-manager" class="service-agent-name add-link" data-text="Service Agent Manager" tabindex="-1">Service Agent Manager</h4>
Service agent used internally by Google Cloud.
<p><code dir="ltr" translate="no">service-agent-manager@system.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="service-consumer-management-service-agent" class="service-agent-name add-link" data-text="Service Consumer Management Service Agent" tabindex="-1">Service Consumer Management Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">serviceconsumermanagement.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @service-consumer-management.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="service-directory-service-account" class="service-agent-name add-link" data-text="Service Directory Service Account" tabindex="-1">Service Directory Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">servicedirectory.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-servicedirectory.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a><br />
( <code dir="ltr" translate="no">roles/servicedirectory.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="service-networking-service-agent" class="service-agent-name add-link" data-text="Service Networking Service Agent" tabindex="-1">Service Networking Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">servicenetworking.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @service-networking.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a><br />
( <code dir="ltr" translate="no">roles/servicenetworking.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="skill-registry-service-agent" class="service-agent-name add-link" data-text="Skill Registry Service Agent" tabindex="-1">Skill Registry Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-skills.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="spectrum-sas-service-account" class="service-agent-name add-link" data-text="Spectrum SAS Service Account" tabindex="-1">Spectrum SAS Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">sasportal.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-spectrumsas.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a><br />
( <code dir="ltr" translate="no">roles/spectrumsas.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="speech-to-text-service-account" class="service-agent-name add-link" data-text="Speech-to-Text Service Account" tabindex="-1">Speech-to-Text Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">speech.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-speech.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/speech#speech.serviceAgent">Cloud Speech-to-Text Service Agent</a><br />
( <code dir="ltr" translate="no">roles/speech.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="storage-insights-service-account" class="service-agent-name add-link" data-text="Storage Insights Service Account" tabindex="-1">Storage Insights Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">storageinsights.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-storageinsights.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.serviceAgent">StorageInsights Service Agent</a><br />
( <code dir="ltr" translate="no">roles/storageinsights.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="storage-transfer-service-service-agent" class="service-agent-name add-link" data-text="Storage Transfer Service Service Agent" tabindex="-1">Storage Transfer Service Service Agent</h4>
Service agent for <code dir="ltr" translate="no">storagetransfer.googleapis.com</code> .
<p><code dir="ltr" translate="no">project-           PROJECT_NUMBER          @storage-transfer-service.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="stream-service-account" class="service-agent-name add-link" data-text="Stream Service Account" tabindex="-1">Stream Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">stream.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-stream.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a><br />
( <code dir="ltr" translate="no">roles/stream.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="tpu-service-agent" class="service-agent-name add-link" data-text="TPU Service Agent" tabindex="-1">TPU Service Agent</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">tpu.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @cloud-tpu.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/tpu.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="tpu-service-agent-(v2)" class="service-agent-name add-link" data-text="TPU Service Agent (v2)" tabindex="-1">TPU Service Agent (v2)</h4>
Service agent for <code dir="ltr" translate="no">tpu.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-tpu.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a><br />
( <code dir="ltr" translate="no">roles/cloudtpu.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="transcoder-service-account" class="service-agent-name add-link" data-text="Transcoder Service Account" tabindex="-1">Transcoder Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">transcoder.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-transcoder.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.serviceAgent">Transcoder Service Agent</a><br />
( <code dir="ltr" translate="no">roles/transcoder.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="transfer-appliance-service-account" class="service-agent-name add-link" data-text="Transfer Appliance Service Account" tabindex="-1">Transfer Appliance Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">transferappliance.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-transferappliance.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine-service-account" class="service-agent-name add-link" data-text="VMwareEngine Service Account" tabindex="-1">VMwareEngine Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">vmwareengine.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vmwareengine.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a><br />
( <code dir="ltr" translate="no">roles/vmwareengine.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vector-search-cmek-service-account" class="service-agent-name add-link" data-text="Vector Search Cmek Service Account" tabindex="-1">Vector Search Cmek Service Account</h4>
Service agent for <code dir="ltr" translate="no">vectorsearch.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vs-cmek.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="vector-search-service-account" class="service-agent-name add-link" data-text="Vector Search Service Account" tabindex="-1">Vector Search Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">vectorsearch.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vectorsearch.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.serviceAgent">Vector Search Service Agent</a><br />
( <code dir="ltr" translate="no">roles/vectorsearch.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-agent-sandbox-service-agent" class="service-agent-name add-link" data-text="Vertex AI Agent Sandbox Service Agent" tabindex="-1">Vertex AI Agent Sandbox Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-sandbox.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.agentSandboxServiceAgent">Vertex AI Agent Sandbox Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.agentSandboxServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-ancillary-secure-fine-tuning-service-agent" class="service-agent-name add-link" data-text="Vertex AI Ancillary Secure Fine Tuning Service Agent" tabindex="-1">Vertex AI Ancillary Secure Fine Tuning Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-shtune.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.user</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-batch-prediction-service-agent" class="service-agent-name add-link" data-text="Vertex AI Batch Prediction Service Agent" tabindex="-1">Vertex AI Batch Prediction Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-bp.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.batchPredictionServiceAgent">Vertex AI Batch Prediction Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.batchPredictionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-colab-service-account" class="service-agent-name add-link" data-text="Vertex AI Colab Service Account" tabindex="-1">Vertex AI Colab Service Account</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-nb.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabServiceAgent">Vertex AI Colab Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.colabServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-extension-service-agent" class="service-agent-name add-link" data-text="Vertex AI Extension Service Agent" tabindex="-1">Vertex AI Extension Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-ex.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.extensionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-extension-service-agent-for-custom-code" class="service-agent-name add-link" data-text="Vertex AI Extension Service Agent for Custom Code" tabindex="-1">Vertex AI Extension Service Agent for Custom Code</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-ex-cc.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.extensionCustomCodeServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-logging-service-agent" class="service-agent-name add-link" data-text="Vertex AI Logging Service Agent" tabindex="-1">Vertex AI Logging Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-logging.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-managed-oss-fine-tuning-service-agent" class="service-agent-name add-link" data-text="Vertex AI Managed OSS Fine Tuning Service Agent" tabindex="-1">Vertex AI Managed OSS Fine Tuning Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-moss-ft.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.tuningServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-model-monitoring-service-agent" class="service-agent-name add-link" data-text="Vertex AI Model Monitoring Service Agent" tabindex="-1">Vertex AI Model Monitoring Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-mm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.modelMonitoringServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-notebook-service-account" class="service-agent-name add-link" data-text="Vertex AI Notebook Service Account" tabindex="-1">Vertex AI Notebook Service Account</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-aiplatform-vm.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.notebookServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-online-prediction-service-agent" class="service-agent-name add-link" data-text="Vertex AI Online Prediction Service Agent" tabindex="-1">Vertex AI Online Prediction Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-op.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.onlinePredictionServiceAgent">Vertex AI Online Prediction Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.onlinePredictionServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-secure-fine-tuning-service-agent" class="service-agent-name add-link" data-text="Vertex AI Secure Fine Tuning Service Agent" tabindex="-1">Vertex AI Secure Fine Tuning Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-tune.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.tuningServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="vertex-ai-telemetry-service-agent" class="service-agent-name add-link" data-text="Vertex AI Telemetry Service Agent" tabindex="-1">Vertex AI Telemetry Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-telemetry.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.telemetryServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="vertex-ai-training-cluster-service-agent" class="service-agent-name add-link" data-text="Vertex AI Training Cluster Service Agent" tabindex="-1">Vertex AI Training Cluster Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-vtc.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="even">
<td><h4 id="vertex-agent-service-agent" class="service-agent-name add-link" data-text="Vertex Agent Service Agent" tabindex="-1">Vertex Agent Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-agent.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="vertex-rag-data-service-agent" class="service-agent-name add-link" data-text="Vertex RAG Data Service Agent" tabindex="-1">Vertex RAG Data Service Agent</h4>
Service agent for <code dir="ltr" translate="no">aiplatform.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-vertex-rag.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.ragServiceAgent">Vertex AI RAG Data Service Agent</a><br />
( <code dir="ltr" translate="no">roles/aiplatform.ragServiceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="virtual-machine-threat-detection-service-account" class="service-agent-name add-link" data-text="Virtual Machine Threat Detection Service Account" tabindex="-1">Virtual Machine Threat Detection Service Account</h4>
Service agent for <code dir="ltr" translate="no">securitycenter.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-scc-vmtd.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
<tr class="odd">
<td><h4 id="vision-ai-service-account" class="service-agent-name add-link" data-text="Vision AI Service Account" tabindex="-1">Vision AI Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">visionai.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-visionai.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a><br />
( <code dir="ltr" translate="no">roles/visionai.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="even">
<td><h4 id="workload-manager-service-account" class="service-agent-name add-link" data-text="Workload Manager Service Account" tabindex="-1">Workload Manager Service Account</h4>
<a href="https://docs.cloud.google.com/iam/docs/service-account-types#primary">Primary service agent</a> for <code dir="ltr" translate="no">workloadmanager.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-workloadmanager.iam.gserviceaccount.com</code></p></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a><br />
( <code dir="ltr" translate="no">roles/workloadmanager.serviceAgent</code> )</p>
<p>Granted on the project.</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations-vm-default-service-account" class="service-agent-name add-link" data-text="Workstations VM Default Service Account" tabindex="-1">Workstations VM Default Service Account</h4>
Service agent for <code dir="ltr" translate="no">workstations.googleapis.com</code> .
<p><code dir="ltr" translate="no">service-           PROJECT_NUMBER          @gcp-sa-workstationsvm.iam.gserviceaccount.com</code></p></td>
<td>None</td>
</tr>
</tbody>
</table>
