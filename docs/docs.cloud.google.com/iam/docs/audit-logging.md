---
name: documents/docs.cloud.google.com/iam/docs/audit-logging
uri: https://docs.cloud.google.com/iam/docs/audit-logging
title: Identity and Access Management audit logging
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document describes audit logging for Identity and Access Management. Google Cloud services generate audit logs that record administrative and access activities within your Google Cloud resources. For more information about Cloud Audit Logs, see the following:

  - [Types of audit logs](https://docs.cloud.google.com/logging/docs/audit#types)
  - [Audit log entry structure](https://docs.cloud.google.com/logging/docs/audit#audit_log_entry_structure)
  - [Storing and routing audit logs](https://docs.cloud.google.com/logging/docs/audit#storing_and_routing_audit_logs)
  - [Cloud Logging pricing summary](https://docs.cloud.google.com/stackdriver/pricing#logs-pricing-summary)
  - [Enable Data Access audit logs](https://docs.cloud.google.com/logging/docs/audit/configure-data-access)

## Notes

You can also view examples of [audit log entries for service accounts](https://docs.cloud.google.com/iam/docs/audit-logging/examples-service-accounts) .

## Service name

Identity and Access Management audit logs use the service name `iam.googleapis.com` . Filter for this service:

``` 
    protoPayload.serviceName="iam.googleapis.com"
  
```

## Methods by permission type

Each IAM permission has a `type` property, whose value is an enum that can be one of four values: `ADMIN_READ` , `ADMIN_WRITE` , `DATA_READ` , or `DATA_WRITE` . When you call a method, Identity and Access Management generates an audit log whose category is dependent on the `type` property of the permission required to perform the method. Methods that require an IAM permission with the `type` property value of `DATA_READ` , `DATA_WRITE` , or `ADMIN_READ` generate [Data Access](https://docs.cloud.google.com/logging/docs/audit#data-access) audit logs. Methods that require an IAM permission with the `type` property value of `ADMIN_WRITE` generate [Admin Activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity) audit logs.

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
<td><code dir="ltr" translate="no">google.iam.admin.v1.GetIAMPolicy</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.GetRole</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.GetServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.GetServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.ListRoles</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.ListServiceAccountKeys</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.ListServiceAccounts</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.TestIAMPermissions</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.GetOauthClient</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.GetOauthClientCredential</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.ListOauthClientCredentials</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.ListOauthClients</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.GetIamPolicy</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.GetWorkforcePool</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProvider</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProviderKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviderKeys</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviders</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.ListWorkforcePools</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetIamPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPool</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolManagedIdentity</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolNamespace</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProviderKey</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListAttestationRules</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolManagedIdentities</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolNamespaces</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviderKeys</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPools</code><br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPool</code><br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider</code><br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders</code><br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPools</code><br />
<code dir="ltr" translate="no">google.iam.v2.Policies.GetPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v2.Policies.ListPolicies</code><br />
<code dir="ltr" translate="no">google.iam.v2alpha.Policies.GetPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v2alpha.Policies.ListPolicies</code><br />
<code dir="ltr" translate="no">google.iam.v2beta.Policies.GetPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v2beta.Policies.ListPolicies</code><br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.GetPolicyBinding</code><br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.ListPolicyBindings</code><br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies</code><br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.GetPolicyBinding</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.ListPolicyBindings</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.SearchTargetPolicyBindings</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies</code><br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings</code><br />
<code dir="ltr" translate="no">google.longrunning.Operations.GetOperation</code></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">ADMIN_WRITE</code></td>
<td><code dir="ltr" translate="no">google.iam.admin.v1.CreateRole</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.CreateServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.CreateServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.DeleteRole</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.DeleteServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.DeleteServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.DisableServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.DisableServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.EnableServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.EnableServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.PatchServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.SetIAMPolicy</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.UndeleteRole</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.UndeleteServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.UpdateRole</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.UpdateServiceAccount</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.UploadServiceAccountKey</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.CreateOauthClient</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.CreateOauthClientCredential</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.DeleteOauthClient</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.DeleteOauthClientCredential</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.UndeleteOauthClient</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.UpdateOauthClient</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.OauthClients.UpdateOauthClientCredential</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.CreateWorkforcePool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.DeleteWorkforcePool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolSubject</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.SetIamPolicy</code><br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolSubject</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UpdateWorkforcePool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.admin.v1.WorkforcePools.UpdateWorkforcePoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.AddAttestationRule</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolManagedIdentity</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolNamespace</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolManagedIdentity</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolNamespace</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.RemoveAttestationRule</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.SetAttestationRules</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.SetIamPolicy</code><br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolManagedIdentity</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolNamespace</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProviderKey</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolManagedIdentity</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolNamespace</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPool</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2.Policies.CreatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2.Policies.DeletePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2.Policies.UpdatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2alpha.Policies.CreatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2alpha.Policies.DeletePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2alpha.Policies.UpdatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2beta.Policies.CreatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2beta.Policies.DeletePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v2beta.Policies.UpdatePolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.CreatePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.DeletePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.UpdatePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.CreatePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.DeletePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PolicyBindings.UpdatePolicyBinding</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy</code> (LRO)<br />
<code dir="ltr" translate="no">google.iam.v3beta.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy</code> (LRO)</td>
</tr>
<tr class="odd">
<td><code dir="ltr" translate="no">OTHER</code></td>
<td><code dir="ltr" translate="no">google.iam.admin.v1.QueryGrantableRoles</code> : To enable this log, enable <code dir="ltr" translate="no">ADMIN_READ</code> under the service <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com</code> .<br />
<code dir="ltr" translate="no">google.iam.v3.PolicyBindings.SearchTargetPolicyBindings</code> : To enable this log, enable <code dir="ltr" translate="no">ADMIN_READ</code> under the service <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com</code> .</td>
</tr>
</tbody>
</table>

## API interface audit logs

For information about how and which permissions are evaluated for each method, see the Identity and Access Management documentation for Identity and Access Management.

### `google.iam.admin.v1.IAM`

The following audit logs are associated with methods belonging to `google.iam.admin.v1.IAM` .

#### `CreateRole`

  - **Method** : `  google.iam.admin.v1.CreateRole  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.roles.create - ADMIN_WRITE`
      - `iam.roles.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.CreateRole"`  

#### `CreateServiceAccount`

  - **Method** : `  google.iam.admin.v1.CreateServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.CreateServiceAccount"`  

#### `CreateServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.CreateServiceAccountKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccountKeys.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.CreateServiceAccountKey"`  

#### `DeleteRole`

  - **Method** : `  google.iam.admin.v1.DeleteRole  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.roles.delete - ADMIN_WRITE`
      - `iam.roles.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.DeleteRole"`  

#### `DeleteServiceAccount`

  - **Method** : `  google.iam.admin.v1.DeleteServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.DeleteServiceAccount"`  

#### `DeleteServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.DeleteServiceAccountKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccountKeys.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.DeleteServiceAccountKey"`  

#### `DisableServiceAccount`

  - **Method** : `  google.iam.admin.v1.DisableServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.disable - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.DisableServiceAccount"`  

#### `DisableServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.DisableServiceAccountKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccountKeys.disable - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.DisableServiceAccountKey"`  

#### `EnableServiceAccount`

  - **Method** : `  google.iam.admin.v1.EnableServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.enable - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.EnableServiceAccount"`  

#### `EnableServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.EnableServiceAccountKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccountKeys.enable - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.EnableServiceAccountKey"`  

#### `GetIAMPolicy`

  - **Method** : `  google.iam.admin.v1.GetIAMPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.getIamPolicy - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.GetIAMPolicy"`  

#### `GetRole`

  - **Method** : `  google.iam.admin.v1.GetRole  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.roles.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.GetRole"`  

#### `GetServiceAccount`

  - **Method** : `  google.iam.admin.v1.GetServiceAccount  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.GetServiceAccount"`  

#### `GetServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.GetServiceAccountKey  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccountKeys.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.GetServiceAccountKey"`  

#### `ListRoles`

  - **Method** : `  google.iam.admin.v1.ListRoles  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.roles.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.ListRoles"`  

#### `ListServiceAccountKeys`

  - **Method** : `  google.iam.admin.v1.ListServiceAccountKeys  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccountKeys.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.ListServiceAccountKeys"`  

#### `ListServiceAccounts`

  - **Method** : `  google.iam.admin.v1.ListServiceAccounts  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.ListServiceAccounts"`  

#### `PatchServiceAccount`

  - **Method** : `  google.iam.admin.v1.PatchServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.PatchServiceAccount"`  

#### `QueryGrantableRoles`

  - **Method** : `  google.iam.admin.v1.QueryGrantableRoles  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `resourcemanager.projects.getIamPolicy - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.QueryGrantableRoles"`  

> **Note:** This method can cause a **getIamPolicy** method to be called in other services' APIs. For example, if this method needs to check the allow policy for a Compute Engine instance, then the **[instances.getIamPolicy method](https://docs.cloud.google.com/compute/docs/reference/rest/v1/instances/getIamPolicy)** in the Compute Engine API is called. To receive audit logs for these additional services, you must enable `ADMIN_READ` audit logs for the other services' APIs.

#### `SetIAMPolicy`

  - **Method** : `  google.iam.admin.v1.SetIAMPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.setIamPolicy - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.SetIAMPolicy"`  

#### `TestIAMPermissions`

  - **Method** : `  google.iam.admin.v1.TestIAMPermissions  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.serviceAccounts.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.TestIAMPermissions"`  

#### `UndeleteRole`

  - **Method** : `  google.iam.admin.v1.UndeleteRole  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.roles.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.UndeleteRole"`  

#### `UndeleteServiceAccount`

  - **Method** : `  google.iam.admin.v1.UndeleteServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.UndeleteServiceAccount"`  

#### `UpdateRole`

  - **Method** : `  google.iam.admin.v1.UpdateRole  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.roles.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.UpdateRole"`  

#### `UpdateServiceAccount`

  - **Method** : `  google.iam.admin.v1.UpdateServiceAccount  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccounts.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.UpdateServiceAccount"`  

#### `UploadServiceAccountKey`

  - **Method** : `  google.iam.admin.v1.UploadServiceAccountKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.serviceAccountKeys.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.UploadServiceAccountKey"`  

### `google.iam.admin.v1.OauthClients`

The following audit logs are associated with methods belonging to `google.iam.admin.v1.OauthClients` .

#### `CreateOauthClient`

  - **Method** : `  google.iam.admin.v1.OauthClients.CreateOauthClient  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClients.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.CreateOauthClient"`  

#### `CreateOauthClientCredential`

  - **Method** : `  google.iam.admin.v1.OauthClients.CreateOauthClientCredential  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClientCredentials.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.CreateOauthClientCredential"`  

#### `DeleteOauthClient`

  - **Method** : `  google.iam.admin.v1.OauthClients.DeleteOauthClient  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClients.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.DeleteOauthClient"`  

#### `DeleteOauthClientCredential`

  - **Method** : `  google.iam.admin.v1.OauthClients.DeleteOauthClientCredential  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClientCredentials.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.DeleteOauthClientCredential"`  

#### `GetOauthClient`

  - **Method** : `  google.iam.admin.v1.OauthClients.GetOauthClient  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.oauthClients.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.GetOauthClient"`  

#### `GetOauthClientCredential`

  - **Method** : `  google.iam.admin.v1.OauthClients.GetOauthClientCredential  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.oauthClientCredentials.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.GetOauthClientCredential"`  

#### `ListOauthClientCredentials`

  - **Method** : `  google.iam.admin.v1.OauthClients.ListOauthClientCredentials  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.oauthClientCredentials.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.ListOauthClientCredentials"`  

#### `ListOauthClients`

  - **Method** : `  google.iam.admin.v1.OauthClients.ListOauthClients  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.oauthClients.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.ListOauthClients"`  

#### `UndeleteOauthClient`

  - **Method** : `  google.iam.admin.v1.OauthClients.UndeleteOauthClient  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClients.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.UndeleteOauthClient"`  

#### `UpdateOauthClient`

  - **Method** : `  google.iam.admin.v1.OauthClients.UpdateOauthClient  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClients.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.UpdateOauthClient"`  

#### `UpdateOauthClientCredential`

  - **Method** : `  google.iam.admin.v1.OauthClients.UpdateOauthClientCredential  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.oauthClientCredentials.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.OauthClients.UpdateOauthClientCredential"`  

### `google.iam.admin.v1.WorkforcePools`

The following audit logs are associated with methods belonging to `google.iam.admin.v1.WorkforcePools` .

#### `CreateWorkforcePool`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.CreateWorkforcePool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePools.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.CreateWorkforcePool"`  

#### `CreateWorkforcePoolProvider`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProvider"`  

#### `CreateWorkforcePoolProviderKey`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderKeys.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.CreateWorkforcePoolProviderKey"`  

#### `DeleteWorkforcePool`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.DeleteWorkforcePool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePools.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.DeleteWorkforcePool"`  

#### `DeleteWorkforcePoolProvider`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProvider"`  

#### `DeleteWorkforcePoolProviderKey`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderKeys.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolProviderKey"`  

#### `DeleteWorkforcePoolSubject`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolSubject  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolSubjects.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.DeleteWorkforcePoolSubject"`  

#### `GetIamPolicy`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.GetIamPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePools.getIamPolicy - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.GetIamPolicy"`  

#### `GetWorkforcePool`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.GetWorkforcePool  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePools.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.GetWorkforcePool"`  

#### `GetWorkforcePoolProvider`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProvider  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePoolProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProvider"`  

#### `GetWorkforcePoolProviderKey`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProviderKey  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePoolProviderKeys.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.GetWorkforcePoolProviderKey"`  

#### `ListWorkforcePoolProviderKeys`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviderKeys  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePoolProviderKeys.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviderKeys"`  

#### `ListWorkforcePoolProviders`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviders  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePoolProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.ListWorkforcePoolProviders"`  

#### `ListWorkforcePools`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.ListWorkforcePools  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workforcePools.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.ListWorkforcePools"`  

#### `SetIamPolicy`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.SetIamPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePools.setIamPolicy - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.SetIamPolicy"`  

#### `UndeleteWorkforcePool`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePools.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePool"`  

#### `UndeleteWorkforcePoolProvider`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProvider"`  

#### `UndeleteWorkforcePoolProviderKey`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviderKeys.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolProviderKey"`  

#### `UndeleteWorkforcePoolSubject`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolSubject  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolSubjects.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UndeleteWorkforcePoolSubject"`  

#### `UpdateWorkforcePool`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UpdateWorkforcePool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePools.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UpdateWorkforcePool"`  

#### `UpdateWorkforcePoolProvider`

  - **Method** : `  google.iam.admin.v1.WorkforcePools.UpdateWorkforcePoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workforcePoolProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.admin.v1.WorkforcePools.UpdateWorkforcePoolProvider"`  

### `google.iam.v1.WorkloadIdentityPools`

The following audit logs are associated with methods belonging to `google.iam.v1.WorkloadIdentityPools` .

#### `AddAttestationRule`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.AddAttestationRule  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.setAttestationRules - ADMIN_WRITE`
      - `iam.workloadIdentityPools.setAttestationRules - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.AddAttestationRule"`  

#### `CreateWorkloadIdentityPool`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPool"`  

#### `CreateWorkloadIdentityPoolManagedIdentity`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolManagedIdentity  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolManagedIdentity"`  

#### `CreateWorkloadIdentityPoolNamespace`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolNamespace  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolNamespace"`  

#### `CreateWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider"`  

#### `CreateWorkloadIdentityPoolProviderKey`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviderKeys.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.CreateWorkloadIdentityPoolProviderKey"`  

#### `DeleteWorkloadIdentityPool`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPool"`  

#### `DeleteWorkloadIdentityPoolManagedIdentity`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolManagedIdentity  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolManagedIdentity"`  

#### `DeleteWorkloadIdentityPoolNamespace`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolNamespace  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolNamespace"`  

#### `DeleteWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider"`  

#### `DeleteWorkloadIdentityPoolProviderKey`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviderKeys.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProviderKey"`  

#### `GetIamPolicy`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetIamPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/workloadIdentityPools.getIamPolicy - ADMIN_READ`
      - `iam.workloadIdentityPools.getIamPolicy - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetIamPolicy"`  

#### `GetWorkloadIdentityPool`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPool  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPools.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPool"`  

#### `GetWorkloadIdentityPoolManagedIdentity`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolManagedIdentity  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolManagedIdentity"`  

#### `GetWorkloadIdentityPoolNamespace`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolNamespace  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolNamespace"`  

#### `GetWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider"`  

#### `GetWorkloadIdentityPoolProviderKey`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProviderKey  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviderKeys.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.GetWorkloadIdentityPoolProviderKey"`  

#### `ListAttestationRules`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListAttestationRules  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.getAttestationRules - ADMIN_READ`
      - `iam.workloadIdentityPools.getAttestationRules - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListAttestationRules"`  

#### `ListWorkloadIdentityPoolManagedIdentities`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolManagedIdentities  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolManagedIdentities"`  

#### `ListWorkloadIdentityPoolNamespaces`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolNamespaces  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolNamespaces"`  

#### `ListWorkloadIdentityPoolProviderKeys`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviderKeys  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviderKeys.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviderKeys"`  

#### `ListWorkloadIdentityPoolProviders`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders"`  

#### `ListWorkloadIdentityPools`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPools  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPools.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.ListWorkloadIdentityPools"`  

#### `RemoveAttestationRule`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.RemoveAttestationRule  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.setAttestationRules - ADMIN_WRITE`
      - `iam.workloadIdentityPools.setAttestationRules - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.RemoveAttestationRule"`  

#### `SetAttestationRules`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.SetAttestationRules  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.setAttestationRules - ADMIN_WRITE`
      - `iam.workloadIdentityPools.setAttestationRules - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.SetAttestationRules"`  

#### `SetIamPolicy`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.SetIamPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/workloadIdentityPools.setIamPolicy - ADMIN_WRITE`
      - `iam.workloadIdentityPools.setIamPolicy - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.SetIamPolicy"`  

#### `UndeleteWorkloadIdentityPool`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPool"`  

#### `UndeleteWorkloadIdentityPoolManagedIdentity`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolManagedIdentity  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolManagedIdentity"`  

#### `UndeleteWorkloadIdentityPoolNamespace`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolNamespace  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolNamespace"`  

#### `UndeleteWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider"`  

#### `UndeleteWorkloadIdentityPoolProviderKey`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProviderKey  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviderKeys.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProviderKey"`  

#### `UpdateWorkloadIdentityPool`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPool"`  

#### `UpdateWorkloadIdentityPoolManagedIdentity`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolManagedIdentity  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolManagedIdentities.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolManagedIdentity"`  

#### `UpdateWorkloadIdentityPoolNamespace`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolNamespace  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolNamespaces.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolNamespace"`  

#### `UpdateWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider"`  

### `google.iam.v1beta.WorkloadIdentityPools`

The following audit logs are associated with methods belonging to `google.iam.v1beta.WorkloadIdentityPools` .

#### `CreateWorkloadIdentityPool`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPool"`  

#### `CreateWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.CreateWorkloadIdentityPoolProvider"`  

#### `DeleteWorkloadIdentityPool`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPool"`  

#### `DeleteWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.DeleteWorkloadIdentityPoolProvider"`  

#### `GetWorkloadIdentityPool`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPool  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPools.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPool"`  

#### `GetWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.GetWorkloadIdentityPoolProvider"`  

#### `ListWorkloadIdentityPoolProviders`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPoolProviders"`  

#### `ListWorkloadIdentityPools`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPools  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.workloadIdentityPools.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.ListWorkloadIdentityPools"`  

#### `UndeleteWorkloadIdentityPool`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPool"`  

#### `UndeleteWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.undelete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.UndeleteWorkloadIdentityPoolProvider"`  

#### `UpdateWorkloadIdentityPool`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPool  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPools.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPool"`  

#### `UpdateWorkloadIdentityPoolProvider`

  - **Method** : `  google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.workloadIdentityPoolProviders.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v1beta.WorkloadIdentityPools.UpdateWorkloadIdentityPoolProvider"`  

### `google.iam.v2.Policies`

The following audit logs are associated with methods belonging to `google.iam.v2.Policies` .

#### `CreatePolicy`

  - **Method** : `  google.iam.v2.Policies.CreatePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2.Policies.CreatePolicy"`  

#### `DeletePolicy`

  - **Method** : `  google.iam.v2.Policies.DeletePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2.Policies.DeletePolicy"`  

#### `GetPolicy`

  - **Method** : `  google.iam.v2.Policies.GetPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2.Policies.GetPolicy"`  

#### `ListPolicies`

  - **Method** : `  google.iam.v2.Policies.ListPolicies  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2.Policies.ListPolicies"`  

#### `UpdatePolicy`

  - **Method** : `  google.iam.v2.Policies.UpdatePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2.Policies.UpdatePolicy"`  

### `google.iam.v2alpha.Policies`

The following audit logs are associated with methods belonging to `google.iam.v2alpha.Policies` .

#### `CreatePolicy`

  - **Method** : `google.iam.v2alpha.Policies.CreatePolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2alpha.Policies.CreatePolicy"`  

#### `DeletePolicy`

  - **Method** : `google.iam.v2alpha.Policies.DeletePolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2alpha.Policies.DeletePolicy"`  

#### `GetPolicy`

  - **Method** : `google.iam.v2alpha.Policies.GetPolicy`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2alpha.Policies.GetPolicy"`  

#### `ListPolicies`

  - **Method** : `google.iam.v2alpha.Policies.ListPolicies`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2alpha.Policies.ListPolicies"`  

#### `UpdatePolicy`

  - **Method** : `google.iam.v2alpha.Policies.UpdatePolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2alpha.Policies.UpdatePolicy"`  

### `google.iam.v2beta.Policies`

The following audit logs are associated with methods belonging to `google.iam.v2beta.Policies` .

#### `CreatePolicy`

  - **Method** : `  google.iam.v2beta.Policies.CreatePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2beta.Policies.CreatePolicy"`  

#### `DeletePolicy`

  - **Method** : `  google.iam.v2beta.Policies.DeletePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2beta.Policies.DeletePolicy"`  

#### `GetPolicy`

  - **Method** : `  google.iam.v2beta.Policies.GetPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/accessboundarypolicies.get - ADMIN_READ`
      - `iam.googleapis.com/denypolicies.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2beta.Policies.GetPolicy"`  

#### `ListPolicies`

  - **Method** : `  google.iam.v2beta.Policies.ListPolicies  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2beta.Policies.ListPolicies"`  

#### `UpdatePolicy`

  - **Method** : `  google.iam.v2beta.Policies.UpdatePolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.googleapis.com/denypolicies.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v2beta.Policies.UpdatePolicy"`  

### `google.iam.v3.PolicyBindings`

The following audit logs are associated with methods belonging to `google.iam.v3.PolicyBindings` .

#### `CreatePolicyBinding`

  - **Method** : `google.iam.v3.PolicyBindings.CreatePolicyBinding`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.createPolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.bind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.CreatePolicyBinding"`  

#### `DeletePolicyBinding`

  - **Method** : `google.iam.v3.PolicyBindings.DeletePolicyBinding`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.deletePolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.unbind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.DeletePolicyBinding"`  

#### `GetPolicyBinding`

  - **Method** : `google.iam.v3.PolicyBindings.GetPolicyBinding`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.policybindings.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.GetPolicyBinding"`  

#### `ListPolicyBindings`

  - **Method** : `google.iam.v3.PolicyBindings.ListPolicyBindings`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.policybindings.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.ListPolicyBindings"`  

#### `SearchTargetPolicyBindings`

  - **Method** : `google.iam.v3.PolicyBindings.SearchTargetPolicyBindings`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.searchPolicyBindings - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.SearchTargetPolicyBindings"`  

#### `UpdatePolicyBinding`

  - **Method** : `google.iam.v3.PolicyBindings.UpdatePolicyBinding`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.updatePolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.bind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PolicyBindings.UpdatePolicyBinding"`  

### `google.iam.v3.PrincipalAccessBoundaryPolicies`

The following audit logs are associated with methods belonging to `google.iam.v3.PrincipalAccessBoundaryPolicies` .

#### `CreatePrincipalAccessBoundaryPolicy`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy"`  

#### `DeletePrincipalAccessBoundaryPolicy`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy"`  

#### `GetPrincipalAccessBoundaryPolicy`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy"`  

#### `ListPrincipalAccessBoundaryPolicies`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies"`  

#### `SearchPrincipalAccessBoundaryPolicyBindings`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings`  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.searchPolicyBindings - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings"`  

#### `UpdatePrincipalAccessBoundaryPolicy`

  - **Method** : `google.iam.v3.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy`  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy"`  

### `google.iam.v3beta.PolicyBindings`

The following audit logs are associated with methods belonging to `google.iam.v3beta.PolicyBindings` .

#### `CreatePolicyBinding`

  - **Method** : `  google.iam.v3beta.PolicyBindings.CreatePolicyBinding  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.createPolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.bind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.CreatePolicyBinding"`  

#### `DeletePolicyBinding`

  - **Method** : `  google.iam.v3beta.PolicyBindings.DeletePolicyBinding  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.deletePolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.unbind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.DeletePolicyBinding"`  

#### `GetPolicyBinding`

  - **Method** : `  google.iam.v3beta.PolicyBindings.GetPolicyBinding  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.policybindings.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.GetPolicyBinding"`  

#### `ListPolicyBindings`

  - **Method** : `  google.iam.v3beta.PolicyBindings.ListPolicyBindings  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.policybindings.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.ListPolicyBindings"`  

#### `SearchTargetPolicyBindings`

  - **Method** : `  google.iam.v3beta.PolicyBindings.SearchTargetPolicyBindings  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/folders.searchPolicyBindings - ADMIN_READ`
      - `cloudresourcemanager.googleapis.com/organizations.searchPolicyBindings - ADMIN_READ`
      - `cloudresourcemanager.googleapis.com/projects.searchPolicyBindings - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.SearchTargetPolicyBindings"`  

#### `UpdatePolicyBinding`

  - **Method** : `  google.iam.v3beta.PolicyBindings.UpdatePolicyBinding  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `cloudresourcemanager.googleapis.com/projects.updatePolicyBinding - ADMIN_WRITE`
      - `iam.googleapis.com/principalaccessboundarypolicies.bind - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PolicyBindings.UpdatePolicyBinding"`  

### `google.iam.v3beta.PrincipalAccessBoundaryPolicies`

The following audit logs are associated with methods belonging to `google.iam.v3beta.PrincipalAccessBoundaryPolicies` .

#### `CreatePrincipalAccessBoundaryPolicy`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.create - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.CreatePrincipalAccessBoundaryPolicy"`  

#### `DeletePrincipalAccessBoundaryPolicy`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.delete - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.DeletePrincipalAccessBoundaryPolicy"`  

#### `GetPrincipalAccessBoundaryPolicy`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.GetPrincipalAccessBoundaryPolicy"`  

#### `ListPrincipalAccessBoundaryPolicies`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.list - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.ListPrincipalAccessBoundaryPolicies"`  

#### `SearchPrincipalAccessBoundaryPolicyBindings`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.searchPolicyBindings - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.SearchPrincipalAccessBoundaryPolicyBindings"`  

#### `UpdatePrincipalAccessBoundaryPolicy`

  - **Method** : `  google.iam.v3beta.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy  `  
  - **Audit log type** : [Admin activity](https://docs.cloud.google.com/logging/docs/audit#admin-activity)  
  - **Permissions** :
      - `iam.principalaccessboundarypolicies.update - ADMIN_WRITE`
  - **Method is a long-running or streaming operation** : [**Long-running operation**](https://docs.cloud.google.com/logging/docs/audit/understanding-audit-logs#lro)  
  - **Filter for this method** : `protoPayload.methodName="google.iam.v3beta.PrincipalAccessBoundaryPolicies.UpdatePrincipalAccessBoundaryPolicy"`  

### `google.longrunning.Operations`

The following audit logs are associated with methods belonging to `google.longrunning.Operations` .

#### `GetOperation`

  - **Method** : `  google.longrunning.Operations.GetOperation  `  
  - **Audit log type** : [Data access](https://docs.cloud.google.com/logging/docs/audit#data-access)  
  - **Permissions** :
      - `iam.operations.get - ADMIN_READ`
  - **Method is a long-running or streaming operation** : No.  
  - **Filter for this method** : `protoPayload.methodName="google.longrunning.Operations.GetOperation"`  

## Methods that don't produce audit logs

A method might not produce audit logs for one or more of the following reasons:

  - It is a high volume method involving significant log generation and storage costs.
  - It has low auditing value.
  - Another audit or platform log already provides method coverage.

The following methods don't produce audit logs:

  - `google.iam.admin.v1.IAM.LintPolicy`
  - `google.iam.admin.v1.IAM.QueryAuditableServices`
  - `google.iam.admin.v1.IAM.QueryTestablePermissions`
  - `google.iam.admin.v1.IAM.SignBlob`
  - `google.iam.admin.v1.IAM.SignJwt`
  - `google.iam.admin.v1.WorkforcePools.TestIamPermissions`

## Sample queries

To use the sample queries in the following table, complete these steps:

1.  Replace the variables in the query expression with your own project information, then copy the expression using the clipboard icon *content\_copy* .

2.  In the Google Cloud console, go to the segment **Logs Explorer** page:
    
    If you use the search bar to find this page, then select the result whose subheading is **Logging** .

3.  Enable **Show query** to open the query-editor field, then paste the expression into the query-editor field:
    
    ![The query editor where you enter sample queries.](https://docs.cloud.google.com/static/logging/docs/images/query-pane-2.png)

4.  Click **Run query** . Logs that match your query are listed in the **Query results** pane.

To find audit logs for Identity and Access Management, use the following queries in the Logs Explorer:

Before using the sample queries, replace the following values:

  - `  SERVICE_ACCOUNT_SHORT_ID  ` : Everything preceding the `@` symbol in the service account's email address. For example, the service account ID of the service account `service-account@example.iam.gserviceaccount.com` is `service-account` .
  - `  SERVICE_ACCOUNT_EMAIL  ` : The full email address of the service account. For example, `service-account@example.iam.gserviceaccount.com` .
  - `  ROLE_NAME  ` : The full role name, including any `organizations/` , `projects/` , or `roles/` prefixes. For example, `organizations/123456789012/roles/myCompanyAdmin` .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Query name</th>
<th>Expression</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Service account created</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type = &quot;service_account&quot;
protoPayload.serviceName = &quot;iam.googleapis.com&quot;
protoPayload.methodName:&quot;CreateServiceAccount&quot;
log_id(&quot;cloudaudit.googleapis.com/activity&quot;)
(protoPayload.request.account_id:&quot;SERVICE_ACCOUNT_SHORT_ID&quot;
  OR protoPayload.response.email:&quot;SERVICE_ACCOUNT_EMAIL&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Service account deleted</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type = &quot;service_account&quot;
protoPayload.serviceName = &quot;iam.googleapis.com&quot;
protoPayload.methodName:&quot;DeleteServiceAccount&quot;
log_id(&quot;cloudaudit.googleapis.com/activity&quot;)
resource.labels.email_id:&quot;SERVICE_ACCOUNT_EMAIL&quot;</code></pre></td>
</tr>
<tr class="odd">
<td>Service account key created</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type = &quot;service_account&quot;
protoPayload.serviceName = &quot;iam.googleapis.com&quot;
protoPayload.methodName:&quot;CreateServiceAccountKey&quot;
log_id(&quot;cloudaudit.googleapis.com/activity&quot;)
resource.labels.email_id:&quot;SERVICE_ACCOUNT_EMAIL&quot;</code></pre></td>
</tr>
<tr class="even">
<td>Service account key deleted</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type = &quot;service_account&quot;
protoPayload.serviceName = &quot;iam.googleapis.com&quot;
protoPayload.methodName:&quot;DeleteServiceAccountKey&quot;
log_id(&quot;cloudaudit.googleapis.com/activity&quot;)
resource.labels.email_id:&quot;SERVICE_ACCOUNT_EMAIL&quot;</code></pre></td>
</tr>
<tr class="odd">
<td>Any resource created, modified, or deleted</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>log_id(&quot;cloudaudit.googleapis.com/activity&quot;) AND
protoPayload.methodName:(&quot;create&quot; OR &quot;delete&quot; OR &quot;update&quot;)</code></pre></td>
</tr>
<tr class="even">
<td>Custom role updated</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>log_id(&quot;cloudaudit.googleapis.com/activity&quot;)
resource.type = &quot;iam_role&quot;
protoPayload.serviceName = &quot;iam.googleapis.com&quot;
protoPayload.methodName:&quot;UpdateRole&quot;
resource.labels.role_name:&quot;ROLE_NAME&quot;</code></pre></td>
</tr>
<tr class="odd">
<td>Project-level allow policy updated</td>
<td><pre dir="ltr" data-is-upgraded="" translate="no"><code>resource.type = &quot;project&quot; AND
log_id(&quot;cloudaudit.googleapis.com/activity&quot;) AND
protoPayload.methodName:&quot;SetIamPolicy&quot;</code></pre></td>
</tr>
</tbody>
</table>
