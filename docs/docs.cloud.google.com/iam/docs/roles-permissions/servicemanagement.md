---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement
title: Service Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Management roles

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
<td><h4 id="servicemanagement.admin" class="role-title add-link" data-text="Service Management Administrator" tabindex="-1">Service Management Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p>Full control of Google Service Management resources.</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  consumers.  get</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  get</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  update</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  addResource</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  create</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  delete</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  removeResource</code></li>
</ul>
<p><code dir="ltr" translate="no">servicemanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  check</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  create</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  delete</code></li>
<li><code dir="ltr" translate="no">servicemanagement.services.get</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  list</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  quota</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  report</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicemanagement.  services.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.editor" class="role-title add-link" data-text="Service Management Editor" tabindex="-1">Service Management Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p>Editor role for Service Management.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  check</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  delete</code></p>
<p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  quota</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.viewer" class="role-title add-link" data-text="Service Management Viewer" tabindex="-1">Service Management Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.viewer</code> )</p>
<p>Viewer role for Service Management.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.checker" class="role-title add-link" data-text="Service Checker" tabindex="-1">Service Checker</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.checker</code> )</p>
<p>Can check admission of a service during runtime.</p></td>
<td><p><code dir="ltr" translate="no">servicemanagement.  services.  check</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.configEditor" class="role-title add-link" data-text="Service Config Editor" tabindex="-1">Service Config Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.configEditor</code> )</p>
<p>Access to update the service config and create rollouts.</p></td>
<td><p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.quotaAdmin" class="role-title add-link" data-text="Quota Administrator Beta" tabindex="-1">Quota Administrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.quotaAdmin</code> )</p>
<p>Provides access to administer service quotas.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudquotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudquotas.quotas.get</code></li>
<li><code dir="ltr" translate="no">cloudquotas.quotas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  create</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></li>
<li><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">monitoring.  alertPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.quotas.get</code></li>
<li><code dir="ltr" translate="no">serviceusage.quotas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.quotaViewer" class="role-title add-link" data-text="Quota Viewer Beta" tabindex="-1">Quota Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.quotaViewer</code> )</p>
<p>Provides access to view service quotas.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudquotas.quotas.get</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.reporter" class="role-title add-link" data-text="Service Reporter" tabindex="-1">Service Reporter</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.reporter</code> )</p>
<p>Can report usage of a service during runtime.</p></td>
<td><p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.serviceConsumer" class="role-title add-link" data-text="Service Consumer" tabindex="-1">Service Consumer</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.serviceConsumer</code> )</p>
<p>Can enable the service.</p></td>
<td><p><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.serviceController" class="role-title add-link" data-text="Service Controller" tabindex="-1">Service Controller</h4>
<p>( <code dir="ltr" translate="no">roles/  servicemanagement.serviceController</code> )</p>
<p>Can check preconditions and report usage of a service during runtime.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">servicemanagement.  services.  check</code></p>
<p><code dir="ltr" translate="no">servicemanagement.services.get</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  quota</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p></td>
</tr>
</tbody>
</table>

## Service Management permissions

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
<td><h4 id="servicemanagement.services.bind" class="permission-name add-link" data-text="servicemanagement.services.bind" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  bind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.serviceConsumer">Service Consumer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.serviceConsumer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkProvisioningServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.services.check" class="permission-name add-link" data-text="servicemanagement.services.check" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  check</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.checker">Service Checker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.checker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.serviceController">Service Controller</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.serviceController</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpoints.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.services.create" class="permission-name add-link" data-text="servicemanagement.services.create" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.services.delete" class="permission-name add-link" data-text="servicemanagement.services.delete" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.services.get" class="permission-name add-link" data-text="servicemanagement.services.get" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.configEditor">Service Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.serviceController">Service Controller</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.serviceController</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpoints.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpointsportal#endpointsportal.serviceAgent">Endpoints Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpointsportal.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.services.getIamPolicy" class="permission-name add-link" data-text="servicemanagement.services.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.services.list" class="permission-name add-link" data-text="servicemanagement.services.list" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpointsportal#endpointsportal.serviceAgent">Endpoints Portal Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpointsportal.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.services.quota" class="permission-name add-link" data-text="servicemanagement.services.quota" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  quota</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.serviceController">Service Controller</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.serviceController</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpoints.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.services.report" class="permission-name add-link" data-text="servicemanagement.services.report" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  report</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.reporter">Service Reporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.reporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.serviceController">Service Controller</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.serviceController</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/endpoints#endpoints.serviceAgent">Cloud Endpoints Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  endpoints.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicemanagement.services.setIamPolicy" class="permission-name add-link" data-text="servicemanagement.services.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicemanagement.services.update" class="permission-name add-link" data-text="servicemanagement.services.update" tabindex="-1"><code dir="ltr" translate="no">servicemanagement.  services.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.configEditor">Service Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.configEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
