---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse
title: FetchEffectiveSettingsResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#SCHEMA_REPRESENTATION)
- [ServiceAccountApproverSettings](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ServiceAccountApproverSettings)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ServiceAccountApproverSettings.SCHEMA_REPRESENTATION)
- [EmailNotificationSettings](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#EmailNotificationSettings)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#EmailNotificationSettings.SCHEMA_REPRESENTATION)
- [DisableAllNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#DisableAllNotifications)
- [CustomNotificationBehavior](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#CustomNotificationBehavior)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#CustomNotificationBehavior.SCHEMA_REPRESENTATION)
- [RequesterNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#RequesterNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#RequesterNotifications.SCHEMA_REPRESENTATION)
- [AdminNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#AdminNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#AdminNotifications.SCHEMA_REPRESENTATION)
- [ApproverNotifications](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ApproverNotifications)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ApproverNotifications.SCHEMA_REPRESENTATION)

The effective value of the settings at the given location resource, evaluated based on the crm resource hierarchy.

**JSON representation**

```
{
  "parent": string,
  "serviceAccountApproverSettings": {
    object (ServiceAccountApproverSettings)
  },
  "emailNotificationSettings": {
    object (EmailNotificationSettings)
  }
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
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Output only. The resource on which the settings are effective. Possible formats:</p>
<ul>
<li><code>projects/{project-number|project-id}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceAccountApproverSettings</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ServiceAccountApproverSettings"><code>ServiceAccountApproverSettings</code></a><code> )</code></p>
<p>Output only. Effective settings for allowing service account as approvers.</p></td>
</tr>
<tr class="odd">
<td><code>emailNotificationSettings</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#EmailNotificationSettings"><code>EmailNotificationSettings</code></a><code> )</code></p>
<p>Output only. <code>EmailNotificationSettings</code> defines effective node-wide email notification preferences for various PAM events.</p></td>
</tr>
</tbody>
</table>

## ServiceAccountApproverSettings

This controls whether service accounts are allowed to approve grants or can be designated as approvers within PAM entitlements.

**JSON representation**

```
{
  "enabled": boolean,
  "source": string
}
```

| Fields    |                                                                                                                                                                                                                                                  |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `enabled` | `boolean` Output only. Indicates whether service account is allowed to grant approvals.                                                                                                                                                          |
| `source`  | `string` Output only. The resource from which the service account approver setting is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied. |

## EmailNotificationSettings

`EmailNotificationSettings` reflects the effective node-wide email notification settings.

**JSON representation**

```
{
  "source": string,

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

| Fields                                                                                                                 |                                                                                                                                                                                                                                                   |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `source`                                                                                                               | `string` Output only. The name of the resource from which the notification behavior is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied. |
| Union field `notification_behavior` . Notification behavior. `notification_behavior` can be only one of the following: |                                                                                                                                                                                                                                                   |
| `disableAllNotifications`                                                                                              | `object ( `[`DisableAllNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#DisableAllNotifications)` )` Output only. Disable all notifications.                                       |
| `customNotificationBehavior`                                                                                           | `object ( `[`CustomNotificationBehavior`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#CustomNotificationBehavior)` )` Output only. Granular settings of notifications.                        |

## DisableAllNotifications

This type has no fields.

This option indicates that all email notifications are disabled.

## CustomNotificationBehavior

`CustomNotificationBehavior` reflects the granular notification delivery settings for specific events and personas, as configured by the admin.

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

| Fields                   |                                                                                                                                                                                                               |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `requesterNotifications` | `object ( `[`RequesterNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#RequesterNotifications)` )` Output only. Requester email notifications. |
| `adminNotifications`     | `object ( `[`AdminNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#AdminNotifications)` )` Output only. Admin email notifications.             |
| `approverNotifications`  | `object ( `[`ApproverNotifications`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse#ApproverNotifications)` )` Output only. Approver email notifications.    |

## RequesterNotifications

Email notifications specific to Requesters.

**JSON representation**

```
{
  "notifyEntitlementAssigned": boolean,
  "notifyGrantActivated": boolean,
  "notifyGrantDenied": boolean,
  "notifyGrantExpired": boolean,
  "notifyGrantEnded": boolean,
  "notifyGrantRevoked": boolean,
  "notifyGrantExternallyModified": boolean,
  "notifyGrantActivationFailed": boolean,
  "notifyGrantActivationScheduled": boolean
}
```

| Fields                           |                                                                              |
|----------------------------------|------------------------------------------------------------------------------|
| `notifyEntitlementAssigned`      | `boolean` Output only. Notification delivery for entitlement assigned.       |
| `notifyGrantActivated`           | `boolean` Output only. Notification delivery for grant activated.            |
| `notifyGrantDenied`              | `boolean` Output only. Notification delivery for grant denied.               |
| `notifyGrantExpired`             | `boolean` Output only. Notification delivery for grant request expired.      |
| `notifyGrantEnded`               | `boolean` Output only. Notification delivery for grant ended.                |
| `notifyGrantRevoked`             | `boolean` Output only. Notification delivery for grant revoked.              |
| `notifyGrantExternallyModified`  | `boolean` Output only. Notification delivery for grant externally modified.  |
| `notifyGrantActivationFailed`    | `boolean` Output only. Notification delivery for grant activation failed.    |
| `notifyGrantActivationScheduled` | `boolean` Output only. Notification delivery for grant activation scheduled. |

## AdminNotifications

Email notifications specific to Admins.

**JSON representation**

```
{
  "notifyGrantActivated": boolean,
  "notifyGrantEnded": boolean,
  "notifyGrantExternallyModified": boolean,
  "notifyGrantActivationFailed": boolean,
  "notifyGrantActivationScheduled": boolean
}
```

| Fields                           |                                                                                        |
|----------------------------------|----------------------------------------------------------------------------------------|
| `notifyGrantActivated`           | `boolean` Output only. Notification delivery for grant activated.                      |
| `notifyGrantEnded`               | `boolean` Output only. Notification delivery for grant ended.                          |
| `notifyGrantExternallyModified`  | `boolean` Output only. Notification delivery for grant externally modified.            |
| `notifyGrantActivationFailed`    | `boolean` Output only. Notification delivery for grant activation failed.              |
| `notifyGrantActivationScheduled` | `boolean` Output only. Notification delivery for grant being scheduled for activation. |

## ApproverNotifications

Email notifications specific to Approvers.

**JSON representation**

```
{
  "notifyPendingApproval": boolean
}
```

| Fields                  |                                                                    |
|-------------------------|--------------------------------------------------------------------|
| `notifyPendingApproval` | `boolean` Output only. Notification delivery for pending approval. |
