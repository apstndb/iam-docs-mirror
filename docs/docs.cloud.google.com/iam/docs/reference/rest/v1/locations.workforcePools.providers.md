---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers
title: 'REST Resource: locations.workforcePools.providers'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: WorkforcePoolProvider](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider.SCHEMA_REPRESENTATION)
- [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#State)
- [Saml](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Saml)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Saml.SCHEMA_REPRESENTATION)
- [Oidc](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Oidc)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Oidc.SCHEMA_REPRESENTATION)
- [ClientSecret](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ClientSecret)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ClientSecret.SCHEMA_REPRESENTATION)
- [Value](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Value)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Value.SCHEMA_REPRESENTATION)
- [WebSsoConfig](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WebSsoConfig)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WebSsoConfig.SCHEMA_REPRESENTATION)
- [ResponseType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ResponseType)
- [AssertionClaimsBehavior](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#AssertionClaimsBehavior)
- [ExtraAttributesOAuth2Client](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ExtraAttributesOAuth2Client)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ExtraAttributesOAuth2Client.SCHEMA_REPRESENTATION)
- [AttributesType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#AttributesType)
- [QueryParameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#QueryParameters)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#QueryParameters.SCHEMA_REPRESENTATION)
- [ScimUsage](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ScimUsage)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#METHODS_SUMMARY)

## Resource: WorkforcePoolProvider

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
  "extraAttributesOauth2Client": {
    object (ExtraAttributesOAuth2Client)
  },
  "detailedAuditLogging": boolean,
  "extendedAttributesOauth2Client": {
    object (ExtraAttributesOAuth2Client)
  },
  "scimUsage": enum (ScimUsage),

  // Union field provider_config can be only one of the following:
  "saml": {
    object (Saml)
  },
  "oidc": {
    object (Oidc)
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
<p>Identifier. The resource name of the provider.</p>
<p>Format: <code>locations/{location}/workforcePools/{workforcePoolId}/providers/{providerId}</code></p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. A display name for the provider.</p>
<p>Cannot exceed 32 characters.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. A description of the provider. Cannot exceed 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#State"><code>State</code></a><code> )</code></p>
<p>Output only. The state of the provider.</p></td>
</tr>
<tr class="odd">
<td><code>disabled</code></td>
<td><p><code>boolean</code></p>
<p>Optional. Disables the workforce pool provider. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.</p></td>
</tr>
<tr class="even">
<td><code>attributeMapping</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Required. Maps attributes from the authentication credentials issued by an external identity provider to Google Cloud attributes, such as <code>subject</code> and <code>segment</code> .</p>
<p>Each key must be a string specifying the Google Cloud IAM attribute to map to.</p>
<p>The following keys are supported:</p>
<ul>
<li><p><code>google.subject</code> : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.</p></li>
<li><p><code>google.groups</code> : Groups the authenticating user belongs to. You can grant groups access to resources using an IAM <code>principalSet</code> binding; access applies to all members of the group.</p></li>
<li><p><code>google.display_name</code> : The name of the authenticated user. This is an optional field and the mapped display name cannot exceed 100 bytes. If not set, <code>google.subject</code> will be displayed instead. This attribute cannot be referenced in IAM bindings.</p></li>
<li><p><code>google.profile_photo</code> : The URL that specifies the authenticated user's thumbnail photo. This is an optional field. When set, the image will be visible as the user's profile picture. If not set, a generic user icon will be displayed instead. This attribute cannot be referenced in IAM bindings.</p></li>
<li><p><code>google.posix_username</code> : The Linux username used by OS Login. This is an optional field and the mapped POSIX username cannot exceed 32 characters. The key must match the regex <code>^[a-zA-Z0-9._][a-zA-Z0-9._-]{0,31}$</code> . This attribute cannot be referenced in IAM bindings.</p></li>
</ul>
<p>You can also provide custom attributes by specifying <code>attribute.{custom_attribute}</code> , where {custom_attribute} is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters <code>[a-z0-9_]</code> .</p>
<p>You can reference these attributes in IAM policies to define fine-grained access for a workforce pool to Google Cloud resources. For example:</p>
<ul>
<li><p><code>google.subject</code> : <code>principal://iam.googleapis.com/locations/global/workforcePools/{pool}/subject/{value}</code></p></li>
<li><p><code>google.groups</code> : <code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/group/{value}</code></p></li>
<li><p><code>attribute.{custom_attribute}</code> : <code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/attribute.{custom_attribute}/{value}</code></p></li>
</ul>
<p>Each value must be a <a href="https://opensource.google/projects/cel">Common Expression Language</a> function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.</p>
<p>You can use the <code>assertion</code> keyword in the expression to access a JSON representation of the authentication credential issued by the provider.</p>
<p>The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 16 KB.</p>
<p>For OIDC providers, you must supply a custom mapping that includes the <code>google.subject</code> attribute. For example, the following maps the <code>sub</code> claim of the incoming credential to the <code>subject</code> attribute on a Google token:</p>
<pre data-fenced=""><code>{&quot;google.subject&quot;: &quot;assertion.sub&quot;}</code></pre>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>attributeCondition</code></td>
<td><p><code>string</code></p>
<p>Optional. A <a href="https://opensource.google/projects/cel">Common Expression Language</a> expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.</p>
<p>The expression must output a boolean representing whether to allow the federation.</p>
<p>The following keywords may be referenced in the expressions:</p>
<ul>
<li><code>assertion</code> : JSON representing the authentication credential issued by the provider.</li>
<li><code>google</code> : The Google attributes mapped from the assertion in the <code>attribute_mappings</code> . <code>google.profile_photo</code> , <code>google.display_name</code> and <code>google.posix_username</code> are not supported.</li>
<li><code>attribute</code> : The custom attributes mapped from the assertion in the <code>attribute_mappings</code> .</li>
</ul>
<p>The maximum length of the attribute condition expression is 4096 characters. If unspecified, all valid authentication credentials will be accepted.</p>
<p>The following example shows how to only allow credentials with a mapped <code>google.groups</code> value of <code>admins</code> :</p>
<pre data-fenced=""><code>&quot;&#39;admins&#39; in google.groups&quot;</code></pre></td>
</tr>
<tr class="even">
<td><code>expireTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Time after which the workforce identity pool provider will be permanently purged and cannot be recovered.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>extraAttributesOauth2Client</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ExtraAttributesOAuth2Client"><code>ExtraAttributesOAuth2Client</code></a><code> )</code></p>
<p>Optional. The configuration for OAuth 2.0 client used to get the additional user attributes. This should be used when users can't get the desired claims in authentication credentials. Currently, this configuration is only supported with OIDC protocol.</p></td>
</tr>
<tr class="even">
<td><code>detailedAuditLogging</code></td>
<td><p><code>boolean</code></p>
<p>Optional. If true, populates additional debug information in Cloud Audit Logs for this provider. Logged attribute mappings and values can be found in <code>sts.googleapis.com</code> data access logs. Default value is false.</p></td>
</tr>
<tr class="odd">
<td><code>extendedAttributesOauth2Client</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ExtraAttributesOAuth2Client"><code>ExtraAttributesOAuth2Client</code></a><code> )</code></p>
<p>Optional. The configuration for OAuth 2.0 client used to get the extended group memberships for user identities. Only the <code>AZURE_AD_GROUPS_ID</code> attribute type is supported. Extended groups supports a subset of Google Cloud services. When the user accesses these services, extended group memberships override the mapped <code>google.groups</code> attribute. Extended group memberships cannot be used in attribute mapping or attribute condition expressions.</p>
<p>To keep extended group memberships up to date, extended groups are retrieved when the user signs in and at regular intervals during the user's active session. Each user identity in the workforce identity pool must map to a unique Microsoft Entra ID user.</p></td>
</tr>
<tr class="even">
<td><code>scimUsage</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ScimUsage"><code>ScimUsage</code></a><code> )</code></p>
<p>Optional. Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups instead of the <code>google.groups</code> attribute mapping for authorization checks.</p>
<p>The <code>scimUsage</code> and <code>extendedAttributesOauth2Client</code> fields are mutually exclusive. A request that enables both fields on the same workforce identity pool provider will produce an error.</p></td>
</tr>
<tr class="odd">
<td><p>Union field <code>provider_config</code> .</p>
<p><code>provider_config</code> can be only one of the following:</p></td>
<td></td>
</tr>
<tr class="even">
<td><code>saml</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Saml"><code>Saml</code></a><code> )</code></p>
<p>A SAML identity provider configuration.</p></td>
</tr>
<tr class="odd">
<td><code>oidc</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Oidc"><code>Oidc</code></a><code> )</code></p>
<p>An OpenID Connect 1.0 identity provider configuration.</p></td>
</tr>
</tbody>
</table>

## State

The current state of the provider.

| Enums               |                                                                                                                                                                                                                                                                                                                                                         |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | State unspecified.                                                                                                                                                                                                                                                                                                                                      |
| `ACTIVE`            | The provider is active and may be used to validate authentication credentials.                                                                                                                                                                                                                                                                          |
| `DELETED`           | The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using [`providers.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/undelete#google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProvider) . |

## Saml

Represents a SAML identity provider.

**JSON representation**

```
{

  // Union field identity_provider can be only one of the following:
  "idpMetadataXml": string
  // End of list of possible types for union field identity_provider.
}
```

| Fields                                                                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-----------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `identity_provider` . `identity_provider` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `idpMetadataXml`                                                                        | `string` Required. SAML Identity provider configuration metadata xml doc. The xml document should comply with [SAML 2.0 specification](https://docs.oasis-open.org/security/saml/v2.0/saml-metadata-2.0-os.pdf) . The max size of the acceptable xml document will be bounded to 128k characters. The metadata xml document should satisfy the following constraints: 1) Must contain an Identity Provider Entity ID. 2) Must contain at least one non-expired signing key certificate. 3) For each signing key: a) Valid from should be no more than 7 days from now. b) Valid to should be no more than 25 years in the future. 4) Up to 3 IdP signing keys are allowed in the metadata xml. When updating the provider's metadata xml, at least one non-expired signing key must overlap with the existing metadata. This requirement is skipped if there are no non-expired signing keys present in the existing metadata. |

## Oidc

Represents an OpenID Connect 1.0 identity provider.

**JSON representation**

```
{
  "issuerUri": string,
  "clientId": string,
  "clientSecret": {
    object (ClientSecret)
  },
  "webSsoConfig": {
    object (WebSsoConfig)
  },
  "jwksJson": string
}
```

| Fields         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `issuerUri`    | `string` Required. The OIDC issuer URI. Must be a valid URI using the `https` scheme.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `clientId`     | `string` Required. The client ID. Must match the audience claim of the JWT issued by the identity provider.                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `clientSecret` | `object ( `[`ClientSecret`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ClientSecret)` )` Optional. The optional client secret. Required to enable Authorization Code flow for web sign-in.                                                                                                                                                                                                                                                                                 |
| `webSsoConfig` | `object ( `[`WebSsoConfig`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WebSsoConfig)` )` Required. Configuration for web single sign-on for the OIDC provider. Here, web sign-in refers to console sign-in and gcloud sign-in through the browser.                                                                                                                                                                                                                         |
| `jwksJson`     | `string` Optional. OIDC JWKs in JSON String format. For details on the definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, the `jwksUri` from the discovery document that is fetched from the well-known path of the `issuerUri` , will be used. RSA and EC asymmetric keys are supported. The JWK must use the following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] } |

## ClientSecret

Representation of a client secret configured for the OIDC provider.

**JSON representation**

```
{

  // Union field source can be only one of the following:
  "value": {
    object (Value)
  }
  // End of list of possible types for union field source.
}
```

| Fields                                                            |                                                                                                                                                             |
|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `source` . `source` can be only one of the following: |                                                                                                                                                             |
| `value`                                                           | `object ( `[`Value`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#Value)` )` The value of the client secret. |

## Value

Representation of the value of the client secret.

**JSON representation**

```
{
  "plainText": string,
  "thumbprint": string
}
```

| Fields       |                                                                                                                                                                                |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `plainText`  | `string` Optional. Input only. The plain text of the client secret value. For security reasons, this field is only used for input and will never be populated in any response. |
| `thumbprint` | `string` Output only. A thumbprint to represent the current client secret value.                                                                                               |

## WebSsoConfig

Configuration for web single sign-on for the OIDC provider.

**JSON representation**

```
{
  "responseType": enum (ResponseType),
  "assertionClaimsBehavior": enum (AssertionClaimsBehavior),
  "additionalScopes": [
    string
  ]
}
```

| Fields                    |                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `responseType`            | `enum ( `[`ResponseType`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ResponseType)` )` Required. The Response Type to request for in the OIDC Authorization Request for web sign-in. The `CODE` Response Type is recommended to avoid the Implicit Flow, for security reasons.                            |
| `assertionClaimsBehavior` | `enum ( `[`AssertionClaimsBehavior`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#AssertionClaimsBehavior)` )` Required. The behavior for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.                                                        |
| `additionalScopes[]`      | `string` Optional. Additional scopes to request for in the OIDC authentication request on top of scopes requested by default. By default, the `openid` , `profile` and `email` scopes that are supported by the identity provider are requested. Each additional scope may be at most 256 characters. A maximum of 10 additional scopes may be configured. |

## ResponseType

Possible Response Types to request for in the OIDC Authorization Request for web sign-in. This determines the OIDC Authentication Flow. See <https://openid.net/specs/openid-connect-core-1_0.html#Authentication> for a mapping of Response Type to OIDC Authentication Flow.

| Enums                       |                                                                                                                          |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------|
| `RESPONSE_TYPE_UNSPECIFIED` | No Response Type specified.                                                                                              |
| `CODE`                      | The `responseType=code` selection uses the Authorization Code Flow for web sign-in. Requires a configured client secret. |
| `ID_TOKEN`                  | The `responseType=id_token` selection uses the Implicit Flow for web sign-in.                                            |

## AssertionClaimsBehavior

Possible behaviors for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.

| Enums                                   |                                                                                                                                                                                   |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ASSERTION_CLAIMS_BEHAVIOR_UNSPECIFIED` | No assertion claims behavior specified.                                                                                                                                           |
| `MERGE_USER_INFO_OVER_ID_TOKEN_CLAIMS`  | Merge the UserInfo Endpoint Claims with ID Token Claims, preferring UserInfo Claim Values for the same Claim Name. This option is available only for the Authorization Code Flow. |
| `ONLY_ID_TOKEN_CLAIMS`                  | Only include ID Token Claims.                                                                                                                                                     |

## ExtraAttributesOAuth2Client

Represents the OAuth 2.0 client credential configuration for retrieving additional user attributes that are not present in the initial authentication credentials from the identity provider, for example, groups. See <https://datatracker.ietf.org/doc/html/rfc6749#section-4.4> for more details on client credentials grant flow.

**JSON representation**

```
{
  "issuerUri": string,
  "clientId": string,
  "clientSecret": {
    object (ClientSecret)
  },
  "attributesType": enum (AttributesType),
  "queryParameters": {
    object (QueryParameters)
  }
}
```

| Fields            |                                                                                                                                                                                                                                                                                                                   |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `issuerUri`       | `string` Required. The OIDC identity provider's issuer URI. Must be a valid URI using the `https` scheme. Required to get the OIDC discovery document.                                                                                                                                                            |
| `clientId`        | `string` Required. The OAuth 2.0 client ID for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow.                                                                                                                                      |
| `clientSecret`    | `object ( `[`ClientSecret`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#ClientSecret)` )` Required. The OAuth 2.0 client secret for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow. |
| `attributesType`  | `enum ( `[`AttributesType`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#AttributesType)` )` Required. Represents the IdP and type of claims that should be fetched.                                                                                               |
| `queryParameters` | `object ( `[`QueryParameters`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#QueryParameters)` )` Optional. Represents the parameters to control which claims are fetched from an IdP.                                                                              |

## AttributesType

Represents the IdP and type of claims that should be fetched.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>ATTRIBUTES_TYPE_UNSPECIFIED</code></td>
<td>No AttributesType specified.</td>
</tr>
<tr class="even">
<td><code>AZURE_AD_GROUPS_MAIL</code></td>
<td><p>Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in <code>ExtraAttributesOAuth2Client</code> . The <code>mail</code> property of the <code>microsoft.graph.group</code> object is used for claim mapping. For more information about <code>microsoft.graph.group</code> properties, see <a href="https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties">https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties</a> . The group mail addresses of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:</p>
<ul>
<li>OIDC: <code>assertion.groups</code></li>
<li>SAML: <code>assertion.attributes.groups</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>AZURE_AD_GROUPS_ID</code></td>
<td><p>Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in <code>ExtraAttributesOAuth2Client</code> . The <code>id</code> property of the <code>microsoft.graph.group</code> object is used for claim mapping. For more information about <code>microsoft.graph.group</code> properties, see <a href="https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties">https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties</a> . The group IDs of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:</p>
<ul>
<li>OIDC: <code>assertion.groups</code></li>
<li>SAML: <code>assertion.attributes.groups</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>AZURE_AD_GROUPS_DISPLAY_NAME</code></td>
<td><p>Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in <code>ExtraAttributesOAuth2Client</code> . The <code>displayName</code> property of the <code>microsoft.graph.group</code> object is used for claim mapping. For more information about <code>microsoft.graph.group</code> properties, see <a href="https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties">https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties</a> . The group displayNames of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:</p>
<ul>
<li>OIDC: <code>assertion.groups</code></li>
<li>SAML: <code>assertion.attributes.groups</code></li>
</ul></td>
</tr>
</tbody>
</table>

## QueryParameters

Represents the parameters to control which claims are fetched from an IdP.

**JSON representation**

```
{
  "filter": string
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
<td><code>filter</code></td>
<td><p><code>string</code></p>
<p>Optional. The filter used to request specific records from the IdP. By default, all of the groups that are associated with a user are fetched. For Microsoft Entra ID, you can add <code>$search</code> query parameters using <a href="https://learn.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference">Keyword Query Language</a> . To learn more about <code>$search</code> querying in Microsoft Entra ID, see <a href="https://learn.microsoft.com/en-us/graph/search-query-parameter">Use the <code>$search</code> query parameter</a> .</p>
<p>Additionally, Workforce Identity Federation automatically adds the following <a href="https://learn.microsoft.com/en-us/graph/filter-query-parameter"><code>$filter</code> query parameters</a> , based on the value of <code>attributesType</code> . Values passed to <code>filter</code> are converted to <code>$search</code> query parameters. Additional <code>$filter</code> query parameters cannot be added using this field.</p>
<ul>
<li><code>AZURE_AD_GROUPS_MAIL</code> : <code>mailEnabled</code> and <code>securityEnabled</code> filters are applied.</li>
<li><code>AZURE_AD_GROUPS_ID</code> : <code>securityEnabled</code> filter is applied.</li>
<li><code>AZURE_AD_GROUPS_DISPLAY_NAME</code> : <code>securityEnabled</code> filter is applied.</li>
</ul></td>
</tr>
</tbody>
</table>

## ScimUsage

Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups.

| Enums                    |                                                                                                         |
|--------------------------|---------------------------------------------------------------------------------------------------------|
| `SCIM_USAGE_UNSPECIFIED` | Gemini Enterprise only. Do not use SCIM data.                                                           |
| `ENABLED_FOR_GROUPS`     | Gemini Enterprise only. SCIM sync is enabled and SCIM-managed groups are used for authorization checks. |

| Methods                                                                                                            |                                                                                                                                                                                                                                                                                                |
|--------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create)     | Creates a new [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) in a [`WorkforcePool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#WorkforcePool) .           |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/delete)     | Deletes a [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) .                                                                                                                                       |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/get)           | Gets an individual [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) .                                                                                                                              |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/list)         | Lists all non-deleted [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) s in a [`WorkforcePool`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools#WorkforcePool) . |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/patch)       | Updates an existing [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) .                                                                                                                             |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/undelete) | Undeletes a [`WorkforcePoolProvider`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers#WorkforcePoolProvider) , as long as it was deleted fewer than 30 days ago.                                                                                   |
