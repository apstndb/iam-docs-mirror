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
<td>Security Center Management Admin
<p>( <code>roles/ securitycentermanagement.admin</code> )</p>
<p>Full access to manage Cloud Security Command Center services and custom modules configuration.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter. organizationsettings.*</code></p>
<ul>
<li><code>securitycenter. organizationsettings. get</code></li>
<li><code>securitycenter. organizationsettings. update</code></li>
</ul>
<p><code>securitycenter. securitycentersettings.*</code></p>
<ul>
<li><code>securitycenter. securitycentersettings. get</code></li>
<li><code>securitycenter. securitycentersettings. update</code></li>
</ul>
<p><code>securitycentermanagement.*</code></p>
<ul>
<li><code>securitycentermanagement. billingMetadata. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></li>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
<li><code>securitycentermanagement. operations. cancel</code></li>
<li><code>securitycentermanagement. operations. delete</code></li>
<li><code>securitycentermanagement. operations. get</code></li>
<li><code>securitycentermanagement. operations. list</code></li>
<li><code>securitycentermanagement. securityCenter. get</code></li>
<li><code>securitycentermanagement. securityCenter. migrate</code></li>
<li><code>securitycentermanagement. securityCenter. update</code></li>
<li><code>securitycentermanagement. securityCenterServices. get</code></li>
<li><code>securitycentermanagement. securityCenterServices. list</code></li>
<li><code>securitycentermanagement. securityCenterServices. update</code></li>
<li><code>securitycentermanagement. securityCommandCenter. activate</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkEligibility</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></li>
<li><code>securitycentermanagement. securityCommandCenter. generateServiceAccounts</code></li>
<li><code>securitycentermanagement. securityCommandCenter. get</code></li>
<li><code>securitycentermanagement. securityCommandCenter. update</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Security Center Management Editor
<p>( <code>roles/ securitycentermanagement.editor</code> )</p>
<p>Editor role for Security Center Management</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter. organizationsettings. get</code></p>
<p><code>securitycenter. securitycentersettings. get</code></p>
<p><code>securitycentermanagement. billingMetadata. get</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. operations.*</code></p>
<ul>
<li><code>securitycentermanagement. operations. cancel</code></li>
<li><code>securitycentermanagement. operations. delete</code></li>
<li><code>securitycentermanagement. operations. get</code></li>
<li><code>securitycentermanagement. operations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityCenter. get</code></p>
<p><code>securitycentermanagement. securityCenter. migrate</code></p>
<p><code>securitycentermanagement. securityCenterServices.*</code></p>
<ul>
<li><code>securitycentermanagement. securityCenterServices. get</code></li>
<li><code>securitycentermanagement. securityCenterServices. list</code></li>
<li><code>securitycentermanagement. securityCenterServices. update</code></li>
</ul>
<p><code>securitycentermanagement. securityCommandCenter.*</code></p>
<ul>
<li><code>securitycentermanagement. securityCommandCenter. activate</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkEligibility</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></li>
<li><code>securitycentermanagement. securityCommandCenter. generateServiceAccounts</code></li>
<li><code>securitycentermanagement. securityCommandCenter. get</code></li>
<li><code>securitycentermanagement. securityCommandCenter. update</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management Viewer
<p>( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p>Readonly access to Cloud Security Command Center services and custom modules configuration.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter. organizationsettings. get</code></p>
<p><code>securitycenter. securitycentersettings. get</code></p>
<p><code>securitycentermanagement. billingMetadata. get</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></p>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. operations. get</code></p>
<p><code>securitycentermanagement. operations. list</code></p>
<p><code>securitycentermanagement. securityCenter. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></p>
<p><code>securitycentermanagement. securityCommandCenter. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></p></td>
</tr>
<tr class="even">
<td>Security Center Management Custom Modules Editor
<p>( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management Custom Modules Viewer
<p>( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></p>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></p></td>
</tr>
<tr class="even">
<td>Security Center Management Custom ETD Modules Editor
<p>( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center ETD custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management ETD Custom Modules Viewer
<p>( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center ETD custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></p>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Security Center Management Services Editor
<p>( <code>roles/ securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center services configuration.</p></td>
<td><p><code>securitycentermanagement. securityCenterServices.*</code></p>
<ul>
<li><code>securitycentermanagement. securityCenterServices. get</code></li>
<li><code>securitycentermanagement. securityCenterServices. list</code></li>
<li><code>securitycentermanagement. securityCenterServices. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management Services Viewer
<p>( <code>roles/ securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center services configuration.</p></td>
<td><p><code>securitycentermanagement. securityCenterServices. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p></td>
</tr>
<tr class="even">
<td>Security Center Management Settings Editor
<p>( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center settings</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter. organizationsettings.*</code></p>
<ul>
<li><code>securitycenter. organizationsettings. get</code></li>
<li><code>securitycenter. organizationsettings. update</code></li>
</ul>
<p><code>securitycenter. securitycentersettings.*</code></p>
<ul>
<li><code>securitycenter. securitycentersettings. get</code></li>
<li><code>securitycenter. securitycentersettings. update</code></li>
</ul>
<p><code>securitycentermanagement. billingMetadata. get</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></li>
<li><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityCenterServices.*</code></p>
<ul>
<li><code>securitycentermanagement. securityCenterServices. get</code></li>
<li><code>securitycentermanagement. securityCenterServices. list</code></li>
<li><code>securitycentermanagement. securityCenterServices. update</code></li>
</ul>
<p><code>securitycentermanagement. securityCommandCenter.*</code></p>
<ul>
<li><code>securitycentermanagement. securityCommandCenter. activate</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkEligibility</code></li>
<li><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></li>
<li><code>securitycentermanagement. securityCommandCenter. generateServiceAccounts</code></li>
<li><code>securitycentermanagement. securityCommandCenter. get</code></li>
<li><code>securitycentermanagement. securityCommandCenter. update</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management Settings Viewer
<p>( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center settings</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter. organizationsettings. get</code></p>
<p><code>securitycenter. securitycentersettings. get</code></p>
<p><code>securitycentermanagement. billingMetadata. get</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></p>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityCenterServices. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></p>
<p><code>securitycentermanagement. securityCommandCenter. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></p></td>
</tr>
<tr class="even">
<td>Security Center Management SHA Custom Modules Editor
<p>( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p>Full access to manage Cloud Security Command Center SHA custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></li>
<li><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Security Center Management SHA Custom Modules Viewer
<p>( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Readonly access to Cloud Security Command Center SHA custom modules.</p></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></p></td>
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
<td><code>securitycentermanagement. billingMetadata. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCenter. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCenter. migrate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCenter. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCenterServices. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code>roles/ securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesViewer">Security Center Management Services Viewer</a> ( <code>roles/ securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCenterServices. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code>roles/ securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesViewer">Security Center Management Services Viewer</a> ( <code>roles/ securitycentermanagement.securityCenterServicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCenterServices. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.securityCenterServicesEditor">Security Center Management Services Editor</a> ( <code>roles/ securitycentermanagement.securityCenterServicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCommandCenter. activate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code>roles/ recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code>roles/ recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCommandCenter. checkEligibility</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code>roles/ recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCommandCenter. generateServiceAccounts</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityCommandCenter. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityCommandCenter. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code>roles/ securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code>roles/ securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>securitycentermanagement. securityHealthAnalyticsCustomModules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
