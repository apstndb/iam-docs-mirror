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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;parent&quot;: string,&quot;serviceAccountApproverSettings&quot;: {object (ServiceAccountApproverSettings)},&quot;emailNotificationSettings&quot;: {object (EmailNotificationSettings)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`parent`

`string`

Output only. The resource on which the settings are effective. Possible formats:

  - `projects/{project-number|project-id}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `organizations/{organization-number}/locations/{region}`

`serviceAccountApproverSettings`

` object ( ServiceAccountApproverSettings  ` )

Output only. Effective settings for allowing service account as approvers.

`emailNotificationSettings`

` object ( EmailNotificationSettings  ` )

Output only. `EmailNotificationSettings` defines effective node-wide email notification preferences for various PAM events.

## ServiceAccountApproverSettings

This controls whether service accounts are allowed to approve grants or can be designated as approvers within PAM entitlements.

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
  &quot;enabled&quot;: boolean,
  &quot;source&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`enabled`

`boolean`

Output only. Indicates whether service account is allowed to grant approvals.

`source`

`string`

Output only. The resource from which the service account approver setting is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied.

## EmailNotificationSettings

`EmailNotificationSettings` reflects the effective node-wide email notification settings.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;source&quot;: string,// Union field notification_behavior can be only one of the following:&quot;disableAllNotifications&quot;: {object (DisableAllNotifications)},&quot;customNotificationBehavior&quot;: {object (CustomNotificationBehavior)}// End of list of possible types for union field notification_behavior.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`source`

`string`

Output only. The name of the resource from which the notification behavior is inherited. This field remains empty if the setting is not defined at either the parent or resource level, in which case PAM's default behavior is applied.

Union field `notification_behavior` . Notification behavior. `notification_behavior` can be only one of the following:

`disableAllNotifications`

` object ( DisableAllNotifications  ` )

Output only. Disable all notifications.

`customNotificationBehavior`

` object ( CustomNotificationBehavior  ` )

Output only. Granular settings of notifications.

## DisableAllNotifications

This type has no fields.

This option indicates that all email notifications are disabled.

## CustomNotificationBehavior

`CustomNotificationBehavior` reflects the granular notification delivery settings for specific events and personas, as configured by the admin.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;requesterNotifications&quot;: {object (RequesterNotifications)},&quot;adminNotifications&quot;: {object (AdminNotifications)},&quot;approverNotifications&quot;: {object (ApproverNotifications)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`requesterNotifications`

` object ( RequesterNotifications  ` )

Output only. Requester email notifications.

`adminNotifications`

` object ( AdminNotifications  ` )

Output only. Admin email notifications.

`approverNotifications`

` object ( ApproverNotifications  ` )

Output only. Approver email notifications.

## RequesterNotifications

Email notifications specific to Requesters.

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
  &quot;notifyEntitlementAssigned&quot;: boolean,
  &quot;notifyGrantActivated&quot;: boolean,
  &quot;notifyGrantDenied&quot;: boolean,
  &quot;notifyGrantExpired&quot;: boolean,
  &quot;notifyGrantEnded&quot;: boolean,
  &quot;notifyGrantRevoked&quot;: boolean,
  &quot;notifyGrantExternallyModified&quot;: boolean,
  &quot;notifyGrantActivationFailed&quot;: boolean,
  &quot;notifyGrantActivationScheduled&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`notifyEntitlementAssigned`

`boolean`

Output only. Notification delivery for entitlement assigned.

`notifyGrantActivated`

`boolean`

Output only. Notification delivery for grant activated.

`notifyGrantDenied`

`boolean`

Output only. Notification delivery for grant denied.

`notifyGrantExpired`

`boolean`

Output only. Notification delivery for grant request expired.

`notifyGrantEnded`

`boolean`

Output only. Notification delivery for grant ended.

`notifyGrantRevoked`

`boolean`

Output only. Notification delivery for grant revoked.

`notifyGrantExternallyModified`

`boolean`

Output only. Notification delivery for grant externally modified.

`notifyGrantActivationFailed`

`boolean`

Output only. Notification delivery for grant activation failed.

`notifyGrantActivationScheduled`

`boolean`

Output only. Notification delivery for grant activation scheduled.

## AdminNotifications

Email notifications specific to Admins.

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
  &quot;notifyGrantActivated&quot;: boolean,
  &quot;notifyGrantEnded&quot;: boolean,
  &quot;notifyGrantExternallyModified&quot;: boolean,
  &quot;notifyGrantActivationFailed&quot;: boolean,
  &quot;notifyGrantActivationScheduled&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`notifyGrantActivated`

`boolean`

Output only. Notification delivery for grant activated.

`notifyGrantEnded`

`boolean`

Output only. Notification delivery for grant ended.

`notifyGrantExternallyModified`

`boolean`

Output only. Notification delivery for grant externally modified.

`notifyGrantActivationFailed`

`boolean`

Output only. Notification delivery for grant activation failed.

`notifyGrantActivationScheduled`

`boolean`

Output only. Notification delivery for grant being scheduled for activation.

## ApproverNotifications

Email notifications specific to Approvers.

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
  &quot;notifyPendingApproval&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`notifyPendingApproval`

`boolean`

Output only. Notification delivery for pending approval.
