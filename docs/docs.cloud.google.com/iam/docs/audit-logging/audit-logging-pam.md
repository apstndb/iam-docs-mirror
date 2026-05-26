---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/audit-logging-pam
uri: https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-pam
title: Privileged Access Manager audit logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes audit logging for Privileged Access Manager. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Service name

Privileged Access Manager audit logs use the service name `privilegedaccessmanager.googleapis.com` . Filter for this service:

``` 
    protoPayload.serviceName="privilegedaccessmanager.googleapis.com"
  
```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, Privileged Access Manager generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

API methods in the following list that are marked with (LRO) are long-running operations (LROs). These methods usually generate two audit log entries: one when the operation starts and another when it ends. For more information see [Audit logs for long-running operations](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission type</th>
<th>Methods</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">ADMIN_READ</code></td>
<td><code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CheckOnboardingStatus</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetEntitlement</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListEntitlements</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListGrants</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CheckOnboardingStatus</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetEntitlement</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListEntitlements</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListGrants</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CheckOnboardingStatus</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetEntitlement</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListEntitlements</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListGrants</code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">ADMIN_WRITE</code></td>
<td><code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ApproveGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DeleteEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DenyGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.RevokeGrant</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.UpdateEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ApproveGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DeleteEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DenyGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.RevokeGrant</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.UpdateEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ApproveGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DeleteEntitlement</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DenyGrant</code><br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.RevokeGrant</code> (LRO)<br />
<code dir="ltr" translate="no">google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.UpdateEntitlement</code> (LRO)</td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for Privileged Access Manager.

### `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager`

The following audit logs are associated with methods belonging to `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager` .

#### `ApproveGrant`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ApproveGrant`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.approve - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ApproveGrant"`  

#### `CheckOnboardingStatus`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CheckOnboardingStatus`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.locations.checkOnboardingStatus - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CheckOnboardingStatus"`  

#### `CreateEntitlement`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateEntitlement`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateEntitlement"`  

#### `CreateGrant`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateGrant`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.CreateGrant"`  

#### `DeleteEntitlement`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DeleteEntitlement`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DeleteEntitlement"`  

#### `DenyGrant`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DenyGrant`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.deny - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.DenyGrant"`  

#### `GetEntitlement`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetEntitlement`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetEntitlement"`  

#### `GetGrant`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetGrant`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.GetGrant"`  

#### `ListEntitlements`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListEntitlements`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListEntitlements"`  

#### `ListGrants`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListGrants`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.ListGrants"`  

#### `RevokeGrant`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.RevokeGrant`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.revoke - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.RevokeGrant"`  

#### `UpdateEntitlement`

  - **Method** : `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.UpdateEntitlement`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.UpdateEntitlement"`  

### `google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager`

The following audit logs are associated with methods belonging to `google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager` .

#### `ApproveGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ApproveGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.approve - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ApproveGrant"`  

#### `CheckOnboardingStatus`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CheckOnboardingStatus  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.locations.checkOnboardingStatus - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CheckOnboardingStatus"`  

#### `CreateEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateEntitlement"`  

#### `CreateGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.CreateGrant"`  

#### `DeleteEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DeleteEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DeleteEntitlement"`  

#### `DenyGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DenyGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.deny - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.DenyGrant"`  

#### `GetEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetEntitlement  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetEntitlement"`  

#### `GetGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetGrant  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.GetGrant"`  

#### `ListEntitlements`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListEntitlements  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListEntitlements"`  

#### `ListGrants`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListGrants  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.ListGrants"`  

#### `RevokeGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.RevokeGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.revoke - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.RevokeGrant"`  

#### `UpdateEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.UpdateEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.UpdateEntitlement"`  

### `google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager`

The following audit logs are associated with methods belonging to `google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager` .

#### `ApproveGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ApproveGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.approve - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ApproveGrant"`  

#### `CheckOnboardingStatus`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CheckOnboardingStatus  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.locations.checkOnboardingStatus - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CheckOnboardingStatus"`  

#### `CreateEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateEntitlement"`  

#### `CreateGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.CreateGrant"`  

#### `DeleteEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DeleteEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DeleteEntitlement"`  

#### `DenyGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DenyGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.deny - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.DenyGrant"`  

#### `GetEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetEntitlement  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetEntitlement"`  

#### `GetGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetGrant  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.GetGrant"`  

#### `ListEntitlements`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListEntitlements  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListEntitlements"`  

#### `ListGrants`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListGrants  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.ListGrants"`  

#### `RevokeGrant`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.RevokeGrant  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.grants.revoke - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.RevokeGrant"`  

#### `UpdateEntitlement`

  - **Method** : `  google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.UpdateEntitlement  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `privilegedaccessmanager.entitlements.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.UpdateEntitlement"`  

## System events

System Event audit logs are generated by GCP systems, not direct user action. For more information, see [System Event audit logs](https://docs.cloud.google.com/logging/docs/audit#system-event) .

| Method Name                        | Filter For This Event                                          | Notes |
| ---------------------------------- | -------------------------------------------------------------- | ----- |
| PAMActivateGrant                   | `protoPayload.methodName="PAMActivateGrant"`                   |       |
| PAMDeleteGrant                     | `protoPayload.methodName="PAMDeleteGrant"`                     |       |
| PAMEndGrant                        | `protoPayload.methodName="PAMEndGrant"`                        |       |
| PAMExpireGrant                     | `protoPayload.methodName="PAMExpireGrant"`                     |       |
| PAMReportExternalGrantModification | `protoPayload.methodName="PAMReportExternalGrantModification"` |       |

## Methods that don't produce audit logs

A method might not produce audit logs for one or more of the following reasons:

  - It is a high volume method involving significant log generation and storage costs.
  - It has low auditing value.
  - Another audit or platform log already provides method coverage.

The following methods don't produce audit logs:

  - `google.cloud.location.Locations.GetLocation`
  - `google.cloud.location.Locations.ListLocations`
  - `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.SearchEntitlements`
  - `google.cloud.privilegedaccessmanager.v1.PrivilegedAccessManager.SearchGrants`
  - `google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.SearchEntitlements`
  - `google.cloud.privilegedaccessmanager.v1alpha.PrivilegedAccessManager.SearchGrants`
  - `google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.SearchEntitlements`
  - `google.cloud.privilegedaccessmanager.v1beta.PrivilegedAccessManager.SearchGrants`
  - `google.longrunning.Operations.CancelOperation`
  - `google.longrunning.Operations.DeleteOperation`
  - `google.longrunning.Operations.GetOperation`
  - `google.longrunning.Operations.ListOperations`
  - `google.longrunning.Operations.WaitOperation`
