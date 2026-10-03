---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules
title: 'Method: projects.locations.workloadIdentityPools.namespaces.managedIdentities.setAttestationRules'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities/setAttestationRules#try-it)

Set all [`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule) on a [`WorkloadIdentityPoolManagedIdentity`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces.managedIdentities#WorkloadIdentityPoolManagedIdentity) .

A maximum of 50 AttestationRules can be set.

### HTTP request

`POST https://iam.googleapis.com/v1/{resource=projects/*/locations/*/workloadIdentityPools/*/namespaces/*/managedIdentities/*}:setAttestationRules`

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
  "attestationRules": [
    {
      object (AttestationRule)
    }
  ]
}
```

| Fields               |                                                                                                                                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `attestationRules[]` | `object ( `[`AttestationRule`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/AttestationRule)` )` Required. The attestation rules to be set. At most 50 attestation rules can be set. |

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
