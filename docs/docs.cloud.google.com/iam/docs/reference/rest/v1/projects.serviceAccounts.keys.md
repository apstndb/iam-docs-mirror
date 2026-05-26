---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys
title: 'REST Resource: projects.serviceAccounts.keys'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: ServiceAccountKey](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey.SCHEMA_REPRESENTATION)
  - [ServiceAccountPrivateKeyType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountPrivateKeyType)
  - [ServiceAccountKeyAlgorithm](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKeyAlgorithm)
  - [ServiceAccountKeyOrigin](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKeyOrigin)
  - [KeyType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#KeyType)
  - [ServiceAccountKeyDisableReason](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKeyDisableReason)
  - [ExtendedStatus](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ExtendedStatus)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ExtendedStatus.SCHEMA_REPRESENTATION)
  - [ServiceAccountKeyExtendedStatusKey](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKeyExtendedStatusKey)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#METHODS_SUMMARY)

## Resource: ServiceAccountKey

Represents a service account key.

A service account has two sets of key-pairs: user-managed, and system-managed.

User-managed key-pairs can be created and deleted by users. Users are responsible for rotating these keys periodically to ensure security of their service accounts. Users retain the private key of these key-pairs, and Google retains ONLY the public key.

System-managed keys are automatically rotated by Google, and are used for signing for a maximum of two weeks. The rotation process is probabilistic, and usage of the new key will gradually ramp up and down over the key's lifetime.

If you cache the public key set for a service account, we recommend that you update the cache every 15 minutes. User-managed keys can be added and removed at any time, so it is important to update the cache frequently. For Google-managed keys, Google will publish a key at least 6 hours before it is first used for signing and will keep publishing it for at least 6 hours after it was last used for signing.

Public keys for all service accounts are also published at the OAuth2 Service Account API.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;privateKeyType&quot;: enum (ServiceAccountPrivateKeyType),&quot;keyAlgorithm&quot;: enum (ServiceAccountKeyAlgorithm),&quot;privateKeyData&quot;: string,&quot;publicKeyData&quot;: string,&quot;validAfterTime&quot;: string,&quot;validBeforeTime&quot;: string,&quot;keyOrigin&quot;: enum (ServiceAccountKeyOrigin),&quot;keyType&quot;: enum (KeyType),&quot;disabled&quot;: boolean,&quot;disableReason&quot;: enum (ServiceAccountKeyDisableReason),&quot;extendedStatus&quot;: [{object (ExtendedStatus)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The resource name of the service account key in the following format `projects/{PROJECT_ID}/serviceAccounts/{ACCOUNT}/keys/{key}` .

`privateKeyType`

` enum ( ServiceAccountPrivateKeyType  ` )

The output format for the private key. Only provided in `keys.create` responses, not in `keys.get` or `ListServiceAccountKey` responses.

Google never exposes system-managed private keys, and never retains user-managed private keys.

`keyAlgorithm`

` enum ( ServiceAccountKeyAlgorithm  ` )

Specifies the algorithm (and possibly key size) for the key.

`privateKeyData`

`string ( bytes format)`

The private key data. Only provided in `keys.create` responses. Make sure to keep the private key data secure because it allows for the assertion of the service account identity. When base64 decoded, the private key data can be used to authenticate with Google API client libraries and with [gcloud auth activate-service-account](https://docs.cloud.google.com/sdk/gcloud/reference/auth/activate-service-account) .

A base64-encoded string.

`publicKeyData`

`string ( bytes format)`

The public key data. Only provided in `keys.get` responses.

A base64-encoded string.

`validAfterTime`

` string ( Timestamp  ` format)

The key can be used after this timestamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`validBeforeTime`

` string ( Timestamp  ` format)

The key can be used before this timestamp. For system-managed key pairs, this timestamp is the end time for the private key signing operation. The public key could still be used for verification for a few hours after this time.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`keyOrigin`

` enum ( ServiceAccountKeyOrigin  ` )

The key origin.

`keyType`

` enum ( KeyType  ` )

The key type.

`disabled`

`boolean`

The key status.

`disableReason`

` enum ( ServiceAccountKeyDisableReason  ` )

Output only. optional. If the key is disabled, it may have a DisableReason describing why it was disabled.

`extendedStatus[]`

` object ( ExtendedStatus  ` )

Output only. Extended Status provides permanent information about a service account key. For example, if this key was detected as exposed or compromised, that information will remain for the lifetime of the key in the extendedStatus.

## ServiceAccountPrivateKeyType

Supported private key output formats.

Enums

`TYPE_UNSPECIFIED`

Unspecified. Equivalent to `TYPE_GOOGLE_CREDENTIALS_FILE` .

`TYPE_PKCS12_FILE`

PKCS12 format. The password for the PKCS12 file is `notasecret` . For more information, see <https://tools.ietf.org/html/rfc7292> .

`TYPE_GOOGLE_CREDENTIALS_FILE`

Google Credentials File format.

## ServiceAccountKeyAlgorithm

Supported key algorithms.

Enums

`KEY_ALG_UNSPECIFIED`

An unspecified key algorithm.

`KEY_ALG_RSA_1024`

1k RSA Key.

`KEY_ALG_RSA_2048`

2k RSA Key.

## ServiceAccountKeyOrigin

Service Account Key Origin.

Enums

`ORIGIN_UNSPECIFIED`

Unspecified key origin.

`USER_PROVIDED`

Key is provided by user.

`GOOGLE_PROVIDED`

Key is provided by Google.

## KeyType

`KeyType` filters to selectively retrieve certain varieties of keys.

Enums

`KEY_TYPE_UNSPECIFIED`

Unspecified key type. The presence of this in the message will immediately result in an error.

`USER_MANAGED`

User-managed keys (managed and rotated by the user).

`SYSTEM_MANAGED`

System-managed keys (managed and rotated by Google).

## ServiceAccountKeyDisableReason

DisableReason is intended to communicate more information about a disabled Service Accounts or Service Account Key.

Enums

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_UNSPECIFIED`

Unspecified disable reason

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_USER_INITIATED`

Disabled by the user

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_EXPOSED`

Google detected this Service Account external key's private key data as exposed, typically in a public repository on GitHub or similar.

`SERVICE_ACCOUNT_KEY_DISABLE_REASON_COMPROMISE_DETECTED`

This service account external key was detected as compromised and used by an attacker.

## ExtendedStatus

Extended status can store additional metadata. For example, for keys disabled due to their private key data being expoesed we may include a message with more information about the exposure.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: enum (ServiceAccountKeyExtendedStatusKey),&quot;value&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

` enum ( ServiceAccountKeyExtendedStatusKey  ` )

The key for this extended status.

`value`

`string`

The value for the extended status.

## ServiceAccountKeyExtendedStatusKey

Different categories of extendedStatus messages. For example the accompanying message for SERVICE\_ACCOUNT\_KEY\_EXTENDED\_STATUS\_KEY\_EXPOSED may contain information about how the key was exposed.

Enums

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_UNSPECIFIED`

Unspecified extended status, should not be used.

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_EXPOSED`

This key has been detected as exposed. extended\_status\_value may contain information about the exposure (public GitHub repo, open internet, etc.)

`SERVICE_ACCOUNT_KEY_EXTENDED_STATUS_KEY_COMPROMISE_DETECTED`

This key was implicated in a compromise or other attack. extended\_status\_value may contain information about the abuse perpetrated.

## Methods

### `            create           `

Creates a `  ServiceAccountKey  ` .

### `            delete           `

Deletes a `  ServiceAccountKey  ` .

### `            disable           `

Disable a `  ServiceAccountKey  ` .

### `            enable           `

Enable a `  ServiceAccountKey  ` .

### `            get           `

Gets a `  ServiceAccountKey  ` .

### `            list           `

Lists every `  ServiceAccountKey  ` for a service account.

### `            upload           `

Uploads the public key portion of a key pair that you manage, and associates the public key with a `  ServiceAccount  ` .
