---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token
title: 'Method: token'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#body.HTTP_TEMPLATE)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#body.ExchangeTokenResponse.SCHEMA_REPRESENTATION)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#try-it)

Exchanges a credential for a Google OAuth 2.0 access token.

The token asserts an external identity within a workload identity pool, or it applies a Credential Access Boundary to a Google access token.

When you call this method, do not send the `Authorization` HTTP header in the request. This method does not require the `Authorization` header, and using the header can cause the request to fail.

### HTTP request

`POST https://sts.googleapis.com/v1beta/token`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "grantType": string,
  "audience": string,
  "scope": string,
  "requestedTokenType": string,
  "subjectToken": string,
  "subjectTokenType": string,
  "options": string
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
<td><code>grantType</code></td>
<td><p><code>string</code></p>
<p>Required. The grant type. Must be <code>urn:ietf:params:oauth:grant-type:token-exchange</code> , which indicates a token exchange.</p></td>
</tr>
<tr class="even">
<td><code>audience</code></td>
<td><p><code>string</code></p>
<p>The full resource name of the identity provider. For example, <code>//iam.googleapis.com/projects/&lt;project-number&gt;/locations/global/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;</code> . Required when exchanging an external credential for a Google access token.</p></td>
</tr>
<tr class="odd">
<td><code>scope</code></td>
<td><p><code>string</code></p>
<p>The OAuth 2.0 scopes to include on the resulting access token, formatted as a list of space-delimited, case-sensitive strings; for example, <code>https://www.googleapis.com/auth/cloud-platform</code> . Required when exchanging an external credential for a Google access token. For a list of OAuth 2.0 scopes, see <a href="https://developers.google.com/identity/protocols/oauth2/scopes">OAuth 2.0 Scopes for Google APIs</a> .</p></td>
</tr>
<tr class="even">
<td><code>requestedTokenType</code></td>
<td><p><code>string</code></p>
<p>Required. The type of security token. Must be <code>urn:ietf:params:oauth:token-type:access_token</code> , which indicates an OAuth 2.0 access token.</p></td>
</tr>
<tr class="odd">
<td><code>subjectToken</code></td>
<td><p><code>string</code></p>
<p>Required. The input token.</p>
<p>This token is either an external credential issued by a workload identity pool provider, or a short-lived access token issued by Google.</p>
<p>If the token is an OIDC JWT, it must use the JWT format defined in <a href="https://tools.ietf.org/html/rfc7523">RFC 7523</a> , and the <code>subjectTokenType</code> must be either <code>urn:ietf:params:oauth:token-type:jwt</code> or <code>urn:ietf:params:oauth:token-type:idToken</code> .</p>
<p>The following headers are required:</p>
<ul>
<li><code>kid</code> : The identifier of the signing key securing the JWT.</li>
<li><code>alg</code> : The cryptographic algorithm securing the JWT. Must be <code>RS256</code> or <code>ES256</code> .</li>
</ul>
<p>The following payload fields are required. For more information, see <a href="https://tools.ietf.org/html/rfc7523#section-3">RFC 7523, Section 3</a> :</p>
<ul>
<li><code>iss</code> : The issuer of the token. The issuer must provide a discovery document at the URL <code>&lt;iss&gt;/.well-known/openid-configuration</code> , where <code>&lt;iss&gt;</code> is the value of this field. The document must be formatted according to section 4.2 of the <a href="https://openid.net/specs/openid-connect-discovery-1_0.html#ProviderConfigurationResponse">OIDC 1.0 Discovery specification</a> .</li>
<li><code>iat</code> : The issue time, in seconds, since the Unix epoch. This timestamp must be in the past and no more than 24 hours in the past, or the token will be rejected. Note that this implies the token is only acceptable within a time window of at most 24 hours.</li>
<li><code>exp</code> : The expiration time, in seconds, since the Unix epoch. Shorter expiration times are more secure. If possible, we recommend setting an expiration time less than 6 hours.</li>
<li><code>sub</code> : The identity asserted in the JWT.</li>
<li><code>aud</code> : For workload identity pools, this must be a value specified in the allowed audiences for the workload identity pool provider, or one of the audiences allowed by default if no audiences were specified. See <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#oidc">https://cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers#oidc</a></li>
</ul>
<p>Example header:</p>
<p><code>{ "alg": "RS256", "kid": "us-east-11" }</code></p>
<p>Example payload:</p>
<p><code>{ "iss": "https://accounts.google.com", "iat": 1517963104, "exp": 1517966704, "aud": "//iam.googleapis.com/projects/1234567890123/locations/global/workloadIdentityPools/my-pool/providers/my-provider", "sub": "113475438248934895348", "my_claims": { "additional_claim": "value" } }</code></p>
<p>If <code>subjectToken</code> is for AWS, it must be a serialized <code>GetCallerIdentity</code> token. This token contains the same information as a request to the AWS <a href="https://docs.aws.amazon.com/STS/latest/APIReference/API_GetCallerIdentity"><code>GetCallerIdentity()</code></a> method, as well as the AWS <a href="https://docs.aws.amazon.com/general/latest/gr/signing_aws_api_requests.html">signature</a> for the request information. Use Signature Version 4. Format the request as URL-encoded JSON, and set the <code>subjectTokenType</code> parameter to <code>urn:ietf:params:aws:token-type:aws4_request</code> .</p>
<p>The following parameters are required:</p>
<ul>
<li><code>url</code> : The URL of the AWS STS endpoint for <code>GetCallerIdentity()</code> , such as <code>https://sts.amazonaws.com?Action=GetCallerIdentity&amp;Version=2011-06-15</code> . Regional endpoints are also supported.</li>
<li><code>method</code> : The HTTP request method: <code>POST</code> .</li>
<li><code>headers</code> : The HTTP request headers, which must include:
<ul>
<li><code>Authorization</code> : The request signature.</li>
<li><code>x-amz-date</code> : The time you will send the request, formatted as an <a href="https://docs.aws.amazon.com/general/latest/gr/sigv4_elements.html#sigv4_elements_date">ISO8601 Basic</a> string. This value is typically set to the current time and is used to help prevent replay attacks.</li>
<li><code>host</code> : The hostname of the <code>url</code> field; for example, <code>sts.amazonaws.com</code> .</li>
<li><code>x-goog-cloud-target-resource</code> : The full, canonical resource name of the workload identity pool provider, with or without an <code>https:</code> prefix. To help ensure data integrity, we recommend including this header in the <code>SignedHeaders</code> field of the signed request. For example:</li>
</ul></li>
</ul>
<pre data-fenced=""><code>   //iam.googleapis.com/projects/&lt;project-number&gt;/locations/global/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;
   https://iam.googleapis.com/projects/&lt;project-number&gt;/locations/global/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;</code></pre>
<p>If you are using temporary security credentials provided by AWS, you must also include the header <code>x-amz-security-token</code> , with the value set to the session token.</p>
<p>The following example shows a <code>GetCallerIdentity</code> token:</p>
<p><code>{ "headers": [ {"key": "x-amz-date", "value": "20200815T015049Z"}, {"key": "Authorization", "value": "AWS4-HMAC-SHA256+Credential=$credential,+SignedHeaders=host;x-amz-date;x-goog-cloud-target-resource,+Signature=$signature"}, {"key": "x-goog-cloud-target-resource", "value": "//iam.googleapis.com/projects/&lt;project-number&gt;/locations/global/workloadIdentityPools/&lt;pool-id&gt;/providers/&lt;provider-id&gt;"}, {"key": "host", "value": "sts.amazonaws.com"} . ], "method": "POST", "url": "https://sts.amazonaws.com?Action=GetCallerIdentity&amp;Version=2011-06-15" }</code></p>
<p>You can also use a Google-issued OAuth 2.0 access token with this field to obtain an access token with new security attributes applied, such as a Credential Access Boundary. In this case, set <code>subjectTokenType</code> to <code>urn:ietf:params:oauth:token-type:access_token</code> .</p>
<p>If an access token already contains security attributes, you cannot apply additional security attributes.</p></td>
</tr>
<tr class="even">
<td><code>subjectTokenType</code></td>
<td><p><code>string</code></p>
<p>Required. An identifier that indicates the type of the security token in the <code>subjectToken</code> parameter. Supported values are <code>urn:ietf:params:oauth:token-type:jwt</code> , <code>urn:ietf:params:oauth:token-type:id_token</code> , <code>urn:ietf:params:aws:token-type:aws4_request</code> , and <code>urn:ietf:params:oauth:token-type:access_token</code> .</p></td>
</tr>
<tr class="odd">
<td><code>options</code></td>
<td><p><code>string</code></p>
<p>A set of features that Security Token Service supports, in addition to the standard OAuth 2.0 token exchange, formatted as a serialized JSON object of <a href="https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/Options"><code>Options</code></a> .</p>
<p>The size of the parameter value must not exceed 4096 characters.</p></td>
</tr>
</tbody>
</table>

### Response body

Response message for [`v1beta.token`](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1beta/TopLevel/token#google.identity.sts.v1beta.SecurityTokenService.ExchangeToken) .

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "access_token": string,
  "issued_token_type": string,
  "token_type": string,
  "expires_in": integer
}
```

| Fields              |                                                                                                                                                                                                                                                                                                                                           |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `access_token`      | `string` An OAuth 2.0 security token, issued by Google, in response to the token exchange request. Tokens can vary in size, depending in part on the size of mapped claims, up to a maximum of 12288 bytes (12 KB). Google reserves the right to change the token size and the maximum length at any time.                                |
| `issued_token_type` | `string` The token type. Always matches the value of `requestedTokenType` from the request.                                                                                                                                                                                                                                               |
| `token_type`        | `string` The type of access token. Always has the value `Bearer` .                                                                                                                                                                                                                                                                        |
| `expires_in`        | `integer` The amount of time, in seconds, between the time when the access token was issued and the time when the access token will expire. This field is absent when the `subjectToken` in the request is a Google-issued, short-lived access token. In this case, the access token has the same expiration time as the `subjectToken` . |
