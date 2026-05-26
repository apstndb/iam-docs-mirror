---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement
title: Security Center Management API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Security Center Management API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Security Center Management API roles

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
<td><h4 id="securitycentermanagement.admin" class="role-title add-link" data-text="Security Center Management Admin" tabindex="-1">Security Center Management Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p>Full access to manage Cloud Security Command Center services and custom modules configuration.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.editor" class="role-title add-link" data-text="Securitycentermanagement Editor" tabindex="-1">Securitycentermanagement Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p>Editor role for securitycentermanagement</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.viewer" class="role-title add-link" data-text="Security Center Management Viewer" tabindex="-1">Security Center Management Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p>Readonly access to Cloud Security Command Center services and custom modules configuration.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.customModulesEditor" class="role-title add-link" data-text="Security Center Management Custom Modules Editor" tabindex="-1">Security Center Management Custom Modules Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.customModulesViewer" class="role-title add-link" data-text="Security Center Management Custom Modules Viewer" tabindex="-1">Security Center Management Custom Modules Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.etdCustomModulesEditor" class="role-title add-link" data-text="Security Center Management Custom ETD Modules Editor" tabindex="-1">Security Center Management Custom ETD Modules Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center ETD custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.etdCustomModulesViewer" class="role-title add-link" data-text="Security Center Management ETD Custom Modules Viewer" tabindex="-1">Security Center Management ETD Custom Modules Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center ETD custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCenterServicesEditor" class="role-title add-link" data-text="Security Center Management Services Editor" tabindex="-1">Security Center Management Services Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center services configuration.</p></td>
<td><p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCenterServicesViewer" class="role-title add-link" data-text="Security Center Management Services Viewer" tabindex="-1">Security Center Management Services Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center services configuration.</p></td>
<td><p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.settingsEditor" class="role-title add-link" data-text="Security Center Management Settings Editor" tabindex="-1">Security Center Management Settings Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center settings</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.settingsViewer" class="role-title add-link" data-text="Security Center Management Settings Viewer" tabindex="-1">Security Center Management Settings Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center settings</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.shaCustomModulesEditor" class="role-title add-link" data-text="Security Center Management SHA Custom Modules Editor" tabindex="-1">Security Center Management SHA Custom Modules Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center SHA custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.shaCustomModulesViewer" class="role-title add-link" data-text="Security Center Management SHA Custom Modules Viewer" tabindex="-1">Security Center Management SHA Custom Modules Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center SHA custom modules.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
</tbody>
</table>

## Security Center Management API permissions

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
<td><h4 id="securitycentermanagement.billingMetadata.get" class="permission-name add-link" data-text="securitycentermanagement.billingMetadata.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.effectiveEventThreatDetectionCustomModules.get" class="permission-name add-link" data-text="securitycentermanagement.effectiveEventThreatDetectionCustomModules.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.effectiveEventThreatDetectionCustomModules.list" class="permission-name add-link" data-text="securitycentermanagement.effectiveEventThreatDetectionCustomModules.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.effectiveSecurityHealthAnalyticsCustomModules.get" class="permission-name add-link" data-text="securitycentermanagement.effectiveSecurityHealthAnalyticsCustomModules.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.effectiveSecurityHealthAnalyticsCustomModules.list" class="permission-name add-link" data-text="securitycentermanagement.effectiveSecurityHealthAnalyticsCustomModules.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.create" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.create" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.delete" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.delete" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.get" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.list" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.update" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.update" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.eventThreatDetectionCustomModules.validate" class="permission-name add-link" data-text="securitycentermanagement.eventThreatDetectionCustomModules.validate" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.locations.get" class="permission-name add-link" data-text="securitycentermanagement.locations.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.locations.list" class="permission-name add-link" data-text="securitycentermanagement.locations.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.operations.cancel" class="permission-name add-link" data-text="securitycentermanagement.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.operations.delete" class="permission-name add-link" data-text="securitycentermanagement.operations.delete" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.operations.get" class="permission-name add-link" data-text="securitycentermanagement.operations.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.operations.list" class="permission-name add-link" data-text="securitycentermanagement.operations.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCenter.get" class="permission-name add-link" data-text="securitycentermanagement.securityCenter.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCenter.migrate" class="permission-name add-link" data-text="securitycentermanagement.securityCenter.migrate" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCenter.update" class="permission-name add-link" data-text="securitycentermanagement.securityCenter.update" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCenterServices.get" class="permission-name add-link" data-text="securitycentermanagement.securityCenterServices.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesViewer">Security Center Management Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCenterServices.list" class="permission-name add-link" data-text="securitycentermanagement.securityCenterServices.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesViewer">Security Center Management Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCenterServices.update" class="permission-name add-link" data-text="securitycentermanagement.securityCenterServices.update" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCommandCenter.activate" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.activate" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCommandCenter.checkActivationOperation" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.checkActivationOperation" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCommandCenter.checkEligibility" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.checkEligibility" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCommandCenter.checkOnboardingStatus" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.checkOnboardingStatus" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCommandCenter.generateServiceAccounts" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.generateServiceAccounts" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityCommandCenter.get" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityCommandCenter.update" class="permission-name add-link" data-text="securitycentermanagement.securityCommandCenter.update" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.create" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.create" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.delete" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.delete" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.get" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.get" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.list" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.list" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.simulate" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.simulate" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.test" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.test" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycentermanagement.securityHealthAnalyticsCustomModules.update" class="permission-name add-link" data-text="securitycentermanagement.securityHealthAnalyticsCustomModules.update" tabindex="-1"><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
