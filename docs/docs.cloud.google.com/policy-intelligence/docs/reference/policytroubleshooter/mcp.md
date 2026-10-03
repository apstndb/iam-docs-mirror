---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp
title: 'MCP Reference: policytroubleshooter.googleapis.com'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

Policy Troubleshooter MCP Server provides tools to troubleshoot Google Cloud IAM access issues.

A [Model Context Protocol (MCP) server](https://modelcontextprotocol.io/docs/learn/server-concepts) acts as a proxy between an external service that provides context, data, or capabilities to a Large Language Model (LLM) or AI application. MCP servers connect AI applications to external systems such as databases and web services, translating their responses into a format that the AI application can understand.

### Server Setup

You must [enable MCP servers](https://docs.cloud.google.com/mcp/enable-disable-mcp-servers) and [set up authentication](https://docs.cloud.google.com/mcp/authenticate-mcp) before use. For more information about using Google and Google Cloud remote MCP servers, see [Google Cloud MCP servers overview](https://docs.cloud.google.com/mcp/overview) .

### Server Endpoints

An MCP service endpoint is the network address and communication interface (usually a URL) of the MCP server that an AI application (the Host for the MCP client) uses to establish a secure, standardized connection. It is the point of contact for the LLM to request context, call a tool, or access a resource. Google MCP endpoints can be global or regional.

The Policy Troubleshooter API MCP server has the following global MCP endpoint:

- https://policytroubleshooter.googleapis.com/mcp

## MCP Tools

An [MCP tool](https://modelcontextprotocol.io/legacy/concepts/tools) is a function or executable capability that an MCP server exposes to a LLM or AI application to perform an action in the real world.

### Tools

The policytroubleshooter.googleapis.com MCP server has the following tools:

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
<td><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access"><code>troubleshoot_access</code></a></td>
<td><p>Analyzes Google Cloud IAM policies to diagnose why a principal has or does not have a specific permission on a resource. This tool examines allow policies, deny policies, and principal access boundary (PAB) policies that impact the principal's access.</p>
<p>Use this tool when a user or service account is unexpectedly denied access to a Google Cloud resource, or to verify that a principal has been granted a specific permission. Do not use this tool for troubleshooting Cloud Storage Access Control Lists (ACLs). For diagnosing VPC Service Controls violations, use the VPC Service Controls violation analyzer ( <a href="https://docs.cloud.google.com/vpc-service-controls/docs/violation-analyzer">https://docs.cloud.google.com/vpc-service-controls/docs/violation-analyzer</a> ) instead.</p>
<p>This tool requires the following parameters:</p>
<ul>
<li><code>principal</code> (string): The email address of the principal (Google Account or service account) whose access you want to check. Only one principal can be specified per request. Group principals are not supported.</li>
<li><code>full_resource_name</code> (string): The full resource name of the Google Cloud resource, in the format described by <a href="https://cloud.google.com/iam/docs/full-resource-names">https://cloud.google.com/iam/docs/full-resource-names</a> . For example, <code>//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance</code> .</li>
<li><code>permission</code> (string): The IAM permission to check for. For example, <code>storage.buckets.get</code> . Do not pass roles, always pass a single permission.</li>
</ul>
<p>The tool returns an explanation of how the applicable IAM policies affect the final access state.</p></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_iam_error_id"><code>troubleshoot_iam_error_id</code></a></td>
<td><p>Checks the access request associated with the error identifier and explains why the access is blocked by IAM policies.</p>
<p>If the error ID is not found by the backend, retry using an exponential backoff strategy. Start with an initial delay of <code>1m</code> , then retry. If the error ID is not found, double the delay time for each retry attempt (for example, <code>2m</code> , <code>4m</code> , <code>8m</code> , etc.). If the total duration from the first attempt exceeds <code>60 minutes</code> , terminate the process. Assume that the backend will not be able to provide an explanation for the error. It is possible that troubleshooting for this specific error ID is not supported or there is an issue on the backend.</p>
<p>If you are an agent that does not have the capability to wait or understand time, do not retry. Instead, return an error stating that waiting is required to retry finding the error ID, but your environment does not support waiting or tracking time.</p></td>
</tr>
</tbody>
</table>

### Get MCP tool specifications

To get the MCP tool specifications for all tools in an MCP server, use the `tools/list` method. The following example demonstrates how to use `curl` to list all tools and their specifications currently available within the MCP server.

**Curl Request**

```
curl --location 'https://policytroubleshooter.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
    "method": "tools/list",
    "jsonrpc": "2.0",
    "id": 1
}'
```
