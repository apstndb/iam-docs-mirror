---
name: documents/docs.cloud.google.com/iam/docs/auth-manager-overview
uri: https://docs.cloud.google.com/iam/docs/auth-manager-overview
title: Agent Identity auth manager overview
description: Centralized outbound credentials vault and authentication broker for generative AI agents.
data_source: docs.cloud.google.com
---

> **Preview**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

When generative AI agents interact with external tools, APIs, or services (such as BigQuery, Jira, GitHub, or Google Maps), they require a secure mechanism to authenticate outbound requests. The Agent Identity auth manager (auth manager) provides this by acting as a centralized credentials vault and authentication broker that simplifies outbound tool authentication.

## Benefits of using the auth manager

The auth manager provides the following benefits for agent development:

  - **Centralized credential vault** : Stores API keys, OAuth client secrets, and user tokens in a Google-managed vault, helping to avoid hardcoded secrets and custom database storage.
  - **Automated OAuth 2.0** : Handles multi-step OAuth 2.0 flows, such as user consent, authorization code exchange, and token refreshes, without custom backend code.
  - **Seamless ADK integration** : Integrates natively with the Agent Development Kit (ADK) to retrieve and inject outbound authentication headers, such as `Authorization` or `X-Goog-Api-Key` , into tool and Model Context Protocol (MCP) server invocations.
  - **Granular SPIFFE ID access control** : Uses SPIFFE-based agent identities to define precise Identity and Access Management (IAM) policies, helping to ensure only authorized agent principals and developers can access specific auth providers.

## How the auth manager works

The auth manager acts as a credentials vault between your Agent Runtime on Gemini Enterprise Agent Platform environment and external service endpoints.

When an agent calls an external tool, the ADK intercepts the tool execution, requests the appropriate credential from the auth manager vault, and attaches the required authentication headers before dispatching the request to the target API.

The following flow diagram illustrates the high-level architecture and credential retrieval lifecycle: ![Outbound credentials retrieval architecture diagram.](https://docs.cloud.google.com/static/iam/img/auth-manager-arch.svg)

1.  The end user triggers an event or prompt that requires outbound tool authentication.
2.  The deployed agent (using the ADK) transparently intercepts the tool request and queries the secure auth manager vault.
3.  The auth manager returns the secure credential (API key or OAuth token) to the agent.
4.  The agent invokes the external API or tool with the attached credential.
5.  The third-party service validates the credential and returns the requested data to the agent.
6.  The agent uses the returned data to generate and deliver the final response to the user.

## What's next

  - [Authenticate using API key with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-api-key-v2)
  - [Authenticate using 2-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-2lo-v2)
  - [Authenticate using 3-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2)
  - [Agent Identity overview](https://docs.cloud.google.com/iam/docs/agent-identity-overview)
  - [Manage Agent Identity auth providers](https://docs.cloud.google.com/iam/docs/manage-auth-providers-v2)
