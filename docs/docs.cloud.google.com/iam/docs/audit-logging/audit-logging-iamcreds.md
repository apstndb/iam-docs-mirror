---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/audit-logging-iamcreds
uri: https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-iamcreds
title: Service Account Credentials audit logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes audit logging for Service Account Credentials. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Service name

Service Account Credentials audit logs use the service name `iamcredentials.googleapis.com` . Filter for this service:

``` 
    protoPayload.serviceName="iamcredentials.googleapis.com"
  
```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, Service Account Credentials generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

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
<td><code dir="ltr" translate="no">GenerateAccessToken</code> (LRO)<br />
<code dir="ltr" translate="no">GenerateIdToken</code> (LRO)<br />
<code dir="ltr" translate="no">SignBlob</code> (LRO)<br />
<code dir="ltr" translate="no">SignJwt</code> (LRO)</td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for Service Account Credentials.

### `google.iam.credentials.v1.IAMCredentials`

The following audit logs are associated with methods belonging to `google.iam.credentials.v1.IAMCredentials` .

#### `GenerateAccessToken`

  - **Method** : `GenerateAccessToken`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.getAccessToken - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="GenerateAccessToken"`  

#### `GenerateIdToken`

  - **Method** : `GenerateIdToken`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.getOpenIdToken - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="GenerateIdToken"`  

#### `SignBlob`

  - **Method** : `SignBlob`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.signBlob - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="SignBlob"`  

#### `SignJwt`

  - **Method** : `SignJwt`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.implicitDelegation - ADMIN_READ`
      - `iam.serviceAccounts.signJwt - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="SignJwt"`
