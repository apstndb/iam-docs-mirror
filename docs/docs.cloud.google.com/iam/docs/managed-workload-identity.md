---
name: documents/docs.cloud.google.com/iam/docs/managed-workload-identity
uri: https://docs.cloud.google.com/iam/docs/managed-workload-identity
title: Managed workload identities overview
description: Discover Identity and Access Management (IAM) managed workload identities. Bind attested identities to Google Kubernetes Engine (GKE) and Compute Engine workloads for secure authentication using SPIFFE, identity pools, and attestation policies.
data_source: docs.cloud.google.com
---

Managed workload identities lets you bind strongly attested identities to your Google Kubernetes Engine (GKE) and Compute Engine workloads. This also includes agent identities, which are designed for agentic workloads.

Google Cloud provisions X.509 credentials and trust anchors that are issued from [Certificate Authority Service](https://docs.cloud.google.com/certificate-authority-service) . The credentials and trust anchors can be used to reliably authenticate your workload with other workloads through [mutual TLS (mTLS)](https://docs.cloud.google.com/chrome-enterprise-premium/docs/understand-mtls) authentication.

The following features are available:

  - Managed workload identities for GKE ( [Preview](https://cloud.google.com/products#product-launch-stages) )
  - Managed workload identities for Compute Engine ( [Preview](https://cloud.google.com/products#product-launch-stages) )
  - [Request access to the managed workload identities for Compute Engine](https://forms.gle/KC1Lq77gMn3kTtWDA) ( [Preview](https://cloud.google.com/products#product-launch-stages) )
  - Agent identities

## SPIFFE interoperability

To enable interoperability across dynamic and heterogeneous environments, managed workload identities is based on [Secure Production Identity Framework For Everyone (SPIFFE)](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/) . SPIFFE defines a framework and set of standards for identifying, authenticating, and securing communications between workloads. SPIFFE workloads are identified by a unique SPIFFE ID. In Google Cloud, a SPIFFE ID has the following formats:

  - Compute Engine workloads:
    
    ` spiffe:// POOL_ID .global. PROJECT_NUMBER .workload.id.goog/ns/ NAMESPACE_ID /sa/ MANAGED_IDENTITY_ID  `

  - GKE workloads:
    
    ` spiffe:// PROJECT_ID .svc.id.goog/ns/ KUBERNETES_NAMESPACE /sa/ KUBERNETES_SERVICE_ACCOUNT  `

  - Agent identity workloads:
    
    ` spiffe://agents.global.org- ORGANIZATION_ID .system.id.goog/resources/aiplatform/projects/ PROJECT_NUMBER /locations/ LOCATION /reasoningEngines/ AGENT_NAME  `

## Resource hierarchy

This section describes managed workload identity resources.

### Workload identity pools

Managed workload identities are defined within a *workload identity pool* , which acts as a trust boundary for all identities within the pool. The workload identity pool forms the trust domain component of the managed workload identity's SPIFFE identifier. We recommend creating a new pool for each logical environment in your organization, such as development, staging, or production.

### Namespaces

Within a workload identity pool, managed workload identities are organized into administrative boundaries called *namespaces* . Namespaces help you organize and grant access to related workload identities.

### Attestation policies

Managed workload identity for Compute Engine requires that you configure *attestation policies* .

Managed workload identity for GKE manages attestation policies for you.

Workload attestation policies let you define which workload can be issued a credential for a managed workload identity based on the workload's verifiable attributes, such as project ID or resource name. A workload attestation policy ensures that only trusted workloads can use the managed identity.

## What's next

  - [Configure managed workload identity authentication for Compute Engine](https://docs.cloud.google.com/iam/docs/create-managed-workload-identities) .

  - [Configure managed workload identity authentication for GKE](https://docs.cloud.google.com/iam/docs/create-managed-workload-identities-gke) .

  - Learn more about [using managed workload identities with Compute Engine workloads](https://docs.cloud.google.com/compute/docs/access/authenticate-workloads-over-mtls) .

  - Learn more about [using agent identity with Vertex AI Agent Engine](https://docs.cloud.google.com/gemini-enterprise-agent-platform/scale/runtime/agent-identity) .
