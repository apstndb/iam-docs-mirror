---
name: documents/docs.cloud.google.com/iam/docs/workforce-revoke-sessions
uri: https://docs.cloud.google.com/iam/docs/workforce-revoke-sessions
title: Revoke Workforce Identity Federation user sessions
description: Revoke active user sessions and credentials for Workforce Identity Federation users. Understand required permissions and how to revoke sessions using gcloud and the REST API.
data_source: docs.cloud.google.com
---

This guide shows you how to revoke active sessions and short-lived credentials for workforce users (also known as workforce principals).

Revoking sessions immediately invalidates active sessions and credentials. However, it doesn't delete user metadata or resources, or prevent subsequent sign-ins if the user remains active in your identity provider (IdP).

Revoking sessions is useful in scenarios such as the following:

- **Suspected credential compromise** : You suspect that a user's active session or credentials are compromised and must immediately cut off access.
- **Offboarding or role transitions** : You must immediately terminate access for a user who is leaving the organization or changing roles, while identity deletion or group updates are in progress. Because [deleting a user](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data) initiates an asynchronous 30-day soft-deletion process, revoke sessions to immediately terminate a user's active access.
- **Immediate policy enforcement** : You modified user permissions or group memberships in your IdP and want the user to re-authenticate immediately so that updated session attributes and group memberships take effect.

## Before you begin

[Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI. After installation, [initialize](https://docs.cloud.google.com/sdk/docs/initializing) the Google Cloud CLI by running the following command:

```
gcloud init
```

If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .

> **Note:** If you installed the gcloud CLI previously, make sure you have the latest version by running `gcloud components update` .

### Required roles

To get the permission that you need to revoke workforce user sessions, ask your administrator to grant you the [Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` ) IAM role on the organization or workforce pool. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the `iam.googleapis.com/workforcePoolSubjects.revokeSessions` permission, which is required to revoke workforce user sessions.

You might also be able to get this permission with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Revoke user sessions

Revoking a workforce user's sessions immediately invalidates all active Google Cloud console sessions, session cookies, short-lived OAuth 2.0 access tokens, and credentials issued for that user subject, requiring the user to re-authenticate with your identity provider (IdP).

To revoke sessions for a workforce user, do the following:

### gcloud

The [`gcloud iam workforce-pools subjects revoke-sessions`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/revoke-sessions) command revokes active sessions and short-lived credentials for a workforce pool subject.

Before using any of the command data below, make the following replacements:

- `SUBJECT_ID` : The user subject ID whose sessions you want to revoke. If you are retrieving the user's identity from Cloud Audit Logs or IAM allow policies, the subject ID is the final segment of the user's principal identifier, which has the following format: `principal://iam.googleapis.com/locations/ `` LOCATION `` /workforcePools/ `` WORKFORCE_POOL_ID `` /subject/ `` SUBJECT_ID` .
- `WORKFORCE_POOL_ID` : The workforce pool ID.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workforce-pools subjects revoke-sessions \
    SUBJECT_ID \
    --workforce-pool=WORKFORCE_POOL_ID \
    --location=global
```

#### Windows (PowerShell)

```
gcloud iam workforce-pools subjects revoke-sessions `
    SUBJECT_ID `
    --workforce-pool=WORKFORCE_POOL_ID `
    --location=global
```

#### Windows (cmd.exe)

```
gcloud iam workforce-pools subjects revoke-sessions ^
    SUBJECT_ID ^
    --workforce-pool=WORKFORCE_POOL_ID ^
    --location=global
```

### REST

The [`locations.workforcePools.subjects.revokeSessions`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions) method revokes active sessions and short-lived credentials for a workforce pool subject.

Before using any of the request data, make the following replacements:

- `SUBJECT_ID` : The user subject ID whose sessions you want to revoke. If you are retrieving the user's identity from Cloud Audit Logs or IAM allow policies, the subject ID is the final segment of the user's principal identifier, which has the following format: `principal://iam.googleapis.com/locations/ `` LOCATION `` /workforcePools/ `` WORKFORCE_POOL_ID `` /subject/ `` SUBJECT_ID` .
- `WORKFORCE_POOL_ID` : The workforce pool ID.

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/locations/global/workforcePools/WORKFORCE_POOL_ID/subjects/SUBJECT_ID:revokeSessions
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d "" \
     "https://iam.googleapis.com/v1/locations/global/workforcePools/WORKFORCE_POOL_ID/subjects/SUBJECT_ID:revokeSessions"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/locations/global/workforcePools/WORKFORCE_POOL_ID/subjects/SUBJECT_ID:revokeSessions" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/revokeSessions) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

If the request is successful, the response body is empty.

```
{}
```

## What's next

- [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data)
- [Manage workforce identity pools and providers](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers)
- [Obtain short-lived credentials for Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials)
- [Best practices for using Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/best-practices-workforce-identity-federation)
