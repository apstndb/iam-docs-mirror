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

- **Product:** The product name.
- **Identity federation launch stage:** Refers to the [launch stage](https://cloud.google.com/products/#product-launch-stages) of the product's support for identity federation. Launch stage doesn't refer to the launch stage of the product itself.
- **Columns that describe supported products:**
  - **Google Cloud API:** The product's identity federation-related limitations that are associated with API methods and the gcloud CLI commands that access those methods.
  - **Console (federated):** The product's Workforce Identity Federation-related console (federated) UI limitations.
  - **Other:** The product's identity federation-related limitations that aren't Google Cloud API or console (federated) limitations.
- **Columns that describe unsupported products:**
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
<td><a href="https://docs.cloud.google.com/assured-workloads/access-approval/docs">Access Approval</a></td>
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
<td><a href="https://docs.cloud.google.com/access-context-manager/docs">Access Context Manager</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/access-context-manager/docs/reference/rpc/google.identity.accesscontextmanager.v1alpha"><code>v1alpha</code> APIs</a> aren't available for federated identities.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/assured-workloads/access-transparency/docs">Access Transparency</a></td>
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
<td><a href="https://docs.cloud.google.com/agent-assist/docs">Agent Assist</a></td>
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
<td><a href="https://docs.cloud.google.com/agent-registry/overview">Agent Registry</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">Preview</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>During Preview, certain Agent Platform Governance and Agent Gateway console pages have limited support for Workforce Identity Federation sessions.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>During Preview, certain API and CLI operations, such as importing Agent Gateway resources, return internal errors when called with Workforce Identity Federation credentials. Use a standard Google Account (Cloud Identity or Google Workspace) instead.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/alloydb/docs">AlloyDB for PostgreSQL</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/financial-services/anti-money-laundering/docs/">Anti Money Laundering AI</a></td>
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
<td><a href="https://docs.cloud.google.com/api-gateway/docs">API Gateway</a></td>
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
<td><a href="https://docs.cloud.google.com/apigee/docs">Apigee</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/apigee/docs/apihub/what-is-api-hub/">Apigee API hub</a></td>
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
<td><a href="https://docs.cloud.google.com/apis/docs">APIs and Services</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/appengine/docs">App Engine</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/app-hub/docs">App Hub</a></td>
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
<td><a href="https://docs.cloud.google.com/application-integration/docs">Application Integration</a></td>
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
<td><a href="https://docs.cloud.google.com/artifact-registry/docs">Artifact Registry</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/assured-workloads/docs">Assured Workloads</a></td>
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
<td><a href="https://docs.cloud.google.com/backup-disaster-recovery/docs">Backup and DR Service</a></td>
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
<td><a href="https://docs.cloud.google.com/batch/docs">Batch</a></td>
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
<td><a href="https://docs.cloud.google.com/bigquery/docs">BigQuery</a></td>
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
<li><a href="https://docs.cloud.google.com/bigquery/docs/write-sql-gemini#generate_a_sql_query">SQL generation with Gemini</a></li>
<li><a href="https://docs.cloud.google.com/bigquery/docs/write-sql-gemini#generate_python_code">Python code generation with Gemini</a></li>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/bigtable/docs">Bigtable</a></td>
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
<td><a href="https://docs.cloud.google.com/binary-authorization/docs">Binary Authorization</a></td>
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
<td><a href="https://docs.cloud.google.com/blockchain-analytics/docs/overview">Blockchain Analytics</a></td>
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
<td><a href="https://docs.cloud.google.com/blockchain-node-engine/docs">Blockchain Node Engine</a></td>
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
<td><a href="https://docs.cloud.google.com/carbon-footprint/docs">Carbon Footprint</a></td>
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
<td><a href="https://docs.cloud.google.com/certificate-authority-service/docs">Certificate Authority Service</a></td>
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
<td><a href="https://docs.cloud.google.com/certificate-manager/docs">Certificate Manager</a></td>
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
<td><a href="https://docs.cloud.google.com/channel/docs">Channel Services</a></td>
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
<td><a href="https://docs.cloud.google.com/asset-inventory/docs">Cloud Asset Inventory</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>In the <strong>IAM policy</strong> tab, the <strong>Analyze Full Access</strong> button is unavailable for Workforce Identity Federation users.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeMove"><code>analyzeMove</code></a> isn't supported by identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/billing/docs">Cloud Billing</a></td>
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
<li>Workforce Identity Federation users must manage billing using the <a href="https://console.cloud.google/">console (federated)</a> Billing pages or <a href="https://payments.cloud.google/">Google Payments center (federated)</a> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/build/docs">Cloud Build</a></td>
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
<td><a href="https://docs.cloud.google.com/cdn/docs">Cloud CDN</a></td>
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
<td><a href="https://docs.cloud.google.com/code/docs">Cloud Code</a></td>
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
<td><a href="https://docs.cloud.google.com/composer/docs">Managed Service for Apache Airflow</a></td>
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
<li>Email messages sent from Airflow only include the Airflow UI link that is accessible by Google accounts. To access Airflow UI as a Workforce Identity Federation user, the link must be manually updated (changed to the <a href="https://docs.cloud.google.com/composer/docs/composer-2/access-environments-with-workforce-identity-federation#access-airflow-ui">URL for Workforce Identity Federation</a> ).</li>
<li>Third-party identifiers in VPC Service Controls ingress and egress rules aren't supported.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://cloud.google.com/cloud-console">Cloud Console</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Workforce Identity Federation users can only access the <a href="https://console.cloud.google/">Google Cloud Workforce Identity Federation console, also known as the console (federated)</a> . They can't access the Google Cloud console. The console (federated) provides limited access to only those Google Cloud products that support Workforce Identity Federation. For more information, see <a href="https://docs.cloud.google.com/iam/docs/workforce-console-learn-more">About the console (federated)</a> . The console (federated) has the following limitations:
<ul>
<li>Language preference is selected at sign-in and can't be updated within the console (federated).</li>
<li>Product notifications, updates, and offers can't be enabled on the <a href="https://docs.cloud.google.com/resource-manager/docs/managing-notifications#manage-preferences">communication preferences</a> page.</li>
<li>Personalization based on your Google Cloud console activity isn't supported.</li>
<li>The <a href="https://docs.cloud.google.com/recommender/docs/opting-out">Transparency and Control Center</a> page isn't available.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>No known limitations</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>Workforce Identity Federation users aren't eligible for the Google Cloud Free Trial.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/support/docs">Cloud Customer Care</a></td>
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
<li>When creating <strong>billing support</strong> cases, users might be required to re-verify their email address. Contact details (for example, email addresses) cannot be changed for Workforce Identity Federation users after interaction with the support team has started.</li>
<li>The Premium Support Event Management Service is unavailable to Workforce Identity Federation users.</li>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/data-fusion/docs">Cloud Data Fusion</a></td>
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
<td><a href="https://docs.cloud.google.com/deploy/docs">Cloud Deploy</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/deployment-manager/docs">Cloud Deployment Manager</a></td>
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
<td><a href="https://docs.cloud.google.com/dns/docs">Cloud DNS</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/domains/docs">Cloud Domains</a></td>
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
<td><a href="https://docs.cloud.google.com/endpoints/docs">Cloud Endpoints</a></td>
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
<td><a href="https://cloud.google.com/ai">Cloud Fleet Routing</a></td>
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
<td><a href="https://docs.cloud.google.com/healthcare-api/docs">Cloud Healthcare API</a></td>
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
<td><a href="https://docs.cloud.google.com/kms/docs/hsm">Cloud HSM</a></td>
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
<td><a href="https://docs.cloud.google.com/intrusion-detection-system/docs/">Cloud Intrusion Detection System</a></td>
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
<td><a href="https://docs.cloud.google.com/kms/docs">Cloud Key Management Service</a></td>
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
<td><a href="https://docs.cloud.google.com/load-balancing/docs">Cloud Load Balancing</a></td>
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
<td><a href="https://docs.cloud.google.com/logging/docs">Cloud Logging</a></td>
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
<td><a href="https://cloud.google.com/app">Cloud Mobile App</a></td>
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
<td><a href="https://docs.cloud.google.com/monitoring/docs">Cloud Monitoring</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/nat/docs">Cloud NAT</a></td>
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
<td><a href="https://docs.cloud.google.com/firewall/docs">Cloud Next Generation Firewall</a></td>
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
<td><a href="https://docs.cloud.google.com/profiler/docs/about-profiler/">Cloud Profiler</a></td>
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
<td><a href="https://docs.cloud.google.com/run/docs">Cloud Run</a></td>
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
<li>The IAM permission <code>run.routes.invoke</code> , which can manage access to Cloud Run service endpoints, doesn't support Workforce Identity Federation. Enable <a href="https://docs.cloud.google.com/run/docs/securing/identity-aware-proxy-cloud-run">Identity-Aware Proxy for Cloud Run</a> to use it.</li>
<li>Cloud Run doesn't support Workload Identity Federation direct resource access. To allow access, use <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#impersonation">service account impersonation</a> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/functions/docs">Cloud Run functions</a></td>
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
<li>The IAM permission <code>run.routes.invoke</code> , which manages access to Cloud Run service endpoints, doesn't support Workforce Identity Federation. Enable <a href="https://docs.cloud.google.com/run/docs/securing/identity-aware-proxy-cloud-run">Identity-Aware Proxy for Cloud Run</a> to use it.</li>
<li>Cloud Run doesn't support Workload Identity Federation. To allow access, use <a href="https://docs.cloud.google.com/iam/docs/workload-identity-federation#impersonation">service account impersonation</a> .</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/scheduler/docs">Cloud Scheduler</a></td>
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
<td>The Cloud Scheduler API doesn't support identity federation for jobs that have their <code>target</code> attribute set to <a href="https://docs.cloud.google.com/scheduler/docs/reference/rest/v1/projects.locations.jobs#appenginehttptarget"><code>appEngineHttpTarget</code></a> . To send a job to an App Engine target using identity federation, create your job with the <code>target</code> type set to <a href="https://docs.cloud.google.com/scheduler/docs/reference/rest/v1/projects.locations.jobs#HttpTarget"><code>httpTarget</code></a> and the <code>uri</code> field set to the full URI path of your App Engine target.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/service-mesh/docs">Cloud Service Mesh</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/shell/docs">Cloud Shell</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/source-repositories/docs">Cloud Source Repositories</a></td>
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
<td><a href="https://docs.cloud.google.com/sql/docs">Cloud SQL</a></td>
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
<li>Query Insights isn't supported.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/storage/docs">Cloud Storage</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/talent-solution/docs">Cloud Talent Solution</a></td>
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
<td><a href="https://docs.cloud.google.com/tasks/docs">Cloud Tasks</a></td>
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
<li><strong>App Engine queues:</strong> Since App Engine queues (queues that are created using a <code>queue.yaml</code> or <code>queue.xml</code> file) contain only tasks with App Engine targets, tasks in these queues aren't supported.</li>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/trace/docs">Cloud Trace</a></td>
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
<td><a href="https://docs.cloud.google.com/translate/docs">Cloud Translation</a></td>
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
<td><a href="https://docs.cloud.google.com/vision/docs">Cloud Vision API</a></td>
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
<td><a href="https://docs.cloud.google.com/workstations/docs">Cloud Workstations</a></td>
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
<td><a href="https://docs.cloud.google.com/cluster-director/docs">Cluster Director</a></td>
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
<td>To connect to the nodes in your cluster by using the <a href="https://docs.cloud.google.com/sdk/gcloud/reference/compute/ssh"><code>gcloud compute ssh</code> command</a> , you must <a href="https://docs.cloud.google.com/compute/docs/oslogin/manage-oslogin-in-an-org#external-user">grant access to users outside of your organization</a> .</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/compute/docs">Compute Engine</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>To use <a href="https://docs.cloud.google.com/compute/docs/ssh-in-browser">SSH-in-browser</a> , you must set up <a href="https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings"><code>google.posix_username</code> attribute mappings</a> .</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><ul>
<li>Importing and exporting images and disks with a Cloud Storage bucket requires <a href="https://docs.cloud.google.com/storage/docs/uniform-bucket-level-access">uniform bucket-level access</a> to be enabled for the bucket. To work around this limitation, use one of the following options:
<ul>
<li>If you don't need fine-grained object access control lists (ACLs), <a href="https://docs.cloud.google.com/storage/docs/using-uniform-bucket-level-access">enable uniform bucket-level access</a> on the affected Cloud Storage bucket:<br />
<code>gcloud storage buckets update gs:// </code><var translate="no"> BUCKET_NAME </var><code> --uniform-bucket-level-access</code></li>
<li>Use <a href="https://docs.cloud.google.com/docs/authentication/use-service-account-impersonation">service account impersonation</a> to import and export images and disks with buckets that don't have uniform bucket-level access enabled. Google service accounts are first-party credentials and aren't subject to identity federation limitations. To impersonate a service account, run the following command:<br />
<code>gcloud config set auth/impersonate_service_account </code><var translate="no"> SERVICE_ACCOUNT_EMAIL</var></li>
</ul></li>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/confidential-computing/docs">Confidential Space</a></td>
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
<td><a href="https://docs.cloud.google.com/beyondcorp-enterprise/docs">Context-Aware Access</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/contact-center/insights/docs">Customer Experience Insights</a></td>
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
<td><a href="https://docs.cloud.google.com/data-catalog/docs">Data Catalog</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/database-migration/docs">Database Migration Service</a></td>
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
<td><a href="https://docs.cloud.google.com/dataflow/docs">Dataflow</a></td>
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
<td><a href="https://docs.cloud.google.com/dataform/docs">Dataform</a></td>
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
<td><a href="https://docs.cloud.google.com/dataplex/docs">Knowledge Catalog</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/dataproc/docs">Managed Service for Apache Spark</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/dataproc-metastore/docs">Dataproc Metastore</a></td>
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
<td><a href="https://docs.cloud.google.com/datastore/docs">Datastore</a></td>
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
<td><a href="https://docs.cloud.google.com/datastream/docs">Datastream</a></td>
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
<td><a href="https://docs.cloud.google.com/dialogflow/docs">Dialogflow</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/document-ai/docs">Document AI</a></td>
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
<td><a href="https://docs.cloud.google.com/endpoint-verification/docs">Endpoint Verification</a></td>
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
<td><a href="https://docs.cloud.google.com/enterprise-knowledge-graph/docs/overview">Enterprise Knowledge Graph</a></td>
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
<td><a href="https://docs.cloud.google.com/error-reporting/docs">Error Reporting</a></td>
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
<td><a href="https://docs.cloud.google.com/eventarc/docs">Eventarc</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>No known limitations</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/eventarc/docs/third-parties/third-parties-overview">Third-party event publishing</a> using a <code>ChannelConnection</code> resource isn't supported for identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/filestore/docs">Filestore</a></td>
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
<td><a href="https://docs.cloud.google.com/firestore/docs">Firestore</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/duet-ai/docs">Gemini</a></td>
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
<tr class="odd">
<td><a href="https://antigravity.google/docs/enterprise">Google Antigravity</a></td>
<td>Unsupported</td>
<td><table>
<tbody>
<tr class="odd">
<td>Alternatives:</td>
<td>Google Antigravity doesn't support Workforce Identity Federation. As an alternative, authenticate the Antigravity CLI using a Google Workspace or Cloud Identity account, or use short-lived credentials through service account impersonation with Application Default Credentials (ADC).</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/armor/docs">Google Cloud Armor</a></td>
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
<td><a href="https://docs.cloud.google.com/contact-center/ccai-platform/docs">Google Cloud Contact Center as a Service</a></td>
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
<td><a href="https://docs.cloud.google.com/managed-service-for-apache-kafka/docs">Google Cloud Managed Service for Apache Kafka</a></td>
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
<td><a href="https://docs.cloud.google.com/marketplace/docs">Google Cloud Marketplace</a></td>
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
<td><a href="https://docs.cloud.google.com/migration-center/docs">Google Cloud Migration Center</a></td>
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
<td><a href="https://docs.cloud.google.com/netapp/volumes/docs/discover/overview/">Google Cloud NetApp Volumes</a></td>
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
<td><a href="https://docs.cloud.google.com/sdk/docs">Google Cloud SDK</a></td>
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
<td><a href="https://docs.cloud.google.com/distributed-cloud/hosted/docs/latest/gdcag">Google Distributed Cloud air-gapped</a></td>
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
<td><a href="https://docs.cloud.google.com/distributed-cloud/connected/latest/docs/overview">Google Distributed Cloud connected</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>When you log in to any attached Google Distributed Cloud connected cluster, the option <strong>Use your Google identity</strong> isn't available for Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>If you use Workload Identity Federation to programmatically run <code>kubectl</code> commands against different clusters from a Pod, you must use service account impersonation, as described in <a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/workload-identity#kubernetes-sa-to-iam">Alternative: link Kubernetes ServiceAccounts to IAM</a> . This limitation doesn't apply if you use your own workload identity pool with Workload Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/kubernetes-engine/distributed-cloud/bare-metal/docs/concepts/about-bare-metal">Google Distributed Cloud software only</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>When you log in to any attached Google Distributed Cloud software-only for bare metal cluster, the option <strong>Use your Google identity</strong> isn't available for Workforce Identity Federation.</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>If you use Workload Identity Federation to programmatically run <code>kubectl</code> commands against different clusters from a Pod, you must use service account impersonation, as described in <a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/workload-identity#kubernetes-sa-to-iam">Alternative: link Kubernetes ServiceAccounts to IAM</a> . This limitation doesn't apply if you use your own workload identity pool with Workload Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><code>gkectl</code> and <code>bmctl</code> don't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://cloud.google.com/earth-engine">Google Earth Engine</a></td>
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
<td>The BigQuery function <a href="https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_regionstats"><code>ST_REGIONSTATS</code></a> for raster data doesn't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/kubernetes-engine/docs">Google Kubernetes Engine</a></td>
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
<li>When you log in to any attached cluster, GKE on AWS cluster, or GKE on Azure cluster, the option <strong>Use your Google identity</strong> isn't available for Workforce Identity Federation.</li>
<li>When you create or attach any attached cluster, GKE on AWS cluster, or GKE on Azure cluster, you won't automatically be added as an administrator for Workforce Identity Federation.</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td>If you use Workload Identity Federation for GKE to programmatically run <code>kubectl</code> commands against a different GKE cluster from a Pod, you must use service account impersonation, as described in <a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/workload-identity#kubernetes-sa-to-iam">Alternative: link Kubernetes ServiceAccounts to IAM</a> . This limitation doesn't apply if you use your own workload identity pool with Workload Identity Federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td><code>gkeadm</code> , <code>gkectl</code> and <code>bmctl</code> don't support Workforce Identity Federation.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/chronicle">Google Security Operations</a></td>
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
<td><a href="https://docs.cloud.google.com/hybrid-connectivity">Hybrid Connectivity</a></td>
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
<td><a href="https://docs.cloud.google.com/iam/docs">Identity and Access Management</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iap/docs">Identity-Aware Proxy</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/identity-platform/docs">Identity Platform</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Enabling Identity Platform through the Google Cloud Workforce Identity Federation console is not supported. Workforce Identity Federation administrators must enable Identity Platform either through the Firebase Authentication console or by logging into the Google Cloud console using a Cloud Identity or Workspace account before Workforce Identity Federation users can access Identity Platform through the console (federated).</td>
</tr>
<tr class="even">
<td>Google Cloud API:</td>
<td><a href="https://docs.cloud.google.com/identity-platform/docs/reference/rpc/google.cloud.identitytoolkit.admin.v2#google.cloud.identitytoolkit.admin.v2.ProjectConfigService.InitializeIdentityPlatform"><code>InitializeIdentityPlatform</code></a> doesn't support identity federation.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/integration-connectors/docs">Integration Connectors</a></td>
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
<td><a href="https://docs.cloud.google.com/assured-workloads/key-access-justifications/docs">Key Access Justifications</a></td>
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
<td><a href="https://docs.cloud.google.com/anthos/run/docs">Knative serving</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/livestream/docs">Live Stream API</a></td>
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
<td><a href="https://docs.cloud.google.com/looker/docs">Looker (Google Cloud core)</a></td>
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
<td><a href="https://docs.cloud.google.com/looker/docs/studio">Data Studio</a></td>
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
<td><a href="https://docs.cloud.google.com/managed-microsoft-ad/docs">Managed Service for Microsoft Active Directory</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/media-cdn/docs">Media CDN</a></td>
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
<td><a href="https://docs.cloud.google.com/memorystore/docs/redis/">Memorystore</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/migrate/containers/docs">Migrate to Containers</a></td>
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
<td><a href="https://docs.cloud.google.com/migrate/virtual-machines/docs">Migrate to Virtual Machines</a></td>
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
<td><a href="https://docs.cloud.google.com/network-connectivity/docs/network-connectivity-center">Network Connectivity Center</a></td>
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
<td><a href="https://docs.cloud.google.com/network-intelligence-center">Network Intelligence Center</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/network-tiers/docs">Network Service Tiers</a></td>
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
<td><a href="https://docs.cloud.google.com/resource-manager/docs/organization-policy/overview/">Organization Policy Service</a></td>
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
<td><a href="https://docs.cloud.google.com/parallelstore/docs/overview/">Parallelstore</a></td>
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
<td><a href="https://docs.cloud.google.com/service-health/docs/overview/">Personalized Service Health</a></td>
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
<td><a href="https://docs.cloud.google.com/policy-intelligence/docs">Policy Intelligence</a></td>
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
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/troubleshoot-access">Policy Troubleshooter</a> : Federated identities can't check the membership of Google groups in allow and deny policies, or the membership of Cloud Identity accounts (domains) in deny policies. When federated identities call the <code>iam.troubleshoot</code> method, role bindings and deny rules that contain groups or domains have an access result of <strong>Unknown</strong> , unless the role binding or deny rule also explicitly includes the principal.</li>
<li><p><a href="https://docs.cloud.google.com/policy-intelligence/docs/policy-analyzer-overview">Policy Analyzer</a> : When calling the <a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeIamPolicy"><code>analyzeIamPolicy</code></a> or the <a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeIamPolicyLongrunning"><code>analyzeIamPolicyLongrunning</code></a> method, federated identities might receive incomplete analysis results because of the following:</p>
<ul>
<li>Federated identities can't check the membership of Google groups in allow policies. As a result, when federated identities analyze access for a principal, the query results don't include permissions and roles that the principal has due to their membership in a group.</li>
<li>When analyzing access, federated identities can't enable the <code>expand-groups</code> option.</li>
</ul>
<p>Federated identities can't use the following API methods:</p>
<ul>
<li><a href="https://docs.cloud.google.com/asset-inventory/docs/reference/rest/v1/TopLevel/analyzeMove"><code>analyzeMove</code></a></li>
</ul></li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview">Policy Simulator</a> : Federated identities can't use the Policy Simulator API ( <code>policysimulator.googleapis.com</code> ).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/activity-analyzer-service-account-authentication">Activity Analyzer</a> : Federated identities can't use the Policy Analyzer API ( <code>policyanalyzer.googleapis.com</code> ).</li>
<li><a href="https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview">IAM Recommender</a> : Federated identities can't use the Recommender API ( <code>recommender.googleapis.com</code> ).</li>
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
<td><a href="https://docs.cloud.google.com/vpc/docs/private-service-connect">Private Service Connect</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/pam-overview/">Privileged Access Manager</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/pubsub/docs">Pub/Sub</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/recaptcha/docs">reCAPTCHA</a></td>
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
<td><a href="https://docs.cloud.google.com/recaptcha/docs/reference/rpc/google.cloud.recaptchaenterprise.v1#google.cloud.recaptchaenterprise.v1.RecaptchaEnterpriseService.MigrateKey"><code>MigrateKey</code></a> isn't supported for federated identities.</td>
</tr>
<tr class="odd">
<td>Other:</td>
<td>No known limitations</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/recommender/docs">Recommender</a></td>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/resource-manager/docs">Resource Manager</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>Workforce Identity Federation users can only view and operate on the organization for which Workforce Identity Federation was configured. Other organizations to which the users are added are not displayed in the Google Cloud console.</td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/retail/docs">AI Commerce Search API</a></td>
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
<td>The following methods don't support identity federation:
<ul>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.CatalogService.UpdateCatalog">UpdateCatalog</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.CompletionService.ImportCompletionData">ImportCompletionData</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ModelService.TuneModel">TuneModel</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ProductService.ImportProducts">ImportProducts</a></li>
<li><a href="https://docs.cloud.google.com/retail/docs/reference/rpc/google.cloud.retail.v2alpha#google.cloud.retail.v2alpha.ProductService.PurgeProducts">PurgeProducts</a></li>
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
<tr class="even">
<td><a href="https://docs.cloud.google.com/secret-manager/docs">Secret Manager</a></td>
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
<td><a href="https://docs.cloud.google.com/secure-source-manager/docs">Secure Source Manager</a></td>
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
<li>Workforce identity pool providers used for Secure Source Manager must provide <code>google.subject</code> and <code>google.email</code> attribute mappings.</li>
<li>You can only use your federated identity to log in to a Secure Source Manager instance that is configured to use Workforce Identity Federation.</li>
<li>Email notifications from Secure Source Manager are not supported for Workforce Identity Federation configured instances.</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/security-command-center/docs">Security Command Center</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/dlp/docs">Sensitive Data Protection</a></td>
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
<td><a href="https://docs.cloud.google.com/vpc/docs/serverless-vpc-access/">Serverless VPC Access</a></td>
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
<td><a href="https://docs.cloud.google.com/service-directory/docs">Service Directory</a></td>
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
<td><a href="https://docs.cloud.google.com/service-infrastructure/docs">Service Infrastructure</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/spanner/docs">Spanner</a></td>
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
<td><a href="https://docs.cloud.google.com/speech-to-text/docs">Speech-to-Text</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/storage-transfer/docs/">Storage Transfer Service</a></td>
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
<td><a href="https://docs.cloud.google.com/text-to-speech/docs">Text-to-Speech</a></td>
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
<td><a href="https://docs.cloud.google.com/transcoder/docs">Transcoder API</a></td>
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
<td><a href="https://docs.cloud.google.com/transfer-appliance/docs/4.0/overview/">Transfer Appliance</a></td>
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
<td><a href="https://docs.cloud.google.com/translation-hub/docs">Translation Hub</a></td>
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
<td><a href="https://docs.cloud.google.com/vertex-ai/docs">Vertex AI</a></td>
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
<tr class="odd">
<td><a href="https://docs.cloud.google.com/agent-builder/overview">Vertex AI Agent Builder</a></td>
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
<tr class="even">
<td><a href="https://cloud.google.com/gemini-enterprise">Gemini Enterprise</a></td>
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
<td>Workspace connectors are not supported for Workforce Identity Federation users.</td>
</tr>
</tbody>
</table></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/vision-ai/docs">Vertex AI Vision</a></td>
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
<td><a href="https://docs.cloud.google.com/vertex-ai/docs/workbench/notebook-solution">Vertex AI Workbench</a></td>
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
<td><a href="https://docs.cloud.google.com/video-intelligence/docs">Video Intelligence API</a></td>
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
<td><a href="https://docs.cloud.google.com/video-stitcher/docs">Video Stitcher API</a></td>
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
<td><a href="https://docs.cloud.google.com/vpc/docs">Virtual Private Cloud</a></td>
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
<td><a href="https://docs.cloud.google.com/vpc-service-controls/docs">VPC Service Controls</a></td>
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
<li><a href="https://docs.cloud.google.com/access-context-manager/docs/reference/rpc/google.identity.accesscontextmanager.v1alpha"><code>v1alpha</code> APIs</a> aren't available to federated identities.</li>
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
<td><a href="https://docs.cloud.google.com/web-risk/docs">Web Risk</a></td>
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
<td><a href="https://docs.cloud.google.com/workflows/docs">Workflows</a></td>
<td><a href="https://cloud.google.com/products/#product-launch-stages">GA</a></td>
<td><table>
<tbody>
<tr class="odd">
<td>Console (federated):</td>
<td>The automated grant feature, which grants the Workforce Identity Federation user the Service Account User ( <code>roles/iam.serviceAccountUser</code> ) role on the project, is inactive. To grant the role to Workforce Identity Federation users, you must go to the IAM page and specify a Workforce Identity Federation <a href="https://docs.cloud.google.com/iam/docs/principal-identifiers">principal identifier</a> or contact the project owner to do so.</td>
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
<td><a href="https://docs.cloud.google.com/workload-manager/docs">Workload Manager</a></td>
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
