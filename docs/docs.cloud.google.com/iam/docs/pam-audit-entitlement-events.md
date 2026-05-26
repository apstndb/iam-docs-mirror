---
name: documents/docs.cloud.google.com/iam/docs/pam-audit-entitlement-events
uri: https://docs.cloud.google.com/iam/docs/pam-audit-entitlement-events
title: Audit entitlement and grant events in Privileged Access Manager
description: Use Privileged Access Manager (PAM) to manage just-in-time temporary privilege elevation for select principals, and view audit logs to find out who had access to what and when.
data_source: docs.cloud.google.com
---

To keep track of entitlement and grant events, you can view the Privileged Access Manager audit logs.

## Before you begin

Make sure you have [enabled Privileged Access Manager and set up permissions for it](https://docs.cloud.google.com/iam/docs/pam-permissions-and-setup) .

## View the Privileged Access Manager audit logs using the Google Cloud console

1.  Go to the **Privileged Access Manager** page.

2.  Select the organization, folder, or project you want to audit entitlement activity in.

3.  Click the **Audit logs** tab.

4.  To view details of the audited resource, click an entry in the **Action** column.

[Audit logs](https://docs.cloud.google.com/iam/docs/audit-logging) are also available in Cloud Audit Logs, and Privileged Access Manager can additionally write to [Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access) if Data Access audit logs are enabled.
