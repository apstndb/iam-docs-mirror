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
<td>Developer Connect Admin
<p>( <code>roles/ developerconnect.admin</code> )</p>
<p>Full access to Developer Connect resources.</p></td>
<td><p><code>developerconnect. connections. constructGitHubAppManifest</code></p>
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
<tr class="even">
<td>Developer Connect Viewer
<p>( <code>roles/ developerconnect.viewer</code> )</p>
<p>Read-only access to Developer Connect resources.</p></td>
<td><p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect HTTP Proxy Writer <sup>Beta</sup>
<p>( <code>roles/ developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Grants read and write access to connections through the HTTP Proxy.</p></td>
<td><p><code>developerconnect. connections. httpProxyRead</code></p>
<p><code>developerconnect. connections. httpProxyWrite</code></p></td>
</tr>
<tr class="even">
<td>Developer Connect Git Proxy Reader
<p>( <code>roles/ developerconnect.gitProxyReader</code> )</p>
<p>Grants read-only access to repositories through the Git Proxy.</p></td>
<td><p><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect Git Proxy User
<p>( <code>roles/ developerconnect.gitProxyUser</code> )</p>
<p>Grants read and write access to repositories through the Git Proxy.</p></td>
<td><p><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></p>
<p><code>developerconnect. gitRepositoryLinks. gitProxyWrite</code></p></td>
</tr>
<tr class="even">
<td>Developer Connect Insights Admin
<p>( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p>Admin access to Developer Connect Insights resources.</p></td>
<td><p><code>developerconnect. deploymentEvents.*</code></p>
<ul>
<li><code>developerconnect. deploymentEvents. get</code></li>
<li><code>developerconnect. deploymentEvents. list</code></li>
</ul>
<p><code>developerconnect. insightsConfigs.*</code></p>
<ul>
<li><code>developerconnect. insightsConfigs. create</code></li>
<li><code>developerconnect. insightsConfigs. delete</code></li>
<li><code>developerconnect. insightsConfigs. get</code></li>
<li><code>developerconnect. insightsConfigs. list</code></li>
<li><code>developerconnect. insightsConfigs. update</code></li>
</ul>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect Insights Config Agent
<p>( <code>roles/ developerconnect.insightsAgent</code> )</p>
<p>Allow Developer Connect to access SDLC information.</p></td>
<td><p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudasset.feeds.create</code></p>
<p><code>cloudasset.feeds.delete</code></p>
<p><code>cloudasset.feeds.get</code></p>
<p><code>cloudasset.feeds.update</code></p>
<p><code>containeranalysis. occurrences. get</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>logging.logEntries.create</code></p></td>
</tr>
<tr class="even">
<td>Developer Connect Insights Viewer
<p>( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p>Read-only access to Developer Connect Insights resources.</p></td>
<td><p><code>developerconnect. deploymentEvents.*</code></p>
<ul>
<li><code>developerconnect. deploymentEvents. get</code></li>
<li><code>developerconnect. deploymentEvents. list</code></li>
</ul>
<p><code>developerconnect. insightsConfigs. get</code></p>
<p><code>developerconnect. insightsConfigs. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect OAuth Admin <sup>Beta</sup>
<p>( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p>Grants read and write access to AccountConnector resources.</p></td>
<td><p><code>developerconnect. accountConnectors.*</code></p>
<ul>
<li><code>developerconnect. accountConnectors. create</code></li>
<li><code>developerconnect. accountConnectors. delete</code></li>
<li><code>developerconnect. accountConnectors. fetchUserRepositories</code></li>
<li><code>developerconnect. accountConnectors. get</code></li>
<li><code>developerconnect. accountConnectors. gitProxyRead</code></li>
<li><code>developerconnect. accountConnectors. gitProxyWrite</code></li>
<li><code>developerconnect. accountConnectors. httpProxyRead</code></li>
<li><code>developerconnect. accountConnectors. httpProxyWrite</code></li>
<li><code>developerconnect. accountConnectors. list</code></li>
<li><code>developerconnect. accountConnectors. update</code></li>
</ul>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>developerconnect. providers. list</code></p>
<p><code>developerconnect.users.*</code></p>
<ul>
<li><code>developerconnect.users.delete</code></li>
<li><code>developerconnect. users. deleteSelf</code></li>
<li><code>developerconnect. users. fetchAccessToken</code></li>
<li><code>developerconnect. users. finishOAuth</code></li>
<li><code>developerconnect.users.getSelf</code></li>
<li><code>developerconnect.users.list</code></li>
<li><code>developerconnect. users. startOAuth</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Developer Connect OAuth User <sup>Beta</sup>
<p>( <code>roles/ developerconnect.oauthUser</code> )</p>
<p>Grants read and write access to User resources, and read access to AccountConnectors.</p></td>
<td><p><code>developerconnect. accountConnectors. fetchUserRepositories</code></p>
<p><code>developerconnect. accountConnectors. get</code></p>
<p><code>developerconnect. accountConnectors. gitProxyRead</code></p>
<p><code>developerconnect. accountConnectors. gitProxyWrite</code></p>
<p><code>developerconnect. accountConnectors. httpProxyRead</code></p>
<p><code>developerconnect. accountConnectors. httpProxyWrite</code></p>
<p><code>developerconnect. accountConnectors. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>developerconnect. users. deleteSelf</code></p>
<p><code>developerconnect. users. fetchAccessToken</code></p>
<p><code>developerconnect. users. finishOAuth</code></p>
<p><code>developerconnect.users.getSelf</code></p>
<p><code>developerconnect. users. startOAuth</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect Read Token Accessor <sup>Beta</sup>
<p>( <code>roles/ developerconnect.readTokenAccessor</code> )</p>
<p>Grants access to Read-Only tokens (both PAT and short-lived). Also grants access to view the git repository link.</p></td>
<td><p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchReadToken</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p></td>
</tr>
<tr class="even">
<td>Developer Connect Token Accessor <sup>Beta</sup>
<p>( <code>roles/ developerconnect.tokenAccessor</code> )</p>
<p>Grants access to Read/Write and Read-Only tokens (both PAT and short-lived). Also grants access to view the git repository link.</p></td>
<td><p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchReadToken</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchReadWriteToken</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p></td>
</tr>
<tr class="odd">
<td>Developer Connect User
<p>( <code>roles/ developerconnect.user</code> )</p>
<p>Grants access to view the connection and to the features that interact with the actual repository such as reading content from the repository</p></td>
<td><p><code>developerconnect. connections. fetchGitHubInstallations</code></p>
<p><code>developerconnect. connections. fetchLinkableGitRepositories</code></p>
<p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. connections. list</code></p>
<p><code>developerconnect. gitRepositoryLinks. fetchGitRefs</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. gitRepositoryLinks. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Developer Connect Service Agent
<p>( <code>roles/ developerconnect.serviceAgent</code> )</p>
<p>Gives the Developer Connect API Service Account access to necessary GCP resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>apphub.applications.get</code></p>
<p><code>apphub.services.get</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.get</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>developerconnect. connections. get</code></p>
<p><code>developerconnect. connections. httpProxyRead</code></p>
<p><code>developerconnect. connections. httpProxyWrite</code></p>
<p><code>developerconnect. gitRepositoryLinks. get</code></p>
<p><code>developerconnect. operations. get</code></p></td>
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
<td><code>developerconnect. accountConnectors. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. accountConnectors. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. accountConnectors. fetchUserRepositories</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. accountConnectors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. accountConnectors. gitProxyRead</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. accountConnectors. gitProxyWrite</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. accountConnectors. httpProxyRead</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. accountConnectors. httpProxyWrite</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. accountConnectors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. accountConnectors. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. constructGitHubAppManifest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. fetchGitHubInstallations</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. fetchLinkableGitRepositories</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. generateGitHubStateToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code>roles/ developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code>roles/ developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code>roles/ geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. httpProxyRead</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.connectionHttpProxyWriter">Developer Connect HTTP Proxy Writer</a> ( <code>roles/ developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code>roles/ geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. httpProxyWrite</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.connectionHttpProxyWriter">Developer Connect HTTP Proxy Writer</a> ( <code>roles/ developerconnect.connectionHttpProxyWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code>roles/ geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. processGitHubAppCreationCallback</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. connections. processGitHubOAuthCallback</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. connections. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. deploymentEvents. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. deploymentEvents. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. gitRepositoryLinks. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. gitRepositoryLinks. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. gitRepositoryLinks. fetchGitRefs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. gitRepositoryLinks. fetchReadToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code>roles/ developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code>roles/ developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>developerconnect. gitRepositoryLinks. fetchReadWriteToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code>roles/ developerconnect.tokenAccessor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. gitRepositoryLinks. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.readTokenAccessor">Developer Connect Read Token Accessor</a> ( <code>roles/ developerconnect.readTokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.tokenAccessor">Developer Connect Token Accessor</a> ( <code>roles/ developerconnect.tokenAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.serviceAgent">Firebase App Hosting Service Agent</a> ( <code>roles/ firebaseapphosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code>roles/ geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>developerconnect. gitRepositoryLinks. gitProxyRead</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyReader">Developer Connect Git Proxy Reader</a> ( <code>roles/ developerconnect.gitProxyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyUser">Developer Connect Git Proxy User</a> ( <code>roles/ developerconnect.gitProxyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. gitRepositoryLinks. gitProxyWrite</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.gitProxyUser">Developer Connect Git Proxy User</a> ( <code>roles/ developerconnect.gitProxyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>developerconnect. gitRepositoryLinks. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. insightsConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. insightsConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. insightsConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. insightsConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. insightsConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicodeassistmanagement#geminicodeassistmanagement.serviceAgent">Gemini Code Assist Management Service Agent</a> ( <code>roles/ geminicodeassistmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>developerconnect. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. providers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect.users.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. users. deleteSelf</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. users. fetchAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect. users. finishOAuth</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect.users.getSelf</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>developerconnect.users.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>developerconnect. users. startOAuth</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
