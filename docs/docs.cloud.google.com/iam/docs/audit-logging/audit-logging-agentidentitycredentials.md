---
name: documents/docs.cloud.google.com/iam/docs/audit-logging/audit-logging-agentidentitycredentials
uri: https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-agentidentitycredentials
title: Agent Identity Credentials API audit logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

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
