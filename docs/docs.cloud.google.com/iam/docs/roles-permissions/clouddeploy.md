---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy
title: Cloud Deploy roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Deploy. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Deploy roles

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
<td><h4 id="clouddeploy.admin" class="role-title add-link" data-text="Cloud Deploy Admin" tabindex="-1">Cloud Deploy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p>Full control of Cloud Deploy resources.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.update</code></li>
<li><code dir="ltr" translate="no">clouddeploy.config.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  update</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  update</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  override</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  update</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.terminate</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.abandon</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.advance</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.approve</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.ignoreJob</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.retryJob</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.rollback</code></li>
<li><code dir="ltr" translate="no">clouddeploy.targets.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">clouddeploy.targets.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">clouddeploy.targets.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.targets.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  targets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.targets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.editor" class="role-title add-link" data-text="Cloud Deploy Editor" tabindex="-1">Cloud Deploy Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p>Editor role for Cloud Deploy</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.automationRuns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.automations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.automations.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  update</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  update</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  override</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  update</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.terminate</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.releases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.releases.abandon</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.advance</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.approve</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.ignoreJob</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.retryJob</code></li>
<li><code dir="ltr" translate="no">clouddeploy.rollouts.rollback</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.targets.create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.viewer" class="role-title add-link" data-text="Cloud Deploy Viewer" tabindex="-1">Cloud Deploy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p>Can view Cloud Deploy resources.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.operations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.approver" class="role-title add-link" data-text="Cloud Deploy Approver" tabindex="-1">Cloud Deploy Approver</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p>Permission to approve or reject rollouts.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.approve</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.customTargetTypeAdmin" class="role-title add-link" data-text="Cloud Deploy Custom Target Type Admin" tabindex="-1">Cloud Deploy Custom Target Type Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p>Permission to manage CustomTargetType resources</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.developer" class="role-title add-link" data-text="Cloud Deploy Developer" tabindex="-1">Cloud Deploy Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p>Permission to manage deployment configuration without permission to access operational resources, such as targets.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  update</code></p>
<p><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.releases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.releases.abandon</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.jobRunner" class="role-title add-link" data-text="Cloud Deploy Runner" tabindex="-1">Cloud Deploy Runner</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.jobRunner</code> )</p>
<p>Permission to execute Cloud Deploy work without permission to deliver to a target.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.operator" class="role-title add-link" data-text="Cloud Deploy Operator" tabindex="-1">Cloud Deploy Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p>Permission to manage deployment configuration.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.automationRuns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.automations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.automations.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.automations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  update</code></p>
<p><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.jobRuns.terminate</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.releases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.releases.abandon</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.releases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.advance</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.cancel</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.ignoreJob</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.retryJob</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.rollback</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.delete</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.policyAdmin" class="role-title add-link" data-text="Cloud Deploy Policy Admin" tabindex="-1">Cloud Deploy Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p>Permission to manage Deploy Policies.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.deployPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  create</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  override</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.policyOverrider" class="role-title add-link" data-text="Cloud Deploy Policy Overrider" tabindex="-1">Cloud Deploy Policy Overrider</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p>Permission to override Deploy Policies.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  override</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.releaser" class="role-title add-link" data-text="Cloud Deploy Releaser" tabindex="-1">Cloud Deploy Releaser</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p>Permission to create Cloud Deploy releases and rollouts.</p></td>
<td><p><code dir="ltr" translate="no">clouddeploy.config.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.locations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.delete</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.get</code></li>
<li><code dir="ltr" translate="no">clouddeploy.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">clouddeploy.releases.create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.advance</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.cancel</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.create</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.rollback</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="clouddeploy.serviceAgent" class="role-title add-link" data-text="Cloud Deploy Service Agent" tabindex="-1">Cloud Deploy Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</p>
<p>Gives Cloud Deploy Service Account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.workerpools.use</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  report</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Deploy permissions

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
<td><h4 id="clouddeploy.automationRuns.cancel" class="permission-name add-link" data-text="clouddeploy.automationRuns.cancel" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  automationRuns.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.automationRuns.get" class="permission-name add-link" data-text="clouddeploy.automationRuns.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automationRuns.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.automationRuns.list" class="permission-name add-link" data-text="clouddeploy.automationRuns.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.automations.create" class="permission-name add-link" data-text="clouddeploy.automations.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.automations.delete" class="permission-name add-link" data-text="clouddeploy.automations.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.automations.get" class="permission-name add-link" data-text="clouddeploy.automations.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.automations.list" class="permission-name add-link" data-text="clouddeploy.automations.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.automations.update" class="permission-name add-link" data-text="clouddeploy.automations.update" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.automations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.config.get" class="permission-name add-link" data-text="clouddeploy.config.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.config.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.jobRunner">Cloud Deploy Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.customTargetTypes.create" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.customTargetTypes.delete" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.customTargetTypes.get" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.customTargetTypes.getIamPolicy" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.customTargetTypes.list" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.customTargetTypes.setIamPolicy" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.customTargetTypes.update" class="permission-name add-link" data-text="clouddeploy.customTargetTypes.update" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.customTargetTypeAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.create" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deliveryPipelines.createTagBinding" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.delete" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deliveryPipelines.deleteTagBinding" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.get" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deliveryPipelines.getIamPolicy" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.list" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deliveryPipelines.listEffectiveTags" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.listTagBindings" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deliveryPipelines.setIamPolicy" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deliveryPipelines.update" class="permission-name add-link" data-text="clouddeploy.deliveryPipelines.update" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deployPolicies.create" class="permission-name add-link" data-text="clouddeploy.deployPolicies.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deployPolicies.delete" class="permission-name add-link" data-text="clouddeploy.deployPolicies.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deployPolicies.get" class="permission-name add-link" data-text="clouddeploy.deployPolicies.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.deployPolicies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deployPolicies.getIamPolicy" class="permission-name add-link" data-text="clouddeploy.deployPolicies.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deployPolicies.list" class="permission-name add-link" data-text="clouddeploy.deployPolicies.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deployPolicies.override" class="permission-name add-link" data-text="clouddeploy.deployPolicies.override" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  override</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.deployPolicies.setIamPolicy" class="permission-name add-link" data-text="clouddeploy.deployPolicies.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.deployPolicies.update" class="permission-name add-link" data-text="clouddeploy.deployPolicies.update" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.jobRuns.get" class="permission-name add-link" data-text="clouddeploy.jobRuns.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.jobRuns.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.jobRuns.list" class="permission-name add-link" data-text="clouddeploy.jobRuns.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.jobRuns.terminate" class="permission-name add-link" data-text="clouddeploy.jobRuns.terminate" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.jobRuns.terminate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.locations.get" class="permission-name add-link" data-text="clouddeploy.locations.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.locations.list" class="permission-name add-link" data-text="clouddeploy.locations.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.operations.cancel" class="permission-name add-link" data-text="clouddeploy.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.operations.delete" class="permission-name add-link" data-text="clouddeploy.operations.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.operations.get" class="permission-name add-link" data-text="clouddeploy.operations.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.operations.list" class="permission-name add-link" data-text="clouddeploy.operations.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.releases.abandon" class="permission-name add-link" data-text="clouddeploy.releases.abandon" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.releases.abandon</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.releases.create" class="permission-name add-link" data-text="clouddeploy.releases.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.releases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.releases.get" class="permission-name add-link" data-text="clouddeploy.releases.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.releases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.releases.list" class="permission-name add-link" data-text="clouddeploy.releases.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.releases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.rollouts.advance" class="permission-name add-link" data-text="clouddeploy.rollouts.advance" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.advance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.rollouts.approve" class="permission-name add-link" data-text="clouddeploy.rollouts.approve" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.rollouts.cancel" class="permission-name add-link" data-text="clouddeploy.rollouts.cancel" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.rollouts.create" class="permission-name add-link" data-text="clouddeploy.rollouts.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.rollouts.get" class="permission-name add-link" data-text="clouddeploy.rollouts.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.rollouts.ignoreJob" class="permission-name add-link" data-text="clouddeploy.rollouts.ignoreJob" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.ignoreJob</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.rollouts.list" class="permission-name add-link" data-text="clouddeploy.rollouts.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.rollouts.retryJob" class="permission-name add-link" data-text="clouddeploy.rollouts.retryJob" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.retryJob</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.rollouts.rollback" class="permission-name add-link" data-text="clouddeploy.rollouts.rollback" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.rollouts.rollback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.create" class="permission-name add-link" data-text="clouddeploy.targets.create" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.targets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.targets.createTagBinding" class="permission-name add-link" data-text="clouddeploy.targets.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.delete" class="permission-name add-link" data-text="clouddeploy.targets.delete" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.targets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.targets.deleteTagBinding" class="permission-name add-link" data-text="clouddeploy.targets.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.get" class="permission-name add-link" data-text="clouddeploy.targets.get" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.targets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.targets.getIamPolicy" class="permission-name add-link" data-text="clouddeploy.targets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.list" class="permission-name add-link" data-text="clouddeploy.targets.list" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.targets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.targets.listEffectiveTags" class="permission-name add-link" data-text="clouddeploy.targets.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.listTagBindings" class="permission-name add-link" data-text="clouddeploy.targets.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="clouddeploy.targets.setIamPolicy" class="permission-name add-link" data-text="clouddeploy.targets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.  targets.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="clouddeploy.targets.update" class="permission-name add-link" data-text="clouddeploy.targets.update" tabindex="-1"><code dir="ltr" translate="no">clouddeploy.targets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.operator</code> )</p></td>
</tr>
</tbody>
</table>
