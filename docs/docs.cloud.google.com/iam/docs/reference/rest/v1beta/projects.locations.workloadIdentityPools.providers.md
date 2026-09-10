---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers
title: 'REST Resource: projects.locations.workloadIdentityPools.providers'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: WorkloadIdentityPoolProvider](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider.SCHEMA_REPRESENTATION)
  - [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#State)
  - [Aws](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#Aws)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#Aws.SCHEMA_REPRESENTATION)
  - [Oidc](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#Oidc)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#Oidc.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1beta/projects.locations.workloadIdentityPools.providers#METHODS_SUMMARY)

## Resource: WorkloadIdentityPoolProvider

A configuration for an external identity provider.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;displayName&quot;: string,&quot;description&quot;: string,&quot;state&quot;: enum (State),&quot;disabled&quot;: boolean,&quot;attributeMapping&quot;: {string: string,...},&quot;attributeCondition&quot;: string,&quot;expireTime&quot;: string,// Union field provider_config can be only one of the following:&quot;aws&quot;: {object (Aws)},&quot;oidc&quot;: {object (Oidc)}// End of list of possible types for union field provider_config.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. The resource name of the provider.

`displayName`

`string`

A display name for the provider. Cannot exceed 32 characters.

`description`

`string`

A description for the provider. Cannot exceed 256 characters.

`state`

` enum ( State  ` )

Output only. The state of the provider.

`disabled`

`boolean`

Whether the provider is disabled. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.

`attributeMapping`

`map (key: string, value: string)`

Maps attributes from authentication credentials issued by an external identity provider to Google Cloud attributes, such as `subject` and `segment` .

Each key must be a string specifying the Google Cloud IAM attribute to map to.

The following keys are supported:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. Cannot exceed 127 bytes.

  - `google.groups` : Groups the external identity belongs to. You can grant groups access to resources using an IAM `principalSet` binding; access applies to all members of the group.

You can also provide custom attributes by specifying `attribute.{custom_attribute}` , where `{custom_attribute}` is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters \[a-z0-9\_\].

You can reference these attributes in IAM policies to define fine-grained access for a workload to Google Cloud resources. For example:

  - `google.subject` : `principal://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/subject/{value}`

  - `google.groups` : `principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/group/{value}`

  - `attribute.{custom_attribute}` : `principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/attribute.{custom_attribute}/{value}`

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.

You can use the `assertion` keyword in the expression to access a JSON representation of the authentication credential issued by the provider.

The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 8KB.

For AWS providers, if no attribute mapping is defined, the following default mapping applies:

    {
      "google.subject":"assertion.arn",
      "attribute.aws_role":
        "assertion.arn.contains('assumed-role')"
        " ? assertion.arn.extract('{account_arn}assumed-role/')"
        "   + 'assumed-role/'"
        "   + assertion.arn.extract('assumed-role/{role_name}/')"
        " : assertion.arn",
    }

If any custom attribute mappings are defined, they must include a mapping to the `google.subject` attribute.

For OIDC providers, you must supply a custom mapping, which must include the `google.subject` attribute. For example, the following maps the `sub` claim of the incoming credential to the `subject` attribute on a Google token:

    {"google.subject": "assertion.sub"}

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`attributeCondition`

`string`

[A Common Expression Language](https://opensource.google/projects/cel) expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.

The expression must output a boolean representing whether to allow the federation.

The following keywords may be referenced in the expressions:

  - `assertion` : JSON representing the authentication credential issued by the provider.
  - `google` : The Google attributes mapped from the assertion in the `attribute_mappings` .
  - `attribute` : The custom attributes mapped from the assertion in the `attribute_mappings` .

The maximum length of the condition expression is 4096 characters. If unspecified, all valid authentication credentials are accepted.

The following example shows how to only allow credentials with a mapped `google.groups` value of `admins` :

    "'admins' in google.groups"

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the workload identity pool provider will be permanently purged and cannot be recovered.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

Union field `provider_config` . Identity provider configuration types. `provider_config` can be only one of the following:

`aws`

` object ( Aws  ` )

An Amazon Web Services identity provider.

`oidc`

` object ( Oidc  ` )

An OpenId Connect 1.0 identity provider.

## State

The current state of the provider.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The provider is active, and may be used to validate authentication credentials.

`DELETED`

The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using `  providers.undelete  ` .

You cannot reuse the ID of a soft-deleted provider until it is permanently deleted.

## Aws

Represents an Amazon Web Services identity provider.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;accountId&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accountId`

`string`

Required. The AWS account ID.

## Oidc

Represents an OpenId Connect 1.0 identity provider.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;issuerUri&quot;: string,
  &quot;allowedAudiences&quot;: [
    string
  ],
  &quot;jwksJson&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`issuerUri`

`string`

Required. The OIDC issuer URL. Must be an HTTPS endpoint.

`allowedAudiences[]`

`string`

Acceptable values for the `aud` field (audience) in the OIDC token. Token exchange requests are rejected if the token audience does not match one of the configured values. Each audience may be at most 256 characters. A maximum of 10 audiences may be configured.

If this list is empty, the OIDC token audience must be equal to the full canonical resource name of the WorkloadIdentityPoolProvider, with or without the HTTPS prefix. For example:

    //iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>
    https://iam.googleapis.com/projects/<project-number>/locations/<location>/workloadIdentityPools/<pool-id>/providers/<provider-id>

`jwksJson`

`string`

Optional. OIDC JWKs in JSON String format. For details on definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, then we use the `jwksUri` from the discovery document fetched from the .well-known path for the `issuerUri` . Currently, RSA and EC asymmetric keys are supported. The JWK must use following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] }

## Methods

### `            create           `

Creates a new `  WorkloadIdentityPoolProvider  ` in a `  WorkloadIdentityPool  ` .

### `            delete           `

Deletes a `  WorkloadIdentityPoolProvider  ` .

### `            get           `

Gets an individual `  WorkloadIdentityPoolProvider  ` .

### `            list           `

Lists all non-deleted `  WorkloadIdentityPoolProvider  ` s in a `  WorkloadIdentityPool  ` .

### `            patch           `

Updates an existing `  WorkloadIdentityPoolProvider  ` .

### `            undelete           `

Undeletes a `  WorkloadIdentityPoolProvider  ` , as long as it was deleted fewer than 30 days ago.
