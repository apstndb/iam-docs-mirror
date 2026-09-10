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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;displayName&quot;: string,&quot;description&quot;: string,&quot;state&quot;: enum (State),&quot;disabled&quot;: boolean,&quot;attributeMapping&quot;: {string: string,...},&quot;attributeCondition&quot;: string,&quot;expireTime&quot;: string,&quot;extraAttributesOauth2Client&quot;: {object (ExtraAttributesOAuth2Client)},&quot;detailedAuditLogging&quot;: boolean,&quot;extendedAttributesOauth2Client&quot;: {object (ExtraAttributesOAuth2Client)},&quot;scimUsage&quot;: enum (ScimUsage),// Union field provider_config can be only one of the following:&quot;saml&quot;: {object (Saml)},&quot;oidc&quot;: {object (Oidc)}// End of list of possible types for union field provider_config.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The resource name of the provider.

Format: `locations/{location}/workforcePools/{workforcePoolId}/providers/{providerId}`

`displayName`

`string`

Optional. A display name for the provider.

Cannot exceed 32 characters.

`description`

`string`

Optional. A description of the provider. Cannot exceed 256 characters.

`state`

` enum ( State  ` )

Output only. The state of the provider.

`disabled`

`boolean`

Optional. Disables the workforce pool provider. You cannot use a disabled provider to exchange tokens. However, existing tokens still grant access.

`attributeMapping`

`map (key: string, value: string)`

Required. Maps attributes from the authentication credentials issued by an external identity provider to Google Cloud attributes, such as `subject` and `segment` .

Each key must be a string specifying the Google Cloud IAM attribute to map to.

The following keys are supported:

  - `google.subject` : The principal IAM is authenticating. You can reference this value in IAM bindings. This is also the subject that appears in Cloud Logging logs. This is a required field and the mapped subject cannot exceed 127 bytes.

  - `google.groups` : Groups the authenticating user belongs to. You can grant groups access to resources using an IAM `principalSet` binding; access applies to all members of the group.

  - `google.display_name` : The name of the authenticated user. This is an optional field and the mapped display name cannot exceed 100 bytes. If not set, `google.subject` will be displayed instead. This attribute cannot be referenced in IAM bindings.

  - `google.profile_photo` : The URL that specifies the authenticated user's thumbnail photo. This is an optional field. When set, the image will be visible as the user's profile picture. If not set, a generic user icon will be displayed instead. This attribute cannot be referenced in IAM bindings.

  - `google.posix_username` : The Linux username used by OS Login. This is an optional field and the mapped POSIX username cannot exceed 32 characters. The key must match the regex `^[a-zA-Z0-9._][a-zA-Z0-9._-]{0,31}$` . This attribute cannot be referenced in IAM bindings.

You can also provide custom attributes by specifying `attribute.{custom_attribute}` , where {custom\_attribute} is the name of the custom attribute to be mapped. You can define a maximum of 50 custom attributes. The maximum length of a mapped attribute key is 100 characters, and the key may only contain the characters `[a-z0-9_]` .

You can reference these attributes in IAM policies to define fine-grained access for a workforce pool to Google Cloud resources. For example:

  - `google.subject` : `principal://iam.googleapis.com/locations/global/workforcePools/{pool}/subject/{value}`

  - `google.groups` : `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/group/{value}`

  - `attribute.{custom_attribute}` : `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool}/attribute.{custom_attribute}/{value}`

Each value must be a [Common Expression Language](https://opensource.google/projects/cel) function that maps an identity provider credential to the normalized attribute specified by the corresponding map key.

You can use the `assertion` keyword in the expression to access a JSON representation of the authentication credential issued by the provider.

The maximum length of an attribute mapping expression is 2048 characters. When evaluated, the total size of all mapped attributes must not exceed 16 KB.

For OIDC providers, you must supply a custom mapping that includes the `google.subject` attribute. For example, the following maps the `sub` claim of the incoming credential to the `subject` attribute on a Google token:

    {"google.subject": "assertion.sub"}

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`attributeCondition`

`string`

Optional. A [Common Expression Language](https://opensource.google/projects/cel) expression, in plain text, to restrict what otherwise valid authentication credentials issued by the provider should not be accepted.

The expression must output a boolean representing whether to allow the federation.

The following keywords may be referenced in the expressions:

  - `assertion` : JSON representing the authentication credential issued by the provider.
  - `google` : The Google attributes mapped from the assertion in the `attribute_mappings` . `google.profile_photo` , `google.display_name` and `google.posix_username` are not supported.
  - `attribute` : The custom attributes mapped from the assertion in the `attribute_mappings` .

The maximum length of the attribute condition expression is 4096 characters. If unspecified, all valid authentication credentials will be accepted.

The following example shows how to only allow credentials with a mapped `google.groups` value of `admins` :

    "'admins' in google.groups"

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the workforce identity pool provider will be permanently purged and cannot be recovered.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`extraAttributesOauth2Client`

` object ( ExtraAttributesOAuth2Client  ` )

Optional. The configuration for OAuth 2.0 client used to get the additional user attributes. This should be used when users can't get the desired claims in authentication credentials. Currently, this configuration is only supported with OIDC protocol.

`detailedAuditLogging`

`boolean`

Optional. If true, populates additional debug information in Cloud Audit Logs for this provider. Logged attribute mappings and values can be found in `sts.googleapis.com` data access logs. Default value is false.

`extendedAttributesOauth2Client`

` object ( ExtraAttributesOAuth2Client  ` )

Optional. The configuration for OAuth 2.0 client used to get the extended group memberships for user identities. Only the `AZURE_AD_GROUPS_ID` attribute type is supported. Extended groups supports a subset of Google Cloud services. When the user accesses these services, extended group memberships override the mapped `google.groups` attribute. Extended group memberships cannot be used in attribute mapping or attribute condition expressions.

To keep extended group memberships up to date, extended groups are retrieved when the user signs in and at regular intervals during the user's active session. Each user identity in the workforce identity pool must map to a unique Microsoft Entra ID user.

`scimUsage`

` enum ( ScimUsage  ` )

Optional. Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups instead of the `google.groups` attribute mapping for authorization checks.

The `scimUsage` and `extendedAttributesOauth2Client` fields are mutually exclusive. A request that enables both fields on the same workforce identity pool provider will produce an error.

Union field `provider_config` .

`provider_config` can be only one of the following:

`saml`

` object ( Saml  ` )

A SAML identity provider configuration.

`oidc`

` object ( Oidc  ` )

An OpenID Connect 1.0 identity provider configuration.

## State

The current state of the provider.

Enums

`STATE_UNSPECIFIED`

State unspecified.

`ACTIVE`

The provider is active and may be used to validate authentication credentials.

`DELETED`

The provider is soft-deleted. Soft-deleted providers are permanently deleted after approximately 30 days. You can restore a soft-deleted provider using `  providers.undelete  ` .

## Saml

Represents a SAML identity provider.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field identity_provider can be only one of the following:&quot;idpMetadataXml&quot;: string// End of list of possible types for union field identity_provider.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `identity_provider` .

`identity_provider` can be only one of the following:

`idpMetadataXml`

`string`

Required. SAML Identity provider configuration metadata xml doc. The xml document should comply with [SAML 2.0 specification](https://docs.oasis-open.org/security/saml/v2.0/saml-metadata-2.0-os.pdf) . The max size of the acceptable xml document will be bounded to 128k characters.

The metadata xml document should satisfy the following constraints: 1) Must contain an Identity Provider Entity ID. 2) Must contain at least one non-expired signing key certificate. 3) For each signing key: a) Valid from should be no more than 7 days from now. b) Valid to should be no more than 25 years in the future. 4) Up to 3 IdP signing keys are allowed in the metadata xml.

When updating the provider's metadata xml, at least one non-expired signing key must overlap with the existing metadata. This requirement is skipped if there are no non-expired signing keys present in the existing metadata.

## Oidc

Represents an OpenID Connect 1.0 identity provider.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;issuerUri&quot;: string,&quot;clientId&quot;: string,&quot;clientSecret&quot;: {object (ClientSecret)},&quot;webSsoConfig&quot;: {object (WebSsoConfig)},&quot;jwksJson&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`issuerUri`

`string`

Required. The OIDC issuer URI. Must be a valid URI using the `https` scheme.

`clientId`

`string`

Required. The client ID. Must match the audience claim of the JWT issued by the identity provider.

`clientSecret`

` object ( ClientSecret  ` )

Optional. The optional client secret. Required to enable Authorization Code flow for web sign-in.

`webSsoConfig`

` object ( WebSsoConfig  ` )

Required. Configuration for web single sign-on for the OIDC provider. Here, web sign-in refers to console sign-in and gcloud sign-in through the browser.

`jwksJson`

`string`

Optional. OIDC JWKs in JSON String format. For details on the definition of a JWK, see <https://tools.ietf.org/html/rfc7517> . If not set, the `jwksUri` from the discovery document that is fetched from the well-known path of the `issuerUri` , will be used. RSA and EC asymmetric keys are supported. The JWK must use the following format and include only the following fields: { "keys": \[ { "kty": "RSA/EC", "alg": " ", "use": "sig", "kid": " ", "n": "", "e": "", "x": "", "y": "", "crv": "" } \] }

## ClientSecret

Representation of a client secret configured for the OIDC provider.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field source can be only one of the following:&quot;value&quot;: {object (Value)}// End of list of possible types for union field source.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `source` .

`source` can be only one of the following:

`value`

` object ( Value  ` )

The value of the client secret.

## Value

Representation of the value of the client secret.

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
  &quot;plainText&quot;: string,
  &quot;thumbprint&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`plainText`

`string`

Optional. Input only. The plain text of the client secret value. For security reasons, this field is only used for input and will never be populated in any response.

`thumbprint`

`string`

Output only. A thumbprint to represent the current client secret value.

## WebSsoConfig

Configuration for web single sign-on for the OIDC provider.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;responseType&quot;: enum (ResponseType),&quot;assertionClaimsBehavior&quot;: enum (AssertionClaimsBehavior),&quot;additionalScopes&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`responseType`

` enum ( ResponseType  ` )

Required. The Response Type to request for in the OIDC Authorization Request for web sign-in.

The `CODE` Response Type is recommended to avoid the Implicit Flow, for security reasons.

`assertionClaimsBehavior`

` enum ( AssertionClaimsBehavior  ` )

Required. The behavior for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.

`additionalScopes[]`

`string`

Optional. Additional scopes to request for in the OIDC authentication request on top of scopes requested by default. By default, the `openid` , `profile` and `email` scopes that are supported by the identity provider are requested.

Each additional scope may be at most 256 characters. A maximum of 10 additional scopes may be configured.

## ResponseType

Possible Response Types to request for in the OIDC Authorization Request for web sign-in. This determines the OIDC Authentication Flow. See <https://openid.net/specs/openid-connect-core-1_0.html#Authentication> for a mapping of Response Type to OIDC Authentication Flow.

Enums

`RESPONSE_TYPE_UNSPECIFIED`

No Response Type specified.

`CODE`

The `responseType=code` selection uses the Authorization Code Flow for web sign-in. Requires a configured client secret.

`ID_TOKEN`

The `responseType=id_token` selection uses the Implicit Flow for web sign-in.

## AssertionClaimsBehavior

Possible behaviors for how OIDC Claims are included in the `assertion` object used for attribute mapping and attribute condition.

Enums

`ASSERTION_CLAIMS_BEHAVIOR_UNSPECIFIED`

No assertion claims behavior specified.

`MERGE_USER_INFO_OVER_ID_TOKEN_CLAIMS`

Merge the UserInfo Endpoint Claims with ID Token Claims, preferring UserInfo Claim Values for the same Claim Name. This option is available only for the Authorization Code Flow.

`ONLY_ID_TOKEN_CLAIMS`

Only include ID Token Claims.

## ExtraAttributesOAuth2Client

Represents the OAuth 2.0 client credential configuration for retrieving additional user attributes that are not present in the initial authentication credentials from the identity provider, for example, groups. See <https://datatracker.ietf.org/doc/html/rfc6749#section-4.4> for more details on client credentials grant flow.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;issuerUri&quot;: string,&quot;clientId&quot;: string,&quot;clientSecret&quot;: {object (ClientSecret)},&quot;attributesType&quot;: enum (AttributesType),&quot;queryParameters&quot;: {object (QueryParameters)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`issuerUri`

`string`

Required. The OIDC identity provider's issuer URI. Must be a valid URI using the `https` scheme. Required to get the OIDC discovery document.

`clientId`

`string`

Required. The OAuth 2.0 client ID for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow.

`clientSecret`

` object ( ClientSecret  ` )

Required. The OAuth 2.0 client secret for retrieving extra attributes from the identity provider. Required to get the Access Token using client credentials grant flow.

`attributesType`

` enum ( AttributesType  ` )

Required. Represents the IdP and type of claims that should be fetched.

`queryParameters`

` object ( QueryParameters  ` )

Optional. Represents the parameters to control which claims are fetched from an IdP.

## AttributesType

Represents the IdP and type of claims that should be fetched.

Enums

`ATTRIBUTES_TYPE_UNSPECIFIED`

No AttributesType specified.

`AZURE_AD_GROUPS_MAIL`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `mail` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group mail addresses of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

`AZURE_AD_GROUPS_ID`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `id` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group IDs of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

`AZURE_AD_GROUPS_DISPLAY_NAME`

Used to get the user's group claims from the Microsoft Entra ID identity provider using the configuration provided in `ExtraAttributesOAuth2Client` . The `displayName` property of the `microsoft.graph.group` object is used for claim mapping. For more information about `microsoft.graph.group` properties, see <https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0#properties> . The group displayNames of the user's groups that are returned from Microsoft Entra ID can be mapped by using the following attributes:

  - OIDC: `assertion.groups`
  - SAML: `assertion.attributes.groups`

## QueryParameters

Represents the parameters to control which claims are fetched from an IdP.

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
  &quot;filter&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`filter`

`string`

Optional. The filter used to request specific records from the IdP. By default, all of the groups that are associated with a user are fetched. For Microsoft Entra ID, you can add `$search` query parameters using [Keyword Query Language](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference) . To learn more about `$search` querying in Microsoft Entra ID, see [Use the `$search` query parameter](https://learn.microsoft.com/en-us/graph/search-query-parameter) .

Additionally, Workforce Identity Federation automatically adds the following [`$filter` query parameters](https://learn.microsoft.com/en-us/graph/filter-query-parameter) , based on the value of `attributesType` . Values passed to `filter` are converted to `$search` query parameters. Additional `$filter` query parameters cannot be added using this field.

  - `AZURE_AD_GROUPS_MAIL` : `mailEnabled` and `securityEnabled` filters are applied.
  - `AZURE_AD_GROUPS_ID` : `securityEnabled` filter is applied.
  - `AZURE_AD_GROUPS_DISPLAY_NAME` : `securityEnabled` filter is applied.

## ScimUsage

Gemini Enterprise only. Specifies whether the workforce identity pool provider uses SCIM-managed groups.

Enums

`SCIM_USAGE_UNSPECIFIED`

Gemini Enterprise only. Do not use SCIM data.

`ENABLED_FOR_GROUPS`

Gemini Enterprise only. SCIM sync is enabled and SCIM-managed groups are used for authorization checks.

## Methods

### `            create           `

Creates a new `  WorkforcePoolProvider  ` in a `  WorkforcePool  ` .

### `            delete           `

Deletes a `  WorkforcePoolProvider  ` .

### `            get           `

Gets an individual `  WorkforcePoolProvider  ` .

### `            list           `

Lists all non-deleted `  WorkforcePoolProvider  ` s in a `  WorkforcePool  ` .

### `            patch           `

Updates an existing `  WorkforcePoolProvider  ` .

### `            undelete           `

Undeletes a `  WorkforcePoolProvider  ` , as long as it was deleted fewer than 30 days ago.
