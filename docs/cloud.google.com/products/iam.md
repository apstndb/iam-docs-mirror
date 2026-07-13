---
name: documents/cloud.google.com/products/iam
uri: https://cloud.google.com/products/iam
title: Identity and Access Management (IAM)
description: Identity and Access Management (IAM) gives admins fine-grained access control and visibility for centrally managing enterprise cloud resources
data_source: cloud.google.com
---

# Identity and Access Management (IAM)

## Unified security and governance for users and agents

Reimagine security with Google Cloud IAM, the unified foundation for governing both human and AI agent access at scale.

[Go to console](https://console.cloud.google.com/iam-admin/?tutorial=iam--quickstart)

[Video: Agentic IAM](https://www.youtube.com/watch?v=DQX81oJfsTE)

Read the [quick walkthrough](https://cloud.google.com/iam/docs/grant-role-console) to begin IAM role setup in the console

### Benefits

  - [](https://cloud.google.com/products/iam#proof-of-concept)
    
    Safeguard identity across humans, workloads, and AI agents

  - [](https://cloud.google.com/products/iam#features)
    
    Enforce Zero Trust with granular access and agent guardrails

  - [](https://cloud.google.com/products/iam#common-uses)
    
    Streamline governance with automated permission management

-----

  - [](https://cloud.google.com/blog/products/identity-security/whats-new-in-iam-security-governance-and-runtime-defense)
    
    What's new in Google Cloud IAM? Read the Next 2026 blog
    
    7 minute read

Features

### Centralized identity across agents, users, and workloads

Consolidate identity for your entire ecosystem: Enable your workforce to securely sign in using SSO and MFA with Google [Cloud Identity](https://docs.cloud.google.com/identity/docs) or syncless [Workforce Identity Federation](https://cloud.google.com/workforce-identity-federation) with your own identity provider. Provide [first-class cryptographic identities unique to your agents](https://docs.cloud.google.com/iam/docs/agent-identity-overview) and applications allowing them to securely authenticate both as themselves and [on behalf of the end user](https://docs.cloud.google.com/iam/docs/agent-identity-overview#agent-auth-manager).

[](https://www.youtube.com/watch?v=gMbMv91g0Zg&t=5s)

![What's next in IAM: Security, goernance, and Runtime defense for AI agents](https://www.gstatic.com/bricks/image/dc5a9da2-07f2-4fd0-9f32-ee6c2d2624e4.png)

What's next in IAM? See updates from Next 2026

### Gemini-powered roles and Policy Intelligence

Simplify setup with Gemini for intelligent optimization. Eliminate guesswork by using the [Gemini Role Picker](https://cloud.google.com/iam/docs/role-picker-gemini) to generate least-privilege roles from natural language. Use the broader [Policy Intelligence](https://cloud.google.com/policy-intelligence) suite to see what your users and agents have access to with [Policy Analyzer](https://docs.cloud.google.com/policy-intelligence/docs/policy-analyzer-overview), then automatically detect and remove excessive permissions, troubleshoot access issues, and ensure your policies remain secure and optimized over time.

[](https://www.youtube.com/watch?v=I6aM-ku_ris&t=1s)

![](https://img.youtube.com/vi/I6aM-ku_ris/hqdefault.jpg)

Simplify permissions management with Gemini

### Streamlined deployment of security and governance

Establish a secure foundation for your workforce, workloads, and AI agents. Use [Organization Policies](https://cloud.google.com/resource-manager/docs/organization-policy/overview) to create a centralized hierarchy for all resources. Define a security baseline with [custom policies](https://docs.cloud.google.com/organization-policy/create-custom-constraints) that programmatically enforce guardrails, ensuring human, workload, and agent access remains compliant with corporate policies from day one.

[](https://www.youtube.com/watch?v=23cgo7dgjEE)

![](https://img.youtube.com/vi/23cgo7dgjEE/hqdefault.jpg)

Organization Policies

### Fine-grained entitlements and just-in-time access

Move beyond broad roles with precise permissions. Use [Principal Access Boundary](https://cloud.google.com/iam/docs/principal-access-boundary-policies) to down-scope agent access from full delegated user permissions. For human administrators, use [Privileged Access Manager (PAM)](https://cloud.google.com/iam/docs/pam-overview) to grant temporary, time-bound access for sensitive tasks, ensuring elevated privileges are never permanent and the "blast radius" of any identity is strictly [contained](https://www.youtube.com/watch?v=I6aM-ku_ris).

### Dynamic, context-aware access control

Enforce a comprehensive Zero Trust model with dynamic, attribute-based access. Use [Access Context Manager](https://cloud.google.com/access-context-manager/docs/overview) to create fine-grained access rules based on user identity and device context. Then, enforce these rules across your applications and Google Cloud services with [Identity-Aware Proxy (IAP)](https://cloud.google.com/iap) and [VPC Service Controls](https://cloud.google.com/vpc-service-controls) to create a secure, unified perimeter.

[](https://www.youtube.com/watch?v=TD06WkY1zLs&t=1s)

![](https://img.youtube.com/vi/TD06WkY1zLs/hqdefault.jpg)

VPC Service Controls

How It Works

### Start secure with a built-in foundation. Establish governance with custom guardrails. Assign every human and agent an Identity. Deploy defense-in-depth Access Management to dictate what they can do. Finally, evaluate Access Risk to secure the context of every session.

[View documentation](https://docs.cloud.google.com/iam/docs)

![Diagram illustrating the Google Cloud Identity and Access Management portfolio. It shows a centralized IAM foundation providing unified access governance, managed by overarching Organization Policy and Policy Intelligence tools, and supported by three core pillars: Access controls, Identity management, and Privileged access.](https://www.gstatic.com/bricks/image/78ec3e5f-9bf9-4291-b3d3-0156c263eb09.webp)

Identity and governance across users and agents

Common Uses

### Establish verifiable identity

Give every agent a unique, short-lived identity using the [SPIFFE framework](https://docs.cloud.google.com/iam/docs/managed-workload-identity) for secretless mTLS auth. [Onboard users by federating your existing identity provider](https://cloud.google.com/workforce-identity-federation). Eradicate risky keys by allowing keyless multi-cloud or on-prem authentication using [Workload identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation). Safely orchestrate OAuth flows so agents act for users without ever exposing credentials.

[Learn more about Agent Identity](https://docs.cloud.google.com/iam/docs/agent-identity-overview)

  - [](https://www.skills.google/course_templates/44)
    
    Take the course: Introduction to Cloud Identity

  - [](https://cloud.google.com/iam/docs/workforce-identity-federation)
    
    Configure Workforce Identity Federation to use single sign-on (SSO) to access Google Cloud

  - [](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/runtime/agent-identity#create-agent-identity)
    
    Read the documentation: create an agent with agent identity

![{msg desc="Alternative text for a build icon"}build{/msg}](https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/build/wght100fill1/20px.svg)

#### Tutorials, quickstarts, & labs

Give every agent a unique, short-lived identity using the [SPIFFE framework](https://docs.cloud.google.com/iam/docs/managed-workload-identity) for secretless mTLS auth. [Onboard users by federating your existing identity provider](https://cloud.google.com/workforce-identity-federation). Eradicate risky keys by allowing keyless multi-cloud or on-prem authentication using [Workload identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation). Safely orchestrate OAuth flows so agents act for users without ever exposing credentials.

[Learn more about Agent Identity](https://docs.cloud.google.com/iam/docs/agent-identity-overview)

  - [](https://www.skills.google/course_templates/44)
    
    Take the course: Introduction to Cloud Identity

  - [](https://cloud.google.com/iam/docs/workforce-identity-federation)
    
    Configure Workforce Identity Federation to use single sign-on (SSO) to access Google Cloud

  - [](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/runtime/agent-identity#create-agent-identity)
    
    Read the documentation: create an agent with agent identity

### Enforce intelligent access

Use [Gemini Role Picker](https://docs.cloud.google.com/iam/docs/role-picker-gemini) for roles from natural language. Use [IAM Recommender](https://cloud.google.com/iam/docs/recommender-overview) in SCC to remove excessive access. Use [Principal Access Boundaries](https://cloud.google.com/iam/docs/principal-access-boundary-policies) to restrict agents and [Organization Policy](https://docs.cloud.google.com/organization-policy/overview) for hierarchy-wide guardrails. Apply [IAM Conditions](https://www.google.com/search?q=https://cloud.google.com/iam/docs/conditions-overview) to enforce context-aware access based on time, device, or resource attributes.

[Start granting IAM roles in the Google Cloud Console with our QuickStart guide](https://docs.cloud.google.com/iam/docs/grant-role-console)

  - [](https://docs.cloud.google.com/iam/docs/role-picker-gemini)
    
    Get pre-defined role suggestions with Gemini

  - [](https://www.youtube.com/watch?v=Sdt-i-Q7tyA)
    
    See how to add IAM Roles and Permissions on Google Cloud

  - [](https://www.skills.google/course_templates/1515)
    
    Learn how to design secure resource hierarchies and enforce least privilege

![{msg desc="Alternative text for a build icon"}build{/msg}](https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/build/wght100fill1/20px.svg)

#### Tutorials, quickstarts, & labs

Use [Gemini Role Picker](https://docs.cloud.google.com/iam/docs/role-picker-gemini) for roles from natural language. Use [IAM Recommender](https://cloud.google.com/iam/docs/recommender-overview) in SCC to remove excessive access. Use [Principal Access Boundaries](https://cloud.google.com/iam/docs/principal-access-boundary-policies) to restrict agents and [Organization Policy](https://docs.cloud.google.com/organization-policy/overview) for hierarchy-wide guardrails. Apply [IAM Conditions](https://www.google.com/search?q=https://cloud.google.com/iam/docs/conditions-overview) to enforce context-aware access based on time, device, or resource attributes.

[Start granting IAM roles in the Google Cloud Console with our QuickStart guide](https://docs.cloud.google.com/iam/docs/grant-role-console)

  - [](https://docs.cloud.google.com/iam/docs/role-picker-gemini)
    
    Get pre-defined role suggestions with Gemini

  - [](https://www.youtube.com/watch?v=Sdt-i-Q7tyA)
    
    See how to add IAM Roles and Permissions on Google Cloud

  - [](https://www.skills.google/course_templates/1515)
    
    Learn how to design secure resource hierarchies and enforce least privilege

### Defend the agent interaction

Ringfence [Model Context Protocol (MCP) servers](https://docs.cloud.google.com/mcp/control-mcp-use-iam) and data with [VPC Service Controls](https://cloud.google.com/security/vpc-service-controls) to prevent exfiltration. Secure all agent interactions—including Agent-to-Agent (A2A) communication—by routing traffic through the [Agent Gateway](https://docs.cloud.google.com/agent-builder/agent-engine/manage/access), where [Model Armor](https://cloud.google.com/security/products/model-armor) policies block prompt injections and harmful content. Use [Security Command Center](https://cloud.google.com/security/products/security-command-center) (SCC) for centralized threat detection and AI posture management.

  - [](https://cloud.google.com/vpc-service-controls)
    
    Learn more about VPC Service Controls

  - [](https://docs.cloud.google.com/model-armor/model-armor-agent-gateway-integration)
    
    Learn more about integrating Agent Gateway with Model Armor policies

  - [](https://docs.cloud.google.com/access-context-manager/docs/securing-console-and-apis)
    
    Setup context-aware access

![book](https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/book/wght100fill1/20px.svg)

#### Learning resources

Ringfence [Model Context Protocol (MCP) servers](https://docs.cloud.google.com/mcp/control-mcp-use-iam) and data with [VPC Service Controls](https://cloud.google.com/security/vpc-service-controls) to prevent exfiltration. Secure all agent interactions—including Agent-to-Agent (A2A) communication—by routing traffic through the [Agent Gateway](https://docs.cloud.google.com/agent-builder/agent-engine/manage/access), where [Model Armor](https://cloud.google.com/security/products/model-armor) policies block prompt injections and harmful content. Use [Security Command Center](https://cloud.google.com/security/products/security-command-center) (SCC) for centralized threat detection and AI posture management.

  - [](https://cloud.google.com/vpc-service-controls)
    
    Learn more about VPC Service Controls

  - [](https://docs.cloud.google.com/model-armor/model-armor-agent-gateway-integration)
    
    Learn more about integrating Agent Gateway with Model Armor policies

  - [](https://docs.cloud.google.com/access-context-manager/docs/securing-console-and-apis)
    
    Setup context-aware access

Pricing

Included in the Google Cloud Console

All use of Identity and Access Management API is free of charge

Package

Description

What's included

Google Cloud IAM

  - Built-in identity and access management for all your Google Cloud resources.

  

  - Centralized organization policies
  - Unlimited custom roles and permissions
  - Workforce and Workload Identity Federation
  - IAM recommender insights
  - No additional cost per user or identity

  

Included in the Google Cloud Console

All use of Identity and Access Management API is free of charge

Google Cloud IAM

Description

  - Built-in identity and access management for all your Google Cloud resources.

  

What's included

  - Centralized organization policies
  - Unlimited custom roles and permissions
  - Workforce and Workload Identity Federation
  - IAM recommender insights
  - No additional cost per user or identity

  

### Start granting IAM roles in Google Cloud today

Google Cloud pricing details

[Learn more about Google Cloud pricing](https://cloud.google.com/pricing)

### Identity and Access Management pricing details

Identity and Access Management pricing details

[Learn more about Identity and Access Management API pricing](https://cloud.google.com/iam/pricing)

### See it in action: the latest in IAM

### Build secure access for agents and users

[Watch the video](https://www.youtube.com/watch?v=DQX81oJfsTE)

### Strict guardrails: Organization Policies

[Watch the video](https://youtu.be/EcWW-cKKhTo?si=lBSo7AvtSt3oJQlr)

![](https://www.gstatic.com/cgc/product-v3/proof-of-concept-blue.svg)

### Agent identity for secure AI innovation

[Watch the Next 2026 session](https://www.youtube.com/watch?v=7l-uAjO8hNE)

![](https://www.gstatic.com/cgc/product-v3/proof-of-concept-yellow.svg)

### Design your resource hierarchy and choose the right federation method

[Read the Architecture Center guides](https://cloud.google.com/architecture/security-iam)

![](https://www.gstatic.com/cgc/product-v3/proof-of-concept-green.svg)

### Technical guide: using service accounts securely

[View IAM best practices](https://docs.cloud.google.com/iam/docs/best-practices-service-accounts)
