---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest
title: Security Token Service API
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

The Security Token Service exchanges Google or third-party credentials for a short-lived access token to Google Cloud resources.

- [REST Resource: v1beta](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1beta)
- [REST Resource: v1](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1)
- [REST Resource: v1.organizations.locations.workloadIdentityPools.openid](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1.organizations.locations.workloadIdentityPools.openid)
- [REST Resource: v1.organizations.locations.workloadIdentityPools.well-known](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1.organizations.locations.workloadIdentityPools.well-known)
- [REST Resource: v1.projects.locations.workloadIdentityPools.openid](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1.projects.locations.workloadIdentityPools.openid)
- [REST Resource: v1.projects.locations.workloadIdentityPools.well-known](https://docs.cloud.google.com/iam/docs/reference/sts/rest#v1.projects.locations.workloadIdentityPools.well-known)

## Service: sts.googleapis.com

### Discovery document

A [Discovery Document](https://developers.google.com/discovery/v1/reference/apis) is a machine-readable specification for describing and consuming REST APIs. It is used to build client libraries, IDE plugins, and other tools that interact with Google APIs. One service may provide multiple discovery documents. This service provides the following discovery documents:

- <https://sts.googleapis.com/$discovery/rest?version=v1>
- <https://sts.googleapis.com/$discovery/rest?version=v1beta>

### Service endpoint

A [service endpoint](https://cloud.google.com/apis/design/glossary#api_service_endpoint) is a base URL that specifies the network address of an API service. One service might have multiple service endpoints. This service has the following service endpoint and all URIs below are relative to this service endpoint:

- `https://sts.googleapis.com`

### Regional service endpoint

A regional service endpoint is a base URL that specifies the network address of an API service in a single region. A service that is available in multiple regions might have multiple regional endpoints. Select a location to see its regional service endpoint for this service.

  

`https://sts.googleapis.com`

## REST Resource: [v1beta](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token)

| Methods                                                                                    |                                                                                  |
|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [`token`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token) | `POST /v1beta/token` Exchanges a credential for a Google OAuth 2.0 access token. |

## REST Resource: [v1](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token)

| Methods                                                                                |                                                                              |
|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| [`token`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token) | `POST /v1/token` Exchanges a credential for a Google OAuth 2.0 access token. |

## REST Resource: [v1.organizations.locations.workloadIdentityPools.openid](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/organizations.locations.workloadIdentityPools.openid)

| Methods                                                                                                                                |                                                                                                                                                                                                                                                             |
|----------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`getJwks`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/organizations.locations.workloadIdentityPools.openid/getJwks) | `GET /v1/{name=organizations/*/locations/*/workloadIdentityPools/*}/openid/jwks` Fetches the signing keys for an agentic or managed workload identity pool and returns them in JWK Set format, defined in [RFC 7517](https://tools.ietf.org/html/rfc7517) . |

## REST Resource: [v1.organizations.locations.workloadIdentityPools.well-known](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/organizations.locations.workloadIdentityPools.well-known)

| Methods                                                                                                                                                                    |                                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`getOpenid-configuration`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/organizations.locations.workloadIdentityPools.well-known/getOpenid-configuration) | `GET /v1/{name=organizations/*/locations/*/workloadIdentityPools/*}/.well-known/openid-configuration` Gets the OIDC provider configuration for an agentic or managed workload identity pool following [the OIDC 1.0 discovery specification](https://openid.net/specs/openid-connect-discovery-1_0.html#ProviderConfigurationResponse) . |

## REST Resource: [v1.projects.locations.workloadIdentityPools.openid](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid)

| Methods                                                                                                                           |                                                                                                                                                                                                                                                        |
|-----------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`getJwks`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks) | `GET /v1/{name=projects/*/locations/*/workloadIdentityPools/*}/openid/jwks` Fetches the signing keys for an agentic or managed workload identity pool and returns them in JWK Set format, defined in [RFC 7517](https://tools.ietf.org/html/rfc7517) . |

## REST Resource: [v1.projects.locations.workloadIdentityPools.well-known](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.well-known)

| Methods                                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`getOpenid-configuration`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.well-known/getOpenid-configuration) | `GET /v1/{name=projects/*/locations/*/workloadIdentityPools/*}/.well-known/openid-configuration` Gets the OIDC provider configuration for an agentic or managed workload identity pool following [the OIDC 1.0 discovery specification](https://openid.net/specs/openid-connect-discovery-1_0.html#ProviderConfigurationResponse) . |
