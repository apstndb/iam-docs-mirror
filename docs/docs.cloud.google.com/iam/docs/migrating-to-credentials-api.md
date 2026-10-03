---
name: documents/docs.cloud.google.com/iam/docs/migrating-to-credentials-api
uri: https://docs.cloud.google.com/iam/docs/migrating-to-credentials-api
title: Migrating to the Service Account Credentials API
description: Migrate code for signing JWTs and binary blobs from the deprecated methods in the IAM API to the Service Account Credentials API. Update REST, client libraries, and gcloud.
data_source: docs.cloud.google.com
---

The [Service Account Credentials API](https://docs.cloud.google.com/iam/docs/reference/credentials/rest) creates short-lived credentials for Identity and Access Management (IAM) service accounts. You can also use this API to sign JSON Web Tokens (JWTs), as well as blobs of binary data that contain other types of tokens.

The [IAM API](https://docs.cloud.google.com/iam/docs/reference/rest) also contains methods for signing JWTs and binary blobs. As of July 1, 2020, these methods are deprecated in the REST API and in all [client libraries](https://docs.cloud.google.com/iam/docs/write-policy-client-libraries) for the IAM API. Also, if you use the Google Cloud CLI to sign JWTs, you might need to add a new claim to the JWT Claims Set. You can still use the deprecated methods, but they don't support advanced features like [HTTP request batching](https://developers.google.com/people/v1/batch) . We encourage you to migrate to the Service Account Credentials API instead.

Compared to the IAM API, the Service Account Credentials API provides more flexibility for the expiration time of signed JWTs. In addition, the Service Account Credentials API adds multiple new API methods to generate impersonation tokens.

This page explains how to update your existing code to use the Service Account Credentials API. If you have feedback on this change, you can [complete the feedback form](https://docs.google.com/forms/d/e/1FAIpQLScbtyMsPmVVHZjM2QH0jQLy3bteyd306EjJyW7OtU4Zeg-9yw/viewform) . You can also use the email address <iam-sign-deprecation-public@google.com> to request support and provide detailed feedback.

## Before you begin

- Enable the Service Account Credentials API, if it is not already enabled.

  **Roles required to enable APIs**

  To enable APIs, you need the `serviceusage.services.enable` permission. If you created the project, then you likely already have this permission through the Owner role ( `roles/owner` ). Otherwise, you can get this permission through the Service Usage Admin role ( `roles/serviceusage.serviceUsageAdmin` ). [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

## Enabling audit logs

If you want to receive [audit logs](https://docs.cloud.google.com/iam/docs/audit-logging) for requests to sign JWTs and blobs, you must [enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access) for the IAM API. Enabling Data Access audit logs for the IAM API also enables these audit logs for the Service Account Credentials API.

There are a few notable differences between the log entries that each API generates:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Differences for audit log entries</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Method name</td>
<td><p><strong>IAM API</strong></p>
<p>The method name ( <code>protoPayload.methodName</code> ) is one of the following:</p>
<ul>
<li><code>google.iam.admin.v1.SignBlob</code></li>
<li><code>google.iam.admin.v1.SignJwt</code></li>
</ul>
<p><strong>Service Account Credentials API</strong></p>
<p>The method name is one of the following:</p>
<ul>
<li><code>SignBlob</code></li>
<li><code>SignJwt</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Request type</td>
<td><p><strong>IAM API</strong></p>
<p>The request type ( <code>protoPayload.request.@type</code> ) is one of the following:</p>
<ul>
<li><code>type.googleapis.com/google.iam.admin.v1.SignBlobRequest</code></li>
<li><code>type.googleapis.com/google.iam.admin.v1.SignJwtRequest</code></li>
</ul>
<p><strong>Service Account Credentials API</strong></p>
<p>The request type is one of the following:</p>
<ul>
<li><code>type.googleapis.com/google.iam.credentials.v1.SignBlobRequest</code></li>
<li><code>type.googleapis.com/google.iam.credentials.v1.SignJwtRequest</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Service name</td>
<td><p><strong>IAM API</strong></p>
<p>The service name ( <code>protoPayload.serviceName</code> ) is <code>iam.googleapis.com</code> .</p>
<p><strong>Service Account Credentials API</strong></p>
<p>The service name is <code>iamcredentials.googleapis.com</code> .</p></td>
</tr>
</tbody>
</table>

Data Access audit logs count toward your free monthly allotment of logging data ingestion. If you exceed this allotment, you will be charged for log ingestion. For details, see [Pricing for Google Cloud Observability](https://docs.cloud.google.com/stackdriver/pricing) .

## Migrating code for signing JWTs

This section describes how to migrate code that signs JWTs to the Service Account Credentials API.

### Signing JWTs with the REST API

The following table shows the differences between [signing a JWT with the IAM REST API](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt) and [signing a JWT with the Service Account Credentials API](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signJwt) . Update your code to reflect these differences:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Differences for signing a JWT</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>HTTP endpoints</td>
<td><p><strong>IAM API</strong></p>
<p>The IAM API uses the following HTTP methods and endpoints:</p>
<ul>
<li><p><code>POST https://iam.googleapis.com/v1/projects/ </code><var translate="no"> project-id </var><code> / serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signJwt</code></p>
<p>In this URL, <var translate="no"> </var><code>project-id</code><var translate="no"> </var> is the project ID, and <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></li>
<li><p><code>POST https://iam.googleapis.com/v1/projects/-/ serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signJwt</code></p>
<p>In this URL, the wildcard character <code>-</code> takes the place of the project ID, and <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></li>
</ul>
<p><strong>Service Account Credentials API</strong></p>
<p>Use the following HTTP method and endpoint. <em>Do not</em> replace the wildcard character with the project ID:</p>
<p><code>POST https://iamcredentials.googleapis.com/v1/ projects/-/ serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signJwt</code></p>
<p>In this URL, <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></td>
</tr>
<tr class="even">
<td>Request body</td>
<td><p><strong>IAM API</strong></p>
<p>The request body includes a <code>payload</code> field. Its value is the JWT payload to sign. The payload must be a JSON object, serialized as a string, that contains a JWT Claims Set.</p>
<p>If you provide an expiration time ( <code>exp</code> ) claim, it must be no more than <em>12 hours</em> in the future. If you omit the <code>exp</code> claim, it <em>is added automatically</em> and is set to <em>1 hour</em> in the future.</p>
<p><strong>Service Account Credentials API</strong></p>
<p>The request body includes a <code>payload</code> field that is identical to the IAM API, except for the behavior of the expiration time ( <code>exp</code> ) claim:</p>
<ul>
<li>If you provide the <code>exp</code> claim, it must be no more than <em>12 hours</em> in the future.</li>
<li>If you omit the <code>exp</code> claim, it <em>is not added automatically</em> . <strong>You must provide this claim if you use the signed JWT to authenticate with Google APIs, or with another API that requires the <code>exp</code> claim.</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td>Response body</td>
<td><p>Both APIs use the same fields in the response body.</p></td>
</tr>
</tbody>
</table>

### Signing JWTs with a client library

The client libraries for the Service Account Credentials API are separate from the client libraries for the IAM API.

To use the Service Account Credentials API, add its client library to your application, and update your code to use the new client library:

### C#

Add the [Service Account Credentials client library for C#](https://googleapis.dev/dotnet/Google.Apis.IAMCredentials.v1/latest/api/Google.Apis.IAMCredentials.v1.html) to your application. Use the [`SignJwt()` method](https://googleapis.dev/dotnet/Google.Apis.IAMCredentials.v1/latest/api/Google.Apis.IAMCredentials.v1.ProjectsResource.ServiceAccountsResource.html) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for C#](https://developers.google.com/api-client-library/dotnet/apis/iam/v1/) , you can remove it from your application.

### Go

Add the [Service Account Credentials client library for Go](https://pkg.go.dev/cloud.google.com/go/iam/credentials/apiv1?tab=doc) to your application. Use the [`IamCredentialsClient.SignJwt() function`](https://pkg.go.dev/cloud.google.com/go/iam/credentials/apiv1?tab=doc#IamCredentialsClient.SignJwt) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Go](https://pkg.go.dev/google.golang.org/api/iam/v1?tab=doc) , you can remove it from your application.

### Java

Add the [Service Account Credentials client library for Java](https://github.com/googleapis/java-iamcredentials) to your application. Use the [`IamCredentialsClient#signJwt()` method](https://cloud.google.com/java/docs/reference/google-cloud-iamcredentials/latest/com.google.cloud.iam.credentials.v1.IamCredentialsClient#com_google_cloud_iam_credentials_v1_IamCredentialsClient_signJwt_com_google_cloud_iam_credentials_v1_ServiceAccountName_java_util_List_java_lang_String__java_lang_String_) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Java](https://github.com/googleapis/google-api-java-client-services/tree/master/clients/google-api-services-iam/v1) , you can remove it from your application.

### Node.js

Add the [Service Account Credentials client library for Node.js](https://github.com/googleapis/google-api-nodejs-client/tree/master/src/apis/iamcredentials) to your application. Use the [`signJwt()` method](https://googleapis.dev/nodejs/googleapis/latest/iamcredentials/classes/Resource$Projects$Serviceaccounts.html#signJwt) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Node.js](https://github.com/googleapis/google-api-nodejs-client/tree/master/src/apis/iam) , you can remove it from your application.

### PHP

Add the [Service Account Credentials client library for PHP](https://github.com/googleapis/google-api-php-client-services/tree/master/src/IAMCredentials) to your application. Use the [`signJwt()` method](https://github.com/googleapis/google-api-php-client-services/blob/master/src/IAMCredentials/Resource/ProjectsServiceAccounts.php) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for PHP](https://github.com/googleapis/google-api-php-client-services/tree/master/src/Iam) , you can remove it from your application.

### Python

Add the [Service Account Credentials client library for Python](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials) to your application. Use the [`sign_jwt()` method](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials.IAMCredentialsAsyncClient#google_cloud_iam_credentials_v1_services_iam_credentials_IAMCredentialsAsyncClient_sign_jwt) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [`iam_credentials` client library](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials) , you can remove it from your application.

### Ruby

Add the [Service Account Credentials client library for Ruby](https://github.com/googleapis/google-api-ruby-client/tree/master/generated/google-apis-iamcredentials_v1) to your application. Use the [`sign_service_account_jwt()` method](https://github.com/googleapis/google-api-ruby-client/blob/master/generated/google-apis-iamcredentials_v1/lib/google/apis/iamcredentials_v1/service.rb) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Ruby](https://github.com/googleapis/google-api-ruby-client/tree/master/generated/google-apis-iam_v1) , you can remove it from your application.

## Migrating code for signing binary blobs

This section describes how to migrate code that signs binary blobs to the Service Account Credentials API.

### Signing binary blobs with the REST API

The following table shows the differences between [signing a binary blob with the IAM REST API](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob) and [signing a binary blob with the Service Account Credentials API](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob) . Update your code to reflect these differences:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Differences for signing a binary blob</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>HTTP endpoints</td>
<td><p><strong>IAM API</strong></p>
<p>The IAM API uses the following HTTP methods and endpoints:</p>
<ul>
<li><p><code>POST https://iam.googleapis.com/v1/projects/ </code><var translate="no"> project-id </var><code> / serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signBlob</code></p>
<p>In this URL, <var translate="no"> </var><code>project-id</code><var translate="no"> </var> is the project ID, and <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></li>
<li><p><code>POST https://iam.googleapis.com/v1/projects/-/ serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signBlob</code></p>
<p>In this URL, the wildcard character <code>-</code> takes the place of the project ID, and <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></li>
</ul>
<p><strong>Service Account Credentials API</strong></p>
<p>Use the following HTTP method and endpoint. <em>Do not</em> replace the wildcard character with the project ID:</p>
<p><code>POST https://iamcredentials.googleapis.com/v1/ projects/-/ serviceAccounts/ </code><var translate="no"> sa-email </var><code> :signBlob</code></p>
<p>In this URL, <var translate="no"> </var><code>sa-email</code><var translate="no"> </var> is the email address for the service account.</p></td>
</tr>
<tr class="even">
<td>Request body</td>
<td><p><strong>IAM API</strong></p>
<p>The request body includes a <code>bytesToSign</code> field. Its value is a base64-encoded string that represents the binary blob to sign.</p>
<p><strong>Service Account Credentials API</strong></p>
<p>The request body includes a <code>payload</code> field that has the same value as the <code>bytesToSign</code> field in the IAM API.</p></td>
</tr>
<tr class="odd">
<td>Response body</td>
<td><p><strong>IAM API</strong></p>
<p>The response body contains a <code>keyId</code> field, which identifies the key that was used to sign the blob, and a <code>signature</code> field, which contains a base64-encoded string that represents the signature.</p>
<p><strong>Service Account Credentials API</strong></p>
<p>The response body contains a <code>keyId</code> field that is identical to the <code>keyId</code> field in the IAM API, as well as a <code>signedBlob</code> field that is identical to the <code>signature</code> field in the IAM API.</p>
<blockquote>
<strong>Note:</strong> The <code>signedBlob</code> field contains only the signature, not the original blob.
</blockquote></td>
</tr>
</tbody>
</table>

### Signing binary blobs with a client library

The client libraries for the Service Account Credentials API are separate from the client libraries for the IAM API.

To use the Service Account Credentials API, add its client library to your application, and update your code to use the new client library:

### C++

**If you use the Cloud Storage C++ client library to sign blobs,** either directly or as a dependency of another client library:

Upgrade to version 0.9.0 or later of [`google-cloud-cpp`](https://github.com/googleapis/google-cloud-cpp/tree/master/google/cloud/storage) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### C#

**If you use the [IAM client library for C#](https://developers.google.com/api-client-library/dotnet/apis/iam/v1/) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for C#](https://googleapis.dev/dotnet/Google.Apis.IAMCredentials.v1/latest/api/Google.Apis.IAMCredentials.v1.html) to your application. Use the [`SignBlob()` method](https://googleapis.dev/dotnet/Google.Apis.IAMCredentials.v1/latest/api/Google.Apis.IAMCredentials.v1.ProjectsResource.ServiceAccountsResource.html) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for C#](https://developers.google.com/api-client-library/dotnet/apis/iam/v1/) , you can remove it from your application.

**If you use the Firebase Admin DotNet SDK,** either directly or as a dependency of another client library:

Upgrade to version 1.17.1 or later of [`firebase-admin-dotnet`](https://github.com/firebase/firebase-admin-dotnet) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### Go

**If you use the [IAM client library for Go](https://pkg.go.dev/google.golang.org/api/iam/v1?tab=doc) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for Go](https://pkg.go.dev/cloud.google.com/go/iam/credentials/apiv1?tab=doc) to your application. Use the [`IamCredentialsClient.SignBlob() function`](https://pkg.go.dev/cloud.google.com/go/iam/credentials/apiv1?tab=doc#IamCredentialsClient.SignBlob) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Go](https://pkg.go.dev/google.golang.org/api/iam/v1?tab=doc) , you can remove it from your application.

**If you use the Firebase Admin Go SDK,** either directly or as a dependency of another client library:

Upgrade to version 4.1.0 or later of [`firebase-admin-go`](https://github.com/firebase/firebase-admin-go) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### Java

**If you use the [IAM client library for Java](https://github.com/googleapis/google-api-java-client-services/tree/master/clients/google-api-services-iam/v1) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for Java](https://github.com/googleapis/java-iamcredentials) to your application. Use the [`IamCredentialsClient#signBlob()` method](https://cloud.google.com/java/docs/reference/google-cloud-iamcredentials/latest/com.google.cloud.iam.credentials.v1.IamCredentialsClient#com_google_cloud_iam_credentials_v1_IamCredentialsClient_signBlob_java_lang_String_java_util_List_java_lang_String__com_google_protobuf_ByteString_) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Java](https://github.com/googleapis/google-api-java-client-services/tree/master/clients/google-api-services-iam/v1) , you can remove it from your application.

**If you use the Google Auth Library for Java,** either directly or as a dependency of another client library:

Upgrade to version 0.14.0 or later of [`google-auth-library-java`](https://github.com/googleapis/google-auth-library-java) .

**If you use the Firebase Admin Java SDK,** either directly or as a dependency of another client library:

Upgrade to version 7.0.1 or later of [`firebase-admin-java`](https://github.com/firebase/firebase-admin-java) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### Node.js

**If you use the [IAM client library for Node.js](https://github.com/googleapis/google-api-nodejs-client/tree/master/src/apis/iam) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for Node.js](https://github.com/googleapis/google-api-nodejs-client/tree/master/src/apis/iamcredentials) to your application. Use the [`signBlob()` method](https://googleapis.dev/nodejs/googleapis/latest/iamcredentials/classes/Resource$Projects$Serviceaccounts.html#signBlob) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Node.js](https://github.com/googleapis/google-api-nodejs-client/tree/master/src/apis/iam) , you can remove it from your application.

**If you use the Google Auth Library for Node.js,** either directly or as a dependency of another client library:

Upgrade to version 6.0.0 or later of [`google-auth-library-nodejs`](https://github.com/googleapis/google-auth-library-nodejs) .

**If you use the Firebase Admin Node.js SDK,** either directly or as a dependency of another client library:

Upgrade to version 8.13.0 or later of [`firebase-admin-node`](https://github.com/firebase/firebase-admin-node) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### PHP

**If you use the [IAM client library for PHP](https://github.com/googleapis/google-api-php-client-services/tree/master/src/Iam) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for PHP](https://github.com/googleapis/google-api-php-client-services/tree/master/src/IAMCredentials) to your application. Use the [`signBlob()` method](https://github.com/googleapis/google-api-php-client-services/blob/master/src/IAMCredentials/Resource/ProjectsServiceAccounts.php) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for PHP](https://github.com/googleapis/google-api-php-client-services/tree/master/src/Iam) , you can remove it from your application.

**If you use the Google Auth Library for PHP,** either directly or as a dependency of another client library:

Upgrade to version 1.5.0 or later of [`google-auth-library-php`](https://github.com/googleapis/google-auth-library-php) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### Python

**If you use the [IAM client library for Python](https://github.com/googleapis/python-iam) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for Python](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials) to your application. Use the [`sign_blob()` method](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials.IAMCredentialsAsyncClient#google_cloud_iam_credentials_v1_services_iam_credentials_IAMCredentialsAsyncClient_sign_blob) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [`iam_credentials` client library](https://docs.cloud.google.com/python/docs/reference/iam/latest/google.cloud.iam_credentials_v1.services.iam_credentials) , you can remove it from your application.

**If you use the Google Auth Library for Python,** either directly or as a dependency of another client library:

Upgrade to version 1.21.2 or later of [`google-auth`](https://github.com/googleapis/google-cloud-python/tree/main/packages/google-auth) .

**If you use the Python client for Cloud Storage,** either directly or as a dependency of another client library:

Upgrade to version 1.30.0 or later of [`python-storage`](https://github.com/googleapis/python-storage) .

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

### Ruby

**If you use the [IAM client library for Ruby](https://github.com/googleapis/google-api-ruby-client/tree/master/generated/google-apis-iam_v1) ,** either directly or as a dependency of another client library:

Add the [Service Account Credentials client library for Ruby](https://github.com/googleapis/google-api-ruby-client/tree/master/generated/google-apis-iamcredentials_v1) to your application. Use the [`sign_service_account_blob()` method](https://github.com/googleapis/google-api-ruby-client/blob/master/generated/google-apis-iamcredentials_v1/lib/google/apis/iamcredentials_v1/service.rb) to generate a signature.

The name of the service account must use the wildcard character `-` to represent the project ID:

Valid: Name with wildcard character

```
projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

Invalid: Name with project ID

```
projects/my-project/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com
```

If you no longer use the [IAM client library for Ruby](https://github.com/googleapis/google-api-ruby-client/tree/master/generated/google-apis-iam_v1) , you can remove it from your application.

**If you use another client library to sign blobs:**

Contact [`iam-sign-deprecation-public@google.com`](mailto:iam-sign-deprecation-public@google.com) for support.

## Migrating code that uses the gcloud CLI

The Google Cloud CLI provides commands that use the IAM API to sign JWTs and binary blobs, including the following:

- [`gcloud beta iam service-accounts sign-jwt`](https://docs.cloud.google.com/sdk/gcloud/reference/beta/iam/service-accounts/sign-jwt)
- [`gcloud iam service-accounts sign-blob`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/sign-blob)

On or after July 1, 2021, we will update these commands to use the Service Account Credentials API. This change will not affect commands to sign blobs.

**If you use the gcloud CLI to sign JWTs, you must follow these steps before July 1, 2021:**

1.  Check whether you include the expiration time ( `exp` ) claim in the JWT Claims Set.

    If you already include this claim, you do not need to make any changes. You can skip the remaining steps.

    If you do not include this claim, continue to the next step.

2.  Check whether you use the signed JWT to authenticate with Google APIs, or with another API that requires the `exp` claim.

    If you omit this claim, the IAM API automatically sets it to 1 hour in the future. In contrast, the Service Account Credentials API does not set this field automatically.

    If you are sure that you do not need the `exp` claim, you do not need to make any changes. You can skip the remaining steps.

    If you know that you need the `exp` claim, or if you aren't sure, continue to the next step.

3.  Update your code for creating JWTs so that it adds the `exp` claim to the JWT Claims Set.

    You can set the `exp` claim up to 1 hour in the future.

## Checking quotas

Quota for the Service Account Credentials API is separate from quota for the IAM API. If you have received a quota increase to sign JWTs and blobs with the IAM API, you might also need to request an increase for the Service Account Credentials API.

> **Note:** Most Google Cloud customers use the default quota for signing JWTs and blobs. If you use the default quota, you do not need to read this section.

To view your quota and actual usage for both APIs, and to request a quota increase if necessary, do the following:

1.  In the Google Cloud console, go to the **Quotas** page.

2.  Select a project. You can click a recent project, or you can click **Select project** to search all of your projects.

3.  In the **Filter table** text box above the table, enter `Sign requests per minute` , then select the value that appears.

4.  In the **Filter table** text box, select **OR** from the drop-down list.

5.  In the **Filter table** text box, enter `Generate credentials` , then select the value that appears.

    The Google Cloud console shows your current usage for signing JWTs and blobs over the past minute; your peak usage per minute over the past 7 days; and your current quota, which appears in the **Limit** column.

6.  Compare the quotas for each row in the table, and ensure that your quota for the Service Account Credentials API is higher than your 7-day peak usage of the IAM API.

7.  Optional: If your quota for the Service Account Credentials API is too low, select the checkbox for the Service Account Credentials API, then click **Edit quotas** . Complete the form to request a quota increase.

8.  Repeat these steps for each project where you use the IAM API to sign JWTs and blobs.

## What's next

- Find out how to [create a signed JWT](https://docs.cloud.google.com/iam/docs/creating-short-lived-service-account-credentials#sa-credentials-jwt) or [create a signed binary blob](https://docs.cloud.google.com/iam/docs/creating-short-lived-service-account-credentials#sa-credentials-blob) with the Service Account Credentials REST API.
- Get details about the [REST API for the Service Account Credentials API](https://docs.cloud.google.com/iam/docs/reference/credentials/rest) .
- Understand [quotas and limits for IAM](https://docs.cloud.google.com/iam/quotas) .
