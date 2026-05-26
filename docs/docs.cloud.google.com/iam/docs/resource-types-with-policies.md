---
name: documents/docs.cloud.google.com/iam/docs/resource-types-with-policies
uri: https://docs.cloud.google.com/iam/docs/resource-types-with-policies
title: Resource types that accept allow policies
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the resource types on which you can set [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) .

> **Note:** Allow policies set on a parent resource (a project, folder, or organization) are inherited by the resource's children, regardless of the policy set on the child resource itself. For example, if the allow policy for a project grants a user the ability to administer Compute Engine virtual machine (VM) instances, then the user can administer any Compute Engine VM in that project, regardless of the allow policy you set on each VM.

Select a service to see which of its resource types support allow policies:

All services BigQuery Identity-Aware Proxy Access Context Manager Gemini Enterprise Agent Platform BigQuery sharing API Gateway Apigee Apigee Registry App Hub Artifact Registry AutoML Backup and Disaster Recovery Chrome Enterprise Premium BigLake BigQuery Connection API BigQuery Data Policy BigQuery Reservation API Cloud Bigtable Admin API Binary Authorization Cloud Billing Cloud Build Cloud Deploy Cloud Run functions Cloud Key Management Service Resource Manager Cloud Tasks Compute Engine Infrastructure Manager Customer Experience Insights Artifact Analysis Data Catalog Dataform Cloud Data Fusion Database Migration Service Knowledge Catalog Managed Service for Apache Spark Cloud Deployment Manager Discovery Engine Cloud DNS Cloud Domains Eventarc Backup for GKE GKE Hub Google Distributed Cloud Cloud Healthcare API Identity and Access Management Cloud Logging Managed Service for Microsoft Active Directory Dataproc Metastore AI Platform Network Connectivity Center Network Management API Network Security Network Services Notebooks Certificate Authority Service Pub/Sub Cloud Run Secret Manager Secure Source Manager Security Command Center Service Directory Service Management Spanner Cloud Storage Google Cloud VMware Engine Cloud Workstations

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Service</th>
<th>Resources that accept allow policies</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>BigQuery</td>
<td>Datasets<br />
Routines<br />
Tables</td>
</tr>
<tr class="even">
<td>Identity-Aware Proxy</td>
<td>All web services<br />
Individual web services<br />
Tunnel<br />
Tunnel instances<br />
Tunnel zones<br />
Web service types<br />
Web service versions</td>
</tr>
<tr class="odd">
<td>Access Context Manager</td>
<td>Access policies</td>
</tr>
<tr class="even">
<td>Gemini Enterprise Agent Platform</td>
<td>Datasets<br />
Entity types<br />
Feature groups<br />
Feature online stores<br />
Feature views<br />
Featurestores<br />
Models<br />
Notebook runtime templates<br />
Reasoning engines</td>
</tr>
<tr class="odd">
<td>BigQuery sharing</td>
<td>Data exchanges<br />
Listings<br />
Subscriptions</td>
</tr>
<tr class="even">
<td>API Gateway</td>
<td>APIs<br />
Configs<br />
Gateways</td>
</tr>
<tr class="odd">
<td>Apigee</td>
<td>Deployments<br />
Environments<br />
Spaces</td>
</tr>
<tr class="even">
<td>Apigee Registry</td>
<td>APIs<br />
Artifacts<br />
Deployments<br />
Documents<br />
Instances<br />
Runtime<br />
Specs<br />
Versions</td>
</tr>
<tr class="odd">
<td>App Hub</td>
<td>Applications</td>
</tr>
<tr class="even">
<td>Artifact Registry</td>
<td>Repositories</td>
</tr>
<tr class="odd">
<td>AutoML</td>
<td>Datasets<br />
Locations<br />
Models</td>
</tr>
<tr class="even">
<td>Backup and Disaster Recovery</td>
<td>Management servers</td>
</tr>
<tr class="odd">
<td>Chrome Enterprise Premium</td>
<td>App connections<br />
App connectors<br />
App gateways<br />
Applications<br />
Security gateways</td>
</tr>
<tr class="even">
<td>BigLake</td>
<td>Catalogs<br />
Namespaces<br />
Tables</td>
</tr>
<tr class="odd">
<td>BigQuery Connection API</td>
<td>Connections</td>
</tr>
<tr class="even">
<td>BigQuery Data Policy</td>
<td>Data policies</td>
</tr>
<tr class="odd">
<td>BigQuery Reservation API</td>
<td>Assignments<br />
Reservations</td>
</tr>
<tr class="even">
<td>Cloud Bigtable Admin API</td>
<td>Authorized views<br />
Backups<br />
Instances<br />
Logical views<br />
Materialized views<br />
Schema bundles<br />
Tables</td>
</tr>
<tr class="odd">
<td>Binary Authorization</td>
<td>Attestors<br />
Policy</td>
</tr>
<tr class="even">
<td>Cloud Billing</td>
<td>Billing accounts</td>
</tr>
<tr class="odd">
<td>Cloud Build</td>
<td>Connections</td>
</tr>
<tr class="even">
<td>Cloud Deploy</td>
<td>Custom target types<br />
Delivery pipelines<br />
Deploy policies<br />
Targets</td>
</tr>
<tr class="odd">
<td>Cloud Run functions</td>
<td>Functions</td>
</tr>
<tr class="even">
<td>Cloud Key Management Service</td>
<td>Crypto keys<br />
EKM config<br />
EKM connections<br />
Import jobs<br />
Key rings</td>
</tr>
<tr class="odd">
<td>Resource Manager</td>
<td>Folders<br />
Organizations<br />
Projects<br />
Tag keys<br />
Tag values</td>
</tr>
<tr class="even">
<td>Cloud Tasks</td>
<td>Queues</td>
</tr>
<tr class="odd">
<td>Compute Engine</td>
<td>Backend buckets<br />
Backend services<br />
Disks<br />
Firewall policies<br />
Images<br />
Instance templates<br />
Instances<br />
Instant snapshot groups<br />
Instant snapshots<br />
Interconnect attachment groups<br />
Interconnect groups<br />
License codes<br />
Licenses<br />
Machine images<br />
Network attachments<br />
Network firewall policies<br />
Node groups<br />
Node templates<br />
Region backend buckets<br />
Region backend services<br />
Region disks<br />
Region instant snapshot groups<br />
Region instant snapshots<br />
Region network firewall policies<br />
Region snapshots<br />
Reservation blocks<br />
Reservation sub-blocks<br />
Reservations<br />
Resource policies<br />
Service attachments<br />
Snapshots<br />
Storage pools<br />
Subnetworks</td>
</tr>
<tr class="even">
<td>Infrastructure Manager</td>
<td>Deployments</td>
</tr>
<tr class="odd">
<td>Customer Experience Insights</td>
<td>Authorized views</td>
</tr>
<tr class="even">
<td>Artifact Analysis</td>
<td>Notes<br />
Occurrences</td>
</tr>
<tr class="odd">
<td>Data Catalog</td>
<td>Entry groups<br />
Policy tags<br />
Tag templates<br />
Taxonomies</td>
</tr>
<tr class="even">
<td>Dataform</td>
<td>Folders<br />
Repositories<br />
Team folders<br />
Workspaces</td>
</tr>
<tr class="odd">
<td>Cloud Data Fusion</td>
<td>Instances</td>
</tr>
<tr class="even">
<td>Database Migration Service</td>
<td>Connection profiles<br />
Conversion workspaces<br />
Migration jobs<br />
Objects<br />
Private connections</td>
</tr>
<tr class="odd">
<td>Knowledge Catalog</td>
<td>Aspect types<br />
Assets<br />
Attributes<br />
Categories<br />
Change requests<br />
Data attribute bindings<br />
Data domains<br />
Data products<br />
Data scans<br />
Data taxonomies<br />
Encryption configs<br />
Entry groups<br />
Entry link types<br />
Entry types<br />
Glossaries<br />
Governance rules<br />
Lakes<br />
Tasks<br />
Terms<br />
Zones</td>
</tr>
<tr class="even">
<td>Managed Service for Apache Spark</td>
<td>Autoscaling policies<br />
Clusters<br />
Jobs<br />
Operations<br />
Workflow templates</td>
</tr>
<tr class="odd">
<td>Cloud Deployment Manager</td>
<td>Deployments</td>
</tr>
<tr class="even">
<td>Discovery Engine</td>
<td>Engines</td>
</tr>
<tr class="odd">
<td>Cloud DNS</td>
<td>Managed zones</td>
</tr>
<tr class="even">
<td>Cloud Domains</td>
<td>Registrations</td>
</tr>
<tr class="odd">
<td>Eventarc</td>
<td>Channel connections<br />
Channels<br />
Enrollments<br />
Google API sources<br />
Message buses<br />
Pipelines<br />
Triggers</td>
</tr>
<tr class="even">
<td>Backup for GKE</td>
<td>Backup plans<br />
Backups<br />
Restore plans<br />
Restores<br />
Volume backups<br />
Volume restores</td>
</tr>
<tr class="odd">
<td>GKE Hub</td>
<td>Features<br />
Memberships<br />
Scopes</td>
</tr>
<tr class="even">
<td>Google Distributed Cloud</td>
<td>Bare metal admin clusters<br />
Bare metal clusters<br />
Bare metal node pools<br />
VMware admin clusters<br />
VMware clusters<br />
VMware node pools</td>
</tr>
<tr class="odd">
<td>Cloud Healthcare API</td>
<td>Consent stores<br />
Data mapper workspaces<br />
Datasets<br />
DICOM stores<br />
FHIR stores<br />
HL7v2 stores</td>
</tr>
<tr class="even">
<td>Identity and Access Management</td>
<td>Service accounts<br />
Workforce identity pools<br />
Workload identity pools</td>
</tr>
<tr class="odd">
<td>Cloud Logging</td>
<td>Views</td>
</tr>
<tr class="even">
<td>Managed Service for Microsoft Active Directory</td>
<td>Backups<br />
Domains<br />
Peerings</td>
</tr>
<tr class="odd">
<td>Dataproc Metastore</td>
<td>Backups<br />
Databases<br />
Federations<br />
Services<br />
Tables</td>
</tr>
<tr class="even">
<td>AI Platform</td>
<td>Jobs<br />
Models</td>
</tr>
<tr class="odd">
<td>Network Connectivity Center</td>
<td>Groups<br />
Hubs<br />
Internal ranges<br />
Policy-based routes<br />
Spokes</td>
</tr>
<tr class="even">
<td>Network Management API</td>
<td>Connectivity tests</td>
</tr>
<tr class="odd">
<td>Network Security</td>
<td>Address groups<br />
Authorization policies<br />
Authz policies<br />
Client TLS policies<br />
Server TLS policies</td>
</tr>
<tr class="even">
<td>Network Services</td>
<td>Edge cache keysets<br />
Edge cache origins<br />
Edge cache services</td>
</tr>
<tr class="odd">
<td>Notebooks</td>
<td>Instances<br />
Runtimes</td>
</tr>
<tr class="even">
<td>Certificate Authority Service</td>
<td>CA pools<br />
Certificate revocation lists<br />
Certificate templates</td>
</tr>
<tr class="odd">
<td>Pub/Sub</td>
<td>Schemas<br />
Snapshots<br />
Subscriptions<br />
Topics</td>
</tr>
<tr class="even">
<td>Cloud Run</td>
<td>Instances<br />
Jobs<br />
Services<br />
Worker pools</td>
</tr>
<tr class="odd">
<td>Secret Manager</td>
<td>Secrets</td>
</tr>
<tr class="even">
<td>Secure Source Manager</td>
<td>Instances<br />
Repositories</td>
</tr>
<tr class="odd">
<td>Security Command Center</td>
<td>Sources</td>
</tr>
<tr class="even">
<td>Service Directory</td>
<td>Namespaces<br />
Services</td>
</tr>
<tr class="odd">
<td>Service Management</td>
<td>Consumers<br />
Services</td>
</tr>
<tr class="even">
<td>Spanner</td>
<td>Backup schedules<br />
Backups<br />
Databases<br />
Instances</td>
</tr>
<tr class="odd">
<td>Cloud Storage</td>
<td>Buckets<br />
Managed folders</td>
</tr>
<tr class="even">
<td>Google Cloud VMware Engine</td>
<td>Clusters<br />
HCX activation keys<br />
Private clouds</td>
</tr>
<tr class="odd">
<td>Cloud Workstations</td>
<td>Workstation configs<br />
Workstations</td>
</tr>
</tbody>
</table>
