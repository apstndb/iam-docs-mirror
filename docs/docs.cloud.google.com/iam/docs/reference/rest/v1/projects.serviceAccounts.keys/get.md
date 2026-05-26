---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get
title: 'Method: projects.serviceAccounts.keys.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.aspect)
  - [ServiceAccountPublicKeyType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#ServiceAccountPublicKeyType)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#try-it)

Gets a `  ServiceAccountKey  ` .

### HTTP request

`GET https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*/keys/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the service account key.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key `projects/-/serviceAccounts/fake@example.com/keys/fake-key` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.serviceAccountKeys.get`

### Query parameters

Parameters

`publicKeyType`

` enum ( ServiceAccountPublicKeyType  ` )

Optional. The output format of the public key. The default is `TYPE_NONE` , which means that the public key is not returned.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ServiceAccountKey  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## ServiceAccountPublicKeyType

Supported public key output formats.

Enums

`TYPE_NONE`

Do not return the public key.

`TYPE_X509_PEM_FILE`

X509 PEM format.

`TYPE_RAW_PUBLIC_KEY`

raw public key.
