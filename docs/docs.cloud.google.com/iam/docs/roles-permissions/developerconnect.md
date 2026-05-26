---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/developerconnect
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect
title: Developer Connect roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Developer Connect. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Developer Connect roles

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
<td><h4 id="developerconnect.admin" class="role-title add-link" data-text="Developer Connect Admin Beta" tabindex="-1">Developer Connect Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p>Full access to Developer Connect resources.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  constructGitHubAppManifest</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  create</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  delete</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  fetchGitHubInstallations</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  fetchLinkableGitRepositories</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  generateGitHubStateToken</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  processGitHubAppCreationCallback</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  processGitHubOAuthCallback</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  update</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  create</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  delete</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchGitRefs</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyRead</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyWrite</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">developerconnect.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">developerconnect.  operations.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.viewer" class="role-title add-link" data-text="Developer Connect Viewer Beta" tabindex="-1">Developer Connect Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p>Read-only access to Developer Connect resources.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connectionHttpProxyWriter" class="role-title add-link" data-text="Developer Connect HTTP Proxy Writer Beta" tabindex="-1">Developer Connect HTTP Proxy Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Grants read and write access to connections through the HTTP Proxy.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  httpProxyRead</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  httpProxyWrite</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.gitProxyReader" class="role-title add-link" data-text="Developer Connect Git Proxy Reader Beta" tabindex="-1">Developer Connect Git Proxy Reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.gitProxyReader</code> )</p>
<p>Grants read-only access to repositories through the Git Proxy.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyRead</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitProxyUser" class="role-title add-link" data-text="Developer Connect Git Proxy User Beta" tabindex="-1">Developer Connect Git Proxy User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.gitProxyUser</code> )</p>
<p>Grants read and write access to repositories through the Git Proxy.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyRead</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyWrite</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.insightsAdmin" class="role-title add-link" data-text="Developer Connect Insights Admin Beta" tabindex="-1">Developer Connect Insights Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p>Admin access to Developer Connect Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  deploymentEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  create</code></li>
<li><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></li>
<li><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.insightsAgent" class="role-title add-link" data-text="Developer Connect Insights Config Agent Beta" tabindex="-1">Developer Connect Insights Config Agent <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.insightsAgent</code> )</p>
<p>Allow Developer Connect to access SDLC information.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.get</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.update</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.insightsViewer" class="role-title add-link" data-text="Developer Connect Insights Viewer Beta" tabindex="-1">Developer Connect Insights Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p>Read-only access to Developer Connect Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  deploymentEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.oauthAdmin" class="role-title add-link" data-text="Developer Connect OAuth Admin Beta" tabindex="-1">Developer Connect OAuth Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p>Grants read and write access to AccountConnector resources.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  accountConnectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  accountConnectors.  create</code></li>
<li><code dir="ltr" translate="no">developerconnect.  accountConnectors.  delete</code></li>
<li><code dir="ltr" translate="no">developerconnect.  accountConnectors.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  accountConnectors.  list</code></li>
<li><code dir="ltr" translate="no">developerconnect.  accountConnectors.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  providers.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.users.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.users.delete</code></li>
<li><code dir="ltr" translate="no">developerconnect.  users.  deleteSelf</code></li>
<li><code dir="ltr" translate="no">developerconnect.  users.  fetchAccessToken</code></li>
<li><code dir="ltr" translate="no">developerconnect.  users.  finishOAuth</code></li>
<li><code dir="ltr" translate="no">developerconnect.users.getSelf</code></li>
<li><code dir="ltr" translate="no">developerconnect.users.list</code></li>
<li><code dir="ltr" translate="no">developerconnect.  users.  startOAuth</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.oauthUser" class="role-title add-link" data-text="Developer Connect OAuth User Beta" tabindex="-1">Developer Connect OAuth User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p>Grants read and write access to User resources, and read access to AccountConnectors.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  accountConnectors.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  accountConnectors.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  users.  deleteSelf</code></p>
<p><code dir="ltr" translate="no">developerconnect.  users.  fetchAccessToken</code></p>
<p><code dir="ltr" translate="no">developerconnect.  users.  finishOAuth</code></p>
<p><code dir="ltr" translate="no">developerconnect.users.getSelf</code></p>
<p><code dir="ltr" translate="no">developerconnect.  users.  startOAuth</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.readTokenAccessor" class="role-title add-link" data-text="Developer Connect Read Token Accessor Beta" tabindex="-1">Developer Connect Read Token Accessor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.readTokenAccessor</code> )</p>
<p>Grants access to Read-Only tokens (both PAT and short-lived). Also grants access to view the git repository link.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchReadToken</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.tokenAccessor" class="role-title add-link" data-text="Developer Connect Token Accessor Beta" tabindex="-1">Developer Connect Token Accessor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.tokenAccessor</code> )</p>
<p>Grants access to Read/Write and Read-Only tokens (both PAT and short-lived). Also grants access to view the git repository link.</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchReadToken</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchReadWriteToken</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.user" class="role-title add-link" data-text="Developer Connect User Beta" tabindex="-1">Developer Connect User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p>Grants access to view the connection and to the features that interact with the actual repository such as reading content from the repository</p></td>
<td><p><code dir="ltr" translate="no">developerconnect.  connections.  fetchGitHubInstallations</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  fetchLinkableGitRepositories</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  connections.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchGitRefs</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
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
<td><h4 id="developerconnect.serviceAgent" class="role-title add-link" data-text="Developer Connect Service Agent" tabindex="-1">Developer Connect Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</p>
<p>Gives the Developer Connect API Service Account access to necessary GCP resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apphub.applications.get</code></p>
<p><code dir="ltr" translate="no">apphub.services.get</code></p>
<p><code dir="ltr" translate="no">apphub.services.list</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.get</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p></td>
</tr>
</tbody>
</table>

## Developer Connect permissions

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
<td><h4 id="developerconnect.accountConnectors.create" class="permission-name add-link" data-text="developerconnect.accountConnectors.create" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  accountConnectors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.accountConnectors.delete" class="permission-name add-link" data-text="developerconnect.accountConnectors.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  accountConnectors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.accountConnectors.get" class="permission-name add-link" data-text="developerconnect.accountConnectors.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  accountConnectors.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.accountConnectors.list" class="permission-name add-link" data-text="developerconnect.accountConnectors.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  accountConnectors.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.accountConnectors.update" class="permission-name add-link" data-text="developerconnect.accountConnectors.update" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  accountConnectors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.constructGitHubAppManifest" class="permission-name add-link" data-text="developerconnect.connections.constructGitHubAppManifest" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  constructGitHubAppManifest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.create" class="permission-name add-link" data-text="developerconnect.connections.create" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.delete" class="permission-name add-link" data-text="developerconnect.connections.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.fetchGitHubInstallations" class="permission-name add-link" data-text="developerconnect.connections.fetchGitHubInstallations" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  fetchGitHubInstallations</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.fetchLinkableGitRepositories" class="permission-name add-link" data-text="developerconnect.connections.fetchLinkableGitRepositories" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  fetchLinkableGitRepositories</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.generateGitHubStateToken" class="permission-name add-link" data-text="developerconnect.connections.generateGitHubStateToken" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  generateGitHubStateToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.get" class="permission-name add-link" data-text="developerconnect.connections.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.httpProxyRead" class="permission-name add-link" data-text="developerconnect.connections.httpProxyRead" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  httpProxyRead</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.connectionHttpProxyWriter">Developer Connect HTTP Proxy Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.httpProxyWrite" class="permission-name add-link" data-text="developerconnect.connections.httpProxyWrite" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  httpProxyWrite</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.connectionHttpProxyWriter">Developer Connect HTTP Proxy Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.list" class="permission-name add-link" data-text="developerconnect.connections.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.processGitHubAppCreationCallback" class="permission-name add-link" data-text="developerconnect.connections.processGitHubAppCreationCallback" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  processGitHubAppCreationCallback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.connections.processGitHubOAuthCallback" class="permission-name add-link" data-text="developerconnect.connections.processGitHubOAuthCallback" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  processGitHubOAuthCallback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.connections.update" class="permission-name add-link" data-text="developerconnect.connections.update" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  connections.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.deploymentEvents.get" class="permission-name add-link" data-text="developerconnect.deploymentEvents.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.deploymentEvents.list" class="permission-name add-link" data-text="developerconnect.deploymentEvents.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitRepositoryLinks.create" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.create" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.gitRepositoryLinks.delete" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitRepositoryLinks.fetchGitRefs" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.fetchGitRefs" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchGitRefs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.gitRepositoryLinks.fetchReadToken" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.fetchReadToken" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchReadToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitRepositoryLinks.fetchReadWriteToken" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.fetchReadWriteToken" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  fetchReadWriteToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.tokenAccessor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.gitRepositoryLinks.get" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitRepositoryLinks.gitProxyRead" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.gitProxyRead" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyRead</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyReader">Developer Connect Git Proxy Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.gitProxyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyUser">Developer Connect Git Proxy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.gitProxyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.gitRepositoryLinks.gitProxyWrite" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.gitProxyWrite" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  gitProxyWrite</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyUser">Developer Connect Git Proxy User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.gitProxyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.gitRepositoryLinks.list" class="permission-name add-link" data-text="developerconnect.gitRepositoryLinks.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  gitRepositoryLinks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.insightsConfigs.create" class="permission-name add-link" data-text="developerconnect.insightsConfigs.create" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.insightsConfigs.delete" class="permission-name add-link" data-text="developerconnect.insightsConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.insightsConfigs.get" class="permission-name add-link" data-text="developerconnect.insightsConfigs.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.insightsConfigs.list" class="permission-name add-link" data-text="developerconnect.insightsConfigs.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.insightsConfigs.update" class="permission-name add-link" data-text="developerconnect.insightsConfigs.update" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.locations.get" class="permission-name add-link" data-text="developerconnect.locations.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.locations.list" class="permission-name add-link" data-text="developerconnect.locations.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.operations.cancel" class="permission-name add-link" data-text="developerconnect.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.operations.delete" class="permission-name add-link" data-text="developerconnect.operations.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.operations.get" class="permission-name add-link" data-text="developerconnect.operations.get" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.operations.list" class="permission-name add-link" data-text="developerconnect.operations.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.providers.list" class="permission-name add-link" data-text="developerconnect.providers.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  providers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.users.delete" class="permission-name add-link" data-text="developerconnect.users.delete" tabindex="-1"><code dir="ltr" translate="no">developerconnect.users.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.users.deleteSelf" class="permission-name add-link" data-text="developerconnect.users.deleteSelf" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  users.  deleteSelf</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.users.fetchAccessToken" class="permission-name add-link" data-text="developerconnect.users.fetchAccessToken" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  users.  fetchAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.users.finishOAuth" class="permission-name add-link" data-text="developerconnect.users.finishOAuth" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  users.  finishOAuth</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.users.getSelf" class="permission-name add-link" data-text="developerconnect.users.getSelf" tabindex="-1"><code dir="ltr" translate="no">developerconnect.users.getSelf</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="developerconnect.users.list" class="permission-name add-link" data-text="developerconnect.users.list" tabindex="-1"><code dir="ltr" translate="no">developerconnect.users.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="developerconnect.users.startOAuth" class="permission-name add-link" data-text="developerconnect.users.startOAuth" tabindex="-1"><code dir="ltr" translate="no">developerconnect.  users.  startOAuth</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.oauthUser</code> )</p></td>
</tr>
</tbody>
</table>
