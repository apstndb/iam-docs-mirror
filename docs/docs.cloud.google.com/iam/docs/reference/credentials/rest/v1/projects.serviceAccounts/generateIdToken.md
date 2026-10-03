---
name: documents/docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken
uri: https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken
title: 'Method: projects.serviceAccounts.generateIdToken'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.GenerateIdTokenResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#body.aspect)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/generateIdToken#try-it)

Generates an OpenID Connect ID token for a service account.

### HTTP request

`POST https://iamcredentials.googleapis.com/v1/{name=projects/*/serviceAccounts/*}:generateIdToken`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameters</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Required. The resource name of the service account for which the credentials are requested, in the following format: <code>projects/-/serviceAccounts/{ACCOUNT_EMAIL_OR_UNIQUEID}</code> . The <code>-</code> wildcard character is required; replacing it with a project ID is invalid.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.serviceAccounts.getOpenIdToken</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "delegates": [
    string
  ],
  "audience": string,
  "includeEmail": boolean,
  "organizationNumberIncluded": boolean
}
```

| Fields                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `delegates[]`                | `string` The sequence of service accounts in a delegation chain. Each service account must be granted the `roles/iam.serviceAccountTokenCreator` role on its next service account in the chain. The last service account in the chain must be granted the `roles/iam.serviceAccountTokenCreator` role on the service account that is specified in the `name` field of the request. The delegates must have the following format: `projects/-/serviceAccounts/{ACCOUNT_EMAIL_OR_UNIQUEID}` . The `-` wildcard character is required; replacing it with a project ID is invalid. |
| `audience`                   | `string` Required. The audience for the token, such as the API or account that this token grants access to.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `includeEmail`               | `boolean` Include the service account email in the token. If set to `true` , the token will contain `email` and `email_verified` claims.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `organizationNumberIncluded` | `boolean` Include the organization number of the service account in the token. If set to `true` , the token will contain a `google.organization_number` claim. The value of the claim will be `null` if the service account isn't associated with an organization.                                                                                                                                                                                                                                                                                                             |

### Response body

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "token": string
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
<td><code>token</code></td>
<td><p><code>string</code></p>
<p>The OpenId Connect ID token.</p>
<p>The token is a JSON Web Token (JWT) that contains a payload with claims. See the <a href="https://tools.ietf.org/html/rfc7519">JSON Web Token spec</a> for more information. Here is an example of a decoded JWT payload:</p>
<pre data-fenced=""><code>{
  &quot;iss&quot;: &quot;https://accounts.google.com&quot;,
  &quot;iat&quot;: 1496953245,
  &quot;exp&quot;: 1496953245,
  &quot;aud&quot;: &quot;https://www.example.com&quot;,
  &quot;sub&quot;: &quot;107517467455664443765&quot;,
  &quot;azp&quot;: &quot;107517467455664443765&quot;,
  &quot;email&quot;: &quot;my-iam-account@my-project.iam.gserviceaccount.com&quot;,
  &quot;email_verified&quot;: true,
  &quot;google&quot;: {
    &quot;organization_number&quot;: 123456
  }
}</code></pre></td>
</tr>
</tbody>
</table>

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
