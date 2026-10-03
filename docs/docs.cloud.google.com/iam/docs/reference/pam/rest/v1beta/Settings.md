---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings
title: Settings
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#SCHEMA_REPRESENTATION)
- [ServiceAccountApproverSettings](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ServiceAccountApproverSettings)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ServiceAccountApproverSettings.SCHEMA_REPRESENTATION)
- [EmailNotificationSettings](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#EmailNotificationSettings)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#EmailNotificationSettings.SCHEMA_REPRESENTATION)
- [DisableAllNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#DisableAllNotifications)
- [CustomNotificationBehavior](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#CustomNotificationBehavior)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#CustomNotificationBehavior.SCHEMA_REPRESENTATION)
- [RequesterNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#RequesterNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#RequesterNotifications.SCHEMA_REPRESENTATION)
- [NotificationMode](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)
- [AdminNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#AdminNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#AdminNotifications.SCHEMA_REPRESENTATION)
- [ApproverNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ApproverNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ApproverNotifications.SCHEMA_REPRESENTATION)

`Settings` resource defines the properties, applied directly to the resource or inherited through the hierarchy, to enable consistent, federated use of PAM.

The behavior is as follows: 1. If explicitly set to empty at the node level, PAM's default settings are applied for that node. 2. If not set at the node level, settings are inherited from the closest ancestor with a non-empty value. If none of the ancestors has the field set, PAM's default settings are applied. 3. If explicitly set to a non-empty value at the node level, the specified settings are applied for that node.

**JSON representation**

```
{
  "name": string,
  "createTime": string,
  "updateTime": string,
  "etag": string,
  "serviceAccountApproverSettings": {
    object (ServiceAccountApproverSettings)
  },
  "emailNotificationSettings": {
    object (EmailNotificationSettings)
  }
}
```

| Fields                           |                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                           | `string` Identifier. Name of the settings resource. Possible formats: projects/{project-id\|project-number}/locations/{location}/settings folders/{folder-number}/locations/{location}/settings organizations/{organization-number}/locations/{location}/settings                                                                                                                                    |
| `createTime`                     | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. Create timestamp. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `updateTime`                     | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. Update timestamp. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `etag`                           | `string` Fingerprint for optimistic concurrency returned in the response of `GetSettings` . Must be provided in the requests to `UpdateSettings` . If the value provided does not match the value known to the server, ABORTED will be thrown, and the client should retry the read-modify-write cycle.                                                                                              |
| `serviceAccountApproverSettings` | `object ( `[`ServiceAccountApproverSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ServiceAccountApproverSettings)` )` Optional. This controls the node-level settings for allowing service accounts as approvers.                                                                                                                                              |
| `emailNotificationSettings`      | `object ( `[`EmailNotificationSettings`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#EmailNotificationSettings)` )` Optional. `EmailNotificationSettings` defines node-wide email notification preferences for various PAM events.                                                                                                                                     |

## ServiceAccountApproverSettings

This controls whether service accounts are allowed to approve grants or can be designated as approvers within PAM entitlements.

**JSON representation**

```
{
  "enabled": boolean
}
```

| Fields    |                                                                                      |
|-----------|--------------------------------------------------------------------------------------|
| `enabled` | `boolean` Optional. Indicates whether service account is allowed to grant approvals. |

## EmailNotificationSettings

`EmailNotificationSettings` defines the node-wide email notification settings.

**JSON representation**

```
{

  // Union field notification_behavior can be only one of the following:
  "disableAllNotifications": {
    object (DisableAllNotifications)
  },
  "customNotificationBehavior": {
    object (CustomNotificationBehavior)
  }
  // End of list of possible types for union field notification_behavior.
}
```

| Fields                                                                                                                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                         |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `notification_behavior` . Notification behavior. 1. If set to `DisableAllNotifications` , all notifications are disabled for the node. 2. If set to `CustomNotificationBehavior` , notifications are customized as per the specified settings. 3. If notification_behavior is not set (none of the options selected), PAM's default settings are applied for that node. `notification_behavior` can be only one of the following: |                                                                                                                                                                                         |
| `disableAllNotifications`                                                                                                                                                                                                                                                                                                                                                                                                                     | `object ( `[`DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#DisableAllNotifications)` )` Disable all notifications.                |
| `customNotificationBehavior`                                                                                                                                                                                                                                                                                                                                                                                                                  | `object ( `[`CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#CustomNotificationBehavior)` )` Granular settings of notifications. |

## DisableAllNotifications

This type has no fields.

This option indicates that all email notifications are disabled.

## CustomNotificationBehavior

`CustomNotificationBehavior` provides granular control over email notification delivery. Allows admins to selectively enable/disable notifications for specific events and specific personas.

**JSON representation**

```
{
  "requesterNotifications": {
    object (RequesterNotifications)
  },
  "adminNotifications": {
    object (AdminNotifications)
  },
  "approverNotifications": {
    object (ApproverNotifications)
  }
}
```

| Fields                   |                                                                                                                                                                                      |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `requesterNotifications` | `object ( `[`RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#RequesterNotifications)` )` Optional. Requester email notifications. |
| `adminNotifications`     | `object ( `[`AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#AdminNotifications)` )` Optional. Admin email notifications.             |
| `approverNotifications`  | `object ( `[`ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#ApproverNotifications)` )` Optional. Approver email notifications.    |

## RequesterNotifications

Email notifications specific to Requesters.

**JSON representation**

```
{
  "entitlementAssigned": enum (NotificationMode),
  "grantActivated": enum (NotificationMode),
  "grantDenied": enum (NotificationMode),
  "grantExpired": enum (NotificationMode),
  "grantEnded": enum (NotificationMode),
  "grantRevoked": enum (NotificationMode),
  "grantExternallyModified": enum (NotificationMode),
  "grantActivationFailed": enum (NotificationMode),
  "grantActivationScheduled": enum (NotificationMode)
}
```

| Fields                     |                                                                                                                                                                                           |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `entitlementAssigned`      | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for entitlement assigned.       |
| `grantActivated`           | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activated.            |
| `grantDenied`              | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant denied.               |
| `grantExpired`             | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant request expired.      |
| `grantEnded`               | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant ended.                |
| `grantRevoked`             | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant revoked.              |
| `grantExternallyModified`  | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant externally modified.  |
| `grantActivationFailed`    | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activation failed.    |
| `grantActivationScheduled` | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activation scheduled. |

## NotificationMode

`NotificationMode` represents the notification delivery setting.

| Enums                           |                                                                  |
|---------------------------------|------------------------------------------------------------------|
| `NOTIFICATION_MODE_UNSPECIFIED` | Default notification behavior following PAM's standard settings. |
| `ENABLED`                       | Notifications are enabled.                                       |
| `DISABLED`                      | Notifications are disabled.                                      |

## AdminNotifications

Email notifications specific to Admins.

**JSON representation**

```
{
  "grantActivated": enum (NotificationMode),
  "grantEnded": enum (NotificationMode),
  "grantExternallyModified": enum (NotificationMode),
  "grantActivationFailed": enum (NotificationMode),
  "grantActivationScheduled": enum (NotificationMode)
}
```

| Fields                     |                                                                                                                                                                                           |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `grantActivated`           | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activated.            |
| `grantEnded`               | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant ended.                |
| `grantExternallyModified`  | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant externally modified.  |
| `grantActivationFailed`    | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activation failed.    |
| `grantActivationScheduled` | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for grant activation scheduled. |

## ApproverNotifications

Email notifications specific to Approvers.

**JSON representation**

```
{
  "pendingApproval": enum (NotificationMode)
}
```

| Fields            |                                                                                                                                                                                 |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pendingApproval` | `enum ( `[`NotificationMode`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/Settings#NotificationMode)` )` Optional. Notification mode for pending approval. |
