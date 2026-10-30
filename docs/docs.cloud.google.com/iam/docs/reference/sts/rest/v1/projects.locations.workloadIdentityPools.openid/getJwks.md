---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks
title: 'Method: projects.locations.workloadIdentityPools.openid.getJwks'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks#body.response_body)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/projects.locations.workloadIdentityPools.openid/getJwks#try-it)

Fetches the signing keys for an agentic or managed workload identity pool and returns them in JWK Set format, defined in [RFC 7517](https://tools.ietf.org/html/rfc7517) . For now, only agentic system pools are supported.

**Preview**

This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products#product-launch-stages) .

### HTTP request

Choose an endpoint:

global africa-south1 asia-east1 asia-east2 asia-northeast1 asia-northeast2 asia-northeast3 asia-south1 asia-south2 asia-southeast1 asia-southeast2 asia-southeast3 asia-southeast4 australia-southeast1 australia-southeast2 europe-central2 europe-north1 europe-north2 europe-southwest1 europe-west1 europe-west10 europe-west12 europe-west15 europe-west2 europe-west3 europe-west4 europe-west6 europe-west8 europe-west9 me-central1 me-central2 me-west1 northamerica-northeast1 northamerica-northeast2 northamerica-south1 southamerica-east1 southamerica-west1 us-central1 us-central2 us-east1 us-east4 us-east5 us-east7 us-south1 us-west1 us-west2 us-west3 us-west4 us-west8

  
`GET https://sts.googleapis.com/v1/{name=projects/*/locations/*/workloadIdentityPools/*}/openid/jwks`

The URLs use [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`     | `string` Required. The name of the pool whose JWKs need to be retrieved. Format: 'organizations/{ORGANIZATION_NUMBER}/locations/global/workloadIdentityPools/{POOL_ID}' 'projects/{PROJECT_NUMBER}/locations/global/workloadIdentityPools/{POOL_ID}' Example(s): 'organizations/1234/locations/global/workloadIdentityPools/agents.global.org-1234.system.id.goog' 'projects/12345678/locations/global/workloadIdentityPools/agents.global.proj-12345678.system.id.goog' |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Jwks`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/Jwks) .
