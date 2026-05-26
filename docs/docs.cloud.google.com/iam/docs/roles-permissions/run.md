---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/run
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/run
title: Cloud Run roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Run. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Run roles

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
<td><h4 id="run.admin" class="role-title add-link" data-text="Cloud Run Admin" tabindex="-1">Cloud Run Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p>Full control over all Cloud Run resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Cloud Run service</li>
<li>Cloud Run job</li>
</ul></td>
<td><p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
<li><code dir="ltr" translate="no">run.jobs.create</code></li>
<li><code dir="ltr" translate="no">run.jobs.createTagBinding</code></li>
<li><code dir="ltr" translate="no">run.jobs.delete</code></li>
<li><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">run.jobs.get</code></li>
<li><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.jobs.list</code></li>
<li><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">run.jobs.listTagBindings</code></li>
<li><code dir="ltr" translate="no">run.jobs.run</code></li>
<li><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></li>
<li><code dir="ltr" translate="no">run.jobs.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.jobs.update</code></li>
<li><code dir="ltr" translate="no">run.locations.list</code></li>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
<li><code dir="ltr" translate="no">run.prompts.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
<li><code dir="ltr" translate="no">run.services.create</code></li>
<li><code dir="ltr" translate="no">run.services.createTagBinding</code></li>
<li><code dir="ltr" translate="no">run.services.delete</code></li>
<li><code dir="ltr" translate="no">run.services.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">run.services.get</code></li>
<li><code dir="ltr" translate="no">run.services.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.services.list</code></li>
<li><code dir="ltr" translate="no">run.services.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">run.services.listTagBindings</code></li>
<li><code dir="ltr" translate="no">run.services.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.services.update</code></li>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
<li><code dir="ltr" translate="no">run.workerpools.create</code></li>
<li><code dir="ltr" translate="no">run.workerpools.delete</code></li>
<li><code dir="ltr" translate="no">run.workerpools.get</code></li>
<li><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.workerpools.list</code></li>
<li><code dir="ltr" translate="no">run.workerpools.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">run.workerpools.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.builder" class="role-title add-link" data-text="Cloud Run Builder" tabindex="-1">Cloud Run Builder</h4>
<p>( <code dir="ltr" translate="no">roles/  run.builder</code> )</p>
<p>Can build Cloud Run functions and source deployed services.</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">source.repos.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="run.developer" class="role-title add-link" data-text="Cloud Run Developer" tabindex="-1">Cloud Run Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p>Read and write access to all Cloud Run resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Cloud Run service</li>
<li>Cloud Run job</li>
</ul></td>
<td><p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="run.editor" class="role-title add-link" data-text="Cloud Run Editor" tabindex="-1">Cloud Run Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p>Editor role for Cloud Run</p></td>
<td><p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="run.invoker" class="role-title add-link" data-text="Cloud Run Invoker" tabindex="-1">Cloud Run Invoker</h4>
<p>( <code dir="ltr" translate="no">roles/  run.invoker</code> )</p>
<p>Can invoke Cloud Run services and execute Cloud Run jobs.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Cloud Run service</li>
<li>Cloud Run job</li>
</ul></td>
<td><p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.routes.invoke</code></p></td>
</tr>
<tr class="even">
<td><h4 id="run.viewer" class="role-title add-link" data-text="Cloud Run Viewer" tabindex="-1">Cloud Run Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p>Can view the state of all Cloud Run resources, including IAM policies.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Cloud Run service</li>
<li>Cloud Run job</li>
</ul></td>
<td><p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.get</code></p>
<p><code dir="ltr" translate="no">run.executions.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.get</code></p>
<p><code dir="ltr" translate="no">run.operations.list</code></p>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.list</code></p>
<p><code dir="ltr" translate="no">run.routes.get</code></p>
<p><code dir="ltr" translate="no">run.routes.list</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobsExecutor" class="role-title add-link" data-text="Cloud Run Jobs Executor" tabindex="-1">Cloud Run Jobs Executor</h4>
<p>( <code dir="ltr" translate="no">roles/  run.jobsExecutor</code> )</p>
<p>Can execute and cancel Cloud Run jobs.</p></td>
<td><p><code dir="ltr" translate="no">run.executions.cancel</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p></td>
</tr>
<tr class="even">
<td><h4 id="run.jobsExecutorWithOverrides" class="role-title add-link" data-text="Cloud Run Jobs Executor With Overrides" tabindex="-1">Cloud Run Jobs Executor With Overrides</h4>
<p>( <code dir="ltr" translate="no">roles/  run.jobsExecutorWithOverrides</code> )</p>
<p>Can execute and cancel Cloud Run jobs with overrides.</p></td>
<td><p><code dir="ltr" translate="no">run.executions.cancel</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="run.servicesInvoker" class="role-title add-link" data-text="Cloud Run Service Invoker" tabindex="-1">Cloud Run Service Invoker</h4>
<p>( <code dir="ltr" translate="no">roles/  run.servicesInvoker</code> )</p>
<p>Can invoke Cloud Run services.</p></td>
<td><p><code dir="ltr" translate="no">run.routes.invoke</code></p></td>
</tr>
<tr class="even">
<td><h4 id="run.sourceDeveloper" class="role-title add-link" data-text="Cloud Run Source Developer" tabindex="-1">Cloud Run Source Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Deploy and manage Cloud Run source deployed resources.</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.attach</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.create</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.publish</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.update</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.create</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  create</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  delete</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  update</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></li>
<li><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.create</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.operations.cancel</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.delete</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.pipelines.create</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.update</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.create</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.delete</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.undelete</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.update</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.attach</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.commit</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.create</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.rollback</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.create</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.seek</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.update</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.executions.cancel</code></li>
<li><code dir="ltr" translate="no">run.executions.delete</code></li>
<li><code dir="ltr" translate="no">run.executions.get</code></li>
<li><code dir="ltr" translate="no">run.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.jobs.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.delete</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></p>
<p><code dir="ltr" translate="no">run.jobs.update</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.operations.delete</code></li>
<li><code dir="ltr" translate="no">run.operations.get</code></li>
<li><code dir="ltr" translate="no">run.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.revisions.delete</code></li>
<li><code dir="ltr" translate="no">run.revisions.get</code></li>
<li><code dir="ltr" translate="no">run.revisions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.routes.get</code></li>
<li><code dir="ltr" translate="no">run.routes.invoke</code></li>
<li><code dir="ltr" translate="no">run.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.services.create</code></p>
<p><code dir="ltr" translate="no">run.services.delete</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.update</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.create</code></p>
<p><code dir="ltr" translate="no">run.workerpools.delete</code></p>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.update</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.create</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.abort</code></p>
<p><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></p>
<p><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.createContext</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="run.sourceViewer" class="role-title add-link" data-text="Cloud Run Source Viewer" tabindex="-1">Cloud Run Source Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>View Cloud Run source deployed resources.</p></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.get</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleChannelConfigs.  get</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.locations.get</code></li>
<li><code dir="ltr" translate="no">eventarc.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.messageBuses.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.list</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.use</code></p>
<p><code dir="ltr" translate="no">eventarc.  multiProjectSources.  collectGoogleApiEvents</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.get</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.get</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">eventarc.providers.get</code></li>
<li><code dir="ltr" translate="no">eventarc.providers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">eventarc.triggers.get</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.configurations.get</code></li>
<li><code dir="ltr" translate="no">run.configurations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.executions.get</code></p>
<p><code dir="ltr" translate="no">run.executions.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.get</code></p>
<p><code dir="ltr" translate="no">run.operations.list</code></p>
<p><code dir="ltr" translate="no">run.prompts.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.get</code></p>
<p><code dir="ltr" translate="no">run.revisions.list</code></p>
<p><code dir="ltr" translate="no">run.routes.get</code></p>
<p><code dir="ltr" translate="no">run.routes.list</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">run.tasks.get</code></li>
<li><code dir="ltr" translate="no">run.tasks.list</code></li>
</ul>
<p><code dir="ltr" translate="no">run.workerpools.get</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
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
<td><h4 id="run.serviceAgent" class="role-title add-link" data-text="Cloud Run Service Agent" tabindex="-1">Cloud Run Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  run.serviceAgent</code> )</p>
<p>Gives Cloud Run service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">run.routes.invoke</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.use</code></p></td>
</tr>
</tbody>
</table>

## Cloud Run permissions

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
<td><h4 id="run.configurations.get" class="permission-name add-link" data-text="run.configurations.get" tabindex="-1"><code dir="ltr" translate="no">run.configurations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.configurations.list" class="permission-name add-link" data-text="run.configurations.list" tabindex="-1"><code dir="ltr" translate="no">run.configurations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.executions.cancel" class="permission-name add-link" data-text="run.executions.cancel" tabindex="-1"><code dir="ltr" translate="no">run.executions.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.jobsExecutor">Cloud Run Jobs Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.jobsExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.jobsExecutorWithOverrides">Cloud Run Jobs Executor With Overrides</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.jobsExecutorWithOverrides</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.executions.delete" class="permission-name add-link" data-text="run.executions.delete" tabindex="-1"><code dir="ltr" translate="no">run.executions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.executions.get" class="permission-name add-link" data-text="run.executions.get" tabindex="-1"><code dir="ltr" translate="no">run.executions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.executions.list" class="permission-name add-link" data-text="run.executions.list" tabindex="-1"><code dir="ltr" translate="no">run.executions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.create" class="permission-name add-link" data-text="run.jobs.create" tabindex="-1"><code dir="ltr" translate="no">run.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.createTagBinding" class="permission-name add-link" data-text="run.jobs.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">run.jobs.createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.delete" class="permission-name add-link" data-text="run.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">run.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.deleteTagBinding" class="permission-name add-link" data-text="run.jobs.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.get" class="permission-name add-link" data-text="run.jobs.get" tabindex="-1"><code dir="ltr" translate="no">run.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.getIamPolicy" class="permission-name add-link" data-text="run.jobs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.list" class="permission-name add-link" data-text="run.jobs.list" tabindex="-1"><code dir="ltr" translate="no">run.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.listEffectiveTags" class="permission-name add-link" data-text="run.jobs.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.listTagBindings" class="permission-name add-link" data-text="run.jobs.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">run.jobs.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.run" class="permission-name add-link" data-text="run.jobs.run" tabindex="-1"><code dir="ltr" translate="no">run.jobs.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.invoker">Cloud Run Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.jobsExecutor">Cloud Run Jobs Executor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.jobsExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.jobsExecutorWithOverrides">Cloud Run Jobs Executor With Overrides</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.jobsExecutorWithOverrides</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.runWithOverrides" class="permission-name add-link" data-text="run.jobs.runWithOverrides" tabindex="-1"><code dir="ltr" translate="no">run.jobs.runWithOverrides</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.jobsExecutorWithOverrides">Cloud Run Jobs Executor With Overrides</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.jobsExecutorWithOverrides</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.jobs.setIamPolicy" class="permission-name add-link" data-text="run.jobs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.jobs.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="run.jobs.update" class="permission-name add-link" data-text="run.jobs.update" tabindex="-1"><code dir="ltr" translate="no">run.jobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.locations.list" class="permission-name add-link" data-text="run.locations.list" tabindex="-1"><code dir="ltr" translate="no">run.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.operations.delete" class="permission-name add-link" data-text="run.operations.delete" tabindex="-1"><code dir="ltr" translate="no">run.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.operations.get" class="permission-name add-link" data-text="run.operations.get" tabindex="-1"><code dir="ltr" translate="no">run.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.operations.list" class="permission-name add-link" data-text="run.operations.list" tabindex="-1"><code dir="ltr" translate="no">run.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.prompts.get" class="permission-name add-link" data-text="run.prompts.get" tabindex="-1"><code dir="ltr" translate="no">run.prompts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.revisions.delete" class="permission-name add-link" data-text="run.revisions.delete" tabindex="-1"><code dir="ltr" translate="no">run.revisions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.revisions.get" class="permission-name add-link" data-text="run.revisions.get" tabindex="-1"><code dir="ltr" translate="no">run.revisions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.revisions.list" class="permission-name add-link" data-text="run.revisions.list" tabindex="-1"><code dir="ltr" translate="no">run.revisions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.routes.get" class="permission-name add-link" data-text="run.routes.get" tabindex="-1"><code dir="ltr" translate="no">run.routes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.routes.invoke" class="permission-name add-link" data-text="run.routes.invoke" tabindex="-1"><code dir="ltr" translate="no">run.routes.invoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.invoker">Cloud Run Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.servicesInvoker">Cloud Run Service Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.servicesInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.routes.list" class="permission-name add-link" data-text="run.routes.list" tabindex="-1"><code dir="ltr" translate="no">run.routes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.create" class="permission-name add-link" data-text="run.services.create" tabindex="-1"><code dir="ltr" translate="no">run.services.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.services.createTagBinding" class="permission-name add-link" data-text="run.services.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">run.services.createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.delete" class="permission-name add-link" data-text="run.services.delete" tabindex="-1"><code dir="ltr" translate="no">run.services.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.services.deleteTagBinding" class="permission-name add-link" data-text="run.services.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">run.services.deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.get" class="permission-name add-link" data-text="run.services.get" tabindex="-1"><code dir="ltr" translate="no">run.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.services.getIamPolicy" class="permission-name add-link" data-text="run.services.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.services.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.list" class="permission-name add-link" data-text="run.services.list" tabindex="-1"><code dir="ltr" translate="no">run.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.services.listEffectiveTags" class="permission-name add-link" data-text="run.services.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">run.services.listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.listTagBindings" class="permission-name add-link" data-text="run.services.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">run.services.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.services.setIamPolicy" class="permission-name add-link" data-text="run.services.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.services.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.services.update" class="permission-name add-link" data-text="run.services.update" tabindex="-1"><code dir="ltr" translate="no">run.services.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.tasks.get" class="permission-name add-link" data-text="run.tasks.get" tabindex="-1"><code dir="ltr" translate="no">run.tasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.tasks.list" class="permission-name add-link" data-text="run.tasks.list" tabindex="-1"><code dir="ltr" translate="no">run.tasks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.workerpools.create" class="permission-name add-link" data-text="run.workerpools.create" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.workerpools.delete" class="permission-name add-link" data-text="run.workerpools.delete" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.workerpools.get" class="permission-name add-link" data-text="run.workerpools.get" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.workerpools.getIamPolicy" class="permission-name add-link" data-text="run.workerpools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="run.workerpools.list" class="permission-name add-link" data-text="run.workerpools.list" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="run.workerpools.setIamPolicy" class="permission-name add-link" data-text="run.workerpools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="run.workerpools.update" class="permission-name add-link" data-text="run.workerpools.update" tabindex="-1"><code dir="ltr" translate="no">run.workerpools.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
