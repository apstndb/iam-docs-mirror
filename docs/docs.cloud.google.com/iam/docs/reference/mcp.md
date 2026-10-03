---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp
uri: https://docs.cloud.google.com/iam/docs/reference/mcp
title: 'MCP Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

MCP server for Google Cloud Identity and Access Management (IAM) API, providing tools to manage v1 roles and v2 deny policies.

A [Model Context Protocol (MCP) server](https://modelcontextprotocol.io/docs/learn/server-concepts) acts as a proxy between an external service that provides context, data, or capabilities to a Large Language Model (LLM) or AI application. MCP servers connect AI applications to external systems such as databases and web services, translating their responses into a format that the AI application can understand.

### Server Setup

You must [enable MCP servers](https://docs.cloud.google.com/mcp/enable-disable-mcp-servers) and [set up authentication](https://docs.cloud.google.com/mcp/authenticate-mcp) before use. For more information about using Google and Google Cloud remote MCP servers, see [Google Cloud MCP servers overview](https://docs.cloud.google.com/mcp/overview) .

### Server Endpoints

An MCP service endpoint is the network address and communication interface (usually a URL) of the MCP server that an AI application (the Host for the MCP client) uses to establish a secure, standardized connection. It is the point of contact for the LLM to request context, call a tool, or access a resource. Google MCP endpoints can be global or regional.

The Identity and Access Management (IAM) API MCP server has the following global MCP endpoint:

- https://iam.googleapis.com/mcp

## MCP Tools

An [MCP tool](https://modelcontextprotocol.io/legacy/concepts/tools) is a function or executable capability that an MCP server exposes to a LLM or AI application to perform an action in the real world.

### Tools

The iam.googleapis.com MCP server has the following tools:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>MCP Tools</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies"><code>list_deny_policies</code></a></td>
<td><p>Lists deny policies attached to a Google Cloud project. Organizations and folders are <em>not</em> supported.</p>
<p>Use this tool to discover deny policies enforced at an attachment point.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>parent</code> (string): The URL-encoded full resource name of the attachment point where the policies are listed. Only projects are supported. The format is <code>policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies</code> (for example, <code>policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies</code> ).</li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>page_size</code> (int32): The maximum number of policies to return.</li>
<li><code>page_token</code> (string): Pagination token from a previous list request.</li>
</ul>
<p>The tool returns a list of deny policies attached to the specified resource along with an optional next page token.</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_deny_policy"><code>get_deny_policy</code></a></td>
<td><p>Gets the details, metadata, and rules of a deny policy attached to a Google Cloud project. Organizations and folders are <em>not</em> supported.</p>
<p>Use this tool to inspect the denied principal sets, exempted principal sets, and denied permissions of a specific deny policy.</p>
<p>This tool requires the <code>name</code> parameter, which is the URL-encoded resource name of the deny policy to retrieve. Only projects are supported. The format is <code>policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies/POLICY_ID</code> . For example, <code>policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy</code> .</p>
<p>This tool returns the deny policy representation including its rules, display name, and etag.</p></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/create_deny_policy"><code>create_deny_policy</code></a></td>
<td><p>Creates a new deny policy attached to a Google Cloud project. Organizations and folders are <em>not</em> supported.</p>
<p>Deny policies set explicit access prohibitions that override allow policies, including inherited allow policies. Creating a deny policy is asynchronous and returns a long-running operation. Use the <code>get_deny_policy_status</code> tool to check for operation completion.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>parent</code> (string): The URL-encoded full resource name of the attachment point where you want to create the deny policy. Only projects are supported. The format is <code>policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies</code> (for example, <code>policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies</code> ).</li>
<li><code>policy_id</code> (string): Unique ID for this policy (3-63 characters, lowercase letters, numbers, dashes, and periods, starting with a letter).</li>
<li><code>policy</code> (object): The deny policy definition containing <code>display_name</code> and <code>rules</code> .</li>
</ul>
<p>This tool returns a long-running operation resource whose resolution status can be tracked with <code>get_deny_policy_status</code> .</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/update_deny_policy"><code>update_deny_policy</code></a></td>
<td><p>Updates an existing deny policy attached to a Google Cloud project. Organizations and folders are <em>not</em> supported.</p>
<p>Use this tool to modify deny rules, denied principals, exceptions, or display names. Perform a read-modify-write pattern by fetching the latest policy via <code>get_deny_policy</code> and providing the current <code>etag</code> to prevent concurrency conflicts. Updating a deny policy is asynchronous and returns a long-running operation. Use the <code>get_deny_policy_status</code> tool to check for operation completion.</p>
<p>This tool requires the <code>policy</code> parameter, which is the updated deny policy containing <code>name</code> , <code>display_name</code> , <code>rules</code> , and the current <code>etag</code> .</p>
<p>This tool returns a long-running operation resource whose resolution status can be tracked with <code>get_deny_policy_status</code> .</p></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/delete_deny_policy"><code>delete_deny_policy</code></a></td>
<td><p>Permanently deletes a deny policy from a Google Cloud project. Organizations and folders are <em>not</em> supported.</p>
<p>Once deleted, the deny rules within the policy no longer restrict access for principals. Deleting a deny policy is asynchronous and returns a long-running operation. Use the <code>get_deny_policy_status</code> tool to check for operation completion.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>name</code> (string): The URL-encoded resource name of the deny policy to delete. Only projects are supported. The format is <code>policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies/POLICY_ID</code> . For example, <code>policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy</code> .</li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>etag</code> (string): The expected etag of the policy for optimistic concurrency control.</li>
</ul>
<p>This tool returns a long-running operation resource whose resolution status can be tracked with <code>get_deny_policy_status</code> .</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_deny_policy_status"><code>get_deny_policy_status</code></a></td>
<td><p>Gets the status of a long-running operation initiated by creating, updating, or deleting a deny policy. Use this tool to check whether an asynchronous deny policy mutation has completed successfully ( <code>done: true</code> ) or if any errors occurred during execution.</p>
<p>This tool requires the <code>name</code> parameter, which is the operation resource name returned by <code>create_deny_policy</code> , <code>update_deny_policy</code> , or <code>delete_deny_policy</code> . The format is <code>operations/OPERATION_ID</code> or <code>projects/PROJECT_ID/locations/LOCATION/operations/OPERATION_ID</code> .</p>
<p>This tool returns an operation object indicating completion status ( <code>done</code> ), metadata, and final response or error details.</p></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles"><code>list_roles</code></a></td>
<td><p>Lists every custom IAM role that is defined for a Google Cloud project. Organizations are <em>not</em> supported.</p>
<p>Use this tool to discover available custom roles. Predefined roles are <em>not</em> supported by this tool.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>parent</code> (string): The parent resource name under which custom roles are defined. Only projects are supported. The format is <code>projects/PROJECT_ID</code> . Wildcards and empty parent values are not supported.</li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>page_size</code> (int32): The maximum number of roles to return. Default is 300, max is 1000.</li>
<li><code>page_token</code> (string): Pagination token from a previous list request.</li>
<li><code>view</code> (string): Level of details. Supported values are 'BASIC' (default, excludes permissions) and 'FULL' (includes permissions).</li>
<li><code>show_deleted</code> (boolean): If true, deleted custom roles are included in the results.</li>
</ul>
<p>This tool returns a list of custom roles for the project along with an optional next page token.</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_role"><code>get_role</code></a></td>
<td><p>Gets the definition of a custom role on a Google Cloud project. Organizations are <em>not</em> supported.</p>
<p>Use this tool to inspect the details of a role, such as its title, description, launch stage, and the exact set of permissions it includes.</p>
<p>This tool requires the <code>name</code> parameter, which is the resource name of the role. Only projects are supported. The format is <code>projects/PROJECT_ID/roles/ROLE_ID</code> . Wildcards are not supported.</p>
<p>This tool returns the role resource containing details including the title, description, and list of included permissions.</p></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/create_role"><code>create_role</code></a></td>
<td><p>Creates a new custom IAM role for a Google Cloud project. Organizations are <em>not</em> supported.</p>
<p>Use this tool only when predefined roles do not satisfy your needs and you require a specific, customized combination of permissions.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>parent</code> (string): The resource where the role will be created. Only projects are supported. The format is <code>projects/PROJECT_ID</code> .</li>
<li><code>role_id</code> (string): A unique identifier for the role. Must be 3-64 characters and contain only alphanumeric characters, underscores, and periods.</li>
<li><p><code>role</code> (object): The role definition containing the following fields:</p>
<ul>
<li><code>title</code> (string): Required. A friendly title for the role.</li>
<li><code>description</code> (string): Optional. A description of the role.</li>
<li><code>included_permissions</code> (list of strings): Required. The list of IAM permissions this role grants (for example, <code>['iam.roles.list', 'iam.roles.get']</code> ).</li>
<li><code>stage</code> (string): Optional. The launch stage of the role. Supported values are: <code>ALPHA</code> , <code>BETA</code> , <code>GA</code> , <code>DEPRECATED</code> , <code>DISABLED</code> , <code>EAP</code> .</li>
</ul></li>
</ul>
<p>This tool returns the created role definition.</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/update_role"><code>update_role</code></a></td>
<td><p>Updates the definition of an existing custom IAM role. Use this tool to modify the title, description, launch stage, or set of permissions of a role that was previously created.</p>
<p>Do <em>not</em> use this tool to update predefined roles (for example, <code>roles/viewer</code> or <code>roles/iam.viewer</code> ), as they are managed by Google and cannot be modified.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>name</code> (string): The resource name of the role to update. The format is <code>projects/PROJECT_ID/roles/ROLE_ID</code> or <code>organizations/ORGANIZATION_ID/roles/ROLE_ID</code> .</li>
<li><p><code>role</code> (object): The updated role definition containing the fields to modify. You must specify at least one of the following parameters:</p>
<ul>
<li><code>title</code> (string): The new title for the role.</li>
<li><code>description</code> (string): The new description.</li>
<li><code>included_permissions</code> (list of strings): The complete, updated list of permissions. This will replace the existing permissions.</li>
<li><code>stage</code> (string): The updated launch stage (for example, 'ALPHA', 'BETA', 'GA').</li>
</ul></li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>update_mask</code> (string): A comma-separated list of fields in the <code>role</code> object to update (for example, 'title,included_permissions'). If omitted, all non-empty fields in <code>role</code> will be updated.</li>
</ul>
<p>This tool returns the updated role definition.</p></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/delete_role"><code>delete_role</code></a></td>
<td><p>Deletes a custom IAM role, making it inactive. Organizations are <em>not</em> supported.</p>
<p>Use this tool to remove a role that is no longer needed.</p>
<p>After a role is deleted, it can no longer be used for new role bindings, and existing bindings utilizing this role will no longer grant any access. This is a destructive operation, although a deleted role can be restored using the <code>undelete_role</code> tool within 7 days.</p>
<p>Predefined roles cannot be deleted.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>name</code> (string): The resource name of the role to delete. Only projects are supported. The format is <code>projects/PROJECT_ID/roles/ROLE_ID</code> .</li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>etag</code> (string): Base64-encoded etag value for optimistic concurrency control to prevent overwriting concurrent changes.</li>
</ul>
<p>This tool returns the details of the role that was deleted.</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/undelete_role"><code>undelete_role</code></a></td>
<td><p>Restores (undeletes) a previously deleted custom IAM role. Organizations are <em>not</em> supported.</p>
<p>Use this tool to recover a role that was accidentally or prematurely deleted. Restoring a role makes it active and functional again, restoring the access granted by existing role bindings that referenced this role. Roles can only be restored within 7 days of deletion.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>name</code> (string): The resource name of the role to restore. Only projects are supported. The format is <code>projects/PROJECT_ID/roles/ROLE_ID</code> .</li>
</ul>
<p>The following parameters are optional:</p>
<ul>
<li><code>etag</code> (string): Base64-encoded etag value for optimistic concurrency control to prevent overwriting concurrent changes.</li>
</ul>
<p>This tool returns the details of the restored role.</p></td>
</tr>
</tbody>
</table>

### Get MCP tool specifications

To get the MCP tool specifications for all tools in an MCP server, use the `tools/list` method. The following example demonstrates how to use `curl` to list all tools and their specifications currently available within the MCP server.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
    "method": "tools/list",
    "jsonrpc": "2.0",
    "id": 1
}'
```
