---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/audit-logging-iamscim
uri: https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-iamscim
title: System for Cross-domain Identity Management (SCIM) audit logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes audit logging for IAM SCIM Service. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Service name

IAM SCIM Service audit logs use the service name `iamscim.googleapis.com` . Filter for this service:

``` 
    protoPayload.serviceName="iamscim.googleapis.com"
  
```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, IAM SCIM Service generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

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
<td><code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Users.ListUsers</code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">ADMIN_WRITE</code></td>
<td><code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Groups.CreateGroup</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Groups.DeleteGroup</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Groups.PatchGroup</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Users.CreateUser</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Users.DeleteUser</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Users.PatchUser</code><br />
<code dir="ltr" translate="no">google.cloud.iamscim.v1alpha1.Users.PutUser</code></td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for IAM SCIM Service.

### `google.cloud.iamscim.v1alpha1.Groups`

The following audit logs are associated with methods belonging to `google.cloud.iamscim.v1alpha1.Groups` .

#### `CreateGroup`

  - **Method** : `google.cloud.iamscim.v1alpha1.Groups.CreateGroup`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimGroups.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Groups.CreateGroup"`  

#### `DeleteGroup`

  - **Method** : `google.cloud.iamscim.v1alpha1.Groups.DeleteGroup`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimGroups.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Groups.DeleteGroup"`  

#### `PatchGroup`

  - **Method** : `google.cloud.iamscim.v1alpha1.Groups.PatchGroup`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimGroups.patch - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Groups.PatchGroup"`  

### `google.cloud.iamscim.v1alpha1.Users`

The following audit logs are associated with methods belonging to `google.cloud.iamscim.v1alpha1.Users` .

#### `CreateUser`

  - **Method** : `google.cloud.iamscim.v1alpha1.Users.CreateUser`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimUsers.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Users.CreateUser"`  

#### `DeleteUser`

  - **Method** : `google.cloud.iamscim.v1alpha1.Users.DeleteUser`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimUsers.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Users.DeleteUser"`  

#### `ListUsers`

  - **Method** : `google.cloud.iamscim.v1alpha1.Users.ListUsers`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimUsers.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Users.ListUsers"`  

#### `PatchUser`

  - **Method** : `google.cloud.iamscim.v1alpha1.Users.PatchUser`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimUsers.patch - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Users.PatchUser"`  

#### `PutUser`

  - **Method** : `google.cloud.iamscim.v1alpha1.Users.PutUser`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderScimUsers.put - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.cloud.iamscim.v1alpha1.Users.PutUser"`  

## Methods that don't produce audit logs

A method might not produce audit logs for one or more of the following reasons:

  - It is a high volume method involving significant log generation and storage costs.
  - It has low auditing value.
  - Another audit or platform log already provides method coverage.

The following methods don't produce audit logs:

  - `google.cloud.iamscim.v1alpha1.Schemas.GetSchema`
  - `google.cloud.iamscim.v1alpha1.Schemas.ListSchemas`
  - `google.cloud.iamscim.v1alpha1.ServiceProviderConfigService.GetServiceProviderConfig`
