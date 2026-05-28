---
name: documents/docs.cloud.google.com/iam/docs/federated-identity-supported-services
uri: https://docs.cloud.google.com/iam/docs/federated-identity-supported-services
title: 'Identity federation: products and limitations'
description: Learn about the Google Cloud products that support Workforce Identity Federation and Workload Identity Federation, and review any limitations.
data_source: docs.cloud.google.com
---

## Overview

This page provides details of limitations and the level of support for each Google Cloud product that can use [Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-identity-federation) or [Workload Identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation) , collectively *identity federation* .

### Workforce Identity Federation

Workforce Identity Federation lets your workforce—employees, vendors, partners, and other users—access Google Cloud products by using an identity provider (IdP). Your workforce can access Google Cloud through the Google Cloud Workforce Identity Federation console, also known as the console (federated), the Google Cloud CLI, or a Google Cloud API.

Workforce Identity Federation limitations for the console (federated), the Google Cloud CLI, and Google Cloud API are listed in UI and API entries for each product.

### Workload Identity Federation

Workload Identity Federation lets your workloads programmatically access Google Cloud products by using workload-provided identities such as IAM roles for AWS workloads, Kubernetes service accounts for GKE workloads, or GitHub identities for your deployment pipelines.

Workload Identity Federation limitations for the Google Cloud CLI and Google Cloud APIs, collectively *API limitations* , are listed in `Google Cloud API limitations` entries for each product, later in this document.

## Google Cloud products and limitations

The table in this section lists products, their level of support for identity federation, limitations, and other information.

### Organization

The limitations table is organized in the following way:

**Product:** The product name.

**Identity federation launch stage:** Refers to the [launch stage](https://cloud.google.com/products/#product-launch-stages) of the product's support for identity federation. Launch stage doesn't refer to the launch stage of the product itself.

**Columns that describe supported products:**

  - **Google Cloud API:** The product's identity federation-related limitations that are associated with API methods and the gcloud CLI commands that access those methods.
  - **Console (federated):** The product's Workforce Identity Federation-related console (federated) UI limitations.
  - **Other:** The product's identity federation-related limitations that aren't Google Cloud API or console (federated) limitations.

**Columns that describe unsupported products:**

  - **Alternatives:** For products that don't support identity federation, this column describes alternative products that support identity federation and provide similar features.

## List of products and limitations

**Launch stage** GA Preview Unsupported

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Product</th>
<th><a href="https://cloud.google.com/products/#product-launch-stages">Identity federation launch stage</a></th>
<th>Limitations</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h3 id="access-approval" data-text="Access Approval" tabindex="-1"><a href="https://docs.cloud.google.com/assured-workloads/access-approval/docs">Access Approval</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="access-context-manager" data-text="Access Context Manager" tabindex="-1"><a href="https://docs.cloud.google.com/access-context-manager/docs">Access Context Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/access-context-manager/docs/reference/rpc/google.identity.accesscontextmanager.v1alpha"><code dir="ltr" translate="no">v1alpha</code> APIs</a> aren't available for federated identities.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="access-transparency" data-text="Access Transparency" tabindex="-1"><a href="https://docs.cloud.google.com/assured-workloads/access-transparency/docs">Access Transparency</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="agent-assist" data-text="Agent Assist" tabindex="-1"><a href="https://docs.cloud.google.com/agent-assist/docs">Agent Assist</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>In order to use <a href="https://docs.cloud.google.com/agent-assist/docs/basics#virtual_agents">Virtual Agent Handoff</a> with a Dialogflow ES agent, API callers cannot use Workforce Identity Federation for logging in.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/agent-assist/docs/smart-reply#import_conversation_transcripts_to_your_conversation_dataset">Agent Assist import of conversation transcripts to conversation datasets</a> does not support Workforce Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="alloydb-for-postgresql" data-text="AlloyDB for PostgreSQL" tabindex="-1"><a href="https://docs.cloud.google.com/alloydb/docs">AlloyDB for PostgreSQL</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>The following fleet health features aren't supported while using Workforce Identity Federation:
<ul>
<li>Performance and Backups summary cards</li>
<li>Data in the clusters table, such as CPU percentage and Memory Available</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="anti-money-laundering-ai" data-text="Anti Money Laundering AI" tabindex="-1"><a href="https://docs.cloud.google.com/financial-services/anti-money-laundering/docs/">Anti Money Laundering AI</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="api-gateway" data-text="API Gateway" tabindex="-1"><a href="https://docs.cloud.google.com/api-gateway/docs">API Gateway</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="apigee" data-text="Apigee" tabindex="-1"><a href="https://docs.cloud.google.com/apigee/docs">Apigee</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><p>Features in <a href="https://docs.cloud.google.com/products#product-launch-stages">Preview</a> aren't supported for Workforce Identity Federation users. This includes the following features:</p>
<ul>
<li><strong>Data Studio integration</strong></li>
<li><strong>Risk assessment</strong></li>
<li><strong>Shadow API discovery</strong></li>
</ul></li>
<li><p><a href="https://docs.cloud.google.com/apigee/docs/api-platform/local-development/overview">Local development with Apigee in Cloud Code</a> isn't supported for Workforce Identity Federation users.</p></li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li><p><a href="https://docs.cloud.google.com/apigee/docs/reference/apis/apim/rest">API Management APIs</a> don't support Workforce Identity Federation users.</p></li>
<li><p><a href="https://docs.cloud.google.com/apigee/docs/hybrid/v1.15/apigee-connect">Apigee Connect APIs</a> don't support Workforce Identity Federation users.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="apigee-api-hub" data-text="Apigee API hub" tabindex="-1"><a href="https://docs.cloud.google.com/apigee/docs/apihub/what-is-api-hub/">Apigee API hub</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="apis-and-services" data-text="APIs and Services" tabindex="-1"><a href="https://docs.cloud.google.com/apis/docs">APIs and Services</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://developers.google.com/identity/protocols/oauth2">OAuth client management</a> isn't supported.</li>
<li><a href="https://developers.google.com/identity/protocols/oauth2/production-readiness/brand-verification">OAuth brand management</a> isn't supported.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="app-engine" data-text="App Engine" tabindex="-1"><a href="https://docs.cloud.google.com/appengine/docs">App Engine</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>Google recommends that you use Cloud Run as an alternative.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="app-hub" data-text="App Hub" tabindex="-1"><a href="https://docs.cloud.google.com/app-hub/docs">App Hub</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="application-integration" data-text="Application Integration" tabindex="-1"><a href="https://docs.cloud.google.com/application-integration/docs">Application Integration</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="artifact-registry" data-text="Artifact Registry" tabindex="-1"><a href="https://docs.cloud.google.com/artifact-registry/docs">Artifact Registry</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>Container Registry doesn't support identity federation. There is an information banner in the settings page in <strong>Container Registry transition</strong> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="assured-workloads" data-text="Assured Workloads" tabindex="-1"><a href="https://docs.cloud.google.com/assured-workloads/docs">Assured Workloads</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="backup-and-dr-service" data-text="Backup and DR Service" tabindex="-1"><a href="https://docs.cloud.google.com/backup-disaster-recovery/docs">Backup and DR Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="batch" data-text="Batch" tabindex="-1"><a href="https://docs.cloud.google.com/batch/docs">Batch</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="bigquery" data-text="BigQuery" tabindex="-1"><a href="https://docs.cloud.google.com/bigquery/docs">BigQuery</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Saving queries isn't supported.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>The following features don't support Workforce Identity Federation with BigQuery:
<ul>
<li><a href="https://docs.cloud.google.com/bigquery/docs/connected-sheets">Connected Sheets</a></li>
<li><a href="https://docs.cloud.google.com/bigquery/docs/external-data-drive">Google Drive</a></li>
<li><a href="https://docs.cloud.google.com/bigquery/docs/recommendation-overview">Recommendations</a></li>
<li><a href="https://docs.cloud.google.com/bigquery/docs/slot-estimator">Slot estimator</a></li>
</ul></li>
<li>The following operations don't support Workforce Identity Federation:
<ul>
<li>Loading data from <a href="https://docs.cloud.google.com/bigquery/docs/omni-aws-create-connection">Amazon S3</a> , <a href="https://docs.cloud.google.com/bigquery/docs/connect-to-spark">Apache Spark</a> , or <a href="https://docs.cloud.google.com/bigquery/docs/omni-azure-create-connection">Azure Blob Storage</a> through the <a href="https://docs.cloud.google.com/bigquery/docs/connections-api-intro">Connection API</a></li>
<li>Loading data from <a href="https://docs.cloud.google.com/bigquery/docs/external-data-drive">Google Drive</a></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="bigtable" data-text="Bigtable" tabindex="-1"><a href="https://docs.cloud.google.com/bigtable/docs">Bigtable</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="binary-authorization" data-text="Binary Authorization" tabindex="-1"><a href="https://docs.cloud.google.com/binary-authorization/docs">Binary Authorization</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="blockchain-analytics" data-text="Blockchain Analytics" tabindex="-1"><a href="https://docs.cloud.google.com/blockchain-analytics/docs/overview">Blockchain Analytics</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="blockchain-node-engine" data-text="Blockchain Node Engine" tabindex="-1"><a href="https://docs.cloud.google.com/blockchain-node-engine/docs">Blockchain Node Engine</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="carbon-footprint" data-text="Carbon Footprint" tabindex="-1"><a href="https://docs.cloud.google.com/carbon-footprint/docs">Carbon Footprint</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="certificate-authority-service" data-text="Certificate Authority Service" tabindex="-1"><a href="https://docs.cloud.google.com/certificate-authority-service/docs">Certificate Authority Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="certificate-manager" data-text="Certificate Manager" tabindex="-1"><a href="https://docs.cloud.google.com/certificate-manager/docs">Certificate Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="channel-services" data-text="Channel Services" tabindex="-1"><a href="https://docs.cloud.google.com/channel/docs">Channel Services</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-asset-inventory" data-text="Cloud Asset Inventory" tabindex="-1"><a href="https://docs.cloud.google.com/asset-inventory/docs">Cloud Asset Inventory</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>In the <strong>IAM policy</strong> tab, the <strong>Analyze Full Access</strong> button is unavailable for Workforce Identity Federation users.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><p><a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeMove"><code dir="ltr" translate="no">analyzeMove</code></a> isn't supported by identity federation.</p></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-billing" data-text="Cloud Billing" tabindex="-1"><a href="https://docs.cloud.google.com/billing/docs">Cloud Billing</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Only <a href="https://docs.cloud.google.com/billing/docs/how-to/invoiced-billing">invoiced billing accounts</a> are supported.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Only <a href="https://docs.cloud.google.com/billing/docs/how-to/invoiced-billing">invoiced billing accounts</a> support identity federation.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-build" data-text="Cloud Build" tabindex="-1"><a href="https://docs.cloud.google.com/build/docs">Cloud Build</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-cdn" data-text="Cloud CDN" tabindex="-1"><a href="https://docs.cloud.google.com/cdn/docs">Cloud CDN</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-code" data-text="Cloud Code" tabindex="-1"><a href="https://docs.cloud.google.com/code/docs">Cloud Code</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="managed-service-for-apache-airflow" data-text="Managed Service for Apache Airflow" tabindex="-1"><a href="https://docs.cloud.google.com/composer/docs">Managed Service for Apache Airflow</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>Managed Airflow supports Workforce Identity Federation only for environments created in Composer version 2.1.11 or later and Airflow version 2.4.3 or later. Upgrading an environment from an earlier version does not enable Workforce Identity Federation support.</li>
<li>Email messages sent from Airflow only include the Airflow UI link that is accessible by Google accounts. To access Airflow UI as a Workforce Identity Federation user, the link must be manually updated (changed to the <a href="https://docs.cloud.google.com/composer/docs/composer-2/access-environments-with-workforce-identity-federation#access-airflow-ui">URL for Workforce Identity Federation</a> ).</li>
<li>Cloud Storage limitations apply to Managed Airflow environment bucket.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-console" data-text="Cloud Console" tabindex="-1"><a href="https://cloud.google.com/cloud-console">Cloud Console</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Workforce Identity Federation users can only access the <a href="https://console.cloud.google/">Google Cloud Workforce Identity Federation console, also known as the console (federated)</a> . They cannot access the Google Cloud console. The console (federated) provides limited access to only those Google Cloud products that support Workforce Identity Federation. For more information, see <a href="https://docs.cloud.google.com/iam/docs/workforce-console-learn-more">About the console (federated)</a> . Additionally, the console (federated) has the following limitations:
<ul>
<li>Language preference is selected at sign-on and can't be updated within the console.</li>
<li>Product notifications, updates and offers can't be enabled on the <a href="https://docs.cloud.google.com/resource-manager/docs/managing-notifications#manage-preferences">communication preferences</a> page.</li>
<li>Personalization based on your Google Cloud console activity is unsupported.</li>
<li>The <a href="https://docs.cloud.google.com/recommender/docs/opting-out">Transparency and Control Center</a> page is unavailable.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Workforce Identity Federation users aren't eligible for Google Cloud Free Trial.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-customer-care" data-text="Cloud Customer Care" tabindex="-1"><a href="https://docs.cloud.google.com/support/docs">Cloud Customer Care</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Due to the <a href="https://cloud.google.com/iam/docs/federated-identity-supported-services#cloud-billing">limitations of Cloud Billing for Workforce Identity Federation</a> , billing related support is accessible only to the organization's administrator through the Google Cloud account used to set up the billing account.</li>
<li>Workforce Identity Federation users can upload—but not download—support case-related files. These files are visible to the Support Engineers who handle your cases.</li>
<li>Contact details (e.g. Email Address) cannot be changed for Workforce Identity Federation users once interaction with Support has started.</li>
<li>Workforce Identity Federation users cannot create cases using the live chat support channel.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Cloud Support API doesn't support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-data-fusion" data-text="Cloud Data Fusion" tabindex="-1"><a href="https://docs.cloud.google.com/data-fusion/docs">Cloud Data Fusion</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-deploy" data-text="Cloud Deploy" tabindex="-1"><a href="https://docs.cloud.google.com/deploy/docs">Cloud Deploy</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Cloud Storage buckets must have <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> enabled to view Cloud Deploy artifacts.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Cloud Storage buckets created through Cloud Deploy have <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> enabled.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-deployment-manager" data-text="Cloud Deployment Manager" tabindex="-1"><a href="https://docs.cloud.google.com/deployment-manager/docs">Cloud Deployment Manager</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-dns" data-text="Cloud DNS" tabindex="-1"><a href="https://docs.cloud.google.com/dns/docs">Cloud DNS</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Cloud DNS has a limitation on the number of name server shards. To learn more, see <a href="https://docs.cloud.google.com/dns/quotas#name-server-limits">Name server limits</a> . Before allocating the final name server shard, Cloud DNS verifies ownership of the domain, which cannot be performed by federated identities.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-domains" data-text="Cloud Domains" tabindex="-1"><a href="https://docs.cloud.google.com/domains/docs">Cloud Domains</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-endpoints" data-text="Cloud Endpoints" tabindex="-1"><a href="https://docs.cloud.google.com/endpoints/docs">Cloud Endpoints</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-fleet-routing" data-text="Cloud Fleet Routing" tabindex="-1"><a href="https://cloud.google.com/ai">Cloud Fleet Routing</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-healthcare-api" data-text="Cloud Healthcare API" tabindex="-1"><a href="https://docs.cloud.google.com/healthcare-api/docs">Cloud Healthcare API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-hsm" data-text="Cloud HSM" tabindex="-1"><a href="https://docs.cloud.google.com/kms/docs/hsm">Cloud HSM</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-intrusion-detection-system" data-text="Cloud Intrusion Detection System" tabindex="-1"><a href="https://docs.cloud.google.com/intrusion-detection-system/docs/">Cloud Intrusion Detection System</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-key-management-service" data-text="Cloud Key Management Service" tabindex="-1"><a href="https://docs.cloud.google.com/kms/docs">Cloud Key Management Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-load-balancing" data-text="Cloud Load Balancing" tabindex="-1"><a href="https://docs.cloud.google.com/load-balancing/docs">Cloud Load Balancing</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-logging" data-text="Cloud Logging" tabindex="-1"><a href="https://docs.cloud.google.com/logging/docs">Cloud Logging</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-mobile-app" data-text="Cloud Mobile App" tabindex="-1"><a href="https://cloud.google.com/app">Cloud Mobile App</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-monitoring" data-text="Cloud Monitoring" tabindex="-1"><a href="https://docs.cloud.google.com/monitoring/docs">Cloud Monitoring</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><a href="https://docs.cloud.google.com/monitoring/agent/monitoring">The legacy Cloud Monitoring agent</a> doesn't support sending metrics with identity federation. Instead, Workforce Identity Federation users can install the <a href="https://cloud.google.com/monitoring/agent/ops-agent">Ops Agent</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-nat" data-text="Cloud NAT" tabindex="-1"><a href="https://docs.cloud.google.com/nat/docs">Cloud NAT</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-next-generation-firewall" data-text="Cloud Next Generation Firewall" tabindex="-1"><a href="https://docs.cloud.google.com/firewall/docs">Cloud Next Generation Firewall</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-profiler" data-text="Cloud Profiler" tabindex="-1"><a href="https://docs.cloud.google.com/profiler/docs/about-profiler/">Cloud Profiler</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-run" data-text="Cloud Run" tabindex="-1"><a href="https://docs.cloud.google.com/run/docs">Cloud Run</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><a href="https://docs.cloud.google.com/run/docs/continuous-deployment">Setting up continuous deployment with Cloud Build</a> from the Cloud Run console is disabled for Workforce Identity Federation. You must set up continuous deployment in Cloud Build.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>The IAM permission <code dir="ltr" translate="no">run.routes.invoke</code> , which can manage access to Cloud Run service endpoints, doesn't support Workforce Identity Federation. Enable <a href="https://docs.cloud.google.com/run/docs/securing/identity-aware-proxy-cloud-run">Identity-Aware Proxy for Cloud Run</a> to use it.</li>
<li>Cloud Run doesn't support Workload Identity Federation direct resource access. To allow access, use <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#impersonation">service account impersonation</a> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-run-functions" data-text="Cloud Run functions" tabindex="-1"><a href="https://docs.cloud.google.com/functions/docs">Cloud Run functions</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><a href="https://docs.cloud.google.com/run/docs/continuous-deployment">Setting up continuous deployment with Cloud Build</a> from the Cloud Run console is disabled for Workforce Identity Federation. You must set up continuous deployment in Cloud Build.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>The IAM permission <code dir="ltr" translate="no">run.routes.invoke</code> , which manages access to Cloud Run service endpoints, doesn't support Workforce Identity Federation. Enable <a href="https://docs.cloud.google.com/run/docs/securing/identity-aware-proxy-cloud-run">Identity-Aware Proxy for Cloud Run</a> to use it.</li>
<li>Cloud Run doesn't support Workload Identity Federation. To allow access, use <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#impersonation">service account impersonation</a> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-scheduler" data-text="Cloud Scheduler" tabindex="-1"><a href="https://docs.cloud.google.com/scheduler/docs">Cloud Scheduler</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>The App Engine Cron Jobs tab isn't available for Workforce Identity Federation users.</li>
<li>The App Engine option in the target type configuration isn't available for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The Cloud Scheduler API doesn't support identity federation for jobs that have their <code dir="ltr" translate="no">target</code> attribute set to <a href="https://docs.cloud.google.com/scheduler/docs/reference/rest/v1/projects.locations.jobs#appenginehttptarget"><code dir="ltr" translate="no">appEngineHttpTarget</code></a> . To send a job to an App Engine target using identity federation, create your job with the <code dir="ltr" translate="no">target</code> type set to <a href="https://docs.cloud.google.com/scheduler/docs/reference/rest/v1/projects.locations.jobs#HttpTarget"><code dir="ltr" translate="no">httpTarget</code></a> and the <code dir="ltr" translate="no">uri</code> field set to the full URI path of your App Engine target.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-service-mesh" data-text="Cloud Service Mesh" tabindex="-1"><a href="https://docs.cloud.google.com/service-mesh/docs">Cloud Service Mesh</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/service-mesh/docs/supported-features">In-cluster control plane</a> doesn't support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-shell" data-text="Cloud Shell" tabindex="-1"><a href="https://docs.cloud.google.com/shell/docs">Cloud Shell</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>Google recommends that you use Cloud Workstations as an alternative.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-source-repositories" data-text="Cloud Source Repositories" tabindex="-1"><a href="https://docs.cloud.google.com/source-repositories/docs">Cloud Source Repositories</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-sql" data-text="Cloud SQL" tabindex="-1"><a href="https://docs.cloud.google.com/sql/docs">Cloud SQL</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Query Insights isn't supported.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>The Help Assistant isn't supported.</li>
<li>IAM database authentication for user logins isn't supported for <a href="https://docs.cloud.google.com/sql/docs/mysql/iam-logins">Cloud SQL for MySQL</a> or <a href="https://docs.cloud.google.com/sql/docs/postgres/iam-logins">Cloud SQL for PostgreSQL</a> databases.</li>
<li>Query Insights isn't supported.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-storage" data-text="Cloud Storage" tabindex="-1"><a href="https://docs.cloud.google.com/storage/docs">Cloud Storage</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Viewing object details requires <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> to be enabled for the bucket.</li>
<li>Process with Cloud Run functions isn't supported.</li>
<li>Scan with Cloud Data Loss Prevention isn't supported.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Identity federation with all Cloud Storage APIs is supported only for <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> buckets. Identity federation access to buckets with fine-grained <a href="https://docs.cloud.google.com/storage/docs/access-control/lists">access control lists (ACLs)</a> is rejected.</li>
<li>Although all users and workloads can use existing <a href="https://docs.cloud.google.com/storage/docs/access-control/signed-urls">signed URLs</a> , identity federation users and workloads cannot generate signed URLs.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><a href="https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials#exchange_external_credentials_for_a_access_token">Google Cloud access tokens that are based on Workforce Identity Federation credentials</a> cannot be downscoped with <a href="https://docs.cloud.google.com/iam/docs/downscoping-short-lived-credentials">Credential Access Boundaries</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-talent-solution" data-text="Cloud Talent Solution" tabindex="-1"><a href="https://docs.cloud.google.com/talent-solution/docs">Cloud Talent Solution</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-tasks" data-text="Cloud Tasks" tabindex="-1"><a href="https://docs.cloud.google.com/tasks/docs">Cloud Tasks</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>The App Engine routing override option isn't available for Workforce Identity Federation users.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The Cloud Tasks API doesn't support identity federation for tasks that have App Engine targets—for example:
<ul>
<li><strong>App Engine queues:</strong> Since App Engine queues (queues that are created using a <code dir="ltr" translate="no">queue.yaml</code> or <code dir="ltr" translate="no">queue.xml</code> file) contain only tasks with App Engine targets, tasks in these queues aren't supported.</li>
<li><strong>Regular queues:</strong> For regular Cloud Tasks queues, tasks with HTTP targets are supported. Tasks with App Engine targets aren't supported (even though the queue isn't an App Engine queue).</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-trace" data-text="Cloud Trace" tabindex="-1"><a href="https://docs.cloud.google.com/trace/docs">Cloud Trace</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-translation" data-text="Cloud Translation" tabindex="-1"><a href="https://docs.cloud.google.com/translate/docs">Cloud Translation</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cloud-vision-api" data-text="Cloud Vision API" tabindex="-1"><a href="https://docs.cloud.google.com/vision/docs">Cloud Vision API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="cloud-workstations" data-text="Cloud Workstations" tabindex="-1"><a href="https://docs.cloud.google.com/workstations/docs">Cloud Workstations</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="cluster-director" data-text="Cluster Director" tabindex="-1"><a href="https://docs.cloud.google.com/cluster-director/docs">Cluster Director</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>To connect to the nodes in your cluster by using the <a href="https://docs.cloud.google.com/sdk/gcloud/reference/compute/ssh"><code dir="ltr" translate="no">gcloud compute ssh</code> command</a> , you must <a href="https://docs.cloud.google.com/compute/docs/oslogin/manage-oslogin-in-an-org#external-user">grant access to users outside of your organization</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="compute-engine" data-text="Compute Engine" tabindex="-1"><a href="https://docs.cloud.google.com/compute/docs">Compute Engine</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>To use <a href="https://docs.cloud.google.com/compute/docs/ssh-in-browser">SSH-in-browser</a> , you must set up <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings"><code dir="ltr" translate="no">google.posix_username</code> attribute mappings</a> .</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Image import from and export to a Cloud Storage bucket requires <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> to be enabled for the bucket.</li>
<li><a href="https://docs.cloud.google.com/bare-metal/docs">Bare Metal Solution</a> isn't supported.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="confidential-space" data-text="Confidential Space" tabindex="-1"><a href="https://docs.cloud.google.com/confidential-computing/docs">Confidential Space</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="context-aware-access" data-text="Context-Aware Access" tabindex="-1"><a href="https://docs.cloud.google.com/beyondcorp-enterprise/docs">Context-Aware Access</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>In <strong>Add principals to the Google Cloud console &amp; APIs</strong> , the <strong>Group ID</strong> text field doesn't support autocomplete or provide validation for Workforce Identity Federation users.</li>
<li>Workforce Identity Federation groups are identified by their IDs rather than their names.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="customer-experience-insights" data-text="Customer Experience Insights" tabindex="-1"><a href="https://docs.cloud.google.com/contact-center/insights/docs">Customer Experience Insights</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="data-catalog" data-text="Data Catalog" tabindex="-1"><a href="https://docs.cloud.google.com/data-catalog/docs">Data Catalog</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>In the edit <a href="https://docs.cloud.google.com/data-catalog/docs/concepts/metadata#types_of_business_metadata">steward</a> dialog on the entry details page, contact suggestions aren't shown.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="database-migration-service" data-text="Database Migration Service" tabindex="-1"><a href="https://docs.cloud.google.com/database-migration/docs">Database Migration Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="dataflow" data-text="Dataflow" tabindex="-1"><a href="https://docs.cloud.google.com/dataflow/docs">Dataflow</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="dataform" data-text="Dataform" tabindex="-1"><a href="https://docs.cloud.google.com/dataform/docs">Dataform</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="knowledge-catalog" data-text="Knowledge Catalog" tabindex="-1"><a href="https://docs.cloud.google.com/dataplex/docs">Knowledge Catalog</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/dataplex/docs/explore-data">Dataplex Explore workbench</a> doesn't support Workforce Identity Federation.</li>
<li><a href="https://docs.cloud.google.com/dataplex/docs/schedule-queries-notebooks">Scheduled scripts and notebooks through explore workbench</a> don't support Workforce Identity Federation.</li>
<li><a href="https://docs.cloud.google.com/dataplex/docs/lake-security#secure-view">Secure view</a> doesn't support Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="managed-service-for-apache-spark" data-text="Managed Service for Apache Spark" tabindex="-1"><a href="https://docs.cloud.google.com/dataproc/docs">Managed Service for Apache Spark</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Workforce Identity Federation users can perform create, view, update, and delete operations in Cluster, Jobs, and Batches list pages. Workflows, Autoscaling policies, and component exchange aren't available to Workforce Identity Federation.</li>
<li>Cluster create functionality is available, except for Managed Service for Apache Spark on GKE cluster creation, Managed Service for Apache Spark Compute Engine cluster with personal authentication, or with Component Gateway enabled.</li>
<li>The <strong>Output <strong>section in the Batch and Job detail page isn't available for Workforce Identity Federation users.</strong></strong></li>
<li>The <strong>Recommend Alert</strong> section in the Cluster and Job list page isn't available for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The following methods don't support identity federation:
<ul>
<li><a href="https://docs.cloud.google.com/dataproc/docs/guides/dpgke/dataproc-gke-overview">Dataproc on GKE</a></li>
<li><a href="https://docs.cloud.google.com/dataproc/docs/concepts/iam/personal-auth">Managed Service for Apache Spark Personal Cluster Authentication</a></li>
<li><a href="https://docs.cloud.google.com/dataproc/docs/concepts/iam/sa-multi-tenancy">Managed Service for Apache Spark Service Account based Secure Multi-tenancy</a></li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="dataproc-metastore" data-text="Dataproc Metastore" tabindex="-1"><a href="https://docs.cloud.google.com/dataproc-metastore/docs">Dataproc Metastore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="datastore" data-text="Datastore" tabindex="-1"><a href="https://docs.cloud.google.com/datastore/docs">Datastore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="datastream" data-text="Datastream" tabindex="-1"><a href="https://docs.cloud.google.com/datastream/docs">Datastream</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="dialogflow" data-text="Dialogflow" tabindex="-1"><a href="https://docs.cloud.google.com/dialogflow/docs">Dialogflow</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Dialogflow ES is not supported in the Google Cloud console for Workforce Identity Federation users.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Workforce Identity Federation is supported only on Dialogflow CX APIs.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="document-ai" data-text="Document AI" tabindex="-1"><a href="https://docs.cloud.google.com/document-ai/docs">Document AI</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="endpoint-verification" data-text="Endpoint Verification" tabindex="-1"><a href="https://docs.cloud.google.com/endpoint-verification/docs">Endpoint Verification</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="enterprise-knowledge-graph" data-text="Enterprise Knowledge Graph" tabindex="-1"><a href="https://docs.cloud.google.com/enterprise-knowledge-graph/docs/overview">Enterprise Knowledge Graph</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="error-reporting" data-text="Error Reporting" tabindex="-1"><a href="https://docs.cloud.google.com/error-reporting/docs">Error Reporting</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="eventarc" data-text="Eventarc" tabindex="-1"><a href="https://docs.cloud.google.com/eventarc/docs">Eventarc</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/eventarc/docs/third-parties/third-parties-overview">Third-party event publishing</a> using a <code dir="ltr" translate="no">ChannelConnection</code> resource isn't supported for identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="filestore" data-text="Filestore" tabindex="-1"><a href="https://docs.cloud.google.com/filestore/docs">Filestore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="firestore" data-text="Firestore" tabindex="-1"><a href="https://docs.cloud.google.com/firestore/docs">Firestore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><a href="https://docs.cloud.google.com/firestore/docs/security/get-started">Security Rules</a> don't support Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="gemini" data-text="Gemini" tabindex="-1"><a href="https://docs.cloud.google.com/duet-ai/docs">Gemini</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Gemini for Google Cloud <a href="https://docs.cloud.google.com/gemini/docs/manage-licenses">license management</a> doesn't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="google-cloud-armor" data-text="Google Cloud Armor" tabindex="-1"><a href="https://docs.cloud.google.com/armor/docs">Google Cloud Armor</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="google-cloud-contact-center-as-a-service" data-text="Google Cloud Contact Center as a Service" tabindex="-1"><a href="https://docs.cloud.google.com/contact-center/ccai-platform/docs">Google Cloud Contact Center as a Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Google Cloud CCaaS cannot be set up by a Workforce Identity Federation user through the Google Cloud CCaaS console.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>To set up Google Cloud CCaaS through the gcloud CLI, <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation">Workforce Identity Federation</a> users must contact Customer Care.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="google-cloud-managed-service-for-apache-kafka" data-text="Google Cloud Managed Service for Apache Kafka" tabindex="-1"><a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs">Google Cloud Managed Service for Apache Kafka</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><a href="https://docs.cloud.google.com/kubernetes-engine/docs/concepts/workload-identity">Workload Identity Federation for GKE</a> is supported for authentication to the <a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs/authentication-kafka">open source Apache Kafka APIs</a> . However, it is not supported for clients using <a href="https://docs.cloud.google.com/kubernetes-engine/fleet-management/docs/use-workload-identity">Fleet Workload Identity Federation for GKE</a> . As an alternative, <a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/workload-identity#kubernetes-sa-to-iam">link Kubernetes ServiceAccounts to IAM</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="google-cloud-marketplace" data-text="Google Cloud Marketplace" tabindex="-1"><a href="https://docs.cloud.google.com/marketplace/docs">Google Cloud Marketplace</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Cloud Marketplace contains links to Google domains that might not support Workforce Identity Federation.</li>
<li>The <strong>Launch</strong> button is disabled for all VM products that use Deployment Manager because Deployment Manager doesn't support Workforce Identity Federation.</li>
<li>SaaS sign-up and SSO login don't support Workforce Identity Federation.</li>
<li>Producer Portal doesn't support Workforce Identity Federation.</li>
<li><a href="https://docs.cloud.google.com/marketplace/docs/governance/requesting-procurement">Request Procurement</a> doesn't support Workforce Identity Federation.</li>
<li>Service Catalog doesn't support Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/marketplace/docs/partners/commerce-procurement-api/reference">Partner API</a> doesn't support Workforce Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Customers don't receive notifications if no email address is provided by Billing Account Admins or Product Owners.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="google-cloud-migration-center" data-text="Google Cloud Migration Center" tabindex="-1"><a href="https://docs.cloud.google.com/migration-center/docs">Google Cloud Migration Center</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/migration-center/docs/generate-tco-report#export_your_tco_report">Exporting Total Cost of Ownership Reports (TCO Reports)</a> isn't supported for Workforce Identity Federation users.</li>
<li><a href="https://docs.cloud.google.com/migration-center/docs/view-assets#export_assets_data">Exporting assets</a> isn't supported for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="google-cloud-netapp-volumes" data-text="Google Cloud NetApp Volumes" tabindex="-1"><a href="https://docs.cloud.google.com/netapp/volumes/docs/discover/overview/">Google Cloud NetApp Volumes</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="google-cloud-sdk" data-text="Google Cloud SDK" tabindex="-1"><a href="https://docs.cloud.google.com/sdk/docs">Google Cloud SDK</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="google-earth-engine" data-text="Google Earth Engine" tabindex="-1"><a href="https://cloud.google.com/earth-engine">Google Earth Engine</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Earth Engine Code Editor doesn't support Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Exporting data to Google Drive from Earth Engine APIs isn't supported for Workforce Identity Federation.</li>
<li>Legacy Earth Engine assets that aren't managed by Google Cloud projects aren't supported for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>The BigQuery function <a href="https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_regionstats"><code dir="ltr" translate="no">ST_REGIONSTATS</code></a> for raster data doesn't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="google-kubernetes-engine" data-text="Google Kubernetes Engine" tabindex="-1"><a href="https://docs.cloud.google.com/kubernetes-engine/docs">Google Kubernetes Engine</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>When you log in to any attached cluster, GKE on AWS cluster, GKE on Azure cluster, or GDC software-only for bare metal cluster, the option <strong>Use your Google identity</strong> isn't available for Workforce Identity Federation.</li>
<li>When you create or attach any attached cluster, GKE on AWS cluster, GKE on Azure cluster, or GDC software-only for bare metal cluster, you won't automatically be added as an administrator for Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>If you use Workload Identity Federation for GKE to programmatically run <code dir="ltr" translate="no">kubectl</code> commands against a different GKE cluster from a Pod, you must use service account impersonation, as described in <a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/workload-identity#kubernetes-sa-to-iam">Alternative: link Kubernetes ServiceAccounts to IAM</a> . This limitation doesn't apply if you use your own workload identity pool with Workload Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><code dir="ltr" translate="no">gkeadm</code> , <code dir="ltr" translate="no">gkectl</code> and <code dir="ltr" translate="no">bmctl</code> don't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="google-security-operations" data-text="Google Security Operations" tabindex="-1"><a href="https://docs.cloud.google.com/chronicle">Google Security Operations</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="hybrid-connectivity" data-text="Hybrid Connectivity" tabindex="-1"><a href="https://docs.cloud.google.com/hybrid-connectivity">Hybrid Connectivity</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="identity-and-access-management" data-text="Identity and Access Management" tabindex="-1"><a href="https://docs.cloud.google.com/iam/docs">Identity and Access Management</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>The <strong>Name</strong> column within the IAM table doesn't show display names for Google identities.</li>
<li>When adding new principals to allow policies, the <strong>Add principals</strong> text field supports only autocompletion for service accounts.</li>
<li>The <strong>Add exempted principal</strong> text field in the <strong>Audit Logs</strong> page supports only autocompletion for service accounts.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="identity-aware-proxy" data-text="Identity-Aware Proxy" tabindex="-1"><a href="https://docs.cloud.google.com/iap/docs">Identity-Aware Proxy</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>In the Applications tab, the <strong>Method</strong> column is disabled, and users cannot use external identities for authorization.</li>
<li>In the Applications tab, App Engine resources cannot be listed.</li>
<li>The <strong>Go to OAuth configuration</strong> item in the <em>more_vert</em> action menu isn't available.</li>
<li>In the <strong>Applications</strong> tab, on-premises connectors cannot be added or listed.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The IAP API doesn't support TCP forwarding for Workforce Identity Federation users. You must instead use console (federated) or the gcloud CLI for TCP forwarding.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="identity-platform" data-text="Identity Platform" tabindex="-1"><a href="https://docs.cloud.google.com/identity-platform/docs">Identity Platform</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Enabling Identity Platform through the Google Cloud Workforce Identity Federation console is not supported. Workforce Identity Federation administrators must enable Identity Platform either through the Firebase Authentication console or by logging into the Google Cloud console using a Cloud Identity or Workspace account before Workforce Identity Federation users can access Identity Platform through the console (federated).</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/identity-platform/docs/reference/rpc/google.cloud.identitytoolkit.admin.v2#google.cloud.identitytoolkit.admin.v2.ProjectConfigService.InitializeIdentityPlatform"><code dir="ltr" translate="no">InitializeIdentityPlatform</code></a> doesn't support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="integration-connectors" data-text="Integration Connectors" tabindex="-1"><a href="https://docs.cloud.google.com/integration-connectors/docs">Integration Connectors</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="key-access-justifications" data-text="Key Access Justifications" tabindex="-1"><a href="https://docs.cloud.google.com/assured-workloads/key-access-justifications/docs">Key Access Justifications</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="knative-serving" data-text="Knative serving" tabindex="-1"><a href="https://docs.cloud.google.com/anthos/run/docs">Knative serving</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/anthos/run/docs/continuous-deployment-with-cloud-build">Continuous deployment with Cloud Build</a> doesn't support Workforce Identity Federation.</li>
<li><a href="https://docs.cloud.google.com/anthos/run/docs/mapping-custom-domains#register-domain">Registering a domain with Cloud Domains</a> doesn't support Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>When using Workforce Identity Federation, Knative serving requires a cluster with managed Cloud Service Mesh.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="live-stream-api" data-text="Live Stream API" tabindex="-1"><a href="https://docs.cloud.google.com/livestream/docs">Live Stream API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="looker-google-cloud-core" data-text="Looker (Google Cloud core)" tabindex="-1"><a href="https://docs.cloud.google.com/looker/docs">Looker (Google Cloud core)</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="data-studio" data-text="Data Studio" tabindex="-1"><a href="https://docs.cloud.google.com/looker/docs/studio">Data Studio</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="managed-service-for-microsoft-active-directory" data-text="Managed Service for Microsoft Active Directory" tabindex="-1"><a href="https://docs.cloud.google.com/managed-microsoft-ad/docs">Managed Service for Microsoft Active Directory</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Workforce Identity Federation users can't use <a href="https://docs.cloud.google.com/iap/docs/tcp-forwarding-overview">IAP TCP forwarding</a> to access the <a href="https://docs.cloud.google.com/managed-microsoft-ad/docs/part-1-deploy-active-directory#creating_a_management_vm">Active Directory management VM</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="media-cdn" data-text="Media CDN" tabindex="-1"><a href="https://docs.cloud.google.com/media-cdn/docs">Media CDN</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="memorystore" data-text="Memorystore" tabindex="-1"><a href="https://docs.cloud.google.com/memorystore/docs/redis/">Memorystore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The following APIs support identity federation:
<ul>
<li><a href="https://docs.cloud.google.com/memorystore/docs/redis">Memorystore for Redis</a></li>
<li><a href="https://docs.cloud.google.com/memorystore/docs/cluster">Memorystore for Redis Cluster</a></li>
<li><a href="https://docs.cloud.google.com/memorystore/docs/memcached">Memorystore for Memcached</a></li>
<li><a href="https://docs.cloud.google.com/memorystore/docs/valkey">Memorystore for Valkey</a></li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="migrate-to-containers" data-text="Migrate to Containers" tabindex="-1"><a href="https://docs.cloud.google.com/migrate/containers/docs">Migrate to Containers</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="migrate-to-virtual-machines" data-text="Migrate to Virtual Machines" tabindex="-1"><a href="https://docs.cloud.google.com/migrate/virtual-machines/docs">Migrate to Virtual Machines</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="network-connectivity-center" data-text="Network Connectivity Center" tabindex="-1"><a href="https://docs.cloud.google.com/network-connectivity/docs/network-connectivity-center">Network Connectivity Center</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="network-intelligence-center" data-text="Network Intelligence Center" tabindex="-1"><a href="https://docs.cloud.google.com/network-intelligence-center">Network Intelligence Center</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Firewall Insights cannot be exported to JSON or CSV.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="network-service-tiers" data-text="Network Service Tiers" tabindex="-1"><a href="https://docs.cloud.google.com/network-tiers/docs">Network Service Tiers</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="organization-policy-service" data-text="Organization Policy Service" tabindex="-1"><a href="https://docs.cloud.google.com/resource-manager/docs/organization-policy/overview/">Organization Policy Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="parallelstore" data-text="Parallelstore" tabindex="-1"><a href="https://docs.cloud.google.com/parallelstore/docs/overview/">Parallelstore</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="personalized-service-health" data-text="Personalized Service Health" tabindex="-1"><a href="https://docs.cloud.google.com/service-health/docs/overview/">Personalized Service Health</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="policy-intelligence" data-text="Policy Intelligence" tabindex="-1"><a href="https://docs.cloud.google.com/policy-intelligence/docs">Policy Intelligence</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><p>The following Policy Intelligence features have limitations for Workforce Identity Federation users who use the Google Cloud Workforce Identity Federation console:</p>
<ul>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/troubleshoot-access">Policy Troubleshooter</a> : Workforce Identity Federation users can't troubleshoot access in the console (federated).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/policy-analyzer-overview">Policy Analyzer</a> : Workforce Identity Federation users can't analyze access in the console (federated).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview">Policy Simulator</a> : Workforce Identity Federation users can't simulate changes to an allow policy within the console (federated).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview">IAM Recommender</a> : Workforce Identity Federation users can't view recommendations in the console (federated).</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><p>The following Policy Intelligence features have API limitations for federated identities:</p>
<ul>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/troubleshoot-access">Policy Troubleshooter</a> : Federated identities can't check the membership of Google groups in allow and deny policies, or the membership of Cloud Identity accounts (domains) in deny policies. When federated identities call the <code dir="ltr" translate="no">iam.troubleshoot</code> method, role bindings and deny rules that contain groups or domains have an access result of <strong>Unknown</strong> , unless the role binding or deny rule also explicitly includes the principal.</li>
<li><p><a href="https://docs.cloud.google.com/policy-intelligence/docs/policy-analyzer-overview">Policy Analyzer</a> : When calling the <a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeIamPolicy"><code dir="ltr" translate="no">analyzeIamPolicy</code></a> or the <a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeIamPolicyLongrunning"><code dir="ltr" translate="no">analyzeIamPolicyLongrunning</code></a> method, federated identities might receive incomplete analysis results because of the following:</p>
<ul>
<li>Federated identities can't check the membership of Google groups in allow policies. As a result, when federated identities analyze access for a principal, the query results don't include permissions and roles that the principal has due to their membership in a group.</li>
<li>When analyzing access, federated identities can't enable the <code dir="ltr" translate="no">expand-groups</code> option.</li>
</ul>
<p>Federated identities can't use the following API methods:</p>
<ul>
<li><a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeMove"><code dir="ltr" translate="no">analyzeMove</code></a></li>
</ul></li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview">Policy Simulator</a> : Federated identities can't use the Policy Simulator API ( <code dir="ltr" translate="no">policysimulator.googleapis.com</code> ).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/activity-analyzer-service-account-authentication">Activity Analyzer</a> : Federated identities can't use the Policy Analyzer API ( <code dir="ltr" translate="no">policyanalyzer.googleapis.com</code> ).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview">IAM Recommender</a> : Federated identities can't use the Recommender API ( <code dir="ltr" translate="no">recommender.googleapis.com</code> ).</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="private-service-connect" data-text="Private Service Connect" tabindex="-1"><a href="https://docs.cloud.google.com/vpc/docs/private-service-connect">Private Service Connect</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>When publishing a service, DNS configuration is not available.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="privileged-access-manager" data-text="Privileged Access Manager" tabindex="-1"><a href="https://docs.cloud.google.com/iam/docs/pam-overview/">Privileged Access Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>In the <strong>Entitlements</strong> section, when you type requester and approver principals, only service account names are autocompleted.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Automated <a href="https://docs.cloud.google.com/iam/docs/pam-overview#email-notifications">email notifications</a> aren't sent for entitlement and grant changes. For notifications to be sent, administrators or requesters can explicitly configure email addresses.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="pubsub" data-text="Pub/Sub" tabindex="-1"><a href="https://docs.cloud.google.com/pubsub/docs">Pub/Sub</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/pubsub/lite/docs">Pub/Sub Lite API</a> doesn't have endpoints that support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="recaptcha" data-text="reCAPTCHA" tabindex="-1"><a href="https://docs.cloud.google.com/recaptcha/docs">reCAPTCHA</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Multi-factor authentication through email cannot be configured by Workforce Identity Federation users. For assistance, <a href="https://go.chronicle.security/recaptchaupgrade">contact sales</a> .</li>
<li>The demonstration website in Cloud Shell isn't supported for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/recaptcha/docs/reference/rpc/google.cloud.recaptchaenterprise.v1#google.cloud.recaptchaenterprise.v1.RecaptchaEnterpriseService.MigrateKey"><code dir="ltr" translate="no">MigrateKey</code></a> isn't supported for federated identities.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="recommender" data-text="Recommender" tabindex="-1"><a href="https://docs.cloud.google.com/recommender/docs">Recommender</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><a href="https://docs.cloud.google.com/recommender/docs/bq-export/export-recommendations-to-bq">Exporting recommendations to BigQuery</a> isn't supported by Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="resource-manager" data-text="Resource Manager" tabindex="-1"><a href="https://docs.cloud.google.com/resource-manager/docs">Resource Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li>Workforce Identity Federation users can only view and operate on the organization for which Workforce Identity Federation was configured. Other organizations to which the users are added are not displayed in the Google Cloud console.</li>
<li>Wait times for certain operations to be reflected in the UI are long—for example, creating a project or folder.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The <a href="https://docs.cloud.google.com/resource-manager/reference/rest/v1beta1/organizations">Organizations API</a> doesn't support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="ai-commerce-search-api" data-text="AI Commerce Search API" tabindex="-1"><a href="https://docs.cloud.google.com/retail/docs">AI Commerce Search API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/retail/docs/user-events">User events information</a> is hidden for Workforce Identity Federation users.</li>
<li><a href="https://docs.cloud.google.com/retail/docs/upload-catalog#mc-ret">Merchant Center accounts</a> are not supported for workforce federation users.</li>
<li><a href="https://docs.cloud.google.com/retail/docs/configs">Serving configs</a> analytics and usage count are hidden for Workforce Identity Federation users.</li>
<li><a href="https://docs.cloud.google.com/retail/docs/create-models#import-reqs">Model data requirements</a> are hidden for Workforce Identity Federation users.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>The following methods don't support identity federtation:
<ul>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.CatalogService.UpdateCatalog">UpdateCatalog</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.CompletionService.ImportCompletionData">ImportCompletionData</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ModelService.TuneModel">TuneModel</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ProductService.ImportProducts">ImportProducts</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ProductService.PurgeProducts">PurgeProducts</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.UserEventService.ImportUserEvents">ImportUserEvents</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.UserEventService.ImportUserEvents">ImportUserEvents</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.UserEventService.PurgeUserEvents">PurgeUserEvents</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.UserEventService.RejoinUserEvents">RejoinUserEvents</a></li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="secret-manager" data-text="Secret Manager" tabindex="-1"><a href="https://docs.cloud.google.com/secret-manager/docs">Secret Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="secure-source-manager" data-text="Secure Source Manager" tabindex="-1"><a href="https://docs.cloud.google.com/secure-source-manager/docs">Secure Source Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Identity federation users must sign in through the Secure Source Manager instance <a href="https://docs.cloud.google.com/secure-source-manager/docs/create-instance-federated-identities#access-instance">web interface</a> before running any of the following commands:
<ul>
<li>Git CLI commands</li>
<li>API calls to <a href="https://docs.cloud.google.com/secure-source-manager/docs/reference/rest#service-endpoint">data plane endpoints</a></li>
</ul></li>
<li>Identity federation users must sign in through the Secure Source Manager instance <a href="https://docs.cloud.google.com/secure-source-manager/docs/create-instance-federated-identities#access-instance">web interface</a> after every session expiry to continue using Git SSH CLI commands with user SSH keys.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><ul>
<li>A new Secure Source Manager instance must be created to use Workforce Identity Federation. Existing instances can't be updated.</li>
<li>Workforce identity pool providers used for Secure Source Manager must provide <code dir="ltr" translate="no">google.subject</code> and <code dir="ltr" translate="no">google.email</code> attribute mappings.</li>
<li>You can only use your federated identity to log in to a Secure Source Manager instance that is configured to use Workforce Identity Federation.</li>
<li>Email notifications from Secure Source Manager are not supported for Workforce Identity Federation configured instances.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="security-command-center" data-text="Security Command Center" tabindex="-1"><a href="https://docs.cloud.google.com/security-command-center/docs">Security Command Center</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>The following features are unavailable for Workforce Identity Federation users:
<ul>
<li>The Security posture service cannot be managed using Google Cloud console.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="sensitive-data-protection" data-text="Sensitive Data Protection" tabindex="-1"><a href="https://docs.cloud.google.com/dlp/docs">Sensitive Data Protection</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="serverless-vpc-access" data-text="Serverless VPC Access" tabindex="-1"><a href="https://docs.cloud.google.com/vpc/docs/serverless-vpc-access/">Serverless VPC Access</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="service-directory" data-text="Service Directory" tabindex="-1"><a href="https://docs.cloud.google.com/service-directory/docs">Service Directory</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="service-infrastructure" data-text="Service Infrastructure" tabindex="-1"><a href="https://docs.cloud.google.com/service-infrastructure/docs">Service Infrastructure</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Managing quota in <a href="https://docs.cloud.google.com/endpoints">Cloud Endpoints</a> is not supported.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/service-infrastructure/docs/service-management/getting-started">Service Management API</a> : Creating a managed service doesn't support identity federation. To verify domain ownership and create a managed service, do the following:
<ol>
<li><a href="https://docs.cloud.google.com/iam/docs/service-accounts-create">Add a service account</a> to domain owners using <a href="https://developers.google.com/site-verification">Site Verification API</a> .</li>
<li><a href="https://docs.cloud.google.com/sdk/gcloud/reference/auth/activate-service-account">Impersonate this service account</a> to create a managed service.</li>
</ol></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="spanner" data-text="Spanner" tabindex="-1"><a href="https://docs.cloud.google.com/spanner/docs">Spanner</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="speech-to-text" data-text="Speech-to-Text" tabindex="-1"><a href="https://docs.cloud.google.com/speech-to-text/docs">Speech-to-Text</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Only the v2 UI pages support Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Only the v2 API supports identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="storage-transfer-service" data-text="Storage Transfer Service" tabindex="-1"><a href="https://docs.cloud.google.com/storage-transfer/docs/">Storage Transfer Service</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="text-to-speech" data-text="Text-to-Speech" tabindex="-1"><a href="https://docs.cloud.google.com/text-to-speech/docs">Text-to-Speech</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="transcoder-api" data-text="Transcoder API" tabindex="-1"><a href="https://docs.cloud.google.com/transcoder/docs">Transcoder API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="transfer-appliance" data-text="Transfer Appliance" tabindex="-1"><a href="https://docs.cloud.google.com/transfer-appliance/docs/4.0/overview/">Transfer Appliance</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="translation-hub" data-text="Translation Hub" tabindex="-1"><a href="https://docs.cloud.google.com/translation-hub/docs">Translation Hub</a></h3></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>No alternatives available</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="vertex-ai" data-text="Vertex AI" tabindex="-1"><a href="https://docs.cloud.google.com/vertex-ai/docs">Vertex AI</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>When Workforce Identity Federation users create a new model monitoring job, Vertex AI doesn't prefill the alert email input with their email address.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Vertex AI doesn't send email messages to Workforce Identity Federation users.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Colab Enterprise doesn't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="vertex-ai-agent-builder" data-text="Vertex AI Agent Builder" tabindex="-1"><a href="https://docs.cloud.google.com/agent-builder/overview">Vertex AI Agent Builder</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/generative-ai-app-builder/docs/introduction#agent">Vertex AI agents</a> creation and preview aren't supported.</li>
<li><a href="https://docs.cloud.google.com/generative-ai-app-builder/docs/create-data-store-es#google-drive">Google Drive data store</a> creation isn't supported.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="vertex-ai-vision" data-text="Vertex AI Vision" tabindex="-1"><a href="https://docs.cloud.google.com/vision-ai/docs">Vertex AI Vision</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Video stream playback doesn't work for Workforce Identity Federation users.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="vertex-ai-workbench" data-text="Vertex AI Workbench" tabindex="-1"><a href="https://docs.cloud.google.com/vertex-ai/docs/workbench/notebook-solution">Vertex AI Workbench</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/vertex-ai/docs/workbench/managed/introduction">Vertex AI Workbench managed notebooks</a> ( <a href="https://docs.cloud.google.com/vertex-ai/docs/deprecations">Deprecated</a> ) doesn't support Workforce Identity Federation.</li>
<li><a href="https://docs.cloud.google.com/vertex-ai/docs/workbench/user-managed/introduction">Vertex AI Workbench user-managed notebooks</a> ( <a href="https://docs.cloud.google.com/vertex-ai/docs/deprecations">Deprecated</a> ) doesn't support Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="video-intelligence-api" data-text="Video Intelligence API" tabindex="-1"><a href="https://docs.cloud.google.com/video-intelligence/docs">Video Intelligence API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="video-stitcher-api" data-text="Video Stitcher API" tabindex="-1"><a href="https://docs.cloud.google.com/video-stitcher/docs">Video Stitcher API</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>Identity federation is not supported for LiveConfig and Slate resources when Google Ad Manager (GAM) fields are set.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="virtual-private-cloud" data-text="Virtual Private Cloud" tabindex="-1"><a href="https://docs.cloud.google.com/vpc/docs">Virtual Private Cloud</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="vpc-service-controls" data-text="VPC Service Controls" tabindex="-1"><a href="https://docs.cloud.google.com/vpc-service-controls/docs">VPC Service Controls</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Autocomplete suggestions aren't supported when adding user identities in the following fields:
<ul>
<li><a href="https://docs.cloud.google.com/access-context-manager/docs/overview#access-policies">Access policies</a></li>
<li><a href="https://docs.cloud.google.com/vpc-service-controls/docs/ingress-egress-rules">Ingress and egress rules</a> in service perimeters</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li><a href="https://docs.cloud.google.com/access-context-manager/docs/reference/rpc/google.identity.accesscontextmanager.v1alpha"><code dir="ltr" translate="no">v1alpha</code> APIs</a> aren't available to federated identities.</li>
<li>VPC Service Controls supports only specific <a href="https://docs.cloud.google.com/vpc-service-controls/docs/supported-identities">Workforce Identity Federation and Workload Identity Federation principal identifiers</a> . You can use these principal identifiers to <a href="https://docs.cloud.google.com/vpc-service-controls/docs/configure-identity-groups">configure identity groups and third-party identities in ingress and egress rules</a> .</li>
</ul></td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="web-risk" data-text="Web Risk" tabindex="-1"><a href="https://docs.cloud.google.com/web-risk/docs">Web Risk</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><h3 id="workflows" data-text="Workflows" tabindex="-1"><a href="https://docs.cloud.google.com/workflows/docs">Workflows</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>The automated grant feature, which grants the Workforce Identity Federation user the Service Account User ( <code dir="ltr" translate="no">roles/iam.serviceAccountUser</code> ) role on the project, is inactive. To grant the role to Workforce Identity Federation users, you must go to the IAM page and specify a Workforce Identity Federation <a href="https://docs.cloud.google.com/iam/docs/principal-identifiers">principal identifier</a> or contact the project owner to do so.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><h3 id="workload-manager" data-text="Workload Manager" tabindex="-1"><a href="https://docs.cloud.google.com/workload-manager/docs">Workload Manager</a></h3></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>
