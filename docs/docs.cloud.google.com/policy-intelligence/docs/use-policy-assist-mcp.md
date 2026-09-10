---
name: documents/docs.cloud.google.com/policy-intelligence/docs/use-policy-assist-mcp
uri: https://docs.cloud.google.com/policy-intelligence/docs/use-policy-assist-mcp
title: Use the Policy Assist remote MCP server
description: Learn how to use the Policy Assist remote MCP server.
data_source: docs.cloud.google.com
---

> **Preview**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

This document shows you how to use the Policy Assist remote Model Context Protocol (MCP) server to connect with AI applications including Gemini CLI, ChatGPT, Claude, and custom applications you are developing. The Policy Assist remote MCP server lets external AI agents access the IAM role picker to suggest roles for your use case. The Policy Assist remote MCP server is enabled when you enable the Policy Assist API.

[Model Context Protocol](https://modelcontextprotocol.io/docs/getting-started/intro) (MCP) standardizes how large language models (LLMs) and AI applications or agents connect to external data sources. MCP servers let you use their tools, resources, and prompts to take actions and get updated data from their backend service.

## What's the difference between local and remote MCP servers?

  - Local MCP servers  
    Typically run on your local machine and use the standard input and output streams (stdio) for communication between services on the same device.
  - Remote MCP servers  
    Run on the service's infrastructure and offer an HTTP endpoint to AI applications for communication between the AI MCP client and the MCP server. For more information about MCP architecture, see [MCP architecture](https://modelcontextprotocol.io/docs/learn/architecture) .

## Google and Google Cloud remote MCP servers

Google and Google Cloud remote MCP servers have the following features and benefits:

  - Simplified, centralized discovery
  - Managed global or regional HTTP endpoints
  - Fine-grained authorization
  - Optional prompt and response security with Model Armor protection
  - Centralized audit logging

For information about other MCP servers and information about security and governance controls available for Google Cloud MCP servers, see [Google Cloud MCP servers overview](https://docs.cloud.google.com/mcp/overview) .

## Before you begin

To ensure your agent can access the Policy Assist MCP server, you must enable the Policy Assist API on your project in the Google Cloud console:

### Required roles

To get the permissions that you need to use the Policy Assist MCP server, ask your administrator to grant you the following IAM roles on the project where you want to use the Policy Assist MCP server:

  - Make MCP tool calls: [MCP Tool User](https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser) ( `roles/mcp.toolUser` )
  - Get custom role suggestions: [IAM Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer) ( `roles/iam.viewer` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to use the Policy Assist MCP server. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to use the Policy Assist MCP server:

  - Make MCP tool calls: `mcp.tools.call`
  - Get custom role suggestions: `iam.roles.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Authentication and authorization

The Policy Assist remote MCP server uses the [OAuth 2.0](https://developers.google.com/identity/protocols/oauth2) protocol with [Identity and Access Management (IAM)](https://docs.cloud.google.com/iam/docs/overview) for authentication and authorization. All [Google Cloud identities](https://docs.cloud.google.com/docs/authentication/identity-products) are supported for authentication to MCP servers.

Policy Assist does not accept API keys for authentication.

We recommend that you create a separate identity for agents that are using MCP tools so that access to resources can be controlled and monitored. For more information about authentication, see [Authenticate to MCP servers](https://docs.cloud.google.com/mcp/authenticate-mcp) .

## Policy Assist MCP OAuth scopes

OAuth 2.0 uses scopes and credentials to determine if an authenticated principal is authorized to take a specific action on a resource. For more information about OAuth 2.0 scopes at Google, read [Using OAuth 2.0 to access Google APIs](https://developers.google.com/identity/protocols/oauth2) .

Policy Assist has the following MCP tool OAuth scopes:

| Scope URI for gcloud CLI                       | Description                                                |
| ---------------------------------------------- | ---------------------------------------------------------- |
| `https://www.googleapis.com/auth/policyassist` | Grants access to policy suggestions through Policy Assist. |

Additional scopes might be required on the resources accessed during a tool call.

## Configure an MCP client to use the Policy Assist MCP server

AI applications and agents, such as Claude or Antigravity, can instantiate an MCP client that connects to a single MCP server. An AI application can have multiple clients that connect to different MCP servers. If your application isn't listed in the [client-specific guidance](https://docs.cloud.google.com/mcp/configure-mcp-ai-application#client-specific-guidance) , then you can use the following information to connect from most applications.

In your AI application, look for a way to add or connect to a remote MCP server. For the Policy Assist MCP server, enter the following information as required:

  - **Server name** : Policy Assist MCP server
  - **Server URL** or **Endpoint** : `https://policyassist.googleapis.com/mcp`
  - **Transport** : HTTP
  - **Authentication details** : Depending on how you want to authenticate, you can enter your Google Cloud credentials, your OAuth Client ID and secret, or an agent identity and credentials. For more information about authentication, see [Authenticate to MCP servers](https://docs.cloud.google.com/mcp/authenticate-mcp) .
  - **OAuth scope** : To access the Policy Assist MCP server, use the `https://www.googleapis.com/auth/policyassist` [OAuth 2.0 scope](https://developers.google.com/identity/protocols/oauth2/scopes) .

### Redirect URIs

For web-based applications, and some desktop applications, you must allowlist a redirect URI when you create a client ID and secret for authentication. Redirect URIs are used by the authorization server to send tokens to your application. Your application's documentation should specify the redirect URI that you must use. [Custom redirect URIs](https://developers.google.com/identity/protocols/oauth2/native-app#redirect-uri_custom-scheme) aren't supported.

For application-specific guidance about setting up and connecting to MCP server, see [Client-specific guidance](https://docs.cloud.google.com/mcp/configure-mcp-ai-application#client-specific-guidance) .

For more general guidance, see the following resources:

  - [Connect to remote MCP servers](https://modelcontextprotocol.io/docs/develop/connect-remote-servers) .
  - [Configure MCP in an AI application](https://docs.cloud.google.com/mcp/configure-mcp-ai-application) .

## Available tools

To view details of available MCP tools and their descriptions for the Policy Assist MCP server, see the [Policy Assist MCP reference](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp) .

### List tools

Use the [MCP inspector](https://modelcontextprotocol.io/docs/tools/inspector) to list tools, or send a `tools/list` HTTP request directly to the Policy Assist remote MCP server. The `tools/list` method doesn't require authentication.

    POST /mcp HTTP/1.1
    Host: policyassist.googleapis.com
    Content-Type: application/json
    
    {
      "jsonrpc": "2.0",
      "method": "tools/list",
    }

## Example use cases

The Policy Assist remote MCP server lets external AI agents access the IAM role picker and use it to suggest roles for your use case. The following are some example use cases for the Policy Assist MCP server.

By default, role suggestions are designed to cover common user journeys within a service. For example, a service's Admin, Editor, or Viewer roles are often suggested.

If you want suggestions for the most granular, least privileged roles, you must specify this preference in your prompt using specific keywords, like "minimal" or "least privileged". For a list of keywords you can use, see [Keywords for least privileged roles](https://docs.cloud.google.com/iam/docs/role-picker-gemini#keywords) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Use case</th>
<th>Prompt examples</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Identifying roles for general service management</td>
<td>"What permissions do I need to manage our AlloyDB for PostgreSQL setup?"</td>
</tr>
<tr class="even">
<td>Identifying the roles necessary to perform specific tasks</td>
<td><p>"What role is required to create, start, and stop VMs?"</p>
<p>or</p>
<p>"What is the <em>minimal role</em> required to create, start, and stop VMs?"</p></td>
</tr>
<tr class="odd">
<td>Identifying roles necessary to run Google Cloud CLI commands</td>
<td><p>"What IAM role is required to run: <code dir="ltr" translate="no">gcloud compute instances create instance-1</code> ?"</p>
<p>or</p>
<p>"What is the <em>smallest role</em> a service account needs to execute: <code dir="ltr" translate="no">gcloud datastore instances describe</code> ?"</p></td>
</tr>
<tr class="even">
<td>Identifying roles for a task that includes transitive dependencies</td>
<td><p>"I need to configure a Compute Engine instance to automatically scale based on CPU utilization. Which IAM roles should I grant to the service account?"</p>
<p>or</p>
<p>"I need to configure a Compute Engine instance to automatically scale based on CPU utilization. What are the <em>minimum permissions</em> I need to grant to a service account used by a Compute Engine instance autoscaler?"</p></td>
</tr>
<tr class="odd">
<td>Identifying roles for a task that might require a combination of multiple granular roles</td>
<td><p>"Provide users access only to a particular dataset in BigQuery. They shouldn't be able to create or delete datasets."</p>
<p>or</p>
<p>"What is the <em>most secure role</em> to give users read-only access to a single dataset in BigQuery, without allowing create or delete actions on any dataset?"</p></td>
</tr>
</tbody>
</table>

## Optional security and safety configurations

MCP introduces new security risks and considerations due to the wide variety of actions that you can do with the MCP tools. To minimize and manage these risks, Google Cloud offers default settings and customizable policies to control the use of MCP tools in your Google Cloud organization or project.

For more information about MCP security and governance, see [AI security and safety](https://docs.cloud.google.com/mcp/ai-security-safety) .

### Control MCP use with Identity and Access Management deny policies

Identity and Access Management (IAM) [deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) and [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) help you secure Google Cloud and Google MCP servers.

You can combine multiple criteria to build customized security and governance policies by allowing or denying access based on the following:

  - The principal.
  - Tool properties like the read-only attribute.
  - The service name or tool name.
  - The application's OAuth client ID.

For more information, see [Control MCP use with Identity and Access Management](https://docs.cloud.google.com/mcp/control-mcp-use-iam) .

## What's next

  - Read the [Policy Assist MCP reference documentation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp) .
  - Learn more about [Google Cloud MCP servers](https://docs.cloud.google.com/mcp/overview) .
