---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp
title: 'MCP Reference: policyassist.googleapis.com'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

A [Model Context Protocol (MCP) server](https://modelcontextprotocol.io/docs/learn/server-concepts) acts as a proxy between an external service that provides context, data, or capabilities to a Large Language Model (LLM) or AI application. MCP servers connect AI applications to external systems such as databases and web services, translating their responses into a format that the AI application can understand.

### Server Setup

You must [enable MCP servers](https://docs.cloud.google.com/mcp/enable-disable-mcp-servers) and [set up authentication](https://docs.cloud.google.com/mcp/authenticate-mcp) before use. For more information about using Google and Google Cloud remote MCP servers, see [Google Cloud MCP servers overview](https://docs.cloud.google.com/mcp/overview) .

### Server Endpoints

An MCP service endpoint is the network address and communication interface (usually a URL) of the MCP server that an AI application (the Host for the MCP client) uses to establish a secure, standardized connection. It is the point of contact for the LLM to request context, call a tool, or access a resource. Google MCP endpoints can be global or regional.

The Policy Assist API MCP server has the following global MCP endpoint:

- https://policyassist.googleapis.com/mcp

## MCP Tools

An [MCP tool](https://modelcontextprotocol.io/legacy/concepts/tools) is a function or executable capability that an MCP server exposes to a LLM or AI application to perform an action in the real world.

### Tools

The policyassist.googleapis.com MCP server has the following tool:

| MCP Tools                                                                                                                                 |                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`recommend_iam_roles`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles) | This tool returns IAM role suggestions based on the intent of a user's prompt. Example prompt: 'What role do I need to read Google Cloud Storage buckets?' |

### Get MCP tool specifications

To get the MCP tool specifications for all tools in an MCP server, use the `tools/list` method. The following example demonstrates how to use `curl` to list all tools and their specifications currently available within the MCP server.

**Curl Request**

```
curl --location 'https://policyassist.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
    "method": "tools/list",
    "jsonrpc": "2.0",
    "id": 1
}'
```
