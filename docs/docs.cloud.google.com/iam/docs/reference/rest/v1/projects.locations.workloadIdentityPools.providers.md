---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers
title: 'REST Resource: projects.locations.workloadIdentityPools.providers'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkloadIdentityPoolProvider](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#State)
- [Aws](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Aws)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Aws.SCHEMA_REPRESENTATION)
- [Oidc](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Oidc)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Oidc.SCHEMA_REPRESENTATION)
- [Saml](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Saml)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Saml.SCHEMA_REPRESENTATION)
- [X509](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#X509)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#X509.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#METHODS_SUMMARY)

## Resource: WorkloadIdentityPoolProvider

A configuration for an external identity provider.

**JSON representation**

```
{
  "name": string,
  "displayName": string,
  "description": string,
  "state": enum (State),
  "disabled": boolean,
  "attributeMapping": {
    string: string,
    ...
  },
  "attributeCondition": string,
  "expireTime": string,

  // Union field provider_config can be only one of the following:
  "aws": {
    object (Aws)
  },
  "oidc": {
    object (Oidc)
  },
  "saml": {
    object (Saml)
  },
  "x509": {
    object (X509)
  }
  // End of list of possible types for union field provider_config.
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Output only. The resource name of the provider.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. A display name for the provider. Cannot exceed 32 characters.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. A description for the provider. Cannot exceed 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#State"><code>State</code></a><code> )</code></p>
<p>Output only. The state of the provider.</p></td>
</tr>
<tr class="odd">
<td><code>disabled</code></td>
<td><p><code>boolean</code></p>
<p>Optional. Whether the provider is disabled. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.</p></td>
</tr>
<tr class="even">
<td><code>attributeMapping</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. Maps attributes from authentication credentials issued by an external identity provider to Google Cloud attributes, such as <code>subject</code> and <code>segment</code> .</p>
<p>Each key must be a string specifying the Google Cloud IAM attribute to map to.</p>
<p>The following keys are supported:</p>
<ul>
<li><p><code>google.subject</code> : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. Cannot exceed 127 bytes.</p></li>
<li><p><code>google.groups</code> : Groups the external identity belongs to. You can grant groups access to resources using an IAM <code>principalSet</code> binding; access applies to all members of the group.</p></li>
</ul>
<p>You can also provide custom attributes by specifying <code>attribute.{custom_attribute}</code> , where <code>{custom_attribute}</code> is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters [a-z0-9_].</p>
<p>You can reference these attributes in IAM policies to define fine-grained access for a workload to Google Cloud resources. For example:</p>
<ul>
<li><p><code>google.subject</code> : <code>principal://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/subject/{value}</code></p></li>
<li><p><code>google.groups</code> : <code>principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/group/{value}</code></p></li>
<li><p><code>attribute.{custom_attribute}</code> : <code>principalSet://iam.googleapis.com/projects/{project}/locations/{location}/workloadIdentityPools/{pool}/attribute.{custom_attribute}/{value}</code></p></li>
</ul>
<p>Each value must be a <a href="https://opensource.google/projects/cel">Common Expression Language</a> function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.</p>
<p>You can use the <code>assertion</code> keyword in the expression to access a JSON representation of the authentication credential issued by the provider.</p>
<p>The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 8KB.</p>
<p>For AWS providers, if no attribute mapping is defined, the following default mapping applies:</p>
<pre data-fenced=""><code>{
  &quot;google.subject&quot;:&quot;assertion.arn&quot;,
  &quot;attribute.aws_role&quot;:
    &quot;assertion.arn.contains(&#39;assumed-role&#39;)&quot;
    &quot; ? assertion.arn.extract(&#39;{account_arn}assumed-role/&#39;)&quot;
    &quot;   + &#39;assumed-role/&#39;&quot;
    &quot;   + assertion.arn.extract(&#39;assumed-role/{role_name}/&#39;)&quot;
    &quot; : assertion.arn&quot;,
}</code></pre>
<p>If any custom attribute mappings are defined, they must include a mapping to the <code>google.subject</code> attribute.</p>
<p>For OIDC providers, you must supply a custom mapping, which must include the <code>google.subject</code> attribute. For example, the following maps the <code>sub</code> claim of the incoming credential to the <code>subject</code> attribute on a Google token:</p>
<pre data-fenced=""><code>{&quot;google.subject&quot;: &quot;assertion.sub&quot;}</code></pre>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>attributeCondition</code></td>
<td><p><code>string</code></p>
<p>Optional. <a href="https://opensource.google/projects/cel">A Common Expression Language</a> expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.</p>
<p>The expression must output a boolean representing whether to allow the federation.</p>
<p>The following keywords may be referenced in the expressions:</p>
<ul>
<li><code>assertion</code> : JSON representing the authentication credential issued by the provider.</li>
<li><code>google</code> : The Google attributes mapped from the assertion in the <code>attribute_mappings</code> .</li>
<li><code>attribute</code> : The custom attributes mapped from the assertion in the <code>attribute_mappings</code> .</li>
</ul>
<p>The maximum length of the <code>attributeCondition</code> expression is 4,096 characters. If unspecified, all valid authentication credentials are accepted. However, multi-tenant identity providers (such as GitHub or Terraform Cloud) require an <code>attributeCondition</code> to prevent token spoofing.</p>
<p>The following example shows how to only allow credentials with a mapped <code>google.groups</code> value of <code>admins</code> :</p>
<pre data-fenced=""><code>&quot;&#39;admins&#39; in google.groups&quot;</code></pre></td>
</tr>
<tr class="even">
<td><code>expireTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Time after which the workload identity pool provider will be permanently purged and cannot be recovered.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td>Union field <code>provider_config</code> . Identity provider configuration types. <code>provider_config</code> can be only one of the following:</td>
<td></td>
</tr>
<tr class="even">
<td><code>aws</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Aws"><code>Aws</code></a><code> )</code></p>
<p>An Amazon Web Services identity provider.</p></td>
</tr>
<tr class="odd">
<td><code>oidc</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Oidc"><code>Oidc</code></a><code> )</code></p>
<p>An OpenId Connect 1.0 identity provider.</p></td>
</tr>
<tr class="even">
<td><code>saml</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#Saml"><code>Saml</code></a><code> )</code></p>
<p>An SAML 2.0 identity provider.</p></td>
</tr>
<tr class="odd">
<td><code>x509</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#X509"><code>X509</code></a><code> )</code></p>
<p>An X.509-type identity provider.</p></td>
</tr>
</tbody>
</table>

## State

The current state of the provider.

| Enums               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `ACTIVE`            | The provider is active, and may be used to validate authentication credentials.                                                                                                                                                                                                                                                                                                                                                                                     |
| `DELETED`           | The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using [`providers.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/undelete#google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider) . You cannot reuse the ID of a soft-deleted provider until it is permanently deleted. |

## Aws

Represents an Amazon Web Services identity provider.

**JSON representation**

```
{
  "accountId": string
}
```

| Fields      |                                        |
|-------------|----------------------------------------|
| `accountId` | `string` Required. The AWS account ID. |

## Oidc

Represents an OpenId Connect 1.0 identity provider.

**JSON representation**

```
{
  "issuerUri": string,
  "allowedAudiences": [
    string
  ],
  "jwksJson": string
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>issuerUri</code></td>
<td><p><code>string</code></p>
<p>Required. The OIDC issuer URL. Must be an HTTPS endpoint. Per OpenID Connect Discovery 1.0 spec, the OIDC issuer URL is used to locate the provider's public keys (via <code>jwksUri</code> ) for verifying tokens like the OIDC ID token. These public key types must be 'EC' or 'RSA'.</p></td>
</tr>
<tr class="even">
<td><code>allowedAudiences[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Acceptable values for the <code>aud</code> field (audience) in the OIDC token. Token exchange requests are rejected if the token audience does not match one of the configured values. Each audience may be at most 256 characters. A maximum of 10 audiences may be configured.</p>
<p>If this list is empty, the OIDC token audience must be equal to the full canonical resource name of the WorkloadIdentityPoolProvider, with or without the HTTPS prefix. For example:</p>
<pre data-fenced=""><code>//iam.googleapis.com/projects/&lt;project-number&gt;/locations/&lt;location&gt;/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;
https://iam.googleapis.com/projects/&lt;project-number&gt;/locations/&lt;location&gt;/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;</code></pre></td>
</tr>
<tr class="odd">
<td><code>jwksJson</code></td>
<td><p><code>string</code></p>
<p>Optional. OIDC JWKs in JSON String format. For details on the definition of a JWK, see <a href="https://tools.ietf.org/html/rfc7517">https://tools.ietf.org/html/rfc7517</a> . If not set, the <code>jwksUri</code> from the discovery document(fetched from the .well-known path of the <code>issuerUri</code> ) will be used. Currently, RSA and EC asymmetric keys are supported. The JWK must use following format and include only the following fields: { "keys": [ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } ] }</p></td>
</tr>
</tbody>
</table>

## Saml

Represents an SAML 2.0 identity provider.

**JSON representation**

```
{

  // Union field identity_provider can be only one of the following:
  "idpMetadataXml": string
  // End of list of possible types for union field identity_provider.
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Union field <code>identity_provider</code> .</p>
<p><code>identity_provider</code> can be only one of the following:</p></td>
<td></td>
</tr>
<tr class="even">
<td><code>idpMetadataXml</code></td>
<td><p><code>string</code></p>
<p>Required. SAML identity provider (IdP) configuration metadata XML doc. The XML document must comply with the <a href="https://docs.oasis-open.org/security/saml/v2.0/saml-metadata-2.0-os.pdf">SAML 2.0 specification</a> . The maximum size of an acceptable XML document is 128K characters.</p>
<p>The SAML metadata XML document must satisfy the following constraints:</p>
<ul>
<li>Must contain an IdP Entity ID.</li>
<li>Must contain at least one non-expired signing certificate.</li>
<li>For each signing certificate, the expiration must be:
<ul>
<li>From no more than 7 days in the future.</li>
<li>To no more than 25 years in the future.</li>
</ul></li>
<li>Up to three IdP signing keys are allowed.</li>
</ul>
<p>When updating the provider's metadata XML, at least one non-expired signing key must overlap with the existing metadata. This requirement is skipped if there are no non-expired signing keys present in the existing metadata.</p></td>
</tr>
</tbody>
</table>

## X509

An X.509-type identity provider represents a CA. It is trusted to assert a client identity if the client has a certificate that chains up to this CA.

**JSON representation**

```
{
  "trustStore": {
    object (TrustStore)
  }
}
```

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `trustStore` | `object ( `[`TrustStore`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore)` )` Required. A [`TrustStore`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/TrustStore) . Use this trust store as a wrapper to config the trust anchor and optional intermediate cas to help build the trust chain for the incoming end entity certificate. Follow the X.509 guidelines to define those PEM encoded certs. Only one trust store is currently supported. |

| Methods                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/create)     | Creates a new [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) in a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools#WorkloadIdentityPool) .           |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/delete)     | Deletes a [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) .                                                                                                                                                                     |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/get)           | Gets an individual [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) .                                                                                                                                                            |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/list)         | Lists all non-deleted [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) s in a [`WorkloadIdentityPool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools#WorkloadIdentityPool) . |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/patch)       | Updates an existing [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) .                                                                                                                                                           |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/undelete) | Undeletes a [`WorkloadIdentityPoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#WorkloadIdentityPoolProvider) , as long as it was deleted fewer than 30 days ago.                                                                                                                 |
