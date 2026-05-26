---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation
title: Telco Automation API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Telco Automation API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Telco Automation API roles

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
<td><h4 id="telcoautomation.admin" class="role-title add-link" data-text="Telco Automation Admin Beta" tabindex="-1">Telco Automation Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p>Full access to Telco Automation resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudquotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudquotas.quotas.get</code></li>
<li><code dir="ltr" translate="no">cloudquotas.quotas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.get</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.get</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.get</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.getShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.listShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.usage.get</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  contentsecuritypolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  contentsecuritypolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  contentsecuritypolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivemcppolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.mcppolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.mcppolicy.get</code></li>
<li><code dir="ltr" translate="no">serviceusage.mcppolicy.update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.quotas.get</code></li>
<li><code dir="ltr" translate="no">serviceusage.quotas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.services.disable</code></li>
<li><code dir="ltr" translate="no">serviceusage.services.enable</code></li>
<li><code dir="ltr" translate="no">serviceusage.services.get</code></li>
<li><code dir="ltr" translate="no">serviceusage.services.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.services.use</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">source.repos.get</code></p>
<p><code dir="ltr" translate="no">source.repos.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  approve</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  propose</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  update</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  edgeSlms.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  edgeSlms.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.edgeSlms.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></li>
<li><code dir="ltr" translate="no">telcoautomation.locations.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.locations.list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.operations.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.editor" class="role-title add-link" data-text="Telcoautomation Editor Beta" tabindex="-1">Telcoautomation Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p>Editor role for telcoautomation</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.blueprints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  approve</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  propose</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  blueprints.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.locations.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.operations.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  delete</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.viewer" class="role-title add-link" data-text="Telcoautomation Viewer Beta" tabindex="-1">Telcoautomation Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p>Viewer role for telcoautomation</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.locations.get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.operations.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.blueprintDesigner" class="role-title add-link" data-text="Telco Automation Blueprint Designer Beta" tabindex="-1">Telco Automation Blueprint Designer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p>Ability to manage blueprints</p></td>
<td><p><code dir="ltr" translate="no">telcoautomation.  blueprints.  create</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  delete</code></p>
<p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  propose</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  update</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.deploymentAdmin" class="role-title add-link" data-text="Telco Automation Deployment Admin Beta" tabindex="-1">Telco Automation Deployment Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p>Ability to manage deployments</p></td>
<td><p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.opsAdminTier1" class="role-title add-link" data-text="Telco Automation Tier 1 Operations Admin Beta" tabindex="-1">Telco Automation Tier 1 Operations Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p>Ability to get status of deployments</p></td>
<td><p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.get</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.get</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.get</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.getShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.listShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.usage.get</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.opsAdminTier4" class="role-title add-link" data-text="Telco Automation Tier 4 Operations Admin Beta" tabindex="-1">Telco Automation Tier 4 Operations Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p>Ability to manage deployments and their status</p></td>
<td><p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.get</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.get</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.get</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.getShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.listShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.usage.get</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.serviceOrchestrator" class="role-title add-link" data-text="Telco Automation Service Orchestrator Beta" tabindex="-1">Telco Automation Service Orchestrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p>
<p>Ability to manage deployments</p></td>
<td><p><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></li>
<li><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p></td>
</tr>
</tbody>
</table>

## Telco Automation API permissions

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
<td><h4 id="telcoautomation.blueprints.approve" class="permission-name add-link" data-text="telcoautomation.blueprints.approve" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.blueprints.create" class="permission-name add-link" data-text="telcoautomation.blueprints.create" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.blueprints.delete" class="permission-name add-link" data-text="telcoautomation.blueprints.delete" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.blueprints.get" class="permission-name add-link" data-text="telcoautomation.blueprints.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.blueprints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.blueprints.list" class="permission-name add-link" data-text="telcoautomation.blueprints.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.blueprints.propose" class="permission-name add-link" data-text="telcoautomation.blueprints.propose" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  propose</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.blueprints.update" class="permission-name add-link" data-text="telcoautomation.blueprints.update" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  blueprints.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.deployments.apply" class="permission-name add-link" data-text="telcoautomation.deployments.apply" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  apply</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.deployments.computeStatus" class="permission-name add-link" data-text="telcoautomation.deployments.computeStatus" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  computeStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.deployments.create" class="permission-name add-link" data-text="telcoautomation.deployments.create" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.deployments.delete" class="permission-name add-link" data-text="telcoautomation.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.deployments.get" class="permission-name add-link" data-text="telcoautomation.deployments.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.deployments.list" class="permission-name add-link" data-text="telcoautomation.deployments.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.deployments.rollback" class="permission-name add-link" data-text="telcoautomation.deployments.rollback" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  rollback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.deployments.update" class="permission-name add-link" data-text="telcoautomation.deployments.update" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  deployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.edgeSlms.create" class="permission-name add-link" data-text="telcoautomation.edgeSlms.create" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  edgeSlms.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.edgeSlms.delete" class="permission-name add-link" data-text="telcoautomation.edgeSlms.delete" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  edgeSlms.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.edgeSlms.get" class="permission-name add-link" data-text="telcoautomation.edgeSlms.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.edgeSlms.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.edgeSlms.list" class="permission-name add-link" data-text="telcoautomation.edgeSlms.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.hydratedDeployments.apply" class="permission-name add-link" data-text="telcoautomation.hydratedDeployments.apply" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  apply</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.hydratedDeployments.get" class="permission-name add-link" data-text="telcoautomation.hydratedDeployments.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.hydratedDeployments.list" class="permission-name add-link" data-text="telcoautomation.hydratedDeployments.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.hydratedDeployments.update" class="permission-name add-link" data-text="telcoautomation.hydratedDeployments.update" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.locations.get" class="permission-name add-link" data-text="telcoautomation.locations.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.locations.list" class="permission-name add-link" data-text="telcoautomation.locations.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.operations.cancel" class="permission-name add-link" data-text="telcoautomation.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.operations.delete" class="permission-name add-link" data-text="telcoautomation.operations.delete" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.operations.get" class="permission-name add-link" data-text="telcoautomation.operations.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.operations.list" class="permission-name add-link" data-text="telcoautomation.operations.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.orchestrationClusters.create" class="permission-name add-link" data-text="telcoautomation.orchestrationClusters.create" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.orchestrationClusters.delete" class="permission-name add-link" data-text="telcoautomation.orchestrationClusters.delete" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.orchestrationClusters.get" class="permission-name add-link" data-text="telcoautomation.orchestrationClusters.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.orchestrationClusters.list" class="permission-name add-link" data-text="telcoautomation.orchestrationClusters.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.deploymentAdmin">Telco Automation Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.serviceOrchestrator">Telco Automation Service Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.serviceOrchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="telcoautomation.publicBlueprints.get" class="permission-name add-link" data-text="telcoautomation.publicBlueprints.get" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="telcoautomation.publicBlueprints.list" class="permission-name add-link" data-text="telcoautomation.publicBlueprints.list" tabindex="-1"><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.blueprintDesigner">Telco Automation Blueprint Designer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  telcoautomation.blueprintDesigner</code> )</p></td>
</tr>
</tbody>
</table>
