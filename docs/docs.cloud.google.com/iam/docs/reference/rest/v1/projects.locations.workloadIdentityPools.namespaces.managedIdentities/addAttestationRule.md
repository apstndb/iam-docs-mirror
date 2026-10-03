---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule
title: 'Method: projects.locations.workloadIdentityPools.namespaces.managedIdentities.addAttestationRule'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/addAttestationRule#try-it)

Add an [`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule) on a [`WorkloadIdentityPoolManagedIdentity`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#WorkloadIdentityPoolManagedIdentity) .

The total attestation rules after addition must not exceed 50.

### HTTP request

`POST https://iam.googleapis.com/v1/{resource=projects/*/locations/*/workloadIdentityPools/*/namespaces/*/managedIdentities/*}:addAttestationRule`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                   |
|------------|-------------------------------------------------------------------------------------------------------------------|
| `resource` | `string` Required. The resource name of the managed identity or namespace resource to add an attestation rule to. |

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "attestationRule": {
    object (AttestationRule)
  }
}
```

| Fields            |                                                                                                                                                          |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| `attestationRule` | `object ( `[`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule)` )` Required. The attestation rule to be added. |

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `resource` resource:

- `CALLBACK`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
