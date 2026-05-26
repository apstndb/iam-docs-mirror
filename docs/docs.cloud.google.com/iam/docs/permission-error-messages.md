---
name: documents/docs.cloud.google.com/iam/docs/permission-error-messages
uri: https://docs.cloud.google.com/iam/docs/permission-error-messages
title: Permission error messages
description: Learn why you encounter permission error messages and what the error messages mean
data_source: docs.cloud.google.com
---

This document describes the error messages that you might encounter if you don't have the required access permissions for a resource.

## Issues that cause permission error messages

The Google Cloud console, Google Cloud CLI, and REST API all display error messages when you try to access a resource that you don't have permission to access.

These error messages can be caused by any of the following:

  - **You don't have the required permissions.** You must have either an [allow policy role binding](https://docs.cloud.google.com/iam/docs/allow-policies) or an active [Privileged Access Manager entitlement](https://docs.cloud.google.com/iam/docs/pam-overview) for a role with the required permissions. If you don't have the required permissions, then Google Cloud displays an error message.

<!-- end list -->

  - **There's a deny policy blocking access.** If a [deny policy](https://docs.cloud.google.com/iam/docs/deny-access) prevents you from using any of the required permissions, then Google Cloud displays an error message.

<!-- end list -->

  - **You aren't eligible to access the resource.** If you're subject to any [principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) , then the resource that you're trying to access must be included in the policies' principal access boundary rules. If it isn't, then Google Cloud displays an error message.

<!-- end list -->

  - **The resource doesn't exist.** If the resource doesn't exist, then Google Cloud displays an error message.

The following sections show what these error messages look like for the Google Cloud console, gcloud CLI, and REST API.

### Google Cloud console error messages

In the Google Cloud console, error messages look similar to the following:

![](https://docs.cloud.google.com/static/iam/img/iam-error-message-2x.png)

These error messages contain the following information:

  - **The resource that you tried to access:** The resource name appears in the title of the error page and indicates the resource that you were trying to access when you encountered the permission error.
  - **The missing required permissions:** A list of the permissions that you need to have to access the resource.

<!-- end list -->

  - **A list of [Privileged Access Manager entitlements](https://docs.cloud.google.com/iam/docs/pam-overview) with roles that contain the required permissions:** This list is non-exhaustive—it contains only the top entitlements that Google Cloud suggests to resolve the access issue.
    
    This list is only available for permission errors that can be resolved by granting additional IAM roles.
    
    You can click an entitlement to learn more about the entitlement and to request a grant against the entitlement. To learn more, see [Request a Privileged Access Manager access grant](https://docs.cloud.google.com/iam/docs/resolve-permission-errors#allow-pam) .
    
    If no entitlements contain the required permissions, then the error message page doesn't include the list of entitlements.

<!-- end list -->

  - **A list of IAM roles that contain the required permissions:** This list is non-exhaustive—it contains a curated list of roles that Google Cloud suggests to resolve the access issue. Ordering is based on the type of actions permitted by the role, service relevance, and the number of permissions.
    
    If you have the [permissions required to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access#required-permissions) , then this section is titled **Select a role to grant** . If you don't have the required permissions, then this section is titled **Request a specific role** .
    
    You can click a role to learn more about the role and request that the role be granted to you. If you have the permissions required to grant roles, then you can grant yourself the role instead of requesting it.

### Google Cloud CLI and REST API error messages

The exact wording of the error message depends on the command that you run. However, it typically contains the following information:

  - The required permission
  - The resource you tried to perform an action on
  - The authenticating account

For example, if you don't have permission to list buckets in a project, you see an error message like the following:

### gcloud

    ERROR: (gcloud.storage.buckets.list) HTTPError 403:
    EMAIL_ADDRESS does not have
    storage.buckets.list access to the Google Cloud project. Permission
    'storage.buckets.list' denied on resource (or it may not exist). This command
    is authenticated as EMAIL_ADDRESS which
    is the active account specified by the [core/account] property.

### REST

    {
      "error": {
        "code": 403,
        "message": "EMAIL_ADDRESS does not have storage.buckets.list access to the Google Cloud project. Permission 'storage.buckets.list' denied on resource (or it may not exist).",
        "errors": [
          {
            "message": "EMAIL_ADDRESS does not have storage.buckets.list access to the Google Cloud project. Permission 'storage.buckets.list' denied on resource (or it may not exist).",
            "domain": "global",
            "reason": "forbidden"
          }
        ]
      }
    }

## What's next

  - If you don't have administrative permissions and you encounter a permission error message, see [Request missing permissions](https://docs.cloud.google.com/iam/docs/request-missing-permissions) .
  - If you have administrative permissions and need to resolve a user access request, see [Resolve permission errors](https://docs.cloud.google.com/iam/docs/resolve-permission-errors) .
