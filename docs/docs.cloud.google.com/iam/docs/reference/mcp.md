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

MCP Tools

`  list_deny_policies  `

Lists deny policies attached to a Google Cloud project. Organizations and folders are *not* supported.

Use this tool to discover deny policies enforced at an attachment point.

This tool requires the following parameters:

  - `parent` (string): The URL-encoded full resource name of the attachment point where the policies are listed. Only projects are supported. The format is `policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies` (for example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` ).

The following parameters are optional:

  - `page_size` (int32): The maximum number of policies to return.
  - `page_token` (string): Pagination token from a previous list request.

The tool returns a list of deny policies attached to the specified resource along with an optional next page token.

`  get_deny_policy  `

Gets the details, metadata, and rules of a deny policy attached to a Google Cloud project. Organizations and folders are *not* supported.

Use this tool to inspect the denied principal sets, exempted principal sets, and denied permissions of a specific deny policy.

This tool requires the `name` parameter, which is the URL-encoded resource name of the deny policy to retrieve. Only projects are supported. The format is `policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies/POLICY_ID` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

This tool returns the deny policy representation including its rules, display name, and etag.

`  create_deny_policy  `

Creates a new deny policy attached to a Google Cloud project. Organizations and folders are *not* supported.

Deny policies set explicit access prohibitions that override allow policies, including inherited allow policies. Creating a deny policy is asynchronous and returns a long-running operation. Use the `get_deny_policy_status` tool to check for operation completion.

This tool requires the following parameters:

  - `parent` (string): The URL-encoded full resource name of the attachment point where you want to create the deny policy. Only projects are supported. The format is `policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies` (for example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` ).
  - `policy_id` (string): Unique ID for this policy (3-63 characters, lowercase letters, numbers, dashes, and periods, starting with a letter).
  - `policy` (object): The deny policy definition containing `display_name` and `rules` .

This tool returns a long-running operation resource whose resolution status can be tracked with `get_deny_policy_status` .

`  update_deny_policy  `

Updates an existing deny policy attached to a Google Cloud project. Organizations and folders are *not* supported.

Use this tool to modify deny rules, denied principals, exceptions, or display names. Perform a read-modify-write pattern by fetching the latest policy via `get_deny_policy` and providing the current `etag` to prevent concurrency conflicts. Updating a deny policy is asynchronous and returns a long-running operation. Use the `get_deny_policy_status` tool to check for operation completion.

This tool requires the `policy` parameter, which is the updated deny policy containing `name` , `display_name` , `rules` , and the current `etag` .

This tool returns a long-running operation resource whose resolution status can be tracked with `get_deny_policy_status` .

`  delete_deny_policy  `

Permanently deletes a deny policy from a Google Cloud project. Organizations and folders are *not* supported.

Once deleted, the deny rules within the policy no longer restrict access for principals. Deleting a deny policy is asynchronous and returns a long-running operation. Use the `get_deny_policy_status` tool to check for operation completion.

This tool requires the following parameters:

  - `name` (string): The URL-encoded resource name of the deny policy to delete. Only projects are supported. The format is `policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies/POLICY_ID` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

The following parameters are optional:

  - `etag` (string): The expected etag of the policy for optimistic concurrency control.

This tool returns a long-running operation resource whose resolution status can be tracked with `get_deny_policy_status` .

`  get_deny_policy_status  `

Gets the status of a long-running operation initiated by creating, updating, or deleting a deny policy. Use this tool to check whether an asynchronous deny policy mutation has completed successfully ( `done: true` ) or if any errors occurred during execution.

This tool requires the `name` parameter, which is the operation resource name returned by `create_deny_policy` , `update_deny_policy` , or `delete_deny_policy` . The format is `operations/OPERATION_ID` or `projects/PROJECT_ID/locations/LOCATION/operations/OPERATION_ID` .

This tool returns an operation object indicating completion status ( `done` ), metadata, and final response or error details.

`  list_roles  `

Lists every custom IAM role that is defined for a Google Cloud project. Organizations are *not* supported.

Use this tool to discover available custom roles. Predefined roles are *not* supported by this tool.

This tool requires the following parameters:

  - `parent` (string): The parent resource name under which custom roles are defined. Only projects are supported. The format is `projects/PROJECT_ID` . Wildcards and empty parent values are not supported.

The following parameters are optional:

  - `page_size` (int32): The maximum number of roles to return. Default is 300, max is 1000.
  - `page_token` (string): Pagination token from a previous list request.
  - `view` (string): Level of details. Supported values are 'BASIC' (default, excludes permissions) and 'FULL' (includes permissions).
  - `show_deleted` (boolean): If true, deleted custom roles are included in the results.

This tool returns a list of custom roles for the project along with an optional next page token.

`  get_role  `

Gets the definition of a custom role on a Google Cloud project. Organizations are *not* supported.

Use this tool to inspect the details of a role, such as its title, description, launch stage, and the exact set of permissions it includes.

This tool requires the `name` parameter, which is the resource name of the role. Only projects are supported. The format is `projects/PROJECT_ID/roles/ROLE_ID` . Wildcards are not supported.

This tool returns the role resource containing details including the title, description, and list of included permissions.

`  create_role  `

Creates a new custom IAM role for a Google Cloud project. Organizations are *not* supported.

Use this tool only when predefined roles do not satisfy your needs and you require a specific, customized combination of permissions.

This tool requires the following parameters:

  - `parent` (string): The resource where the role will be created. Only projects are supported. The format is `projects/PROJECT_ID` .

  - `role_id` (string): A unique identifier for the role. Must be 3-64 characters and contain only alphanumeric characters, underscores, and periods.

  - `role` (object): The role definition containing the following fields:
    
      - `title` (string): Required. A friendly title for the role.
      - `description` (string): Optional. A description of the role.
      - `included_permissions` (list of strings): Required. The list of IAM permissions this role grants (for example, `['iam.roles.list', 'iam.roles.get']` ).
      - `stage` (string): Optional. The launch stage of the role. Supported values are: `ALPHA` , `BETA` , `GA` , `DEPRECATED` , `DISABLED` , `EAP` .

This tool returns the created role definition.

`  update_role  `

Updates the definition of an existing custom IAM role. Use this tool to modify the title, description, launch stage, or set of permissions of a role that was previously created.

Do *not* use this tool to update predefined roles (for example, `roles/viewer` or `roles/iam.viewer` ), as they are managed by Google and cannot be modified.

This tool requires the following parameters:

  - `name` (string): The resource name of the role to update. The format is `projects/PROJECT_ID/roles/ROLE_ID` or `organizations/ORGANIZATION_ID/roles/ROLE_ID` .

  - `role` (object): The updated role definition containing the fields to modify. You must specify at least one of the following parameters:
    
      - `title` (string): The new title for the role.
      - `description` (string): The new description.
      - `included_permissions` (list of strings): The complete, updated list of permissions. This will replace the existing permissions.
      - `stage` (string): The updated launch stage (for example, 'ALPHA', 'BETA', 'GA').

The following parameters are optional:

  - `update_mask` (string): A comma-separated list of fields in the `role` object to update (for example, 'title,included\_permissions'). If omitted, all non-empty fields in `role` will be updated.

This tool returns the updated role definition.

`  delete_role  `

Deletes a custom IAM role, making it inactive. Organizations are *not* supported.

Use this tool to remove a role that is no longer needed.

After a role is deleted, it can no longer be used for new role bindings, and existing bindings utilizing this role will no longer grant any access. This is a destructive operation, although a deleted role can be restored using the `undelete_role` tool within 7 days.

Predefined roles cannot be deleted.

This tool requires the following parameters:

  - `name` (string): The resource name of the role to delete. Only projects are supported. The format is `projects/PROJECT_ID/roles/ROLE_ID` .

The following parameters are optional:

  - `etag` (string): Base64-encoded etag value for optimistic concurrency control to prevent overwriting concurrent changes.

This tool returns the details of the role that was deleted.

`  undelete_role  `

Restores (undeletes) a previously deleted custom IAM role. Organizations are *not* supported.

Use this tool to recover a role that was accidentally or prematurely deleted. Restoring a role makes it active and functional again, restoring the access granted by existing role bindings that referenced this role. Roles can only be restored within 7 days of deletion.

This tool requires the following parameters:

  - `name` (string): The resource name of the role to restore. Only projects are supported. The format is `projects/PROJECT_ID/roles/ROLE_ID` .

The following parameters are optional:

  - `etag` (string): Base64-encoded etag value for optimistic concurrency control to prevent overwriting concurrent changes.

This tool returns the details of the restored role.

### Get MCP tool specifications

To get the MCP tool specifications for all tools in an MCP server, use the `tools/list` method. The following example demonstrates how to use `curl` to list all tools and their specifications currently available within the MCP server.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>Curl Request</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" data-syntax="Bash" translate="no"><code>curl --location &#39;https://iam.googleapis.com/mcp&#39; \
--header &#39;content-type: application/json&#39; \
--header &#39;accept: application/json, text/event-stream&#39; \
--data &#39;{
    &quot;method&quot;: &quot;tools/list&quot;,
    &quot;jsonrpc&quot;: &quot;2.0&quot;,
    &quot;id&quot;: 1
}&#39;</code></pre></td>
</tr>
</tbody>
</table>
