---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/iam
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/iam
title: Identity and Access Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Identity and Access Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Identity and Access Management roles

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
<td>Access Policy Admin <sup>Beta</sup>
<p>( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p>Access Policy admin role, with permissions to read and modify access policies, and to bind and unbind access policies to targets.</p></td>
<td><p><code>iam.accesspolicies.*</code></p>
<ul>
<li><code>iam.accesspolicies.bind</code></li>
<li><code>iam.accesspolicies.create</code></li>
<li><code>iam.accesspolicies.delete</code></li>
<li><code>iam.accesspolicies.get</code></li>
<li><code>iam.accesspolicies.list</code></li>
<li><code>iam. accesspolicies. searchPolicyBindings</code></li>
<li><code>iam.accesspolicies.unbind</code></li>
<li><code>iam.accesspolicies.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Iam Admin
<p>( <code>roles/ iam.admin</code> )</p>
<p>Admin role for iam</p></td>
<td><p><code>iam.accesspolicies.*</code></p>
<ul>
<li><code>iam.accesspolicies.bind</code></li>
<li><code>iam.accesspolicies.create</code></li>
<li><code>iam.accesspolicies.delete</code></li>
<li><code>iam.accesspolicies.get</code></li>
<li><code>iam.accesspolicies.list</code></li>
<li><code>iam. accesspolicies. searchPolicyBindings</code></li>
<li><code>iam.accesspolicies.unbind</code></li>
<li><code>iam.accesspolicies.update</code></li>
</ul>
<p><code>iam.denypolicies.get</code></p>
<p><code>iam.denypolicies.list</code></p>
<p><code>iam.oauthClientCredentials.*</code></p>
<ul>
<li><code>iam.googleapis. com/oauthClientCredentials. create</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. delete</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. get</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. list</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. update</code></li>
</ul>
<p><code>iam.oauthClients.*</code></p>
<ul>
<li><code>iam.googleapis. com/oauthClients. create</code></li>
<li><code>iam.googleapis. com/oauthClients. delete</code></li>
<li><code>iam.googleapis. com/oauthClients. get</code></li>
<li><code>iam.googleapis. com/oauthClients. list</code></li>
<li><code>iam.googleapis. com/oauthClients. undelete</code></li>
<li><code>iam.googleapis. com/oauthClients. update</code></li>
</ul>
<p><code>iam.operations.get</code></p>
<p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>iam. principalaccessboundarypolicies. get</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></p>
<p><code>iam.roles.*</code></p>
<ul>
<li><code>iam.roles.create</code></li>
<li><code>iam.roles.createTagBinding</code></li>
<li><code>iam.roles.delete</code></li>
<li><code>iam.roles.deleteTagBinding</code></li>
<li><code>iam.roles.get</code></li>
<li><code>iam.roles.list</code></li>
<li><code>iam.roles.listEffectiveTags</code></li>
<li><code>iam.roles.listTagBindings</code></li>
<li><code>iam.roles.undelete</code></li>
<li><code>iam.roles.update</code></li>
</ul>
<p><code>iam. serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code>iam. serviceAccountApiKeyBindings. create</code></li>
<li><code>iam. serviceAccountApiKeyBindings. delete</code></li>
<li><code>iam. serviceAccountApiKeyBindings. undelete</code></li>
</ul>
<p><code>iam.serviceAccountKeys.*</code></p>
<ul>
<li><code>iam.serviceAccountKeys.create</code></li>
<li><code>iam.serviceAccountKeys.delete</code></li>
<li><code>iam.serviceAccountKeys.disable</code></li>
<li><code>iam.serviceAccountKeys.enable</code></li>
<li><code>iam.serviceAccountKeys.get</code></li>
<li><code>iam.serviceAccountKeys.list</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam. serviceAccounts. createTagBinding</code></p>
<p><code>iam.serviceAccounts.delete</code></p>
<p><code>iam. serviceAccounts. deleteTagBinding</code></p>
<p><code>iam.serviceAccounts.disable</code></p>
<p><code>iam.serviceAccounts.enable</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>iam. serviceAccounts. setIamPolicy</code></p>
<p><code>iam.serviceAccounts.undelete</code></p>
<p><code>iam.serviceAccounts.update</code></p>
<p><code>iam. workforcePoolProviderKeys.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. undelete</code></li>
</ul>
<p><code>iam. workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. put</code></li>
</ul>
<p><code>iam. workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. put</code></li>
</ul>
<p><code>iam.workforcePoolProviders.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. undelete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. update</code></li>
</ul>
<p><code>iam.workforcePoolSubjects.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolSubjects. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolSubjects. revokeSessions</code></li>
<li><code>iam.googleapis. com/workforcePoolSubjects. undelete</code></li>
</ul>
<p><code>iam.workforcePools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePools. create</code></li>
<li><code>iam.googleapis. com/workforcePools. createPolicyBinding</code></li>
<li><code>iam.googleapis. com/workforcePools. delete</code></li>
<li><code>iam.googleapis. com/workforcePools. deletePolicyBinding</code></li>
<li><code>iam.googleapis. com/workforcePools. get</code></li>
<li><code>iam.googleapis. com/workforcePools. getIamPolicy</code></li>
<li><code>iam.googleapis. com/workforcePools. list</code></li>
<li><code>iam.googleapis. com/workforcePools. searchPolicyBindings</code></li>
<li><code>iam.googleapis. com/workforcePools. setIamPolicy</code></li>
<li><code>iam.googleapis. com/workforcePools. undelete</code></li>
<li><code>iam.googleapis. com/workforcePools. update</code></li>
<li><code>iam.googleapis. com/workforcePools. updatePolicyBinding</code></li>
</ul>
<p><code>iam. workloadIdentityPoolManagedIdentities.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. setAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. update</code></li>
</ul>
<p><code>iam. workloadIdentityPoolNamespaces.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. update</code></li>
</ul>
<p><code>iam. workloadIdentityPoolProviderKeys.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. undelete</code></li>
</ul>
<p><code>iam. workloadIdentityPoolProviders.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. update</code></li>
</ul>
<p><code>iam.workloadIdentityPools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPools. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. setAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. setIamPolicy</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. update</code></li>
<li><code>iam. workloadIdentityPools. createPolicyBinding</code></li>
<li><code>iam. workloadIdentityPools. deletePolicyBinding</code></li>
<li><code>iam. workloadIdentityPools. searchPolicyBindings</code></li>
<li><code>iam. workloadIdentityPools. updatePolicyBinding</code></li>
</ul>
<p><code>iam.workspacePools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workspacePools. createPolicyBinding</code></li>
<li><code>iam.googleapis. com/workspacePools. deletePolicyBinding</code></li>
<li><code>iam.googleapis. com/workspacePools. searchPolicyBindings</code></li>
<li><code>iam.googleapis. com/workspacePools. updatePolicyBinding</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Iam Editor
<p>( <code>roles/ iam.editor</code> )</p>
<p>Editor role for iam</p></td>
<td><p><code>iam.accesspolicies.get</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam. accesspolicies. searchPolicyBindings</code></p>
<p><code>iam.denypolicies.get</code></p>
<p><code>iam.denypolicies.list</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. get</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. list</code></p>
<p><code>iam.googleapis. com/oauthClients. get</code></p>
<p><code>iam.googleapis. com/oauthClients. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. get</code></p>
<p><code>iam.googleapis. com/workforcePools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workforcePools. searchPolicyBindings</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>iam.googleapis. com/workspacePools. searchPolicyBindings</code></p>
<p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>iam. principalaccessboundarypolicies. get</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam. serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code>iam. serviceAccountApiKeyBindings. create</code></li>
<li><code>iam. serviceAccountApiKeyBindings. delete</code></li>
<li><code>iam. serviceAccountApiKeyBindings. undelete</code></li>
</ul>
<p><code>iam.serviceAccountKeys.*</code></p>
<ul>
<li><code>iam.serviceAccountKeys.create</code></li>
<li><code>iam.serviceAccountKeys.delete</code></li>
<li><code>iam.serviceAccountKeys.disable</code></li>
<li><code>iam.serviceAccountKeys.enable</code></li>
<li><code>iam.serviceAccountKeys.get</code></li>
<li><code>iam.serviceAccountKeys.list</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.delete</code></p>
<p><code>iam.serviceAccounts.disable</code></p>
<p><code>iam.serviceAccounts.enable</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>iam.serviceAccounts.update</code></p>
<p><code>iam. workloadIdentityPools. searchPolicyBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Principal Access Boundary Policy Viewer
<p>( <code>roles/ iam.principalAccessBoundaryViewer</code> )</p>
<p>Read-only access to Principal Access Boundary policies and their associated bindings.</p></td>
<td><p><code>iam. principalaccessboundarypolicies. get</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></p></td>
</tr>
<tr class="odd">
<td>Role Administrator
<p>( <code>roles/ iam.roleAdmin</code> )</p>
<p>Provides access to all custom roles in the project. This role can only be granted at the project level.</p></td>
<td><p><code>iam.roles.*</code></p>
<ul>
<li><code>iam.roles.create</code></li>
<li><code>iam.roles.createTagBinding</code></li>
<li><code>iam.roles.delete</code></li>
<li><code>iam.roles.deleteTagBinding</code></li>
<li><code>iam.roles.get</code></li>
<li><code>iam.roles.list</code></li>
<li><code>iam.roles.listEffectiveTags</code></li>
<li><code>iam.roles.listTagBindings</code></li>
<li><code>iam.roles.undelete</code></li>
<li><code>iam.roles.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p></td>
</tr>
<tr class="even">
<td>Role Viewer
<p>( <code>roles/ iam.roleViewer</code> )</p>
<p>Provides read access to all custom roles in the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td>Security Admin
<p>( <code>roles/ iam.securityAdmin</code> )</p>
<p>Security admin role, with permissions to get and set any IAM policy.</p></td>
<td><p><code>accessapproval.requests.list</code></p>
<p><code>accesscontextmanager. accessLevels. list</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. list</code></p>
<p><code>accesscontextmanager. gcpUserAccessBindings. list</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. policies. setIamPolicy</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>actions.agentVersions.list</code></p>
<p><code>advisorynotifications. notifications.*</code></p>
<ul>
<li><code>advisorynotifications. notifications. get</code></li>
<li><code>advisorynotifications. notifications. list</code></li>
</ul>
<p><code>agentidentity. accessSummaries. list</code></p>
<p><code>agentidentity. authProviders. getIamPolicy</code></p>
<p><code>agentidentity. authProviders. list</code></p>
<p><code>agentidentity. authProviders. setIamPolicy</code></p>
<p><code>agentidentity. authorizations. list</code></p>
<p><code>agentidentity.locations.list</code></p>
<p><code>agentregistry.agents.list</code></p>
<p><code>agentregistry.bindings.list</code></p>
<p><code>agentregistry.endpoints.list</code></p>
<p><code>agentregistry.locations.list</code></p>
<p><code>agentregistry.mcpServers.list</code></p>
<p><code>agentregistry.operations.list</code></p>
<p><code>agentregistry.publishers.list</code></p>
<p><code>agentregistry.services.list</code></p>
<p><code>agentregistry. skillRevisions. list</code></p>
<p><code>agentregistry. skills. getIamPolicy</code></p>
<p><code>agentregistry.skills.list</code></p>
<p><code>agentregistry. skills. setIamPolicy</code></p>
<p><code>aiplatform. agentAnomalyDetectionScopes. list</code></p>
<p><code>aiplatform.agentExamples.list</code></p>
<p><code>aiplatform.agents.list</code></p>
<p><code>aiplatform. analyzedInvocations. list</code></p>
<p><code>aiplatform. analyzedSessions. list</code></p>
<p><code>aiplatform. annotationSpecs. list</code></p>
<p><code>aiplatform.annotations.list</code></p>
<p><code>aiplatform.apps.list</code></p>
<p><code>aiplatform.artifacts.list</code></p>
<p><code>aiplatform. batchPredictionJobs. list</code></p>
<p><code>aiplatform.cachedContents.list</code></p>
<p><code>aiplatform.contexts.list</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform.dataItems.list</code></p>
<p><code>aiplatform. dataLabelingJobs. list</code></p>
<p><code>aiplatform. datasetVersions. list</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform. deploymentResourcePools. list</code></p>
<p><code>aiplatform. edgeDeploymentJobs. list</code></p>
<p><code>aiplatform.edgeDevices.list</code></p>
<p><code>aiplatform. endpoints. getIamPolicy</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform. endpoints. setIamPolicy</code></p>
<p><code>aiplatform. entityTypes. getIamPolicy</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform. entityTypes. setIamPolicy</code></p>
<p><code>aiplatform. evaluationExperiments. list</code></p>
<p><code>aiplatform. evaluationItems. list</code></p>
<p><code>aiplatform. evaluationMetrics. list</code></p>
<p><code>aiplatform.evaluationRuns.list</code></p>
<p><code>aiplatform.evaluationSets.list</code></p>
<p><code>aiplatform.exampleStores.list</code></p>
<p><code>aiplatform.executions.list</code></p>
<p><code>aiplatform.extensions.list</code></p>
<p><code>aiplatform. featureGroups. getIamPolicy</code></p>
<p><code>aiplatform.featureGroups.list</code></p>
<p><code>aiplatform. featureGroups. setIamPolicy</code></p>
<p><code>aiplatform. featureMonitorJobs. list</code></p>
<p><code>aiplatform. featureMonitors. list</code></p>
<p><code>aiplatform. featureOnlineStores. getIamPolicy</code></p>
<p><code>aiplatform. featureOnlineStores. list</code></p>
<p><code>aiplatform. featureOnlineStores. setIamPolicy</code></p>
<p><code>aiplatform. featureViewSyncs. list</code></p>
<p><code>aiplatform. featureViews. getIamPolicy</code></p>
<p><code>aiplatform.featureViews.list</code></p>
<p><code>aiplatform. featureViews. setIamPolicy</code></p>
<p><code>aiplatform.features.list</code></p>
<p><code>aiplatform. featurestores. getIamPolicy</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform. featurestores. setIamPolicy</code></p>
<p><code>aiplatform. humanInTheLoops. list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.indexEndpoints.list</code></p>
<p><code>aiplatform.indexes.list</code></p>
<p><code>aiplatform.interactions.list</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>aiplatform.memories.list</code></p>
<p><code>aiplatform. memoryRevisions. list</code></p>
<p><code>aiplatform. metadataSchemas. list</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. list</code></p>
<p><code>aiplatform. modelEvaluationSlices. list</code></p>
<p><code>aiplatform. modelEvaluations. list</code></p>
<p><code>aiplatform. modelMonitoringJobs. list</code></p>
<p><code>aiplatform.modelMonitors.list</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform. monitoredAgents. list</code></p>
<p><code>aiplatform.nasJobs.list</code></p>
<p><code>aiplatform. nasTrialDetails. list</code></p>
<p><code>aiplatform. notebookExecutionJobs. list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. getIamPolicy</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. setIamPolicy</code></p>
<p><code>aiplatform. notebookRuntimes. list</code></p>
<p><code>aiplatform. onlineEvaluators. list</code></p>
<p><code>aiplatform.operations.list</code></p>
<p><code>aiplatform. persistentResources. list</code></p>
<p><code>aiplatform.pipelineJobs.list</code></p>
<p><code>aiplatform. provisionedThroughputRevisions. list</code></p>
<p><code>aiplatform. provisionedThroughputs. list</code></p>
<p><code>aiplatform.ragCorpora.list</code></p>
<p><code>aiplatform.ragFiles.list</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. list</code></p>
<p><code>aiplatform. reasoningEngines. getIamPolicy</code></p>
<p><code>aiplatform. reasoningEngines. list</code></p>
<p><code>aiplatform. reasoningEngines. setIamPolicy</code></p>
<p><code>aiplatform. sandboxEnvironments. list</code></p>
<p><code>aiplatform.schedules.list</code></p>
<p><code>aiplatform. semanticGovernancePolicies. list</code></p>
<p><code>aiplatform.sessionEvents.list</code></p>
<p><code>aiplatform.sessions.list</code></p>
<p><code>aiplatform. specialistPools. list</code></p>
<p><code>aiplatform.studies.list</code></p>
<p><code>aiplatform.tasks.list</code></p>
<p><code>aiplatform. tensorboardExperiments. list</code></p>
<p><code>aiplatform. tensorboardRuns. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. list</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>aiplatform.trials.list</code></p>
<p><code>aiplatform.tuningJobs.list</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb.databases.list</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>alloydb.locations.list</code></p>
<p><code>alloydb.operations.list</code></p>
<p><code>alloydb. supportedDatabaseFlags. list</code></p>
<p><code>alloydb.users.list</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub. dataExchanges. setIamPolicy</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. listings. setIamPolicy</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>analyticshub. subscriptions. list</code></p>
<p><code>apigateway. apiconfigs. getIamPolicy</code></p>
<p><code>apigateway.apiconfigs.list</code></p>
<p><code>apigateway. apiconfigs. setIamPolicy</code></p>
<p><code>apigateway.apis.getIamPolicy</code></p>
<p><code>apigateway.apis.list</code></p>
<p><code>apigateway.apis.setIamPolicy</code></p>
<p><code>apigateway. gateways. getIamPolicy</code></p>
<p><code>apigateway.gateways.list</code></p>
<p><code>apigateway. gateways. setIamPolicy</code></p>
<p><code>apigateway.locations.list</code></p>
<p><code>apigateway.operations.list</code></p>
<p><code>apigee. apiproductattributes. list</code></p>
<p><code>apigee.apiproducts.list</code></p>
<p><code>apigee.appgroupapps.list</code></p>
<p><code>apigee.appgroups.list</code></p>
<p><code>apigee. appgroupsubscriptions. list</code></p>
<p><code>apigee.apps.list</code></p>
<p><code>apigee.archivedeployments.list</code></p>
<p><code>apigee.caches.list</code></p>
<p><code>apigee.datacollectors.list</code></p>
<p><code>apigee.datastores.list</code></p>
<p><code>apigee. deployments. getIamPolicy</code></p>
<p><code>apigee.deployments.list</code></p>
<p><code>apigee. deployments. setIamPolicy</code></p>
<p><code>apigee. developerappattributes. list</code></p>
<p><code>apigee.developerapps.list</code></p>
<p><code>apigee. developerattributes. list</code></p>
<p><code>apigee.developers.list</code></p>
<p><code>apigee. developersubscriptions. list</code></p>
<p><code>apigee.dnsZones.list</code></p>
<p><code>apigee. endpointattachments. list</code></p>
<p><code>apigee. envgroupattachments. list</code></p>
<p><code>apigee.envgroups.list</code></p>
<p><code>apigee. environments. getIamPolicy</code></p>
<p><code>apigee.environments.list</code></p>
<p><code>apigee. environments. setIamPolicy</code></p>
<p><code>apigee.exports.list</code></p>
<p><code>apigee.flowhooks.list</code></p>
<p><code>apigee.hostqueries.list</code></p>
<p><code>apigee. hostsecurityreports. list</code></p>
<p><code>apigee. instanceattachments. list</code></p>
<p><code>apigee.instances.list</code></p>
<p><code>apigee.keystorealiases.list</code></p>
<p><code>apigee.keystores.list</code></p>
<p><code>apigee.keyvaluemapentries.list</code></p>
<p><code>apigee.keyvaluemaps.list</code></p>
<p><code>apigee.nataddresses.list</code></p>
<p><code>apigee.operations.list</code></p>
<p><code>apigee.organizations.list</code></p>
<p><code>apigee.portals.list</code></p>
<p><code>apigee.proxies.list</code></p>
<p><code>apigee.proxyrevisions.list</code></p>
<p><code>apigee.queries.list</code></p>
<p><code>apigee.rateplans.list</code></p>
<p><code>apigee.references.list</code></p>
<p><code>apigee.reports.list</code></p>
<p><code>apigee.resourcefiles.list</code></p>
<p><code>apigee.securityActions.list</code></p>
<p><code>apigee.securityFeedback.list</code></p>
<p><code>apigee.securityIncidents.list</code></p>
<p><code>apigee. securityMonitoringConditions. list</code></p>
<p><code>apigee.securityProfiles.list</code></p>
<p><code>apigee.securityProfilesV2.list</code></p>
<p><code>apigee.securityreports.list</code></p>
<p><code>apigee. sharedflowrevisions. list</code></p>
<p><code>apigee.sharedflows.list</code></p>
<p><code>apigee.spaces.getIamPolicy</code></p>
<p><code>apigee.spaces.list</code></p>
<p><code>apigee.spaces.setIamPolicy</code></p>
<p><code>apigee.targetservers.list</code></p>
<p><code>apigee. traceconfigoverrides. list</code></p>
<p><code>apigee.tracesessions.list</code></p>
<p><code>apigeeconnect.connections.list</code></p>
<p><code>apigeeregistry. apis. getIamPolicy</code></p>
<p><code>apigeeregistry.apis.list</code></p>
<p><code>apigeeregistry. apis. setIamPolicy</code></p>
<p><code>apigeeregistry. artifacts. getIamPolicy</code></p>
<p><code>apigeeregistry.artifacts.list</code></p>
<p><code>apigeeregistry. artifacts. setIamPolicy</code></p>
<p><code>apigeeregistry. deployments. list</code></p>
<p><code>apigeeregistry.locations.list</code></p>
<p><code>apigeeregistry.operations.list</code></p>
<p><code>apigeeregistry. specs. getIamPolicy</code></p>
<p><code>apigeeregistry.specs.list</code></p>
<p><code>apigeeregistry. specs. setIamPolicy</code></p>
<p><code>apigeeregistry. versions. getIamPolicy</code></p>
<p><code>apigeeregistry.versions.list</code></p>
<p><code>apigeeregistry. versions. setIamPolicy</code></p>
<p><code>apihub.addons.list</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apiOperations.list</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.attributes.list</code></p>
<p><code>apihub.curations.list</code></p>
<p><code>apihub.definitions.list</code></p>
<p><code>apihub.dependencies.list</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub. discoveredApiObservations. list</code></p>
<p><code>apihub. discoveredApiOperations. list</code></p>
<p><code>apihub.externalApis.list</code></p>
<p><code>apihub. hostProjectRegistrations. list</code></p>
<p><code>apihub.llmEnablements.list</code></p>
<p><code>apihub.operations.list</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub. runTimeProjectAttachments. list</code></p>
<p><code>apihub.specs.list</code></p>
<p><code>apihub.versions.list</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apim.apiObservations.list</code></p>
<p><code>apim.apiOperations.list</code></p>
<p><code>apim.locations.list</code></p>
<p><code>apim.observationJobs.list</code></p>
<p><code>apim.observationSources.list</code></p>
<p><code>apim.operations.list</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.memcache.list</code></p>
<p><code>appengine.operations.list</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>apphub. applications. getIamPolicy</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub. applications. setIamPolicy</code></p>
<p><code>apphub.discoveredServices.list</code></p>
<p><code>apphub. discoveredWorkloads. list</code></p>
<p><code>apphub. extendedMetadataSchemas. list</code></p>
<p><code>apphub.locations.list</code></p>
<p><code>apphub.operations.list</code></p>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>applianceactivation. rttCommands. list</code></p>
<p><code>appoptimize.locations.list</code></p>
<p><code>appoptimize.operations.list</code></p>
<p><code>appoptimize.reports.list</code></p>
<p><code>apptopology.domains.list</code></p>
<p><code>apptopology.locations.list</code></p>
<p><code>apptopology.operations.list</code></p>
<p><code>apptopology.topologyViews.list</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages. list</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry. locations. list</code></p>
<p><code>artifactregistry. mavenartifacts. list</code></p>
<p><code>artifactregistry. npmpackages. list</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. pythonpackages. list</code></p>
<p><code>artifactregistry. repositories. getIamPolicy</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry. repositories. setIamPolicy</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.locations.list</code></p>
<p><code>assuredoss.metadata.list</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>assuredworkloads. dbControlComplianceSummaries. list</code></p>
<p><code>assuredworkloads. dbFindingSummaries. list</code></p>
<p><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></p>
<p><code>assuredworkloads. operations. list</code></p>
<p><code>assuredworkloads.updates.list</code></p>
<p><code>assuredworkloads. violations. list</code></p>
<p><code>assuredworkloads.workload.list</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. controlReports. list</code></p>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager. customComplianceFrameworks. list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.list</code></p>
<p><code>auditmanager. resourceEnrollmentStatuses. list</code></p>
<p><code>automl.annotationSpecs.list</code></p>
<p><code>automl.annotations.list</code></p>
<p><code>automl.columnSpecs.list</code></p>
<p><code>automl.datasets.getIamPolicy</code></p>
<p><code>automl.datasets.list</code></p>
<p><code>automl.datasets.setIamPolicy</code></p>
<p><code>automl.examples.list</code></p>
<p><code>automl.files.list</code></p>
<p><code>automl. humanAnnotationTasks. list</code></p>
<p><code>automl.locations.getIamPolicy</code></p>
<p><code>automl.locations.list</code></p>
<p><code>automl.locations.setIamPolicy</code></p>
<p><code>automl.modelEvaluations.list</code></p>
<p><code>automl.models.getIamPolicy</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.models.setIamPolicy</code></p>
<p><code>automl.operations.list</code></p>
<p><code>automl.tableSpecs.list</code></p>
<p><code>automlrecommendations. apiKeys. list</code></p>
<p><code>automlrecommendations. catalogItems. list</code></p>
<p><code>automlrecommendations. catalogs. list</code></p>
<p><code>automlrecommendations. eventStores. list</code></p>
<p><code>automlrecommendations. events. list</code></p>
<p><code>automlrecommendations. placements. list</code></p>
<p><code>automlrecommendations. recommendations. list</code></p>
<p><code>autoscaling.sites.getIamPolicy</code></p>
<p><code>autoscaling.sites.setIamPolicy</code></p>
<p><code>backupdr. appliedAutoProtectionPolicies. list</code></p>
<p><code>backupdr. autoProtectionBindings. list</code></p>
<p><code>backupdr. autoProtectionPolicies. list</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanRevisions. list</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. dataSourceReferences. list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. setIamPolicy</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. resourceBackupConfigs. list</code></p>
<p><code>baremetalsolution. instancequotas. list</code></p>
<p><code>baremetalsolution. instances. list</code></p>
<p><code>baremetalsolution.luns.list</code></p>
<p><code>baremetalsolution. maintenanceevents. list</code></p>
<p><code>baremetalsolution. networkquotas. list</code></p>
<p><code>baremetalsolution. networks. list</code></p>
<p><code>baremetalsolution. nfsshares. list</code></p>
<p><code>baremetalsolution. osimages. list</code></p>
<p><code>baremetalsolution.pods.list</code></p>
<p><code>baremetalsolution. procurements. list</code></p>
<p><code>baremetalsolution.skus.list</code></p>
<p><code>baremetalsolution. snapshotschedulepolicies. list</code></p>
<p><code>baremetalsolution.sshKeys.list</code></p>
<p><code>baremetalsolution. storageaggregatepools. list</code></p>
<p><code>baremetalsolution. volumequotas. list</code></p>
<p><code>baremetalsolution.volumes.list</code></p>
<p><code>baremetalsolution. volumesnapshots. list</code></p>
<p><code>batch.jobs.list</code></p>
<p><code>batch.locations.list</code></p>
<p><code>batch.operations.list</code></p>
<p><code>batch.resourceAllowances.list</code></p>
<p><code>batch.tasks.list</code></p>
<p><code>beyondcorp. appConnections. getIamPolicy</code></p>
<p><code>beyondcorp.appConnections.list</code></p>
<p><code>beyondcorp. appConnections. setIamPolicy</code></p>
<p><code>beyondcorp. appConnectors. getIamPolicy</code></p>
<p><code>beyondcorp.appConnectors.list</code></p>
<p><code>beyondcorp. appConnectors. setIamPolicy</code></p>
<p><code>beyondcorp. appGateways. getIamPolicy</code></p>
<p><code>beyondcorp.appGateways.list</code></p>
<p><code>beyondcorp. appGateways. setIamPolicy</code></p>
<p><code>beyondcorp.locations.list</code></p>
<p><code>beyondcorp.operations.list</code></p>
<p><code>beyondcorp. securityGateways. getIamPolicy</code></p>
<p><code>beyondcorp. securityGateways. list</code></p>
<p><code>beyondcorp. securityGateways. setIamPolicy</code></p>
<p><code>beyondcorp. sgApplications. getIamPolicy</code></p>
<p><code>beyondcorp.sgApplications.list</code></p>
<p><code>beyondcorp. sgApplications. setIamPolicy</code></p>
<p><code>beyondcorp.subscriptions.list</code></p>
<p><code>biglake.catalogs.getIamPolicy</code></p>
<p><code>biglake.catalogs.list</code></p>
<p><code>biglake.catalogs.setIamPolicy</code></p>
<p><code>biglake.databases.list</code></p>
<p><code>biglake.locks.list</code></p>
<p><code>biglake. namespaces. getIamPolicy</code></p>
<p><code>biglake.namespaces.list</code></p>
<p><code>biglake. namespaces. setIamPolicy</code></p>
<p><code>biglake.tables.getIamPolicy</code></p>
<p><code>biglake.tables.list</code></p>
<p><code>biglake.tables.setIamPolicy</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery. connections. getIamPolicy</code></p>
<p><code>bigquery.connections.list</code></p>
<p><code>bigquery. connections. setIamPolicy</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery. dataPolicies. setIamPolicy</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.datasets.setIamPolicy</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.models.list</code></p>
<p><code>bigquery.propertyGraphs.list</code></p>
<p><code>bigquery. reservationAssignments. list</code></p>
<p><code>bigquery. reservationGroups. list</code></p>
<p><code>bigquery. reservations. getIamPolicy</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery. reservations. setIamPolicy</code></p>
<p><code>bigquery.routines.list</code></p>
<p><code>bigquery. rowAccessPolicies. getIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. list</code></p>
<p><code>bigquery. rowAccessPolicies. setIamPolicy</code></p>
<p><code>bigquery.savedqueries.list</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery.tables.setIamPolicy</code></p>
<p><code>bigquerymigration. subtasks. list</code></p>
<p><code>bigquerymigration. workflows. list</code></p>
<p><code>bigtable.appProfiles.list</code></p>
<p><code>bigtable. authorizedViews. getIamPolicy</code></p>
<p><code>bigtable.authorizedViews.list</code></p>
<p><code>bigtable. authorizedViews. setIamPolicy</code></p>
<p><code>bigtable.backups.getIamPolicy</code></p>
<p><code>bigtable.backups.list</code></p>
<p><code>bigtable.backups.setIamPolicy</code></p>
<p><code>bigtable.clusters.list</code></p>
<p><code>bigtable.hotTablets.list</code></p>
<p><code>bigtable. instances. getIamPolicy</code></p>
<p><code>bigtable.instances.list</code></p>
<p><code>bigtable. instances. setIamPolicy</code></p>
<p><code>bigtable.keyvisualizer.list</code></p>
<p><code>bigtable.locations.list</code></p>
<p><code>bigtable. logicalViews. getIamPolicy</code></p>
<p><code>bigtable.logicalViews.list</code></p>
<p><code>bigtable. logicalViews. setIamPolicy</code></p>
<p><code>bigtable. materializedViews. getIamPolicy</code></p>
<p><code>bigtable. materializedViews. list</code></p>
<p><code>bigtable. materializedViews. setIamPolicy</code></p>
<p><code>bigtable.memoryLayers.list</code></p>
<p><code>bigtable. schemaBundles. getIamPolicy</code></p>
<p><code>bigtable.schemaBundles.list</code></p>
<p><code>bigtable. schemaBundles. setIamPolicy</code></p>
<p><code>bigtable.tables.getIamPolicy</code></p>
<p><code>bigtable.tables.list</code></p>
<p><code>bigtable.tables.setIamPolicy</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing.accounts.setIamPolicy</code></p>
<p><code>billing.anomalies.list</code></p>
<p><code>billing. billingAccountPrices. list</code></p>
<p><code>billing. billingAccountServices. list</code></p>
<p><code>billing. billingAccountSkuGroupSkus. list</code></p>
<p><code>billing. billingAccountSkuGroups. list</code></p>
<p><code>billing. billingAccountSkus. list</code></p>
<p><code>billing.budgets.list</code></p>
<p><code>billing.credits.list</code></p>
<p><code>billing. resourceAssociations. list</code></p>
<p><code>billing.subscriptions.list</code></p>
<p><code>binaryauthorization. attestors. getIamPolicy</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. setIamPolicy</code></p>
<p><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></p>
<p><code>binaryauthorization. continuousValidationConfig. setIamPolicy</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization. policy. getIamPolicy</code></p>
<p><code>binaryauthorization. policy. setIamPolicy</code></p>
<p><code>blockchainnodeengine. blockchainNodes. list</code></p>
<p><code>blockchainnodeengine. locations. list</code></p>
<p><code>blockchainnodeengine. operations. list</code></p>
<p><code>blockchainvalidatormanager. blockchainValidatorConfigs. list</code></p>
<p><code>blockchainvalidatormanager. locations. list</code></p>
<p><code>blockchainvalidatormanager. operations. list</code></p>
<p><code>capacityplanner. capacityPlans. list</code></p>
<p><code>capacityplanner.forecasts.list</code></p>
<p><code>capacityplanner. planAlertInsights. list</code></p>
<p><code>capacityplanner. usageAlertInsights. list</code></p>
<p><code>capacityplanner. usageHistories. list</code></p>
<p><code>carestudio.patients.list</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. locations. list</code></p>
<p><code>certificatemanager. observedcerts. list</code></p>
<p><code>certificatemanager. operations. list</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>ces.agents.list</code></p>
<p><code>ces.appVersions.list</code></p>
<p><code>ces.apps.list</code></p>
<p><code>ces.assistantSessions.list</code></p>
<p><code>ces.changelogs.list</code></p>
<p><code>ces.conversations.list</code></p>
<p><code>ces.deployments.list</code></p>
<p><code>ces.evaluationDatasets.list</code></p>
<p><code>ces. evaluationExpectations. list</code></p>
<p><code>ces.evaluationResults.list</code></p>
<p><code>ces.evaluationRuns.list</code></p>
<p><code>ces.evaluations.list</code></p>
<p><code>ces.examples.list</code></p>
<p><code>ces.guardrails.list</code></p>
<p><code>ces.locations.list</code></p>
<p><code>ces.operations.list</code></p>
<p><code>ces.tools.list</code></p>
<p><code>ces.toolsets.list</code></p>
<p><code>chronicle.analyticValues.list</code></p>
<p><code>chronicle.analytics.list</code></p>
<p><code>chronicle. chatSessionMessages. list</code></p>
<p><code>chronicle.chatSessions.list</code></p>
<p><code>chronicle.collectors.list</code></p>
<p><code>chronicle.conversations.list</code></p>
<p><code>chronicle.coverageDetails.list</code></p>
<p><code>chronicle. curatedRuleSetCategories. list</code></p>
<p><code>chronicle. curatedRuleSetDeployments. list</code></p>
<p><code>chronicle.curatedRuleSets.list</code></p>
<p><code>chronicle.curatedRules.list</code></p>
<p><code>chronicle.dashboardCharts.list</code></p>
<p><code>chronicle. dashboardQueries. list</code></p>
<p><code>chronicle. dashboardScheduledReports. list</code></p>
<p><code>chronicle.dashboards.list</code></p>
<p><code>chronicle. dataAccessLabels. list</code></p>
<p><code>chronicle. dataAccessScopes. list</code></p>
<p><code>chronicle.dataExports.list</code></p>
<p><code>chronicle.dataTableRows.list</code></p>
<p><code>chronicle.dataTables.list</code></p>
<p><code>chronicle.dataTaps.list</code></p>
<p><code>chronicle. enrichmentControls. list</code></p>
<p><code>chronicle.entities.list</code></p>
<p><code>chronicle. extensionValidationReports. list</code></p>
<p><code>chronicle. featuredContentNativeDashboards. list</code></p>
<p><code>chronicle. featuredContentPlaybooks. list</code></p>
<p><code>chronicle. featuredContentRules. list</code></p>
<p><code>chronicle. featuredContentSearchQueries. list</code></p>
<p><code>chronicle.features.list</code></p>
<p><code>chronicle. federationGroups. list</code></p>
<p><code>chronicle.feedPacks.list</code></p>
<p><code>chronicle. feedSourceTypeSchemas. list</code></p>
<p><code>chronicle.feeds.list</code></p>
<p><code>chronicle. findingsRefinementDeployments. list</code></p>
<p><code>chronicle. findingsRefinements. list</code></p>
<p><code>chronicle.forwarders.list</code></p>
<p><code>chronicle. ingestionLogLabels. list</code></p>
<p><code>chronicle. ingestionLogNamespaces. list</code></p>
<p><code>chronicle. investigationComments. list</code></p>
<p><code>chronicle. investigationSteps. list</code></p>
<p><code>chronicle.investigations.list</code></p>
<p><code>chronicle. labsExperimentExecutions. list</code></p>
<p><code>chronicle.labsExperiments.list</code></p>
<p><code>chronicle. logProcessingPipelines. list</code></p>
<p><code>chronicle.logTypeSchemas.list</code></p>
<p><code>chronicle.logTypeSettings.list</code></p>
<p><code>chronicle.logTypes.list</code></p>
<p><code>chronicle.logs.list</code></p>
<p><code>chronicle.messages.list</code></p>
<p><code>chronicle. nativeDashboards. list</code></p>
<p><code>chronicle.notebooks.list</code></p>
<p><code>chronicle.operations.list</code></p>
<p><code>chronicle. parserExtensions. list</code></p>
<p><code>chronicle.parsers.list</code></p>
<p><code>chronicle.parsingErrors.list</code></p>
<p><code>chronicle.queryMetrics.list</code></p>
<p><code>chronicle.referenceLists.list</code></p>
<p><code>chronicle.retrohunts.list</code></p>
<p><code>chronicle.ruleDeployments.list</code></p>
<p><code>chronicle. ruleExecutionErrors. list</code></p>
<p><code>chronicle.rules.list</code></p>
<p><code>chronicle.savedColumnSets.list</code></p>
<p><code>chronicle.searchQueries.list</code></p>
<p><code>chronicle.searchedResults.list</code></p>
<p><code>chronicle. sharedPreferenceSets. list</code></p>
<p><code>chronicle.summaryTables.list</code></p>
<p><code>chronicle. tagSubscriptions. list</code></p>
<p><code>chronicle.tags.list</code></p>
<p><code>chronicle.tenants.list</code></p>
<p><code>chronicle. threatCollections. list</code></p>
<p><code>chronicle. transformerDefinitions. list</code></p>
<p><code>chronicle. validationErrors. list</code></p>
<p><code>chronicle.watchlists.list</code></p>
<p><code>chroniclesm. gcpAssociations. list</code></p>
<p><code>chroniclesm. soarRoleScripts. list</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloud.locations.list</code></p>
<p><code>cloudaicompanion. aiDevToolsSettings. list</code></p>
<p><code>cloudaicompanion. codeRepositoryIndexes. list</code></p>
<p><code>cloudaicompanion. codeToolsSettings. list</code></p>
<p><code>cloudaicompanion. dataSharingWithGoogleSettings. list</code></p>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></p>
<p><code>cloudaicompanion. gibqObservabilitySettings. list</code></p>
<p><code>cloudaicompanion. loggingSettings. list</code></p>
<p><code>cloudaicompanion. operations. list</code></p>
<p><code>cloudaicompanion. releaseChannelSettings. list</code></p>
<p><code>cloudaicompanion. repositoryGroups. getIamPolicy</code></p>
<p><code>cloudaicompanion. repositoryGroups. list</code></p>
<p><code>cloudaicompanion. repositoryGroups. setIamPolicy</code></p>
<p><code>cloudaicompanion. topics. getIamPolicy</code></p>
<p><code>cloudaicompanion. topics. setIamPolicy</code></p>
<p><code>cloudapiregistry. locations. list</code></p>
<p><code>cloudapiregistry. mcpServers. list</code></p>
<p><code>cloudapiregistry.mcpTools.list</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudasset.feeds.list</code></p>
<p><code>cloudasset. othercloudconnections. list</code></p>
<p><code>cloudasset.savedqueries.list</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild. connections. getIamPolicy</code></p>
<p><code>cloudbuild.connections.list</code></p>
<p><code>cloudbuild. connections. setIamPolicy</code></p>
<p><code>cloudbuild.integrations.list</code></p>
<p><code>cloudbuild.locations.list</code></p>
<p><code>cloudbuild.operations.list</code></p>
<p><code>cloudbuild.repositories.list</code></p>
<p><code>cloudbuild.workerpools.list</code></p>
<p><code>cloudcontrolspartner. accessapprovalrequests. list</code></p>
<p><code>cloudcontrolspartner. customers. list</code></p>
<p><code>cloudcontrolspartner. violations. list</code></p>
<p><code>cloudcontrolspartner. workloads. list</code></p>
<p><code>clouddebugger.breakpoints.list</code></p>
<p><code>clouddebugger.debuggees.list</code></p>
<p><code>clouddeploy. automationRuns. list</code></p>
<p><code>clouddeploy.automations.list</code></p>
<p><code>clouddeploy. customTargetTypes. getIamPolicy</code></p>
<p><code>clouddeploy. customTargetTypes. list</code></p>
<p><code>clouddeploy. customTargetTypes. setIamPolicy</code></p>
<p><code>clouddeploy. deliveryPipelines. getIamPolicy</code></p>
<p><code>clouddeploy. deliveryPipelines. list</code></p>
<p><code>clouddeploy. deliveryPipelines. setIamPolicy</code></p>
<p><code>clouddeploy. deployPolicies. getIamPolicy</code></p>
<p><code>clouddeploy. deployPolicies. list</code></p>
<p><code>clouddeploy. deployPolicies. setIamPolicy</code></p>
<p><code>clouddeploy.jobRuns.list</code></p>
<p><code>clouddeploy.locations.list</code></p>
<p><code>clouddeploy.operations.list</code></p>
<p><code>clouddeploy.releases.list</code></p>
<p><code>clouddeploy.rollouts.list</code></p>
<p><code>clouddeploy. targets. getIamPolicy</code></p>
<p><code>clouddeploy.targets.list</code></p>
<p><code>clouddeploy. targets. setIamPolicy</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions. functions. setIamPolicy</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.list</code></p>
<p><code>cloudjobdiscovery. companies. list</code></p>
<p><code>cloudkms. cryptoKeyVersions. list</code></p>
<p><code>cloudkms. cryptoKeys. getIamPolicy</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms. cryptoKeys. setIamPolicy</code></p>
<p><code>cloudkms. ekmConfigs. getIamPolicy</code></p>
<p><code>cloudkms. ekmConfigs. setIamPolicy</code></p>
<p><code>cloudkms. ekmConnections. getIamPolicy</code></p>
<p><code>cloudkms.ekmConnections.list</code></p>
<p><code>cloudkms. ekmConnections. setIamPolicy</code></p>
<p><code>cloudkms. importJobs. getIamPolicy</code></p>
<p><code>cloudkms.importJobs.list</code></p>
<p><code>cloudkms. importJobs. setIamPolicy</code></p>
<p><code>cloudkms.keyHandles.list</code></p>
<p><code>cloudkms.keyRings.getIamPolicy</code></p>
<p><code>cloudkms.keyRings.list</code></p>
<p><code>cloudkms.keyRings.setIamPolicy</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>cloudkms. protectableResources. list</code></p>
<p><code>cloudkms.retiredResources.list</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p>
<p><code>cloudlocationfinder. cloudLocations. list</code></p>
<p><code>cloudlocationfinder. locations. list</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudnumberregistry. customRanges. list</code></p>
<p><code>cloudnumberregistry. discoveredRanges. list</code></p>
<p><code>cloudnumberregistry. ipamAdminScopes. list</code></p>
<p><code>cloudnumberregistry. locations. list</code></p>
<p><code>cloudnumberregistry. operations. list</code></p>
<p><code>cloudnumberregistry. realms. list</code></p>
<p><code>cloudnumberregistry. registryBooks. list</code></p>
<p><code>cloudonefs.isiloncloud. com/clusters. list</code></p>
<p><code>cloudonefs.isiloncloud. com/fileshares. list</code></p>
<p><code>cloudprivatecatalogproducer. associations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogAssociations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. setIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. setIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. products. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. products. list</code></p>
<p><code>cloudprivatecatalogproducer. products. setIamPolicy</code></p>
<p><code>cloudprofiler.profiles.list</code></p>
<p><code>cloudscheduler.jobs.list</code></p>
<p><code>cloudscheduler.locations.list</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controls. list</code></p>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></p>
<p><code>cloudsecurityscanner. crawledurls. list</code></p>
<p><code>cloudsecurityscanner. results. list</code></p>
<p><code>cloudsecurityscanner. scanruns. list</code></p>
<p><code>cloudsecurityscanner. scans. list</code></p>
<p><code>cloudsql.backupRuns.list</code></p>
<p><code>cloudsql. blueGreenDeployments. list</code></p>
<p><code>cloudsql.databases.list</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>cloudsql.sslCerts.list</code></p>
<p><code>cloudsql.users.list</code></p>
<p><code>cloudsql.workloadCaptures.list</code></p>
<p><code>cloudsupport. accounts. getIamPolicy</code></p>
<p><code>cloudsupport.accounts.list</code></p>
<p><code>cloudsupport. accounts. setIamPolicy</code></p>
<p><code>cloudsupport.techCases.list</code></p>
<p><code>cloudtasks.locations.list</code></p>
<p><code>cloudtasks.queues.getIamPolicy</code></p>
<p><code>cloudtasks.queues.list</code></p>
<p><code>cloudtasks.queues.setIamPolicy</code></p>
<p><code>cloudtasks.tasks.list</code></p>
<p><code>cloudtestservice. devicesession. list</code></p>
<p><code>cloudtoolresults. executions. list</code></p>
<p><code>cloudtoolresults. histories. list</code></p>
<p><code>cloudtoolresults.steps.list</code></p>
<p><code>cloudtrace.insights.list</code></p>
<p><code>cloudtrace.tasks.list</code></p>
<p><code>cloudtrace.traceScopes.list</code></p>
<p><code>cloudtrace.traces.list</code></p>
<p><code>cloudtranslate. adaptiveMtDatasets. list</code></p>
<p><code>cloudtranslate. adaptiveMtFiles. list</code></p>
<p><code>cloudtranslate. adaptiveMtSentences. list</code></p>
<p><code>cloudtranslate. customModels. list</code></p>
<p><code>cloudtranslate.datasets.list</code></p>
<p><code>cloudtranslate.glossaries.list</code></p>
<p><code>cloudtranslate. glossaryentries. list</code></p>
<p><code>cloudtranslate.locations.list</code></p>
<p><code>cloudtranslate.operations.list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/activeDirectories. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/ipRanges. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/jobs. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/regions. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/serviceLevels. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/snapshots. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/volumereplication. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/volumes. list</code></p>
<p><code>commerceagreementpublishing. agreements. list</code></p>
<p><code>commerceagreementpublishing. documents. list</code></p>
<p><code>commercebusinessenablement. operations. list</code></p>
<p><code>commercebusinessenablement. partnerAccounts. list</code></p>
<p><code>commercebusinessenablement. refunds. list</code></p>
<p><code>commercebusinessenablement. resellerDiscountOffers. list</code></p>
<p><code>commercebusinessenablement. resellerPrivateOfferPlans. list</code></p>
<p><code>commercebusinessenablement. resellerRestrictions. list</code></p>
<p><code>commerceoffercatalog. agreements. list</code></p>
<p><code>commerceoffercatalog. documents. list</code></p>
<p><code>commerceorggovernance. collectionRequestApprovals. list</code></p>
<p><code>commerceorggovernance. collections. list</code></p>
<p><code>commerceorggovernance. populateCollectionJobs. list</code></p>
<p><code>commerceorggovernance. services. list</code></p>
<p><code>commerceprice.events.list</code></p>
<p><code>commerceprice. privateoffers. list</code></p>
<p><code>commerceproducer. analyticsHubListingProductConfigs. list</code></p>
<p><code>commerceproducer. locations. list</code></p>
<p><code>commerceproducer. privateOfferDocuments. list</code></p>
<p><code>commerceproducer. privateOffers. list</code></p>
<p><code>commerceproducer.products.list</code></p>
<p><code>commerceproducer.releases.list</code></p>
<p><code>commerceproducer.services.list</code></p>
<p><code>commerceproducer. skuGroups. list</code></p>
<p><code>commerceproducer.skus.list</code></p>
<p><code>commerceproducer. standardOffers. list</code></p>
<p><code>composer.dags.list</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>compute.acceleratorTypes.list</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute. backendBuckets. getIamPolicy</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendBuckets. setIamPolicy</code></p>
<p><code>compute. backendServices. getIamPolicy</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. setIamPolicy</code></p>
<p><code>compute.commitments.list</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute.diskTypes.list</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setIamPolicy</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. firewallPolicies. getIamPolicy</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute. firewallPolicies. setIamPolicy</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. futureReservations. getIamPolicy</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute. futureReservations. setIamPolicy</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute. globalOperations. getIamPolicy</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. globalOperations. setIamPolicy</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. list</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.hosts.list</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute.images.setIamPolicy</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute. instanceTemplates. getIamPolicy</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute. instanceTemplates. setIamPolicy</code></p>
<p><code>compute.instances.getIamPolicy</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.instances.setIamPolicy</code></p>
<p><code>compute. instantSnapshotGroups. getIamPolicy</code></p>
<p><code>compute. instantSnapshotGroups. list</code></p>
<p><code>compute. instantSnapshotGroups. setIamPolicy</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. setIamPolicy</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectGroups. list</code></p>
<p><code>compute. interconnectLocations. list</code></p>
<p><code>compute. interconnectRemoteLocations. list</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute. licenseCodes. getIamPolicy</code></p>
<p><code>compute.licenseCodes.list</code></p>
<p><code>compute. licenseCodes. setIamPolicy</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute.licenses.setIamPolicy</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. setIamPolicy</code></p>
<p><code>compute.machineTypes.list</code></p>
<p><code>compute.managedRulesets.list</code></p>
<p><code>compute.multiMig.list</code></p>
<p><code>compute.multiMigMembers.list</code></p>
<p><code>compute. networkAttachments. getIamPolicy</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. setIamPolicy</code></p>
<p><code>compute. networkEdgeSecurityServices. list</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute.networkProfiles.list</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. nodeGroups. getIamPolicy</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute. nodeGroups. setIamPolicy</code></p>
<p><code>compute. nodeTemplates. getIamPolicy</code></p>
<p><code>compute.nodeTemplates.list</code></p>
<p><code>compute. nodeTemplates. setIamPolicy</code></p>
<p><code>compute.nodeTypes.list</code></p>
<p><code>compute.orgRolloutPlans.list</code></p>
<p><code>compute.orgRollouts.list</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute.previewFeatures.list</code></p>
<p><code>compute. publicAdvertisedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. list</code></p>
<p><code>compute. recoverableSnapshots. getIamPolicy</code></p>
<p><code>compute. recoverableSnapshots. list</code></p>
<p><code>compute. recoverableSnapshots. setIamPolicy</code></p>
<p><code>compute. regionBackendBuckets. getIamPolicy</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendBuckets. setIamPolicy</code></p>
<p><code>compute. regionBackendServices. getIamPolicy</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. setIamPolicy</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionFirewallPolicies. getIamPolicy</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionFirewallPolicies. setIamPolicy</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute. regionOperations. getIamPolicy</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionOperations. setIamPolicy</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslPolicies. getIamPolicy</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. setIamPolicy</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute.regions.list</code></p>
<p><code>compute.reliabilityRisks.list</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.list</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. resourcePolicies. getIamPolicy</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute. resourcePolicies. setIamPolicy</code></p>
<p><code>compute.rolloutPlans.list</code></p>
<p><code>compute.rollouts.list</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. serviceAttachments. getIamPolicy</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. setIamPolicy</code></p>
<p><code>compute. snapshotGroups. getIamPolicy</code></p>
<p><code>compute.snapshotGroups.list</code></p>
<p><code>compute. snapshotGroups. setIamPolicy</code></p>
<p><code>compute.snapshots.getIamPolicy</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>compute.snapshots.setIamPolicy</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslPolicies. getIamPolicy</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. setIamPolicy</code></p>
<p><code>compute. storagePools. getIamPolicy</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. setIamPolicy</code></p>
<p><code>compute. subnetworks. getIamPolicy</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. setIamPolicy</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. vmExtensionPolicies. list</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute. zoneOperations. getIamPolicy</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute. zoneOperations. setIamPolicy</code></p>
<p><code>compute.zones.list</code></p>
<p><code>confidentialcomputing. locations. list</code></p>
<p><code>config. deploymentgrouprevisions. list</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. setIamPolicy</code></p>
<p><code>config.locations.list</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.list</code></p>
<p><code>config.resourcechanges.list</code></p>
<p><code>config.resourcedrifts.list</code></p>
<p><code>config.resources.list</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.list</code></p>
<p><code>configdelivery. fleetPackages. list</code></p>
<p><code>configdelivery.locations.list</code></p>
<p><code>configdelivery.operations.list</code></p>
<p><code>configdelivery.releases.list</code></p>
<p><code>configdelivery. resourceBundles. list</code></p>
<p><code>configdelivery.rollouts.list</code></p>
<p><code>configdelivery.variants.list</code></p>
<p><code>connectors.actions.list</code></p>
<p><code>connectors. connections. getIamPolicy</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors. connections. setIamPolicy</code></p>
<p><code>connectors.connectors.list</code></p>
<p><code>connectors. customConnectorVersions. getIamPolicy</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectorVersions. setIamPolicy</code></p>
<p><code>connectors. customConnectors. getIamPolicy</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. customConnectors. setIamPolicy</code></p>
<p><code>connectors. endpointAttachments. getIamPolicy</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors. endpointAttachments. setIamPolicy</code></p>
<p><code>connectors.entities.list</code></p>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors. eventSubscriptions. list</code></p>
<p><code>connectors.eventtypes.list</code></p>
<p><code>connectors.locations.list</code></p>
<p><code>connectors. managedZones. getIamPolicy</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>connectors. managedZones. setIamPolicy</code></p>
<p><code>connectors.operations.list</code></p>
<p><code>connectors.providers.list</code></p>
<p><code>connectors.versions.list</code></p>
<p><code>consumerprocurement. accounts. list</code></p>
<p><code>consumerprocurement. consents. list</code></p>
<p><code>consumerprocurement. entitlements. list</code></p>
<p><code>consumerprocurement. events. list</code></p>
<p><code>consumerprocurement. freeTrials. list</code></p>
<p><code>consumerprocurement. orderAttributions. list</code></p>
<p><code>consumerprocurement. orders. list</code></p>
<p><code>contactcenteraiplatform. contactCenters. list</code></p>
<p><code>contactcenteraiplatform. locations. list</code></p>
<p><code>contactcenteraiplatform. operations. list</code></p>
<p><code>contactcenterinsights. analyses. list</code></p>
<p><code>contactcenterinsights. analysisRules. list</code></p>
<p><code>contactcenterinsights. assessmentRules. list</code></p>
<p><code>contactcenterinsights. assessments. list</code></p>
<p><code>contactcenterinsights. authorizedAnalyses. list</code></p>
<p><code>contactcenterinsights. authorizedAssessments. list</code></p>
<p><code>contactcenterinsights. authorizedConversations. list</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. authorizedNotes. list</code></p>
<p><code>contactcenterinsights. authorizedOperations. list</code></p>
<p><code>contactcenterinsights. authorizedViewSets. list</code></p>
<p><code>contactcenterinsights. authorizedViews. getIamPolicy</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p>
<p><code>contactcenterinsights. authorizedViews. setIamPolicy</code></p>
<p><code>contactcenterinsights. conversations. list</code></p>
<p><code>contactcenterinsights. datasetAnalyses. list</code></p>
<p><code>contactcenterinsights. datasetConversations. list</code></p>
<p><code>contactcenterinsights. datasetFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. datasets. list</code></p>
<p><code>contactcenterinsights. diagnostics. list</code></p>
<p><code>contactcenterinsights. discoveries. list</code></p>
<p><code>contactcenterinsights. discoveryResults. list</code></p>
<p><code>contactcenterinsights. discoveryRevisions. list</code></p>
<p><code>contactcenterinsights. discoveryWorkspaces. list</code></p>
<p><code>contactcenterinsights. faqEntries. list</code></p>
<p><code>contactcenterinsights. faqModels. list</code></p>
<p><code>contactcenterinsights. feedbackLabels. list</code></p>
<p><code>contactcenterinsights. issueModels. list</code></p>
<p><code>contactcenterinsights. issues. list</code></p>
<p><code>contactcenterinsights. notes. list</code></p>
<p><code>contactcenterinsights. operations. list</code></p>
<p><code>contactcenterinsights. phraseMatchers. list</code></p>
<p><code>contactcenterinsights. qaQuestionTags. list</code></p>
<p><code>contactcenterinsights. qaQuestions. list</code></p>
<p><code>contactcenterinsights. qaScorecardRevisions. list</code></p>
<p><code>contactcenterinsights. qaScorecards. list</code></p>
<p><code>contactcenterinsights. views. list</code></p>
<p><code>contactcenterinsights. visibilityLabels. list</code></p>
<p><code>container.apiServices.list</code></p>
<p><code>container.auditSinks.list</code></p>
<p><code>container.backendConfigs.list</code></p>
<p><code>container.bindings.list</code></p>
<p><code>container. certificateSigningRequests. list</code></p>
<p><code>container. clusterRoleBindings. list</code></p>
<p><code>container.clusterRoles.list</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container. componentStatuses. list</code></p>
<p><code>container.configMaps.list</code></p>
<p><code>container. controllerRevisions. list</code></p>
<p><code>container.cronJobs.list</code></p>
<p><code>container.csiDrivers.list</code></p>
<p><code>container.csiNodeInfos.list</code></p>
<p><code>container.csiNodes.list</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container.daemonSets.list</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.endpointSlices.list</code></p>
<p><code>container.endpoints.list</code></p>
<p><code>container.events.list</code></p>
<p><code>container.frontendConfigs.list</code></p>
<p><code>container. horizontalPodAutoscalers. list</code></p>
<p><code>container.ingresses.list</code></p>
<p><code>container. initializerConfigurations. list</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container.leases.list</code></p>
<p><code>container.limitRanges.list</code></p>
<p><code>container. localSubjectAccessReviews. list</code></p>
<p><code>container. managedCertificates. list</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container.namespaces.list</code></p>
<p><code>container.networkPolicies.list</code></p>
<p><code>container.nodes.list</code></p>
<p><code>container.operations.list</code></p>
<p><code>container. persistentVolumeClaims. list</code></p>
<p><code>container. persistentVolumes. list</code></p>
<p><code>container.petSets.list</code></p>
<p><code>container. podDisruptionBudgets. list</code></p>
<p><code>container.podPresets.list</code></p>
<p><code>container. podSecurityPolicies. list</code></p>
<p><code>container.podTemplates.list</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.priorityClasses.list</code></p>
<p><code>container.replicaSets.list</code></p>
<p><code>container. replicationControllers. list</code></p>
<p><code>container.resourceQuotas.list</code></p>
<p><code>container.roleBindings.list</code></p>
<p><code>container.roles.list</code></p>
<p><code>container.runtimeClasses.list</code></p>
<p><code>container.scheduledJobs.list</code></p>
<p><code>container. selfSubjectAccessReviews. list</code></p>
<p><code>container.serviceAccounts.list</code></p>
<p><code>container.services.list</code></p>
<p><code>container.statefulSets.list</code></p>
<p><code>container.storageClasses.list</code></p>
<p><code>container.storageStates.list</code></p>
<p><code>container. storageVersionMigrations. list</code></p>
<p><code>container. subjectAccessReviews. list</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. thirdPartyResources. list</code></p>
<p><code>container.updateInfos.list</code></p>
<p><code>container. validatingWebhookConfigurations. list</code></p>
<p><code>container. volumeAttachments. list</code></p>
<p><code>container. volumeSnapshotClasses. list</code></p>
<p><code>container. volumeSnapshotContents. list</code></p>
<p><code>container.volumeSnapshots.list</code></p>
<p><code>containeranalysis. notes. getIamPolicy</code></p>
<p><code>containeranalysis.notes.list</code></p>
<p><code>containeranalysis. notes. setIamPolicy</code></p>
<p><code>containeranalysis. occurrences. getIamPolicy</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>containeranalysis. occurrences. setIamPolicy</code></p>
<p><code>containersecurity. clusterSummaries. list</code></p>
<p><code>containersecurity. findings. list</code></p>
<p><code>containersecurity. locations. list</code></p>
<p><code>contentwarehouse.corpora.list</code></p>
<p><code>contentwarehouse. documentSchemas. list</code></p>
<p><code>contentwarehouse. documents. getIamPolicy</code></p>
<p><code>contentwarehouse. documents. list</code></p>
<p><code>contentwarehouse. documents. setIamPolicy</code></p>
<p><code>contentwarehouse.ruleSets.list</code></p>
<p><code>contentwarehouse. synonymSets. list</code></p>
<p><code>databasecenter. databaseGroups. list</code></p>
<p><code>databasecenter. fleetHealthStats. list</code></p>
<p><code>databasecenter. fleetInsights. list</code></p>
<p><code>databasecenter.fleetStats.list</code></p>
<p><code>databasecenter.locations.list</code></p>
<p><code>databasecenter.products.list</code></p>
<p><code>databasecenter.queryStats.list</code></p>
<p><code>databasecenter. reportConfigs. list</code></p>
<p><code>databasecenter.userLabels.list</code></p>
<p><code>databasecenter.userTags.list</code></p>
<p><code>databaseinsights. locations. list</code></p>
<p><code>databasesconsole. locations. list</code></p>
<p><code>databasesconsole. operations. list</code></p>
<p><code>databasesconsole. studioQueries. list</code></p>
<p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog. categories. setIamPolicy</code></p>
<p><code>datacatalog. entries. getIamPolicy</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog. entries. setIamPolicy</code></p>
<p><code>datacatalog. entryGroups. getIamPolicy</code></p>
<p><code>datacatalog.entryGroups.list</code></p>
<p><code>datacatalog. entryGroups. setIamPolicy</code></p>
<p><code>datacatalog.operations.list</code></p>
<p><code>datacatalog.relationships.list</code></p>
<p><code>datacatalog. tagTemplates. getIamPolicy</code></p>
<p><code>datacatalog. tagTemplates. setIamPolicy</code></p>
<p><code>datacatalog. taxonomies. getIamPolicy</code></p>
<p><code>datacatalog.taxonomies.list</code></p>
<p><code>datacatalog. taxonomies. setIamPolicy</code></p>
<p><code>dataconnectors. connectors. getIamPolicy</code></p>
<p><code>dataconnectors.connectors.list</code></p>
<p><code>dataconnectors. connectors. setIamPolicy</code></p>
<p><code>dataconnectors.locations.list</code></p>
<p><code>dataconnectors.operations.list</code></p>
<p><code>dataflow.jobs.list</code></p>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.snapshots.list</code></p>
<p><code>dataform.commentThreads.list</code></p>
<p><code>dataform.comments.list</code></p>
<p><code>dataform. compilationResults. list</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.folders.setIamPolicy</code></p>
<p><code>dataform.locations.list</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.releaseConfigs.list</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. setIamPolicy</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform. teamFolders. setIamPolicy</code></p>
<p><code>dataform.workflowConfigs.list</code></p>
<p><code>dataform. workflowInvocations. list</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>dataform. workspaces. setIamPolicy</code></p>
<p><code>datafusion.artifacts.list</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion. instances. setIamPolicy</code></p>
<p><code>datafusion.locations.list</code></p>
<p><code>datafusion. namespaces. getIamPolicy</code></p>
<p><code>datafusion.namespaces.list</code></p>
<p><code>datafusion. namespaces. setIamPolicy</code></p>
<p><code>datafusion.operations.list</code></p>
<p><code>datafusion. pipelineConnections. list</code></p>
<p><code>datafusion.pipelines.list</code></p>
<p><code>datafusion.profiles.list</code></p>
<p><code>datafusion.secureKeys.list</code></p>
<p><code>datalabeling. annotateddatasets. list</code></p>
<p><code>datalabeling. annotationspecsets. list</code></p>
<p><code>datalabeling.dataitems.list</code></p>
<p><code>datalabeling.datasets.list</code></p>
<p><code>datalabeling.examples.list</code></p>
<p><code>datalabeling.instructions.list</code></p>
<p><code>datalabeling.operations.list</code></p>
<p><code>datalineage.events.list</code></p>
<p><code>datalineage. processRevisions. list</code></p>
<p><code>datalineage.processes.list</code></p>
<p><code>datalineage.runs.list</code></p>
<p><code>datamigration. connectionprofiles. getIamPolicy</code></p>
<p><code>datamigration. connectionprofiles. list</code></p>
<p><code>datamigration. connectionprofiles. setIamPolicy</code></p>
<p><code>datamigration. conversionworkspaces. getIamPolicy</code></p>
<p><code>datamigration. conversionworkspaces. list</code></p>
<p><code>datamigration. conversionworkspaces. setIamPolicy</code></p>
<p><code>datamigration.locations.list</code></p>
<p><code>datamigration. mappingrules. getIamPolicy</code></p>
<p><code>datamigration. mappingrules. setIamPolicy</code></p>
<p><code>datamigration. migrationjobs. getIamPolicy</code></p>
<p><code>datamigration. migrationjobs. list</code></p>
<p><code>datamigration. migrationjobs. setIamPolicy</code></p>
<p><code>datamigration.objects.list</code></p>
<p><code>datamigration.operations.list</code></p>
<p><code>datamigration. privateconnections. getIamPolicy</code></p>
<p><code>datamigration. privateconnections. list</code></p>
<p><code>datamigration. privateconnections. setIamPolicy</code></p>
<p><code>datapipelines.jobs.list</code></p>
<p><code>datapipelines.pipelines.list</code></p>
<p><code>dataplex. aspectTypes. getIamPolicy</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex. aspectTypes. setIamPolicy</code></p>
<p><code>dataplex.assetActions.list</code></p>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex.assets.setIamPolicy</code></p>
<p><code>dataplex. changeRequests. getIamPolicy</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex. changeRequests. setIamPolicy</code></p>
<p><code>dataplex.content.getIamPolicy</code></p>
<p><code>dataplex.content.list</code></p>
<p><code>dataplex.content.setIamPolicy</code></p>
<p><code>dataplex.dataAssets.list</code></p>
<p><code>dataplex. dataAttributeBindings. getIamPolicy</code></p>
<p><code>dataplex. dataAttributeBindings. list</code></p>
<p><code>dataplex. dataAttributeBindings. setIamPolicy</code></p>
<p><code>dataplex. dataAttributes. getIamPolicy</code></p>
<p><code>dataplex.dataAttributes.list</code></p>
<p><code>dataplex. dataAttributes. setIamPolicy</code></p>
<p><code>dataplex. dataDomainBindings. list</code></p>
<p><code>dataplex. dataDomains. getIamPolicy</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataDomains. setIamPolicy</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>dataplex. dataProducts. setIamPolicy</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p>
<p><code>dataplex. dataTaxonomies. setIamPolicy</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex. datascans. setIamPolicy</code></p>
<p><code>dataplex.encryptionConfig.list</code></p>
<p><code>dataplex.entities.list</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex. entryGroups. getIamPolicy</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex. entryGroups. setIamPolicy</code></p>
<p><code>dataplex. entryLinkTypes. getIamPolicy</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex. entryLinkTypes. setIamPolicy</code></p>
<p><code>dataplex. entryTypes. getIamPolicy</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. entryTypes. setIamPolicy</code></p>
<p><code>dataplex. environments. getIamPolicy</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex. environments. setIamPolicy</code></p>
<p><code>dataplex. glossaries. getIamPolicy</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex. glossaries. setIamPolicy</code></p>
<p><code>dataplex. glossaryCategories. list</code></p>
<p><code>dataplex.glossaryTerms.list</code></p>
<p><code>dataplex.lakeActions.list</code></p>
<p><code>dataplex.lakes.getIamPolicy</code></p>
<p><code>dataplex.lakes.list</code></p>
<p><code>dataplex.lakes.setIamPolicy</code></p>
<p><code>dataplex.locations.list</code></p>
<p><code>dataplex.metadataFeeds.list</code></p>
<p><code>dataplex.metadataJobs.list</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.partitions.list</code></p>
<p><code>dataplex.tasks.getIamPolicy</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.tasks.setIamPolicy</code></p>
<p><code>dataplex.zoneActions.list</code></p>
<p><code>dataplex.zones.getIamPolicy</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>dataplex.zones.setIamPolicy</code></p>
<p><code>dataproc.agents.list</code></p>
<p><code>dataproc. autoscalingPolicies. getIamPolicy</code></p>
<p><code>dataproc. autoscalingPolicies. list</code></p>
<p><code>dataproc. autoscalingPolicies. setIamPolicy</code></p>
<p><code>dataproc.batches.list</code></p>
<p><code>dataproc.clusters.getIamPolicy</code></p>
<p><code>dataproc.clusters.list</code></p>
<p><code>dataproc.clusters.setIamPolicy</code></p>
<p><code>dataproc.jobs.getIamPolicy</code></p>
<p><code>dataproc.jobs.list</code></p>
<p><code>dataproc.jobs.setIamPolicy</code></p>
<p><code>dataproc. operations. getIamPolicy</code></p>
<p><code>dataproc.operations.list</code></p>
<p><code>dataproc. operations. setIamPolicy</code></p>
<p><code>dataproc.sessionTemplates.list</code></p>
<p><code>dataproc.sessions.list</code></p>
<p><code>dataproc. workflowTemplates. getIamPolicy</code></p>
<p><code>dataproc. workflowTemplates. list</code></p>
<p><code>dataproc. workflowTemplates. setIamPolicy</code></p>
<p><code>dataprocessing. datasources. list</code></p>
<p><code>dataprocessing. featurecontrols. list</code></p>
<p><code>dataprocessing. groupcontrols. list</code></p>
<p><code>dataprocrm.locations.list</code></p>
<p><code>dataprocrm.nodePools.list</code></p>
<p><code>dataprocrm.nodes.list</code></p>
<p><code>dataprocrm.operations.list</code></p>
<p><code>dataprocrm.workloads.list</code></p>
<p><code>datastore.backupSchedules.list</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore. keyVisualizerScans. list</code></p>
<p><code>datastore.locations.list</code></p>
<p><code>datastore.namespaces.list</code></p>
<p><code>datastore.operations.list</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.list</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>datastream. connectionProfiles. getIamPolicy</code></p>
<p><code>datastream. connectionProfiles. list</code></p>
<p><code>datastream. connectionProfiles. setIamPolicy</code></p>
<p><code>datastream.locations.list</code></p>
<p><code>datastream.objects.list</code></p>
<p><code>datastream.operations.list</code></p>
<p><code>datastream. privateConnections. getIamPolicy</code></p>
<p><code>datastream. privateConnections. list</code></p>
<p><code>datastream. privateConnections. setIamPolicy</code></p>
<p><code>datastream.routes.getIamPolicy</code></p>
<p><code>datastream.routes.list</code></p>
<p><code>datastream.routes.setIamPolicy</code></p>
<p><code>datastream. streams. getIamPolicy</code></p>
<p><code>datastream.streams.list</code></p>
<p><code>datastream. streams. setIamPolicy</code></p>
<p><code>datastudio. datasources. getIamPolicy</code></p>
<p><code>datastudio. datasources. setIamPolicy</code></p>
<p><code>datastudio. reports. getIamPolicy</code></p>
<p><code>datastudio. reports. setIamPolicy</code></p>
<p><code>datastudio. workspaces. getIamPolicy</code></p>
<p><code>datastudio. workspaces. setIamPolicy</code></p>
<p><code>deploymentmanager. compositeTypes. list</code></p>
<p><code>deploymentmanager. deployments. getIamPolicy</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. deployments. setIamPolicy</code></p>
<p><code>deploymentmanager. manifests. list</code></p>
<p><code>deploymentmanager. operations. list</code></p>
<p><code>deploymentmanager. resources. list</code></p>
<p><code>deploymentmanager. typeProviders. list</code></p>
<p><code>deploymentmanager.types.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.list</code></p>
<p><code>designcenter.connections.list</code></p>
<p><code>designcenter.locations.list</code></p>
<p><code>designcenter.operations.list</code></p>
<p><code>designcenter. sharedTemplateRevisions. list</code></p>
<p><code>designcenter. sharedTemplates. list</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>designcenter. spaces. setIamPolicy</code></p>
<p><code>developerconnect. accountConnectors. list</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. deploymentEvents. list</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect. insightsConfigs. list</code></p>
<p><code>developerconnect. locations. list</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>developerconnect. providers. list</code></p>
<p><code>developerconnect.users.list</code></p>
<p><code>devicerun.devices.list</code></p>
<p><code>devicerun.locations.list</code></p>
<p><code>devicerun.operations.list</code></p>
<p><code>devicerun.sessions.list</code></p>
<p><code>devicerun. softwareVersions. list</code></p>
<p><code>devicestreaming. deviceSessions. list</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.list</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.list</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow. modelEvaluations. list</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>discoveryengine. agentFiles. list</code></p>
<p><code>discoveryengine. agentIamProposals. list</code></p>
<p><code>discoveryengine. agents. getIamPolicy</code></p>
<p><code>discoveryengine.agents.list</code></p>
<p><code>discoveryengine. agents. setIamPolicy</code></p>
<p><code>discoveryengine. assistants. list</code></p>
<p><code>discoveryengine. authorizations. list</code></p>
<p><code>discoveryengine. billingAccountLicenseConfigs. list</code></p>
<p><code>discoveryengine.branches.list</code></p>
<p><code>discoveryengine. cannedQueries. list</code></p>
<p><code>discoveryengine. cmekConfigs. list</code></p>
<p><code>discoveryengine. collections. getIamPolicy</code></p>
<p><code>discoveryengine. collections. list</code></p>
<p><code>discoveryengine. collections. setIamPolicy</code></p>
<p><code>discoveryengine. connectorRuns. list</code></p>
<p><code>discoveryengine.controls.list</code></p>
<p><code>discoveryengine. conversations. list</code></p>
<p><code>discoveryengine. dataStores. getIamPolicy</code></p>
<p><code>discoveryengine. dataStores. list</code></p>
<p><code>discoveryengine. dataStores. setIamPolicy</code></p>
<p><code>discoveryengine.documents.list</code></p>
<p><code>discoveryengine. engines. getIamPolicy</code></p>
<p><code>discoveryengine.engines.list</code></p>
<p><code>discoveryengine. engines. setIamPolicy</code></p>
<p><code>discoveryengine. evaluations. list</code></p>
<p><code>discoveryengine. identityMappingStores. list</code></p>
<p><code>discoveryengine. immersiveArtifacts. list</code></p>
<p><code>discoveryengine. licenseConfigs. list</code></p>
<p><code>discoveryengine.memories.list</code></p>
<p><code>discoveryengine.models.list</code></p>
<p><code>discoveryengine. notebooks. getIamPolicy</code></p>
<p><code>discoveryengine.notebooks.list</code></p>
<p><code>discoveryengine. notebooks. setIamPolicy</code></p>
<p><code>discoveryengine. notificationMessages. list</code></p>
<p><code>discoveryengine. operations. list</code></p>
<p><code>discoveryengine. sampleQueries. list</code></p>
<p><code>discoveryengine. sampleQuerySets. list</code></p>
<p><code>discoveryengine.schemas.list</code></p>
<p><code>discoveryengine. servingConfigs. list</code></p>
<p><code>discoveryengine.sessions.list</code></p>
<p><code>discoveryengine. sharedContents. list</code></p>
<p><code>discoveryengine. targetSites. list</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.columnDataProfiles.list</code></p>
<p><code>dlp.connections.list</code></p>
<p><code>dlp.contentPolicies.list</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.estimates.list</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.locations.list</code></p>
<p><code>dlp.projectDataProfiles.list</code></p>
<p><code>dlp.storedInfoTypes.list</code></p>
<p><code>dlp.subscriptions.list</code></p>
<p><code>dlp.tableDataProfiles.list</code></p>
<p><code>dns.changes.list</code></p>
<p><code>dns.dnsKeys.list</code></p>
<p><code>dns.managedZoneOperations.list</code></p>
<p><code>dns.managedZones.getIamPolicy</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.managedZones.setIamPolicy</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.responsePolicies.list</code></p>
<p><code>dns.responsePolicyRules.list</code></p>
<p><code>documentai. dataLabelingJobs. list</code></p>
<p><code>documentai.evaluations.list</code></p>
<p><code>documentai.labelerPools.list</code></p>
<p><code>documentai.locations.list</code></p>
<p><code>documentai.processorTypes.list</code></p>
<p><code>documentai. processorVersions. list</code></p>
<p><code>documentai.processors.list</code></p>
<p><code>documentai.rules.list</code></p>
<p><code>documentai.schemaVersions.list</code></p>
<p><code>documentai.schemas.list</code></p>
<p><code>documentai.validators.list</code></p>
<p><code>domains.locations.list</code></p>
<p><code>domains.operations.list</code></p>
<p><code>domains. registrations. getIamPolicy</code></p>
<p><code>domains.registrations.list</code></p>
<p><code>domains. registrations. setIamPolicy</code></p>
<p><code>dspm.locations.list</code></p>
<p><code>dspm.operations.list</code></p>
<p><code>earthengine. assets. getIamPolicy</code></p>
<p><code>earthengine.assets.list</code></p>
<p><code>earthengine. assets. setIamPolicy</code></p>
<p><code>earthengine.operations.list</code></p>
<p><code>edgecontainer.apikeys.list</code></p>
<p><code>edgecontainer. clusters. getIamPolicy</code></p>
<p><code>edgecontainer.clusters.list</code></p>
<p><code>edgecontainer. clusters. setIamPolicy</code></p>
<p><code>edgecontainer. identityproviders. list</code></p>
<p><code>edgecontainer.locations.list</code></p>
<p><code>edgecontainer. machines. getIamPolicy</code></p>
<p><code>edgecontainer.machines.list</code></p>
<p><code>edgecontainer. machines. setIamPolicy</code></p>
<p><code>edgecontainer. nodePools. getIamPolicy</code></p>
<p><code>edgecontainer.nodePools.list</code></p>
<p><code>edgecontainer. nodePools. setIamPolicy</code></p>
<p><code>edgecontainer.operations.list</code></p>
<p><code>edgecontainer. serviceaccounts. list</code></p>
<p><code>edgecontainer. vpnConnections. getIamPolicy</code></p>
<p><code>edgecontainer. vpnConnections. list</code></p>
<p><code>edgecontainer. vpnConnections. setIamPolicy</code></p>
<p><code>edgecontainer. zonalProjects. list</code></p>
<p><code>edgecontainer. zonalservices. list</code></p>
<p><code>edgecontainer.zones.list</code></p>
<p><code>edgenetwork. interconnectAttachments. getIamPolicy</code></p>
<p><code>edgenetwork. interconnectAttachments. list</code></p>
<p><code>edgenetwork. interconnectAttachments. setIamPolicy</code></p>
<p><code>edgenetwork. interconnects. getIamPolicy</code></p>
<p><code>edgenetwork.interconnects.list</code></p>
<p><code>edgenetwork. interconnects. setIamPolicy</code></p>
<p><code>edgenetwork.locations.list</code></p>
<p><code>edgenetwork. networks. getIamPolicy</code></p>
<p><code>edgenetwork.networks.list</code></p>
<p><code>edgenetwork. networks. setIamPolicy</code></p>
<p><code>edgenetwork.operations.list</code></p>
<p><code>edgenetwork. routers. getIamPolicy</code></p>
<p><code>edgenetwork.routers.list</code></p>
<p><code>edgenetwork. routers. setIamPolicy</code></p>
<p><code>edgenetwork.routes.list</code></p>
<p><code>edgenetwork. subnetworks. getIamPolicy</code></p>
<p><code>edgenetwork.subnetworks.list</code></p>
<p><code>edgenetwork. subnetworks. setIamPolicy</code></p>
<p><code>edgenetwork.zones.list</code></p>
<p><code>enterpriseknowledgegraph. entityReconciliationJobs. list</code></p>
<p><code>enterprisepurchasing. gcveCuds. list</code></p>
<p><code>enterprisepurchasing. gcveNodePricingInfo. list</code></p>
<p><code>enterprisepurchasing. licenseKeys. list</code></p>
<p><code>enterprisepurchasing. locations. list</code></p>
<p><code>enterprisepurchasing. operations. list</code></p>
<p><code>errorreporting. applications. list</code></p>
<p><code>errorreporting. errorEvents. list</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc. channelConnections. setIamPolicy</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc.channels.setIamPolicy</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc. enrollments. setIamPolicy</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. googleApiSources. setIamPolicy</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc. kafkaSources. setIamPolicy</code></p>
<p><code>eventarc.locations.list</code></p>
<p><code>eventarc. messageBuses. getIamPolicy</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc. messageBuses. setIamPolicy</code></p>
<p><code>eventarc.operations.list</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc. pipelines. setIamPolicy</code></p>
<p><code>eventarc.providers.list</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>eventarc.triggers.setIamPolicy</code></p>
<p><code>externalexposure. locations. list</code></p>
<p><code>externalexposure. operations. list</code></p>
<p><code>faulttesting. affectedResources. list</code></p>
<p><code>faulttesting. experimentTemplates. list</code></p>
<p><code>faulttesting.experiments.list</code></p>
<p><code>faulttesting.locations.list</code></p>
<p><code>faulttesting.operations.list</code></p>
<p><code>faulttesting. validationResources. list</code></p>
<p><code>faulttesting.validations.list</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>file.backups.list</code></p>
<p><code>file.instances.list</code></p>
<p><code>file.locations.list</code></p>
<p><code>file.operations.list</code></p>
<p><code>financialservices. locations. list</code></p>
<p><code>financialservices. operations. list</code></p>
<p><code>financialservices. v1backtests. list</code></p>
<p><code>financialservices. v1datasets. list</code></p>
<p><code>financialservices. v1engineconfigs. list</code></p>
<p><code>financialservices. v1engineversions. list</code></p>
<p><code>financialservices. v1instances. list</code></p>
<p><code>financialservices. v1models. list</code></p>
<p><code>financialservices. v1predictions. list</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebaseabt.experiments.list</code></p>
<p><code>firebaseappcheck. automations. list</code></p>
<p><code>firebaseappdistro.groups.list</code></p>
<p><code>firebaseappdistro. releases. list</code></p>
<p><code>firebaseappdistro.testers.list</code></p>
<p><code>firebaseapphosting. backends. list</code></p>
<p><code>firebaseapphosting.builds.list</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting. locations. list</code></p>
<p><code>firebaseapphosting. operations. list</code></p>
<p><code>firebaseapphosting. rollouts. list</code></p>
<p><code>firebasecrashlytics. issues. list</code></p>
<p><code>firebasedatabase. instances. list</code></p>
<p><code>firebasedataconnect. connectorRevisions. list</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations. list</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. schemaRevisions. list</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebasedynamiclinks. destinations. list</code></p>
<p><code>firebasedynamiclinks. domains. list</code></p>
<p><code>firebasedynamiclinks. links. list</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseextensionspublisher. extensions. list</code></p>
<p><code>firebasehosting.sites.list</code></p>
<p><code>firebaseinappmessaging. campaigns. list</code></p>
<p><code>firebasemessagingcampaigns. campaigns. list</code></p>
<p><code>firebaseml.models.list</code></p>
<p><code>firebaseml.modelversions.list</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>firebasestorage.buckets.list</code></p>
<p><code>firebasevertexai. promptTemplates. list</code></p>
<p><code>fleetengine. deliveryvehicles. list</code></p>
<p><code>fleetengine.tasks.list</code></p>
<p><code>fleetengine.vehicles.list</code></p>
<p><code>ftp.locations.list</code></p>
<p><code>ftp.operations.list</code></p>
<p><code>ftp.servers.list</code></p>
<p><code>ftp.users.list</code></p>
<p><code>gcp.redisenterprise. com/databases. list</code></p>
<p><code>gcp.redisenterprise. com/subscriptions. list</code></p>
<p><code>gdchardwaremanagement. changeLogEntries. list</code></p>
<p><code>gdchardwaremanagement. comments. list</code></p>
<p><code>gdchardwaremanagement. hardware. list</code></p>
<p><code>gdchardwaremanagement. hardwareGroups. list</code></p>
<p><code>gdchardwaremanagement. locations. list</code></p>
<p><code>gdchardwaremanagement. operations. list</code></p>
<p><code>gdchardwaremanagement. orders. list</code></p>
<p><code>gdchardwaremanagement. sites. list</code></p>
<p><code>gdchardwaremanagement. skus. list</code></p>
<p><code>gdchardwaremanagement. zones. list</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist. investigations. setIamPolicy</code></p>
<p><code>geminicloudassist. locations. list</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>geminidataanalytics. dataAgents. getIamPolicy</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p>
<p><code>geminidataanalytics. dataAgents. setIamPolicy</code></p>
<p><code>geminidataanalytics. locations. list</code></p>
<p><code>geminidataanalytics. operations. list</code></p>
<p><code>genomics.datasets.getIamPolicy</code></p>
<p><code>genomics.datasets.list</code></p>
<p><code>genomics.datasets.setIamPolicy</code></p>
<p><code>genomics.operations.list</code></p>
<p><code>gkebackup.backupChannels.list</code></p>
<p><code>gkebackup. backupPlanBindings. list</code></p>
<p><code>gkebackup. backupPlans. getIamPolicy</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup. backupPlans. setIamPolicy</code></p>
<p><code>gkebackup.backups.list</code></p>
<p><code>gkebackup.locations.list</code></p>
<p><code>gkebackup.operations.list</code></p>
<p><code>gkebackup.restoreChannels.list</code></p>
<p><code>gkebackup. restorePlanBindings. list</code></p>
<p><code>gkebackup. restorePlans. getIamPolicy</code></p>
<p><code>gkebackup.restorePlans.list</code></p>
<p><code>gkebackup. restorePlans. setIamPolicy</code></p>
<p><code>gkebackup.restores.list</code></p>
<p><code>gkebackup.volumeBackups.list</code></p>
<p><code>gkebackup.volumeRestores.list</code></p>
<p><code>gkehub.features.getIamPolicy</code></p>
<p><code>gkehub.features.list</code></p>
<p><code>gkehub.features.setIamPolicy</code></p>
<p><code>gkehub.locations.list</code></p>
<p><code>gkehub.membershipbindings.list</code></p>
<p><code>gkehub.membershipfeatures.list</code></p>
<p><code>gkehub. memberships. getIamPolicy</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>gkehub. memberships. setIamPolicy</code></p>
<p><code>gkehub.namespaces.list</code></p>
<p><code>gkehub.operations.list</code></p>
<p><code>gkehub.rbacrolebindings.list</code></p>
<p><code>gkehub.scopes.getIamPolicy</code></p>
<p><code>gkehub.scopes.list</code></p>
<p><code>gkehub.scopes.setIamPolicy</code></p>
<p><code>gkemulticloud. attachedClusters. list</code></p>
<p><code>gkemulticloud.awsClusters.list</code></p>
<p><code>gkemulticloud. awsNodePools. list</code></p>
<p><code>gkemulticloud. azureClients. list</code></p>
<p><code>gkemulticloud. azureClusters. list</code></p>
<p><code>gkemulticloud. azureNodePools. list</code></p>
<p><code>gkemulticloud.operations.list</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. list</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. setIamPolicy</code></p>
<p><code>gkeonprem. bareMetalClusters. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalClusters. list</code></p>
<p><code>gkeonprem. bareMetalClusters. setIamPolicy</code></p>
<p><code>gkeonprem. bareMetalNodePools. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalNodePools. list</code></p>
<p><code>gkeonprem. bareMetalNodePools. setIamPolicy</code></p>
<p><code>gkeonprem.locations.list</code></p>
<p><code>gkeonprem.operations.list</code></p>
<p><code>gkeonprem. vmwareAdminClusters. getIamPolicy</code></p>
<p><code>gkeonprem. vmwareAdminClusters. list</code></p>
<p><code>gkeonprem. vmwareAdminClusters. setIamPolicy</code></p>
<p><code>gkeonprem. vmwareClusters. getIamPolicy</code></p>
<p><code>gkeonprem.vmwareClusters.list</code></p>
<p><code>gkeonprem. vmwareClusters. setIamPolicy</code></p>
<p><code>gkeonprem. vmwareNodePools. getIamPolicy</code></p>
<p><code>gkeonprem.vmwareNodePools.list</code></p>
<p><code>gkeonprem. vmwareNodePools. setIamPolicy</code></p>
<p><code>gsuiteaddons.deployments.list</code></p>
<p><code>health.subscribers.list</code></p>
<p><code>health.subscriptions.list</code></p>
<p><code>healthcare. annotationStores. getIamPolicy</code></p>
<p><code>healthcare. annotationStores. list</code></p>
<p><code>healthcare. annotationStores. setIamPolicy</code></p>
<p><code>healthcare.annotations.list</code></p>
<p><code>healthcare. attributeDefinitions. list</code></p>
<p><code>healthcare. consentArtifacts. list</code></p>
<p><code>healthcare. consentStores. getIamPolicy</code></p>
<p><code>healthcare.consentStores.list</code></p>
<p><code>healthcare. consentStores. setIamPolicy</code></p>
<p><code>healthcare.consents.list</code></p>
<p><code>healthcare. datasets. getIamPolicy</code></p>
<p><code>healthcare.datasets.list</code></p>
<p><code>healthcare. datasets. setIamPolicy</code></p>
<p><code>healthcare. dicomStores. getIamPolicy</code></p>
<p><code>healthcare.dicomStores.list</code></p>
<p><code>healthcare. dicomStores. setIamPolicy</code></p>
<p><code>healthcare. fhirStores. getIamPolicy</code></p>
<p><code>healthcare.fhirStores.list</code></p>
<p><code>healthcare. fhirStores. setIamPolicy</code></p>
<p><code>healthcare.hl7V2Messages.list</code></p>
<p><code>healthcare. hl7V2Stores. getIamPolicy</code></p>
<p><code>healthcare.hl7V2Stores.list</code></p>
<p><code>healthcare. hl7V2Stores. setIamPolicy</code></p>
<p><code>healthcare.locations.list</code></p>
<p><code>healthcare.operations.list</code></p>
<p><code>healthcare. userDataMappings. list</code></p>
<p><code>hypercomputecluster. clusters. list</code></p>
<p><code>hypercomputecluster. locations. list</code></p>
<p><code>hypercomputecluster. machineLearningRuns. list</code></p>
<p><code>hypercomputecluster. operations. list</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam.denypolicies.list</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. list</code></p>
<p><code>iam.googleapis. com/oauthClients. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workforcePools. setIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. setIamPolicy</code></p>
<p><code>iam.policybindings.list</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. setIamPolicy</code></p>
<p><code>iamconnectors. accessEvents. list</code></p>
<p><code>iamconnectors. authorizations. list</code></p>
<p><code>iamconnectors. connectors. getIamPolicy</code></p>
<p><code>iamconnectors.connectors.list</code></p>
<p><code>iamconnectors. connectors. setIamPolicy</code></p>
<p><code>iamconnectors.locations.list</code></p>
<p><code>iamconnectors.operations.list</code></p>
<p><code>iap.tunnel.*</code></p>
<ul>
<li><code>iap.tunnel.getIamPolicy</code></li>
<li><code>iap.tunnel.setIamPolicy</code></li>
</ul>
<p><code>iap. tunnelDestGroups. getIamPolicy</code></p>
<p><code>iap.tunnelDestGroups.list</code></p>
<p><code>iap. tunnelDestGroups. setIamPolicy</code></p>
<p><code>iap. tunnelInstances. getIamPolicy</code></p>
<p><code>iap. tunnelInstances. setIamPolicy</code></p>
<p><code>iap.tunnelLocations.*</code></p>
<ul>
<li><code>iap. tunnelLocations. getIamPolicy</code></li>
<li><code>iap. tunnelLocations. setIamPolicy</code></li>
</ul>
<p><code>iap.tunnelZones.*</code></p>
<ul>
<li><code>iap.tunnelZones.getIamPolicy</code></li>
<li><code>iap.tunnelZones.setIamPolicy</code></li>
</ul>
<p><code>iap.web.getIamPolicy</code></p>
<p><code>iap.web.setIamPolicy</code></p>
<p><code>iap. webServiceVersions. getIamPolicy</code></p>
<p><code>iap. webServiceVersions. setIamPolicy</code></p>
<p><code>iap.webServices.getIamPolicy</code></p>
<p><code>iap.webServices.setIamPolicy</code></p>
<p><code>iap.webTypes.getIamPolicy</code></p>
<p><code>iap.webTypes.setIamPolicy</code></p>
<p><code>identitytoolkit. tenants. getIamPolicy</code></p>
<p><code>identitytoolkit.tenants.list</code></p>
<p><code>identitytoolkit. tenants. setIamPolicy</code></p>
<p><code>ids.endpoints.getIamPolicy</code></p>
<p><code>ids.endpoints.list</code></p>
<p><code>ids.endpoints.setIamPolicy</code></p>
<p><code>ids.locations.list</code></p>
<p><code>ids.operations.list</code></p>
<p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations. apigeeSuspensions. list</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations.certificates.list</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. securityAuthConfigs. list</code></p>
<p><code>integrations. securityExecutions. list</code></p>
<p><code>integrations. securityIntegTempVers. list</code></p>
<p><code>integrations. securityIntegrationVers. list</code></p>
<p><code>integrations. securityIntegrations. list</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>integrations.suspensions.list</code></p>
<p><code>integrations.templates.list</code></p>
<p><code>integrations.testCases.list</code></p>
<p><code>issuerswitch. accountManagerTransactions. list</code></p>
<p><code>issuerswitch. complaintTransactions. list</code></p>
<p><code>issuerswitch. financialTransactions. list</code></p>
<p><code>issuerswitch. mandateTransactions. list</code></p>
<p><code>issuerswitch. metadataTransactions. list</code></p>
<p><code>issuerswitch.operations.list</code></p>
<p><code>issuerswitch.ruleMetadata.list</code></p>
<p><code>issuerswitch. ruleMetadataValues. list</code></p>
<p><code>issuerswitch.rules.list</code></p>
<p><code>krmapihosting. krmApiHosts. getIamPolicy</code></p>
<p><code>krmapihosting.krmApiHosts.list</code></p>
<p><code>krmapihosting. krmApiHosts. setIamPolicy</code></p>
<p><code>krmapihosting.locations.list</code></p>
<p><code>krmapihosting.operations.list</code></p>
<p><code>licensemanager. configurations. list</code></p>
<p><code>licensemanager.instances.list</code></p>
<p><code>licensemanager.locations.list</code></p>
<p><code>licensemanager.operations.list</code></p>
<p><code>licensemanager.products.list</code></p>
<p><code>lifesciences.operations.list</code></p>
<p><code>livestream.assets.list</code></p>
<p><code>livestream.channels.list</code></p>
<p><code>livestream.clips.list</code></p>
<p><code>livestream.dvrSessions.list</code></p>
<p><code>livestream.events.list</code></p>
<p><code>livestream.inputs.list</code></p>
<p><code>livestream.locations.list</code></p>
<p><code>livestream.operations.list</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging.exclusions.list</code></p>
<p><code>logging.links.list</code></p>
<p><code>logging.locations.list</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>logging.logScopes.list</code></p>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.notificationRules.list</code></p>
<p><code>logging.operations.list</code></p>
<p><code>logging.privateLogEntries.list</code></p>
<p><code>logging.queries.usePrivate</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>logging.views.getIamPolicy</code></p>
<p><code>logging.views.list</code></p>
<p><code>logging.views.setIamPolicy</code></p>
<p><code>looker.backups.list</code></p>
<p><code>looker.instances.list</code></p>
<p><code>looker.locations.list</code></p>
<p><code>looker.operations.list</code></p>
<p><code>lustre.instances.list</code></p>
<p><code>lustre.locations.list</code></p>
<p><code>lustre.operations.list</code></p>
<p><code>maintenance.locations.list</code></p>
<p><code>maintenance. resourceMaintenances. list</code></p>
<p><code>managedflink.deployments.list</code></p>
<p><code>managedflink.jobs.list</code></p>
<p><code>managedflink.locations.list</code></p>
<p><code>managedflink.operations.list</code></p>
<p><code>managedflink.sessions.list</code></p>
<p><code>managedidentities. backups. getIamPolicy</code></p>
<p><code>managedidentities.backups.list</code></p>
<p><code>managedidentities. backups. setIamPolicy</code></p>
<p><code>managedidentities. domains. getIamPolicy</code></p>
<p><code>managedidentities.domains.list</code></p>
<p><code>managedidentities. domains. setIamPolicy</code></p>
<p><code>managedidentities. locations. list</code></p>
<p><code>managedidentities. operations. list</code></p>
<p><code>managedidentities. peerings. getIamPolicy</code></p>
<p><code>managedidentities. peerings. list</code></p>
<p><code>managedidentities. peerings. setIamPolicy</code></p>
<p><code>managedidentities. sqlintegrations. list</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.list</code></p>
<p><code>managedkafka.locations.list</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>mapsadmin.clientMaps.list</code></p>
<p><code>mapsadmin. clientStyleSheetSnapshots. list</code></p>
<p><code>mapsadmin.clientStyles.list</code></p>
<p><code>mapsadmin.mapViews.list</code></p>
<p><code>mapsadmin.styleSnapshots.list</code></p>
<p><code>mapsanalytics. metricMetadata. list</code></p>
<p><code>mapsplatformdatasets. datasets. list</code></p>
<p><code>marketplacesolutions. locations. list</code></p>
<p><code>marketplacesolutions. operations. list</code></p>
<p><code>marketplacesolutions. powerImages. list</code></p>
<p><code>marketplacesolutions. powerInstances. list</code></p>
<p><code>marketplacesolutions. powerNetworks. list</code></p>
<p><code>marketplacesolutions. powerSshKeys. list</code></p>
<p><code>marketplacesolutions. powerVolumes. list</code></p>
<p><code>memcache.instances.list</code></p>
<p><code>memcache.locations.list</code></p>
<p><code>memcache.operations.list</code></p>
<p><code>memorystore. backupCollections. list</code></p>
<p><code>memorystore.backups.list</code></p>
<p><code>memorystore.instances.list</code></p>
<p><code>memorystore.locations.list</code></p>
<p><code>memorystore.operations.list</code></p>
<p><code>metastore.backups.getIamPolicy</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.backups.setIamPolicy</code></p>
<p><code>metastore. databases. getIamPolicy</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore. databases. setIamPolicy</code></p>
<p><code>metastore. federations. getIamPolicy</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore. federations. setIamPolicy</code></p>
<p><code>metastore.imports.list</code></p>
<p><code>metastore.locations.list</code></p>
<p><code>metastore.migrations.list</code></p>
<p><code>metastore.operations.list</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. setIamPolicy</code></p>
<p><code>metastore.tables.getIamPolicy</code></p>
<p><code>metastore.tables.list</code></p>
<p><code>metastore.tables.setIamPolicy</code></p>
<p><code>migrationcenter.assets.list</code></p>
<p><code>migrationcenter. assetsExportJobs. list</code></p>
<p><code>migrationcenter. discoveryClients. list</code></p>
<p><code>migrationcenter. errorFrames. list</code></p>
<p><code>migrationcenter.groups.list</code></p>
<p><code>migrationcenter. importDataFiles. list</code></p>
<p><code>migrationcenter. importJobs. list</code></p>
<p><code>migrationcenter.locations.list</code></p>
<p><code>migrationcenter. operations. list</code></p>
<p><code>migrationcenter. preferenceSets. list</code></p>
<p><code>migrationcenter.relations.list</code></p>
<p><code>migrationcenter. reportConfigs. list</code></p>
<p><code>migrationcenter.reports.list</code></p>
<p><code>migrationcenter.sources.list</code></p>
<p><code>ml.jobs.getIamPolicy</code></p>
<p><code>ml.jobs.list</code></p>
<p><code>ml.jobs.setIamPolicy</code></p>
<p><code>ml.locations.list</code></p>
<p><code>ml.models.getIamPolicy</code></p>
<p><code>ml.models.list</code></p>
<p><code>ml.models.setIamPolicy</code></p>
<p><code>ml.operations.list</code></p>
<p><code>ml.studies.getIamPolicy</code></p>
<p><code>ml.studies.list</code></p>
<p><code>ml.studies.setIamPolicy</code></p>
<p><code>ml.trials.list</code></p>
<p><code>ml.versions.list</code></p>
<p><code>modelarmor.locations.list</code></p>
<p><code>modelarmor.templates.list</code></p>
<p><code>modelarmor.topics.list</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring.alerts.list</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors. list</code></p>
<p><code>monitoring. notificationChannelDescriptors. list</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>netapp.activeDirectories.list</code></p>
<p><code>netapp.backupPolicies.list</code></p>
<p><code>netapp.backupVaults.list</code></p>
<p><code>netapp.backups.list</code></p>
<p><code>netapp.hostGroups.list</code></p>
<p><code>netapp.kmsConfigs.list</code></p>
<p><code>netapp.locations.list</code></p>
<p><code>netapp.operations.list</code></p>
<p><code>netapp.quotaRules.list</code></p>
<p><code>netapp.replications.list</code></p>
<p><code>netapp.snapshots.list</code></p>
<p><code>netapp.storagePools.list</code></p>
<p><code>netapp.volumes.list</code></p>
<p><code>networkconnectivity. gatewayAdvertisedRoutes. list</code></p>
<p><code>networkconnectivity. groups. getIamPolicy</code></p>
<p><code>networkconnectivity. groups. list</code></p>
<p><code>networkconnectivity. groups. setIamPolicy</code></p>
<p><code>networkconnectivity. hubRouteTables. getIamPolicy</code></p>
<p><code>networkconnectivity. hubRouteTables. list</code></p>
<p><code>networkconnectivity. hubRouteTables. setIamPolicy</code></p>
<p><code>networkconnectivity. hubRoutes. getIamPolicy</code></p>
<p><code>networkconnectivity. hubRoutes. list</code></p>
<p><code>networkconnectivity. hubRoutes. setIamPolicy</code></p>
<p><code>networkconnectivity. hubs. getIamPolicy</code></p>
<p><code>networkconnectivity.hubs.list</code></p>
<p><code>networkconnectivity. hubs. setIamPolicy</code></p>
<p><code>networkconnectivity. internalRanges. getIamPolicy</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. internalRanges. setIamPolicy</code></p>
<p><code>networkconnectivity. locations. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferConfigs. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferDestinations. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferSupportedServices. list</code></p>
<p><code>networkconnectivity. operations. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. getIamPolicy</code></p>
<p><code>networkconnectivity. policyBasedRoutes. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. setIamPolicy</code></p>
<p><code>networkconnectivity. pscAuthorizationPolicies. list</code></p>
<p><code>networkconnectivity. regionalEndpoints. list</code></p>
<p><code>networkconnectivity. remoteTransportProfiles. list</code></p>
<p><code>networkconnectivity. serviceClasses. list</code></p>
<p><code>networkconnectivity. serviceConnectionMaps. list</code></p>
<p><code>networkconnectivity. serviceConnectionPolicies. list</code></p>
<p><code>networkconnectivity. spokes. getIamPolicy</code></p>
<p><code>networkconnectivity. spokes. list</code></p>
<p><code>networkconnectivity. spokes. setIamPolicy</code></p>
<p><code>networkconnectivity. transports. list</code></p>
<p><code>networkmanagement. connectivitytests. getIamPolicy</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networkmanagement. connectivitytests. setIamPolicy</code></p>
<p><code>networkmanagement. locations. list</code></p>
<p><code>networkmanagement. monitoringpoints. list</code></p>
<p><code>networkmanagement. networkpaths. list</code></p>
<p><code>networkmanagement. operations. list</code></p>
<p><code>networkmanagement. providers. list</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs. list</code></p>
<p><code>networkmanagement. webpaths. list</code></p>
<p><code>networksecurity. addressGroups. getIamPolicy</code></p>
<p><code>networksecurity. addressGroups. list</code></p>
<p><code>networksecurity. addressGroups. setIamPolicy</code></p>
<p><code>networksecurity. authorizationPolicies. getIamPolicy</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authorizationPolicies. setIamPolicy</code></p>
<p><code>networksecurity. authzPolicies. getIamPolicy</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. authzPolicies. setIamPolicy</code></p>
<p><code>networksecurity. backendAuthenticationConfigs. list</code></p>
<p><code>networksecurity. clientTlsPolicies. getIamPolicy</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. setIamPolicy</code></p>
<p><code>networksecurity. dnsThreatDetectors. list</code></p>
<p><code>networksecurity. firewallEndpointAssociations. list</code></p>
<p><code>networksecurity. firewallEndpoints. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity. interceptDeploymentGroups. list</code></p>
<p><code>networksecurity. interceptDeployments. list</code></p>
<p><code>networksecurity. interceptEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. interceptEndpointGroups. list</code></p>
<p><code>networksecurity.locations.list</code></p>
<p><code>networksecurity. mirroringDeploymentGroups. list</code></p>
<p><code>networksecurity. mirroringDeployments. list</code></p>
<p><code>networksecurity. mirroringEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. mirroringEndpointGroups. list</code></p>
<p><code>networksecurity. operations. list</code></p>
<p><code>networksecurity. sacAttachments. list</code></p>
<p><code>networksecurity.sacRealms.list</code></p>
<p><code>networksecurity. securityProfileGroups. list</code></p>
<p><code>networksecurity. securityProfiles. list</code></p>
<p><code>networksecurity. serverTlsPolicies. getIamPolicy</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. serverTlsPolicies. setIamPolicy</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networkservices. agentGateways. list</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices. googleTagGatewayPolicies. list</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. httpfilters. getIamPolicy</code></p>
<p><code>networkservices. httpfilters. list</code></p>
<p><code>networkservices. httpfilters. setIamPolicy</code></p>
<p><code>networkservices. lbEdgeExtensions. list</code></p>
<p><code>networkservices. lbRouteExtensions. list</code></p>
<p><code>networkservices. lbTrafficExtensions. list</code></p>
<p><code>networkservices.locations.list</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices. operations. list</code></p>
<p><code>networkservices. route_views. list</code></p>
<p><code>networkservices. serviceBindings. list</code></p>
<p><code>networkservices. serviceLbPolicies. list</code></p>
<p><code>networkservices. swpSecurityExtensions. list</code></p>
<p><code>networkservices.tcpRoutes.list</code></p>
<p><code>networkservices.tlsRoutes.list</code></p>
<p><code>networkservices. wasmPlugins. list</code></p>
<p><code>notebooks. environments. getIamPolicy</code></p>
<p><code>notebooks.environments.list</code></p>
<p><code>notebooks. environments. setIamPolicy</code></p>
<p><code>notebooks. executions. getIamPolicy</code></p>
<p><code>notebooks.executions.list</code></p>
<p><code>notebooks. executions. setIamPolicy</code></p>
<p><code>notebooks. instances. getIamPolicy</code></p>
<p><code>notebooks.instances.list</code></p>
<p><code>notebooks. instances. setIamPolicy</code></p>
<p><code>notebooks.locations.list</code></p>
<p><code>notebooks.operations.list</code></p>
<p><code>notebooks. runtimes. getIamPolicy</code></p>
<p><code>notebooks.runtimes.list</code></p>
<p><code>notebooks. runtimes. setIamPolicy</code></p>
<p><code>notebooks. schedules. getIamPolicy</code></p>
<p><code>notebooks.schedules.list</code></p>
<p><code>notebooks. schedules. setIamPolicy</code></p>
<p><code>observability. analyticsViews. list</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.datasets.list</code></p>
<p><code>observability.links.list</code></p>
<p><code>observability.locations.list</code></p>
<p><code>observability.operations.list</code></p>
<p><code>observability.traceScopes.list</code></p>
<p><code>observability.views.list</code></p>
<p><code>ondemandscanning. operations. list</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>oracledatabase. autonomousDatabaseBackups. list</code></p>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases. list</code></p>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudVmClusters. list</code></p>
<p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.list</code></p>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemInitialStorageSizes. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.list</code></p>
<p><code>oracledatabase.dbVersions.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments. list</code></p>
<p><code>oracledatabase. goldenGateConnectionTypes. list</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentEnvironments. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentTypes. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentVersions. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase.locations.list</code></p>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase. odbNetworks. list</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>oracledatabase. pluggableDatabases. list</code></p>
<p><code>oracledatabase. systemVersions. list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy. customConstraints. list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>osconfig.guestPolicies.list</code></p>
<p><code>osconfig. instanceOSPoliciesCompliances. list</code></p>
<p><code>osconfig.inventories.list</code></p>
<p><code>osconfig.locations.list</code></p>
<p><code>osconfig.operations.list</code></p>
<p><code>osconfig. osPolicyAssignmentReports. list</code></p>
<p><code>osconfig. osPolicyAssignments. list</code></p>
<p><code>osconfig.patchDeployments.list</code></p>
<p><code>osconfig.patchJobs.list</code></p>
<p><code>osconfig. policyOrchestrators. list</code></p>
<p><code>osconfig.upgradeReports.list</code></p>
<p><code>osconfig. vulnerabilityReports. list</code></p>
<p><code>parallelstore.instances.list</code></p>
<p><code>parallelstore.locations.list</code></p>
<p><code>parallelstore.operations.list</code></p>
<p><code>parametermanager. locations. list</code></p>
<p><code>parametermanager. parameterVersions. list</code></p>
<p><code>parametermanager. parameters. list</code></p>
<p><code>parametermanager. templateVersions. list</code></p>
<p><code>parametermanager. templates. list</code></p>
<p><code>paymentsresellersubscription. products. list</code></p>
<p><code>paymentsresellersubscription. promotions. list</code></p>
<p><code>policyremediatormanager. locations. list</code></p>
<p><code>policyremediatormanager. operations. list</code></p>
<p><code>policysimulator. accessPolicySimulationResults. list</code></p>
<p><code>policysimulator. accessPolicySimulations. list</code></p>
<p><code>policysimulator. orgPolicyViolations. list</code></p>
<p><code>policysimulator. orgPolicyViolationsPreviews. list</code></p>
<p><code>policysimulator. replayResults. list</code></p>
<p><code>policysimulator.replays.*</code></p>
<ul>
<li><code>policysimulator.replays.create</code></li>
<li><code>policysimulator.replays.get</code></li>
<li><code>policysimulator.replays.list</code></li>
<li><code>policysimulator.replays.run</code></li>
</ul>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca.caPools.setIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateAuthorities. setIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateRevocationLists. setIamPolicy</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificateTemplates. setIamPolicy</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca. certificates. setIamPolicy</code></p>
<p><code>privateca.locations.list</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>privateca. reusableConfigs. setIamPolicy</code></p>
<p><code>privilegedaccessmanager. entitlements. list</code></p>
<p><code>privilegedaccessmanager. entitlements. setIamPolicy</code></p>
<p><code>privilegedaccessmanager. grants. list</code></p>
<p><code>privilegedaccessmanager. locations. list</code></p>
<p><code>privilegedaccessmanager. operations. list</code></p>
<p><code>proximitybeacon. attachments. list</code></p>
<p><code>proximitybeacon. beacons. getIamPolicy</code></p>
<p><code>proximitybeacon.beacons.list</code></p>
<p><code>proximitybeacon. beacons. setIamPolicy</code></p>
<p><code>proximitybeacon. namespaces. getIamPolicy</code></p>
<p><code>proximitybeacon. namespaces. list</code></p>
<p><code>proximitybeacon. namespaces. setIamPolicy</code></p>
<p><code>pubsub.schemas.getIamPolicy</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.schemas.setIamPolicy</code></p>
<p><code>pubsub.snapshots.getIamPolicy</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub.snapshots.setIamPolicy</code></p>
<p><code>pubsub. subscriptions. getIamPolicy</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub. subscriptions. setIamPolicy</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsub.topics.setIamPolicy</code></p>
<p><code>pubsublite.operations.list</code></p>
<p><code>pubsublite.reservations.list</code></p>
<p><code>pubsublite.subscriptions.list</code></p>
<p><code>pubsublite.topics.list</code></p>
<p><code>recaptchaenterprise. firewallpolicies. list</code></p>
<p><code>recaptchaenterprise.keys.list</code></p>
<p><code>recaptchaenterprise. relatedaccountgroupmemberships. list</code></p>
<p><code>recaptchaenterprise. relatedaccountgroups. list</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. list</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. list</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. list</code></p>
<p><code>recommender. alloydbInstanceSecurityInsights. list</code></p>
<p><code>recommender. alloydbInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. appengineVersionCostInsights. list</code></p>
<p><code>recommender. appengineVersionCostRecommendations. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsInsights. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsRecommendations. list</code></p>
<p><code>recommender. bigqueryMaterializedViewInsights. list</code></p>
<p><code>recommender. bigqueryMaterializedViewRecommendations. list</code></p>
<p><code>recommender. bigqueryPartitionClusterRecommendations. list</code></p>
<p><code>recommender. bigqueryTableStatsInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender. cloudCostGeneralInsights. list</code></p>
<p><code>recommender. cloudCostGeneralRecommendations. list</code></p>
<p><code>recommender. cloudDeprecationGeneralInsights. list</code></p>
<p><code>recommender. cloudDeprecationGeneralRecommendations. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudManageabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudManageabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudPerformanceGeneralInsights. list</code></p>
<p><code>recommender. cloudPerformanceGeneralRecommendations. list</code></p>
<p><code>recommender. cloudRecentChangeInsights. list</code></p>
<p><code>recommender. cloudRecentChangeRecommendations. list</code></p>
<p><code>recommender. cloudReliabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudReliabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudSecurityGeneralInsights. list</code></p>
<p><code>recommender. cloudSecurityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceActivityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOomProbabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceInsights. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. list</code></p>
<p><code>recommender. commitmentUtilizationInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeDiskIdleResourceInsights. list</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeFirewallInsights. list</code></p>
<p><code>recommender. computeIdleResourceInsights. list</code></p>
<p><code>recommender. computeIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeImageIdleResourceInsights. list</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceNetworkThroughputInsights. list</code></p>
<p><code>recommender. containerDiagnosisInsights. list</code></p>
<p><code>recommender. containerDiagnosisRecommendations. list</code></p>
<p><code>recommender.costInsights.list</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. list</code></p>
<p><code>recommender. errorReportingInsights. list</code></p>
<p><code>recommender. errorReportingRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesInsights. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityInsights. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityRecommendations. list</code></p>
<p><code>recommender. gmpGuidedExperienceInsights. list</code></p>
<p><code>recommender. gmpGuidedExperienceRecommendations. list</code></p>
<p><code>recommender. gmpProjectManagementInsights. list</code></p>
<p><code>recommender. gmpProjectManagementRecommendations. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsInsights. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsRecommendations. list</code></p>
<p><code>recommender. iamPolicyChangeRiskInsights. list</code></p>
<p><code>recommender. iamPolicyChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamPolicyInsights. list</code></p>
<p><code>recommender. iamPolicyLateralMovementInsights. list</code></p>
<p><code>recommender. iamPolicyRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountChangeRiskInsights. list</code></p>
<p><code>recommender. iamServiceAccountChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountInsights. list</code></p>
<p><code>recommender.locations.list</code></p>
<p><code>recommender. loggingProductSuggestionContainerInsights. list</code></p>
<p><code>recommender. loggingProductSuggestionContainerRecommendations. list</code></p>
<p><code>recommender. memorystoreManageabilityInsights. list</code></p>
<p><code>recommender. memorystoreManageabilityRecommendations. list</code></p>
<p><code>recommender. memorystorePerformanceInsights. list</code></p>
<p><code>recommender. memorystorePerformanceRecommendations. list</code></p>
<p><code>recommender. memorystoreReliabilityInsights. list</code></p>
<p><code>recommender. memorystoreReliabilityRecommendations. list</code></p>
<p><code>recommender. memorystoreUtilizationInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeRecommendations. list</code></p>
<p><code>recommender. networkAnalyzerCloudSqlInsights. list</code></p>
<p><code>recommender. networkAnalyzerDynamicRouteInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeServiceAccountInsights. list</code></p>
<p><code>recommender. networkAnalyzerIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerLoadBalancerInsights. list</code></p>
<p><code>recommender. networkAnalyzerVpcConnectivityInsights. list</code></p>
<p><code>recommender. orgPolicyInsights. list</code></p>
<p><code>recommender. orgPolicyRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. list</code></p>
<p><code>recommender. resourcemanagerServiceLimitInsights. list</code></p>
<p><code>recommender. resourcemanagerServiceLimitRecommendations. list</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>recommender. spannerDatabaseSecurityInsights. list</code></p>
<p><code>recommender. spannerDatabaseSecurityRecommendations. list</code></p>
<p><code>recommender. spannerProjectReliabilityInsights. list</code></p>
<p><code>recommender. spannerProjectReliabilityRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentInsights. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. list</code></p>
<p><code>recommender. storageBucketSoftDeleteInsights. list</code></p>
<p><code>recommender. storageBucketSoftDeleteRecommendations. list</code></p>
<p><code>recommender. usageCommitmentRecommendations. list</code></p>
<p><code>redis.aclPolicies.list</code></p>
<p><code>redis.backupCollections.list</code></p>
<p><code>redis.backups.list</code></p>
<p><code>redis.clusters.list</code></p>
<p><code>redis.instances.list</code></p>
<p><code>redis.locations.list</code></p>
<p><code>redis.operations.list</code></p>
<p><code>remotebuildexecution. instances. list</code></p>
<p><code>remotebuildexecution. workerpools. list</code></p>
<p><code>resourcemanager. boundaries. list</code></p>
<p><code>resourcemanager. capabilityConfigs. list</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. folders. setIamPolicy</code></p>
<p><code>resourcemanager. hierarchyNodes. listTagBindings</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager. organizations. setIamPolicy</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>resourcemanager.tagHolds.list</code></p>
<p><code>resourcemanager. tagKeys. getIamPolicy</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager. tagKeys. setIamPolicy</code></p>
<p><code>resourcemanager. tagValues. getIamPolicy</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>resourcemanager. tagValues. setIamPolicy</code></p>
<p><code>resourcesettings.settings.list</code></p>
<p><code>retail.branches.list</code></p>
<p><code>retail.catalogs.list</code></p>
<p><code>retail.controls.list</code></p>
<p><code>retail.experiments.list</code></p>
<p><code>retail.models.list</code></p>
<p><code>retail.operations.list</code></p>
<p><code>retail.products.list</code></p>
<p><code>retail.servingConfigs.list</code></p>
<p><code>riskmanager. controlScoreBreakdowns. list</code></p>
<p><code>riskmanager.operations.list</code></p>
<p><code>riskmanager.policies.list</code></p>
<p><code>riskmanager.reports.list</code></p>
<p><code>rma.collectors.list</code></p>
<p><code>rma.locations.list</code></p>
<p><code>rma.operations.list</code></p>
<p><code>roads.selectedRoutes.list</code></p>
<p><code>run.configurations.list</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.instances.setIamPolicy</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.jobs.setIamPolicy</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.operations.list</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.routes.list</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.services.setIamPolicy</code></p>
<p><code>run.tasks.list</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>run.workerpools.setIamPolicy</code></p>
<p><code>runapps.applications.list</code></p>
<p><code>runapps.deployments.list</code></p>
<p><code>runapps.locations.list</code></p>
<p><code>runapps.operations.list</code></p>
<p><code>runtimeconfig. configs. getIamPolicy</code></p>
<p><code>runtimeconfig.configs.list</code></p>
<p><code>runtimeconfig. configs. setIamPolicy</code></p>
<p><code>runtimeconfig.operations.list</code></p>
<p><code>runtimeconfig. variables. getIamPolicy</code></p>
<p><code>runtimeconfig.variables.list</code></p>
<p><code>runtimeconfig. variables. setIamPolicy</code></p>
<p><code>runtimeconfig. waiters. getIamPolicy</code></p>
<p><code>runtimeconfig.waiters.list</code></p>
<p><code>runtimeconfig. waiters. setIamPolicy</code></p>
<p><code>saasservicemgmt. flagAttributes. list</code></p>
<p><code>saasservicemgmt. flagReleases. list</code></p>
<p><code>saasservicemgmt. flagRevisions. list</code></p>
<p><code>saasservicemgmt.flags.list</code></p>
<p><code>saasservicemgmt.locations.list</code></p>
<p><code>saasservicemgmt. operations. list</code></p>
<p><code>saasservicemgmt.poolKinds.list</code></p>
<p><code>saasservicemgmt.pools.list</code></p>
<p><code>saasservicemgmt.releases.list</code></p>
<p><code>saasservicemgmt. rolloutKinds. list</code></p>
<p><code>saasservicemgmt.rollouts.list</code></p>
<p><code>saasservicemgmt.saas.list</code></p>
<p><code>saasservicemgmt. saasReleases. list</code></p>
<p><code>saasservicemgmt. tenantOperations. list</code></p>
<p><code>saasservicemgmt.tenants.list</code></p>
<p><code>saasservicemgmt. unitGroupOperations. list</code></p>
<p><code>saasservicemgmt. unitGroups. list</code></p>
<p><code>saasservicemgmt.unitKinds.list</code></p>
<p><code>saasservicemgmt. unitOperations. list</code></p>
<p><code>saasservicemgmt.units.list</code></p>
<p><code>secretmanager.locations.list</code></p>
<p><code>secretmanager. secrets. getIamPolicy</code></p>
<p><code>secretmanager.secrets.list</code></p>
<p><code>secretmanager. secrets. setIamPolicy</code></p>
<p><code>secretmanager.versions.list</code></p>
<p><code>securedlandingzone. overwatches. list</code></p>
<p><code>securesourcemanager. branchRules. list</code></p>
<p><code>securesourcemanager.hooks.list</code></p>
<p><code>securesourcemanager. instances. getIamPolicy</code></p>
<p><code>securesourcemanager. instances. list</code></p>
<p><code>securesourcemanager. instances. setIamPolicy</code></p>
<p><code>securesourcemanager. issuecomments. list</code></p>
<p><code>securesourcemanager. issues. list</code></p>
<p><code>securesourcemanager. locations. list</code></p>
<p><code>securesourcemanager. operations. list</code></p>
<p><code>securesourcemanager. prcomments. list</code></p>
<p><code>securesourcemanager. pullRequests. list</code></p>
<p><code>securesourcemanager. repositories. getIamPolicy</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. repositories. setIamPolicy</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p>
<p><code>securitycenter.assets.list</code></p>
<p><code>securitycenter. attackpaths. list</code></p>
<p><code>securitycenter. bigQueryExports. list</code></p>
<p><code>securitycenter. compliancesnapshots. list</code></p>
<p><code>securitycenter. effectivesecurityhealthanalyticscustommodules. list</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>securitycenter.issues.list</code></p>
<p><code>securitycenter. muteconfigs. list</code></p>
<p><code>securitycenter. notificationconfig. list</code></p>
<p><code>securitycenter. resourcevalueconfigs. list</code></p>
<p><code>securitycenter. riskreports. list</code></p>
<p><code>securitycenter. securityhealthanalyticscustommodules. list</code></p>
<p><code>securitycenter. sources. getIamPolicy</code></p>
<p><code>securitycenter.sources.list</code></p>
<p><code>securitycenter. sources. setIamPolicy</code></p>
<p><code>securitycenter. valuedresources. list</code></p>
<p><code>securitycenter. vulnerabilitysnapshots. list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. locations. list</code></p>
<p><code>securitycentermanagement. operations. list</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securityposture.locations.list</code></p>
<p><code>securityposture. operations. list</code></p>
<p><code>securityposture. postureDeployments. list</code></p>
<p><code>securityposture. postureTemplates. list</code></p>
<p><code>securityposture.postures.list</code></p>
<p><code>securityposture.reports.list</code></p>
<p><code>servicebroker. bindingoperations. list</code></p>
<p><code>servicebroker. bindings. getIamPolicy</code></p>
<p><code>servicebroker.bindings.list</code></p>
<p><code>servicebroker. bindings. setIamPolicy</code></p>
<p><code>servicebroker. catalogs. getIamPolicy</code></p>
<p><code>servicebroker.catalogs.list</code></p>
<p><code>servicebroker. catalogs. setIamPolicy</code></p>
<p><code>servicebroker. instanceoperations. list</code></p>
<p><code>servicebroker. instances. getIamPolicy</code></p>
<p><code>servicebroker.instances.list</code></p>
<p><code>servicebroker. instances. setIamPolicy</code></p>
<p><code>serviceconsumermanagement. tenancyu. list</code></p>
<p><code>servicedirectory. endpoints. getIamPolicy</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory. endpoints. setIamPolicy</code></p>
<p><code>servicedirectory. locations. list</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory. namespaces. setIamPolicy</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>servicedirectory. services. setIamPolicy</code></p>
<p><code>serviceextensions. locations. list</code></p>
<p><code>servicehealth.artifacts.list</code></p>
<p><code>servicehealth.events.list</code></p>
<p><code>servicehealth.locations.list</code></p>
<p><code>servicehealth. organizationEvents. list</code></p>
<p><code>servicehealth. organizationImpacts. list</code></p>
<p><code>servicemanagement. services. getIamPolicy</code></p>
<p><code>servicemanagement. services. list</code></p>
<p><code>servicemanagement. services. setIamPolicy</code></p>
<p><code>servicenetworking. operations. list</code></p>
<p><code>servicesecurityinsights. clusterSecurityInfo. list</code></p>
<p><code>servicesecurityinsights. securityInfo. list</code></p>
<p><code>servicesecurityinsights. workloadPolicies. list</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>source.repos.getIamPolicy</code></p>
<p><code>source.repos.list</code></p>
<p><code>source.repos.setIamPolicy</code></p>
<p><code>spanner.backupOperations.list</code></p>
<p><code>spanner. backupSchedules. getIamPolicy</code></p>
<p><code>spanner.backupSchedules.list</code></p>
<p><code>spanner. backupSchedules. setIamPolicy</code></p>
<p><code>spanner.backups.getIamPolicy</code></p>
<p><code>spanner.backups.list</code></p>
<p><code>spanner.backups.setIamPolicy</code></p>
<p><code>spanner. databaseOperations. list</code></p>
<p><code>spanner.databaseRoles.list</code></p>
<p><code>spanner.databases.getIamPolicy</code></p>
<p><code>spanner.databases.list</code></p>
<p><code>spanner.databases.setIamPolicy</code></p>
<p><code>spanner. instanceConfigOperations. list</code></p>
<p><code>spanner.instanceConfigs.list</code></p>
<p><code>spanner. instanceOperations. list</code></p>
<p><code>spanner. instancePartitionOperations. list</code></p>
<p><code>spanner. instancePartitions. list</code></p>
<p><code>spanner.instances.getIamPolicy</code></p>
<p><code>spanner.instances.list</code></p>
<p><code>spanner.instances.setIamPolicy</code></p>
<p><code>spanner.sessions.list</code></p>
<p><code>speakerid.phrases.list</code></p>
<p><code>speakerid.speakers.list</code></p>
<p><code>speech.customClasses.list</code></p>
<p><code>speech.locations.list</code></p>
<p><code>speech.operations.list</code></p>
<p><code>speech.phraseSets.list</code></p>
<p><code>speech.recognizers.list</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.list</code></p>
<p><code>storage.bucketOperations.list</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.featureConfigs.list</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.hmacKeys.list</code></p>
<p><code>storage. managedFolders. getIamPolicy</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage. managedFolders. setIamPolicy</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.setIamPolicy</code></p>
<p><code>storagebatchoperations. bucketOperations. list</code></p>
<p><code>storagebatchoperations. jobs. list</code></p>
<p><code>storagebatchoperations. locations. list</code></p>
<p><code>storagebatchoperations. operations. list</code></p>
<p><code>storageinsights. datasetConfigs. list</code></p>
<p><code>storageinsights.locations.list</code></p>
<p><code>storageinsights. operations. list</code></p>
<p><code>storageinsights. reportConfigs. list</code></p>
<p><code>storageinsights. reportDetails. list</code></p>
<p><code>storagetransfer. agentpools. list</code></p>
<p><code>storagetransfer.jobs.list</code></p>
<p><code>storagetransfer. operations. list</code></p>
<p><code>stream.locations.list</code></p>
<p><code>stream.operations.list</code></p>
<p><code>stream.streamContents.list</code></p>
<p><code>stream.streamInstances.list</code></p>
<p><code>telcoautomation. blueprints. list</code></p>
<p><code>telcoautomation. deployments. list</code></p>
<p><code>telcoautomation.edgeSlms.list</code></p>
<p><code>telcoautomation. hydratedDeployments. list</code></p>
<p><code>telcoautomation.locations.list</code></p>
<p><code>telcoautomation. operations. list</code></p>
<p><code>telcoautomation. orchestrationClusters. list</code></p>
<p><code>telcoautomation. publicBlueprints. list</code></p>
<p><code>telemetry. consumers. getIamPolicy</code></p>
<p><code>telemetry. consumers. setIamPolicy</code></p>
<p><code>threatintelligence.alerts.list</code></p>
<p><code>threatintelligence. configurations. list</code></p>
<p><code>threatintelligence. findings. list</code></p>
<p><code>tpu.acceleratortypes.list</code></p>
<p><code>tpu.locations.list</code></p>
<p><code>tpu.nodes.list</code></p>
<p><code>tpu.operations.list</code></p>
<p><code>tpu.runtimeversions.list</code></p>
<p><code>tpu.tensorflowversions.list</code></p>
<p><code>transcoder.jobTemplates.list</code></p>
<p><code>transcoder.jobs.list</code></p>
<p><code>transferappliance. appliances. list</code></p>
<p><code>transferappliance. locations. list</code></p>
<p><code>transferappliance. operations. list</code></p>
<p><code>transferappliance.orders.list</code></p>
<p><code>transferappliance. savedAddresses. list</code></p>
<p><code>translationhub.portals.list</code></p>
<p><code>universalledger.endpoints.list</code></p>
<p><code>universalledger.locations.list</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch.indexes.list</code></p>
<p><code>vectorsearch.locations.list</code></p>
<p><code>vectorsearch.operations.list</code></p>
<p><code>videostitcher.cdnKeys.list</code></p>
<p><code>videostitcher. liveAdTagDetails. list</code></p>
<p><code>videostitcher.liveConfigs.list</code></p>
<p><code>videostitcher.operations.list</code></p>
<p><code>videostitcher.slates.list</code></p>
<p><code>videostitcher. vodAdTagDetails. list</code></p>
<p><code>videostitcher.vodConfigs.list</code></p>
<p><code>videostitcher. vodStitchDetails. list</code></p>
<p><code>visionai.analyses.getIamPolicy</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.analyses.setIamPolicy</code></p>
<p><code>visionai.annotations.list</code></p>
<p><code>visionai.applications.list</code></p>
<p><code>visionai.assets.list</code></p>
<p><code>visionai.clusters.getIamPolicy</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.clusters.setIamPolicy</code></p>
<p><code>visionai.corpora.list</code></p>
<p><code>visionai.dataSchemas.list</code></p>
<p><code>visionai.drafts.list</code></p>
<p><code>visionai.events.getIamPolicy</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.events.setIamPolicy</code></p>
<p><code>visionai.indexEndpoints.list</code></p>
<p><code>visionai.indexes.list</code></p>
<p><code>visionai.instances.list</code></p>
<p><code>visionai.locations.list</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai. operators. getIamPolicy</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai. operators. setIamPolicy</code></p>
<p><code>visionai.processors.list</code></p>
<p><code>visionai.searchConfigs.list</code></p>
<p><code>visionai.series.getIamPolicy</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.series.setIamPolicy</code></p>
<p><code>visionai.streams.getIamPolicy</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.streams.setIamPolicy</code></p>
<p><code>visionai.uistreams.list</code></p>
<p><code>visualinspection. annotationSets. list</code></p>
<p><code>visualinspection. annotationSpecs. list</code></p>
<p><code>visualinspection. annotations. list</code></p>
<p><code>visualinspection.datasets.list</code></p>
<p><code>visualinspection.images.list</code></p>
<p><code>visualinspection. locations. list</code></p>
<p><code>visualinspection. modelEvaluations. list</code></p>
<p><code>visualinspection.models.list</code></p>
<p><code>visualinspection.modules.list</code></p>
<p><code>visualinspection. operations. list</code></p>
<p><code>visualinspection. solutionArtifacts. list</code></p>
<p><code>visualinspection. solutions. list</code></p>
<p><code>vmmigration.cloneJobs.list</code></p>
<p><code>vmmigration.cutoverJobs.list</code></p>
<p><code>vmmigration. datacenterConnectors. list</code></p>
<p><code>vmmigration.deployments.list</code></p>
<p><code>vmmigration.groups.list</code></p>
<p><code>vmmigration. imageImportJobs. list</code></p>
<p><code>vmmigration.imageImports.list</code></p>
<p><code>vmmigration.locations.list</code></p>
<p><code>vmmigration.migratingVms.list</code></p>
<p><code>vmmigration.operations.list</code></p>
<p><code>vmmigration. replicationCycles. list</code></p>
<p><code>vmmigration.sources.list</code></p>
<p><code>vmmigration.targets.list</code></p>
<p><code>vmmigration. utilizationReports. list</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine. clusters. setIamPolicy</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine. datastores. setIamPolicy</code></p>
<p><code>vmwareengine. externalAccessRules. list</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. setIamPolicy</code></p>
<p><code>vmwareengine.locations.list</code></p>
<p><code>vmwareengine. loggingServers. list</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. list</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine.nodeTypes.list</code></p>
<p><code>vmwareengine.nodes.list</code></p>
<p><code>vmwareengine.operations.list</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. setIamPolicy</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine.subnets.list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vpcaccess.connectors.list</code></p>
<p><code>vpcaccess.locations.list</code></p>
<p><code>vpcaccess.operations.list</code></p>
<p><code>workflows.callbacks.list</code></p>
<p><code>workflows.executions.list</code></p>
<p><code>workflows.locations.list</code></p>
<p><code>workflows.operations.list</code></p>
<p><code>workflows.stepEntries.list</code></p>
<p><code>workflows.workflows.list</code></p>
<p><code>workloadcertificate. locations. list</code></p>
<p><code>workloadcertificate. operations. list</code></p>
<p><code>workloadcertificate. workloadRegistrations. list</code></p>
<p><code>workloadidentity. locations. list</code></p>
<p><code>workloadidentity. operations. list</code></p>
<p><code>workloadmanager. actuations. list</code></p>
<p><code>workloadmanager. deployments. list</code></p>
<p><code>workloadmanager. discoveredprofiles. list</code></p>
<p><code>workloadmanager. evaluations. list</code></p>
<p><code>workloadmanager. executions. list</code></p>
<p><code>workloadmanager.findings.list</code></p>
<p><code>workloadmanager.locations.list</code></p>
<p><code>workloadmanager. operations. list</code></p>
<p><code>workloadmanager.results.list</code></p>
<p><code>workloadmanager.rules.list</code></p>
<p><code>workloadmanager.workloads.list</code></p>
<p><code>workstations.operations.list</code></p>
<p><code>workstations. workstationClusters. list</code></p>
<p><code>workstations. workstationConfigs. getIamPolicy</code></p>
<p><code>workstations. workstationConfigs. list</code></p>
<p><code>workstations. workstationConfigs. setIamPolicy</code></p>
<p><code>workstations. workstations. getIamPolicy</code></p>
<p><code>workstations.workstations.list</code></p>
<p><code>workstations. workstations. setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td>Security Reviewer
<p>( <code>roles/ iam.securityReviewer</code> )</p>
<p>Provides permissions to list all resources and allow policies on them.</p></td>
<td><p><code>accessapproval.requests.list</code></p>
<p><code>accesscontextmanager. accessLevels. list</code></p>
<p><code>accesscontextmanager. authorizedOrgsDescs. list</code></p>
<p><code>accesscontextmanager. gcpUserAccessBindings. list</code></p>
<p><code>accesscontextmanager. policies. getIamPolicy</code></p>
<p><code>accesscontextmanager. policies. list</code></p>
<p><code>accesscontextmanager. servicePerimeters. list</code></p>
<p><code>actions.agentVersions.list</code></p>
<p><code>advisorynotifications. notifications.*</code></p>
<ul>
<li><code>advisorynotifications. notifications. get</code></li>
<li><code>advisorynotifications. notifications. list</code></li>
</ul>
<p><code>agentidentity. accessSummaries. list</code></p>
<p><code>agentidentity. authProviders. getIamPolicy</code></p>
<p><code>agentidentity. authProviders. list</code></p>
<p><code>agentidentity. authorizations. list</code></p>
<p><code>agentidentity.locations.list</code></p>
<p><code>agentregistry.agents.list</code></p>
<p><code>agentregistry.bindings.list</code></p>
<p><code>agentregistry.endpoints.list</code></p>
<p><code>agentregistry.locations.list</code></p>
<p><code>agentregistry.mcpServers.list</code></p>
<p><code>agentregistry.operations.list</code></p>
<p><code>agentregistry.publishers.list</code></p>
<p><code>agentregistry.services.list</code></p>
<p><code>agentregistry. skillRevisions. list</code></p>
<p><code>agentregistry. skills. getIamPolicy</code></p>
<p><code>agentregistry.skills.list</code></p>
<p><code>aiplatform. agentAnomalyDetectionScopes. list</code></p>
<p><code>aiplatform.agentExamples.list</code></p>
<p><code>aiplatform.agents.list</code></p>
<p><code>aiplatform. analyzedInvocations. list</code></p>
<p><code>aiplatform. analyzedSessions. list</code></p>
<p><code>aiplatform. annotationSpecs. list</code></p>
<p><code>aiplatform.annotations.list</code></p>
<p><code>aiplatform.apps.list</code></p>
<p><code>aiplatform.artifacts.list</code></p>
<p><code>aiplatform. batchPredictionJobs. list</code></p>
<p><code>aiplatform.cachedContents.list</code></p>
<p><code>aiplatform.contexts.list</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform.dataItems.list</code></p>
<p><code>aiplatform. dataLabelingJobs. list</code></p>
<p><code>aiplatform. datasetVersions. list</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform. deploymentResourcePools. list</code></p>
<p><code>aiplatform. edgeDeploymentJobs. list</code></p>
<p><code>aiplatform.edgeDevices.list</code></p>
<p><code>aiplatform. endpoints. getIamPolicy</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform. entityTypes. getIamPolicy</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform. evaluationExperiments. list</code></p>
<p><code>aiplatform. evaluationItems. list</code></p>
<p><code>aiplatform. evaluationMetrics. list</code></p>
<p><code>aiplatform.evaluationRuns.list</code></p>
<p><code>aiplatform.evaluationSets.list</code></p>
<p><code>aiplatform.exampleStores.list</code></p>
<p><code>aiplatform.executions.list</code></p>
<p><code>aiplatform.extensions.list</code></p>
<p><code>aiplatform. featureGroups. getIamPolicy</code></p>
<p><code>aiplatform.featureGroups.list</code></p>
<p><code>aiplatform. featureMonitorJobs. list</code></p>
<p><code>aiplatform. featureMonitors. list</code></p>
<p><code>aiplatform. featureOnlineStores. getIamPolicy</code></p>
<p><code>aiplatform. featureOnlineStores. list</code></p>
<p><code>aiplatform. featureViewSyncs. list</code></p>
<p><code>aiplatform. featureViews. getIamPolicy</code></p>
<p><code>aiplatform.featureViews.list</code></p>
<p><code>aiplatform.features.list</code></p>
<p><code>aiplatform. featurestores. getIamPolicy</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform. humanInTheLoops. list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.indexEndpoints.list</code></p>
<p><code>aiplatform.indexes.list</code></p>
<p><code>aiplatform.interactions.list</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>aiplatform.memories.list</code></p>
<p><code>aiplatform. memoryRevisions. list</code></p>
<p><code>aiplatform. metadataSchemas. list</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. list</code></p>
<p><code>aiplatform. modelEvaluationSlices. list</code></p>
<p><code>aiplatform. modelEvaluations. list</code></p>
<p><code>aiplatform. modelMonitoringJobs. list</code></p>
<p><code>aiplatform.modelMonitors.list</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform. monitoredAgents. list</code></p>
<p><code>aiplatform.nasJobs.list</code></p>
<p><code>aiplatform. nasTrialDetails. list</code></p>
<p><code>aiplatform. notebookExecutionJobs. list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. getIamPolicy</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform. notebookRuntimes. list</code></p>
<p><code>aiplatform. onlineEvaluators. list</code></p>
<p><code>aiplatform.operations.list</code></p>
<p><code>aiplatform. persistentResources. list</code></p>
<p><code>aiplatform.pipelineJobs.list</code></p>
<p><code>aiplatform. provisionedThroughputRevisions. list</code></p>
<p><code>aiplatform. provisionedThroughputs. list</code></p>
<p><code>aiplatform.ragCorpora.list</code></p>
<p><code>aiplatform.ragFiles.list</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. list</code></p>
<p><code>aiplatform. reasoningEngines. getIamPolicy</code></p>
<p><code>aiplatform. reasoningEngines. list</code></p>
<p><code>aiplatform. sandboxEnvironments. list</code></p>
<p><code>aiplatform.schedules.list</code></p>
<p><code>aiplatform. semanticGovernancePolicies. list</code></p>
<p><code>aiplatform.sessionEvents.list</code></p>
<p><code>aiplatform.sessions.list</code></p>
<p><code>aiplatform. specialistPools. list</code></p>
<p><code>aiplatform.studies.list</code></p>
<p><code>aiplatform.tasks.list</code></p>
<p><code>aiplatform. tensorboardExperiments. list</code></p>
<p><code>aiplatform. tensorboardRuns. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. list</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>aiplatform.trials.list</code></p>
<p><code>aiplatform.tuningJobs.list</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb.databases.list</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>alloydb.locations.list</code></p>
<p><code>alloydb.operations.list</code></p>
<p><code>alloydb. supportedDatabaseFlags. list</code></p>
<p><code>alloydb.users.list</code></p>
<p><code>analyticshub. dataExchanges. getIamPolicy</code></p>
<p><code>analyticshub. dataExchanges. list</code></p>
<p><code>analyticshub. listings. getIamPolicy</code></p>
<p><code>analyticshub.listings.list</code></p>
<p><code>analyticshub. queryTemplates. list</code></p>
<p><code>analyticshub. subscriptions. list</code></p>
<p><code>apigateway. apiconfigs. getIamPolicy</code></p>
<p><code>apigateway.apiconfigs.list</code></p>
<p><code>apigateway.apis.getIamPolicy</code></p>
<p><code>apigateway.apis.list</code></p>
<p><code>apigateway. gateways. getIamPolicy</code></p>
<p><code>apigateway.gateways.list</code></p>
<p><code>apigateway.locations.list</code></p>
<p><code>apigateway.operations.list</code></p>
<p><code>apigee. apiproductattributes. list</code></p>
<p><code>apigee.apiproducts.list</code></p>
<p><code>apigee.appgroupapps.list</code></p>
<p><code>apigee.appgroups.list</code></p>
<p><code>apigee. appgroupsubscriptions. list</code></p>
<p><code>apigee.apps.list</code></p>
<p><code>apigee.archivedeployments.list</code></p>
<p><code>apigee.caches.list</code></p>
<p><code>apigee.datacollectors.list</code></p>
<p><code>apigee.datastores.list</code></p>
<p><code>apigee. deployments. getIamPolicy</code></p>
<p><code>apigee.deployments.list</code></p>
<p><code>apigee. developerappattributes. list</code></p>
<p><code>apigee.developerapps.list</code></p>
<p><code>apigee. developerattributes. list</code></p>
<p><code>apigee.developers.list</code></p>
<p><code>apigee. developersubscriptions. list</code></p>
<p><code>apigee.dnsZones.list</code></p>
<p><code>apigee. endpointattachments. list</code></p>
<p><code>apigee. envgroupattachments. list</code></p>
<p><code>apigee.envgroups.list</code></p>
<p><code>apigee. environments. getIamPolicy</code></p>
<p><code>apigee.environments.list</code></p>
<p><code>apigee.exports.list</code></p>
<p><code>apigee.flowhooks.list</code></p>
<p><code>apigee.hostqueries.list</code></p>
<p><code>apigee. hostsecurityreports. list</code></p>
<p><code>apigee. instanceattachments. list</code></p>
<p><code>apigee.instances.list</code></p>
<p><code>apigee.keystorealiases.list</code></p>
<p><code>apigee.keystores.list</code></p>
<p><code>apigee.keyvaluemapentries.list</code></p>
<p><code>apigee.keyvaluemaps.list</code></p>
<p><code>apigee.nataddresses.list</code></p>
<p><code>apigee.operations.list</code></p>
<p><code>apigee.organizations.list</code></p>
<p><code>apigee.portals.list</code></p>
<p><code>apigee.proxies.list</code></p>
<p><code>apigee.proxyrevisions.list</code></p>
<p><code>apigee.queries.list</code></p>
<p><code>apigee.rateplans.list</code></p>
<p><code>apigee.references.list</code></p>
<p><code>apigee.reports.list</code></p>
<p><code>apigee.resourcefiles.list</code></p>
<p><code>apigee.securityActions.list</code></p>
<p><code>apigee.securityFeedback.list</code></p>
<p><code>apigee.securityIncidents.list</code></p>
<p><code>apigee. securityMonitoringConditions. list</code></p>
<p><code>apigee.securityProfiles.list</code></p>
<p><code>apigee.securityProfilesV2.list</code></p>
<p><code>apigee.securityreports.list</code></p>
<p><code>apigee. sharedflowrevisions. list</code></p>
<p><code>apigee.sharedflows.list</code></p>
<p><code>apigee.spaces.getIamPolicy</code></p>
<p><code>apigee.spaces.list</code></p>
<p><code>apigee.targetservers.list</code></p>
<p><code>apigee. traceconfigoverrides. list</code></p>
<p><code>apigee.tracesessions.list</code></p>
<p><code>apigeeconnect.connections.list</code></p>
<p><code>apigeeregistry. apis. getIamPolicy</code></p>
<p><code>apigeeregistry.apis.list</code></p>
<p><code>apigeeregistry. artifacts. getIamPolicy</code></p>
<p><code>apigeeregistry.artifacts.list</code></p>
<p><code>apigeeregistry. deployments. list</code></p>
<p><code>apigeeregistry.locations.list</code></p>
<p><code>apigeeregistry.operations.list</code></p>
<p><code>apigeeregistry. specs. getIamPolicy</code></p>
<p><code>apigeeregistry.specs.list</code></p>
<p><code>apigeeregistry. versions. getIamPolicy</code></p>
<p><code>apigeeregistry.versions.list</code></p>
<p><code>apihub.addons.list</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apiOperations.list</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.attributes.list</code></p>
<p><code>apihub.curations.list</code></p>
<p><code>apihub.definitions.list</code></p>
<p><code>apihub.dependencies.list</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub. discoveredApiObservations. list</code></p>
<p><code>apihub. discoveredApiOperations. list</code></p>
<p><code>apihub.externalApis.list</code></p>
<p><code>apihub. hostProjectRegistrations. list</code></p>
<p><code>apihub.llmEnablements.list</code></p>
<p><code>apihub.operations.list</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub. runTimeProjectAttachments. list</code></p>
<p><code>apihub.specs.list</code></p>
<p><code>apihub.versions.list</code></p>
<p><code>apikeys.keys.list</code></p>
<p><code>apim.apiObservations.list</code></p>
<p><code>apim.apiOperations.list</code></p>
<p><code>apim.locations.list</code></p>
<p><code>apim.observationJobs.list</code></p>
<p><code>apim.observationSources.list</code></p>
<p><code>apim.operations.list</code></p>
<p><code>appengine.instances.list</code></p>
<p><code>appengine.memcache.list</code></p>
<p><code>appengine.operations.list</code></p>
<p><code>appengine.services.list</code></p>
<p><code>appengine.versions.list</code></p>
<p><code>apphub. applications. getIamPolicy</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.discoveredServices.list</code></p>
<p><code>apphub. discoveredWorkloads. list</code></p>
<p><code>apphub. extendedMetadataSchemas. list</code></p>
<p><code>apphub.locations.list</code></p>
<p><code>apphub.operations.list</code></p>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>applianceactivation. rttCommands. list</code></p>
<p><code>appoptimize.locations.list</code></p>
<p><code>appoptimize.operations.list</code></p>
<p><code>appoptimize.reports.list</code></p>
<p><code>apptopology.domains.list</code></p>
<p><code>apptopology.locations.list</code></p>
<p><code>apptopology.operations.list</code></p>
<p><code>apptopology.topologyViews.list</code></p>
<p><code>artifactregistry. attachments. list</code></p>
<p><code>artifactregistry. dockerimages. list</code></p>
<p><code>artifactregistry.files.list</code></p>
<p><code>artifactregistry. locations. list</code></p>
<p><code>artifactregistry. mavenartifacts. list</code></p>
<p><code>artifactregistry. npmpackages. list</code></p>
<p><code>artifactregistry.packages.list</code></p>
<p><code>artifactregistry. pythonpackages. list</code></p>
<p><code>artifactregistry. repositories. getIamPolicy</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>artifactregistry.rules.list</code></p>
<p><code>artifactregistry.tags.list</code></p>
<p><code>artifactregistry.versions.list</code></p>
<p><code>assuredoss.locations.list</code></p>
<p><code>assuredoss.metadata.list</code></p>
<p><code>assuredoss.operations.list</code></p>
<p><code>assuredworkloads. dbControlComplianceSummaries. list</code></p>
<p><code>assuredworkloads. dbFindingSummaries. list</code></p>
<p><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></p>
<p><code>assuredworkloads. operations. list</code></p>
<p><code>assuredworkloads.updates.list</code></p>
<p><code>assuredworkloads. violations. list</code></p>
<p><code>assuredworkloads.workload.list</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. controlReports. list</code></p>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager. customComplianceFrameworks. list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.list</code></p>
<p><code>auditmanager. resourceEnrollmentStatuses. list</code></p>
<p><code>automl.annotationSpecs.list</code></p>
<p><code>automl.annotations.list</code></p>
<p><code>automl.columnSpecs.list</code></p>
<p><code>automl.datasets.getIamPolicy</code></p>
<p><code>automl.datasets.list</code></p>
<p><code>automl.examples.list</code></p>
<p><code>automl.files.list</code></p>
<p><code>automl. humanAnnotationTasks. list</code></p>
<p><code>automl.locations.getIamPolicy</code></p>
<p><code>automl.locations.list</code></p>
<p><code>automl.modelEvaluations.list</code></p>
<p><code>automl.models.getIamPolicy</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.operations.list</code></p>
<p><code>automl.tableSpecs.list</code></p>
<p><code>automlrecommendations. apiKeys. list</code></p>
<p><code>automlrecommendations. catalogItems. list</code></p>
<p><code>automlrecommendations. catalogs. list</code></p>
<p><code>automlrecommendations. eventStores. list</code></p>
<p><code>automlrecommendations. events. list</code></p>
<p><code>automlrecommendations. placements. list</code></p>
<p><code>automlrecommendations. recommendations. list</code></p>
<p><code>autoscaling.sites.getIamPolicy</code></p>
<p><code>backupdr. appliedAutoProtectionPolicies. list</code></p>
<p><code>backupdr. autoProtectionBindings. list</code></p>
<p><code>backupdr. autoProtectionPolicies. list</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanRevisions. list</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. dataSourceReferences. list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. resourceBackupConfigs. list</code></p>
<p><code>baremetalsolution. instancequotas. list</code></p>
<p><code>baremetalsolution. instances. list</code></p>
<p><code>baremetalsolution.luns.list</code></p>
<p><code>baremetalsolution. maintenanceevents. list</code></p>
<p><code>baremetalsolution. networkquotas. list</code></p>
<p><code>baremetalsolution. networks. list</code></p>
<p><code>baremetalsolution. nfsshares. list</code></p>
<p><code>baremetalsolution. osimages. list</code></p>
<p><code>baremetalsolution.pods.list</code></p>
<p><code>baremetalsolution. procurements. list</code></p>
<p><code>baremetalsolution.skus.list</code></p>
<p><code>baremetalsolution. snapshotschedulepolicies. list</code></p>
<p><code>baremetalsolution.sshKeys.list</code></p>
<p><code>baremetalsolution. storageaggregatepools. list</code></p>
<p><code>baremetalsolution. volumequotas. list</code></p>
<p><code>baremetalsolution.volumes.list</code></p>
<p><code>baremetalsolution. volumesnapshots. list</code></p>
<p><code>batch.jobs.list</code></p>
<p><code>batch.locations.list</code></p>
<p><code>batch.operations.list</code></p>
<p><code>batch.resourceAllowances.list</code></p>
<p><code>batch.tasks.list</code></p>
<p><code>beyondcorp. appConnections. getIamPolicy</code></p>
<p><code>beyondcorp.appConnections.list</code></p>
<p><code>beyondcorp. appConnectors. getIamPolicy</code></p>
<p><code>beyondcorp.appConnectors.list</code></p>
<p><code>beyondcorp. appGateways. getIamPolicy</code></p>
<p><code>beyondcorp.appGateways.list</code></p>
<p><code>beyondcorp.locations.list</code></p>
<p><code>beyondcorp.operations.list</code></p>
<p><code>beyondcorp. securityGateways. getIamPolicy</code></p>
<p><code>beyondcorp. securityGateways. list</code></p>
<p><code>beyondcorp. sgApplications. getIamPolicy</code></p>
<p><code>beyondcorp.sgApplications.list</code></p>
<p><code>beyondcorp.subscriptions.list</code></p>
<p><code>biglake.catalogs.getIamPolicy</code></p>
<p><code>biglake.catalogs.list</code></p>
<p><code>biglake.databases.list</code></p>
<p><code>biglake.locks.list</code></p>
<p><code>biglake. namespaces. getIamPolicy</code></p>
<p><code>biglake.namespaces.list</code></p>
<p><code>biglake.tables.getIamPolicy</code></p>
<p><code>biglake.tables.list</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery. connections. getIamPolicy</code></p>
<p><code>bigquery.connections.list</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.models.list</code></p>
<p><code>bigquery.propertyGraphs.list</code></p>
<p><code>bigquery. reservationAssignments. list</code></p>
<p><code>bigquery. reservationGroups. list</code></p>
<p><code>bigquery. reservations. getIamPolicy</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery.routines.list</code></p>
<p><code>bigquery. rowAccessPolicies. getIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. list</code></p>
<p><code>bigquery.savedqueries.list</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquerymigration. subtasks. list</code></p>
<p><code>bigquerymigration. workflows. list</code></p>
<p><code>bigtable.appProfiles.list</code></p>
<p><code>bigtable. authorizedViews. getIamPolicy</code></p>
<p><code>bigtable.authorizedViews.list</code></p>
<p><code>bigtable.backups.getIamPolicy</code></p>
<p><code>bigtable.backups.list</code></p>
<p><code>bigtable.clusters.list</code></p>
<p><code>bigtable.hotTablets.list</code></p>
<p><code>bigtable. instances. getIamPolicy</code></p>
<p><code>bigtable.instances.list</code></p>
<p><code>bigtable.keyvisualizer.list</code></p>
<p><code>bigtable.locations.list</code></p>
<p><code>bigtable. logicalViews. getIamPolicy</code></p>
<p><code>bigtable.logicalViews.list</code></p>
<p><code>bigtable. materializedViews. getIamPolicy</code></p>
<p><code>bigtable. materializedViews. list</code></p>
<p><code>bigtable.memoryLayers.list</code></p>
<p><code>bigtable. schemaBundles. getIamPolicy</code></p>
<p><code>bigtable.schemaBundles.list</code></p>
<p><code>bigtable.tables.getIamPolicy</code></p>
<p><code>bigtable.tables.list</code></p>
<p><code>billing.accounts.getIamPolicy</code></p>
<p><code>billing.accounts.list</code></p>
<p><code>billing.anomalies.list</code></p>
<p><code>billing. billingAccountPrices. list</code></p>
<p><code>billing. billingAccountServices. list</code></p>
<p><code>billing. billingAccountSkuGroupSkus. list</code></p>
<p><code>billing. billingAccountSkuGroups. list</code></p>
<p><code>billing. billingAccountSkus. list</code></p>
<p><code>billing.budgets.list</code></p>
<p><code>billing.credits.list</code></p>
<p><code>billing. resourceAssociations. list</code></p>
<p><code>billing.subscriptions.list</code></p>
<p><code>binaryauthorization. attestors. getIamPolicy</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization. policy. getIamPolicy</code></p>
<p><code>blockchainnodeengine. blockchainNodes. list</code></p>
<p><code>blockchainnodeengine. locations. list</code></p>
<p><code>blockchainnodeengine. operations. list</code></p>
<p><code>blockchainvalidatormanager. blockchainValidatorConfigs. list</code></p>
<p><code>blockchainvalidatormanager. locations. list</code></p>
<p><code>blockchainvalidatormanager. operations. list</code></p>
<p><code>capacityplanner. capacityPlans. list</code></p>
<p><code>capacityplanner.forecasts.list</code></p>
<p><code>capacityplanner. planAlertInsights. list</code></p>
<p><code>capacityplanner. usageAlertInsights. list</code></p>
<p><code>capacityplanner. usageHistories. list</code></p>
<p><code>carestudio.patients.list</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. locations. list</code></p>
<p><code>certificatemanager. observedcerts. list</code></p>
<p><code>certificatemanager. operations. list</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>ces.agents.list</code></p>
<p><code>ces.appVersions.list</code></p>
<p><code>ces.apps.list</code></p>
<p><code>ces.assistantSessions.list</code></p>
<p><code>ces.changelogs.list</code></p>
<p><code>ces.conversations.list</code></p>
<p><code>ces.deployments.list</code></p>
<p><code>ces.evaluationDatasets.list</code></p>
<p><code>ces. evaluationExpectations. list</code></p>
<p><code>ces.evaluationResults.list</code></p>
<p><code>ces.evaluationRuns.list</code></p>
<p><code>ces.evaluations.list</code></p>
<p><code>ces.examples.list</code></p>
<p><code>ces.guardrails.list</code></p>
<p><code>ces.locations.list</code></p>
<p><code>ces.operations.list</code></p>
<p><code>ces.tools.list</code></p>
<p><code>ces.toolsets.list</code></p>
<p><code>chronicle.analyticValues.list</code></p>
<p><code>chronicle.analytics.list</code></p>
<p><code>chronicle. chatSessionMessages. list</code></p>
<p><code>chronicle.chatSessions.list</code></p>
<p><code>chronicle.collectors.list</code></p>
<p><code>chronicle.conversations.list</code></p>
<p><code>chronicle.coverageDetails.list</code></p>
<p><code>chronicle. curatedRuleSetCategories. list</code></p>
<p><code>chronicle. curatedRuleSetDeployments. list</code></p>
<p><code>chronicle.curatedRuleSets.list</code></p>
<p><code>chronicle.curatedRules.list</code></p>
<p><code>chronicle.dashboardCharts.list</code></p>
<p><code>chronicle. dashboardQueries. list</code></p>
<p><code>chronicle. dashboardScheduledReports. list</code></p>
<p><code>chronicle.dashboards.list</code></p>
<p><code>chronicle. dataAccessLabels. list</code></p>
<p><code>chronicle. dataAccessScopes. list</code></p>
<p><code>chronicle.dataExports.list</code></p>
<p><code>chronicle.dataTableRows.list</code></p>
<p><code>chronicle.dataTables.list</code></p>
<p><code>chronicle.dataTaps.list</code></p>
<p><code>chronicle. enrichmentControls. list</code></p>
<p><code>chronicle.entities.list</code></p>
<p><code>chronicle. extensionValidationReports. list</code></p>
<p><code>chronicle. featuredContentNativeDashboards. list</code></p>
<p><code>chronicle. featuredContentPlaybooks. list</code></p>
<p><code>chronicle. featuredContentRules. list</code></p>
<p><code>chronicle. featuredContentSearchQueries. list</code></p>
<p><code>chronicle.features.list</code></p>
<p><code>chronicle. federationGroups. list</code></p>
<p><code>chronicle.feedPacks.list</code></p>
<p><code>chronicle. feedSourceTypeSchemas. list</code></p>
<p><code>chronicle.feeds.list</code></p>
<p><code>chronicle. findingsRefinementDeployments. list</code></p>
<p><code>chronicle. findingsRefinements. list</code></p>
<p><code>chronicle.forwarders.list</code></p>
<p><code>chronicle. ingestionLogLabels. list</code></p>
<p><code>chronicle. ingestionLogNamespaces. list</code></p>
<p><code>chronicle. investigationComments. list</code></p>
<p><code>chronicle. investigationSteps. list</code></p>
<p><code>chronicle.investigations.list</code></p>
<p><code>chronicle. labsExperimentExecutions. list</code></p>
<p><code>chronicle.labsExperiments.list</code></p>
<p><code>chronicle. logProcessingPipelines. list</code></p>
<p><code>chronicle.logTypeSchemas.list</code></p>
<p><code>chronicle.logTypeSettings.list</code></p>
<p><code>chronicle.logTypes.list</code></p>
<p><code>chronicle.logs.list</code></p>
<p><code>chronicle.messages.list</code></p>
<p><code>chronicle. nativeDashboards. list</code></p>
<p><code>chronicle.notebooks.list</code></p>
<p><code>chronicle.operations.list</code></p>
<p><code>chronicle. parserExtensions. list</code></p>
<p><code>chronicle.parsers.list</code></p>
<p><code>chronicle.parsingErrors.list</code></p>
<p><code>chronicle.queryMetrics.list</code></p>
<p><code>chronicle.referenceLists.list</code></p>
<p><code>chronicle.retrohunts.list</code></p>
<p><code>chronicle.ruleDeployments.list</code></p>
<p><code>chronicle. ruleExecutionErrors. list</code></p>
<p><code>chronicle.rules.list</code></p>
<p><code>chronicle.savedColumnSets.list</code></p>
<p><code>chronicle.searchQueries.list</code></p>
<p><code>chronicle.searchedResults.list</code></p>
<p><code>chronicle. sharedPreferenceSets. list</code></p>
<p><code>chronicle.summaryTables.list</code></p>
<p><code>chronicle. tagSubscriptions. list</code></p>
<p><code>chronicle.tags.list</code></p>
<p><code>chronicle.tenants.list</code></p>
<p><code>chronicle. threatCollections. list</code></p>
<p><code>chronicle. transformerDefinitions. list</code></p>
<p><code>chronicle. validationErrors. list</code></p>
<p><code>chronicle.watchlists.list</code></p>
<p><code>chroniclesm. gcpAssociations. list</code></p>
<p><code>chroniclesm. soarRoleScripts. list</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>cloud.locations.list</code></p>
<p><code>cloudaicompanion. aiDevToolsSettings. list</code></p>
<p><code>cloudaicompanion. codeRepositoryIndexes. list</code></p>
<p><code>cloudaicompanion. codeToolsSettings. list</code></p>
<p><code>cloudaicompanion. dataSharingWithGoogleSettings. list</code></p>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></p>
<p><code>cloudaicompanion. gibqObservabilitySettings. list</code></p>
<p><code>cloudaicompanion. loggingSettings. list</code></p>
<p><code>cloudaicompanion. operations. list</code></p>
<p><code>cloudaicompanion. releaseChannelSettings. list</code></p>
<p><code>cloudaicompanion. repositoryGroups. getIamPolicy</code></p>
<p><code>cloudaicompanion. repositoryGroups. list</code></p>
<p><code>cloudaicompanion. topics. getIamPolicy</code></p>
<p><code>cloudapiregistry. locations. list</code></p>
<p><code>cloudapiregistry. mcpServers. list</code></p>
<p><code>cloudapiregistry.mcpTools.list</code></p>
<p><code>cloudasset.feeds.list</code></p>
<p><code>cloudasset. othercloudconnections. list</code></p>
<p><code>cloudasset.savedqueries.list</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild. connections. getIamPolicy</code></p>
<p><code>cloudbuild.connections.list</code></p>
<p><code>cloudbuild.integrations.list</code></p>
<p><code>cloudbuild.locations.list</code></p>
<p><code>cloudbuild.operations.list</code></p>
<p><code>cloudbuild.repositories.list</code></p>
<p><code>cloudbuild.workerpools.list</code></p>
<p><code>cloudcontrolspartner. accessapprovalrequests. list</code></p>
<p><code>cloudcontrolspartner. customers. list</code></p>
<p><code>cloudcontrolspartner. violations. list</code></p>
<p><code>cloudcontrolspartner. workloads. list</code></p>
<p><code>clouddebugger.breakpoints.list</code></p>
<p><code>clouddebugger.debuggees.list</code></p>
<p><code>clouddeploy. automationRuns. list</code></p>
<p><code>clouddeploy.automations.list</code></p>
<p><code>clouddeploy. customTargetTypes. getIamPolicy</code></p>
<p><code>clouddeploy. customTargetTypes. list</code></p>
<p><code>clouddeploy. deliveryPipelines. getIamPolicy</code></p>
<p><code>clouddeploy. deliveryPipelines. list</code></p>
<p><code>clouddeploy. deployPolicies. getIamPolicy</code></p>
<p><code>clouddeploy. deployPolicies. list</code></p>
<p><code>clouddeploy.jobRuns.list</code></p>
<p><code>clouddeploy.locations.list</code></p>
<p><code>clouddeploy.operations.list</code></p>
<p><code>clouddeploy.releases.list</code></p>
<p><code>clouddeploy.rollouts.list</code></p>
<p><code>clouddeploy. targets. getIamPolicy</code></p>
<p><code>clouddeploy.targets.list</code></p>
<p><code>cloudfunctions. functions. getIamPolicy</code></p>
<p><code>cloudfunctions.functions.list</code></p>
<p><code>cloudfunctions.locations.list</code></p>
<p><code>cloudfunctions.operations.list</code></p>
<p><code>cloudjobdiscovery. companies. list</code></p>
<p><code>cloudkms. cryptoKeyVersions. list</code></p>
<p><code>cloudkms. cryptoKeys. getIamPolicy</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms. ekmConfigs. getIamPolicy</code></p>
<p><code>cloudkms. ekmConnections. getIamPolicy</code></p>
<p><code>cloudkms.ekmConnections.list</code></p>
<p><code>cloudkms. importJobs. getIamPolicy</code></p>
<p><code>cloudkms.importJobs.list</code></p>
<p><code>cloudkms.keyHandles.list</code></p>
<p><code>cloudkms.keyRings.getIamPolicy</code></p>
<p><code>cloudkms.keyRings.list</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>cloudkms. protectableResources. list</code></p>
<p><code>cloudkms.retiredResources.list</code></p>
<p><code>cloudkms. singleTenantHsmInstanceProposals. list</code></p>
<p><code>cloudkms. singleTenantHsmInstances. list</code></p>
<p><code>cloudlocationfinder. cloudLocations. list</code></p>
<p><code>cloudlocationfinder. locations. list</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudnumberregistry. customRanges. list</code></p>
<p><code>cloudnumberregistry. discoveredRanges. list</code></p>
<p><code>cloudnumberregistry. ipamAdminScopes. list</code></p>
<p><code>cloudnumberregistry. locations. list</code></p>
<p><code>cloudnumberregistry. operations. list</code></p>
<p><code>cloudnumberregistry. realms. list</code></p>
<p><code>cloudnumberregistry. registryBooks. list</code></p>
<p><code>cloudonefs.isiloncloud. com/clusters. list</code></p>
<p><code>cloudonefs.isiloncloud. com/fileshares. list</code></p>
<p><code>cloudprivatecatalogproducer. associations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogAssociations. list</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. catalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. producerCatalogs. list</code></p>
<p><code>cloudprivatecatalogproducer. products. getIamPolicy</code></p>
<p><code>cloudprivatecatalogproducer. products. list</code></p>
<p><code>cloudprofiler.profiles.list</code></p>
<p><code>cloudscheduler.jobs.list</code></p>
<p><code>cloudscheduler.locations.list</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controls. list</code></p>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></p>
<p><code>cloudsecurityscanner. crawledurls. list</code></p>
<p><code>cloudsecurityscanner. results. list</code></p>
<p><code>cloudsecurityscanner. scanruns. list</code></p>
<p><code>cloudsecurityscanner. scans. list</code></p>
<p><code>cloudsql.backupRuns.list</code></p>
<p><code>cloudsql. blueGreenDeployments. list</code></p>
<p><code>cloudsql.databases.list</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>cloudsql.sslCerts.list</code></p>
<p><code>cloudsql.users.list</code></p>
<p><code>cloudsql.workloadCaptures.list</code></p>
<p><code>cloudsupport. accounts. getIamPolicy</code></p>
<p><code>cloudsupport.accounts.list</code></p>
<p><code>cloudsupport.techCases.list</code></p>
<p><code>cloudtasks.locations.list</code></p>
<p><code>cloudtasks.queues.getIamPolicy</code></p>
<p><code>cloudtasks.queues.list</code></p>
<p><code>cloudtasks.tasks.list</code></p>
<p><code>cloudtestservice. devicesession. list</code></p>
<p><code>cloudtoolresults. executions. list</code></p>
<p><code>cloudtoolresults. histories. list</code></p>
<p><code>cloudtoolresults.steps.list</code></p>
<p><code>cloudtrace.insights.list</code></p>
<p><code>cloudtrace.tasks.list</code></p>
<p><code>cloudtrace.traceScopes.list</code></p>
<p><code>cloudtrace.traces.list</code></p>
<p><code>cloudtranslate. adaptiveMtDatasets. list</code></p>
<p><code>cloudtranslate. adaptiveMtFiles. list</code></p>
<p><code>cloudtranslate. adaptiveMtSentences. list</code></p>
<p><code>cloudtranslate. customModels. list</code></p>
<p><code>cloudtranslate.datasets.list</code></p>
<p><code>cloudtranslate.glossaries.list</code></p>
<p><code>cloudtranslate. glossaryentries. list</code></p>
<p><code>cloudtranslate.locations.list</code></p>
<p><code>cloudtranslate.operations.list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/activeDirectories. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/ipRanges. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/jobs. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/regions. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/serviceLevels. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/snapshots. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/volumereplication. list</code></p>
<p><code>cloudvolumesgcp-api.netapp. com/volumes. list</code></p>
<p><code>commerceagreementpublishing. agreements. list</code></p>
<p><code>commerceagreementpublishing. documents. list</code></p>
<p><code>commercebusinessenablement. operations. list</code></p>
<p><code>commercebusinessenablement. partnerAccounts. list</code></p>
<p><code>commercebusinessenablement. refunds. list</code></p>
<p><code>commercebusinessenablement. resellerDiscountOffers. list</code></p>
<p><code>commercebusinessenablement. resellerPrivateOfferPlans. list</code></p>
<p><code>commercebusinessenablement. resellerRestrictions. list</code></p>
<p><code>commerceoffercatalog. agreements. list</code></p>
<p><code>commerceoffercatalog. documents. list</code></p>
<p><code>commerceorggovernance. collectionRequestApprovals. list</code></p>
<p><code>commerceorggovernance. collections. list</code></p>
<p><code>commerceorggovernance. populateCollectionJobs. list</code></p>
<p><code>commerceorggovernance. services. list</code></p>
<p><code>commerceprice.events.list</code></p>
<p><code>commerceprice. privateoffers. list</code></p>
<p><code>commerceproducer. analyticsHubListingProductConfigs. list</code></p>
<p><code>commerceproducer. locations. list</code></p>
<p><code>commerceproducer. privateOfferDocuments. list</code></p>
<p><code>commerceproducer. privateOffers. list</code></p>
<p><code>commerceproducer.products.list</code></p>
<p><code>commerceproducer.releases.list</code></p>
<p><code>commerceproducer.services.list</code></p>
<p><code>commerceproducer. skuGroups. list</code></p>
<p><code>commerceproducer.skus.list</code></p>
<p><code>commerceproducer. standardOffers. list</code></p>
<p><code>composer.dags.list</code></p>
<p><code>composer.environments.list</code></p>
<p><code>composer.imageversions.list</code></p>
<p><code>composer.operations.list</code></p>
<p><code>composer. userworkloadsconfigmaps. list</code></p>
<p><code>composer. userworkloadssecrets. list</code></p>
<p><code>compute.acceleratorTypes.list</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute. backendBuckets. getIamPolicy</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendServices. getIamPolicy</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.commitments.list</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute.diskTypes.list</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. firewallPolicies. getIamPolicy</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. futureReservations. getIamPolicy</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute. globalOperations. getIamPolicy</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. list</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.hosts.list</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute. instanceTemplates. getIamPolicy</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute.instances.getIamPolicy</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instantSnapshotGroups. getIamPolicy</code></p>
<p><code>compute. instantSnapshotGroups. list</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectGroups. list</code></p>
<p><code>compute. interconnectLocations. list</code></p>
<p><code>compute. interconnectRemoteLocations. list</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute. licenseCodes. getIamPolicy</code></p>
<p><code>compute.licenseCodes.list</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute.machineTypes.list</code></p>
<p><code>compute.managedRulesets.list</code></p>
<p><code>compute.multiMig.list</code></p>
<p><code>compute.multiMigMembers.list</code></p>
<p><code>compute. networkAttachments. getIamPolicy</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkEdgeSecurityServices. list</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute.networkProfiles.list</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. nodeGroups. getIamPolicy</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute. nodeTemplates. getIamPolicy</code></p>
<p><code>compute.nodeTemplates.list</code></p>
<p><code>compute.nodeTypes.list</code></p>
<p><code>compute.orgRolloutPlans.list</code></p>
<p><code>compute.orgRollouts.list</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute.previewFeatures.list</code></p>
<p><code>compute. publicAdvertisedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. list</code></p>
<p><code>compute. recoverableSnapshots. getIamPolicy</code></p>
<p><code>compute. recoverableSnapshots. list</code></p>
<p><code>compute. regionBackendBuckets. getIamPolicy</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendServices. getIamPolicy</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionFirewallPolicies. getIamPolicy</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute. regionOperations. getIamPolicy</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslPolicies. getIamPolicy</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute.regions.list</code></p>
<p><code>compute.reliabilityRisks.list</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.list</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. resourcePolicies. getIamPolicy</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute.rolloutPlans.list</code></p>
<p><code>compute.rollouts.list</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. serviceAttachments. getIamPolicy</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. snapshotGroups. getIamPolicy</code></p>
<p><code>compute.snapshotGroups.list</code></p>
<p><code>compute.snapshots.getIamPolicy</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslPolicies. getIamPolicy</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. storagePools. getIamPolicy</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. subnetworks. getIamPolicy</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. vmExtensionPolicies. list</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute. zoneOperations. getIamPolicy</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>confidentialcomputing. locations. list</code></p>
<p><code>config. deploymentgrouprevisions. list</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.locations.list</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.list</code></p>
<p><code>config.resourcechanges.list</code></p>
<p><code>config.resourcedrifts.list</code></p>
<p><code>config.resources.list</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.list</code></p>
<p><code>configdelivery. fleetPackages. list</code></p>
<p><code>configdelivery.locations.list</code></p>
<p><code>configdelivery.operations.list</code></p>
<p><code>configdelivery.releases.list</code></p>
<p><code>configdelivery. resourceBundles. list</code></p>
<p><code>configdelivery.rollouts.list</code></p>
<p><code>configdelivery.variants.list</code></p>
<p><code>connectors.actions.list</code></p>
<p><code>connectors. connections. getIamPolicy</code></p>
<p><code>connectors.connections.list</code></p>
<p><code>connectors.connectors.list</code></p>
<p><code>connectors. customConnectorVersions. getIamPolicy</code></p>
<p><code>connectors. customConnectorVersions. list</code></p>
<p><code>connectors. customConnectors. getIamPolicy</code></p>
<p><code>connectors. customConnectors. list</code></p>
<p><code>connectors. endpointAttachments. getIamPolicy</code></p>
<p><code>connectors. endpointAttachments. list</code></p>
<p><code>connectors.entities.list</code></p>
<p><code>connectors.entityTypes.list</code></p>
<p><code>connectors. eventSubscriptions. list</code></p>
<p><code>connectors.eventtypes.list</code></p>
<p><code>connectors.locations.list</code></p>
<p><code>connectors. managedZones. getIamPolicy</code></p>
<p><code>connectors.managedZones.list</code></p>
<p><code>connectors.operations.list</code></p>
<p><code>connectors.providers.list</code></p>
<p><code>connectors.versions.list</code></p>
<p><code>consumerprocurement. accounts. list</code></p>
<p><code>consumerprocurement. consents. list</code></p>
<p><code>consumerprocurement. entitlements. list</code></p>
<p><code>consumerprocurement. events. list</code></p>
<p><code>consumerprocurement. freeTrials. list</code></p>
<p><code>consumerprocurement. orderAttributions. list</code></p>
<p><code>consumerprocurement. orders. list</code></p>
<p><code>contactcenteraiplatform. contactCenters. list</code></p>
<p><code>contactcenteraiplatform. locations. list</code></p>
<p><code>contactcenteraiplatform. operations. list</code></p>
<p><code>contactcenterinsights. analyses. list</code></p>
<p><code>contactcenterinsights. analysisRules. list</code></p>
<p><code>contactcenterinsights. assessmentRules. list</code></p>
<p><code>contactcenterinsights. assessments. list</code></p>
<p><code>contactcenterinsights. authorizedAnalyses. list</code></p>
<p><code>contactcenterinsights. authorizedAssessments. list</code></p>
<p><code>contactcenterinsights. authorizedConversations. list</code></p>
<p><code>contactcenterinsights. authorizedFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. authorizedNotes. list</code></p>
<p><code>contactcenterinsights. authorizedOperations. list</code></p>
<p><code>contactcenterinsights. authorizedViewSets. list</code></p>
<p><code>contactcenterinsights. authorizedViews. getIamPolicy</code></p>
<p><code>contactcenterinsights. authorizedViews. list</code></p>
<p><code>contactcenterinsights. conversations. list</code></p>
<p><code>contactcenterinsights. datasetAnalyses. list</code></p>
<p><code>contactcenterinsights. datasetConversations. list</code></p>
<p><code>contactcenterinsights. datasetFeedbackLabels. list</code></p>
<p><code>contactcenterinsights. datasets. list</code></p>
<p><code>contactcenterinsights. diagnostics. list</code></p>
<p><code>contactcenterinsights. discoveries. list</code></p>
<p><code>contactcenterinsights. discoveryResults. list</code></p>
<p><code>contactcenterinsights. discoveryRevisions. list</code></p>
<p><code>contactcenterinsights. discoveryWorkspaces. list</code></p>
<p><code>contactcenterinsights. faqEntries. list</code></p>
<p><code>contactcenterinsights. faqModels. list</code></p>
<p><code>contactcenterinsights. feedbackLabels. list</code></p>
<p><code>contactcenterinsights. issueModels. list</code></p>
<p><code>contactcenterinsights. issues. list</code></p>
<p><code>contactcenterinsights. notes. list</code></p>
<p><code>contactcenterinsights. operations. list</code></p>
<p><code>contactcenterinsights. phraseMatchers. list</code></p>
<p><code>contactcenterinsights. qaQuestionTags. list</code></p>
<p><code>contactcenterinsights. qaQuestions. list</code></p>
<p><code>contactcenterinsights. qaScorecardRevisions. list</code></p>
<p><code>contactcenterinsights. qaScorecards. list</code></p>
<p><code>contactcenterinsights. views. list</code></p>
<p><code>contactcenterinsights. visibilityLabels. list</code></p>
<p><code>container.apiServices.list</code></p>
<p><code>container.auditSinks.list</code></p>
<p><code>container.backendConfigs.list</code></p>
<p><code>container.bindings.list</code></p>
<p><code>container. certificateSigningRequests. list</code></p>
<p><code>container. clusterRoleBindings. list</code></p>
<p><code>container.clusterRoles.list</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container. componentStatuses. list</code></p>
<p><code>container.configMaps.list</code></p>
<p><code>container. controllerRevisions. list</code></p>
<p><code>container.cronJobs.list</code></p>
<p><code>container.csiDrivers.list</code></p>
<p><code>container.csiNodeInfos.list</code></p>
<p><code>container.csiNodes.list</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container.daemonSets.list</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.endpointSlices.list</code></p>
<p><code>container.endpoints.list</code></p>
<p><code>container.events.list</code></p>
<p><code>container.frontendConfigs.list</code></p>
<p><code>container. horizontalPodAutoscalers. list</code></p>
<p><code>container.ingresses.list</code></p>
<p><code>container. initializerConfigurations. list</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container.leases.list</code></p>
<p><code>container.limitRanges.list</code></p>
<p><code>container. localSubjectAccessReviews. list</code></p>
<p><code>container. managedCertificates. list</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container.namespaces.list</code></p>
<p><code>container.networkPolicies.list</code></p>
<p><code>container.nodes.list</code></p>
<p><code>container.operations.list</code></p>
<p><code>container. persistentVolumeClaims. list</code></p>
<p><code>container. persistentVolumes. list</code></p>
<p><code>container.petSets.list</code></p>
<p><code>container. podDisruptionBudgets. list</code></p>
<p><code>container.podPresets.list</code></p>
<p><code>container. podSecurityPolicies. list</code></p>
<p><code>container.podTemplates.list</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.priorityClasses.list</code></p>
<p><code>container.replicaSets.list</code></p>
<p><code>container. replicationControllers. list</code></p>
<p><code>container.resourceQuotas.list</code></p>
<p><code>container.roleBindings.list</code></p>
<p><code>container.roles.list</code></p>
<p><code>container.runtimeClasses.list</code></p>
<p><code>container.scheduledJobs.list</code></p>
<p><code>container. selfSubjectAccessReviews. list</code></p>
<p><code>container.serviceAccounts.list</code></p>
<p><code>container.services.list</code></p>
<p><code>container.statefulSets.list</code></p>
<p><code>container.storageClasses.list</code></p>
<p><code>container.storageStates.list</code></p>
<p><code>container. storageVersionMigrations. list</code></p>
<p><code>container. subjectAccessReviews. list</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. thirdPartyResources. list</code></p>
<p><code>container.updateInfos.list</code></p>
<p><code>container. validatingWebhookConfigurations. list</code></p>
<p><code>container. volumeAttachments. list</code></p>
<p><code>container. volumeSnapshotClasses. list</code></p>
<p><code>container. volumeSnapshotContents. list</code></p>
<p><code>container.volumeSnapshots.list</code></p>
<p><code>containeranalysis. notes. getIamPolicy</code></p>
<p><code>containeranalysis.notes.list</code></p>
<p><code>containeranalysis. occurrences. getIamPolicy</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>containersecurity. clusterSummaries. list</code></p>
<p><code>containersecurity. findings. list</code></p>
<p><code>containersecurity. locations. list</code></p>
<p><code>contentwarehouse.corpora.list</code></p>
<p><code>contentwarehouse. documentSchemas. list</code></p>
<p><code>contentwarehouse. documents. getIamPolicy</code></p>
<p><code>contentwarehouse. documents. list</code></p>
<p><code>contentwarehouse.ruleSets.list</code></p>
<p><code>contentwarehouse. synonymSets. list</code></p>
<p><code>databasecenter. databaseGroups. list</code></p>
<p><code>databasecenter. fleetHealthStats. list</code></p>
<p><code>databasecenter. fleetInsights. list</code></p>
<p><code>databasecenter.fleetStats.list</code></p>
<p><code>databasecenter.locations.list</code></p>
<p><code>databasecenter.products.list</code></p>
<p><code>databasecenter.queryStats.list</code></p>
<p><code>databasecenter. reportConfigs. list</code></p>
<p><code>databasecenter.userLabels.list</code></p>
<p><code>databasecenter.userTags.list</code></p>
<p><code>databaseinsights. locations. list</code></p>
<p><code>databasesconsole. locations. list</code></p>
<p><code>databasesconsole. operations. list</code></p>
<p><code>databasesconsole. studioQueries. list</code></p>
<p><code>datacatalog. categories. getIamPolicy</code></p>
<p><code>datacatalog. entries. getIamPolicy</code></p>
<p><code>datacatalog.entries.list</code></p>
<p><code>datacatalog. entryGroups. getIamPolicy</code></p>
<p><code>datacatalog.entryGroups.list</code></p>
<p><code>datacatalog.operations.list</code></p>
<p><code>datacatalog.relationships.list</code></p>
<p><code>datacatalog. tagTemplates. getIamPolicy</code></p>
<p><code>datacatalog. taxonomies. getIamPolicy</code></p>
<p><code>datacatalog.taxonomies.list</code></p>
<p><code>dataconnectors. connectors. getIamPolicy</code></p>
<p><code>dataconnectors.connectors.list</code></p>
<p><code>dataconnectors.locations.list</code></p>
<p><code>dataconnectors.operations.list</code></p>
<p><code>dataflow.jobs.list</code></p>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.snapshots.list</code></p>
<p><code>dataform.commentThreads.list</code></p>
<p><code>dataform.comments.list</code></p>
<p><code>dataform. compilationResults. list</code></p>
<p><code>dataform.folders.getIamPolicy</code></p>
<p><code>dataform.locations.list</code></p>
<p><code>dataform.operations.list</code></p>
<p><code>dataform.releaseConfigs.list</code></p>
<p><code>dataform. repositories. getIamPolicy</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. teamFolders. getIamPolicy</code></p>
<p><code>dataform.workflowConfigs.list</code></p>
<p><code>dataform. workflowInvocations. list</code></p>
<p><code>dataform. workspaces. getIamPolicy</code></p>
<p><code>dataform.workspaces.list</code></p>
<p><code>datafusion.artifacts.list</code></p>
<p><code>datafusion. instances. getIamPolicy</code></p>
<p><code>datafusion.instances.list</code></p>
<p><code>datafusion.locations.list</code></p>
<p><code>datafusion. namespaces. getIamPolicy</code></p>
<p><code>datafusion.namespaces.list</code></p>
<p><code>datafusion.operations.list</code></p>
<p><code>datafusion. pipelineConnections. list</code></p>
<p><code>datafusion.pipelines.list</code></p>
<p><code>datafusion.profiles.list</code></p>
<p><code>datafusion.secureKeys.list</code></p>
<p><code>datalabeling. annotateddatasets. list</code></p>
<p><code>datalabeling. annotationspecsets. list</code></p>
<p><code>datalabeling.dataitems.list</code></p>
<p><code>datalabeling.datasets.list</code></p>
<p><code>datalabeling.examples.list</code></p>
<p><code>datalabeling.instructions.list</code></p>
<p><code>datalabeling.operations.list</code></p>
<p><code>datalineage.events.list</code></p>
<p><code>datalineage. processRevisions. list</code></p>
<p><code>datalineage.processes.list</code></p>
<p><code>datalineage.runs.list</code></p>
<p><code>datamigration. connectionprofiles. getIamPolicy</code></p>
<p><code>datamigration. connectionprofiles. list</code></p>
<p><code>datamigration. conversionworkspaces. getIamPolicy</code></p>
<p><code>datamigration. conversionworkspaces. list</code></p>
<p><code>datamigration.locations.list</code></p>
<p><code>datamigration. mappingrules. getIamPolicy</code></p>
<p><code>datamigration. migrationjobs. getIamPolicy</code></p>
<p><code>datamigration. migrationjobs. list</code></p>
<p><code>datamigration.objects.list</code></p>
<p><code>datamigration.operations.list</code></p>
<p><code>datamigration. privateconnections. getIamPolicy</code></p>
<p><code>datamigration. privateconnections. list</code></p>
<p><code>datapipelines.jobs.list</code></p>
<p><code>datapipelines.pipelines.list</code></p>
<p><code>dataplex. aspectTypes. getIamPolicy</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.assetActions.list</code></p>
<p><code>dataplex.assets.getIamPolicy</code></p>
<p><code>dataplex.assets.list</code></p>
<p><code>dataplex. changeRequests. getIamPolicy</code></p>
<p><code>dataplex.changeRequests.list</code></p>
<p><code>dataplex.content.getIamPolicy</code></p>
<p><code>dataplex.content.list</code></p>
<p><code>dataplex.dataAssets.list</code></p>
<p><code>dataplex. dataAttributeBindings. getIamPolicy</code></p>
<p><code>dataplex. dataAttributeBindings. list</code></p>
<p><code>dataplex. dataAttributes. getIamPolicy</code></p>
<p><code>dataplex.dataAttributes.list</code></p>
<p><code>dataplex. dataDomainBindings. list</code></p>
<p><code>dataplex. dataDomains. getIamPolicy</code></p>
<p><code>dataplex.dataDomains.list</code></p>
<p><code>dataplex. dataProducts. getIamPolicy</code></p>
<p><code>dataplex.dataProducts.list</code></p>
<p><code>dataplex. dataTaxonomies. getIamPolicy</code></p>
<p><code>dataplex.dataTaxonomies.list</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.encryptionConfig.list</code></p>
<p><code>dataplex.entities.list</code></p>
<p><code>dataplex.entries.list</code></p>
<p><code>dataplex. entryGroups. getIamPolicy</code></p>
<p><code>dataplex.entryGroups.list</code></p>
<p><code>dataplex. entryLinkTypes. getIamPolicy</code></p>
<p><code>dataplex.entryLinkTypes.list</code></p>
<p><code>dataplex. entryTypes. getIamPolicy</code></p>
<p><code>dataplex.entryTypes.list</code></p>
<p><code>dataplex. environments. getIamPolicy</code></p>
<p><code>dataplex.environments.list</code></p>
<p><code>dataplex. glossaries. getIamPolicy</code></p>
<p><code>dataplex.glossaries.list</code></p>
<p><code>dataplex. glossaryCategories. list</code></p>
<p><code>dataplex.glossaryTerms.list</code></p>
<p><code>dataplex.lakeActions.list</code></p>
<p><code>dataplex.lakes.getIamPolicy</code></p>
<p><code>dataplex.lakes.list</code></p>
<p><code>dataplex.locations.list</code></p>
<p><code>dataplex.metadataFeeds.list</code></p>
<p><code>dataplex.metadataJobs.list</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.partitions.list</code></p>
<p><code>dataplex.tasks.getIamPolicy</code></p>
<p><code>dataplex.tasks.list</code></p>
<p><code>dataplex.zoneActions.list</code></p>
<p><code>dataplex.zones.getIamPolicy</code></p>
<p><code>dataplex.zones.list</code></p>
<p><code>dataproc.agents.list</code></p>
<p><code>dataproc. autoscalingPolicies. getIamPolicy</code></p>
<p><code>dataproc. autoscalingPolicies. list</code></p>
<p><code>dataproc.batches.list</code></p>
<p><code>dataproc.clusters.getIamPolicy</code></p>
<p><code>dataproc.clusters.list</code></p>
<p><code>dataproc.jobs.getIamPolicy</code></p>
<p><code>dataproc.jobs.list</code></p>
<p><code>dataproc. operations. getIamPolicy</code></p>
<p><code>dataproc.operations.list</code></p>
<p><code>dataproc.sessionTemplates.list</code></p>
<p><code>dataproc.sessions.list</code></p>
<p><code>dataproc. workflowTemplates. getIamPolicy</code></p>
<p><code>dataproc. workflowTemplates. list</code></p>
<p><code>dataprocessing. datasources. list</code></p>
<p><code>dataprocessing. featurecontrols. list</code></p>
<p><code>dataprocessing. groupcontrols. list</code></p>
<p><code>dataprocrm.locations.list</code></p>
<p><code>dataprocrm.nodePools.list</code></p>
<p><code>dataprocrm.nodes.list</code></p>
<p><code>dataprocrm.operations.list</code></p>
<p><code>dataprocrm.workloads.list</code></p>
<p><code>datastore.backupSchedules.list</code></p>
<p><code>datastore.backups.list</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.list</code></p>
<p><code>datastore. keyVisualizerScans. list</code></p>
<p><code>datastore.locations.list</code></p>
<p><code>datastore.namespaces.list</code></p>
<p><code>datastore.operations.list</code></p>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.list</code></p>
<p><code>datastore.userCreds.list</code></p>
<p><code>datastream. connectionProfiles. getIamPolicy</code></p>
<p><code>datastream. connectionProfiles. list</code></p>
<p><code>datastream.locations.list</code></p>
<p><code>datastream.objects.list</code></p>
<p><code>datastream.operations.list</code></p>
<p><code>datastream. privateConnections. getIamPolicy</code></p>
<p><code>datastream. privateConnections. list</code></p>
<p><code>datastream.routes.getIamPolicy</code></p>
<p><code>datastream.routes.list</code></p>
<p><code>datastream. streams. getIamPolicy</code></p>
<p><code>datastream.streams.list</code></p>
<p><code>datastudio. datasources. getIamPolicy</code></p>
<p><code>datastudio. reports. getIamPolicy</code></p>
<p><code>datastudio. workspaces. getIamPolicy</code></p>
<p><code>deploymentmanager. compositeTypes. list</code></p>
<p><code>deploymentmanager. deployments. getIamPolicy</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. manifests. list</code></p>
<p><code>deploymentmanager. operations. list</code></p>
<p><code>deploymentmanager. resources. list</code></p>
<p><code>deploymentmanager. typeProviders. list</code></p>
<p><code>deploymentmanager.types.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.list</code></p>
<p><code>designcenter.connections.list</code></p>
<p><code>designcenter.locations.list</code></p>
<p><code>designcenter.operations.list</code></p>
<p><code>designcenter. sharedTemplateRevisions. list</code></p>
<p><code>designcenter. sharedTemplates. list</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>developerconnect. accountConnectors. list</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. deploymentEvents. list</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect. insightsConfigs. list</code></p>
<p><code>developerconnect. locations. list</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>developerconnect. providers. list</code></p>
<p><code>developerconnect.users.list</code></p>
<p><code>devicerun.devices.list</code></p>
<p><code>devicerun.locations.list</code></p>
<p><code>devicerun.operations.list</code></p>
<p><code>devicerun.sessions.list</code></p>
<p><code>devicerun. softwareVersions. list</code></p>
<p><code>devicestreaming. deviceSessions. list</code></p>
<p><code>dialogflow.agents.list</code></p>
<p><code>dialogflow.answerrecords.list</code></p>
<p><code>dialogflow.callMatchers.list</code></p>
<p><code>dialogflow.changelogs.list</code></p>
<p><code>dialogflow. companionAgents. list</code></p>
<p><code>dialogflow.contexts.list</code></p>
<p><code>dialogflow. conversationDatasets. list</code></p>
<p><code>dialogflow. conversationModels. list</code></p>
<p><code>dialogflow. conversationProfiles. list</code></p>
<p><code>dialogflow.conversations.list</code></p>
<p><code>dialogflow.deployments.list</code></p>
<p><code>dialogflow.documents.list</code></p>
<p><code>dialogflow.entityTypes.list</code></p>
<p><code>dialogflow.environments.list</code></p>
<p><code>dialogflow.examples.list</code></p>
<p><code>dialogflow.experiments.list</code></p>
<p><code>dialogflow.flows.list</code></p>
<p><code>dialogflow.generators.list</code></p>
<p><code>dialogflow.integrations.list</code></p>
<p><code>dialogflow.intents.list</code></p>
<p><code>dialogflow.knowledgeBases.list</code></p>
<p><code>dialogflow.messages.list</code></p>
<p><code>dialogflow. modelEvaluations. list</code></p>
<p><code>dialogflow.pages.list</code></p>
<p><code>dialogflow.participants.list</code></p>
<p><code>dialogflow. phoneNumberOrders. list</code></p>
<p><code>dialogflow.phoneNumbers.list</code></p>
<p><code>dialogflow.playbooks.list</code></p>
<p><code>dialogflow. securitySettings. list</code></p>
<p><code>dialogflow. sessionEntityTypes. list</code></p>
<p><code>dialogflow. smartMessagingEntries. list</code></p>
<p><code>dialogflow.testcases.list</code></p>
<p><code>dialogflow.tools.list</code></p>
<p><code>dialogflow. transitionRouteGroups. list</code></p>
<p><code>dialogflow.versions.list</code></p>
<p><code>dialogflow.webhooks.list</code></p>
<p><code>discoveryengine. agentFiles. list</code></p>
<p><code>discoveryengine. agentIamProposals. list</code></p>
<p><code>discoveryengine. agents. getIamPolicy</code></p>
<p><code>discoveryengine.agents.list</code></p>
<p><code>discoveryengine. assistants. list</code></p>
<p><code>discoveryengine. authorizations. list</code></p>
<p><code>discoveryengine. billingAccountLicenseConfigs. list</code></p>
<p><code>discoveryengine.branches.list</code></p>
<p><code>discoveryengine. cannedQueries. list</code></p>
<p><code>discoveryengine. cmekConfigs. list</code></p>
<p><code>discoveryengine. collections. getIamPolicy</code></p>
<p><code>discoveryengine. collections. list</code></p>
<p><code>discoveryengine. connectorRuns. list</code></p>
<p><code>discoveryengine.controls.list</code></p>
<p><code>discoveryengine. conversations. list</code></p>
<p><code>discoveryengine. dataStores. getIamPolicy</code></p>
<p><code>discoveryengine. dataStores. list</code></p>
<p><code>discoveryengine.documents.list</code></p>
<p><code>discoveryengine. engines. getIamPolicy</code></p>
<p><code>discoveryengine.engines.list</code></p>
<p><code>discoveryengine. evaluations. list</code></p>
<p><code>discoveryengine. identityMappingStores. list</code></p>
<p><code>discoveryengine. immersiveArtifacts. list</code></p>
<p><code>discoveryengine. licenseConfigs. list</code></p>
<p><code>discoveryengine.memories.list</code></p>
<p><code>discoveryengine.models.list</code></p>
<p><code>discoveryengine. notebooks. getIamPolicy</code></p>
<p><code>discoveryengine.notebooks.list</code></p>
<p><code>discoveryengine. notificationMessages. list</code></p>
<p><code>discoveryengine. operations. list</code></p>
<p><code>discoveryengine. sampleQueries. list</code></p>
<p><code>discoveryengine. sampleQuerySets. list</code></p>
<p><code>discoveryengine.schemas.list</code></p>
<p><code>discoveryengine. servingConfigs. list</code></p>
<p><code>discoveryengine.sessions.list</code></p>
<p><code>discoveryengine. sharedContents. list</code></p>
<p><code>discoveryengine. targetSites. list</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.columnDataProfiles.list</code></p>
<p><code>dlp.connections.list</code></p>
<p><code>dlp.contentPolicies.list</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.estimates.list</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.locations.list</code></p>
<p><code>dlp.projectDataProfiles.list</code></p>
<p><code>dlp.storedInfoTypes.list</code></p>
<p><code>dlp.subscriptions.list</code></p>
<p><code>dlp.tableDataProfiles.list</code></p>
<p><code>dns.changes.list</code></p>
<p><code>dns.dnsKeys.list</code></p>
<p><code>dns.managedZoneOperations.list</code></p>
<p><code>dns.managedZones.getIamPolicy</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.responsePolicies.list</code></p>
<p><code>dns.responsePolicyRules.list</code></p>
<p><code>documentai. dataLabelingJobs. list</code></p>
<p><code>documentai.evaluations.list</code></p>
<p><code>documentai.labelerPools.list</code></p>
<p><code>documentai.locations.list</code></p>
<p><code>documentai.processorTypes.list</code></p>
<p><code>documentai. processorVersions. list</code></p>
<p><code>documentai.processors.list</code></p>
<p><code>documentai.rules.list</code></p>
<p><code>documentai.schemaVersions.list</code></p>
<p><code>documentai.schemas.list</code></p>
<p><code>documentai.validators.list</code></p>
<p><code>domains.locations.list</code></p>
<p><code>domains.operations.list</code></p>
<p><code>domains. registrations. getIamPolicy</code></p>
<p><code>domains.registrations.list</code></p>
<p><code>dspm.locations.list</code></p>
<p><code>dspm.operations.list</code></p>
<p><code>earthengine. assets. getIamPolicy</code></p>
<p><code>earthengine.assets.list</code></p>
<p><code>earthengine.operations.list</code></p>
<p><code>edgecontainer.apikeys.list</code></p>
<p><code>edgecontainer. clusters. getIamPolicy</code></p>
<p><code>edgecontainer.clusters.list</code></p>
<p><code>edgecontainer. identityproviders. list</code></p>
<p><code>edgecontainer.locations.list</code></p>
<p><code>edgecontainer. machines. getIamPolicy</code></p>
<p><code>edgecontainer.machines.list</code></p>
<p><code>edgecontainer. nodePools. getIamPolicy</code></p>
<p><code>edgecontainer.nodePools.list</code></p>
<p><code>edgecontainer.operations.list</code></p>
<p><code>edgecontainer. serviceaccounts. list</code></p>
<p><code>edgecontainer. vpnConnections. getIamPolicy</code></p>
<p><code>edgecontainer. vpnConnections. list</code></p>
<p><code>edgecontainer. zonalProjects. list</code></p>
<p><code>edgecontainer. zonalservices. list</code></p>
<p><code>edgecontainer.zones.list</code></p>
<p><code>edgenetwork. interconnectAttachments. getIamPolicy</code></p>
<p><code>edgenetwork. interconnectAttachments. list</code></p>
<p><code>edgenetwork. interconnects. getIamPolicy</code></p>
<p><code>edgenetwork.interconnects.list</code></p>
<p><code>edgenetwork.locations.list</code></p>
<p><code>edgenetwork. networks. getIamPolicy</code></p>
<p><code>edgenetwork.networks.list</code></p>
<p><code>edgenetwork.operations.list</code></p>
<p><code>edgenetwork. routers. getIamPolicy</code></p>
<p><code>edgenetwork.routers.list</code></p>
<p><code>edgenetwork.routes.list</code></p>
<p><code>edgenetwork. subnetworks. getIamPolicy</code></p>
<p><code>edgenetwork.subnetworks.list</code></p>
<p><code>edgenetwork.zones.list</code></p>
<p><code>enterpriseknowledgegraph. entityReconciliationJobs. list</code></p>
<p><code>enterprisepurchasing. gcveCuds. list</code></p>
<p><code>enterprisepurchasing. gcveNodePricingInfo. list</code></p>
<p><code>enterprisepurchasing. licenseKeys. list</code></p>
<p><code>enterprisepurchasing. locations. list</code></p>
<p><code>enterprisepurchasing. operations. list</code></p>
<p><code>errorreporting. applications. list</code></p>
<p><code>errorreporting. errorEvents. list</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>eventarc. channelConnections. getIamPolicy</code></p>
<p><code>eventarc. channelConnections. list</code></p>
<p><code>eventarc.channels.getIamPolicy</code></p>
<p><code>eventarc.channels.list</code></p>
<p><code>eventarc. enrollments. getIamPolicy</code></p>
<p><code>eventarc.enrollments.list</code></p>
<p><code>eventarc. googleApiSources. getIamPolicy</code></p>
<p><code>eventarc.googleApiSources.list</code></p>
<p><code>eventarc. kafkaSources. getIamPolicy</code></p>
<p><code>eventarc.kafkaSources.list</code></p>
<p><code>eventarc.locations.list</code></p>
<p><code>eventarc. messageBuses. getIamPolicy</code></p>
<p><code>eventarc.messageBuses.list</code></p>
<p><code>eventarc.operations.list</code></p>
<p><code>eventarc. pipelines. getIamPolicy</code></p>
<p><code>eventarc.pipelines.list</code></p>
<p><code>eventarc.providers.list</code></p>
<p><code>eventarc.triggers.getIamPolicy</code></p>
<p><code>eventarc.triggers.list</code></p>
<p><code>externalexposure. locations. list</code></p>
<p><code>externalexposure. operations. list</code></p>
<p><code>faulttesting. affectedResources. list</code></p>
<p><code>faulttesting. experimentTemplates. list</code></p>
<p><code>faulttesting.experiments.list</code></p>
<p><code>faulttesting.locations.list</code></p>
<p><code>faulttesting.operations.list</code></p>
<p><code>faulttesting. validationResources. list</code></p>
<p><code>faulttesting.validations.list</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>file.backups.list</code></p>
<p><code>file.instances.list</code></p>
<p><code>file.locations.list</code></p>
<p><code>file.operations.list</code></p>
<p><code>financialservices. locations. list</code></p>
<p><code>financialservices. operations. list</code></p>
<p><code>financialservices. v1backtests. list</code></p>
<p><code>financialservices. v1datasets. list</code></p>
<p><code>financialservices. v1engineconfigs. list</code></p>
<p><code>financialservices. v1engineversions. list</code></p>
<p><code>financialservices. v1instances. list</code></p>
<p><code>financialservices. v1models. list</code></p>
<p><code>financialservices. v1predictions. list</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.links.list</code></p>
<p><code>firebase.playLinks.list</code></p>
<p><code>firebaseabt.experiments.list</code></p>
<p><code>firebaseappcheck. automations. list</code></p>
<p><code>firebaseappdistro.groups.list</code></p>
<p><code>firebaseappdistro. releases. list</code></p>
<p><code>firebaseappdistro.testers.list</code></p>
<p><code>firebaseapphosting. backends. list</code></p>
<p><code>firebaseapphosting.builds.list</code></p>
<p><code>firebaseapphosting. domains. list</code></p>
<p><code>firebaseapphosting. locations. list</code></p>
<p><code>firebaseapphosting. operations. list</code></p>
<p><code>firebaseapphosting. rollouts. list</code></p>
<p><code>firebasecrashlytics. issues. list</code></p>
<p><code>firebasedatabase. instances. list</code></p>
<p><code>firebasedataconnect. connectorRevisions. list</code></p>
<p><code>firebasedataconnect. connectors. list</code></p>
<p><code>firebasedataconnect. locations. list</code></p>
<p><code>firebasedataconnect. operations. list</code></p>
<p><code>firebasedataconnect. schemaRevisions. list</code></p>
<p><code>firebasedataconnect. schemas. list</code></p>
<p><code>firebasedataconnect. services. list</code></p>
<p><code>firebasedynamiclinks. destinations. list</code></p>
<p><code>firebasedynamiclinks. domains. list</code></p>
<p><code>firebasedynamiclinks. links. list</code></p>
<p><code>firebaseextensions. configs. list</code></p>
<p><code>firebaseextensionspublisher. extensions. list</code></p>
<p><code>firebasehosting.sites.list</code></p>
<p><code>firebaseinappmessaging. campaigns. list</code></p>
<p><code>firebasemessagingcampaigns. campaigns. list</code></p>
<p><code>firebaseml.models.list</code></p>
<p><code>firebaseml.modelversions.list</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>firebaserules.releases.list</code></p>
<p><code>firebaserules.rulesets.list</code></p>
<p><code>firebasestorage.buckets.list</code></p>
<p><code>firebasevertexai. promptTemplates. list</code></p>
<p><code>fleetengine. deliveryvehicles. list</code></p>
<p><code>fleetengine.tasks.list</code></p>
<p><code>fleetengine.vehicles.list</code></p>
<p><code>ftp.locations.list</code></p>
<p><code>ftp.operations.list</code></p>
<p><code>ftp.servers.list</code></p>
<p><code>ftp.users.list</code></p>
<p><code>gcp.redisenterprise. com/databases. list</code></p>
<p><code>gcp.redisenterprise. com/subscriptions. list</code></p>
<p><code>gdchardwaremanagement. changeLogEntries. list</code></p>
<p><code>gdchardwaremanagement. comments. list</code></p>
<p><code>gdchardwaremanagement. hardware. list</code></p>
<p><code>gdchardwaremanagement. hardwareGroups. list</code></p>
<p><code>gdchardwaremanagement. locations. list</code></p>
<p><code>gdchardwaremanagement. operations. list</code></p>
<p><code>gdchardwaremanagement. orders. list</code></p>
<p><code>gdchardwaremanagement. sites. list</code></p>
<p><code>gdchardwaremanagement. skus. list</code></p>
<p><code>gdchardwaremanagement. zones. list</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist. locations. list</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>geminidataanalytics. dataAgents. getIamPolicy</code></p>
<p><code>geminidataanalytics. dataAgents. list</code></p>
<p><code>geminidataanalytics. locations. list</code></p>
<p><code>geminidataanalytics. operations. list</code></p>
<p><code>genomics.datasets.getIamPolicy</code></p>
<p><code>genomics.datasets.list</code></p>
<p><code>genomics.operations.list</code></p>
<p><code>gkebackup.backupChannels.list</code></p>
<p><code>gkebackup. backupPlanBindings. list</code></p>
<p><code>gkebackup. backupPlans. getIamPolicy</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup.backups.list</code></p>
<p><code>gkebackup.locations.list</code></p>
<p><code>gkebackup.operations.list</code></p>
<p><code>gkebackup.restoreChannels.list</code></p>
<p><code>gkebackup. restorePlanBindings. list</code></p>
<p><code>gkebackup. restorePlans. getIamPolicy</code></p>
<p><code>gkebackup.restorePlans.list</code></p>
<p><code>gkebackup.restores.list</code></p>
<p><code>gkebackup.volumeBackups.list</code></p>
<p><code>gkebackup.volumeRestores.list</code></p>
<p><code>gkehub.features.getIamPolicy</code></p>
<p><code>gkehub.features.list</code></p>
<p><code>gkehub.locations.list</code></p>
<p><code>gkehub.membershipbindings.list</code></p>
<p><code>gkehub.membershipfeatures.list</code></p>
<p><code>gkehub. memberships. getIamPolicy</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>gkehub.namespaces.list</code></p>
<p><code>gkehub.operations.list</code></p>
<p><code>gkehub.rbacrolebindings.list</code></p>
<p><code>gkehub.scopes.getIamPolicy</code></p>
<p><code>gkehub.scopes.list</code></p>
<p><code>gkemulticloud. attachedClusters. list</code></p>
<p><code>gkemulticloud.awsClusters.list</code></p>
<p><code>gkemulticloud. awsNodePools. list</code></p>
<p><code>gkemulticloud. azureClients. list</code></p>
<p><code>gkemulticloud. azureClusters. list</code></p>
<p><code>gkemulticloud. azureNodePools. list</code></p>
<p><code>gkemulticloud.operations.list</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. list</code></p>
<p><code>gkeonprem. bareMetalClusters. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalClusters. list</code></p>
<p><code>gkeonprem. bareMetalNodePools. getIamPolicy</code></p>
<p><code>gkeonprem. bareMetalNodePools. list</code></p>
<p><code>gkeonprem.locations.list</code></p>
<p><code>gkeonprem.operations.list</code></p>
<p><code>gkeonprem. vmwareAdminClusters. getIamPolicy</code></p>
<p><code>gkeonprem. vmwareAdminClusters. list</code></p>
<p><code>gkeonprem. vmwareClusters. getIamPolicy</code></p>
<p><code>gkeonprem.vmwareClusters.list</code></p>
<p><code>gkeonprem. vmwareNodePools. getIamPolicy</code></p>
<p><code>gkeonprem.vmwareNodePools.list</code></p>
<p><code>gsuiteaddons.deployments.list</code></p>
<p><code>health.subscribers.list</code></p>
<p><code>health.subscriptions.list</code></p>
<p><code>healthcare. annotationStores. getIamPolicy</code></p>
<p><code>healthcare. annotationStores. list</code></p>
<p><code>healthcare.annotations.list</code></p>
<p><code>healthcare. attributeDefinitions. list</code></p>
<p><code>healthcare. consentArtifacts. list</code></p>
<p><code>healthcare. consentStores. getIamPolicy</code></p>
<p><code>healthcare.consentStores.list</code></p>
<p><code>healthcare.consents.list</code></p>
<p><code>healthcare. datasets. getIamPolicy</code></p>
<p><code>healthcare.datasets.list</code></p>
<p><code>healthcare. dicomStores. getIamPolicy</code></p>
<p><code>healthcare.dicomStores.list</code></p>
<p><code>healthcare. fhirStores. getIamPolicy</code></p>
<p><code>healthcare.fhirStores.list</code></p>
<p><code>healthcare.hl7V2Messages.list</code></p>
<p><code>healthcare. hl7V2Stores. getIamPolicy</code></p>
<p><code>healthcare.hl7V2Stores.list</code></p>
<p><code>healthcare.locations.list</code></p>
<p><code>healthcare.operations.list</code></p>
<p><code>healthcare. userDataMappings. list</code></p>
<p><code>hypercomputecluster. clusters. list</code></p>
<p><code>hypercomputecluster. locations. list</code></p>
<p><code>hypercomputecluster. machineLearningRuns. list</code></p>
<p><code>hypercomputecluster. operations. list</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam.denypolicies.list</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. list</code></p>
<p><code>iam.googleapis. com/oauthClients. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>iam.policybindings.list</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iamconnectors. accessEvents. list</code></p>
<p><code>iamconnectors. authorizations. list</code></p>
<p><code>iamconnectors. connectors. getIamPolicy</code></p>
<p><code>iamconnectors.connectors.list</code></p>
<p><code>iamconnectors.locations.list</code></p>
<p><code>iamconnectors.operations.list</code></p>
<p><code>iap.tunnel.getIamPolicy</code></p>
<p><code>iap. tunnelDestGroups. getIamPolicy</code></p>
<p><code>iap.tunnelDestGroups.list</code></p>
<p><code>iap. tunnelInstances. getIamPolicy</code></p>
<p><code>iap. tunnelLocations. getIamPolicy</code></p>
<p><code>iap.tunnelZones.getIamPolicy</code></p>
<p><code>iap.web.getIamPolicy</code></p>
<p><code>iap. webServiceVersions. getIamPolicy</code></p>
<p><code>iap.webServices.getIamPolicy</code></p>
<p><code>iap.webTypes.getIamPolicy</code></p>
<p><code>identitytoolkit. tenants. getIamPolicy</code></p>
<p><code>identitytoolkit.tenants.list</code></p>
<p><code>ids.endpoints.getIamPolicy</code></p>
<p><code>ids.endpoints.list</code></p>
<p><code>ids.locations.list</code></p>
<p><code>ids.operations.list</code></p>
<p><code>integrations. apigeeAuthConfigs. list</code></p>
<p><code>integrations. apigeeCertificates. list</code></p>
<p><code>integrations. apigeeExecutions. list</code></p>
<p><code>integrations. apigeeIntegrationVers. list</code></p>
<p><code>integrations. apigeeIntegrations. list</code></p>
<p><code>integrations. apigeeSfdcChannels. list</code></p>
<p><code>integrations. apigeeSfdcInstances. list</code></p>
<p><code>integrations. apigeeSuspensions. list</code></p>
<p><code>integrations.authConfigs.list</code></p>
<p><code>integrations.certificates.list</code></p>
<p><code>integrations.executions.list</code></p>
<p><code>integrations. integrationVersions. list</code></p>
<p><code>integrations.integrations.list</code></p>
<p><code>integrations. securityAuthConfigs. list</code></p>
<p><code>integrations. securityExecutions. list</code></p>
<p><code>integrations. securityIntegTempVers. list</code></p>
<p><code>integrations. securityIntegrationVers. list</code></p>
<p><code>integrations. securityIntegrations. list</code></p>
<p><code>integrations.sfdcChannels.list</code></p>
<p><code>integrations. sfdcInstances. list</code></p>
<p><code>integrations.suspensions.list</code></p>
<p><code>integrations.templates.list</code></p>
<p><code>integrations.testCases.list</code></p>
<p><code>issuerswitch. accountManagerTransactions. list</code></p>
<p><code>issuerswitch. complaintTransactions. list</code></p>
<p><code>issuerswitch. financialTransactions. list</code></p>
<p><code>issuerswitch. mandateTransactions. list</code></p>
<p><code>issuerswitch. metadataTransactions. list</code></p>
<p><code>issuerswitch.operations.list</code></p>
<p><code>issuerswitch.ruleMetadata.list</code></p>
<p><code>issuerswitch. ruleMetadataValues. list</code></p>
<p><code>issuerswitch.rules.list</code></p>
<p><code>krmapihosting. krmApiHosts. getIamPolicy</code></p>
<p><code>krmapihosting.krmApiHosts.list</code></p>
<p><code>krmapihosting.locations.list</code></p>
<p><code>krmapihosting.operations.list</code></p>
<p><code>licensemanager. configurations. list</code></p>
<p><code>licensemanager.instances.list</code></p>
<p><code>licensemanager.locations.list</code></p>
<p><code>licensemanager.operations.list</code></p>
<p><code>licensemanager.products.list</code></p>
<p><code>lifesciences.operations.list</code></p>
<p><code>livestream.assets.list</code></p>
<p><code>livestream.channels.list</code></p>
<p><code>livestream.clips.list</code></p>
<p><code>livestream.dvrSessions.list</code></p>
<p><code>livestream.events.list</code></p>
<p><code>livestream.inputs.list</code></p>
<p><code>livestream.locations.list</code></p>
<p><code>livestream.operations.list</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging.exclusions.list</code></p>
<p><code>logging.links.list</code></p>
<p><code>logging.locations.list</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>logging.logScopes.list</code></p>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.notificationRules.list</code></p>
<p><code>logging.operations.list</code></p>
<p><code>logging.privateLogEntries.list</code></p>
<p><code>logging.queries.usePrivate</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>logging.views.getIamPolicy</code></p>
<p><code>logging.views.list</code></p>
<p><code>looker.backups.list</code></p>
<p><code>looker.instances.list</code></p>
<p><code>looker.locations.list</code></p>
<p><code>looker.operations.list</code></p>
<p><code>lustre.instances.list</code></p>
<p><code>lustre.locations.list</code></p>
<p><code>lustre.operations.list</code></p>
<p><code>maintenance.locations.list</code></p>
<p><code>maintenance. resourceMaintenances. list</code></p>
<p><code>managedflink.deployments.list</code></p>
<p><code>managedflink.jobs.list</code></p>
<p><code>managedflink.locations.list</code></p>
<p><code>managedflink.operations.list</code></p>
<p><code>managedflink.sessions.list</code></p>
<p><code>managedidentities. backups. getIamPolicy</code></p>
<p><code>managedidentities.backups.list</code></p>
<p><code>managedidentities. domains. getIamPolicy</code></p>
<p><code>managedidentities.domains.list</code></p>
<p><code>managedidentities. locations. list</code></p>
<p><code>managedidentities. operations. list</code></p>
<p><code>managedidentities. peerings. getIamPolicy</code></p>
<p><code>managedidentities. peerings. list</code></p>
<p><code>managedidentities. sqlintegrations. list</code></p>
<p><code>managedkafka.acls.list</code></p>
<p><code>managedkafka.clusters.list</code></p>
<p><code>managedkafka. connectClusters. list</code></p>
<p><code>managedkafka.connectors.list</code></p>
<p><code>managedkafka. consumerGroups. list</code></p>
<p><code>managedkafka.contexts.list</code></p>
<p><code>managedkafka.locations.list</code></p>
<p><code>managedkafka.operations.list</code></p>
<p><code>managedkafka. schemaRegistries. list</code></p>
<p><code>managedkafka.subjects.list</code></p>
<p><code>managedkafka.topics.list</code></p>
<p><code>managedkafka.versions.list</code></p>
<p><code>mapsadmin.clientMaps.list</code></p>
<p><code>mapsadmin. clientStyleSheetSnapshots. list</code></p>
<p><code>mapsadmin.clientStyles.list</code></p>
<p><code>mapsadmin.mapViews.list</code></p>
<p><code>mapsadmin.styleSnapshots.list</code></p>
<p><code>mapsanalytics. metricMetadata. list</code></p>
<p><code>mapsplatformdatasets. datasets. list</code></p>
<p><code>marketplacesolutions. locations. list</code></p>
<p><code>marketplacesolutions. operations. list</code></p>
<p><code>marketplacesolutions. powerImages. list</code></p>
<p><code>marketplacesolutions. powerInstances. list</code></p>
<p><code>marketplacesolutions. powerNetworks. list</code></p>
<p><code>marketplacesolutions. powerSshKeys. list</code></p>
<p><code>marketplacesolutions. powerVolumes. list</code></p>
<p><code>memcache.instances.list</code></p>
<p><code>memcache.locations.list</code></p>
<p><code>memcache.operations.list</code></p>
<p><code>memorystore. backupCollections. list</code></p>
<p><code>memorystore.backups.list</code></p>
<p><code>memorystore.instances.list</code></p>
<p><code>memorystore.locations.list</code></p>
<p><code>memorystore.operations.list</code></p>
<p><code>metastore.backups.getIamPolicy</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore. databases. getIamPolicy</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore. federations. getIamPolicy</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore.imports.list</code></p>
<p><code>metastore.locations.list</code></p>
<p><code>metastore.migrations.list</code></p>
<p><code>metastore.operations.list</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore.tables.getIamPolicy</code></p>
<p><code>metastore.tables.list</code></p>
<p><code>migrationcenter.assets.list</code></p>
<p><code>migrationcenter. assetsExportJobs. list</code></p>
<p><code>migrationcenter. discoveryClients. list</code></p>
<p><code>migrationcenter. errorFrames. list</code></p>
<p><code>migrationcenter.groups.list</code></p>
<p><code>migrationcenter. importDataFiles. list</code></p>
<p><code>migrationcenter. importJobs. list</code></p>
<p><code>migrationcenter.locations.list</code></p>
<p><code>migrationcenter. operations. list</code></p>
<p><code>migrationcenter. preferenceSets. list</code></p>
<p><code>migrationcenter.relations.list</code></p>
<p><code>migrationcenter. reportConfigs. list</code></p>
<p><code>migrationcenter.reports.list</code></p>
<p><code>migrationcenter.sources.list</code></p>
<p><code>ml.jobs.getIamPolicy</code></p>
<p><code>ml.jobs.list</code></p>
<p><code>ml.locations.list</code></p>
<p><code>ml.models.getIamPolicy</code></p>
<p><code>ml.models.list</code></p>
<p><code>ml.operations.list</code></p>
<p><code>ml.studies.getIamPolicy</code></p>
<p><code>ml.studies.list</code></p>
<p><code>ml.trials.list</code></p>
<p><code>ml.versions.list</code></p>
<p><code>modelarmor.locations.list</code></p>
<p><code>modelarmor.templates.list</code></p>
<p><code>modelarmor.topics.list</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring.alerts.list</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors. list</code></p>
<p><code>monitoring. notificationChannelDescriptors. list</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>netapp.activeDirectories.list</code></p>
<p><code>netapp.backupPolicies.list</code></p>
<p><code>netapp.backupVaults.list</code></p>
<p><code>netapp.backups.list</code></p>
<p><code>netapp.hostGroups.list</code></p>
<p><code>netapp.kmsConfigs.list</code></p>
<p><code>netapp.locations.list</code></p>
<p><code>netapp.operations.list</code></p>
<p><code>netapp.quotaRules.list</code></p>
<p><code>netapp.replications.list</code></p>
<p><code>netapp.snapshots.list</code></p>
<p><code>netapp.storagePools.list</code></p>
<p><code>netapp.volumes.list</code></p>
<p><code>networkconnectivity. gatewayAdvertisedRoutes. list</code></p>
<p><code>networkconnectivity. groups. getIamPolicy</code></p>
<p><code>networkconnectivity. groups. list</code></p>
<p><code>networkconnectivity. hubRouteTables. getIamPolicy</code></p>
<p><code>networkconnectivity. hubRouteTables. list</code></p>
<p><code>networkconnectivity. hubRoutes. getIamPolicy</code></p>
<p><code>networkconnectivity. hubRoutes. list</code></p>
<p><code>networkconnectivity. hubs. getIamPolicy</code></p>
<p><code>networkconnectivity.hubs.list</code></p>
<p><code>networkconnectivity. internalRanges. getIamPolicy</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. locations. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferConfigs. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferDestinations. list</code></p>
<p><code>networkconnectivity. multicloudDataTransferSupportedServices. list</code></p>
<p><code>networkconnectivity. operations. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. getIamPolicy</code></p>
<p><code>networkconnectivity. policyBasedRoutes. list</code></p>
<p><code>networkconnectivity. pscAuthorizationPolicies. list</code></p>
<p><code>networkconnectivity. regionalEndpoints. list</code></p>
<p><code>networkconnectivity. remoteTransportProfiles. list</code></p>
<p><code>networkconnectivity. serviceClasses. list</code></p>
<p><code>networkconnectivity. serviceConnectionMaps. list</code></p>
<p><code>networkconnectivity. serviceConnectionPolicies. list</code></p>
<p><code>networkconnectivity. spokes. getIamPolicy</code></p>
<p><code>networkconnectivity. spokes. list</code></p>
<p><code>networkconnectivity. transports. list</code></p>
<p><code>networkmanagement. connectivitytests. getIamPolicy</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networkmanagement. locations. list</code></p>
<p><code>networkmanagement. monitoringpoints. list</code></p>
<p><code>networkmanagement. networkpaths. list</code></p>
<p><code>networkmanagement. operations. list</code></p>
<p><code>networkmanagement. providers. list</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs. list</code></p>
<p><code>networkmanagement. webpaths. list</code></p>
<p><code>networksecurity. addressGroups. getIamPolicy</code></p>
<p><code>networksecurity. addressGroups. list</code></p>
<p><code>networksecurity. authorizationPolicies. getIamPolicy</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authzPolicies. getIamPolicy</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. backendAuthenticationConfigs. list</code></p>
<p><code>networksecurity. clientTlsPolicies. getIamPolicy</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. dnsThreatDetectors. list</code></p>
<p><code>networksecurity. firewallEndpointAssociations. list</code></p>
<p><code>networksecurity. firewallEndpoints. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity. interceptDeploymentGroups. list</code></p>
<p><code>networksecurity. interceptDeployments. list</code></p>
<p><code>networksecurity. interceptEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. interceptEndpointGroups. list</code></p>
<p><code>networksecurity.locations.list</code></p>
<p><code>networksecurity. mirroringDeploymentGroups. list</code></p>
<p><code>networksecurity. mirroringDeployments. list</code></p>
<p><code>networksecurity. mirroringEndpointGroupAssociations. list</code></p>
<p><code>networksecurity. mirroringEndpointGroups. list</code></p>
<p><code>networksecurity. operations. list</code></p>
<p><code>networksecurity. sacAttachments. list</code></p>
<p><code>networksecurity.sacRealms.list</code></p>
<p><code>networksecurity. securityProfileGroups. list</code></p>
<p><code>networksecurity. securityProfiles. list</code></p>
<p><code>networksecurity. serverTlsPolicies. getIamPolicy</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networkservices. agentGateways. list</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices. googleTagGatewayPolicies. list</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. httpfilters. getIamPolicy</code></p>
<p><code>networkservices. httpfilters. list</code></p>
<p><code>networkservices. lbEdgeExtensions. list</code></p>
<p><code>networkservices. lbRouteExtensions. list</code></p>
<p><code>networkservices. lbTrafficExtensions. list</code></p>
<p><code>networkservices.locations.list</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices. operations. list</code></p>
<p><code>networkservices. route_views. list</code></p>
<p><code>networkservices. serviceBindings. list</code></p>
<p><code>networkservices. serviceLbPolicies. list</code></p>
<p><code>networkservices. swpSecurityExtensions. list</code></p>
<p><code>networkservices.tcpRoutes.list</code></p>
<p><code>networkservices.tlsRoutes.list</code></p>
<p><code>networkservices. wasmPlugins. list</code></p>
<p><code>notebooks. environments. getIamPolicy</code></p>
<p><code>notebooks.environments.list</code></p>
<p><code>notebooks. executions. getIamPolicy</code></p>
<p><code>notebooks.executions.list</code></p>
<p><code>notebooks. instances. getIamPolicy</code></p>
<p><code>notebooks.instances.list</code></p>
<p><code>notebooks.locations.list</code></p>
<p><code>notebooks.operations.list</code></p>
<p><code>notebooks. runtimes. getIamPolicy</code></p>
<p><code>notebooks.runtimes.list</code></p>
<p><code>notebooks. schedules. getIamPolicy</code></p>
<p><code>notebooks.schedules.list</code></p>
<p><code>observability. analyticsViews. list</code></p>
<p><code>observability.buckets.list</code></p>
<p><code>observability.datasets.list</code></p>
<p><code>observability.links.list</code></p>
<p><code>observability.locations.list</code></p>
<p><code>observability.operations.list</code></p>
<p><code>observability.traceScopes.list</code></p>
<p><code>observability.views.list</code></p>
<p><code>ondemandscanning. operations. list</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>oracledatabase. autonomousDatabaseBackups. list</code></p>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases. list</code></p>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudVmClusters. list</code></p>
<p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.list</code></p>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemInitialStorageSizes. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.list</code></p>
<p><code>oracledatabase.dbVersions.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments. list</code></p>
<p><code>oracledatabase. goldenGateConnectionTypes. list</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentEnvironments. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentTypes. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentVersions. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase.locations.list</code></p>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase. odbNetworks. list</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>oracledatabase. pluggableDatabases. list</code></p>
<p><code>oracledatabase. systemVersions. list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy. customConstraints. list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>osconfig.guestPolicies.list</code></p>
<p><code>osconfig. instanceOSPoliciesCompliances. list</code></p>
<p><code>osconfig.inventories.list</code></p>
<p><code>osconfig.locations.list</code></p>
<p><code>osconfig.operations.list</code></p>
<p><code>osconfig. osPolicyAssignmentReports. list</code></p>
<p><code>osconfig. osPolicyAssignments. list</code></p>
<p><code>osconfig.patchDeployments.list</code></p>
<p><code>osconfig.patchJobs.list</code></p>
<p><code>osconfig. policyOrchestrators. list</code></p>
<p><code>osconfig.upgradeReports.list</code></p>
<p><code>osconfig. vulnerabilityReports. list</code></p>
<p><code>parallelstore.instances.list</code></p>
<p><code>parallelstore.locations.list</code></p>
<p><code>parallelstore.operations.list</code></p>
<p><code>parametermanager. locations. list</code></p>
<p><code>parametermanager. parameterVersions. list</code></p>
<p><code>parametermanager. parameters. list</code></p>
<p><code>parametermanager. templateVersions. list</code></p>
<p><code>parametermanager. templates. list</code></p>
<p><code>paymentsresellersubscription. products. list</code></p>
<p><code>paymentsresellersubscription. promotions. list</code></p>
<p><code>policyremediatormanager. locations. list</code></p>
<p><code>policyremediatormanager. operations. list</code></p>
<p><code>policysimulator. accessPolicySimulationResults. list</code></p>
<p><code>policysimulator. accessPolicySimulations. list</code></p>
<p><code>policysimulator. orgPolicyViolations. list</code></p>
<p><code>policysimulator. orgPolicyViolationsPreviews. list</code></p>
<p><code>policysimulator. replayResults. list</code></p>
<p><code>policysimulator.replays.list</code></p>
<p><code>privateca.caPools.getIamPolicy</code></p>
<p><code>privateca.caPools.list</code></p>
<p><code>privateca. certificateAuthorities. getIamPolicy</code></p>
<p><code>privateca. certificateAuthorities. list</code></p>
<p><code>privateca. certificateRevocationLists. getIamPolicy</code></p>
<p><code>privateca. certificateRevocationLists. list</code></p>
<p><code>privateca. certificateTemplates. getIamPolicy</code></p>
<p><code>privateca. certificateTemplates. list</code></p>
<p><code>privateca. certificates. getIamPolicy</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>privateca.locations.list</code></p>
<p><code>privateca.operations.list</code></p>
<p><code>privateca. reusableConfigs. getIamPolicy</code></p>
<p><code>privateca.reusableConfigs.list</code></p>
<p><code>privilegedaccessmanager. entitlements. list</code></p>
<p><code>privilegedaccessmanager. grants. list</code></p>
<p><code>privilegedaccessmanager. locations. list</code></p>
<p><code>privilegedaccessmanager. operations. list</code></p>
<p><code>proximitybeacon. attachments. list</code></p>
<p><code>proximitybeacon. beacons. getIamPolicy</code></p>
<p><code>proximitybeacon.beacons.list</code></p>
<p><code>proximitybeacon. namespaces. getIamPolicy</code></p>
<p><code>proximitybeacon. namespaces. list</code></p>
<p><code>pubsub.schemas.getIamPolicy</code></p>
<p><code>pubsub.schemas.list</code></p>
<p><code>pubsub.snapshots.getIamPolicy</code></p>
<p><code>pubsub.snapshots.list</code></p>
<p><code>pubsub. subscriptions. getIamPolicy</code></p>
<p><code>pubsub.subscriptions.list</code></p>
<p><code>pubsub.topics.getIamPolicy</code></p>
<p><code>pubsub.topics.list</code></p>
<p><code>pubsublite.operations.list</code></p>
<p><code>pubsublite.reservations.list</code></p>
<p><code>pubsublite.subscriptions.list</code></p>
<p><code>pubsublite.topics.list</code></p>
<p><code>recaptchaenterprise. firewallpolicies. list</code></p>
<p><code>recaptchaenterprise.keys.list</code></p>
<p><code>recaptchaenterprise. relatedaccountgroupmemberships. list</code></p>
<p><code>recaptchaenterprise. relatedaccountgroups. list</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. list</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. list</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. list</code></p>
<p><code>recommender. alloydbInstanceSecurityInsights. list</code></p>
<p><code>recommender. alloydbInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. appengineVersionCostInsights. list</code></p>
<p><code>recommender. appengineVersionCostRecommendations. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsInsights. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsRecommendations. list</code></p>
<p><code>recommender. bigqueryMaterializedViewInsights. list</code></p>
<p><code>recommender. bigqueryMaterializedViewRecommendations. list</code></p>
<p><code>recommender. bigqueryPartitionClusterRecommendations. list</code></p>
<p><code>recommender. bigqueryTableStatsInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender. cloudCostGeneralInsights. list</code></p>
<p><code>recommender. cloudCostGeneralRecommendations. list</code></p>
<p><code>recommender. cloudDeprecationGeneralInsights. list</code></p>
<p><code>recommender. cloudDeprecationGeneralRecommendations. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudManageabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudManageabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudPerformanceGeneralInsights. list</code></p>
<p><code>recommender. cloudPerformanceGeneralRecommendations. list</code></p>
<p><code>recommender. cloudRecentChangeInsights. list</code></p>
<p><code>recommender. cloudRecentChangeRecommendations. list</code></p>
<p><code>recommender. cloudReliabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudReliabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudSecurityGeneralInsights. list</code></p>
<p><code>recommender. cloudSecurityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceActivityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOomProbabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceInsights. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. list</code></p>
<p><code>recommender. commitmentUtilizationInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeDiskIdleResourceInsights. list</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeFirewallInsights. list</code></p>
<p><code>recommender. computeIdleResourceInsights. list</code></p>
<p><code>recommender. computeIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeImageIdleResourceInsights. list</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceNetworkThroughputInsights. list</code></p>
<p><code>recommender. containerDiagnosisInsights. list</code></p>
<p><code>recommender. containerDiagnosisRecommendations. list</code></p>
<p><code>recommender.costInsights.list</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. list</code></p>
<p><code>recommender. errorReportingInsights. list</code></p>
<p><code>recommender. errorReportingRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesInsights. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityInsights. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityRecommendations. list</code></p>
<p><code>recommender. gmpGuidedExperienceInsights. list</code></p>
<p><code>recommender. gmpGuidedExperienceRecommendations. list</code></p>
<p><code>recommender. gmpProjectManagementInsights. list</code></p>
<p><code>recommender. gmpProjectManagementRecommendations. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsInsights. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsRecommendations. list</code></p>
<p><code>recommender. iamPolicyChangeRiskInsights. list</code></p>
<p><code>recommender. iamPolicyChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamPolicyInsights. list</code></p>
<p><code>recommender. iamPolicyLateralMovementInsights. list</code></p>
<p><code>recommender. iamPolicyRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountChangeRiskInsights. list</code></p>
<p><code>recommender. iamServiceAccountChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountInsights. list</code></p>
<p><code>recommender.locations.list</code></p>
<p><code>recommender. loggingProductSuggestionContainerInsights. list</code></p>
<p><code>recommender. loggingProductSuggestionContainerRecommendations. list</code></p>
<p><code>recommender. memorystoreManageabilityInsights. list</code></p>
<p><code>recommender. memorystoreManageabilityRecommendations. list</code></p>
<p><code>recommender. memorystorePerformanceInsights. list</code></p>
<p><code>recommender. memorystorePerformanceRecommendations. list</code></p>
<p><code>recommender. memorystoreReliabilityInsights. list</code></p>
<p><code>recommender. memorystoreReliabilityRecommendations. list</code></p>
<p><code>recommender. memorystoreUtilizationInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeRecommendations. list</code></p>
<p><code>recommender. networkAnalyzerCloudSqlInsights. list</code></p>
<p><code>recommender. networkAnalyzerDynamicRouteInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeServiceAccountInsights. list</code></p>
<p><code>recommender. networkAnalyzerIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerLoadBalancerInsights. list</code></p>
<p><code>recommender. networkAnalyzerVpcConnectivityInsights. list</code></p>
<p><code>recommender. orgPolicyInsights. list</code></p>
<p><code>recommender. orgPolicyRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. list</code></p>
<p><code>recommender. resourcemanagerServiceLimitInsights. list</code></p>
<p><code>recommender. resourcemanagerServiceLimitRecommendations. list</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>recommender. spannerDatabaseSecurityInsights. list</code></p>
<p><code>recommender. spannerDatabaseSecurityRecommendations. list</code></p>
<p><code>recommender. spannerProjectReliabilityInsights. list</code></p>
<p><code>recommender. spannerProjectReliabilityRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentInsights. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. list</code></p>
<p><code>recommender. storageBucketSoftDeleteInsights. list</code></p>
<p><code>recommender. storageBucketSoftDeleteRecommendations. list</code></p>
<p><code>recommender. usageCommitmentRecommendations. list</code></p>
<p><code>redis.aclPolicies.list</code></p>
<p><code>redis.backupCollections.list</code></p>
<p><code>redis.backups.list</code></p>
<p><code>redis.clusters.list</code></p>
<p><code>redis.instances.list</code></p>
<p><code>redis.locations.list</code></p>
<p><code>redis.operations.list</code></p>
<p><code>remotebuildexecution. instances. list</code></p>
<p><code>remotebuildexecution. workerpools. list</code></p>
<p><code>resourcemanager. boundaries. list</code></p>
<p><code>resourcemanager. capabilityConfigs. list</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. hierarchyNodes. listTagBindings</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagHolds.list</code></p>
<p><code>resourcemanager. tagKeys. getIamPolicy</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager. tagValues. getIamPolicy</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>resourcesettings.settings.list</code></p>
<p><code>retail.branches.list</code></p>
<p><code>retail.catalogs.list</code></p>
<p><code>retail.controls.list</code></p>
<p><code>retail.experiments.list</code></p>
<p><code>retail.models.list</code></p>
<p><code>retail.operations.list</code></p>
<p><code>retail.products.list</code></p>
<p><code>retail.servingConfigs.list</code></p>
<p><code>riskmanager. controlScoreBreakdowns. list</code></p>
<p><code>riskmanager.operations.list</code></p>
<p><code>riskmanager.policies.list</code></p>
<p><code>riskmanager.reports.list</code></p>
<p><code>rma.collectors.list</code></p>
<p><code>rma.locations.list</code></p>
<p><code>rma.operations.list</code></p>
<p><code>roads.selectedRoutes.list</code></p>
<p><code>run.configurations.list</code></p>
<p><code>run.executions.list</code></p>
<p><code>run.instances.getIamPolicy</code></p>
<p><code>run.instances.list</code></p>
<p><code>run.jobs.getIamPolicy</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.locations.list</code></p>
<p><code>run.operations.list</code></p>
<p><code>run.revisions.list</code></p>
<p><code>run.routes.list</code></p>
<p><code>run.services.getIamPolicy</code></p>
<p><code>run.services.list</code></p>
<p><code>run.tasks.list</code></p>
<p><code>run.workerpools.getIamPolicy</code></p>
<p><code>run.workerpools.list</code></p>
<p><code>runapps.applications.list</code></p>
<p><code>runapps.deployments.list</code></p>
<p><code>runapps.locations.list</code></p>
<p><code>runapps.operations.list</code></p>
<p><code>runtimeconfig. configs. getIamPolicy</code></p>
<p><code>runtimeconfig.configs.list</code></p>
<p><code>runtimeconfig.operations.list</code></p>
<p><code>runtimeconfig. variables. getIamPolicy</code></p>
<p><code>runtimeconfig.variables.list</code></p>
<p><code>runtimeconfig. waiters. getIamPolicy</code></p>
<p><code>runtimeconfig.waiters.list</code></p>
<p><code>saasservicemgmt. flagAttributes. list</code></p>
<p><code>saasservicemgmt. flagReleases. list</code></p>
<p><code>saasservicemgmt. flagRevisions. list</code></p>
<p><code>saasservicemgmt.flags.list</code></p>
<p><code>saasservicemgmt.locations.list</code></p>
<p><code>saasservicemgmt. operations. list</code></p>
<p><code>saasservicemgmt.poolKinds.list</code></p>
<p><code>saasservicemgmt.pools.list</code></p>
<p><code>saasservicemgmt.releases.list</code></p>
<p><code>saasservicemgmt. rolloutKinds. list</code></p>
<p><code>saasservicemgmt.rollouts.list</code></p>
<p><code>saasservicemgmt.saas.list</code></p>
<p><code>saasservicemgmt. saasReleases. list</code></p>
<p><code>saasservicemgmt. tenantOperations. list</code></p>
<p><code>saasservicemgmt.tenants.list</code></p>
<p><code>saasservicemgmt. unitGroupOperations. list</code></p>
<p><code>saasservicemgmt. unitGroups. list</code></p>
<p><code>saasservicemgmt.unitKinds.list</code></p>
<p><code>saasservicemgmt. unitOperations. list</code></p>
<p><code>saasservicemgmt.units.list</code></p>
<p><code>secretmanager.locations.list</code></p>
<p><code>secretmanager. secrets. getIamPolicy</code></p>
<p><code>secretmanager.secrets.list</code></p>
<p><code>secretmanager.versions.list</code></p>
<p><code>securedlandingzone. overwatches. list</code></p>
<p><code>securesourcemanager. branchRules. list</code></p>
<p><code>securesourcemanager.hooks.list</code></p>
<p><code>securesourcemanager. instances. getIamPolicy</code></p>
<p><code>securesourcemanager. instances. list</code></p>
<p><code>securesourcemanager. issuecomments. list</code></p>
<p><code>securesourcemanager. issues. list</code></p>
<p><code>securesourcemanager. locations. list</code></p>
<p><code>securesourcemanager. operations. list</code></p>
<p><code>securesourcemanager. prcomments. list</code></p>
<p><code>securesourcemanager. pullRequests. list</code></p>
<p><code>securesourcemanager. repositories. getIamPolicy</code></p>
<p><code>securesourcemanager. repositories. list</code></p>
<p><code>securesourcemanager. sshkeys. list</code></p>
<p><code>securitycenter.assets.list</code></p>
<p><code>securitycenter. attackpaths. list</code></p>
<p><code>securitycenter. bigQueryExports. list</code></p>
<p><code>securitycenter. compliancesnapshots. list</code></p>
<p><code>securitycenter. effectivesecurityhealthanalyticscustommodules. list</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>securitycenter.issues.list</code></p>
<p><code>securitycenter. muteconfigs. list</code></p>
<p><code>securitycenter. notificationconfig. list</code></p>
<p><code>securitycenter. resourcevalueconfigs. list</code></p>
<p><code>securitycenter. riskreports. list</code></p>
<p><code>securitycenter. securityhealthanalyticscustommodules. list</code></p>
<p><code>securitycenter. sources. getIamPolicy</code></p>
<p><code>securitycenter.sources.list</code></p>
<p><code>securitycenter. valuedresources. list</code></p>
<p><code>securitycenter. vulnerabilitysnapshots. list</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. locations. list</code></p>
<p><code>securitycentermanagement. operations. list</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securityposture.locations.list</code></p>
<p><code>securityposture. operations. list</code></p>
<p><code>securityposture. postureDeployments. list</code></p>
<p><code>securityposture. postureTemplates. list</code></p>
<p><code>securityposture.postures.list</code></p>
<p><code>securityposture.reports.list</code></p>
<p><code>servicebroker. bindingoperations. list</code></p>
<p><code>servicebroker. bindings. getIamPolicy</code></p>
<p><code>servicebroker.bindings.list</code></p>
<p><code>servicebroker. catalogs. getIamPolicy</code></p>
<p><code>servicebroker.catalogs.list</code></p>
<p><code>servicebroker. instanceoperations. list</code></p>
<p><code>servicebroker. instances. getIamPolicy</code></p>
<p><code>servicebroker.instances.list</code></p>
<p><code>serviceconsumermanagement. tenancyu. list</code></p>
<p><code>servicedirectory. endpoints. getIamPolicy</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory. locations. list</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>serviceextensions. locations. list</code></p>
<p><code>servicehealth.artifacts.list</code></p>
<p><code>servicehealth.events.list</code></p>
<p><code>servicehealth.locations.list</code></p>
<p><code>servicehealth. organizationEvents. list</code></p>
<p><code>servicehealth. organizationImpacts. list</code></p>
<p><code>servicemanagement. services. getIamPolicy</code></p>
<p><code>servicemanagement. services. list</code></p>
<p><code>servicenetworking. operations. list</code></p>
<p><code>servicesecurityinsights. clusterSecurityInfo. list</code></p>
<p><code>servicesecurityinsights. securityInfo. list</code></p>
<p><code>servicesecurityinsights. workloadPolicies. list</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>source.repos.getIamPolicy</code></p>
<p><code>source.repos.list</code></p>
<p><code>spanner.backupOperations.list</code></p>
<p><code>spanner. backupSchedules. getIamPolicy</code></p>
<p><code>spanner.backupSchedules.list</code></p>
<p><code>spanner.backups.getIamPolicy</code></p>
<p><code>spanner.backups.list</code></p>
<p><code>spanner. databaseOperations. list</code></p>
<p><code>spanner.databaseRoles.list</code></p>
<p><code>spanner.databases.getIamPolicy</code></p>
<p><code>spanner.databases.list</code></p>
<p><code>spanner. instanceConfigOperations. list</code></p>
<p><code>spanner.instanceConfigs.list</code></p>
<p><code>spanner. instanceOperations. list</code></p>
<p><code>spanner. instancePartitionOperations. list</code></p>
<p><code>spanner. instancePartitions. list</code></p>
<p><code>spanner.instances.getIamPolicy</code></p>
<p><code>spanner.instances.list</code></p>
<p><code>spanner.sessions.list</code></p>
<p><code>speakerid.phrases.list</code></p>
<p><code>speakerid.speakers.list</code></p>
<p><code>speech.customClasses.list</code></p>
<p><code>speech.locations.list</code></p>
<p><code>speech.operations.list</code></p>
<p><code>speech.phraseSets.list</code></p>
<p><code>speech.recognizers.list</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.list</code></p>
<p><code>storage.bucketOperations.list</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.featureConfigs.list</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.hmacKeys.list</code></p>
<p><code>storage. managedFolders. getIamPolicy</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storagebatchoperations. bucketOperations. list</code></p>
<p><code>storagebatchoperations. jobs. list</code></p>
<p><code>storagebatchoperations. locations. list</code></p>
<p><code>storagebatchoperations. operations. list</code></p>
<p><code>storageinsights. datasetConfigs. list</code></p>
<p><code>storageinsights.locations.list</code></p>
<p><code>storageinsights. operations. list</code></p>
<p><code>storageinsights. reportConfigs. list</code></p>
<p><code>storageinsights. reportDetails. list</code></p>
<p><code>storagetransfer. agentpools. list</code></p>
<p><code>storagetransfer.jobs.list</code></p>
<p><code>storagetransfer. operations. list</code></p>
<p><code>stream.locations.list</code></p>
<p><code>stream.operations.list</code></p>
<p><code>stream.streamContents.list</code></p>
<p><code>stream.streamInstances.list</code></p>
<p><code>telcoautomation. blueprints. list</code></p>
<p><code>telcoautomation. deployments. list</code></p>
<p><code>telcoautomation.edgeSlms.list</code></p>
<p><code>telcoautomation. hydratedDeployments. list</code></p>
<p><code>telcoautomation.locations.list</code></p>
<p><code>telcoautomation. operations. list</code></p>
<p><code>telcoautomation. orchestrationClusters. list</code></p>
<p><code>telcoautomation. publicBlueprints. list</code></p>
<p><code>telemetry. consumers. getIamPolicy</code></p>
<p><code>threatintelligence.alerts.list</code></p>
<p><code>threatintelligence. configurations. list</code></p>
<p><code>threatintelligence. findings. list</code></p>
<p><code>tpu.acceleratortypes.list</code></p>
<p><code>tpu.locations.list</code></p>
<p><code>tpu.nodes.list</code></p>
<p><code>tpu.operations.list</code></p>
<p><code>tpu.runtimeversions.list</code></p>
<p><code>tpu.tensorflowversions.list</code></p>
<p><code>transcoder.jobTemplates.list</code></p>
<p><code>transcoder.jobs.list</code></p>
<p><code>transferappliance. appliances. list</code></p>
<p><code>transferappliance. locations. list</code></p>
<p><code>transferappliance. operations. list</code></p>
<p><code>transferappliance.orders.list</code></p>
<p><code>transferappliance. savedAddresses. list</code></p>
<p><code>translationhub.portals.list</code></p>
<p><code>universalledger.endpoints.list</code></p>
<p><code>universalledger.locations.list</code></p>
<p><code>vectorsearch.collections.list</code></p>
<p><code>vectorsearch.indexes.list</code></p>
<p><code>vectorsearch.locations.list</code></p>
<p><code>vectorsearch.operations.list</code></p>
<p><code>videostitcher.cdnKeys.list</code></p>
<p><code>videostitcher. liveAdTagDetails. list</code></p>
<p><code>videostitcher.liveConfigs.list</code></p>
<p><code>videostitcher.operations.list</code></p>
<p><code>videostitcher.slates.list</code></p>
<p><code>videostitcher. vodAdTagDetails. list</code></p>
<p><code>videostitcher.vodConfigs.list</code></p>
<p><code>videostitcher. vodStitchDetails. list</code></p>
<p><code>visionai.analyses.getIamPolicy</code></p>
<p><code>visionai.analyses.list</code></p>
<p><code>visionai.annotations.list</code></p>
<p><code>visionai.applications.list</code></p>
<p><code>visionai.assets.list</code></p>
<p><code>visionai.clusters.getIamPolicy</code></p>
<p><code>visionai.clusters.list</code></p>
<p><code>visionai.corpora.list</code></p>
<p><code>visionai.dataSchemas.list</code></p>
<p><code>visionai.drafts.list</code></p>
<p><code>visionai.events.getIamPolicy</code></p>
<p><code>visionai.events.list</code></p>
<p><code>visionai.indexEndpoints.list</code></p>
<p><code>visionai.indexes.list</code></p>
<p><code>visionai.instances.list</code></p>
<p><code>visionai.locations.list</code></p>
<p><code>visionai.operations.list</code></p>
<p><code>visionai. operators. getIamPolicy</code></p>
<p><code>visionai.operators.list</code></p>
<p><code>visionai.processors.list</code></p>
<p><code>visionai.searchConfigs.list</code></p>
<p><code>visionai.series.getIamPolicy</code></p>
<p><code>visionai.series.list</code></p>
<p><code>visionai.streams.getIamPolicy</code></p>
<p><code>visionai.streams.list</code></p>
<p><code>visionai.uistreams.list</code></p>
<p><code>visualinspection. annotationSets. list</code></p>
<p><code>visualinspection. annotationSpecs. list</code></p>
<p><code>visualinspection. annotations. list</code></p>
<p><code>visualinspection.datasets.list</code></p>
<p><code>visualinspection.images.list</code></p>
<p><code>visualinspection. locations. list</code></p>
<p><code>visualinspection. modelEvaluations. list</code></p>
<p><code>visualinspection.models.list</code></p>
<p><code>visualinspection.modules.list</code></p>
<p><code>visualinspection. operations. list</code></p>
<p><code>visualinspection. solutionArtifacts. list</code></p>
<p><code>visualinspection. solutions. list</code></p>
<p><code>vmmigration.cloneJobs.list</code></p>
<p><code>vmmigration.cutoverJobs.list</code></p>
<p><code>vmmigration. datacenterConnectors. list</code></p>
<p><code>vmmigration.deployments.list</code></p>
<p><code>vmmigration.groups.list</code></p>
<p><code>vmmigration. imageImportJobs. list</code></p>
<p><code>vmmigration.imageImports.list</code></p>
<p><code>vmmigration.locations.list</code></p>
<p><code>vmmigration.migratingVms.list</code></p>
<p><code>vmmigration.operations.list</code></p>
<p><code>vmmigration. replicationCycles. list</code></p>
<p><code>vmmigration.sources.list</code></p>
<p><code>vmmigration.targets.list</code></p>
<p><code>vmmigration. utilizationReports. list</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine. externalAccessRules. list</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine.locations.list</code></p>
<p><code>vmwareengine. loggingServers. list</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. list</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine.nodeTypes.list</code></p>
<p><code>vmwareengine.nodes.list</code></p>
<p><code>vmwareengine.operations.list</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine.subnets.list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vpcaccess.connectors.list</code></p>
<p><code>vpcaccess.locations.list</code></p>
<p><code>vpcaccess.operations.list</code></p>
<p><code>workflows.callbacks.list</code></p>
<p><code>workflows.executions.list</code></p>
<p><code>workflows.locations.list</code></p>
<p><code>workflows.operations.list</code></p>
<p><code>workflows.stepEntries.list</code></p>
<p><code>workflows.workflows.list</code></p>
<p><code>workloadcertificate. locations. list</code></p>
<p><code>workloadcertificate. operations. list</code></p>
<p><code>workloadcertificate. workloadRegistrations. list</code></p>
<p><code>workloadidentity. locations. list</code></p>
<p><code>workloadidentity. operations. list</code></p>
<p><code>workloadmanager. actuations. list</code></p>
<p><code>workloadmanager. deployments. list</code></p>
<p><code>workloadmanager. discoveredprofiles. list</code></p>
<p><code>workloadmanager. evaluations. list</code></p>
<p><code>workloadmanager. executions. list</code></p>
<p><code>workloadmanager.findings.list</code></p>
<p><code>workloadmanager.locations.list</code></p>
<p><code>workloadmanager. operations. list</code></p>
<p><code>workloadmanager.results.list</code></p>
<p><code>workloadmanager.rules.list</code></p>
<p><code>workloadmanager.workloads.list</code></p>
<p><code>workstations.operations.list</code></p>
<p><code>workstations. workstationClusters. list</code></p>
<p><code>workstations. workstationConfigs. getIamPolicy</code></p>
<p><code>workstations. workstationConfigs. list</code></p>
<p><code>workstations. workstations. getIamPolicy</code></p>
<p><code>workstations.workstations.list</code></p></td>
</tr>
<tr class="odd">
<td>Service Account Admin
<p>( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p>Create and manage service accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code>iam. serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code>iam. serviceAccountApiKeyBindings. create</code></li>
<li><code>iam. serviceAccountApiKeyBindings. delete</code></li>
<li><code>iam. serviceAccountApiKeyBindings. undelete</code></li>
</ul>
<p><code>iam.serviceAccounts.create</code></p>
<p><code>iam. serviceAccounts. createTagBinding</code></p>
<p><code>iam.serviceAccounts.delete</code></p>
<p><code>iam. serviceAccounts. deleteTagBinding</code></p>
<p><code>iam.serviceAccounts.disable</code></p>
<p><code>iam.serviceAccounts.enable</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>iam. serviceAccounts. setIamPolicy</code></p>
<p><code>iam.serviceAccounts.undelete</code></p>
<p><code>iam.serviceAccounts.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Create Service Accounts
<p>( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p>Access to create service accounts.</p></td>
<td><p><code>iam.serviceAccounts.create</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Service Account Key Admin
<p>( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p>Create and manage (and rotate) service account keys.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code>iam.serviceAccountKeys.*</code></p>
<ul>
<li><code>iam.serviceAccountKeys.create</code></li>
<li><code>iam.serviceAccountKeys.delete</code></li>
<li><code>iam.serviceAccountKeys.disable</code></li>
<li><code>iam.serviceAccountKeys.enable</code></li>
<li><code>iam.serviceAccountKeys.get</code></li>
<li><code>iam.serviceAccountKeys.list</code></li>
</ul>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Service Account Token Creator
<p>( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p>Impersonate service accounts (create OAuth2 access tokens, sign blobs or JWTs, etc).</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam. serviceAccounts. implicitDelegation</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>iam.serviceAccounts.signJwt</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Service Account User
<p>( <code>roles/ iam.serviceAccountUser</code> )</p>
<p>Run operations as the service account.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>View Service Accounts
<p>( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p>Read access to service accounts, metadata, and keys.</p></td>
<td><p><code>iam.serviceAccountKeys.get</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Iam Viewer
<p>( <code>roles/ iam.viewer</code> )</p>
<p>Viewer role for iam</p></td>
<td><p><code>iam.accesspolicies.get</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam. accesspolicies. searchPolicyBindings</code></p>
<p><code>iam.denypolicies.get</code></p>
<p><code>iam.denypolicies.list</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. get</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. list</code></p>
<p><code>iam.googleapis. com/oauthClients. get</code></p>
<p><code>iam.googleapis. com/oauthClients. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. get</code></p>
<p><code>iam.googleapis. com/workforcePools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workforcePools. searchPolicyBindings</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>iam.googleapis. com/workspacePools. searchPolicyBindings</code></p>
<p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>iam. principalaccessboundarypolicies. get</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></p>
<p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam.serviceAccountKeys.get</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>iam. workloadIdentityPools. searchPolicyBindings</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Workload Identity User
<p>( <code>roles/ iam.workloadIdentityUser</code> )</p>
<p>Impersonate service accounts from federated workloads.</p></td>
<td><p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>iam.serviceAccounts.list</code></p></td>
</tr>
<tr class="odd">
<td>Access Policy User <sup>Beta</sup>
<p>( <code>roles/ iam.accessPolicyUser</code> )</p>
<p>Access Policies user role, with permissions to view access policies, and to bind and unbind access policies to targets.</p></td>
<td><p><code>iam.accesspolicies.bind</code></p>
<p><code>iam.accesspolicies.get</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam.accesspolicies.unbind</code></p></td>
</tr>
<tr class="even">
<td>Access Policy Viewer <sup>Beta</sup>
<p>( <code>roles/ iam.accessPolicyViewer</code> )</p>
<p>Access Policy Viewer role, with permissions to read access policies and view associated policy bindings.</p></td>
<td><p><code>iam.accesspolicies.get</code></p>
<p><code>iam.accesspolicies.list</code></p>
<p><code>iam. accesspolicies. searchPolicyBindings</code></p></td>
</tr>
<tr class="odd">
<td>Deny Admin
<p>( <code>roles/ iam.denyAdmin</code> )</p>
<p>Deny admin role, with permissions to read and modify deny policies</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>cloudasset.assets.listResource</code></p>
<p><code>iam.denypolicies.*</code></p>
<ul>
<li><code>iam.denypolicies.create</code></li>
<li><code>iam.denypolicies.delete</code></li>
<li><code>iam.denypolicies.get</code></li>
<li><code>iam.denypolicies.list</code></li>
<li><code>iam.denypolicies.update</code></li>
</ul>
<p><code>policyanalyzer. resourceAuthorizationActivities. query</code></p>
<p><code>policysimulator. accessPolicySimulationResults. list</code></p>
<p><code>policysimulator. accessPolicySimulations.*</code></p>
<ul>
<li><code>policysimulator. accessPolicySimulations. create</code></li>
<li><code>policysimulator. accessPolicySimulations. get</code></li>
<li><code>policysimulator. accessPolicySimulations. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Deny Reviewer
<p>( <code>roles/ iam.denyReviewer</code> )</p>
<p>Deny Reviewer role, with permissions to read deny policies</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>iam.denypolicies.get</code></p>
<p><code>iam.denypolicies.list</code></p></td>
</tr>
<tr class="odd">
<td>IAM OAuth Client Admin
<p>( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p>Full rights to create and manage OAuth clients.</p></td>
<td><p><code>iam.oauthClientCredentials.*</code></p>
<ul>
<li><code>iam.googleapis. com/oauthClientCredentials. create</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. delete</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. get</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. list</code></li>
<li><code>iam.googleapis. com/oauthClientCredentials. update</code></li>
</ul>
<p><code>iam.oauthClients.*</code></p>
<ul>
<li><code>iam.googleapis. com/oauthClients. create</code></li>
<li><code>iam.googleapis. com/oauthClients. delete</code></li>
<li><code>iam.googleapis. com/oauthClients. get</code></li>
<li><code>iam.googleapis. com/oauthClients. list</code></li>
<li><code>iam.googleapis. com/oauthClients. undelete</code></li>
<li><code>iam.googleapis. com/oauthClients. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>IAM OAuth Client Viewer
<p>( <code>roles/ iam.oauthClientViewer</code> )</p>
<p>Read access to a particular instance of an OAuth client.</p></td>
<td><p><code>iam.googleapis. com/oauthClientCredentials. get</code></p>
<p><code>iam.googleapis. com/oauthClientCredentials. list</code></p>
<p><code>iam.googleapis. com/oauthClients. get</code></p>
<p><code>iam.googleapis. com/oauthClients. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>IAM Operation Viewer
<p>( <code>roles/ iam.operationViewer</code> )</p>
<p>Operation user role, with permissions to view and list operations in IAM v3</p></td>
<td><p><code>iam.operations.get</code></p></td>
</tr>
<tr class="even">
<td>Organization Role Administrator
<p>( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p>Provides access to administer all custom roles in the organization and the projects below it.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>iam.roles.*</code></p>
<ul>
<li><code>iam.roles.create</code></li>
<li><code>iam.roles.createTagBinding</code></li>
<li><code>iam.roles.delete</code></li>
<li><code>iam.roles.deleteTagBinding</code></li>
<li><code>iam.roles.get</code></li>
<li><code>iam.roles.list</code></li>
<li><code>iam.roles.listEffectiveTags</code></li>
<li><code>iam.roles.listTagBindings</code></li>
<li><code>iam.roles.undelete</code></li>
<li><code>iam.roles.update</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Organization Role Viewer
<p>( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p>Provides read access to all custom roles in the organization and the projects below it.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>iam.roles.get</code></p>
<p><code>iam.roles.list</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Principal Access Boundary Policy Admin
<p>( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p>Full management of Principal Access Boundary policies and their bindings to principal sets, including the ability to simulate policy impacts.</p></td>
<td><p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>iam. principalaccessboundarypolicies.*</code></p>
<ul>
<li><code>iam. principalaccessboundarypolicies. bind</code></li>
<li><code>iam. principalaccessboundarypolicies. create</code></li>
<li><code>iam. principalaccessboundarypolicies. delete</code></li>
<li><code>iam. principalaccessboundarypolicies. get</code></li>
<li><code>iam. principalaccessboundarypolicies. list</code></li>
<li><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></li>
<li><code>iam. principalaccessboundarypolicies. unbind</code></li>
<li><code>iam. principalaccessboundarypolicies. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Principal Access Boundary Policy User
<p>( <code>roles/ iam.principalAccessBoundaryUser</code> )</p>
<p>View Principal Access Boundary policies and manage policy bindings to associate them with principal sets.</p></td>
<td><p><code>iam. principalaccessboundarypolicies. bind</code></p>
<p><code>iam. principalaccessboundarypolicies. get</code></p>
<p><code>iam. principalaccessboundarypolicies. list</code></p>
<p><code>iam. principalaccessboundarypolicies. unbind</code></p></td>
</tr>
<tr class="even">
<td>SCIM Data Syncer
<p>( <code>roles/ iam.scimSyncer</code> )</p>
<p>Rights to sync users and groups from external identity providers.</p></td>
<td><p><code>iam. workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. put</code></li>
</ul>
<p><code>iam. workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. put</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Service Account API Key Binding Admin
<p>( <code>roles/ iam.serviceAccountApiKeyBindingAdmin</code> )</p>
<p>Create and delete service account API Key bindings</p></td>
<td><p><code>iam. serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code>iam. serviceAccountApiKeyBindings. create</code></li>
<li><code>iam. serviceAccountApiKeyBindings. delete</code></li>
<li><code>iam. serviceAccountApiKeyBindings. undelete</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Delete Service Accounts
<p>( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p>Access to delete service accounts.</p></td>
<td><p><code>iam.serviceAccounts.delete</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Service Account OpenID Connect Identity Token Creator
<p>( <code>roles/ iam.serviceAccountOpenIdTokenCreator</code> )</p>
<p>Create OpenID Connect (OIDC) identity tokens</p></td>
<td><p><code>iam. serviceAccounts. getOpenIdToken</code></p></td>
</tr>
<tr class="even">
<td>IAM Workforce Pool Admin
<p>( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p>Full rights to create and manage all workforce pools in the org, along with the ability to delegate permissions to other admins.</p></td>
<td><p><code>iam. workforcePoolProviderKeys.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderKeys. undelete</code></li>
</ul>
<p><code>iam. workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimGroups. put</code></li>
</ul>
<p><code>iam. workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. patch</code></li>
<li><code>iam.googleapis. com/workforcePoolProviderScimUsers. put</code></li>
</ul>
<p><code>iam.workforcePoolProviders.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. undelete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. update</code></li>
</ul>
<p><code>iam.workforcePoolSubjects.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolSubjects. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolSubjects. revokeSessions</code></li>
<li><code>iam.googleapis. com/workforcePoolSubjects. undelete</code></li>
</ul>
<p><code>iam.workforcePools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePools. create</code></li>
<li><code>iam.googleapis. com/workforcePools. createPolicyBinding</code></li>
<li><code>iam.googleapis. com/workforcePools. delete</code></li>
<li><code>iam.googleapis. com/workforcePools. deletePolicyBinding</code></li>
<li><code>iam.googleapis. com/workforcePools. get</code></li>
<li><code>iam.googleapis. com/workforcePools. getIamPolicy</code></li>
<li><code>iam.googleapis. com/workforcePools. list</code></li>
<li><code>iam.googleapis. com/workforcePools. searchPolicyBindings</code></li>
<li><code>iam.googleapis. com/workforcePools. setIamPolicy</code></li>
<li><code>iam.googleapis. com/workforcePools. undelete</code></li>
<li><code>iam.googleapis. com/workforcePools. update</code></li>
<li><code>iam.googleapis. com/workforcePools. updatePolicyBinding</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>IAM Workforce Pool Editor
<p>( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p>Gives permission to edit workforce pools.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Workforce pool</li>
</ul></td>
<td><p><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePools. get</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p>
<p><code>iam.googleapis. com/workforcePools. update</code></p>
<p><code>iam.workforcePoolProviders.*</code></p>
<ul>
<li><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. create</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. delete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. get</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. list</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. undelete</code></li>
<li><code>iam.googleapis. com/workforcePoolProviders. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>IAM Workforce Pool Viewer
<p>( <code>roles/ iam.workforcePoolViewer</code> )</p>
<p>Rights to read workforce pool.</p></td>
<td><p><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. get</code></p>
<p><code>iam.googleapis. com/workforcePoolProviders. list</code></p>
<p><code>iam.googleapis. com/workforcePools. get</code></p>
<p><code>iam.googleapis. com/workforcePools. list</code></p></td>
</tr>
<tr class="odd">
<td>IAM Workload Identity Pool Admin <sup>Beta</sup>
<p>( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p>Full rights to create and manage workload identity pools.</p></td>
<td><p><code>iam. workloadIdentityPoolManagedIdentities.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. setAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. update</code></li>
</ul>
<p><code>iam. workloadIdentityPoolNamespaces.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolNamespaces. update</code></li>
</ul>
<p><code>iam. workloadIdentityPoolProviderKeys.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. undelete</code></li>
</ul>
<p><code>iam. workloadIdentityPoolProviders.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPoolProviders. update</code></li>
</ul>
<p><code>iam.workloadIdentityPools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workloadIdentityPools. create</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. delete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. get</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. list</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. setAttestationRules</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. setIamPolicy</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. undelete</code></li>
<li><code>iam.googleapis. com/workloadIdentityPools. update</code></li>
<li><code>iam. workloadIdentityPools. createPolicyBinding</code></li>
<li><code>iam. workloadIdentityPools. deletePolicyBinding</code></li>
<li><code>iam. workloadIdentityPools. searchPolicyBindings</code></li>
<li><code>iam. workloadIdentityPools. updatePolicyBinding</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>IAM Workload Identity Pool Viewer <sup>Beta</sup>
<p>( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p>
<p>Read access to workload identity pools.</p></td>
<td><p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. get</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></p>
<p><code>iam.googleapis. com/workloadIdentityPools. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Workspace Pool IAM Admin
<p>( <code>roles/ iam.workspacePoolAdmin</code> )</p>
<p>IAM workspace pool admin able to bind IAM policies to Dasher accounts.</p></td>
<td><p><code>iam.workspacePools.*</code></p>
<ul>
<li><code>iam.googleapis. com/workspacePools. createPolicyBinding</code></li>
<li><code>iam.googleapis. com/workspacePools. deletePolicyBinding</code></li>
<li><code>iam.googleapis. com/workspacePools. searchPolicyBindings</code></li>
<li><code>iam.googleapis. com/workspacePools. updatePolicyBinding</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Identity and Access Management permissions

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
<td><code>iam.accesspolicies.bind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code>roles/ iam.accessPolicyUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.accesspolicies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.accesspolicies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.accesspolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code>roles/ iam.accessPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code>roles/ iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.accesspolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code>roles/ iam.accessPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code>roles/ iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. accesspolicies. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code>roles/ iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.accesspolicies.unbind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code>roles/ iam.accessPolicyUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.accesspolicies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code>roles/ iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.denypolicies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code>roles/ iam.denyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.denypolicies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code>roles/ iam.denyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.denypolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code>roles/ iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyReviewer">Deny Reviewer</a> ( <code>roles/ iam.denyReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam.denypolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code>roles/ iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyReviewer">Deny Reviewer</a> ( <code>roles/ iam.denyReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
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
<td><code>iam.denypolicies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code>roles/ iam.denyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClientCredentials. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/oauthClientCredentials. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClientCredentials. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/oauthClientCredentials. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClientCredentials. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/oauthClients. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClients. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/oauthClients. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClients. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/oauthClients. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/oauthClients. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderKeys. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderKeys. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderKeys. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderKeys. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderKeys. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. patch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimGroups. put</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. patch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviderScimUsers. put</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code>roles/ iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviders. computeUserAttributes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviders. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviders. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviders. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviders. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolProviders. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolProviders. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolSubjects. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePoolSubjects. revokeSessions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePoolSubjects. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code>roles/ iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workforcePools. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code>roles/ iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workforcePools. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code>roles/ iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. getAttestationRules</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. setAttestationRules</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolManagedIdentities. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolNamespaces. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviderKeys. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p>
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
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPoolProviders. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPools. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPools. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPools. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPools. getAttestationRules</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPools. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPools. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p>
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
<td><code>iam.googleapis. com/workloadIdentityPools. setAttestationRules</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPools. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workloadIdentityPools. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workloadIdentityPools. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workspacePools. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code>roles/ iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workspacePools. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code>roles/ iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.googleapis. com/workspacePools. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code>roles/ iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.googleapis. com/workspacePools. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code>roles/ iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer">IAM Operation Viewer</a> ( <code>roles/ iam.operationViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.policybindings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.policybindings.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. principalaccessboundarypolicies. bind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code>roles/ iam.principalAccessBoundaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. principalaccessboundarypolicies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. principalaccessboundarypolicies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. principalaccessboundarypolicies. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code>roles/ iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code>roles/ iam.principalAccessBoundaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. principalaccessboundarypolicies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code>roles/ iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code>roles/ iam.principalAccessBoundaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. principalaccessboundarypolicies. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code>roles/ iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. principalaccessboundarypolicies. unbind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code>roles/ iam.principalAccessBoundaryUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. principalaccessboundarypolicies. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code>roles/ iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.roles.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.roles.createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.roles.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.roles.deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.roles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.orgServiceAgent">Chronicle Organization Service Agent</a> ( <code>roles/ chronicle.orgServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code>roles/ privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code>roles/ privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.roles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam.roles.listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.roles.listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.roles.undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.roles.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccountApiKeyBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code>roles/ iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccountApiKeyBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code>roles/ iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccountApiKeyBindings. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code>roles/ iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccountKeys.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccountKeys.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccountKeys.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccountKeys.enable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccountKeys.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccountKeys.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccounts.actAs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code>roles/ iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabServiceAgent">Vertex AI Colab Service Agent</a> ( <code>roles/ aiplatform.colabServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code>roles/ compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code>roles/ configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code>roles/ gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code>roles/ krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code>roles/ osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code>roles/ securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccounts. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccounts. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccounts.enable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code>roles/ iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code>roles/ iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code>roles/ apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code>roles/ workflows.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccounts. getAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code>roles/ iam.workloadIdentityUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code>roles/ aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code>roles/ apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery#bigquerycontinuousquery.serviceAgent">BigQuery Continuous Query Service Agent</a> ( <code>roles/ bigquerycontinuousquery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark#bigqueryspark.serviceAgent">BigQuery Spark Service Agent</a> ( <code>roles/ bigqueryspark.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code>roles/ cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code>roles/ clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a> ( <code>roles/ cloudscheduler.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a> ( <code>roles/ cloudtasks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#sourcerepo.serviceAgent">Cloud Source Repositories Service Agent</a> ( <code>roles/ sourcerepo.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code>roles/ workflows.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccounts. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.ServiceAgentV2Ext">Cloud Composer v2 API Service Agent Extension</a> ( <code>roles/ composer.ServiceAgentV2Ext</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccounts. getOpenIdToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code>roles/ iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountOpenIdTokenCreator">Service Account OpenID Connect Identity Token Creator</a> ( <code>roles/ iam.serviceAccountOpenIdTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code>roles/ aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code>roles/ apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a> ( <code>roles/ cloudscheduler.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a> ( <code>roles/ cloudtasks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code>roles/ workflows.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccounts. implicitDelegation</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccounts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code>roles/ cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code>roles/ iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code>roles/ iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccounts. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. serviceAccounts. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. serviceAccounts. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.ServiceAgentV2Ext">Cloud Composer v2 API Service Agent Extension</a> ( <code>roles/ composer.ServiceAgentV2Ext</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccounts.signBlob</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code>roles/ appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.signJwt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a> ( <code>roles/ securesourcemanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam.serviceAccounts.undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam.serviceAccounts.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>iam. workloadIdentityPools. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. workloadIdentityPools. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>iam. workloadIdentityPools. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>iam. workloadIdentityPools. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
</tbody>
</table>
