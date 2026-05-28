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
<td><h4 id="iam.accessPolicyAdmin" class="role-title add-link" data-text="Access Policy Admin Beta" tabindex="-1">Access Policy Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p>Access Policy admin role, with permissions to read and modify access policies, and to bind and unbind access policies to targets.</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.accesspolicies.bind</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.create</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.delete</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.get</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.list</code></li>
<li><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.unbind</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.admin" class="role-title add-link" data-text="Iam Admin" tabindex="-1">Iam Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p>Admin role for iam</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.accesspolicies.bind</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.create</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.delete</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.get</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.list</code></li>
<li><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.unbind</code></li>
<li><code dir="ltr" translate="no">iam.accesspolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.oauthClientCredentials.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.oauthClients.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.operations.get</code></p>
<p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.roles.create</code></li>
<li><code dir="ltr" translate="no">iam.roles.createTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.delete</code></li>
<li><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.get</code></li>
<li><code dir="ltr" translate="no">iam.roles.list</code></li>
<li><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">iam.roles.listTagBindings</code></li>
<li><code dir="ltr" translate="no">iam.roles.undelete</code></li>
<li><code dir="ltr" translate="no">iam.roles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  create</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  delete</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.create</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.delete</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.disable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.enable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.disable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.enable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.undelete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.update</code></p>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  put</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  put</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePoolProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePoolSubjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  update</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolManagedIdentities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  setAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolNamespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolProviderKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workloadIdentityPools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  update</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workspacePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.editor" class="role-title add-link" data-text="Iam Editor" tabindex="-1">Iam Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p>Editor role for iam</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  create</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  delete</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.create</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.delete</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.disable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.enable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.disable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.enable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.update</code></p>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalAccessBoundaryViewer" class="role-title add-link" data-text="Principal Access Boundary Policy Viewer" tabindex="-1">Principal Access Boundary Policy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.principalAccessBoundaryViewer</code> )</p>
<p>Principal Access Boundary Reviewer role, with permissions to read principal access boundary policies and view associated policy bindings</p></td>
<td><p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roleAdmin" class="role-title add-link" data-text="Role Administrator" tabindex="-1">Role Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p>Provides access to all custom roles in the project. This role can only be granted at the project level.</p></td>
<td><p><code dir="ltr" translate="no">iam.roles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.roles.create</code></li>
<li><code dir="ltr" translate="no">iam.roles.createTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.delete</code></li>
<li><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.get</code></li>
<li><code dir="ltr" translate="no">iam.roles.list</code></li>
<li><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">iam.roles.listTagBindings</code></li>
<li><code dir="ltr" translate="no">iam.roles.undelete</code></li>
<li><code dir="ltr" translate="no">iam.roles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.roleViewer" class="role-title add-link" data-text="Role Viewer" tabindex="-1">Role Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p>Provides read access to all custom roles in the project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.securityAdmin" class="role-title add-link" data-text="Security Admin" tabindex="-1">Security Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p>Security admin role, with permissions to get and set any IAM policy.</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">actions.agentVersions.list</code></p>
<p><code dir="ltr" translate="no">advisorynotifications.  notifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  get</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.agents.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.endpoints.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.locations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.services.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agentExamples.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  datasetVersions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  endpoints.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  entityTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  entityTypes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationItems.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitors.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featurestores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featurestores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  humanInTheLoops.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  memoryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  metadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  nasTrialDetails.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.operations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessionEvents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardRuns.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.locations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></p>
<p><code dir="ltr" translate="no">alloydb.users.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigateway.  apiconfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.apiconfigs.list</code></p>
<p><code dir="ltr" translate="no">apigateway.  apiconfigs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.apis.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.apis.list</code></p>
<p><code dir="ltr" translate="no">apigateway.apis.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.gateways.list</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.locations.list</code></p>
<p><code dir="ltr" translate="no">apigateway.operations.list</code></p>
<p><code dir="ltr" translate="no">apigee.  apiproductattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.apiproducts.list</code></p>
<p><code dir="ltr" translate="no">apigee.appgroupapps.list</code></p>
<p><code dir="ltr" translate="no">apigee.appgroups.list</code></p>
<p><code dir="ltr" translate="no">apigee.  appgroupsubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.apps.list</code></p>
<p><code dir="ltr" translate="no">apigee.archivedeployments.list</code></p>
<p><code dir="ltr" translate="no">apigee.caches.list</code></p>
<p><code dir="ltr" translate="no">apigee.datacollectors.list</code></p>
<p><code dir="ltr" translate="no">apigee.datastores.list</code></p>
<p><code dir="ltr" translate="no">apigee.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.deployments.list</code></p>
<p><code dir="ltr" translate="no">apigee.  deployments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.  developerappattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.developerapps.list</code></p>
<p><code dir="ltr" translate="no">apigee.  developerattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.developers.list</code></p>
<p><code dir="ltr" translate="no">apigee.  developersubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.dnsZones.list</code></p>
<p><code dir="ltr" translate="no">apigee.  endpointattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.  envgroupattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.envgroups.list</code></p>
<p><code dir="ltr" translate="no">apigee.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.environments.list</code></p>
<p><code dir="ltr" translate="no">apigee.  environments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.exports.list</code></p>
<p><code dir="ltr" translate="no">apigee.flowhooks.list</code></p>
<p><code dir="ltr" translate="no">apigee.hostqueries.list</code></p>
<p><code dir="ltr" translate="no">apigee.  hostsecurityreports.  list</code></p>
<p><code dir="ltr" translate="no">apigee.  instanceattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.instances.list</code></p>
<p><code dir="ltr" translate="no">apigee.keystorealiases.list</code></p>
<p><code dir="ltr" translate="no">apigee.keystores.list</code></p>
<p><code dir="ltr" translate="no">apigee.keyvaluemapentries.list</code></p>
<p><code dir="ltr" translate="no">apigee.keyvaluemaps.list</code></p>
<p><code dir="ltr" translate="no">apigee.nataddresses.list</code></p>
<p><code dir="ltr" translate="no">apigee.operations.list</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.list</code></p>
<p><code dir="ltr" translate="no">apigee.portals.list</code></p>
<p><code dir="ltr" translate="no">apigee.proxies.list</code></p>
<p><code dir="ltr" translate="no">apigee.proxyrevisions.list</code></p>
<p><code dir="ltr" translate="no">apigee.queries.list</code></p>
<p><code dir="ltr" translate="no">apigee.rateplans.list</code></p>
<p><code dir="ltr" translate="no">apigee.references.list</code></p>
<p><code dir="ltr" translate="no">apigee.reports.list</code></p>
<p><code dir="ltr" translate="no">apigee.resourcefiles.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityActions.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityFeedback.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityIncidents.list</code></p>
<p><code dir="ltr" translate="no">apigee.  securityMonitoringConditions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.securityProfiles.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityProfilesV2.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityreports.list</code></p>
<p><code dir="ltr" translate="no">apigee.  sharedflowrevisions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.sharedflows.list</code></p>
<p><code dir="ltr" translate="no">apigee.spaces.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.spaces.list</code></p>
<p><code dir="ltr" translate="no">apigee.spaces.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.targetservers.list</code></p>
<p><code dir="ltr" translate="no">apigee.  traceconfigoverrides.  list</code></p>
<p><code dir="ltr" translate="no">apigee.tracesessions.list</code></p>
<p><code dir="ltr" translate="no">apigeeconnect.connections.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  apis.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.apis.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  apis.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  artifacts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.artifacts.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  artifacts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.locations.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  specs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.specs.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  specs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  versions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  versions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apihub.addons.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.list</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.list</code></p>
<p><code dir="ltr" translate="no">apihub.curations.list</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.list</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.list</code></p>
<p><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.externalApis.list</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.llmEnablements.list</code></p>
<p><code dir="ltr" translate="no">apihub.operations.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.list</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.list</code></p>
<p><code dir="ltr" translate="no">apihub.versions.list</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">apim.apiObservations.list</code></p>
<p><code dir="ltr" translate="no">apim.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apim.locations.list</code></p>
<p><code dir="ltr" translate="no">apim.observationJobs.list</code></p>
<p><code dir="ltr" translate="no">apim.observationSources.list</code></p>
<p><code dir="ltr" translate="no">apim.operations.list</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.list</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">apphub.  applications.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apphub.applications.list</code></p>
<p><code dir="ltr" translate="no">apphub.  applications.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.list</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></p>
<p><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">apphub.locations.list</code></p>
<p><code dir="ltr" translate="no">apphub.operations.list</code></p>
<p><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apphub.services.list</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.list</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></p>
<p><code dir="ltr" translate="no">appoptimize.locations.list</code></p>
<p><code dir="ltr" translate="no">appoptimize.operations.list</code></p>
<p><code dir="ltr" translate="no">appoptimize.reports.list</code></p>
<p><code dir="ltr" translate="no">apptopology.domains.list</code></p>
<p><code dir="ltr" translate="no">apptopology.locations.list</code></p>
<p><code dir="ltr" translate="no">apptopology.operations.list</code></p>
<p><code dir="ltr" translate="no">apptopology.topologyViews.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.locations.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.metadata.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.operations.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.updates.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.auditReports.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.controls.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.findings.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.annotations.list</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.examples.list</code></p>
<p><code dir="ltr" translate="no">automl.files.list</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></p>
<p><code dir="ltr" translate="no">automl.locations.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.locations.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.list</code></p>
<p><code dir="ltr" translate="no">automl.models.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.models.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.operations.list</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">batch.jobs.list</code></p>
<p><code dir="ltr" translate="no">batch.locations.list</code></p>
<p><code dir="ltr" translate="no">batch.operations.list</code></p>
<p><code dir="ltr" translate="no">batch.resourceAllowances.list</code></p>
<p><code dir="ltr" translate="no">batch.tasks.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appConnections.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appConnectors.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appGateways.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.locations.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.operations.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  securityGateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  securityGateways.  list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  securityGateways.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  sgApplications.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.sgApplications.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  sgApplications.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.list</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.databases.list</code></p>
<p><code dir="ltr" translate="no">biglake.locks.list</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.list</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  connections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></p>
<p><code dir="ltr" translate="no">bigtable.appProfiles.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.authorizedViews.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.backups.list</code></p>
<p><code dir="ltr" translate="no">bigtable.backups.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.clusters.list</code></p>
<p><code dir="ltr" translate="no">bigtable.hotTablets.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.keyvisualizer.list</code></p>
<p><code dir="ltr" translate="no">bigtable.locations.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  logicalViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.logicalViews.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  logicalViews.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.  materializedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.  materializedViews.  list</code></p>
<p><code dir="ltr" translate="no">bigtable.  materializedViews.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.memoryLayers.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  schemaBundles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.schemaBundles.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  schemaBundles.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.list</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.accounts.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></p>
<p><code dir="ltr" translate="no">billing.budgets.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  list</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  locations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  operations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  capacityPlans.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.forecasts.list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  planAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageHistories.  list</code></p>
<p><code dir="ltr" translate="no">carestudio.patients.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  observedcerts.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  list</code></p>
<p><code dir="ltr" translate="no">ces.agents.list</code></p>
<p><code dir="ltr" translate="no">ces.appVersions.list</code></p>
<p><code dir="ltr" translate="no">ces.apps.list</code></p>
<p><code dir="ltr" translate="no">ces.assistantSessions.list</code></p>
<p><code dir="ltr" translate="no">ces.changelogs.list</code></p>
<p><code dir="ltr" translate="no">ces.conversations.list</code></p>
<p><code dir="ltr" translate="no">ces.deployments.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationDatasets.list</code></p>
<p><code dir="ltr" translate="no">ces.  evaluationExpectations.  list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationResults.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluations.list</code></p>
<p><code dir="ltr" translate="no">ces.examples.list</code></p>
<p><code dir="ltr" translate="no">ces.guardrails.list</code></p>
<p><code dir="ltr" translate="no">ces.locations.list</code></p>
<p><code dir="ltr" translate="no">ces.operations.list</code></p>
<p><code dir="ltr" translate="no">ces.tools.list</code></p>
<p><code dir="ltr" translate="no">ces.toolsets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.analyticValues.list</code></p>
<p><code dir="ltr" translate="no">chronicle.analytics.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  chatSessionMessages.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.chatSessions.list</code></p>
<p><code dir="ltr" translate="no">chronicle.collectors.list</code></p>
<p><code dir="ltr" translate="no">chronicle.conversations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.coverageDetails.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  curatedRuleSetCategories.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  curatedRuleSetDeployments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.curatedRuleSets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.curatedRules.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dashboardCharts.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dashboardQueries.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dashboardScheduledReports.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.dashboards.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dataAccessLabels.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dataAccessScopes.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataExports.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTableRows.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTables.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTaps.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  enrichmentControls.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.entities.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  extensionValidationReports.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentNativeDashboards.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentRules.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentSearchQueries.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.features.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  federationGroups.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.feedPacks.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  feedSourceTypeSchemas.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.feeds.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  findingsRefinementDeployments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  findingsRefinements.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.forwarders.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ingestionLogLabels.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ingestionLogNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  investigationComments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  investigationSteps.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.investigations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.iocMatches.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  labsExperimentExecutions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.labsExperiments.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  logProcessingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypeSchemas.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypeSettings.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypes.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logs.list</code></p>
<p><code dir="ltr" translate="no">chronicle.messages.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  nativeDashboards.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.notebooks.list</code></p>
<p><code dir="ltr" translate="no">chronicle.operations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  parserExtensions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.parsers.list</code></p>
<p><code dir="ltr" translate="no">chronicle.parsingErrors.list</code></p>
<p><code dir="ltr" translate="no">chronicle.referenceLists.list</code></p>
<p><code dir="ltr" translate="no">chronicle.retrohunts.list</code></p>
<p><code dir="ltr" translate="no">chronicle.ruleDeployments.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ruleExecutionErrors.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.rules.list</code></p>
<p><code dir="ltr" translate="no">chronicle.savedColumnSets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.searchQueries.list</code></p>
<p><code dir="ltr" translate="no">chronicle.searchedResults.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  sharedPreferenceSets.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.summaryTables.list</code></p>
<p><code dir="ltr" translate="no">chronicle.tenants.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  threatCollections.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  transformerDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  validationErrors.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.watchlists.list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloud.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  aiDevToolsSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  codeRepositoryIndexes.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  codeToolsSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  dataSharingWithGoogleSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  geminiGcpEnablementSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  loggingSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  releaseChannelSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  repositoryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  repositoryGroups.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  repositoryGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  topics.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  topics.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  list</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.mcpTools.list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudbuild.connections.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.  connections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudbuild.integrations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.repositories.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.workerpools.list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.debuggees.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.operations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  importJobs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  importJobs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  protectableResources.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.retiredResources.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  list</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  realms.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.list</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controlComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findingSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findings.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  crawledurls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  results.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.  accounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudsupport.accounts.list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.  accounts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.insights.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.tasks.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.traces.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/ipRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/regions.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/serviceLevels.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  collectionRequestApprovals.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  collections.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  populateCollectionJobs.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  services.  list</code></p>
<p><code dir="ltr" translate="no">commerceprice.events.list</code></p>
<p><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  analyticsHubListingProductConfigs.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  locations.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.products.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.releases.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.services.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  skuGroups.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.skus.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  standardOffers.  list</code></p>
<p><code dir="ltr" translate="no">composer.dags.list</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.commitments.list</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  list</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalOperations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.hosts.list</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.images.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.images.list</code></p>
<p><code dir="ltr" translate="no">compute.images.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenseCodes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.licenses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.multiMig.list</code></p>
<p><code dir="ltr" translate="no">compute.multiMigMembers.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  nodeGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  nodeGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  nodeTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.  nodeTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.orgRolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.orgRollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.previewFeatures.list</code></p>
<p><code dir="ltr" translate="no">compute.  publicAdvertisedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionOperations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationSlots.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.rolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.rollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  snapshotGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  vmExtensionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  zoneOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  zoneOperations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></p>
<p><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.list</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.locations.list</code></p>
<p><code dir="ltr" translate="no">config.operations.list</code></p>
<p><code dir="ltr" translate="no">config.previews.list</code></p>
<p><code dir="ltr" translate="no">config.resourcechanges.list</code></p>
<p><code dir="ltr" translate="no">config.resourcedrifts.list</code></p>
<p><code dir="ltr" translate="no">config.resources.list</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">config.terraformversions.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.locations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.operations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.list</code></p>
<p><code dir="ltr" translate="no">connectors.actions.list</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.connections.list</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.entities.list</code></p>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.eventtypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.locations.list</code></p>
<p><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.managedZones.list</code></p>
<p><code dir="ltr" translate="no">connectors.  managedZones.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.operations.list</code></p>
<p><code dir="ltr" translate="no">connectors.providers.list</code></p>
<p><code dir="ltr" translate="no">connectors.versions.list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  analyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  analysisRules.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  assessmentRules.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  assessments.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedAnalyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedAssessments.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedConversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedFeedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedNotes.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedOperations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViewSets.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViews.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViews.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  conversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetAnalyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetConversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetFeedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveries.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryResults.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryWorkspaces.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  faqEntries.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  faqModels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  feedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  issueModels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  issues.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  notes.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  phraseMatchers.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaQuestionTags.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaQuestions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaScorecardRevisions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaScorecards.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  views.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  visibilityLabels.  list</code></p>
<p><code dir="ltr" translate="no">container.apiServices.list</code></p>
<p><code dir="ltr" translate="no">container.auditSinks.list</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.bindings.list</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.  componentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">container.configMaps.list</code></p>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.list</code></p>
<p><code dir="ltr" translate="no">container.csiDrivers.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodeInfos.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodes.list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.list</code></p>
<p><code dir="ltr" translate="no">container.deployments.list</code></p>
<p><code dir="ltr" translate="no">container.endpointSlices.list</code></p>
<p><code dir="ltr" translate="no">container.endpoints.list</code></p>
<p><code dir="ltr" translate="no">container.events.list</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></p>
<p><code dir="ltr" translate="no">container.ingresses.list</code></p>
<p><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.jobs.list</code></p>
<p><code dir="ltr" translate="no">container.leases.list</code></p>
<p><code dir="ltr" translate="no">container.limitRanges.list</code></p>
<p><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  list</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.namespaces.list</code></p>
<p><code dir="ltr" translate="no">container.networkPolicies.list</code></p>
<p><code dir="ltr" translate="no">container.nodes.list</code></p>
<p><code dir="ltr" translate="no">container.operations.list</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></p>
<p><code dir="ltr" translate="no">container.petSets.list</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></p>
<p><code dir="ltr" translate="no">container.podPresets.list</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">container.podTemplates.list</code></p>
<p><code dir="ltr" translate="no">container.pods.list</code></p>
<p><code dir="ltr" translate="no">container.priorityClasses.list</code></p>
<p><code dir="ltr" translate="no">container.replicaSets.list</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  list</code></p>
<p><code dir="ltr" translate="no">container.resourceQuotas.list</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.list</code></p>
<p><code dir="ltr" translate="no">container.roles.list</code></p>
<p><code dir="ltr" translate="no">container.runtimeClasses.list</code></p>
<p><code dir="ltr" translate="no">container.scheduledJobs.list</code></p>
<p><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">container.services.list</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.list</code></p>
<p><code dir="ltr" translate="no">container.storageClasses.list</code></p>
<p><code dir="ltr" translate="no">container.storageStates.list</code></p>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></p>
<p><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></p>
<p><code dir="ltr" translate="no">container.updateInfos.list</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></p>
<p><code dir="ltr" translate="no">container.volumeSnapshots.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">containersecurity.  clusterSummaries.  list</code></p>
<p><code dir="ltr" translate="no">containersecurity.  findings.  list</code></p>
<p><code dir="ltr" translate="no">containersecurity.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.corpora.list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.ruleSets.list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  databaseGroups.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  fleetHealthStats.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  fleetInsights.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.fleetStats.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.locations.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.products.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.queryStats.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.userLabels.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.userTags.list</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  operations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.operations.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  taxonomies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.locations.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.operations.list</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.list</code></p>
<p><code dir="ltr" translate="no">dataform.commentThreads.list</code></p>
<p><code dir="ltr" translate="no">dataform.comments.list</code></p>
<p><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.folders.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.locations.list</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.artifacts.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.locations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.list</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.list</code></p>
<p><code dir="ltr" translate="no">datafusion.secureKeys.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.dataitems.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.datasets.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.examples.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.instructions.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.operations.list</code></p>
<p><code dir="ltr" translate="no">datalineage.events.list</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.list</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.locations.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  mappingrules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  mappingrules.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.objects.list</code></p>
<p><code dir="ltr" translate="no">datamigration.operations.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datapipelines.jobs.list</code></p>
<p><code dir="ltr" translate="no">datapipelines.pipelines.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assetActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.content.list</code></p>
<p><code dir="ltr" translate="no">dataplex.content.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.encryptionConfig.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entities.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  environments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakeActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.locations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.partitions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.zoneActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.agents.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  list</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.list</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.list</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.  operations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  operations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.sessionTemplates.list</code></p>
<p><code dir="ltr" translate="no">dataproc.sessions.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  list</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.locations.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodePools.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodes.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.operations.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.workloads.list</code></p>
<p><code dir="ltr" translate="no">datastore.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></p>
<p><code dir="ltr" translate="no">datastore.locations.list</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.list</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.locations.list</code></p>
<p><code dir="ltr" translate="no">datastream.objects.list</code></p>
<p><code dir="ltr" translate="no">datastream.operations.list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.routes.list</code></p>
<p><code dir="ltr" translate="no">datastream.routes.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.streams.list</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.applications.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.catalogs.list</code></p>
<p><code dir="ltr" translate="no">designcenter.components.list</code></p>
<p><code dir="ltr" translate="no">designcenter.connections.list</code></p>
<p><code dir="ltr" translate="no">designcenter.locations.list</code></p>
<p><code dir="ltr" translate="no">designcenter.operations.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  sharedTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  sharedTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.shares.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  spaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">designcenter.spaces.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  spaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">developerconnect.  accountConnectors.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  locations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  providers.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.users.list</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agentFiles.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agentIamProposals.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.agents.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agents.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  assistants.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.branches.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  cannedQueries.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  cmekConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  collections.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  connectorRuns.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.controls.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  conversations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.documents.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  engines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  engines.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  identityMappingStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  licenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.memories.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.models.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  notebooks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.notebooks.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  notebooks.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  notificationMessages.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  operations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sampleQueries.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sampleQuerySets.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.schemas.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  servingConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.sessions.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sharedContents.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  targetSites.  list</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.connections.list</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.estimates.list</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p>
<p><code dir="ltr" translate="no">dlp.locations.list</code></p>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p>
<p><code dir="ltr" translate="no">dlp.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dns.changes.list</code></p>
<p><code dir="ltr" translate="no">dns.dnsKeys.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZoneOperations.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dns.policies.list</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></p>
<p><code dir="ltr" translate="no">dns.responsePolicies.list</code></p>
<p><code dir="ltr" translate="no">dns.responsePolicyRules.list</code></p>
<p><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">documentai.evaluations.list</code></p>
<p><code dir="ltr" translate="no">documentai.labelerPools.list</code></p>
<p><code dir="ltr" translate="no">documentai.locations.list</code></p>
<p><code dir="ltr" translate="no">documentai.processorTypes.list</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></p>
<p><code dir="ltr" translate="no">documentai.processors.list</code></p>
<p><code dir="ltr" translate="no">documentai.rules.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemaVersions.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemas.list</code></p>
<p><code dir="ltr" translate="no">documentai.validators.list</code></p>
<p><code dir="ltr" translate="no">domains.locations.list</code></p>
<p><code dir="ltr" translate="no">domains.operations.list</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">domains.registrations.list</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">dspm.locations.list</code></p>
<p><code dir="ltr" translate="no">dspm.operations.list</code></p>
<p><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.list</code></p>
<p><code dir="ltr" translate="no">earthengine.  assets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">earthengine.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.locations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  nodePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.locations.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  networks.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.operations.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routes.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.zones.list</code></p>
<p><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  gcveCuds.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  gcveNodePricingInfo.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  locations.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  operations.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  applications.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">externalexposure.  locations.  list</code></p>
<p><code dir="ltr" translate="no">externalexposure.  operations.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  affectedResources.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.experiments.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.locations.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.operations.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  validationResources.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.validations.list</code></p>
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">file.backups.list</code></p>
<p><code dir="ltr" translate="no">file.instances.list</code></p>
<p><code dir="ltr" translate="no">file.locations.list</code></p>
<p><code dir="ltr" translate="no">file.operations.list</code></p>
<p><code dir="ltr" translate="no">financialservices.  locations.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1backtests.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1datasets.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineversions.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1instances.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1models.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1predictions.  list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.list</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.list</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.list</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.list</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.list</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.list</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  list</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigationRevisions.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigations.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  locations.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  operations.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  operations.  list</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.list</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">genomics.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlans.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.locations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlans.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></p>
<p><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.features.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.list</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.locations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></p>
<p><code dir="ltr" translate="no">health.subscribers.list</code></p>
<p><code dir="ltr" translate="no">health.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.annotations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.consents.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  datasets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  datasets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Messages.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  userDataMappings.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  clusters.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  locations.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  operations.  list</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.policybindings.list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.locations.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.operations.list</code></p>
<p><code dir="ltr" translate="no">iap.tunnel.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.tunnel.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.tunnel.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.tunnelLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.  tunnelLocations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.  tunnelLocations.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.tunnelZones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iap.tunnelZones.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iap.tunnelZones.setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">iap.web.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.web.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webServices.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.list</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.locations.list</code></p>
<p><code dir="ltr" translate="no">ids.operations.list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeAuthConfigs.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeCertificates.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeExecutions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeIntegrationVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeIntegrations.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSfdcChannels.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSfdcInstances.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSuspensions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.authConfigs.list</code></p>
<p><code dir="ltr" translate="no">integrations.certificates.list</code></p>
<p><code dir="ltr" translate="no">integrations.executions.list</code></p>
<p><code dir="ltr" translate="no">integrations.  integrationVersions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.integrations.list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityAuthConfigs.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityExecutions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegTempVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegrationVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegrations.  list</code></p>
<p><code dir="ltr" translate="no">integrations.sfdcChannels.list</code></p>
<p><code dir="ltr" translate="no">integrations.  sfdcInstances.  list</code></p>
<p><code dir="ltr" translate="no">integrations.suspensions.list</code></p>
<p><code dir="ltr" translate="no">integrations.templates.list</code></p>
<p><code dir="ltr" translate="no">integrations.testCases.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.rules.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">krmapihosting.locations.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.operations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">licensemanager.instances.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.locations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.operations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.products.list</code></p>
<p><code dir="ltr" translate="no">lifesciences.operations.list</code></p>
<p><code dir="ltr" translate="no">livestream.assets.list</code></p>
<p><code dir="ltr" translate="no">livestream.channels.list</code></p>
<p><code dir="ltr" translate="no">livestream.clips.list</code></p>
<p><code dir="ltr" translate="no">livestream.dvrSessions.list</code></p>
<p><code dir="ltr" translate="no">livestream.events.list</code></p>
<p><code dir="ltr" translate="no">livestream.inputs.list</code></p>
<p><code dir="ltr" translate="no">livestream.locations.list</code></p>
<p><code dir="ltr" translate="no">livestream.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.privateLogEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.views.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">logging.views.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">looker.backups.list</code></p>
<p><code dir="ltr" translate="no">looker.instances.list</code></p>
<p><code dir="ltr" translate="no">looker.locations.list</code></p>
<p><code dir="ltr" translate="no">looker.operations.list</code></p>
<p><code dir="ltr" translate="no">lustre.instances.list</code></p>
<p><code dir="ltr" translate="no">lustre.locations.list</code></p>
<p><code dir="ltr" translate="no">lustre.operations.list</code></p>
<p><code dir="ltr" translate="no">maintenance.locations.list</code></p>
<p><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></p>
<p><code dir="ltr" translate="no">managedflink.deployments.list</code></p>
<p><code dir="ltr" translate="no">managedflink.jobs.list</code></p>
<p><code dir="ltr" translate="no">managedflink.locations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.operations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.sessions.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  locations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.locations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientMaps.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.mapViews.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.styleSnapshots.list</code></p>
<p><code dir="ltr" translate="no">mapsanalytics.  metricMetadata.  list</code></p>
<p><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></p>
<p><code dir="ltr" translate="no">memcache.instances.list</code></p>
<p><code dir="ltr" translate="no">memcache.locations.list</code></p>
<p><code dir="ltr" translate="no">memcache.operations.list</code></p>
<p><code dir="ltr" translate="no">memorystore.  backupCollections.  list</code></p>
<p><code dir="ltr" translate="no">memorystore.backups.list</code></p>
<p><code dir="ltr" translate="no">memorystore.instances.list</code></p>
<p><code dir="ltr" translate="no">memorystore.locations.list</code></p>
<p><code dir="ltr" translate="no">memorystore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.federations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.imports.list</code></p>
<p><code dir="ltr" translate="no">metastore.locations.list</code></p>
<p><code dir="ltr" translate="no">metastore.migrations.list</code></p>
<p><code dir="ltr" translate="no">metastore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.list</code></p>
<p><code dir="ltr" translate="no">metastore.tables.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">migrationcenter.assets.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  errorFrames.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.groups.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.locations.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  operations.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.relations.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.reports.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.list</code></p>
<p><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.jobs.list</code></p>
<p><code dir="ltr" translate="no">ml.jobs.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.locations.list</code></p>
<p><code dir="ltr" translate="no">ml.models.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.models.list</code></p>
<p><code dir="ltr" translate="no">ml.models.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.operations.list</code></p>
<p><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.studies.list</code></p>
<p><code dir="ltr" translate="no">ml.studies.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.trials.list</code></p>
<p><code dir="ltr" translate="no">ml.versions.list</code></p>
<p><code dir="ltr" translate="no">modelarmor.locations.list</code></p>
<p><code dir="ltr" translate="no">modelarmor.templates.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.list</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.services.list</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.list</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">netapp.activeDirectories.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupPolicies.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">netapp.backups.list</code></p>
<p><code dir="ltr" translate="no">netapp.hostGroups.list</code></p>
<p><code dir="ltr" translate="no">netapp.kmsConfigs.list</code></p>
<p><code dir="ltr" translate="no">netapp.locations.list</code></p>
<p><code dir="ltr" translate="no">netapp.operations.list</code></p>
<p><code dir="ltr" translate="no">netapp.quotaRules.list</code></p>
<p><code dir="ltr" translate="no">netapp.replications.list</code></p>
<p><code dir="ltr" translate="no">netapp.snapshots.list</code></p>
<p><code dir="ltr" translate="no">netapp.storagePools.list</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  gatewayAdvertisedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  groups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  groups.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  groups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRouteTables.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRouteTables.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRouteTables.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRoutes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRoutes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.hubs.list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferConfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferDestinations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferSupportedServices.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  remoteTransportProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  transports.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  dnsThreatDetectors.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptDeploymentGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptDeployments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptEndpointGroupAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.locations.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringDeploymentGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringDeployments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringEndpointGroupAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  agentGateways.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.locations.list</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  route_views.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></p>
<p><code dir="ltr" translate="no">notebooks.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.environments.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  environments.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.  executions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.executions.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  executions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.instances.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  instances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.locations.list</code></p>
<p><code dir="ltr" translate="no">notebooks.operations.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  runtimes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.runtimes.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  runtimes.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.  schedules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.schedules.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  schedules.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></p>
<p><code dir="ltr" translate="no">observability.buckets.list</code></p>
<p><code dir="ltr" translate="no">observability.datasets.list</code></p>
<p><code dir="ltr" translate="no">observability.links.list</code></p>
<p><code dir="ltr" translate="no">observability.locations.list</code></p>
<p><code dir="ltr" translate="no">observability.operations.list</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">observability.views.list</code></p>
<p><code dir="ltr" translate="no">ondemandscanning.  operations.  list</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemInitialStorageSizes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  systemVersions.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.  customConstraints.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.inventories.list</code></p>
<p><code dir="ltr" translate="no">osconfig.locations.list</code></p>
<p><code dir="ltr" translate="no">osconfig.operations.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></p>
<p><code dir="ltr" translate="no">osconfig.patchJobs.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></p>
<p><code dir="ltr" translate="no">parallelstore.instances.list</code></p>
<p><code dir="ltr" translate="no">parallelstore.locations.list</code></p>
<p><code dir="ltr" translate="no">parallelstore.operations.list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  replayResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.replays.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policysimulator.replays.create</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.get</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.list</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.run</code></li>
</ul>
<p><code dir="ltr" translate="no">privateca.caPools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.caPools.list</code></p>
<p><code dir="ltr" translate="no">privateca.caPools.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateAuthorities.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateAuthorities.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateAuthorities.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateRevocationLists.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateRevocationLists.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateRevocationLists.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.certificates.list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificates.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.locations.list</code></p>
<p><code dir="ltr" translate="no">privateca.operations.list</code></p>
<p><code dir="ltr" translate="no">privateca.  reusableConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.reusableConfigs.list</code></p>
<p><code dir="ltr" translate="no">privateca.  reusableConfigs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  beacons.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  beacons.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsublite.operations.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.reservations.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroupmemberships.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroups.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryPartitionClusterRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryTableStatsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeFirewallInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceNetworkThroughputInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.list</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyLateralMovementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.list</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerCloudSqlInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerDynamicRouteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerLoadBalancerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerVpcConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">redis.aclPolicies.list</code></p>
<p><code dir="ltr" translate="no">redis.backupCollections.list</code></p>
<p><code dir="ltr" translate="no">redis.backups.list</code></p>
<p><code dir="ltr" translate="no">redis.clusters.list</code></p>
<p><code dir="ltr" translate="no">redis.instances.list</code></p>
<p><code dir="ltr" translate="no">redis.locations.list</code></p>
<p><code dir="ltr" translate="no">redis.operations.list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagKeys.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcesettings.settings.list</code></p>
<p><code dir="ltr" translate="no">retail.branches.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.controls.list</code></p>
<p><code dir="ltr" translate="no">retail.experiments.list</code></p>
<p><code dir="ltr" translate="no">retail.models.list</code></p>
<p><code dir="ltr" translate="no">retail.operations.list</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></p>
<p><code dir="ltr" translate="no">riskmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.policies.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.list</code></p>
<p><code dir="ltr" translate="no">rma.collectors.list</code></p>
<p><code dir="ltr" translate="no">rma.locations.list</code></p>
<p><code dir="ltr" translate="no">rma.operations.list</code></p>
<p><code dir="ltr" translate="no">roads.selectedRoutes.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.list</code></p>
<p><code dir="ltr" translate="no">run.executions.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.list</code></p>
<p><code dir="ltr" translate="no">run.revisions.list</code></p>
<p><code dir="ltr" translate="no">run.routes.list</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.services.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.tasks.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">runapps.applications.list</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.list</code></p>
<p><code dir="ltr" translate="no">runapps.locations.list</code></p>
<p><code dir="ltr" translate="no">runapps.operations.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  configs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  configs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  variables.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  variables.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  waiters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  waiters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.units.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">secretmanager.secrets.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.list</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  riskreports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  sources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  sources.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.locations.list</code></p>
<p><code dir="ltr" translate="no">securityposture.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p>
<p><code dir="ltr" translate="no">securityposture.reports.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  bindingoperations.  list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  bindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.bindings.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  bindings.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.catalogs.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  catalogs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.  instanceoperations.  list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.instances.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  instances.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicehealth.artifacts.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.events.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.locations.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.  organizationEvents.  list</code></p>
<p><code dir="ltr" translate="no">servicehealth.  organizationImpacts.  list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  securityInfo.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  workloadPolicies.  list</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">source.repos.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">source.repos.list</code></p>
<p><code dir="ltr" translate="no">source.repos.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backupOperations.list</code></p>
<p><code dir="ltr" translate="no">spanner.  backupSchedules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">spanner.  backupSchedules.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.backups.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.databaseRoles.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instanceOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.instances.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.list</code></p>
<p><code dir="ltr" translate="no">speakerid.phrases.list</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.list</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.list</code></p>
<p><code dir="ltr" translate="no">speech.locations.list</code></p>
<p><code dir="ltr" translate="no">speech.operations.list</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.list</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.list</code></p>
<p><code dir="ltr" translate="no">storage.bucketOperations.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.featureConfigs.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.list</code></p>
<p><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.locations.list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></p>
<p><code dir="ltr" translate="no">stream.locations.list</code></p>
<p><code dir="ltr" translate="no">stream.operations.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.list</code></p>
<p><code dir="ltr" translate="no">stream.streamInstances.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.locations.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">threatintelligence.alerts.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></p>
<p><code dir="ltr" translate="no">tpu.acceleratortypes.list</code></p>
<p><code dir="ltr" translate="no">tpu.locations.list</code></p>
<p><code dir="ltr" translate="no">tpu.nodes.list</code></p>
<p><code dir="ltr" translate="no">tpu.operations.list</code></p>
<p><code dir="ltr" translate="no">tpu.runtimeversions.list</code></p>
<p><code dir="ltr" translate="no">tpu.tensorflowversions.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  appliances.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  locations.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.orders.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  savedAddresses.  list</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.indexes.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.locations.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.operations.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.cdnKeys.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  list</code></p>
<p><code dir="ltr" translate="no">videostitcher.liveConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.operations.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.slates.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  list</code></p>
<p><code dir="ltr" translate="no">videostitcher.vodConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.list</code></p>
<p><code dir="ltr" translate="no">visionai.applications.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.list</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.list</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.list</code></p>
<p><code dir="ltr" translate="no">visionai.instances.list</code></p>
<p><code dir="ltr" translate="no">visionai.locations.list</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.  operators.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.processors.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotationSets.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.datasets.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.images.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  locations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.models.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.modules.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  operations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  solutionArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  solutions.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cloneJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cutoverJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.deployments.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.groups.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.imageImports.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.locations.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.migratingVms.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.operations.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  replicationCycles.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.sources.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.targets.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  utilizationReports.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodes.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.operations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.locations.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.operations.list</code></p>
<p><code dir="ltr" translate="no">workflows.callbacks.list</code></p>
<p><code dir="ltr" translate="no">workflows.executions.list</code></p>
<p><code dir="ltr" translate="no">workflows.locations.list</code></p>
<p><code dir="ltr" translate="no">workflows.operations.list</code></p>
<p><code dir="ltr" translate="no">workflows.stepEntries.list</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.securityReviewer" class="role-title add-link" data-text="Security Reviewer" tabindex="-1">Security Reviewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p>Provides permissions to list all resources and allow policies on them.</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">actions.agentVersions.list</code></p>
<p><code dir="ltr" translate="no">advisorynotifications.  notifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  get</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentregistry.agents.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.bindings.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.endpoints.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.locations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.mcpServers.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">agentregistry.services.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agentExamples.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  datasetVersions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  entityTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationItems.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitors.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featurestores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  humanInTheLoops.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  memoryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  metadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  nasTrialDetails.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.operations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessionEvents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardRuns.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.locations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></p>
<p><code dir="ltr" translate="no">alloydb.users.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.  dataExchanges.  list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  listings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">analyticshub.listings.list</code></p>
<p><code dir="ltr" translate="no">analyticshub.  subscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigateway.  apiconfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.apiconfigs.list</code></p>
<p><code dir="ltr" translate="no">apigateway.apis.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.apis.list</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigateway.gateways.list</code></p>
<p><code dir="ltr" translate="no">apigateway.locations.list</code></p>
<p><code dir="ltr" translate="no">apigateway.operations.list</code></p>
<p><code dir="ltr" translate="no">apigee.  apiproductattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.apiproducts.list</code></p>
<p><code dir="ltr" translate="no">apigee.appgroupapps.list</code></p>
<p><code dir="ltr" translate="no">apigee.appgroups.list</code></p>
<p><code dir="ltr" translate="no">apigee.  appgroupsubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.apps.list</code></p>
<p><code dir="ltr" translate="no">apigee.archivedeployments.list</code></p>
<p><code dir="ltr" translate="no">apigee.caches.list</code></p>
<p><code dir="ltr" translate="no">apigee.datacollectors.list</code></p>
<p><code dir="ltr" translate="no">apigee.datastores.list</code></p>
<p><code dir="ltr" translate="no">apigee.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.deployments.list</code></p>
<p><code dir="ltr" translate="no">apigee.  developerappattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.developerapps.list</code></p>
<p><code dir="ltr" translate="no">apigee.  developerattributes.  list</code></p>
<p><code dir="ltr" translate="no">apigee.developers.list</code></p>
<p><code dir="ltr" translate="no">apigee.  developersubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.dnsZones.list</code></p>
<p><code dir="ltr" translate="no">apigee.  endpointattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.  envgroupattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.envgroups.list</code></p>
<p><code dir="ltr" translate="no">apigee.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.environments.list</code></p>
<p><code dir="ltr" translate="no">apigee.exports.list</code></p>
<p><code dir="ltr" translate="no">apigee.flowhooks.list</code></p>
<p><code dir="ltr" translate="no">apigee.hostqueries.list</code></p>
<p><code dir="ltr" translate="no">apigee.  hostsecurityreports.  list</code></p>
<p><code dir="ltr" translate="no">apigee.  instanceattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.instances.list</code></p>
<p><code dir="ltr" translate="no">apigee.keystorealiases.list</code></p>
<p><code dir="ltr" translate="no">apigee.keystores.list</code></p>
<p><code dir="ltr" translate="no">apigee.keyvaluemapentries.list</code></p>
<p><code dir="ltr" translate="no">apigee.keyvaluemaps.list</code></p>
<p><code dir="ltr" translate="no">apigee.nataddresses.list</code></p>
<p><code dir="ltr" translate="no">apigee.operations.list</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.list</code></p>
<p><code dir="ltr" translate="no">apigee.portals.list</code></p>
<p><code dir="ltr" translate="no">apigee.proxies.list</code></p>
<p><code dir="ltr" translate="no">apigee.proxyrevisions.list</code></p>
<p><code dir="ltr" translate="no">apigee.queries.list</code></p>
<p><code dir="ltr" translate="no">apigee.rateplans.list</code></p>
<p><code dir="ltr" translate="no">apigee.references.list</code></p>
<p><code dir="ltr" translate="no">apigee.reports.list</code></p>
<p><code dir="ltr" translate="no">apigee.resourcefiles.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityActions.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityFeedback.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityIncidents.list</code></p>
<p><code dir="ltr" translate="no">apigee.  securityMonitoringConditions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.securityProfiles.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityProfilesV2.list</code></p>
<p><code dir="ltr" translate="no">apigee.securityreports.list</code></p>
<p><code dir="ltr" translate="no">apigee.  sharedflowrevisions.  list</code></p>
<p><code dir="ltr" translate="no">apigee.sharedflows.list</code></p>
<p><code dir="ltr" translate="no">apigee.spaces.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigee.spaces.list</code></p>
<p><code dir="ltr" translate="no">apigee.targetservers.list</code></p>
<p><code dir="ltr" translate="no">apigee.  traceconfigoverrides.  list</code></p>
<p><code dir="ltr" translate="no">apigee.tracesessions.list</code></p>
<p><code dir="ltr" translate="no">apigeeconnect.connections.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  apis.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.apis.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  artifacts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.artifacts.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.locations.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.operations.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  specs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.specs.list</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.  versions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apigeeregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">apihub.addons.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.list</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.list</code></p>
<p><code dir="ltr" translate="no">apihub.curations.list</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.list</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.list</code></p>
<p><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.externalApis.list</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.llmEnablements.list</code></p>
<p><code dir="ltr" translate="no">apihub.operations.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.list</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.list</code></p>
<p><code dir="ltr" translate="no">apihub.versions.list</code></p>
<p><code dir="ltr" translate="no">apikeys.keys.list</code></p>
<p><code dir="ltr" translate="no">apim.apiObservations.list</code></p>
<p><code dir="ltr" translate="no">apim.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apim.locations.list</code></p>
<p><code dir="ltr" translate="no">apim.observationJobs.list</code></p>
<p><code dir="ltr" translate="no">apim.observationSources.list</code></p>
<p><code dir="ltr" translate="no">apim.operations.list</code></p>
<p><code dir="ltr" translate="no">appengine.instances.list</code></p>
<p><code dir="ltr" translate="no">appengine.memcache.list</code></p>
<p><code dir="ltr" translate="no">appengine.operations.list</code></p>
<p><code dir="ltr" translate="no">appengine.services.list</code></p>
<p><code dir="ltr" translate="no">appengine.versions.list</code></p>
<p><code dir="ltr" translate="no">apphub.  applications.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">apphub.applications.list</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.list</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></p>
<p><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">apphub.locations.list</code></p>
<p><code dir="ltr" translate="no">apphub.operations.list</code></p>
<p><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apphub.services.list</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.list</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></p>
<p><code dir="ltr" translate="no">appoptimize.locations.list</code></p>
<p><code dir="ltr" translate="no">appoptimize.operations.list</code></p>
<p><code dir="ltr" translate="no">appoptimize.reports.list</code></p>
<p><code dir="ltr" translate="no">apptopology.domains.list</code></p>
<p><code dir="ltr" translate="no">apptopology.locations.list</code></p>
<p><code dir="ltr" translate="no">apptopology.operations.list</code></p>
<p><code dir="ltr" translate="no">apptopology.topologyViews.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.locations.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.metadata.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.operations.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  operations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.updates.list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.workload.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.auditReports.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.controls.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.findings.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">automl.annotationSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.annotations.list</code></p>
<p><code dir="ltr" translate="no">automl.columnSpecs.list</code></p>
<p><code dir="ltr" translate="no">automl.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.datasets.list</code></p>
<p><code dir="ltr" translate="no">automl.examples.list</code></p>
<p><code dir="ltr" translate="no">automl.files.list</code></p>
<p><code dir="ltr" translate="no">automl.  humanAnnotationTasks.  list</code></p>
<p><code dir="ltr" translate="no">automl.locations.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.locations.list</code></p>
<p><code dir="ltr" translate="no">automl.modelEvaluations.list</code></p>
<p><code dir="ltr" translate="no">automl.models.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">automl.models.list</code></p>
<p><code dir="ltr" translate="no">automl.operations.list</code></p>
<p><code dir="ltr" translate="no">automl.tableSpecs.list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">autoscaling.sites.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">batch.jobs.list</code></p>
<p><code dir="ltr" translate="no">batch.locations.list</code></p>
<p><code dir="ltr" translate="no">batch.operations.list</code></p>
<p><code dir="ltr" translate="no">batch.resourceAllowances.list</code></p>
<p><code dir="ltr" translate="no">batch.tasks.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appConnections.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appConnectors.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.appGateways.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.locations.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.operations.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  securityGateways.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  securityGateways.  list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  sgApplications.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">beyondcorp.sgApplications.list</code></p>
<p><code dir="ltr" translate="no">beyondcorp.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.list</code></p>
<p><code dir="ltr" translate="no">biglake.databases.list</code></p>
<p><code dir="ltr" translate="no">biglake.locks.list</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></p>
<p><code dir="ltr" translate="no">bigtable.appProfiles.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.authorizedViews.list</code></p>
<p><code dir="ltr" translate="no">bigtable.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.backups.list</code></p>
<p><code dir="ltr" translate="no">bigtable.clusters.list</code></p>
<p><code dir="ltr" translate="no">bigtable.hotTablets.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.instances.list</code></p>
<p><code dir="ltr" translate="no">bigtable.keyvisualizer.list</code></p>
<p><code dir="ltr" translate="no">bigtable.locations.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  logicalViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.logicalViews.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  materializedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.  materializedViews.  list</code></p>
<p><code dir="ltr" translate="no">bigtable.memoryLayers.list</code></p>
<p><code dir="ltr" translate="no">bigtable.  schemaBundles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.schemaBundles.list</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigtable.tables.list</code></p>
<p><code dir="ltr" translate="no">billing.accounts.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">billing.anomalies.list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountPrices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountServices.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroupSkus.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkuGroups.  list</code></p>
<p><code dir="ltr" translate="no">billing.  billingAccountSkus.  list</code></p>
<p><code dir="ltr" translate="no">billing.budgets.list</code></p>
<p><code dir="ltr" translate="no">billing.credits.list</code></p>
<p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">billing.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  list</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  locations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  operations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  capacityPlans.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.forecasts.list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  planAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageHistories.  list</code></p>
<p><code dir="ltr" translate="no">carestudio.patients.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  observedcerts.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  list</code></p>
<p><code dir="ltr" translate="no">ces.agents.list</code></p>
<p><code dir="ltr" translate="no">ces.appVersions.list</code></p>
<p><code dir="ltr" translate="no">ces.apps.list</code></p>
<p><code dir="ltr" translate="no">ces.assistantSessions.list</code></p>
<p><code dir="ltr" translate="no">ces.changelogs.list</code></p>
<p><code dir="ltr" translate="no">ces.conversations.list</code></p>
<p><code dir="ltr" translate="no">ces.deployments.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationDatasets.list</code></p>
<p><code dir="ltr" translate="no">ces.  evaluationExpectations.  list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationResults.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">ces.evaluations.list</code></p>
<p><code dir="ltr" translate="no">ces.examples.list</code></p>
<p><code dir="ltr" translate="no">ces.guardrails.list</code></p>
<p><code dir="ltr" translate="no">ces.locations.list</code></p>
<p><code dir="ltr" translate="no">ces.operations.list</code></p>
<p><code dir="ltr" translate="no">ces.tools.list</code></p>
<p><code dir="ltr" translate="no">ces.toolsets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.analyticValues.list</code></p>
<p><code dir="ltr" translate="no">chronicle.analytics.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  chatSessionMessages.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.chatSessions.list</code></p>
<p><code dir="ltr" translate="no">chronicle.collectors.list</code></p>
<p><code dir="ltr" translate="no">chronicle.conversations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.coverageDetails.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  curatedRuleSetCategories.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  curatedRuleSetDeployments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.curatedRuleSets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.curatedRules.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dashboardCharts.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dashboardQueries.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dashboardScheduledReports.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.dashboards.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dataAccessLabels.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  dataAccessScopes.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataExports.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTableRows.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTables.list</code></p>
<p><code dir="ltr" translate="no">chronicle.dataTaps.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  enrichmentControls.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.entities.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  extensionValidationReports.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentNativeDashboards.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentRules.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  featuredContentSearchQueries.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.features.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  federationGroups.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.feedPacks.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  feedSourceTypeSchemas.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.feeds.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  findingsRefinementDeployments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  findingsRefinements.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.forwarders.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ingestionLogLabels.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ingestionLogNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  investigationComments.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  investigationSteps.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.investigations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.iocMatches.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  labsExperimentExecutions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.labsExperiments.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  logProcessingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypeSchemas.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypeSettings.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logTypes.list</code></p>
<p><code dir="ltr" translate="no">chronicle.logs.list</code></p>
<p><code dir="ltr" translate="no">chronicle.messages.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  nativeDashboards.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.notebooks.list</code></p>
<p><code dir="ltr" translate="no">chronicle.operations.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  parserExtensions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.parsers.list</code></p>
<p><code dir="ltr" translate="no">chronicle.parsingErrors.list</code></p>
<p><code dir="ltr" translate="no">chronicle.referenceLists.list</code></p>
<p><code dir="ltr" translate="no">chronicle.retrohunts.list</code></p>
<p><code dir="ltr" translate="no">chronicle.ruleDeployments.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  ruleExecutionErrors.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.rules.list</code></p>
<p><code dir="ltr" translate="no">chronicle.savedColumnSets.list</code></p>
<p><code dir="ltr" translate="no">chronicle.searchQueries.list</code></p>
<p><code dir="ltr" translate="no">chronicle.searchedResults.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  sharedPreferenceSets.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.summaryTables.list</code></p>
<p><code dir="ltr" translate="no">chronicle.tenants.list</code></p>
<p><code dir="ltr" translate="no">chronicle.  threatCollections.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  transformerDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.  validationErrors.  list</code></p>
<p><code dir="ltr" translate="no">chronicle.watchlists.list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">cloud.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  aiDevToolsSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  codeRepositoryIndexes.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  codeToolsSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  dataSharingWithGoogleSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  geminiGcpEnablementSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  loggingSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  releaseChannelSettings.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  repositoryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  repositoryGroups.  list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  topics.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.  mcpServers.  list</code></p>
<p><code dir="ltr" translate="no">cloudapiregistry.mcpTools.list</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudbuild.connections.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.integrations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.repositories.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.workerpools.list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.breakpoints.list</code></p>
<p><code dir="ltr" translate="no">clouddebugger.debuggees.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  automationRuns.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.automations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  customTargetTypes.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deployPolicies.  list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.jobRuns.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.locations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.operations.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.releases.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.rollouts.list</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">clouddeploy.targets.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.  functions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.functions.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudfunctions.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudjobdiscovery.  companies.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  importJobs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.importJobs.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  protectableResources.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.retiredResources.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstanceProposals.  list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  singleTenantHsmInstances.  list</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  list</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  realms.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  associations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogAssociations.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  producerCatalogs.  list</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudprivatecatalogproducer.  products.  list</code></p>
<p><code dir="ltr" translate="no">cloudprofiler.profiles.list</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.jobs.list</code></p>
<p><code dir="ltr" translate="no">cloudscheduler.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controlComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findingSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findings.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  crawledurls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  results.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.  accounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudsupport.accounts.list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.insights.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.tasks.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">cloudtrace.traces.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtDatasets.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtFiles.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  adaptiveMtSentences.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  customModels.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.datasets.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.glossaries.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.  glossaryentries.  list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.locations.list</code></p>
<p><code dir="ltr" translate="no">cloudtranslate.operations.list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/ipRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/regions.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/serviceLevels.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceagreementpublishing.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  partnerAccounts.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  refunds.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerDiscountOffers.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerPrivateOfferPlans.  list</code></p>
<p><code dir="ltr" translate="no">commercebusinessenablement.  resellerRestrictions.  list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.  agreements.  list</code></p>
<p><code dir="ltr" translate="no">commerceoffercatalog.  documents.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  collectionRequestApprovals.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  collections.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  populateCollectionJobs.  list</code></p>
<p><code dir="ltr" translate="no">commerceorggovernance.  services.  list</code></p>
<p><code dir="ltr" translate="no">commerceprice.events.list</code></p>
<p><code dir="ltr" translate="no">commerceprice.  privateoffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  analyticsHubListingProductConfigs.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  locations.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOfferDocuments.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  privateOffers.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.products.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.releases.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.services.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  skuGroups.  list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.skus.list</code></p>
<p><code dir="ltr" translate="no">commerceproducer.  standardOffers.  list</code></p>
<p><code dir="ltr" translate="no">composer.dags.list</code></p>
<p><code dir="ltr" translate="no">composer.environments.list</code></p>
<p><code dir="ltr" translate="no">composer.imageversions.list</code></p>
<p><code dir="ltr" translate="no">composer.operations.list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadsconfigmaps.  list</code></p>
<p><code dir="ltr" translate="no">composer.  userworkloadssecrets.  list</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.commitments.list</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.hosts.list</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.images.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.images.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.list</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.multiMig.list</code></p>
<p><code dir="ltr" translate="no">compute.multiMigMembers.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  nodeGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  nodeTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.orgRolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.orgRollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.previewFeatures.list</code></p>
<p><code dir="ltr" translate="no">compute.  publicAdvertisedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationSlots.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.rolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.rollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  vmExtensionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  zoneOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">confidentialcomputing.  locations.  list</code></p>
<p><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.list</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.locations.list</code></p>
<p><code dir="ltr" translate="no">config.operations.list</code></p>
<p><code dir="ltr" translate="no">config.previews.list</code></p>
<p><code dir="ltr" translate="no">config.resourcechanges.list</code></p>
<p><code dir="ltr" translate="no">config.resourcedrifts.list</code></p>
<p><code dir="ltr" translate="no">config.resources.list</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">config.terraformversions.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  fleetPackages.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.locations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.operations.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.releases.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.  resourceBundles.  list</code></p>
<p><code dir="ltr" translate="no">configdelivery.rollouts.list</code></p>
<p><code dir="ltr" translate="no">configdelivery.variants.list</code></p>
<p><code dir="ltr" translate="no">connectors.actions.list</code></p>
<p><code dir="ltr" translate="no">connectors.  connections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.connections.list</code></p>
<p><code dir="ltr" translate="no">connectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectorVersions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  customConnectors.  list</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.  endpointAttachments.  list</code></p>
<p><code dir="ltr" translate="no">connectors.entities.list</code></p>
<p><code dir="ltr" translate="no">connectors.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.  eventSubscriptions.  list</code></p>
<p><code dir="ltr" translate="no">connectors.eventtypes.list</code></p>
<p><code dir="ltr" translate="no">connectors.locations.list</code></p>
<p><code dir="ltr" translate="no">connectors.  managedZones.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">connectors.managedZones.list</code></p>
<p><code dir="ltr" translate="no">connectors.operations.list</code></p>
<p><code dir="ltr" translate="no">connectors.providers.list</code></p>
<p><code dir="ltr" translate="no">connectors.versions.list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  accounts.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  consents.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  events.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  freeTrials.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orderAttributions.  list</code></p>
<p><code dir="ltr" translate="no">consumerprocurement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  analyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  analysisRules.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  assessmentRules.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  assessments.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedAnalyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedAssessments.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedConversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedFeedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedNotes.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedOperations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViewSets.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViews.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  authorizedViews.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  conversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetAnalyses.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetConversations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasetFeedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveries.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryResults.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  discoveryWorkspaces.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  faqEntries.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  faqModels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  feedbackLabels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  issueModels.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  issues.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  notes.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  phraseMatchers.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaQuestionTags.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaQuestions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaScorecardRevisions.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  qaScorecards.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  views.  list</code></p>
<p><code dir="ltr" translate="no">contactcenterinsights.  visibilityLabels.  list</code></p>
<p><code dir="ltr" translate="no">container.apiServices.list</code></p>
<p><code dir="ltr" translate="no">container.auditSinks.list</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.bindings.list</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.  componentStatuses.  list</code></p>
<p><code dir="ltr" translate="no">container.configMaps.list</code></p>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.list</code></p>
<p><code dir="ltr" translate="no">container.csiDrivers.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodeInfos.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodes.list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.list</code></p>
<p><code dir="ltr" translate="no">container.deployments.list</code></p>
<p><code dir="ltr" translate="no">container.endpointSlices.list</code></p>
<p><code dir="ltr" translate="no">container.endpoints.list</code></p>
<p><code dir="ltr" translate="no">container.events.list</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></p>
<p><code dir="ltr" translate="no">container.ingresses.list</code></p>
<p><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.jobs.list</code></p>
<p><code dir="ltr" translate="no">container.leases.list</code></p>
<p><code dir="ltr" translate="no">container.limitRanges.list</code></p>
<p><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  list</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.namespaces.list</code></p>
<p><code dir="ltr" translate="no">container.networkPolicies.list</code></p>
<p><code dir="ltr" translate="no">container.nodes.list</code></p>
<p><code dir="ltr" translate="no">container.operations.list</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></p>
<p><code dir="ltr" translate="no">container.petSets.list</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></p>
<p><code dir="ltr" translate="no">container.podPresets.list</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">container.podTemplates.list</code></p>
<p><code dir="ltr" translate="no">container.pods.list</code></p>
<p><code dir="ltr" translate="no">container.priorityClasses.list</code></p>
<p><code dir="ltr" translate="no">container.replicaSets.list</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  list</code></p>
<p><code dir="ltr" translate="no">container.resourceQuotas.list</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.list</code></p>
<p><code dir="ltr" translate="no">container.roles.list</code></p>
<p><code dir="ltr" translate="no">container.runtimeClasses.list</code></p>
<p><code dir="ltr" translate="no">container.scheduledJobs.list</code></p>
<p><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">container.services.list</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.list</code></p>
<p><code dir="ltr" translate="no">container.storageClasses.list</code></p>
<p><code dir="ltr" translate="no">container.storageStates.list</code></p>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></p>
<p><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></p>
<p><code dir="ltr" translate="no">container.updateInfos.list</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></p>
<p><code dir="ltr" translate="no">container.volumeSnapshots.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">containersecurity.  clusterSummaries.  list</code></p>
<p><code dir="ltr" translate="no">containersecurity.  findings.  list</code></p>
<p><code dir="ltr" translate="no">containersecurity.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.corpora.list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documentSchemas.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  documents.  list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.ruleSets.list</code></p>
<p><code dir="ltr" translate="no">contentwarehouse.  synonymSets.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  databaseGroups.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  fleetHealthStats.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  fleetInsights.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.fleetStats.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.locations.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.products.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.queryStats.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">databasecenter.userLabels.list</code></p>
<p><code dir="ltr" translate="no">databasecenter.userTags.list</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  operations.  list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.operations.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.relationships.list</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.  taxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datacatalog.taxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.locations.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.operations.list</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.list</code></p>
<p><code dir="ltr" translate="no">dataform.commentThreads.list</code></p>
<p><code dir="ltr" translate="no">dataform.comments.list</code></p>
<p><code dir="ltr" translate="no">dataform.  compilationResults.  list</code></p>
<p><code dir="ltr" translate="no">dataform.folders.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.locations.list</code></p>
<p><code dir="ltr" translate="no">dataform.operations.list</code></p>
<p><code dir="ltr" translate="no">dataform.releaseConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataform.  teamFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workflowConfigs.list</code></p>
<p><code dir="ltr" translate="no">dataform.  workflowInvocations.  list</code></p>
<p><code dir="ltr" translate="no">dataform.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataform.workspaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.artifacts.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.instances.list</code></p>
<p><code dir="ltr" translate="no">datafusion.locations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datafusion.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datafusion.operations.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  pipelineConnections.  list</code></p>
<p><code dir="ltr" translate="no">datafusion.pipelines.list</code></p>
<p><code dir="ltr" translate="no">datafusion.profiles.list</code></p>
<p><code dir="ltr" translate="no">datafusion.secureKeys.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotateddatasets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.  annotationspecsets.  list</code></p>
<p><code dir="ltr" translate="no">datalabeling.dataitems.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.datasets.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.examples.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.instructions.list</code></p>
<p><code dir="ltr" translate="no">datalabeling.operations.list</code></p>
<p><code dir="ltr" translate="no">datalineage.events.list</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.list</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.locations.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  mappingrules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.objects.list</code></p>
<p><code dir="ltr" translate="no">datamigration.operations.list</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  list</code></p>
<p><code dir="ltr" translate="no">datapipelines.jobs.list</code></p>
<p><code dir="ltr" translate="no">datapipelines.pipelines.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assetActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.assets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.content.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.content.list</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAssets.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributeBindings.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataAttributes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataAttributes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataProducts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataProducts.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  dataTaxonomies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.dataTaxonomies.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.encryptionConfig.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entities.list</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryGroups.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  entryTypes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.entryTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.environments.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaries.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaries.list</code></p>
<p><code dir="ltr" translate="no">dataplex.  glossaryCategories.  list</code></p>
<p><code dir="ltr" translate="no">dataplex.glossaryTerms.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakeActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.lakes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.locations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataFeeds.list</code></p>
<p><code dir="ltr" translate="no">dataplex.metadataJobs.list</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.partitions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.tasks.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zoneActions.list</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.zones.list</code></p>
<p><code dir="ltr" translate="no">dataproc.agents.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.  autoscalingPolicies.  list</code></p>
<p><code dir="ltr" translate="no">dataproc.batches.list</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.clusters.list</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.jobs.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  operations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.operations.list</code></p>
<p><code dir="ltr" translate="no">dataproc.sessionTemplates.list</code></p>
<p><code dir="ltr" translate="no">dataproc.sessions.list</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataproc.  workflowTemplates.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.locations.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodePools.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.nodes.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.operations.list</code></p>
<p><code dir="ltr" translate="no">dataprocrm.workloads.list</code></p>
<p><code dir="ltr" translate="no">datastore.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></p>
<p><code dir="ltr" translate="no">datastore.locations.list</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.list</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.list</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></p>
<p><code dir="ltr" translate="no">datastream.locations.list</code></p>
<p><code dir="ltr" translate="no">datastream.objects.list</code></p>
<p><code dir="ltr" translate="no">datastream.operations.list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.routes.list</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.streams.list</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  resources.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.types.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.applications.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.catalogs.list</code></p>
<p><code dir="ltr" translate="no">designcenter.components.list</code></p>
<p><code dir="ltr" translate="no">designcenter.connections.list</code></p>
<p><code dir="ltr" translate="no">designcenter.locations.list</code></p>
<p><code dir="ltr" translate="no">designcenter.operations.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  sharedTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  sharedTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.shares.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  spaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">designcenter.spaces.list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  accountConnectors.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  locations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  providers.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.users.list</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.agents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.answerrecords.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.callMatchers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.changelogs.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  companionAgents.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.contexts.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationDatasets.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationModels.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  conversationProfiles.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.conversations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.deployments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.documents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.environments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.examples.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.experiments.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.flows.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.generators.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.integrations.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.intents.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.knowledgeBases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.pages.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.participants.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  phoneNumberOrders.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.phoneNumbers.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.playbooks.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  securitySettings.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  sessionEntityTypes.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  smartMessagingEntries.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.testcases.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.tools.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.  transitionRouteGroups.  list</code></p>
<p><code dir="ltr" translate="no">dialogflow.versions.list</code></p>
<p><code dir="ltr" translate="no">dialogflow.webhooks.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agentFiles.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agentIamProposals.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  agents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.agents.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  assistants.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  billingAccountLicenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.branches.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  cannedQueries.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  cmekConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  collections.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  connectorRuns.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.controls.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  conversations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.documents.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  engines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.engines.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  identityMappingStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  licenseConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.memories.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.models.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  notebooks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">discoveryengine.notebooks.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  notificationMessages.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  operations.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sampleQueries.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sampleQuerySets.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.schemas.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  servingConfigs.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.sessions.list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  sharedContents.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  targetSites.  list</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.connections.list</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.estimates.list</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p>
<p><code dir="ltr" translate="no">dlp.locations.list</code></p>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p>
<p><code dir="ltr" translate="no">dlp.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dns.changes.list</code></p>
<p><code dir="ltr" translate="no">dns.dnsKeys.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZoneOperations.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.policies.list</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></p>
<p><code dir="ltr" translate="no">dns.responsePolicies.list</code></p>
<p><code dir="ltr" translate="no">dns.responsePolicyRules.list</code></p>
<p><code dir="ltr" translate="no">documentai.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">documentai.evaluations.list</code></p>
<p><code dir="ltr" translate="no">documentai.labelerPools.list</code></p>
<p><code dir="ltr" translate="no">documentai.locations.list</code></p>
<p><code dir="ltr" translate="no">documentai.processorTypes.list</code></p>
<p><code dir="ltr" translate="no">documentai.  processorVersions.  list</code></p>
<p><code dir="ltr" translate="no">documentai.processors.list</code></p>
<p><code dir="ltr" translate="no">documentai.rules.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemaVersions.list</code></p>
<p><code dir="ltr" translate="no">documentai.schemas.list</code></p>
<p><code dir="ltr" translate="no">documentai.validators.list</code></p>
<p><code dir="ltr" translate="no">domains.locations.list</code></p>
<p><code dir="ltr" translate="no">domains.operations.list</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">domains.registrations.list</code></p>
<p><code dir="ltr" translate="no">dspm.locations.list</code></p>
<p><code dir="ltr" translate="no">dspm.operations.list</code></p>
<p><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.list</code></p>
<p><code dir="ltr" translate="no">earthengine.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.apikeys.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.clusters.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  identityproviders.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.locations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  machines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.machines.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  nodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.nodePools.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.operations.list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  serviceaccounts.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  vpnConnections.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalProjects.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.  zonalservices.  list</code></p>
<p><code dir="ltr" translate="no">edgecontainer.zones.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.locations.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.operations.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routes.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.zones.list</code></p>
<p><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  gcveCuds.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  gcveNodePricingInfo.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  locations.  list</code></p>
<p><code dir="ltr" translate="no">enterprisepurchasing.  operations.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  applications.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  list</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.channels.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  enrollments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.enrollments.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  googleApiSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.googleApiSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  kafkaSources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.kafkaSources.list</code></p>
<p><code dir="ltr" translate="no">eventarc.locations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  messageBuses.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.messageBuses.list</code></p>
<p><code dir="ltr" translate="no">eventarc.operations.list</code></p>
<p><code dir="ltr" translate="no">eventarc.  pipelines.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.pipelines.list</code></p>
<p><code dir="ltr" translate="no">eventarc.providers.list</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">eventarc.triggers.list</code></p>
<p><code dir="ltr" translate="no">externalexposure.  locations.  list</code></p>
<p><code dir="ltr" translate="no">externalexposure.  operations.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  affectedResources.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.experiments.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.locations.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.operations.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  validationResources.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.validations.list</code></p>
<p><code dir="ltr" translate="no">fcmdata.deliverydata.list</code></p>
<p><code dir="ltr" translate="no">file.backups.list</code></p>
<p><code dir="ltr" translate="no">file.instances.list</code></p>
<p><code dir="ltr" translate="no">file.locations.list</code></p>
<p><code dir="ltr" translate="no">file.operations.list</code></p>
<p><code dir="ltr" translate="no">financialservices.  locations.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1backtests.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1datasets.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineversions.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1instances.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1models.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1predictions.  list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.links.list</code></p>
<p><code dir="ltr" translate="no">firebase.playLinks.list</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  automations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.groups.list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.  releases.  list</code></p>
<p><code dir="ltr" translate="no">firebaseappdistro.testers.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  backends.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.builds.list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  locations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebaseapphosting.  rollouts.  list</code></p>
<p><code dir="ltr" translate="no">firebasecrashlytics.  issues.  list</code></p>
<p><code dir="ltr" translate="no">firebasedatabase.  instances.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectorRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  connectors.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  locations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemaRevisions.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  schemas.  list</code></p>
<p><code dir="ltr" translate="no">firebasedataconnect.  services.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensions.  configs.  list</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.list</code></p>
<p><code dir="ltr" translate="no">firebaseinappmessaging.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebasemessagingcampaigns.  campaigns.  list</code></p>
<p><code dir="ltr" translate="no">firebaseml.models.list</code></p>
<p><code dir="ltr" translate="no">firebaseml.modelversions.list</code></p>
<p><code dir="ltr" translate="no">firebasenotifications.  messages.  list</code></p>
<p><code dir="ltr" translate="no">firebaserules.releases.list</code></p>
<p><code dir="ltr" translate="no">firebaserules.rulesets.list</code></p>
<p><code dir="ltr" translate="no">firebasestorage.buckets.list</code></p>
<p><code dir="ltr" translate="no">firebasevertexai.  promptTemplates.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.  deliveryvehicles.  list</code></p>
<p><code dir="ltr" translate="no">fleetengine.tasks.list</code></p>
<p><code dir="ltr" translate="no">fleetengine.vehicles.list</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/databases.  list</code></p>
<p><code dir="ltr" translate="no">gcp.redisenterprise.  com/subscriptions.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigationRevisions.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  investigations.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  locations.  list</code></p>
<p><code dir="ltr" translate="no">geminicloudassist.  operations.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  dataAgents.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  locations.  list</code></p>
<p><code dir="ltr" translate="no">geminidataanalytics.  operations.  list</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.list</code></p>
<p><code dir="ltr" translate="no">genomics.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.locations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></p>
<p><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.features.list</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.list</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.namespaces.list</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.list</code></p>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.locations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.operations.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareClusters.list</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareNodePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkeonprem.vmwareNodePools.list</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></p>
<p><code dir="ltr" translate="no">health.subscribers.list</code></p>
<p><code dir="ltr" translate="no">health.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.  annotationStores.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.annotations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  attributeDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">healthcare.  consentStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.consentStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.consents.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  datasets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.datasets.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  dicomStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.dicomStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  fhirStores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.fhirStores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Messages.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  hl7V2Stores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">healthcare.hl7V2Stores.list</code></p>
<p><code dir="ltr" translate="no">healthcare.locations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.operations.list</code></p>
<p><code dir="ltr" translate="no">healthcare.  userDataMappings.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  clusters.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  locations.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  operations.  list</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">iam.policybindings.list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.locations.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.operations.list</code></p>
<p><code dir="ltr" translate="no">iap.tunnel.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelDestGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.tunnelDestGroups.list</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelInstances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  tunnelLocations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.tunnelZones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.web.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.  webServiceVersions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webServices.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iap.webTypes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.list</code></p>
<p><code dir="ltr" translate="no">ids.locations.list</code></p>
<p><code dir="ltr" translate="no">ids.operations.list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeAuthConfigs.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeCertificates.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeExecutions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeIntegrationVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeIntegrations.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSfdcChannels.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSfdcInstances.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  apigeeSuspensions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.authConfigs.list</code></p>
<p><code dir="ltr" translate="no">integrations.certificates.list</code></p>
<p><code dir="ltr" translate="no">integrations.executions.list</code></p>
<p><code dir="ltr" translate="no">integrations.  integrationVersions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.integrations.list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityAuthConfigs.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityExecutions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegTempVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegrationVers.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegrations.  list</code></p>
<p><code dir="ltr" translate="no">integrations.sfdcChannels.list</code></p>
<p><code dir="ltr" translate="no">integrations.  sfdcInstances.  list</code></p>
<p><code dir="ltr" translate="no">integrations.suspensions.list</code></p>
<p><code dir="ltr" translate="no">integrations.templates.list</code></p>
<p><code dir="ltr" translate="no">integrations.testCases.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.rules.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.locations.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.operations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">licensemanager.instances.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.locations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.operations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.products.list</code></p>
<p><code dir="ltr" translate="no">lifesciences.operations.list</code></p>
<p><code dir="ltr" translate="no">livestream.assets.list</code></p>
<p><code dir="ltr" translate="no">livestream.channels.list</code></p>
<p><code dir="ltr" translate="no">livestream.clips.list</code></p>
<p><code dir="ltr" translate="no">livestream.dvrSessions.list</code></p>
<p><code dir="ltr" translate="no">livestream.events.list</code></p>
<p><code dir="ltr" translate="no">livestream.inputs.list</code></p>
<p><code dir="ltr" translate="no">livestream.locations.list</code></p>
<p><code dir="ltr" translate="no">livestream.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.privateLogEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.views.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">looker.backups.list</code></p>
<p><code dir="ltr" translate="no">looker.instances.list</code></p>
<p><code dir="ltr" translate="no">looker.locations.list</code></p>
<p><code dir="ltr" translate="no">looker.operations.list</code></p>
<p><code dir="ltr" translate="no">lustre.instances.list</code></p>
<p><code dir="ltr" translate="no">lustre.locations.list</code></p>
<p><code dir="ltr" translate="no">lustre.operations.list</code></p>
<p><code dir="ltr" translate="no">maintenance.locations.list</code></p>
<p><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></p>
<p><code dir="ltr" translate="no">managedflink.deployments.list</code></p>
<p><code dir="ltr" translate="no">managedflink.jobs.list</code></p>
<p><code dir="ltr" translate="no">managedflink.locations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.operations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.sessions.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  backups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.backups.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.domains.list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  locations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  operations.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">managedidentities.  peerings.  list</code></p>
<p><code dir="ltr" translate="no">managedidentities.  sqlintegrations.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.acls.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  connectClusters.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.connectors.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  consumerGroups.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.contexts.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.locations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.operations.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.  schemaRegistries.  list</code></p>
<p><code dir="ltr" translate="no">managedkafka.subjects.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.topics.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.versions.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientMaps.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.mapViews.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.styleSnapshots.list</code></p>
<p><code dir="ltr" translate="no">mapsanalytics.  metricMetadata.  list</code></p>
<p><code dir="ltr" translate="no">mapsplatformdatasets.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></p>
<p><code dir="ltr" translate="no">memcache.instances.list</code></p>
<p><code dir="ltr" translate="no">memcache.locations.list</code></p>
<p><code dir="ltr" translate="no">memcache.operations.list</code></p>
<p><code dir="ltr" translate="no">memorystore.  backupCollections.  list</code></p>
<p><code dir="ltr" translate="no">memorystore.backups.list</code></p>
<p><code dir="ltr" translate="no">memorystore.instances.list</code></p>
<p><code dir="ltr" translate="no">memorystore.locations.list</code></p>
<p><code dir="ltr" translate="no">memorystore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.backups.list</code></p>
<p><code dir="ltr" translate="no">metastore.  databases.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.databases.list</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.federations.list</code></p>
<p><code dir="ltr" translate="no">metastore.imports.list</code></p>
<p><code dir="ltr" translate="no">metastore.locations.list</code></p>
<p><code dir="ltr" translate="no">metastore.migrations.list</code></p>
<p><code dir="ltr" translate="no">metastore.operations.list</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.services.list</code></p>
<p><code dir="ltr" translate="no">metastore.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">metastore.tables.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.assets.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  errorFrames.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.groups.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.locations.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  operations.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.relations.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.reports.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.list</code></p>
<p><code dir="ltr" translate="no">ml.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.jobs.list</code></p>
<p><code dir="ltr" translate="no">ml.locations.list</code></p>
<p><code dir="ltr" translate="no">ml.models.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.models.list</code></p>
<p><code dir="ltr" translate="no">ml.operations.list</code></p>
<p><code dir="ltr" translate="no">ml.studies.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ml.studies.list</code></p>
<p><code dir="ltr" translate="no">ml.trials.list</code></p>
<p><code dir="ltr" translate="no">ml.versions.list</code></p>
<p><code dir="ltr" translate="no">modelarmor.locations.list</code></p>
<p><code dir="ltr" translate="no">modelarmor.templates.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.list</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.services.list</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.list</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">netapp.activeDirectories.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupPolicies.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">netapp.backups.list</code></p>
<p><code dir="ltr" translate="no">netapp.hostGroups.list</code></p>
<p><code dir="ltr" translate="no">netapp.kmsConfigs.list</code></p>
<p><code dir="ltr" translate="no">netapp.locations.list</code></p>
<p><code dir="ltr" translate="no">netapp.operations.list</code></p>
<p><code dir="ltr" translate="no">netapp.quotaRules.list</code></p>
<p><code dir="ltr" translate="no">netapp.replications.list</code></p>
<p><code dir="ltr" translate="no">netapp.snapshots.list</code></p>
<p><code dir="ltr" translate="no">netapp.storagePools.list</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  gatewayAdvertisedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  groups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  groups.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRouteTables.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRouteTables.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRoutes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.hubs.list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferConfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferDestinations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  multicloudDataTransferSupportedServices.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  regionalEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  remoteTransportProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceClasses.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionMaps.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  serviceConnectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  transports.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  dnsThreatDetectors.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptDeploymentGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptDeployments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptEndpointGroupAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  interceptEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.locations.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringDeploymentGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringDeployments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringEndpointGroupAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  mirroringEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  agentGateways.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  googleTagGatewayPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.locations.list</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  route_views.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></p>
<p><code dir="ltr" translate="no">notebooks.  environments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.environments.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  executions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.executions.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.instances.list</code></p>
<p><code dir="ltr" translate="no">notebooks.locations.list</code></p>
<p><code dir="ltr" translate="no">notebooks.operations.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  runtimes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.runtimes.list</code></p>
<p><code dir="ltr" translate="no">notebooks.  schedules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">notebooks.schedules.list</code></p>
<p><code dir="ltr" translate="no">observability.  analyticsViews.  list</code></p>
<p><code dir="ltr" translate="no">observability.buckets.list</code></p>
<p><code dir="ltr" translate="no">observability.datasets.list</code></p>
<p><code dir="ltr" translate="no">observability.links.list</code></p>
<p><code dir="ltr" translate="no">observability.locations.list</code></p>
<p><code dir="ltr" translate="no">observability.operations.list</code></p>
<p><code dir="ltr" translate="no">observability.traceScopes.list</code></p>
<p><code dir="ltr" translate="no">observability.views.list</code></p>
<p><code dir="ltr" translate="no">ondemandscanning.  operations.  list</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemInitialStorageSizes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  systemVersions.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.  customConstraints.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.guestPolicies.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  instanceOSPoliciesCompliances.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.inventories.list</code></p>
<p><code dir="ltr" translate="no">osconfig.locations.list</code></p>
<p><code dir="ltr" translate="no">osconfig.operations.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignmentReports.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.  osPolicyAssignments.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.patchDeployments.list</code></p>
<p><code dir="ltr" translate="no">osconfig.patchJobs.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  policyOrchestrators.  list</code></p>
<p><code dir="ltr" translate="no">osconfig.upgradeReports.list</code></p>
<p><code dir="ltr" translate="no">osconfig.  vulnerabilityReports.  list</code></p>
<p><code dir="ltr" translate="no">parallelstore.instances.list</code></p>
<p><code dir="ltr" translate="no">parallelstore.locations.list</code></p>
<p><code dir="ltr" translate="no">parallelstore.operations.list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  products.  list</code></p>
<p><code dir="ltr" translate="no">paymentsresellersubscription.  promotions.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  replayResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.replays.list</code></p>
<p><code dir="ltr" translate="no">privateca.caPools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.caPools.list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateAuthorities.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateAuthorities.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateRevocationLists.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateRevocationLists.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  list</code></p>
<p><code dir="ltr" translate="no">privateca.  certificates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.certificates.list</code></p>
<p><code dir="ltr" translate="no">privateca.locations.list</code></p>
<p><code dir="ltr" translate="no">privateca.operations.list</code></p>
<p><code dir="ltr" translate="no">privateca.  reusableConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">privateca.reusableConfigs.list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  beacons.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.operations.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.reservations.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsublite.topics.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroupmemberships.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroups.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryPartitionClusterRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryTableStatsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeFirewallInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceNetworkThroughputInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.list</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyLateralMovementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.list</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerCloudSqlInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerDynamicRouteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerLoadBalancerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerVpcConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">redis.aclPolicies.list</code></p>
<p><code dir="ltr" translate="no">redis.backupCollections.list</code></p>
<p><code dir="ltr" translate="no">redis.backups.list</code></p>
<p><code dir="ltr" translate="no">redis.clusters.list</code></p>
<p><code dir="ltr" translate="no">redis.instances.list</code></p>
<p><code dir="ltr" translate="no">redis.locations.list</code></p>
<p><code dir="ltr" translate="no">redis.operations.list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">resourcesettings.settings.list</code></p>
<p><code dir="ltr" translate="no">retail.branches.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.controls.list</code></p>
<p><code dir="ltr" translate="no">retail.experiments.list</code></p>
<p><code dir="ltr" translate="no">retail.models.list</code></p>
<p><code dir="ltr" translate="no">retail.operations.list</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></p>
<p><code dir="ltr" translate="no">riskmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.policies.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.list</code></p>
<p><code dir="ltr" translate="no">rma.collectors.list</code></p>
<p><code dir="ltr" translate="no">rma.locations.list</code></p>
<p><code dir="ltr" translate="no">rma.operations.list</code></p>
<p><code dir="ltr" translate="no">roads.selectedRoutes.list</code></p>
<p><code dir="ltr" translate="no">run.configurations.list</code></p>
<p><code dir="ltr" translate="no">run.executions.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.locations.list</code></p>
<p><code dir="ltr" translate="no">run.operations.list</code></p>
<p><code dir="ltr" translate="no">run.revisions.list</code></p>
<p><code dir="ltr" translate="no">run.routes.list</code></p>
<p><code dir="ltr" translate="no">run.services.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">run.tasks.list</code></p>
<p><code dir="ltr" translate="no">run.workerpools.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">run.workerpools.list</code></p>
<p><code dir="ltr" translate="no">runapps.applications.list</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.list</code></p>
<p><code dir="ltr" translate="no">runapps.locations.list</code></p>
<p><code dir="ltr" translate="no">runapps.operations.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  configs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  variables.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.  waiters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagAttributes.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagReleases.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  flagRevisions.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.flags.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.locations.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  operations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.releases.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  rolloutKinds.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.rollouts.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.saas.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.tenants.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.unitKinds.list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.  unitOperations.  list</code></p>
<p><code dir="ltr" translate="no">saasservicemgmt.units.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">secretmanager.secrets.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.list</code></p>
<p><code dir="ltr" translate="no">securedlandingzone.  overwatches.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  branchRules.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.hooks.list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  instances.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issuecomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  issues.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  prcomments.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  pullRequests.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">securesourcemanager.  sshkeys.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  riskreports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  sources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.locations.list</code></p>
<p><code dir="ltr" translate="no">securityposture.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p>
<p><code dir="ltr" translate="no">securityposture.reports.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  bindingoperations.  list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  bindings.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.bindings.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  catalogs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.catalogs.list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  instanceoperations.  list</code></p>
<p><code dir="ltr" translate="no">servicebroker.  instances.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicebroker.instances.list</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.artifacts.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.events.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.locations.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.  organizationEvents.  list</code></p>
<p><code dir="ltr" translate="no">servicehealth.  organizationImpacts.  list</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicemanagement.  services.  list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  clusterSecurityInfo.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  securityInfo.  list</code></p>
<p><code dir="ltr" translate="no">servicesecurityinsights.  workloadPolicies.  list</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">source.repos.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">source.repos.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupOperations.list</code></p>
<p><code dir="ltr" translate="no">spanner.  backupSchedules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.databaseRoles.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instanceOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.list</code></p>
<p><code dir="ltr" translate="no">speakerid.phrases.list</code></p>
<p><code dir="ltr" translate="no">speakerid.speakers.list</code></p>
<p><code dir="ltr" translate="no">speech.customClasses.list</code></p>
<p><code dir="ltr" translate="no">speech.locations.list</code></p>
<p><code dir="ltr" translate="no">speech.operations.list</code></p>
<p><code dir="ltr" translate="no">speech.phraseSets.list</code></p>
<p><code dir="ltr" translate="no">speech.recognizers.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.list</code></p>
<p><code dir="ltr" translate="no">storage.bucketOperations.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.featureConfigs.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.hmacKeys.list</code></p>
<p><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></p>
<p><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.locations.list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></p>
<p><code dir="ltr" translate="no">stream.locations.list</code></p>
<p><code dir="ltr" translate="no">stream.operations.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.list</code></p>
<p><code dir="ltr" translate="no">stream.streamInstances.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  blueprints.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.edgeSlms.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  hydratedDeployments.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.locations.list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  operations.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  orchestrationClusters.  list</code></p>
<p><code dir="ltr" translate="no">telcoautomation.  publicBlueprints.  list</code></p>
<p><code dir="ltr" translate="no">telemetry.  consumers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">threatintelligence.alerts.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  datasets.  list</code></p>
<p><code dir="ltr" translate="no">timeseriesinsights.  locations.  list</code></p>
<p><code dir="ltr" translate="no">tpu.acceleratortypes.list</code></p>
<p><code dir="ltr" translate="no">tpu.locations.list</code></p>
<p><code dir="ltr" translate="no">tpu.nodes.list</code></p>
<p><code dir="ltr" translate="no">tpu.operations.list</code></p>
<p><code dir="ltr" translate="no">tpu.runtimeversions.list</code></p>
<p><code dir="ltr" translate="no">tpu.tensorflowversions.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobTemplates.list</code></p>
<p><code dir="ltr" translate="no">transcoder.jobs.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  appliances.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  locations.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.orders.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  savedAddresses.  list</code></p>
<p><code dir="ltr" translate="no">translationhub.portals.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.collections.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.indexes.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.locations.list</code></p>
<p><code dir="ltr" translate="no">vectorsearch.operations.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.cdnKeys.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  liveAdTagDetails.  list</code></p>
<p><code dir="ltr" translate="no">videostitcher.liveConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.operations.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.slates.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodAdTagDetails.  list</code></p>
<p><code dir="ltr" translate="no">videostitcher.vodConfigs.list</code></p>
<p><code dir="ltr" translate="no">videostitcher.  vodStitchDetails.  list</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.analyses.list</code></p>
<p><code dir="ltr" translate="no">visionai.annotations.list</code></p>
<p><code dir="ltr" translate="no">visionai.applications.list</code></p>
<p><code dir="ltr" translate="no">visionai.assets.list</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.clusters.list</code></p>
<p><code dir="ltr" translate="no">visionai.corpora.list</code></p>
<p><code dir="ltr" translate="no">visionai.dataSchemas.list</code></p>
<p><code dir="ltr" translate="no">visionai.drafts.list</code></p>
<p><code dir="ltr" translate="no">visionai.events.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.events.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">visionai.indexes.list</code></p>
<p><code dir="ltr" translate="no">visionai.instances.list</code></p>
<p><code dir="ltr" translate="no">visionai.locations.list</code></p>
<p><code dir="ltr" translate="no">visionai.operations.list</code></p>
<p><code dir="ltr" translate="no">visionai.  operators.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.operators.list</code></p>
<p><code dir="ltr" translate="no">visionai.processors.list</code></p>
<p><code dir="ltr" translate="no">visionai.searchConfigs.list</code></p>
<p><code dir="ltr" translate="no">visionai.series.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.series.list</code></p>
<p><code dir="ltr" translate="no">visionai.streams.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">visionai.streams.list</code></p>
<p><code dir="ltr" translate="no">visionai.uistreams.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotationSets.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  annotations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.datasets.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.images.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  locations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.models.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.modules.list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  operations.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  solutionArtifacts.  list</code></p>
<p><code dir="ltr" translate="no">visualinspection.  solutions.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cloneJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cutoverJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.deployments.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.groups.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.imageImports.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.locations.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.migratingVms.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.operations.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  replicationCycles.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.sources.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.targets.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  utilizationReports.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodes.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.operations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.locations.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.operations.list</code></p>
<p><code dir="ltr" translate="no">workflows.callbacks.list</code></p>
<p><code dir="ltr" translate="no">workflows.executions.list</code></p>
<p><code dir="ltr" translate="no">workflows.locations.list</code></p>
<p><code dir="ltr" translate="no">workflows.operations.list</code></p>
<p><code dir="ltr" translate="no">workflows.stepEntries.list</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  actuations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  discoveredprofiles.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  evaluations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  executions.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.results.list</code></p>
<p><code dir="ltr" translate="no">workloadmanager.rules.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountAdmin" class="role-title add-link" data-text="Service Account Admin" tabindex="-1">Service Account Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p>Create and manage service accounts.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  create</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  delete</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.disable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.enable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.undelete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountCreator" class="role-title add-link" data-text="Create Service Accounts" tabindex="-1">Create Service Accounts</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p>Access to create service accounts.</p></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountKeyAdmin" class="role-title add-link" data-text="Service Account Key Admin" tabindex="-1">Service Account Key Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p>Create and manage (and rotate) service account keys.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccountKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.create</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.delete</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.disable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.enable</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></li>
<li><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountTokenCreator" class="role-title add-link" data-text="Service Account Token Creator" tabindex="-1">Service Account Token Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p>Impersonate service accounts (create OAuth2 access tokens, sign blobs or JWTs, etc).</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  implicitDelegation</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountUser" class="role-title add-link" data-text="Service Account User" tabindex="-1">Service Account User</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p>Run operations as the service account.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountViewer" class="role-title add-link" data-text="View Service Accounts" tabindex="-1">View Service Accounts</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p>Read access to service accounts, metadata, and keys.</p></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.viewer" class="role-title add-link" data-text="Iam Viewer" tabindex="-1">Iam Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p>Viewer role for iam</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.policybindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPools.  searchPolicyBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.workloadIdentityUser" class="role-title add-link" data-text="Workload Identity User" tabindex="-1">Workload Identity User</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workloadIdentityUser</code> )</p>
<p>Impersonate service accounts from federated workloads.</p></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.accessPolicyUser" class="role-title add-link" data-text="Access Policy User Beta" tabindex="-1">Access Policy User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iam.accessPolicyUser</code> )</p>
<p>Access Policies user role, with permissions to view access policies, and to bind and unbind access policies to targets.</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.bind</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.unbind</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.accessPolicyViewer" class="role-title add-link" data-text="Access Policy Viewer Beta" tabindex="-1">Access Policy Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iam.accessPolicyViewer</code> )</p>
<p>Access Policy Viewer role, with permissions to read access policies and view associated policy bindings.</p></td>
<td><p><code dir="ltr" translate="no">iam.accesspolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.accesspolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.denyAdmin" class="role-title add-link" data-text="Deny Admin" tabindex="-1">Deny Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p>Deny admin role, with permissions to read and modify deny policies</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.denypolicies.create</code></li>
<li><code dir="ltr" translate="no">iam.denypolicies.delete</code></li>
<li><code dir="ltr" translate="no">iam.denypolicies.get</code></li>
<li><code dir="ltr" translate="no">iam.denypolicies.list</code></li>
<li><code dir="ltr" translate="no">iam.denypolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">policyanalyzer.  resourceAuthorizationActivities.  query</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  create</code></li>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  get</code></li>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.denyReviewer" class="role-title add-link" data-text="Deny Reviewer" tabindex="-1">Deny Reviewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.denyReviewer</code> )</p>
<p>Deny Reviewer role, with permissions to read deny policies</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.oauthClientAdmin" class="role-title add-link" data-text="IAM OAuth Client Admin" tabindex="-1">IAM OAuth Client Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p>Full rights to create and manage OAuth clients.</p></td>
<td><p><code dir="ltr" translate="no">iam.oauthClientCredentials.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.oauthClients.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.oauthClientViewer" class="role-title add-link" data-text="IAM OAuth Client Viewer" tabindex="-1">IAM OAuth Client Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p>Read access to a particular instance of an OAuth client.</p></td>
<td><p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.operationViewer" class="role-title add-link" data-text="IAM Operation Viewer" tabindex="-1">IAM Operation Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.operationViewer</code> )</p>
<p>Operation user role, with permissions to view and list operations in IAM v3</p></td>
<td><p><code dir="ltr" translate="no">iam.operations.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.organizationRoleAdmin" class="role-title add-link" data-text="Organization Role Administrator" tabindex="-1">Organization Role Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p>Provides access to administer all custom roles in the organization and the projects below it.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.roles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.roles.create</code></li>
<li><code dir="ltr" translate="no">iam.roles.createTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.delete</code></li>
<li><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">iam.roles.get</code></li>
<li><code dir="ltr" translate="no">iam.roles.list</code></li>
<li><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">iam.roles.listTagBindings</code></li>
<li><code dir="ltr" translate="no">iam.roles.undelete</code></li>
<li><code dir="ltr" translate="no">iam.roles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.organizationRoleViewer" class="role-title add-link" data-text="Organization Role Viewer" tabindex="-1">Organization Role Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p>Provides read access to all custom roles in the organization and the projects below it.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">iam.roles.list</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalAccessBoundaryAdmin" class="role-title add-link" data-text="Principal Access Boundary Policy Admin" tabindex="-1">Principal Access Boundary Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p>Principal Access Boundary admin role, with permissions to read and modify principal access boundary policies, and to bind and unbind principal access boundary policies to targets. Also includes permissions to read principal authorization activities analysis and permissions to list assets from Cloud Asset Inventory</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  bind</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  create</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  delete</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  unbind</code></li>
<li><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.principalAccessBoundaryUser" class="role-title add-link" data-text="Principal Access Boundary Policy User" tabindex="-1">Principal Access Boundary Policy User</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.principalAccessBoundaryUser</code> )</p>
<p>Principal Access Boundary Policies user role, with permissions to view principal access boundary policies, and to bind and unbind principal access boundary policies to targets</p></td>
<td><p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  bind</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></p>
<p><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  unbind</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.scimSyncer" class="role-title add-link" data-text="SCIM Data Syncer" tabindex="-1">SCIM Data Syncer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p>Rights to sync users and groups from external identity providers.</p></td>
<td><p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  put</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  put</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountApiKeyBindingAdmin" class="role-title add-link" data-text="Service Account API Key Binding Admin" tabindex="-1">Service Account API Key Binding Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountApiKeyBindingAdmin</code> )</p>
<p>Create and delete service account API Key bindings</p></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  create</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  delete</code></li>
<li><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  undelete</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountDeleter" class="role-title add-link" data-text="Delete Service Accounts" tabindex="-1">Delete Service Accounts</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p>Access to delete service accounts.</p></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountOpenIdTokenCreator" class="role-title add-link" data-text="Service Account OpenID Connect Identity Token Creator" tabindex="-1">Service Account OpenID Connect Identity Token Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.serviceAccountOpenIdTokenCreator</code> )</p>
<p>Create OpenID Connect (OIDC) identity tokens</p></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.workforcePoolAdmin" class="role-title add-link" data-text="IAM Workforce Pool Admin" tabindex="-1">IAM Workforce Pool Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p>Full rights to create and manage all workforce pools in the org, along with the ability to delegate permissions to other admins.</p></td>
<td><p><code dir="ltr" translate="no">iam.  workforcePoolProviderKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  put</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workforcePoolProviderScimUsers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  patch</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  put</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePoolProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePoolSubjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workforcePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  update</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  updatePolicyBinding</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.workforcePoolEditor" class="role-title add-link" data-text="IAM Workforce Pool Editor" tabindex="-1">IAM Workforce Pool Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p>Gives permission to edit workforce pools.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Workforce pool</li>
</ul></td>
<td><p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  update</code></p>
<p><code dir="ltr" translate="no">iam.workforcePoolProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.workforcePoolViewer" class="role-title add-link" data-text="IAM Workforce Pool Viewer" tabindex="-1">IAM Workforce Pool Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p>
<p>Rights to read workforce pool.</p></td>
<td><p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.workloadIdentityPoolAdmin" class="role-title add-link" data-text="IAM Workload Identity Pool Admin Beta" tabindex="-1">IAM Workload Identity Pool Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p>Full rights to create and manage workload identity pools.</p></td>
<td><p><code dir="ltr" translate="no">iam.  workloadIdentityPoolManagedIdentities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  setAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolNamespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolProviderKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  undelete</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.  workloadIdentityPoolProviders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.workloadIdentityPools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  create</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  delete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setAttestationRules</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  undelete</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  update</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.  workloadIdentityPools.  updatePolicyBinding</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iam.workloadIdentityPoolViewer" class="role-title add-link" data-text="IAM Workload Identity Pool Viewer Beta" tabindex="-1">IAM Workload Identity Pool Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p>
<p>Read access to workload identity pools.</p></td>
<td><p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.workspacePoolAdmin" class="role-title add-link" data-text="Workspace Pool IAM Admin" tabindex="-1">Workspace Pool IAM Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  iam.workspacePoolAdmin</code> )</p>
<p>IAM workspace pool admin able to bind IAM policies to Dasher accounts.</p></td>
<td><p><code dir="ltr" translate="no">iam.workspacePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  createPolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  deletePolicyBinding</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  searchPolicyBindings</code></li>
<li><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  updatePolicyBinding</code></li>
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
<td><h4 id="iam.accesspolicies.bind" class="permission-name add-link" data-text="iam.accesspolicies.bind" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.bind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.accesspolicies.create" class="permission-name add-link" data-text="iam.accesspolicies.create" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.accesspolicies.delete" class="permission-name add-link" data-text="iam.accesspolicies.delete" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.accesspolicies.get" class="permission-name add-link" data-text="iam.accesspolicies.get" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.accesspolicies.list" class="permission-name add-link" data-text="iam.accesspolicies.list" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.accesspolicies.searchPolicyBindings" class="permission-name add-link" data-text="iam.accesspolicies.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">iam.  accesspolicies.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer">Access Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.accesspolicies.unbind" class="permission-name add-link" data-text="iam.accesspolicies.unbind" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.unbind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser">Access Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.accesspolicies.update" class="permission-name add-link" data-text="iam.accesspolicies.update" tabindex="-1"><code dir="ltr" translate="no">iam.accesspolicies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin">Access Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.accessPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.denypolicies.create" class="permission-name add-link" data-text="iam.denypolicies.create" tabindex="-1"><code dir="ltr" translate="no">iam.denypolicies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.denypolicies.delete" class="permission-name add-link" data-text="iam.denypolicies.delete" tabindex="-1"><code dir="ltr" translate="no">iam.denypolicies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.denypolicies.get" class="permission-name add-link" data-text="iam.denypolicies.get" tabindex="-1"><code dir="ltr" translate="no">iam.denypolicies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyReviewer">Deny Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.denypolicies.list" class="permission-name add-link" data-text="iam.denypolicies.list" tabindex="-1"><code dir="ltr" translate="no">iam.denypolicies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyReviewer">Deny Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
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
<td><h4 id="iam.denypolicies.update" class="permission-name add-link" data-text="iam.denypolicies.update" tabindex="-1"><code dir="ltr" translate="no">iam.denypolicies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClientCredentials.create" class="permission-name add-link" data-text="iam.googleapis.com/oauthClientCredentials.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_oauthClientCredentials.delete" class="permission-name add-link" data-text="iam.googleapis.com/oauthClientCredentials.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClientCredentials.get" class="permission-name add-link" data-text="iam.googleapis.com/oauthClientCredentials.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_oauthClientCredentials.list" class="permission-name add-link" data-text="iam.googleapis.com/oauthClientCredentials.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClientCredentials.update" class="permission-name add-link" data-text="iam.googleapis.com/oauthClientCredentials.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClientCredentials.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_oauthClients.create" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClients.delete" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_oauthClients.get" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClients.list" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_oauthClients.undelete" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_oauthClients.update" class="permission-name add-link" data-text="iam.googleapis.com/oauthClients.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/oauthClients.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.oauthClientAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderKeys.create" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderKeys.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderKeys.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderKeys.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderKeys.get" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderKeys.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderKeys.list" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderKeys.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderKeys.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderKeys.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderKeys.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.create" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.get" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.list" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.patch" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.patch" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimGroups.put" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimGroups.put" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimGroups.  put</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.create" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.get" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.list" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.patch" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.patch" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviderScimUsers.put" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviderScimUsers.put" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviderScimUsers.  put</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.scimSyncer">SCIM Data Syncer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.scimSyncer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.computeUserAttributes" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.computeUserAttributes" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  computeUserAttributes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.create" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.get" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.list" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolProviders.update" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolProviders.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolProviders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePoolSubjects.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolSubjects.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePoolSubjects.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePoolSubjects.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePoolSubjects.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.create" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.createPolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.delete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.deletePolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.get" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.getIamPolicy" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.list" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolViewer">IAM Workforce Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.searchPolicyBindings" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.setIamPolicy" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workforcePools.update" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolEditor">IAM Workforce Pool Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workforcePools.updatePolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workforcePools.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workforcePools.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin">IAM Workforce Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workforcePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.create" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.delete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.get" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.getAttestationRules" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.getAttestationRules" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  getAttestationRules</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.list" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.setAttestationRules" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.setAttestationRules" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  setAttestationRules</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolManagedIdentities.update" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolManagedIdentities.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolManagedIdentities.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.create" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.delete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.get" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.list" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolNamespaces.update" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolNamespaces.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolNamespaces.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviderKeys.create" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviderKeys.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviderKeys.delete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviderKeys.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviderKeys.get" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviderKeys.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviderKeys.list" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviderKeys.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviderKeys.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviderKeys.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviderKeys.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.create" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.delete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.get" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.list" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPoolProviders.update" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPoolProviders.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.create" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.create" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.delete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.delete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.get" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.get" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.getAttestationRules" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.getAttestationRules" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getAttestationRules</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.getIamPolicy" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.list" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.list" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.setAttestationRules" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.setAttestationRules" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setAttestationRules</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.setIamPolicy" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.undelete" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workloadIdentityPools.update" class="permission-name add-link" data-text="iam.googleapis.com/workloadIdentityPools.update" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workspacePools.createPolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workspacePools.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workspacePools.deletePolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workspacePools.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.googleapis.com_workspacePools.searchPolicyBindings" class="permission-name add-link" data-text="iam.googleapis.com/workspacePools.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.googleapis.com_workspacePools.updatePolicyBinding" class="permission-name add-link" data-text="iam.googleapis.com/workspacePools.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.googleapis.  com/workspacePools.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin">Workspace Pool IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workspacePoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.operations.get" class="permission-name add-link" data-text="iam.operations.get" tabindex="-1"><code dir="ltr" translate="no">iam.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer">IAM Operation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.operationViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.policybindings.get" class="permission-name add-link" data-text="iam.policybindings.get" tabindex="-1"><code dir="ltr" translate="no">iam.policybindings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.policybindings.list" class="permission-name add-link" data-text="iam.policybindings.list" tabindex="-1"><code dir="ltr" translate="no">iam.policybindings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.principalaccessboundarypolicies.bind" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.bind" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  bind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalaccessboundarypolicies.create" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.create" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.principalaccessboundarypolicies.delete" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.delete" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalaccessboundarypolicies.get" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.get" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.principalaccessboundarypolicies.list" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.list" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalaccessboundarypolicies.searchPolicyBindings" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryViewer">Principal Access Boundary Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.principalaccessboundarypolicies.unbind" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.unbind" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  unbind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser">Principal Access Boundary Policy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.principalaccessboundarypolicies.update" class="permission-name add-link" data-text="iam.principalaccessboundarypolicies.update" tabindex="-1"><code dir="ltr" translate="no">iam.  principalaccessboundarypolicies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin">Principal Access Boundary Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.principalAccessBoundaryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roles.create" class="permission-name add-link" data-text="iam.roles.create" tabindex="-1"><code dir="ltr" translate="no">iam.roles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.roles.createTagBinding" class="permission-name add-link" data-text="iam.roles.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">iam.roles.createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roles.delete" class="permission-name add-link" data-text="iam.roles.delete" tabindex="-1"><code dir="ltr" translate="no">iam.roles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.roles.deleteTagBinding" class="permission-name add-link" data-text="iam.roles.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roles.get" class="permission-name add-link" data-text="iam.roles.get" tabindex="-1"><code dir="ltr" translate="no">iam.roles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.orgServiceAgent">Chronicle Organization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.orgServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.roles.list" class="permission-name add-link" data-text="iam.roles.list" tabindex="-1"><code dir="ltr" translate="no">iam.roles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roles.listEffectiveTags" class="permission-name add-link" data-text="iam.roles.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.roles.listTagBindings" class="permission-name add-link" data-text="iam.roles.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">iam.roles.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.roles.undelete" class="permission-name add-link" data-text="iam.roles.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.roles.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.roles.update" class="permission-name add-link" data-text="iam.roles.update" tabindex="-1"><code dir="ltr" translate="no">iam.roles.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.organizationRoleAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountApiKeyBindings.create" class="permission-name add-link" data-text="iam.serviceAccountApiKeyBindings.create" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountApiKeyBindings.delete" class="permission-name add-link" data-text="iam.serviceAccountApiKeyBindings.delete" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountApiKeyBindings.undelete" class="permission-name add-link" data-text="iam.serviceAccountApiKeyBindings.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccountApiKeyBindings.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountApiKeyBindingAdmin">Service Account API Key Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountApiKeyBindingAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountKeys.create" class="permission-name add-link" data-text="iam.serviceAccountKeys.create" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountKeys.delete" class="permission-name add-link" data-text="iam.serviceAccountKeys.delete" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountKeys.disable" class="permission-name add-link" data-text="iam.serviceAccountKeys.disable" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountKeys.enable" class="permission-name add-link" data-text="iam.serviceAccountKeys.enable" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccountKeys.get" class="permission-name add-link" data-text="iam.serviceAccountKeys.get" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccountKeys.list" class="permission-name add-link" data-text="iam.serviceAccountKeys.list" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.actAs" class="permission-name add-link" data-text="iam.serviceAccounts.actAs" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabServiceAgent">Vertex AI Colab Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.colabServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.serviceAgent">Config Delivery Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  configdelivery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.create" class="permission-name add-link" data-text="iam.serviceAccounts.create" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.createTagBinding" class="permission-name add-link" data-text="iam.serviceAccounts.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.delete" class="permission-name add-link" data-text="iam.serviceAccounts.delete" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.deleteTagBinding" class="permission-name add-link" data-text="iam.serviceAccounts.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.disable" class="permission-name add-link" data-text="iam.serviceAccounts.disable" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.enable" class="permission-name add-link" data-text="iam.serviceAccounts.enable" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.get" class="permission-name add-link" data-text="iam.serviceAccounts.get" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway_management.serviceAgent">Cloud API Gateway Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway_management.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.getAccessToken" class="permission-name add-link" data-text="iam.serviceAccounts.getAccessToken" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerycontinuousquery#bigquerycontinuousquery.serviceAgent">BigQuery Continuous Query Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerycontinuousquery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark#bigqueryspark.serviceAgent">BigQuery Spark Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigqueryspark.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.serviceAgent">Infrastructure Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.serviceAgent">Cloud Deploy Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploy.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#sourcerepo.serviceAgent">Cloud Source Repositories Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  sourcerepo.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.getIamPolicy" class="permission-name add-link" data-text="iam.serviceAccounts.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.ServiceAgentV2Ext">Cloud Composer v2 API Service Agent Extension</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.ServiceAgentV2Ext</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.getOpenIdToken" class="permission-name add-link" data-text="iam.serviceAccounts.getOpenIdToken" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountOpenIdTokenCreator">Service Account OpenID Connect Identity Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountOpenIdTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionServiceAgent">Vertex AI Extension Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.extensionServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.serviceAgent">Cloud API Gateway Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.serviceAgent">Cloud Scheduler Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudscheduler.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.serviceAgent">Cloud Tasks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.serviceAgent">Cloud Workflows Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.implicitDelegation" class="permission-name add-link" data-text="iam.serviceAccounts.implicitDelegation" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  implicitDelegation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.list" class="permission-name add-link" data-text="iam.serviceAccounts.list" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityUser">Workload Identity User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadmanager.deploymentAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.listEffectiveTags" class="permission-name add-link" data-text="iam.serviceAccounts.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.listTagBindings" class="permission-name add-link" data-text="iam.serviceAccounts.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.setIamPolicy" class="permission-name add-link" data-text="iam.serviceAccounts.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.ServiceAgentV2Ext">Cloud Composer v2 API Service Agent Extension</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.ServiceAgentV2Ext</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.signBlob" class="permission-name add-link" data-text="iam.serviceAccounts.signBlob" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.signJwt" class="permission-name add-link" data-text="iam.serviceAccounts.signJwt" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountTokenCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.serviceAgent">Secure Source Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securesourcemanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.serviceAccounts.undelete" class="permission-name add-link" data-text="iam.serviceAccounts.undelete" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.serviceAccounts.update" class="permission-name add-link" data-text="iam.serviceAccounts.update" tabindex="-1"><code dir="ltr" translate="no">iam.serviceAccounts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iam.workloadIdentityPools.createPolicyBinding" class="permission-name add-link" data-text="iam.workloadIdentityPools.createPolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.  workloadIdentityPools.  createPolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.workloadIdentityPools.deletePolicyBinding" class="permission-name add-link" data-text="iam.workloadIdentityPools.deletePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.  workloadIdentityPools.  deletePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iam.workloadIdentityPools.searchPolicyBindings" class="permission-name add-link" data-text="iam.workloadIdentityPools.searchPolicyBindings" tabindex="-1"><code dir="ltr" translate="no">iam.  workloadIdentityPools.  searchPolicyBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iam.workloadIdentityPools.updatePolicyBinding" class="permission-name add-link" data-text="iam.workloadIdentityPools.updatePolicyBinding" tabindex="-1"><code dir="ltr" translate="no">iam.  workloadIdentityPools.  updatePolicyBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.workloadIdentityPoolAdmin</code> )</p></td>
</tr>
</tbody>
</table>
