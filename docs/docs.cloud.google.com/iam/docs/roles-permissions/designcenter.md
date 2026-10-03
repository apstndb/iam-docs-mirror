---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/designcenter
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter
title: Application Design Center roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Application Design Center. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Application Design Center roles

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
<td>Application Design Center Admin
<p>( <code>roles/ designcenter.admin</code> )</p>
<p>Full access to Application Design Center resources.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.boundaries.attach</code></p>
<p><code>apphub.boundaries.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.get</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
<li><code>designcenter. catalogTemplateRevisions. create</code></li>
<li><code>designcenter. catalogTemplateRevisions. delete</code></li>
<li><code>designcenter. catalogTemplateRevisions. get</code></li>
<li><code>designcenter. catalogTemplateRevisions. list</code></li>
<li><code>designcenter. catalogTemplates. create</code></li>
<li><code>designcenter. catalogTemplates. delete</code></li>
<li><code>designcenter. catalogTemplates. get</code></li>
<li><code>designcenter. catalogTemplates. list</code></li>
<li><code>designcenter. catalogTemplates. update</code></li>
<li><code>designcenter.catalogs.create</code></li>
<li><code>designcenter.catalogs.delete</code></li>
<li><code>designcenter.catalogs.get</code></li>
<li><code>designcenter.catalogs.list</code></li>
<li><code>designcenter.catalogs.update</code></li>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
<li><code>designcenter.locations.get</code></li>
<li><code>designcenter.locations.list</code></li>
<li><code>designcenter.operations.cancel</code></li>
<li><code>designcenter.operations.delete</code></li>
<li><code>designcenter.operations.get</code></li>
<li><code>designcenter.operations.list</code></li>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
<li><code>designcenter.shares.create</code></li>
<li><code>designcenter.shares.delete</code></li>
<li><code>designcenter.shares.get</code></li>
<li><code>designcenter.shares.list</code></li>
<li><code>designcenter.spaces.create</code></li>
<li><code>designcenter.spaces.delete</code></li>
<li><code>designcenter.spaces.get</code></li>
<li><code>designcenter. spaces. getIamPolicy</code></li>
<li><code>designcenter.spaces.list</code></li>
<li><code>designcenter. spaces. setIamPolicy</code></li>
<li><code>designcenter.spaces.update</code></li>
</ul>
<p><code>developerconnect. connections. constructGitHubAppManifest</code></p>
<p><code>developerconnect. connections. create</code></p>
<p><code>developerconnect. connections. delete</code></p>
<p><code>developerconnect. connections. fetchGitHubInstallations</code></p>
<p><code>developerconnect. connections. fetchLinkableGitRepositories</code></p>
<p><code>developerconnect. connections. generateGitHubStateToken</code></p>
<p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. connections. processGitHubAppCreationCallback</code></p>
<p><code>developerconnect. connections. processGitHubOAuthCallback</code></p>
<p><code>developerconnect. connections. update</code></p>
<p><code>developerconnect. gitRepositoryLinks. create</code></p>
<p><code>developerconnect. gitRepositoryLinks. delete</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchGitRefs</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyWrite</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect.operations.*</code></p>
<ul>
<li><code>developerconnect. operations. cancel</code></li>
<li><code>developerconnect. operations. delete</code></li>
<li><code>developerconnect. operations. get</code></li>
<li><code>developerconnect. operations. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.move</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.update</code></p>
<p><code>storage.objects.updateContext</code></p></td>
</tr>
<tr class="even">
<td>Designcenter Editor
<p>( <code>roles/ designcenter.editor</code> )</p>
<p>Editor role for designcenter</p></td>
<td><p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. applicationTemplates.*</code></p>
<ul>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
</ul>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. catalogTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. catalogTemplateRevisions. create</code></li>
<li><code>designcenter. catalogTemplateRevisions. delete</code></li>
<li><code>designcenter. catalogTemplateRevisions. get</code></li>
<li><code>designcenter. catalogTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. catalogTemplates.*</code></p>
<ul>
<li><code>designcenter. catalogTemplates. create</code></li>
<li><code>designcenter. catalogTemplates. delete</code></li>
<li><code>designcenter. catalogTemplates. get</code></li>
<li><code>designcenter. catalogTemplates. list</code></li>
<li><code>designcenter. catalogTemplates. update</code></li>
</ul>
<p><code>designcenter.catalogs.*</code></p>
<ul>
<li><code>designcenter.catalogs.create</code></li>
<li><code>designcenter.catalogs.delete</code></li>
<li><code>designcenter.catalogs.get</code></li>
<li><code>designcenter.catalogs.list</code></li>
<li><code>designcenter.catalogs.update</code></li>
</ul>
<p><code>designcenter.components.*</code></p>
<ul>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
</ul>
<p><code>designcenter.connections.*</code></p>
<ul>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
</ul>
<p><code>designcenter.locations.*</code></p>
<ul>
<li><code>designcenter.locations.get</code></li>
<li><code>designcenter.locations.list</code></li>
</ul>
<p><code>designcenter.operations.*</code></p>
<ul>
<li><code>designcenter.operations.cancel</code></li>
<li><code>designcenter.operations.delete</code></li>
<li><code>designcenter.operations.get</code></li>
<li><code>designcenter.operations.list</code></li>
</ul>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.*</code></p>
<ul>
<li><code>designcenter.shares.create</code></li>
<li><code>designcenter.shares.delete</code></li>
<li><code>designcenter.shares.get</code></li>
<li><code>designcenter.shares.list</code></li>
</ul>
<p><code>designcenter.spaces.create</code></p>
<p><code>designcenter.spaces.delete</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>designcenter.spaces.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Design Center Viewer
<p>( <code>roles/ designcenter.viewer</code> )</p>
<p>Readonly access to Application Design Center resources.</p></td>
<td><p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. get</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. get</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.get</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.get</code></p>
<p><code>designcenter.components.list</code></p>
<p><code>designcenter.connections.get</code></p>
<p><code>designcenter.connections.list</code></p>
<p><code>designcenter.locations.*</code></p>
<ul>
<li><code>designcenter.locations.get</code></li>
<li><code>designcenter.locations.list</code></li>
</ul>
<p><code>designcenter.operations.get</code></p>
<p><code>designcenter.operations.list</code></p>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Admin
<p>( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p>Admin access to Application.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.get</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. get</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. get</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>developerconnect. connections. constructGitHubAppManifest</code></p>
<p><code>developerconnect. connections. create</code></p>
<p><code>developerconnect. connections. delete</code></p>
<p><code>developerconnect. connections. fetchGitHubInstallations</code></p>
<p><code>developerconnect. connections. fetchLinkableGitRepositories</code></p>
<p><code>developerconnect. connections. generateGitHubStateToken</code></p>
<p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. connections. processGitHubAppCreationCallback</code></p>
<p><code>developerconnect. connections. processGitHubOAuthCallback</code></p>
<p><code>developerconnect. connections. update</code></p>
<p><code>developerconnect. gitRepositoryLinks. create</code></p>
<p><code>developerconnect. gitRepositoryLinks. delete</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchGitRefs</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyWrite</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect.operations.*</code></p>
<ul>
<li><code>developerconnect. operations. cancel</code></li>
<li><code>developerconnect. operations. delete</code></li>
<li><code>developerconnect. operations. get</code></li>
<li><code>developerconnect. operations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Editor
<p>( <code>roles/ designcenter.applicationEditor</code> )</p>
<p>Read and Write access to Application.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.get</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. get</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. get</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Application Viewer
<p>( <code>roles/ designcenter.applicationViewer</code> )</p>
<p>Readonly access to Application.</p></td>
<td><p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.get</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. get</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. get</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.get</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Application Design Center User
<p>( <code>roles/ designcenter.user</code> )</p>
<p>Readonly access to Application Design Center resources.</p></td>
<td><p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. applicationTemplates.*</code></p>
<ul>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
</ul>
<p><code>designcenter.applications.get</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.*</code></p>
<ul>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
</ul>
<p><code>designcenter.connections.*</code></p>
<ul>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
</ul>
<p><code>designcenter.locations.*</code></p>
<ul>
<li><code>designcenter.locations.get</code></li>
<li><code>designcenter.locations.list</code></li>
</ul>
<p><code>designcenter.operations.get</code></p>
<p><code>designcenter.operations.list</code></p>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.createContext</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.deleteContext</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.move</code></p>
<p><code>storage.objects.restore</code></p>
<p><code>storage.objects.update</code></p>
<p><code>storage.objects.updateContext</code></p></td>
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
<td>DesignCenter Service Agent
<p>( <code>roles/ designcenter.serviceAgent</code> )</p>
<p>Gives the DesignCenter API Service Account access to necessary GCP resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.boundaries.attach</code></p>
<p><code>apphub.boundaries.update</code></p>
<p><code>apphub.discoveredServices.*</code></p>
<ul>
<li><code>apphub.discoveredServices.get</code></li>
<li><code>apphub.discoveredServices.list</code></li>
<li><code>apphub. discoveredServices. register</code></li>
</ul>
<p><code>apphub.discoveredWorkloads.*</code></p>
<ul>
<li><code>apphub.discoveredWorkloads.get</code></li>
<li><code>apphub. discoveredWorkloads. list</code></li>
<li><code>apphub. discoveredWorkloads. register</code></li>
</ul>
<p><code>apphub.operations.get</code></p>
<p><code>apphub.operations.list</code></p>
<p><code>apphub. serviceProjectAttachments. get</code></p>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>apphub. serviceProjectAttachments. lookup</code></p>
<p><code>apphub.services.create</code></p>
<p><code>apphub.workloads.create</code></p>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.create</code></p>
<p><code>config.deploymentgroups.delete</code></p>
<p><code>config. deploymentgroups. deprovision</code></p>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. provision</code></p>
<p><code>config.deploymentgroups.update</code></p>
<p><code>config.deployments.create</code></p>
<p><code>config.deployments.delete</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config.deployments.getState</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.deployments.lock</code></p>
<p><code>config.deployments.unlock</code></p>
<p><code>config.deployments.update</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.*</code></p>
<ul>
<li><code>config.operations.cancel</code></li>
<li><code>config.operations.delete</code></li>
<li><code>config.operations.get</code></li>
<li><code>config.operations.list</code></li>
</ul>
<p><code>config.previews.create</code></p>
<p><code>config.previews.delete</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.*</code></p>
<ul>
<li><code>config.revisions.get</code></li>
<li><code>config.revisions.getState</code></li>
<li><code>config.revisions.list</code></li>
</ul>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyWrite</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage. managedFolders. getIamPolicy</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Application Design Center permissions

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
<td><code>designcenter. applicationTemplateRevisions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. applicationTemplateRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>designcenter. applicationTemplateRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. applicationTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. applicationTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. applicationTemplates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>designcenter. applicationTemplates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. applicationTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>designcenter. applications. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. applications. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.applications.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.applications.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. applications. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. catalogTemplateRevisions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. catalogTemplateRevisions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. catalogTemplateRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. catalogTemplateRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. catalogTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. catalogTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. catalogTemplates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. catalogTemplates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. catalogTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.catalogs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.catalogs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.catalogs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.catalogs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.catalogs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.components.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.components.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.components.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.components.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.components.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. connections. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. connections. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.connections.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.connections.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. connections. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>designcenter.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>designcenter.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. sharedTemplateRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. sharedTemplateRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter. sharedTemplates. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. sharedTemplates. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.shares.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.shares.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.shares.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.shares.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.spaces.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter.spaces.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.spaces.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. spaces. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.spaces.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>designcenter. spaces. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>designcenter.spaces.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
