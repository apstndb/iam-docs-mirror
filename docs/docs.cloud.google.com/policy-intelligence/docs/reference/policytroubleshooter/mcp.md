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

MCP Tools

`  troubleshoot_access  `

Analyzes Google Cloud IAM policies to diagnose why a principal has or does not have a specific permission on a resource. This tool examines allow policies, deny policies, and principal access boundary (PAB) policies that impact the principal's access.

Use this tool when a user or service account is unexpectedly denied access to a Google Cloud resource, or to verify that a principal has been granted a specific permission. Do not use this tool for troubleshooting Cloud Storage Access Control Lists (ACLs). For diagnosing VPC Service Controls violations, use the VPC Service Controls violation analyzer ( <https://docs.cloud.google.com/vpc-service-controls/docs/violation-analyzer> ) instead.

This tool requires the following parameters:

  - `principal` (string): The email address of the principal (Google Account or service account) whose access you want to check. Only one principal can be specified per request. Group principals are not supported.
  - `full_resource_name` (string): The full resource name of the Google Cloud resource, in the format described by <https://cloud.google.com/iam/docs/full-resource-names> . For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .
  - `permission` (string): The IAM permission to check for. For example, `storage.buckets.get` . Do not pass roles, always pass a single permission.

The tool returns an explanation of how the applicable IAM policies affect the final access state.

`  troubleshoot_iam_error_id  `

Checks the access request associated with the error identifier and explains why the access is blocked by IAM policies.

If the error ID is not found by the backend, retry using an exponential backoff strategy. Start with an initial delay of `1m` , then retry. If the error ID is not found, double the delay time for each retry attempt (for example, `2m` , `4m` , `8m` , etc.). If the total duration from the first attempt exceeds `60 minutes` , terminate the process. Assume that the backend will not be able to provide an explanation for the error. It is possible that troubleshooting for this specific error ID is not supported or there is an issue on the backend.

If you are an agent that does not have the capability to wait or understand time, do not retry. Instead, return an error stating that waiting is required to retry finding the error ID, but your environment does not support waiting or tracking time.

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
<td><pre dir="ltr" data-is-upgraded="" data-syntax="Bash" translate="no"><code>                      
curl --location &#39;https://policytroubleshooter.googleapis.com/mcp&#39; \
--header &#39;content-type: application/json&#39; \
--header &#39;accept: application/json, text/event-stream&#39; \
--data &#39;{
    &quot;method&quot;: &quot;tools/list&quot;,
    &quot;jsonrpc&quot;: &quot;2.0&quot;,
    &quot;id&quot;: 1
}&#39;
                    </code></pre></td>
</tr>
</tbody>
</table>
