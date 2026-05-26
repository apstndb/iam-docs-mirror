---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/examples-oauth-clients
uri: https://docs.cloud.google.com/iam/docs/audit-logging/examples-oauth-clients
title: Example logs for Workforce Identity Federation OAuth application integration
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page provides examples of the audit logs that are generated when you use [Workforce Identity Federation OAuth application integration](https://docs.cloud.google.com/iam/docs/workforce-oauth-app) . With Workforce Identity Federation OAuth application integration, you can allow third-party applications to integrate with Google Cloud through OAuth and use external identities to access Google Cloud resources.

Each of the following examples shows only the most relevant fields in the log entries.

For more information about enabling and viewing audit logs, see [Identity and Access Management audit logging](https://docs.cloud.google.com/iam/docs/audit-logging) .

## Required roles

IAM can generate audit logs when you create and manage OAuth clients. To enable audit logs when managing OAuth clients, you must [enable audit logs for Data Access activity](https://docs.cloud.google.com/iam/docs/audit-logging#enabling_audit_logging) for the following API:

  - Identity and Access Management API (enable log type "ADMIN\_READ")

## Logs for creating an OAuth client

The log entry is similar to the following:

    {
      "logName": "projects/PROJECT_NUMBER/logs/cloudaudit.googleapis.com%2Factivity",
      "protoPayload": {
        "@type": "type.googleapis.com/google.cloud.audit.AuditLog",
        "authenticationInfo": {
          "principalEmail": PRINCIPAL_EMAIL,
        },
        "methodName": "google.iam.admin.v1.OauthClients.CreateOauthClient",
        "resourceName": "projects/PROJECT_NUMBER/locations/global",
        "serviceName": "iam.googleapis.com",
        "request": {
          "@type": "type.googleapis.com/google.iam.admin.v1.CreateOauthClientRequest",
          "oauthClient": {},
          "oauthClientId": OAUTH_CLIENT_ID,
          "parent": "projects/PROJECT_NUMBER/locations/global"
        }
      },
      "resource": {
        "type": "audited_resource"
      }
    }

This log entry includes the following values, which you can use to filter logs:

  - PROJECT\_NUMBER : the project number of the project that contains the OAuth application integration.

  - PRINCIPAL\_EMAIL : the email address of the principal that owns the OAuth client.

  - OAUTH\_CLIENT\_ID : the identity of the OAuth client

## Logs for creating an OAuth client credential

The log entry is similar to the following:

    {
      "logName": "projects/PROJECT_NUMBER/logs/cloudaudit.googleapis.com%2Factivity",
      "protoPayload": {
        "@type": "type.googleapis.com/google.cloud.audit.AuditLog",
        "authenticationInfo": {
          "principalEmail": PRINCIPAL_EMAIL,
        },
        "methodName": "google.iam.admin.v1.OauthClients.CreateOauthClientCredential",
        "resourceName": "projects/PROJECT_NUMBER/locations/global/oauthClients/OAUTH_CLIENT_ID",
        "serviceName": "iam.googleapis.com",
        "request": {
          "@type": "type.googleapis.com/google.iam.admin.v1.CreateOauthClientCredentialRequest",
          "oauthClientCredential": {},
          "oauthClientCredentialId": OAUTH_CLIENT_CREDENTIAL_ID,
          "parent": "projects/PROJECT_NUMBER/locations/global/oauthClients/OAUTH_CLIENT_ID"
        }
      },
      "resource": {
        "type": "audited_resource"
      }
    }

This log entry includes the following values, which you can use to filter logs:

  - PROJECT\_NUMBER : the project number of the project that contains the OAuth application integration.

  - PRINCIPAL\_EMAIL : the email address of the principal that (owns|accessed) the OAuth client.

  - OAUTH\_CLIENT\_ID : the identity of the OAuth client

  - OAUTH\_CLIENT\_CREDENTIAL\_ID : the identity of the OAuth client credential

## What's next

  - [Configure and view the audit logs](https://docs.cloud.google.com/iam/docs/audit-logging) for IAM.
  - Get more information about [Cloud Audit Logs](https://docs.cloud.google.com/logging/docs/audit) .
  - Set up [Workforce OAuth application integration](https://docs.cloud.google.com/iam/docs/workforce-oauth-app) using OAuth clients.
