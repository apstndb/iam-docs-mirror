---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/DenyRule
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/DenyRule
title: DenyRule
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/Shared.Types/DenyRule#SCHEMA_REPRESENTATION)

A deny rule in an IAM deny policy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;deniedPrincipals&quot;: [string],&quot;exceptionPrincipals&quot;: [string],&quot;deniedPermissions&quot;: [string],&quot;exceptionPermissions&quot;: [string],&quot;denialCondition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`deniedPrincipals[]`

`string`

The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{groupId}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/public:all` : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.

  - `principalSet://goog/cloudIdentityCustomerId/{customer_id}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{groupId}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/group/{groupId}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{projectNumber|folder_number|org_number}/type/ServiceAccount` : All service accounts grouped under a resource (project, folder, or organization).

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{projectNumber|folder_number|org_number}/type/ServiceAgent` : All service agents grouped under a resource (project, folder, or organization).

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{groupId}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`exceptionPrincipals[]`

`string`

The identities that are excluded from the deny rule, even if they are listed in the `deniedPrincipals` . For example, you could add a Google group to the `deniedPrincipals` , then exclude specific users who belong to that group.

This field can contain the same values as the `deniedPrincipals` field, excluding `principalSet://goog/public:all` , which represents all users on the internet.

`deniedPermissions[]`

`string`

The permissions that are explicitly denied by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. For example, `iam.googleapis.com/roles.list` .

`exceptionPermissions[]`

`string`

Specifies the permissions that this rule excludes from the set of denied permissions given by `deniedPermissions` . If a permission appears in `deniedPermissions` *and* in `exceptionPermissions` then it will *not* be denied.

The excluded permissions can be specified using the same syntax as `deniedPermissions` .

`denialCondition`

` object ( Expr  ` )

The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to `true` , then the deny rule is applied; otherwise, the deny rule is not applied.

Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.

The condition can use CEL functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) . Other functions and operators are not supported.
