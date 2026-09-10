---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/audit-logging-agentidentity
uri: https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-agentidentity
title: Agent Identity API audit logging
description: Lists the audited methods for the Agent Identity API and Agent Identity Credentials API.
data_source: docs.cloud.google.com
---

This document lists the audited methods for Agent Identity API. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Service name

To view the Agent Identity API audit logs, do the following:

1.  In the Google Cloud console, go to the Logs Explorer page:

2.  Copy and paste the following query into the **Query** field of the Logs Explorer, and then click **Run query** .
    
    ``` 
        protoPayload.serviceName="agentidentity.googleapis.com"
      
    ```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, Agent Identity API generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

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
<td><code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.GetAccessSummary</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.GetAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.GetAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.ListAccessSummaries</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.ListAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.ListAuthorizations</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.QueryAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.QueryWorkloads</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.GetAccessSummary</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.ListAccessSummaries</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthorizations</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.QueryAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.QueryWorkloads</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.GetAccessSummary</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.ListAccessSummaries</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthorizations</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.QueryAuthProviders</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.QueryWorkloads</code><br />
<code dir="ltr" translate="no">GetIamPolicy</code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">ADMIN_WRITE</code></td>
<td><code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.CreateAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.DeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.DisableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.EnableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.RevokeAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.UndeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1.AuthProviderService.UpdateAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.CreateAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.DeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.DisableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.EnableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.RevokeAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.UndeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1alpha.AuthProviderService.UpdateAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.CreateAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.DeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.DisableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.EnableAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.RevokeAuthorization</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.UndeleteAuthProvider</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentity.v1beta.AuthProviderService.UpdateAuthProvider</code><br />
<code dir="ltr" translate="no">SetIamPolicy</code></td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for Agent Identity API.

### `google.cloud.agentidentity.v1.AuthProviderService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentity.v1.AuthProviderService` .

#### `CreateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.CreateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.CreateAuthProvider"`  

#### `DeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.DeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.DeleteAuthProvider"`  

#### `DisableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.DisableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.DisableAuthProvider"`  

#### `EnableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.EnableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.EnableAuthProvider"`  

#### `GetAccessSummary`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.GetAccessSummary`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.GetAccessSummary"`  

#### `GetAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.GetAuthProvider`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.GetAuthProvider"`  

#### `GetAuthorization`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.GetAuthorization`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.GetAuthorization"`  

#### `ListAccessSummaries`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.ListAccessSummaries`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.ListAccessSummaries"`  

#### `ListAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.ListAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.ListAuthProviders"`  

#### `ListAuthorizations`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.ListAuthorizations`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.ListAuthorizations"`  

#### `QueryAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.QueryAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.QueryAuthProviders"`  

#### `QueryWorkloads`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.QueryWorkloads`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.queryWorkloads - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.QueryWorkloads"`  

#### `RevokeAuthorization`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.RevokeAuthorization`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.revokeAuthorizations - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.RevokeAuthorization"`  

#### `UndeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.UndeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.UndeleteAuthProvider"`  

#### `UpdateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1.AuthProviderService.UpdateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1.AuthProviderService.UpdateAuthProvider"`  

### `google.cloud.agentidentity.v1alpha.AuthProviderService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentity.v1alpha.AuthProviderService` .

#### `CreateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.CreateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.CreateAuthProvider"`  

#### `DeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.DeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.DeleteAuthProvider"`  

#### `DisableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.DisableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.DisableAuthProvider"`  

#### `EnableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.EnableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.EnableAuthProvider"`  

#### `GetAccessSummary`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.GetAccessSummary`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.GetAccessSummary"`  

#### `GetAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthProvider`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthProvider"`  

#### `GetAuthorization`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthorization`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.GetAuthorization"`  

#### `ListAccessSummaries`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.ListAccessSummaries`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.ListAccessSummaries"`  

#### `ListAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthProviders"`  

#### `ListAuthorizations`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthorizations`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.ListAuthorizations"`  

#### `QueryAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.QueryAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.QueryAuthProviders"`  

#### `QueryWorkloads`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.QueryWorkloads`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.queryWorkloads - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.QueryWorkloads"`  

#### `RevokeAuthorization`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.RevokeAuthorization`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.revokeAuthorizations - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.RevokeAuthorization"`  

#### `UndeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.UndeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.UndeleteAuthProvider"`  

#### `UpdateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1alpha.AuthProviderService.UpdateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1alpha.AuthProviderService.UpdateAuthProvider"`  

### `google.cloud.agentidentity.v1beta.AuthProviderService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentity.v1beta.AuthProviderService` .

#### `CreateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.CreateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.CreateAuthProvider"`  

#### `DeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.DeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.DeleteAuthProvider"`  

#### `DisableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.DisableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.DisableAuthProvider"`  

#### `EnableAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.EnableAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.EnableAuthProvider"`  

#### `GetAccessSummary`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.GetAccessSummary`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.GetAccessSummary"`  

#### `GetAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthProvider`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthProvider"`  

#### `GetAuthorization`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthorization`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.GetAuthorization"`  

#### `ListAccessSummaries`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.ListAccessSummaries`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.accessSummaries.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.ListAccessSummaries"`  

#### `ListAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthProviders"`  

#### `ListAuthorizations`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthorizations`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authorizations.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.ListAuthorizations"`  

#### `QueryAuthProviders`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.QueryAuthProviders`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.QueryAuthProviders"`  

#### `QueryWorkloads`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.QueryWorkloads`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.queryWorkloads - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.QueryWorkloads"`  

#### `RevokeAuthorization`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.RevokeAuthorization`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.revokeAuthorizations - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.RevokeAuthorization"`  

#### `UndeleteAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.UndeleteAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.UndeleteAuthProvider"`  

#### `UpdateAuthProvider`

  - **Method** : `google.cloud.agentidentity.v1beta.AuthProviderService.UpdateAuthProvider`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentity.v1beta.AuthProviderService.UpdateAuthProvider"`  

### `google.iam.v1.IAMPolicy`

The following audit logs are associated with methods belonging to `google.iam.v1.IAMPolicy` .

#### `GetIamPolicy`

  - **Method** : `GetIamPolicy`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.getIamPolicy - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="GetIamPolicy"`  

#### `SetIamPolicy`

  - **Method** : `SetIamPolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `agentidentity.authProviders.setIamPolicy - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="SetIamPolicy"`  

## Methods that don't produce audit logs

A method might not produce audit logs for one or more of the following reasons:

  - It is a high volume method involving significant log generation and storage costs.
  - It has low auditing value.
  - Another audit or platform log already provides method coverage.

The following methods don't produce audit logs:

  - `google.cloud.agentidentity.v1.AuthProviderService.DeleteAuthorization`
  - `google.cloud.agentidentity.v1alpha.AuthProviderService.DeleteAuthorization`
  - `google.cloud.agentidentity.v1beta.AuthProviderService.DeleteAuthorization`
  - `google.cloud.location.Locations.GetLocation`
  - `google.cloud.location.Locations.ListLocations`

This document lists the audited methods for Agent Identity Credentials API. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Service name

To view the Agent Identity Credentials API audit logs, do the following:

1.  In the Google Cloud console, go to the Logs Explorer page:

2.  Copy and paste the following query into the **Query** field of the Logs Explorer, and then click **Run query** .
    
    ``` 
        protoPayload.serviceName="agentidentitycredentials.googleapis.com"
      
    ```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, Agent Identity Credentials API generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

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
<td><code dir="ltr" translate="no">DATA_READ</code></td>
<td><code dir="ltr" translate="no">google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService.RetrieveCredentials</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService.RetrieveCredentials</code><br />
<code dir="ltr" translate="no">google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService.RetrieveCredentials</code></td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for Agent Identity Credentials API.

### `google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService` .

#### `RetrieveCredentials`

  - **Method** : `google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService.RetrieveCredentials`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.retrieveCredentials - DATA_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService.RetrieveCredentials"`  

### `google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService` .

#### `RetrieveCredentials`

  - **Method** : `google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService.RetrieveCredentials`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.retrieveCredentials - DATA_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService.RetrieveCredentials"`  

### `google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService`

The following audit logs are associated with methods belonging to `google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService` .

#### `RetrieveCredentials`

  - **Method** : `google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService.RetrieveCredentials`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `agentidentity.authProviders.retrieveCredentials - DATA_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService.RetrieveCredentials"`  

## Methods that don't produce audit logs

A method might not produce audit logs for one or more of the following reasons:

  - It is a high volume method involving significant log generation and storage costs.
  - It has low auditing value.
  - Another audit or platform log already provides method coverage.

The following methods don't produce audit logs:

  - `google.cloud.agentidentitycredentials.v1.AuthProviderCredentialsService.FinalizeCredentials`
  - `google.cloud.agentidentitycredentials.v1alpha.AuthProviderCredentialsService.FinalizeCredentials`
  - `google.cloud.agentidentitycredentials.v1beta.AuthProviderCredentialsService.FinalizeCredentials`
