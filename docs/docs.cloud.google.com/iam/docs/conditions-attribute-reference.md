---
name: documents/docs.cloud.google.com/iam/docs/conditions-attribute-reference
uri: https://docs.cloud.google.com/iam/docs/conditions-attribute-reference
title: Attribute reference for IAM Conditions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes supported attributes in a [condition expression](https://docs.cloud.google.com/iam/docs/conditions-overview) .

> **Note:** This page shows common uses of each function and operator. For more details about the allowed syntax for functions and operators, see the [CEL language definition](https://github.com/google/cel-spec/blob/master/doc/langdef.md) .

## Supported condition attributes

The following sections summarize the supported attributes and indicate which Google Cloud services recognize each attribute.

### Resource attributes

The following attributes relate to the resource that is the subject of the request.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Attribute</strong></th>
<th><strong>Usage summary</strong></th>
<th><strong>Supported Google Cloud services</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-service">Resource service attribute</a></strong></td>
<td><p>Manage access based on the Google Cloud service being used.</p>
<p>You can use this attribute in allow policy role bindings.</p></td>
<td><ul>
<li>Apigee</li>
<li>Application Integration</li>
<li>Apigee API Hub</li>
<li>Backup and DR Service</li>
<li>BigQuery</li>
<li>BigQuery Reservation API</li>
<li>Bigtable</li>
<li>Binary Authorization</li>
<li>Cloud Deploy</li>
<li>Customer Experience Agent Studio</li>
<li>Cloud Key Management Service</li>
<li>Cloud Logging</li>
<li>Cloud SQL</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Dataform</li>
<li>Cloud DNS</li>
<li>Google Kubernetes Engine</li>
<li>Firestore</li>
<li>Identity-Aware Proxy</li>
<li>Integration Connectors</li>
<li>Google Cloud Managed Service for Apache Kafka</li>
<li>Network Security Integration</li>
<li>Parameter Manager</li>
<li>Cloud NGFW</li>
<li>Pub/Sub Lite</li>
<li>Resource Manager</li>
<li>Secret Manager</li>
<li>Spanner</li>
</ul></td>
</tr>
<tr class="even">
<td><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-type">Resource type attribute</a></strong></td>
<td><p>Manage access based on the resource type.</p>
<p>You can use this attribute in allow policy role bindings.</p></td>
<td><ul>
<li>Apigee</li>
<li>Application Integration</li>
<li>Apigee API Hub</li>
<li>BigQuery</li>
<li>BigQuery Reservation API</li>
<li>Bigtable</li>
<li>Binary Authorization</li>
<li>Customer Experience Agent Studio</li>
<li>Cloud Key Management Service</li>
<li>Cloud Logging</li>
<li>Cloud SQL</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Dataform</li>
<li>Cloud DNS</li>
<li>Google Kubernetes Engine</li>
<li>Firestore</li>
<li>Cloud NGFW</li>
<li>Identity-Aware Proxy</li>
<li>Integration Connectors</li>
<li>Google Cloud Managed Service for Apache Kafka</li>
<li>Network Security Integration</li>
<li>Parameter Manager</li>
<li>Pub/Sub Lite</li>
<li>Resource Manager</li>
<li>Secret Manager</li>
<li>Spanner</li>
</ul></td>
</tr>
<tr class="odd">
<td><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-name">Resource name attribute</a></strong></td>
<td><p>Manage access based on the name of the resource.</p>
<p>You can use this attribute in allow policy role bindings.</p></td>
<td><ul>
<li>Apigee</li>
<li>Application Integration</li>
<li>Apigee API Hub</li>
<li>Backup and DR Service</li>
<li>BigQuery</li>
<li>BigQuery Reservation API</li>
<li>Bigtable</li>
<li>Binary Authorization</li>
<li>Cloud Deploy</li>
<li>Customer Experience Agent Studio</li>
<li>Cloud Key Management Service</li>
<li>Cloud Logging</li>
<li>Cloud SQL</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Dataform</li>
<li>Cloud DNS</li>
<li>Google Kubernetes Engine</li>
<li>Firestore</li>
<li>Cloud NGFW</li>
<li>Integration Connectors</li>
<li>Google Cloud Managed Service for Apache Kafka</li>
<li>Network Security Integration</li>
<li>Parameter Manager</li>
<li>Pub/Sub Lite</li>
<li>Secret Manager</li>
<li>Spanner</li>
</ul></td>
</tr>
<tr class="even">
<td><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-tags">Resource tags</a></strong></td>
<td><p>Manage access based on the tags attached to the resource.</p>
<p>You can use this attribute in the following places:</p>
<ul>
<li>Allow policy role bindings</li>
<li>Deny policy deny rules</li>
</ul></td>
<td><p>All Google Cloud services (see <a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#inherited-support">Support for inherited conditions</a> )</p>
<blockquote>
<strong>Note:</strong> Certain areas of the Google Cloud console don't recognize allow policy role bindings with tag-based conditions. As a result, if you have a role with a tag-based condition, then the Google Cloud console might incorrectly prevent you from performing certain actions. If you encounter this issue, then use an alternate method, such as the gcloud CLI, to perform the action.
</blockquote></td>
</tr>
</tbody>
</table>

For more details about resource attributes, see [Resource attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource) on this page.

### Principal attributes

The following attributes relate to the principal making the request.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Attribute</strong></th>
<th><strong>Usage summary</strong></th>
<th><strong>Supported principal types</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principal-type">Principal type attribute</a></strong></p></td>
<td><p>Apply policies based on the type of principal in the request.</p>
<p>You can use this attribute in policy bindings for principal access boundary policies.</p></td>
<td><ul>
<li>Google Accounts</li>
<li>Workforce identity pool identities</li>
<li>Workload identity pool identities</li>
<li>Service accounts</li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principal-subject">Principal subject attribute</a></strong></p></td>
<td><p>Apply policies based on the identity of the principal in the request.</p>
<p>You can use this attribute in policy bindings for principal access boundary policies.</p></td>
<td><ul>
<li>Google Accounts</li>
<li>Workforce identity pool identities</li>
<li>Workload identity pool identities</li>
<li>Service accounts</li>
</ul></td>
</tr>
</tbody>
</table>

For more details about principal attributes, see [Principal attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principals) on this page.

### Request attributes

The following attributes relate to the details of the request.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Attribute</strong></th>
<th><strong>Usage summary</strong></th>
<th><strong>Supported Google Cloud services</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#access-levels">Access levels attribute</a></strong></p></td>
<td><p>Manage access based on specific access level(s).</p>
<p>An access level is a calculated attribute based on raw attributes about the request and requester, such as the origin IP address, device attributes, and time of day. For example, an <code dir="ltr" translate="no">onNetwork</code> access level might require that the device making the request originates from a particular IP address range. Access levels are defined by an organization's administrators.</p>
<p>You can use this attribute in allow policy role bindings.</p></td>
<td><p>Identity-Aware Proxy</p></td>
</tr>
<tr class="even">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#api">API attributes</a></strong></p></td>
<td><p>Manage access based on data provided by a specific Google Cloud API or service.</p>
<p>You can use this attribute in allow policy role bindings.</p></td>
<td><ul>
<li>API Gateway</li>
<li>AutoML</li>
<li>Certificate Authority Service</li>
<li>Cloud Run functions</li>
<li>Cloud Healthcare API</li>
<li>Cloud Key Management Service</li>
<li>Cloud Run</li>
<li>Cloud Runtime Configuration API</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Artifact Analysis</li>
<li>Managed Service for Apache Spark</li>
<li>Earth Engine</li>
<li>Game Servers</li>
<li>Identity and Access Management</li>
<li>Identity-Aware Proxy</li>
<li>Managed Service for Microsoft Active Directory</li>
<li>User-managed notebooks</li>
<li>Resource Manager</li>
<li>Secret Manager</li>
<li>Service Management</li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#date-time">Date/time attributes</a></strong></p></td>
<td><p>Set expirable, scheduled, or limited-duration access to Google Cloud resources.</p>
<p>You can use these attributes in allow policy role bindings.</p></td>
<td><p>All Google Cloud services (see <a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#inherited-support">Support for inherited conditions</a> )</p></td>
</tr>
<tr class="even">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#ip-port">Destination IP/port attributes</a></strong></p></td>
<td><p>Manage access based on the destination IP address and/or port of a request. For example, a Compute Engine virtual machine (VM) instance might expose an external IP, such as <code dir="ltr" translate="no">10.0.0.2</code> , but port <code dir="ltr" translate="no">22</code> might be exposed for administrative usage only.</p>
<p>Used for <a href="https://docs.cloud.google.com/iap/docs/tcp-forwarding-overview">Identity-Aware Proxy TCP forwarding.</a></p>
<p>You can use these attributes in allow policy role bindings.</p></td>
<td><p>Identity-Aware Proxy</p></td>
</tr>
<tr class="odd">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#forwarding-rule">Forwarding rule attributes</a></strong></p></td>
<td><p>Specify the types of <a href="https://docs.cloud.google.com/load-balancing/docs/forwarding-rule-concepts">forwarding rules</a> that a principal can create. For example, you could allow a principal to create forwarding rules for <a href="https://docs.cloud.google.com/load-balancing/docs/load-balancing-overview#types-of-cloud-load-balancing">internal Google Cloud load balancers</a> , which handle traffic that originates inside a Google Cloud network, but not for external Google Cloud load balancers, which handle traffic that originates from the internet.</p>
<p>You can use these attributes in allow policy role bindings.</p></td>
<td><ul>
<li>Cloud Load Balancing</li>
<li>Cloud VPN</li>
<li>Compute Engine <a href="https://docs.cloud.google.com/load-balancing/docs/protocol-forwarding">protocol forwarding</a></li>
<li>Cloud Service Mesh</li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong><a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#url">URL path/host attributes</a></strong></p></td>
<td><p>Manage access based on the URL path and/or host of a request. For example, a condition could specify that <code dir="ltr" translate="no">https://example.com</code> is the main application accessible by a general domain of users, while <code dir="ltr" translate="no">https://hr.example.com/admin</code> is used to access a page in the application that only Human Resources admins can access.</p>
<p>You can use these attributes in allow policy role bindings.</p></td>
<td><ul>
<li>Identity-Aware Proxy</li>
<li>Cloud Run</li>
</ul></td>
</tr>
</tbody>
</table>

For more details about request attributes, see [Request attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#request) on this page.

### Support for inherited conditions

In addition to adding conditions to the allow policies of some service-specific resources, it's possible to add conditional role bindings to resources at the organization, folder, or project level. When added at the container resource level, the conditional role bindings are inherited by other resources through the [resource hierarchy](https://docs.cloud.google.com/iam/docs/overview#policy_hierarchy) . Inherited conditions are useful when a resource doesn't allow [conditions in their allow policies](https://docs.cloud.google.com/iam/docs/resource-types-with-conditional-roles) or doesn't have an allow policy.

When you use attributes at the organization, folder, or project level, keep in mind that most attributes are available only for specific resource types. If part of a condition uses an attribute that isn't available for a resource, then that part of the condition is never interpreted as granting access. For example, the condition `resource.name.endsWith == devResource` never grants access to any IAM resource because IAM resources don't provide the resource name.

To prevent this issue, use the [resource type](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-type) and [resource service](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-service) attributes to limit the scope of the condition. For example, the following condition evaluates to `true` for all resource types other than Compute Engine instances; in contrast, for Compute Engine instances, the condition checks resource name:

    resource.type != 'compute.googleapis.com/Disk' ||
        resource.name.endsWith('devResource')

> **Important:** If your condition uses the `resource.name` attribute, we strongly recommend that you use the `resource.type` attribute, not the `resource.service` attribute, to explicitly limit which resource types the `resource.name` condition applies to. For details, see [`resource.name` attribute](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-name) on this page.

## Resource attributes

The resource service, resource type, and resource name attributes are typically used to change the scope of an access grant provided by the role binding. When a role contains permissions that apply to different resource-specific attributes, resource-based conditions can be used to grant a subset of the role's permissions for specific type(s) or for specific service(s).

### resource.service attribute

The `resource.service` attribute lets you set a condition based on the Google Cloud service being used. For example, you could set a condition limiting a user's access to resources that use the `cloudresourcemanager.googleapis.com` service. For a list of supported values, see [Resource service values](https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-service) .

You can use the `resource.service` attribute in allow policy role bindings.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">resource.service</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><p><code dir="ltr" translate="no">string</code></p>
<p>For a list of supported values, see <a href="https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-service">Resource service values</a> .</p></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">          ==        ,           !=       </code></td>
</tr>
<tr class="even">
<td>Details</td>
<td>When you use the <code dir="ltr" translate="no">resource.type</code> attribute in conditions, check for exact equality ( <code dir="ltr" translate="no">        ==       </code> ) or exact inequality ( <code dir="ltr" translate="no">        !=       </code> ) with the attribute. Other comparisons, such as checking for a prefix or suffix, might give you unexpected results.</td>
</tr>
<tr class="odd">
<td>Example</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> for Compute Engine resources:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.service == &quot;compute.googleapis.com&quot;</code></pre></td>
</tr>
<tr class="even">
<td>Supported services</td>
<td><ul>
<li>Apigee</li>
<li>Application Integration</li>
<li>Apigee API Hub</li>
<li>Backup and DR Service</li>
<li>BigQuery</li>
<li>BigQuery Reservation API</li>
<li>Bigtable</li>
<li>Binary Authorization</li>
<li>Cloud Deploy</li>
<li>Customer Experience Agent Studio</li>
<li>Cloud Key Management Service</li>
<li>Cloud Logging</li>
<li>Cloud SQL</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Dataform</li>
<li>Cloud DNS</li>
<li>Google Kubernetes Engine</li>
<li>Firestore</li>
<li>Identity-Aware Proxy</li>
<li>Integration Connectors</li>
<li>Google Cloud Managed Service for Apache Kafka</li>
<li>Network Security Integration</li>
<li>Parameter Manager</li>
<li>Cloud NGFW</li>
<li>Pub/Sub Lite</li>
<li>Resource Manager</li>
<li>Secret Manager</li>
<li>Spanner</li>
</ul></td>
</tr>
</tbody>
</table>

### resource.type attribute

The `resource.type` attribute lets you set a condition based on the resource's type. For example, you could set a condition limiting a user's access to resources of the type `storage.googleapis.com/Object` . For a list of supported values, see [Resource type values](https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-type) .

If your condition uses the `resource.name` attribute, we strongly recommend that you use the `resource.type` attribute to control which resource types the condition applies to. For details, see [`resource.name` attribute](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-name) on this page.

You can use the `resource.type` attribute in allow policy role bindings.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">resource.type</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><p><code dir="ltr" translate="no">string</code></p>
<p>For a list of supported values, see <a href="https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-type">Resource type values</a> .</p></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">          ==        ,           !=       </code></td>
</tr>
<tr class="even">
<td>Details</td>
<td>When you use the <code dir="ltr" translate="no">resource.type</code> attribute in conditions, check for exact equality ( <code dir="ltr" translate="no">          ==       </code> ) or exact inequality ( <code dir="ltr" translate="no">          !=       </code> ) with the attribute. Other comparisons, such as checking for a prefix or suffix, might give you unexpected results.</td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> unless the resource is a Compute Engine image:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type != &quot;compute.googleapis.com/Image&quot;</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> only if the resource is a Compute Engine image or persistent disk:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>(resource.type == &quot;compute.googleapis.com/Image&quot; ||
 resource.type == &quot;compute.googleapis.com/Disk&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td><table style="width:40%;">
<colgroup>
<col style="width: 40%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Apigee</td>
<td><ul>
<li>API product attributes</li>
<li>API products</li>
<li>API proxies</li>
<li>API proxy key-value map entries</li>
<li>API proxy key-value maps</li>
<li>API proxy revisions</li>
<li>Caches</li>
<li>Developer app attributes</li>
<li>Developer apps</li>
<li>Developer attributes</li>
<li>Developers</li>
<li>Environment key-value map entries</li>
<li>Environment key-value maps</li>
<li>Exports</li>
<li>Flow hooks</li>
<li>Keystore aliases</li>
<li>Keystores</li>
<li>Queries</li>
<li>Rate plans</li>
<li>References</li>
<li>Shared flow revisions</li>
<li>Shared flows</li>
<li>Target servers</li>
<li>Trace (debug) sessions</li>
</ul></td>
</tr>
<tr class="even">
<td>Application Integration</td>
<td><ul>
<li>Auth configs</li>
<li>Executions</li>
<li>Integration versions</li>
<li>Integrations</li>
<li>Locations</li>
<li>Suspensions</li>
</ul></td>
</tr>
<tr class="odd">
<td>Apigee API Hub</td>
<td><ul>
<li>APIs</li>
<li>API operations</li>
<li>Definitions</li>
<li>Deployments</li>
<li>Specs</li>
<li>Versions</li>
</ul></td>
</tr>
<tr class="even">
<td>Backup and DR Service</td>
<td><ul>
<li>Backup vaults</li>
</ul></td>
</tr>
<tr class="odd">
<td>BigQuery</td>
<td><ul>
<li>Datasets</li>
<li>Models</li>
<li>Routines</li>
<li>Tables</li>
</ul></td>
</tr>
<tr class="even">
<td>BigQuery Reservation API</td>
<td><ul>
<li>Assignments</li>
<li>BI reservations</li>
<li>Capacity commitments</li>
<li>Locations</li>
<li>Reservations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Bigtable</td>
<td><ul>
<li>Clusters</li>
<li>Instances</li>
<li>Tables</li>
</ul></td>
</tr>
<tr class="even">
<td>Binary Authorization</td>
<td><ul>
<li>Attestors</li>
<li>Continuous Validation configs</li>
<li>Policies</li>
</ul></td>
</tr>
<tr class="odd">
<td>Customer Experience Agent Studio</td>
<td><ul>
<li>Apps</li>
<li>Operations</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Key Management Service</td>
<td><ul>
<li>Crypto key versions</li>
<li>Crypto keys</li>
<li>Key rings</li>
<li>Locations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Logging</td>
<td><ul>
<li>Log buckets</li>
<li>Log views</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud NGFW</td>
<td><ul>
<li>Address groups</li>
<li>Security Profile Groups</li>
<li>Security Profiles</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud SQL</td>
<td><ul>
<li>Backup runs</li>
<li>Instances</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Storage</td>
<td><ul>
<li>Buckets</li>
<li>Managed folders</li>
<li>Objects</li>
</ul></td>
</tr>
<tr class="odd">
<td>Compute Engine</td>
<td><ul>
<li>Backend services (global and regional)</li>
<li>Firewalls</li>
<li>Forwarding rules (global and regional)</li>
<li>Images</li>
<li>Instance templates</li>
<li>Instances</li>
<li>Persistent disks (regional and zonal)</li>
<li>Snapshots</li>
<li>Target HTTP(S) proxies (global and regional)</li>
<li>Target SSL proxies</li>
<li>Target TCP proxies</li>
</ul></td>
</tr>
<tr class="even">
<td>Dataform</td>
<td><ul>
<li>Compilation results</li>
<li>Locations</li>
<li>Release configs</li>
<li>Repositories</li>
<li>Workflow configs</li>
<li>Workflow invocations</li>
<li>Workspaces</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud DNS</td>
<td><ul>
<li>resource record sets</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud</td>
<td><ul>
<li>Locations <sup>1</sup></li>
</ul></td>
</tr>
<tr class="odd">
<td>Google Kubernetes Engine</td>
<td><ul>
<li>Clusters</li>
</ul></td>
</tr>
<tr class="even">
<td>Firestore</td>
<td><ul>
<li>Databases</li>
</ul></td>
</tr>
<tr class="odd">
<td>Identity-Aware Proxy</td>
<td><ul>
<li>All backend services and App Engine apps</li>
<li>All tunnel resources</li>
<li>All tunnel zones</li>
<li>All web services</li>
<li>App Engine app service versions</li>
<li>App Engine app services</li>
<li>Compute Engine backend services</li>
<li>Tunnel instances</li>
</ul></td>
</tr>
<tr class="even">
<td>Integration Connectors</td>
<td><ul>
<li>Connections</li>
<li>Connection schema metadata</li>
<li>Endpoint attachments</li>
<li>Event subscriptions</li>
<li>Managed zones</li>
</ul></td>
</tr>
<tr class="odd">
<td>Google Cloud Managed Service for Apache Kafka</td>
<td><ul>
<li>Clusters</li>
<li>Consumer groups</li>
<li>Operations</li>
<li>Topics</li>
</ul></td>
</tr>
<tr class="even">
<td>Parameter Manager</td>
<td><ul>
<li>Parameter versions</li>
<li>Parameters</li>
</ul></td>
</tr>
<tr class="odd">
<td>Pub/Sub Lite</td>
<td><ul>
<li>Locations</li>
<li>Subscriptions</li>
<li>Topics</li>
</ul></td>
</tr>
<tr class="even">
<td>Network Security Integration</td>
<td><ul>
<li>Intercept Deployment Groups</li>
<li>Intercept Deployments</li>
<li>Intercept Endpoint Groups</li>
<li>Intercept Endpoint Group Associations</li>
<li>Mirroring Deployment Groups</li>
<li>Mirroring Deployments</li>
<li>Mirroring Endpoint Groups</li>
<li>Mirroring Endpoint Group Associations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Resource Manager</td>
<td><ul>
<li>Projects</li>
</ul></td>
</tr>
<tr class="even">
<td>Secret Manager</td>
<td><ul>
<li>Secret versions</li>
<li>Secrets</li>
</ul></td>
</tr>
<tr class="odd">
<td>Spanner</td>
<td><ul>
<li>Backups</li>
<li>Databases</li>
<li>Instances</li>
</ul></td>
</tr>
</tbody>
</table>
<p><sup>1</sup> Cloud Key Management Service uses this resource type as the parent of key ring resources.</p></td>
</tr>
</tbody>
</table>

<span id="resourcename_attribute"></span>

### resource.name attribute

The `resource.name` attribute lets you set a condition based on all or part of a resource name. For a list of resource name formats, see [Resource name format](https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-name) .

The `resource.name` attribute is available only for specific resource types, which are listed in the table in this section. We strongly recommend that you limit the applicability of the condition to the intended resource type. If a role contains permissions for a resource type that does not provide the `resource.name` attribute, you should ensure that those permissions are not restricted by the part of the condition that checks `resource.name` .

The following example shows how to ensure this behavior. In this example, the condition allows access to all resource types except Cloud Storage buckets and objects. In contrast, for buckets and objects, the condition only allows access to the bucket `example-bucket` and the objects it contains:

    (resource.type != 'storage.googleapis.com/Bucket' &&
     resource.type != 'storage.googleapis.com/Object') ||
    resource.name.startsWith('projects/_/buckets/example-bucket')

Note that the first part of the condition checks whether the resource is neither a bucket nor an object. If the resource has a different type, then the entire condition evaluates to `true` , regardless of the resource name.

Also, note that the condition checks the `resource.type` attribute, not the `resource.service` attribute. There are a few benefits of checking the `resource.type` attribute:

  - It limits the `resource.name` check to the appropriate set of resources. For example, if you want to grant access to Compute Engine instances with a specific name, it makes sense to exclude all resource types other than Compute Engine instances.
  - It prevents the scope of the condition from changing if a service adds new resource types in the future.

Finally, note that the condition uses the `startsWith()` function to evaluate the resource name, rather than checking for equality with the `  ==  ` operator. Because the condition looks at the start of the resource name, it matches a bucket as well as the objects in that bucket. If it checked for equality, it would only match the bucket.

You cannot use wildcard characters such as `*` to match multiple resource names. Consider these alternatives:

  - Use the `extract()` function to extract a value from a resource name. For example, you can extract a project ID from the resource name of a Compute Engine VM instance, then write a condition expression that refers to the project ID.
    
    For details, see [Extracting values from attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#extract) on this page.

  - Use the `startsWith()` or `endsWith()` function to write a condition that evaluates the start or end of the resource name.

You can use the `resource.name` attribute in allow policy role bindings.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">resource.name</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><p><code dir="ltr" translate="no">string</code></p>
<p>Each resource type uses a specific format for the resource name. For a list of formats, see <a href="https://docs.cloud.google.com/iam/docs/conditions-resource-attributes#resource-name">Resource name format</a> .</p></td>
</tr>
<tr class="odd">
<td>Supported functions and operators</td>
<td><code dir="ltr" translate="no">startsWith(), endsWith(), extract(),           ==        ,           !=       </code></td>
</tr>
<tr class="even">
<td>Details</td>
<td><p>The <code dir="ltr" translate="no">resource.name</code> contains the <a href="https://docs.cloud.google.com/apis/design/resource_names#relative_resource_name"><em>relative resource name</em></a> for the target resource in the request. The relative resource name is a URI path without a leading forward slash ( <code dir="ltr" translate="no">/</code> ).</p>
<p>The <code dir="ltr" translate="no">startsWith()</code> function takes the prefix string literal to be evaluated against <code dir="ltr" translate="no">resource.name</code> .</p>
<p>The <code dir="ltr" translate="no">endsWith()</code> function takes the suffix string literal to be evaluated against <code dir="ltr" translate="no">resource.name</code> .</p>
<p>The <code dir="ltr" translate="no">extract()</code> function uses an extraction template to extract part of <code dir="ltr" translate="no">resource.name</code> . For details, see <a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#extract">Extracting values from resource names</a> on this page.</p>
<p>The <code dir="ltr" translate="no">           ==        </code> and <code dir="ltr" translate="no">           !=        </code> operators are for comparison with the entire <code dir="ltr" translate="no">resource.name</code> , or an extracted portion of the <code dir="ltr" translate="no">resource.name</code> .</p></td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> unless the resource name identifies a Cloud Storage bucket named <code dir="ltr" translate="no">secret-bucket-123</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.name != &quot;projects/_/buckets/secret-bucket-123&quot;</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the resource name starts with the specified prefix, in the format used by Compute Engine VM instances:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.name.startsWith(&quot;projects/project-123/zones/us-east1-b/instances/prod-&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the resource name starts with the specified prefix, in the format used by Cloud Storage buckets:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.name.startsWith(&quot;projects/_/buckets/my_bucket/objects/test-object-&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the resource name ends with the specified suffix—for example, the file extension of a Cloud Storage object:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.name.endsWith(&quot;.jpg&quot;)</code></pre>
<p>Returns the project name or number if it's present:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.name.extract(&quot;projects/{project}/&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td><table style="width:40%;">
<colgroup>
<col style="width: 40%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Apigee</td>
<td><ul>
<li>API product attributes</li>
<li>API products</li>
<li>API proxies</li>
<li>API proxy key-value map entries</li>
<li>API proxy key-value maps</li>
<li>API proxy revisions</li>
<li>Caches</li>
<li>Developer app attributes</li>
<li>Developer apps</li>
<li>Developer attributes</li>
<li>Developers</li>
<li>Environment key-value map entries</li>
<li>Environment key-value maps</li>
<li>Exports</li>
<li>Flow hooks</li>
<li>Keystore aliases</li>
<li>Keystores</li>
<li>Queries</li>
<li>Rate plans</li>
<li>References</li>
<li>Shared flow revisions</li>
<li>Shared flows</li>
<li>Target servers</li>
<li>Trace (debug) sessions</li>
</ul></td>
</tr>
<tr class="even">
<td>Application Integration</td>
<td><ul>
<li>Auth configs</li>
<li>Executions</li>
<li>Integration versions</li>
<li>Integrations</li>
<li>Locations</li>
<li>Suspensions</li>
</ul></td>
</tr>
<tr class="odd">
<td>Apigee API Hub</td>
<td><ul>
<li>APIs</li>
<li>API operations</li>
<li>Definitions</li>
<li>Deployments</li>
<li>Specs</li>
<li>Versions</li>
</ul></td>
</tr>
<tr class="even">
<td>Backup and DR Service</td>
<td><ul>
<li>Backup vaults</li>
</ul></td>
</tr>
<tr class="odd">
<td>BigQuery</td>
<td><ul>
<li>Datasets</li>
<li>Models</li>
<li>Routines</li>
<li>Tables</li>
</ul></td>
</tr>
<tr class="even">
<td>BigQuery Reservation API</td>
<td><ul>
<li>Assignments</li>
<li>BI reservations</li>
<li>Capacity commitments</li>
<li>Locations</li>
<li>Reservations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Bigtable</td>
<td><ul>
<li>Clusters</li>
<li>Instances</li>
<li>Tables</li>
</ul></td>
</tr>
<tr class="even">
<td>Binary Authorization</td>
<td><ul>
<li>Attestors</li>
<li>Continuous Validation configs</li>
<li>Policies</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Deploy</td>
<td><ul>
<li>Automation runs</li>
<li>Automations</li>
<li>Custom target types</li>
<li>Delivery pipelines</li>
<li>Job runs</li>
<li>Releases</li>
<li>Rollouts</li>
<li>Targets</li>
</ul></td>
</tr>
<tr class="even">
<td>Customer Experience Agent Studio</td>
<td><ul>
<li>Apps</li>
<li>Operations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Key Management Service</td>
<td><ul>
<li>Crypto keys</li>
<li>Crypto key versions</li>
<li>Key rings</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Logging</td>
<td><ul>
<li>Log buckets</li>
<li>Log views</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud NGFW</td>
<td><ul>
<li>Address groups</li>
<li>Security Profile Groups</li>
<li>Security Profiles</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud SQL</td>
<td><ul>
<li>Backup runs</li>
<li>Instances</li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Storage</td>
<td><ul>
<li>Buckets</li>
<li>Managed folders</li>
<li>Objects</li>
</ul></td>
</tr>
<tr class="even">
<td>Compute Engine</td>
<td><ul>
<li>Backend services (global and regional)</li>
<li>Firewalls</li>
<li>Forwarding rules (global and regional)</li>
<li>Images</li>
<li>Instance templates</li>
<li>Instances</li>
<li>Persistent disks (regional and zonal)</li>
<li>Snapshots</li>
<li>Target HTTP(S) proxies (global and regional)</li>
<li>Target SSL proxies</li>
<li>Target TCP proxies</li>
</ul></td>
</tr>
<tr class="odd">
<td>Google Kubernetes Engine</td>
<td><ul>
<li>Clusters</li>
</ul></td>
</tr>
<tr class="even">
<td>Firestore</td>
<td><ul>
<li>Databases</li>
</ul></td>
</tr>
<tr class="odd">
<td>Dataform</td>
<td><ul>
<li>Compilation results</li>
<li>Locations</li>
<li>Release configs</li>
<li>Repositories</li>
<li>Workflow configs</li>
<li>Workflow invocations</li>
<li>Workspaces</li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud DNS</td>
<td><ul>
<li>resource record sets</li>
</ul></td>
</tr>
<tr class="odd">
<td>Integration Connectors</td>
<td><ul>
<li>Connections</li>
<li>Connection schema metadata</li>
<li>Endpoint attachments</li>
<li>Event subscriptions</li>
<li>Managed zones</li>
</ul></td>
</tr>
<tr class="even">
<td>Google Cloud Managed Service for Apache Kafka</td>
<td><ul>
<li>Clusters</li>
<li>Consumer groups</li>
<li>Operations</li>
<li>Topics</li>
</ul></td>
</tr>
<tr class="odd">
<td>Parameter Manager</td>
<td><ul>
<li>Parameter versions</li>
<li>Parameters</li>
</ul></td>
</tr>
<tr class="even">
<td>Pub/Sub Lite</td>
<td><ul>
<li>Locations</li>
<li>Subscriptions</li>
<li>Topics</li>
</ul></td>
</tr>
<tr class="odd">
<td>Network Security Integration</td>
<td><ul>
<li>Intercept Deployment Groups</li>
<li>Intercept Deployments</li>
<li>Intercept Endpoint Groups</li>
<li>Intercept Endpoint Group Associations</li>
<li>Mirroring Deployment Groups</li>
<li>Mirroring Deployments</li>
<li>Mirroring Endpoint Groups</li>
<li>Mirroring Endpoint Group Associations</li>
</ul></td>
</tr>
<tr class="even">
<td>Secret Manager</td>
<td><ul>
<li>Secret versions</li>
<li>Secrets</li>
</ul></td>
</tr>
<tr class="odd">
<td>Spanner</td>
<td><ul>
<li>Backups</li>
<li>Databases</li>
<li>Instances</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

### Resource tags

The resource tag functions let you set a condition based on the tags that are attached to [supported resources](https://docs.cloud.google.com/resource-manager/docs/tags/tags-supported-services#supported_service_resources) or inherited by those resources' descendants. For example, you can set a condition that grants a role only for resources that have the tag `env: prod` attached. To learn more about controlling access with tags, see [Tags and access control](https://docs.cloud.google.com/iam/docs/tags-access-control) .

Each tag consists of a key and a value. There are a few different types of identifiers for each key and value:

  - A *permanent ID* , which is globally unique and can never be reused. For example, a tag key could have the permanent ID `tagKeys/123456789012` , and a tag value could have the permanent ID `tagValues/567890123456` .
  - A *short name* . The short name for each key must be unique within the project or organization under which the key is defined, and the short name for each value must be unique for its associated key. For example, a tag key could have the short name `env` , and a tag value could have the short name `prod` .
  - A *namespaced name* , which adds your organization's numeric ID or project's ID to the short name of a tag key. For example, a tag key created for an organization could have the namespaced name `123456789012/env` . To learn how to get your organization ID, see [Getting your organization resource ID](https://docs.cloud.google.com/resource-manager/docs/creating-managing-organization#retrieving_your_organization_id) . A tag key created for a project could have the namespaced name `myproject/env` . To learn how to get your project ID, see [Identifying projects](https://docs.cloud.google.com/resource-manager/docs/creating-managing-projects#identifying_projects) .

For guidance on choosing which type of identifier to use in your conditions, see [Tag definitions and identifiers](https://docs.cloud.google.com/iam/docs/tags-access-control#definitions) .

You can use tag-based conditions to conditionalize access to any resource. This includes resources with their own tags, as well as resources that inherit tags from other resources. To learn more about how tags are inherited through the resource hierarchy, see [Tag inheritance](https://docs.cloud.google.com/resource-manager/docs/tags/tags-overview#inheritance) .

However, certain areas of the Google Cloud console don't recognize allow policy role bindings with tag-based conditions. As a result, if you have a role with a tag-based condition, then the Google Cloud console might incorrectly prevent you from performing certain actions. If you encounter this issue, then use an alternate method, such as the gcloud CLI, to perform the action.

You can use tag-based conditions in the following:

  - Allow policy role bindings
  - Deny policy deny rules

You can use the following functions to set conditions based on tags:

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Function</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">resource.hasTagKey(  keyName: string  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the resource for the request has a tag with the specified key. The tag key is looked up by its <em>namespaced name</em> . To check for a tag key using its <em>permanent ID</em> , use the function <code dir="ltr" translate="no">resource.hasTagKeyId()</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">keyName</code> : The namespaced name of the tag key, with the organization's numeric ID and a forward slash as a prefix. For example, <code dir="ltr" translate="no">123456789012/env</code> .
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the resource for the request has a tag with the key <code dir="ltr" translate="no">env</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.hasTagKey(&#39;123456789012/env&#39;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">resource.hasTagKeyId(  keyId: string  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the resource for the request has a tag with the specified key. The tag key is looked up by its <em>permanent ID</em> . To check for a tag key using its <em>namespaced name</em> , use the function <code dir="ltr" translate="no">resource.hasTagKey()</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">keyId</code> : The permanent ID for the tag key. For example, <code dir="ltr" translate="no">tagKeys/123456789012</code> .
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the resource for the request has a tag with the key <code dir="ltr" translate="no">tagKeys/123456789012</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.hasTagKeyId(&#39;tagKeys/123456789012&#39;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">resource.matchTag(  keyName: string,  valueShortName: string  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the resource for the request has a tag with the specified key and value. The key is looked up by its <em>namespaced name</em> , and the value is looked up by its <em>short name</em> . To check for a tag key and value using their <em>permanent IDs</em> , use the function <code dir="ltr" translate="no">resource.matchTagId()</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><ul>
<li><code dir="ltr" translate="no">keyName</code> : The namespaced name for the tag key, with the organization's numeric ID and a forward slash as a prefix. For example, <code dir="ltr" translate="no">123456789012/env</code> .</li>
<li><code dir="ltr" translate="no">valueShortName</code> : The short name for the tag value. For example, <code dir="ltr" translate="no">prod</code> .</li>
</ul>
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the resource for the request has a tag with the key <code dir="ltr" translate="no">123456789012/env</code> and the value <code dir="ltr" translate="no">prod</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.matchTag(&#39;123456789012/env&#39;, &#39;prod&#39;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">resource.matchTagId(  keyId: string,  valueId: string  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the resource for the request has a tag with the specified key and value. The key and value are looked up by their <em>permanent IDs</em> . To check for a tag key using its <em>namespaced name</em> and a value using its <em>short name</em> , use the function <code dir="ltr" translate="no">resource.matchTag()</code> .</p>
<dl>
<dt>Parameters</dt>
<dd><ul>
<li><code dir="ltr" translate="no">keyId</code> : The permanent ID for the tag key. For example, <code dir="ltr" translate="no">tagKeys/123456789012</code> .</li>
<li><code dir="ltr" translate="no">valueId</code> : The permanent ID for the tag value. For example, <code dir="ltr" translate="no">tagValues/567890123456</code> .</li>
</ul>
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the resource for the request has a tag with the key <code dir="ltr" translate="no">tagKeys/123456789012</code> and the value <code dir="ltr" translate="no">tagValues/567890123456</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.matchTagId(&#39;tagKeys/123456789012&#39;, &#39;tagValues/567890123456&#39;)</code></pre>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## Principal attributes

The principal attributes let you write conditions based on the principal that issued the request. With these attributes, you can refine the principals that a policy is enforced for.

You can use principal attributes in policy bindings for principal access boundary policies.

### `principal.type` attribute

The `principal.type` attribute lets you set a condition based on the type of principal issuing the request. For example, you could add a condition to a policy binding for a principal access boundary policy to ensure that the policy is only enforced for service accounts.

You can use principal attributes in policy bindings for principal access boundary policies.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">principal.type</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><p><code dir="ltr" translate="no">string</code></p></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">          ==        ,           !=        , in</code></td>
</tr>
<tr class="even">
<td>Supported principal types</td>
<td><dl>
<dt>Google Accounts</dt>
<dd><code dir="ltr" translate="no">iam.googleapis.com/WorkspaceIdentity</code>
</dd>
<dt>Workforce identity pool identities</dt>
<dd><code dir="ltr" translate="no">iam.googleapis.com/WorkforcePoolIdentity</code>
</dd>
<dt>Workload identity pool identities</dt>
<dd><code dir="ltr" translate="no">iam.googleapis.com/WorkloadPoolIdentity</code>
</dd>
<dt>Service accounts</dt>
<dd><code dir="ltr" translate="no">iam.googleapis.com/ServiceAccount</code>
</dd>
<dt>Agent identity <a href="https://cloud.google.com/products/#product-launch-stages">(Preview)</a></dt>
<dd><code dir="ltr" translate="no">iam.googleapis.com/AgentPoolIdentity</code>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request is a service account:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.type == &quot;iam.googleapis.com/ServiceAccount&quot;
        </code></pre>
<p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request is an agent identity:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.type == &quot;iam.googleapis.com/AgentPoolIdentity&quot;
        </code></pre>
<p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request is a Google Workspace identity or workforce identity pool identity:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.type in [&quot;iam.googleapis.com/WorkspaceIdentity&quot;, &quot;iam.googleapis.com/WorkforcePoolIdentity&quot;]
        </code></pre></td>
</tr>
</tbody>
</table>

### `principal.subject` attribute

The `principal.subject` attribute lets you set a condition based on the principal issuing the request. For example, you could add a condition to a policy binding for a principal access boundary policy to ensure that the policy is only enforced for principals whose email addresses end with `@example.com` .

If you use the `principal.subject` attribute in a condition, we recommend also using the [`principal.type`](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principal-type) attribute to control which types of principals the condition applies to. This is because principal identifiers aren't necessarily unique across principal types. For example, the identifier `example-user@example.com` could identify a Google Account or a user in a workforce identity pool.

By using the `principal.type` attribute in addition to the `principal.subject` attribute, you can ensure that the condition only matches principals with the intended type. For example, the following expression matches Google Accounts whose email addresses end with `@example.com` :

    principal.type == 'iam.googleapis.com/WorkspaceIdentity' &&
    principal.subject.endsWith('@example.com')

> **Note:** Conditions with this attribute evaluate against a principal's primary email address only—they don't evaluate against a principal's aliases.

You can use principal attributes in policy bindings for principal access boundary policies.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">principal.subject</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><p><code dir="ltr" translate="no">string</code></p></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><p><code dir="ltr" translate="no">           ==         ,            !=         , in, startsWith(), endsWith()</code></p>
<blockquote>
Caution: The <code dir="ltr" translate="no">startsWith()</code> and <code dir="ltr" translate="no">endsWith()</code> functions match <em>all</em> principals that start with or end with the specified value. For example, the expression <code dir="ltr" translate="no">startsWith('security-admin')</code> matches <code dir="ltr" translate="no">security-admin@example.com</code> and <code dir="ltr" translate="no">security-admin@example-project.iam.gserviceaccount.com</code> , but also matches <code dir="ltr" translate="no">security-admin-fake@example.com</code> .
</blockquote></td>
</tr>
<tr class="even">
<td>Supported principal subjects</td>
<td><dl>
<dt>Google Accounts</dt>
<dd><p>Identifier: user's email address</p>
<p>Example: <code dir="ltr" translate="no">alex@example.com</code></p>
</dd>
<dt>Workforce identity pool identities</dt>
<dd><p>Identifier: identity's subject attribute value</p>
<p>Example: <code dir="ltr" translate="no">raha@altostrat.com</code></p>
</dd>
<dt>Workload identity pool identities</dt>
<dd><p>Identifier: identity's subject attribute value</p>
</dd>
<dt>Service accounts</dt>
<dd><p>Identifier: service account's email address</p>
<p>Example: <code dir="ltr" translate="no">my-service-account@my-project.iam.gserviceaccount.com</code></p>
</dd>
<dt>Agent identity <a href="https://cloud.google.com/products/#product-launch-stages">(Preview)</a></dt>
<dd><p>Identifier: the agent identity, starting with <code dir="ltr" translate="no">resources/</code></p>
<p>Example: <code dir="ltr" translate="no">resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent</code></p>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td>Example</td>
<td><p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request ends with <code dir="ltr" translate="no">@example.com</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.subject.endsWith(&quot;@example.com&quot;)
        </code></pre>
<p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request starts with <code dir="ltr" translate="no">resources/aiplatform</code> , which is true for agent identities that use the Vertex AI platform:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.subject.startsWith(&quot;resources/aiplatform/&quot;)
        </code></pre>
<p>Evaluates to <code dir="ltr" translate="no">true</code> if the principal in the request is <code dir="ltr" translate="no">example-service-account@example-project.iam.gserviceaccount.com</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>principal.subject == &quot;example-service-account@example-project.iam.gserviceaccount.com&quot;
        </code></pre></td>
</tr>
</tbody>
</table>

## Request attributes

Request attributes enable you to create conditions that evaluate details about the request, such as its access level, its date and time, the destination IP address and port (for IAP TCP tunneling), or the expected URL path/host (for IAP and Cloud Run).

### Access levels attribute

The access levels attribute enables users to set a condition requiring that a request meets one or more access levels in order to be authorized. You can use the access levels attribute in allow policy role bindings.

The access levels attribute is derived from attributes of the request, such as the origin IP address, device attributes, and the time of day. For example, an access level named `fullyTrusted` might require that the device making the request is owned by the company and has a screen lock. An `onNetwork` access level might require that the device making the request originates from a particular IP address range. See the [Access Context Manager](https://docs.cloud.google.com/access-context-manager/docs/overview#access-levels) documentation for more information about access levels.

The access levels attribute is available only when you use Identity-Aware Proxy either to access a tunnel instance or to access a web application that runs on App Engine or Compute Engine backend services. More specifically, the access levels attribute is available only for requests that check one of these permissions:

  - `iap.tunnelInstances.accessViaIAP`
  - `iap.webServiceVersions.accessViaIAP`

> **Warning:** If you use the access levels attribute in a role binding, then the binding must grant a role that contains only the `iap.tunnelInstances.accessViaIAP` and `iap.webServiceVersions.accessViaIAP` permissions. If the binding grants a role that contains other permissions, then these additional, unsupported permissions won't work correctly.

You can use the access levels attribute when you conditionally grant the following predefined roles:

  - IAP-secured Tunnel User ( `roles/iap.tunnelResourceAccessor` )
    
    Contains a single permission, `iap.tunnelInstances.accessViaIAP` .

  - IAP-secured Web App User ( `roles/iap.httpsResourceAccessor` )
    
    Contains a single permission, `iap.webServiceVersions.accessViaIAP` .

You can also use the access levels attribute to conditionally grant a custom role that contains these permissions. The custom role must not contain any other permissions.

<span id="requestauthaccess_levels_attribute"></span>

#### `request.auth.access_levels` attribute

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">request.auth.access_levels</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">list</code> &lt; <code dir="ltr" translate="no">string</code> &gt;</td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">in</code></td>
</tr>
<tr class="even">
<td>Details</td>
<td><p>To check whether a request meets a specific access level, use the <code dir="ltr" translate="no">in</code> operator:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>ACCESS_LEVEL_FULL_NAME in request.auth.access_levels</code></pre>
<p>The full name of an access level uses the following format:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>accessPolicies/POLICY_NUMBER/accessLevels/ACCESS_LEVEL</code></pre>
<blockquote>
<strong>Note:</strong> The access level is case sensitive, and it must match exactly what is configured in Access Context Manager. For example, if the condition uses <code dir="ltr" translate="no">accesslevels</code> , in all lowercase, rather than <code dir="ltr" translate="no">accessLevels</code> , with <code dir="ltr" translate="no">Levels</code> capitalized, then the access level in the request will never match the access level in the condition.
</blockquote></td>
</tr>
<tr class="odd">
<td>Example</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the request meets the <code dir="ltr" translate="no">CorpNet</code> access level:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>&quot;accessPolicies/199923665455/accessLevels/CorpNet&quot;
    in request.auth.access_levels</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td>Available for requests that use Identity-Aware Proxy to access a tunnel instance, tunnel destination group, web application running on Google Cloud load balancing, or web application running on App Engine.</td>
</tr>
</tbody>
</table>

### API attributes

API attributes help you manage access based on data provided by a specific Google Cloud API or service. You can use API attributes in allow policy role bindings.

For example, when you use Cloud Storage to [list the objects in a bucket](https://docs.cloud.google.com/storage/docs/json_api/v1/objects/list) , you can use the `prefix` parameter in the request to include only objects whose names begin with a specific prefix. If you use [Credential Access Boundaries](https://docs.cloud.google.com/iam/docs/downscoping-short-lived-credentials) to downscope short-lived credentials, you can create a Credential Access Boundary that limits permissions to list objects by checking the API attribute `storage.googleapis.com/objectListPrefix` . This API attribute contains the value of the `prefix` parameter from the request.

For examples of when you might need to use API attributes in a condition, see the following pages:

  - [Limit permissions when listing objects](https://docs.cloud.google.com/iam/docs/downscoping-short-lived-credentials#example-object-prefix)
  - [Setting limits on granting roles](https://docs.cloud.google.com/iam/docs/setting-limits-on-granting-roles)

Not all services recognize API attributes. The following sections indicate which services recognize each API attribute.

#### Functions for API attributes

You can use the following function to work with API attributes:

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Function</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">api.getAttribute(  attributeName: string,  defaultValue: V&lt;T&gt;  )</code> trending_flat <code dir="ltr" translate="no">V&lt;T&gt;</code></td>
<td><p>Gets the requested API attribute.</p>
<dl>
<dt>Parameters</dt>
<dd><ul>
<li><code dir="ltr" translate="no">attributeName</code> : The API attribute to get. For supported values, see <a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#api-attributes-storage">Cloud Storage API attributes</a> and <a href="https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#api-attributes-iam">IAM API attributes</a> on this page.</li>
<li><p><code dir="ltr" translate="no">defaultValue</code> : The default value ( <code dir="ltr" translate="no">V</code> ) to use if the API attribute is not available. The value <code dir="ltr" translate="no">V</code> is of type <code dir="ltr" translate="no">T</code> , where <code dir="ltr" translate="no">T</code> is the same type as the API attribute's value. For example, if the API attribute's value is a string, you can use an empty string, or a placeholder string such as <code dir="ltr" translate="no">undefined</code> .</p>
<blockquote>
<strong>Note:</strong> For the API attribute <code dir="ltr" translate="no">iam.googleapis.com/modifiedGrantsByRole</code> , the default value must be an empty list ( <code dir="ltr" translate="no">[]</code> ).
</blockquote></li>
</ul>
</dd>
<dt>Example</dt>
<dd><p>Returns one of the following:</p>
<ul>
<li>For requests to grant or revoke a role, returns a list of roles that were modified by the request.</li>
<li>For all other types of requests, returns an empty list.</li>
</ul>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>api.getAttribute(&quot;iam.googleapis.com/modifiedGrantsByRole&quot;, [])</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">hasOnly(  items: list&lt;T&gt;  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks that a list contains only the allowed items, or a subset of those items. You can call the function on a list returned by <code dir="ltr" translate="no">api.getAttribute()</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">items</code> : A list of items with type <code dir="ltr" translate="no">T</code> . Each item is a value that the API attribute is allowed to contain.
</dd>
<dt>Example</dt>
<dd><p>Checks whether the request would grant or revoke any roles other than Pub/Sub Editor ( <code dir="ltr" translate="no">roles/pubsub.editor</code> ) or Pub/Sub Publisher ( <code dir="ltr" translate="no">roles/pubsub.publisher</code> ):</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>api.getAttribute(&#39;iam.googleapis.com/modifiedGrantsByRole&#39;, [])
    .hasOnly([&#39;roles/pubsub.editor&#39;, &#39;roles/pubsub.publisher&#39;])</code></pre>
<p>The following shows the result for different request values:</p>
<table style="width:50%;">
<colgroup>
<col style="width: 50%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Granted/revoked roles</th>
<th>Result</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>None</td>
<td><p><code dir="ltr" translate="no">true</code></p>
<p>If no roles are modified, then <code dir="ltr" translate="no">api.getAttribute()</code> returns the default value. For this attribute, the default value is always an empty list. By definition, an empty list does not contain values that are not on the allowlist.</p></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">roles/pubsub.editor</code></td>
<td><p><code dir="ltr" translate="no">true</code></p>
<p>The role is on the allowlist.</p></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">roles/pubsub.editor</code><br />
<code dir="ltr" translate="no">roles/pubsub.publisher</code></td>
<td><p><code dir="ltr" translate="no">true</code></p>
<p>Both roles are on the allowlist.</p></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">roles/billing.admin</code></td>
<td><p><code dir="ltr" translate="no">false</code></p>
<p>The role is not on the allowlist.</p></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">roles/billing.admin</code><br />
<code dir="ltr" translate="no">roles/pubsub.editor</code></td>
<td><p><code dir="ltr" translate="no">false</code></p>
<p>One role is on the allowlist, but the other is not.</p></td>
</tr>
</tbody>
</table>
</dd>
</dl></td>
</tr>
</tbody>
</table>

#### Cloud Storage API attributes

Cloud Storage provides the following API attribute.

> **Warning:** API attributes for Cloud Storage are supported only in [Credential Access Boundaries](https://docs.cloud.google.com/iam/docs/downscoping-short-lived-credentials) . If you use Cloud Storage API attributes in a conditional role binding, then Cloud Storage methods will work incorrectly and fail unexpectedly. In addition, it might take longer to check IAM permissions when you access Cloud Storage.

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">storage.googleapis.com/objectListPrefix</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">string</code></td>
</tr>
<tr class="odd">
<td>Details</td>
<td><p>For a request to <a href="https://docs.cloud.google.com/storage/docs/json_api/v1/objects/list">list objects in a bucket</a> , contains the value of the <code dir="ltr" translate="no">prefix</code> parameter from the request. If the request omits the <code dir="ltr" translate="no">prefix</code> parameter, the attribute is not defined.</p>
<p>For other types of requests, the attribute is not defined.</p></td>
</tr>
<tr class="even">
<td>Services that recognize this attribute</td>
<td>Cloud Storage</td>
</tr>
</tbody>
</table>

#### IAM API attributes

IAM provides the following API attribute:

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">iam.googleapis.com/modifiedGrantsByRole</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">list&lt;string&gt;</code></td>
</tr>
<tr class="odd">
<td>Details</td>
<td><p>For a request to <a href="https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access#policy-overview">set the allow policy</a> of a resource, this attribute contains the role names from the role bindings that the request modifies.</p>
<p>For other types of requests, the attribute is not defined.</p></td>
</tr>
<tr class="even">
<td>Resource types that accept this attribute</td>
<td><p>The following resource types accept conditions with the <code dir="ltr" translate="no">modifiedGrantsByRole</code> attribute in their allow policies:</p>
<ul>
<li>Projects</li>
<li>Folders</li>
<li>Organizations</li>
</ul></td>
</tr>
<tr class="odd">
<td>Services that recognize this attribute</td>
<td><p>The following services recognize the <code dir="ltr" translate="no">modifiedGrantsByRole</code> attribute:</p>
<blockquote>
<p><strong>Caution:</strong> If a service does not recognize the <code dir="ltr" translate="no">modifiedGrantsByRole</code> attribute, you cannot <a href="https://docs.cloud.google.com/iam/docs/setting-limits-on-granting-roles">limit an IAM admin's ability to grant roles</a> for that service. If a limited IAM admin tries to grant a role on a resource, and the resource's service does not recognize the <code dir="ltr" translate="no">modifiedGrantsByRole</code> attribute, then the request fails.</p>
<p>The exception to this behavior is <a href="https://docs.cloud.google.com/bigquery/docs/reference/rest/v2/datasets">BigQuery datasets</a> . Datasets don't recognize the <code dir="ltr" translate="no">modifiedGrantsByRole</code> attribute, but limited IAM admins can still grant or revoke roles on datasets. Specifically, if a limited IAM admin's role includes permissions to grant roles on datasets, <strong>they can do so</strong> , regardless of any limits placed on their role granting.</p>
</blockquote>
<ul>
<li>API Gateway</li>
<li>AutoML</li>
<li>Certificate Authority Service</li>
<li>Cloud Run functions</li>
<li>Cloud Healthcare API</li>
<li>Cloud Key Management Service</li>
<li>Cloud Run</li>
<li>Cloud Runtime Configuration API</li>
<li>Cloud Storage</li>
<li>Compute Engine</li>
<li>Artifact Analysis</li>
<li>Managed Service for Apache Spark</li>
<li>Earth Engine</li>
<li>Game Servers</li>
<li>Identity and Access Management</li>
<li>Identity-Aware Proxy</li>
<li>Managed Service for Microsoft Active Directory</li>
<li>User-managed notebooks</li>
<li>Resource Manager</li>
<li>Secret Manager</li>
<li>Service Management</li>
</ul></td>
</tr>
</tbody>
</table>

#### Vertex AI Agent Engine API attributes

Vertex AI Agent Engine provides the following API attributes for its [Memory Bank](https://docs.cloud.google.com/agent-builder/agent-engine/memory-bank/overview) and [Session](https://docs.cloud.google.com/agent-builder/agent-engine/sessions/overview) context management services:

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">aiplatform.googleapis.com/memoryScope</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">map&lt;string, string&gt;</code></td>
</tr>
<tr class="odd">
<td>Details</td>
<td><p>For a request that accesses or modifies <a href="https://docs.cloud.google.com/agent-builder/agent-engine/memory-bank/overview">Memory Bank</a> resources, contains the value of the <code dir="ltr" translate="no">scope</code> field within the Memory.</p>
<p>For other types of requests, the attribute is not defined.</p></td>
</tr>
<tr class="even">
<td>Services that recognize this attribute</td>
<td>Vertex AI Agent Engine</td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">aiplatform.googleapis.com/sessionUserId</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">string</code></td>
</tr>
<tr class="odd">
<td>Details</td>
<td><p>For a request that accesses or modifies <a href="https://docs.cloud.google.com/agent-builder/agent-engine/sessions/overview">Session</a> resources, contains the value of the <code dir="ltr" translate="no">user_id</code> field within the Session.</p>
<p>For other types of requests, the attribute is not defined.</p></td>
</tr>
<tr class="even">
<td>Services that recognize this attribute</td>
<td>Vertex AI Agent Engine</td>
</tr>
</tbody>
</table>

### Date/time attribute

The date/time attribute is used to set expirable, scheduled, or limited-duration access to Google Cloud resources. You can use date/time attributes in allow policy role bindings.

This attribute is supported for all Google Cloud services and resource types. To learn how to apply date/time conditions to resources that don't directly support them, see [Support for inherited conditions](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#inherited-support) on this page.

The `request.time` attribute contains the timestamp for the request. You can compare this timestamp to another timestamp, or to a duration of time.

The following sections list the functions that you can use to set conditions based on timestamps and durations.

#### Create, compare, and modify timestamps and durations

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Function or operator</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">date(  value: string  )</code> trending_flat <code dir="ltr" translate="no">Timestamp</code></td>
<td><p>Converts a date from a <code dir="ltr" translate="no">string</code> to a <code dir="ltr" translate="no">         Timestamp        </code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">value</code> : A date in the format <code dir="ltr" translate="no">YYYY-MM-DD</code> , where <code dir="ltr" translate="no">YYYY</code> is the year, <code dir="ltr" translate="no">MM</code> is the two-digit month, and <code dir="ltr" translate="no">DD</code> is the two-digit day. The resulting <code dir="ltr" translate="no">Timestamp</code> contains the specified date and the time <code dir="ltr" translate="no">00:00:00.000 UTC</code> .
</dd>
<dt>Example</dt>
<dd><p>Creates a <code dir="ltr" translate="no">Timestamp</code> that represents the date <code dir="ltr" translate="no">2023-02-01</code> and the time <code dir="ltr" translate="no">00:00:00.000 UTC</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>date(&quot;2023-02-01&quot;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">duration(  value: string  )</code> trending_flat <code dir="ltr" translate="no">        Duration       </code></td>
<td><p>Converts an amount of time from a <code dir="ltr" translate="no">string</code> to a <code dir="ltr" translate="no">         Duration        </code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">value</code> : A <code dir="ltr" translate="no">Duration</code> in seconds, followed by <code dir="ltr" translate="no">s</code> .
</dd>
<dt>Examples</dt>
<dd><p>Creates a duration that represents 1.5 minutes:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>duration(&quot;90s&quot;)</code></pre>
<p>Creates a duration that represents 30 days:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>duration(&quot;2592000s&quot;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">timestamp(  value: string  )</code> trending_flat <code dir="ltr" translate="no">Timestamp</code></td>
<td><p>Converts a <code dir="ltr" translate="no">string</code> to a <code dir="ltr" translate="no">         Timestamp        </code> .</p>
<dl>
<dt>Parameter</dt>
<dd><p><code dir="ltr" translate="no">value</code> : A UTC timestamp that complies with <a href="https://tools.ietf.org/html/rfc3339">RFC 3339</a> .</p>
<blockquote>
<strong>Important:</strong> If the input parameter is invalid, then the condition will never allow access to any resource.
</blockquote>
</dd>
<dt>Example</dt>
<dd><p>Creates a timestamp that represents April 12, 2023, at 23:20:50.52 in UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>timestamp(&quot;2023-04-12T23:20:50.52Z&quot;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">          &lt;        ,           &lt;=        ,           &gt;        ,           &gt;=       </code></td>
<td><p>Compares two <code dir="ltr" translate="no">         Timestamp        </code> values.</p>
<blockquote>
<strong>Note:</strong> Avoid using the equality ( <code dir="ltr" translate="no">         ==        </code> ) and inequality ( <code dir="ltr" translate="no">         !=        </code> ) operators to compare timestamps. Timestamps have millisecond precision, so it's typically not useful to check for exact matches or mismatches.
</blockquote>
<dl>
<dt>Examples</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request time is <em>before</em> April 12, 2022, at 00:00:00 UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time &lt; timestamp(&quot;2022-04-12T00:00:00.00Z&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request time is <em>before or equal to</em> April 12, 2022, at 00:00:00 UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time &lt;= timestamp(&quot;2022-04-12T00:00:00.00Z&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request time is <em>after</em> April 12, 2022, at 00:00:00 UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time &gt; timestamp(&quot;2022-04-12T00:00:00.00Z&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request time is <em>after or equal to</em> April 12, 2022, at 00:00:00 UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time &gt;= timestamp(&quot;2022-04-12T00:00:00.00Z&quot;)</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><ul>
<li><code dir="ltr" translate="no">timestamp + duration</code> trending_flat <code dir="ltr" translate="no">Timestamp</code></li>
<li><code dir="ltr" translate="no">timestamp - duration</code> trending_flat <code dir="ltr" translate="no">Timestamp</code></li>
</ul></td>
<td><p>Add or subtract a <code dir="ltr" translate="no">         Duration        </code> from a <code dir="ltr" translate="no">         Timestamp        </code> .</p>
<dl>
<dt>Examples</dt>
<dd><p>Returns the <code dir="ltr" translate="no">Timestamp</code> that falls 30 minutes after 14:30:00 UTC on 2024-04-12:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>timestamp(&quot;2024-04-12T14:30:00.00Z&quot;) + duration(&quot;1800s&quot;)</code></pre>
<p>Returns the <code dir="ltr" translate="no">Timestamp</code> that falls 60 days before 14:30:00 UTC on 2024-04-12:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>timestamp(&quot;2024-04-12T14:30:00.00Z&quot;) - duration(&quot;5184000s&quot;)</code></pre>
</dd>
</dl></td>
</tr>
</tbody>
</table>

#### Extract information from a timestamp

The functions in this section let you extract information from a timestamp, such as the day of the week that the timestamp falls on.

In IAM Conditions, all timestamps are in UTC. However, you might want to extract information based on a different time zone. For example, you might want to know whether a UTC timestamp falls on a Monday in the time zone for Berlin, Germany.

To specify a different time zone, pass the time zone into the function. Use a name or UTC offset from the [IETF Time Zone Database](https://wikipedia.org/wiki/List_of_tz_database_time_zones) . For example, you could use `Europe/Berlin` or `+01:00` for Central European Time (CET).

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Supported functions and operators</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">Timestamp.getDate(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the day of the month from the <code dir="ltr" translate="no">Timestamp</code> . The value uses one-based indexing; the first day of the month is <code dir="ltr" translate="no">1</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent after the 15th day of the month in UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getDate() &gt; 15</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">Timestamp.getDayOfMonth(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the day of the month from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; the first day of the month is <code dir="ltr" translate="no">0</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent after the 15th day of the month in UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getDayOfMonth() &gt; 14</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">Timestamp.getDayOfWeek(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the day of the week from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; for example, Sunday is <code dir="ltr" translate="no">0</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent between Monday and Friday in Berlin, Germany:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getDayOfWeek(&quot;Europe/Berlin&quot;) &gt; 0 &amp;&amp;
    request.time.getDayOfWeek(&quot;Europe/Berlin&quot;) &lt; 6</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">Timestamp.getDayOfYear(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the day of the year from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; the first day of the year is <code dir="ltr" translate="no">0</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent during the first 5 days of the year in Mountain View, California:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getDayOfYear(&quot;America/Los_Angeles&quot;) &gt;= 0 &amp;&amp;
    request.time.getDayOfYear(&quot;America/Los_Angeles&quot;) &lt; 5</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">Timestamp.getFullYear(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the year from the <code dir="ltr" translate="no">         Timestamp        </code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent during the year 2023 in Mountain View, California:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getFullYear(&quot;America/Los_Angeles&quot;) == 2023</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request is sent during the year 2022 in UTC:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getFullYear() == 2022</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">Timestamp.getHours(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the hour of the day from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; values range from <code dir="ltr" translate="no">0</code> to <code dir="ltr" translate="no">23</code> .</p>
<p>You can combine this function with <code dir="ltr" translate="no">getDayofWeek()</code> to grant access only during the permitted working hours in your jurisdiction.</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent between 09:00 (9:00 AM) and 17:00 (5:00 PM) on a weekday in Berlin, Germany:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getDayOfWeek(&quot;Europe/Berlin&quot;) &gt;= 1 &amp;&amp;
    request.time.getDayOfWeek(&quot;Europe/Berlin&quot;) &lt;= 5 &amp;&amp;
    request.time.getHours(&quot;Europe/Berlin&quot;) &gt;= 9 &amp;&amp;
    request.time.getHours(&quot;Europe/Berlin&quot;) &lt;= 17</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">Timestamp.getMilliseconds(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the number of milliseconds from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; values range from <code dir="ltr" translate="no">0</code> to <code dir="ltr" translate="no">999</code> .</p>
<blockquote>
<strong>Note:</strong> In general, when you use IAM Conditions, you won't need to evaluate timestamps with this level of precision.
</blockquote>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">Timestamp.getMinutes(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the number of minutes after the hour from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; values range from <code dir="ltr" translate="no">0</code> to <code dir="ltr" translate="no">59</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent at or after 09:30 (9:30 AM) in Berlin, Germany:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getHours(&quot;Europe/Berlin&quot;) &gt;= 9 &amp;&amp;
    request.time.getMinutes(&quot;Europe/Berlin&quot;) &gt;= 30</code></pre>
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">Timestamp.getMonth(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the month of the year from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; values range from <code dir="ltr" translate="no">0</code> to <code dir="ltr" translate="no">11</code> .</p>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
<dt>Example</dt>
<dd><p>Returns <code dir="ltr" translate="no">true</code> if the request is sent during the month of April in Mountain View, California:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.time.getMonth(&quot;America/Los_Angeles&quot;) == 3</code></pre>
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">Timestamp.getSeconds(  timeZone: string  )</code> trending_flat <code dir="ltr" translate="no">int</code></td>
<td><p>Gets the number of seconds from the <code dir="ltr" translate="no">         Timestamp        </code> . The value uses zero-based indexing; values range from <code dir="ltr" translate="no">0</code> to <code dir="ltr" translate="no">59</code> .</p>
<blockquote>
<strong>Note:</strong> In general, when you use IAM Conditions, you won't need to evaluate timestamps with this level of precision.
</blockquote>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">timeZone</code> : The time zone for which to calculate the result. Defaults to UTC.
</dd>
</dl></td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">          &lt;        ,           &lt;=        ,           &gt;        ,           &gt;=,                   ==                ,                   !=        </code></td>
<td><p>Compares the output of two functions in this table.</p></td>
</tr>
</tbody>
</table>

### Destination IP/port attributes

The destination IP/port attribute enables users to manage access based on the internal destination IP address and port for a request. You can use destination IP/port attributes in allow policy role bindings.

For example, a Compute Engine VM instance might map the external IP address and port `132.168.42.21:3001` to the internal IP address and port `10.0.0.1:2300` for general usage. In contrast, the internal IP address and port `10.0.0.1:22` might only be available internally for administrative usage. You can use the destination IP/port attributes to grant different amounts of access based on the internal IP address and port.

For more information about TCP forwarding, see the [Identity-Aware Proxy documentation](https://docs.cloud.google.com/iap/docs/tcp-forwarding-overview) .

<span id="destinationip_attribute"></span>

#### destination.ip attribute

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">destination.ip</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">string</code></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">          ==        ,           !=       </code></td>
</tr>
<tr class="even">
<td>Details</td>
<td><p>The variable <code dir="ltr" translate="no">destination.ip</code> identifies an internal IP address in IPv4 format.</p>
<blockquote>
<strong>Note:</strong> We don't recommend using the <code dir="ltr" translate="no">startsWith()</code> and <code dir="ltr" translate="no">endsWith()</code> functions with the <code dir="ltr" translate="no">destination.ip</code> attribute. These functions might give you unexpected results. In particular, we don't recommend matching a prefix in <code dir="ltr" translate="no">destination.ip</code> to check a CIDR address range.
</blockquote></td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the destination IP address is <code dir="ltr" translate="no">10.0.0.1</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>destination.ip == &quot;10.0.0.1&quot;</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> unless the destination IP address is <code dir="ltr" translate="no">10.0.0.1</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>destination.ip != &quot;10.0.0.1&quot;</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td>Available for requests that use Identity-Aware Proxy to access a tunnel instance</td>
</tr>
</tbody>
</table>

<span id="destinationport_attribute"></span>

#### destination.port attribute

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">destination.port</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">int</code></td>
</tr>
<tr class="odd">
<td>Supported operators</td>
<td><code dir="ltr" translate="no">          ==        ,           !=        ,           &lt;        ,           &lt;=        ,           &gt;        ,           &gt;=       </code></td>
</tr>
<tr class="even">
<td>Details</td>
<td><p>The variable <code dir="ltr" translate="no">destination.port</code> identifies an internal TCP port number.</p></td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the destination port is <code dir="ltr" translate="no">21</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>destination.port == 21</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the destination port is less than <code dir="ltr" translate="no">3001</code> :</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>destination.port &lt; 3001</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td>Available for requests that use Identity-Aware Proxy to access a tunnel instance</td>
</tr>
</tbody>
</table>

### Forwarding rule attributes

The forwarding rule attributes enable you to specify the types of [forwarding rules](https://docs.cloud.google.com/load-balancing/docs/forwarding-rule-concepts) that a principal can create. For example, you could allow a principal to create forwarding rules for [internal Google Cloud load balancers](https://docs.cloud.google.com/load-balancing/docs/load-balancing-overview#types-of-cloud-load-balancing) , which handle traffic that originates inside a Google Cloud network, but not for external Google Cloud load balancers, which handle traffic that originates from the internet. You can use forwarding rule attributes in allow policy role bindings.

For Cloud Load Balancing, the forwarding rule attributes don't affect the ability to create other components of a Google Cloud load balancer, such as backend services, target proxies, health checks, and URL maps.

> **Note:** In the Google Cloud console, if you want to include the forwarding rule attributes in a condition expression, you must use the Condition editor. The forwarding rule attributes are not available in the Condition builder.

#### Supported functions

<table style="width:30%;">
<colgroup>
<col style="width: 30%" />
<col style="width: 0%" />
</colgroup>
<thead>
<tr class="header">
<th>Function</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">compute.isForwardingRule  CreationOperation()</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the request is creating a <a href="https://docs.cloud.google.com/load-balancing/docs/forwarding-rule-concepts">forwarding rule</a> .</p>
<dl>
<dt>Example</dt>
<dd>See the example for <code dir="ltr" translate="no">compute.matchLoadBalancingSchemes()</code> .
</dd>
</dl></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">compute.matchLoad  BalancingSchemes(  schemes: list&lt;string&gt;  )</code> trending_flat <code dir="ltr" translate="no">bool</code></td>
<td><p>Checks whether the request affects one of the specified types of load balancing scheme. To find the identifier for each load balancing scheme, as well as more details, see <a href="https://docs.cloud.google.com/load-balancing/docs/access-control/iam-conditions#conditions-iam">Using IAM Conditions on Google Cloud load balancers</a> .</p>
<blockquote>
<strong>Note:</strong> In general, if you use this function in a condition expression, you should also use <code dir="ltr" translate="no">compute.isForwardingRuleCreationOperation()</code> . See the examples in this cell for details.
</blockquote>
<dl>
<dt>Parameter</dt>
<dd><code dir="ltr" translate="no">schemes</code> : The load balancing schemes that the request is allowed to affect.
</dd>
<dt>Example</dt>
<dd><p>Returns one of the following:</p>
<ul>
<li>If the request <em>is not</em> creating a forwarding rule, returns <code dir="ltr" translate="no">true</code> .</li>
<li>If the request <em>is</em> creating a forwarding rule, returns <code dir="ltr" translate="no">true</code> only if the forwarding rule affects an <code dir="ltr" translate="no">INTERNAL</code> , <code dir="ltr" translate="no">INTERNAL_MANAGED</code> , or <code dir="ltr" translate="no">INTERNAL_SELF_MANAGED</code> load balancing scheme.</li>
</ul>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>!compute.isForwardingRuleCreationOperation() || (
  compute.isForwardingRuleCreationOperation() &amp;&amp;
  compute.matchLoadBalancingSchemes([
    &#39;INTERNAL&#39;, &#39;INTERNAL_MANAGED&#39;, &#39;INTERNAL_SELF_MANAGED&#39;
  ])
)</code></pre>
</dd>
</dl></td>
</tr>
</tbody>
</table>

#### Supported resource types

This attribute is available for requests to create the following resource types:

| Service                         | Resource types                                                                                                      |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Cloud Load Balancing            | Forwarding rules                                                                                                    |
| Cloud VPN                       | Forwarding rules (global and regional)                                                                              |
| Compute Engine                  | Forwarding rules (for [protocol forwarding)](https://docs.cloud.google.com/load-balancing/docs/protocol-forwarding) |
| Cloud Service Mesh <sup>1</sup> | Forwarding rules                                                                                                    |

<sup>1</sup> Uses the [resource attributes](https://docs.cloud.google.com/iam/docs/conditions-resource-attributes) for Compute Engine.

### URL path/host attribute

The URL path/host attribute enables users to manage access based on the URL path and host of a request. For example, a condition could specify that `https://example.com` is the main application accessible by a general domain of users, while `https://hr.example.com/admin` is used to access a page in the application where only Human Resources admins can access this portion.

You can use the URL path/host attribute in allow policy role bindings.

<span id="requestpath_attribute"></span>

#### request.path attribute

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">request.path</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">string</code></td>
</tr>
<tr class="odd">
<td>Supported functions and operators</td>
<td><code dir="ltr" translate="no">          ==        , startsWith(), endsWith()</code></td>
</tr>
<tr class="even">
<td>Details</td>
<td>We don't recommend using the <code dir="ltr" translate="no">          !=       </code> operator with this attribute. Instead of checking for inequality, as in <code dir="ltr" translate="no">request.path != "/admin"</code> , check the attribute's prefix, as in <code dir="ltr" translate="no">!request.path.startsWith("/admin")</code> . By checking the prefix, you also protect URL paths within the <code dir="ltr" translate="no">/admin</code> hierarchy, such as <code dir="ltr" translate="no">/admin/payroll/</code> .</td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the request path is equal to the specified URL path:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.path == &quot;/admin&quot;</code></pre>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.path == &quot;/admin/payroll&quot;</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request path starts with the specified URL path:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.path.startsWith(&quot;/admin&quot;)</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the request path ends with the specified URL path:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.path.endsWith(&quot;/payroll.js&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td><ul>
<li>Identity-Aware Proxy app service versions (App Engine): Available for requests that use Identity-Aware Proxy to access a web application running on App Engine or Compute Engine</li>
<li>Cloud Run services</li>
</ul></td>
</tr>
</tbody>
</table>

<span id="requesthost_attribute"></span>

#### request.host attribute

<table style="width:25%;">
<colgroup>
<col style="width: 25%" />
<col style="width: 0%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Attribute variable</td>
<td><code dir="ltr" translate="no">request.host</code></td>
</tr>
<tr class="even">
<td>Attribute type</td>
<td><code dir="ltr" translate="no">string</code></td>
</tr>
<tr class="odd">
<td>Supported functions and operators</td>
<td><code dir="ltr" translate="no">          ==        , endsWith()</code></td>
</tr>
<tr class="even">
<td>Details</td>
<td>We don't recommend using the <code dir="ltr" translate="no">.startsWith()</code> function or the <code dir="ltr" translate="no">          !=       </code> operator with this attribute. These functions and operators might give you unexpected results.</td>
</tr>
<tr class="odd">
<td>Examples</td>
<td><p>Returns <code dir="ltr" translate="no">true</code> if the hostname is equal to the specified value:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.host == &quot;www.example.com&quot;</code></pre>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.host == &quot;hr.example.com&quot;</code></pre>
<p>Returns <code dir="ltr" translate="no">true</code> if the hostname ends with the specified value:</p>
<pre dir="ltr" data-is-upgraded="" translate="no"><code>request.host.endsWith(&quot;example.com&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Supported resource types</td>
<td><ul>
<li>Identity-Aware Proxy app service versions (App Engine): Available for requests that use Identity-Aware Proxy to access an app service version.</li>
<li>Cloud Run services</li>
</ul></td>
</tr>
</tbody>
</table>

## Extract values from attributes

You can use the `extract()` function to extract a value from an attribute. For example, you can extract an arbitrary part of a resource name, then write a condition expression that refers to the text you extracted.

To use the `extract()` function, you provide an *extraction template* , which specifies the part of the attribute to extract. For example, if you want to extract a project ID from the resource name of a Compute Engine VM instance, you might use the template `projects/{project}/` .

An extraction template contains the following parts:

  - An *identifier* , enclosed in curly braces, that identifies the substring to extract.
    
    Choose a short, meaningful identifier that makes it clear what value you want to extract. You can use uppercase and lowercase letters from `A` to `Z` ; numeric digits; and underscores ( `_` ).
    
    In the template `projects/{project}/` , the identifier is `project` .

  - Optional: A *prefix* , which must appear before the substring to extract.
    
    In the template `projects/{project}/` , the prefix is `projects/` .

  - Optional: A *suffix* , which must appear after the substring to extract.
    
    In the template `projects/{project}/` , the suffix is `/` .

The `extract()` function extracts different parts of the attribute based on whether the extraction template has a prefix, a suffix, or both:

| Has prefix | Has suffix | Extracted value                                                                                                                                                                              |
| ---------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| —          | —          | The entire attribute                                                                                                                                                                         |
| check      | —          | The characters after the first occurrence of the prefix, or an empty string if there are no characters after the prefix                                                                      |
| —          | check      | The characters before the first occurrence of the suffix, or an empty string if there are no characters before the suffix                                                                    |
| check      | check      | The characters between the first occurrence of the prefix and the first subsequent occurrence of the suffix, or an empty string if there are no characters between the prefix and the suffix |

If you specify a prefix or suffix that don't appear in the attribute, or if the suffix appears only before the prefix, the `extract()` function returns an empty string.

The following examples show the output from several different extraction templates. These examples refer to a resource name for a Cloud Storage object, `projects/_/buckets/acme-orders-aaa/objects/data_lake/orders/ order_date=2019-11-03/aef87g87ae0876` :

| Extraction template                              | Output                                                                                               |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `/order_date={date}/`                            | `2019-11-03`                                                                                         |
| `buckets/{name}/`                                | `acme-orders-aaa`                                                                                    |
| `/orders/{empty}order_date`                      | Empty `string`                                                                                       |
| `{start}/objects/data_lake`                      | `projects/_/buckets/acme-orders-aaa`                                                                 |
| `orders/{end}`                                   | `order_date=2019-11-03/aef87g87ae0876`                                                               |
| `{all}`                                          | `projects/_/buckets/acme-orders-aaa/objects/data_lake/orders/  order_date=2019-11-03/aef87g87ae0876` |
| `/orders/{none}/order_date=`                     | Empty `string`                                                                                       |
| `/orders/order_date=2019-11-03/  {id}/data_lake` | Empty `string`                                                                                       |

If you extract a string that represents a date, you can use the [date/time functions and operators](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#date-time) on this page to convert the extracted value to a `  Timestamp  ` . For examples, see [Configuring resource-based access](https://docs.cloud.google.com/iam/docs/configuring-resource-based-access#extract-values) .
