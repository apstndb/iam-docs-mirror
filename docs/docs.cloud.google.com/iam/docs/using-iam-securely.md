---
name: documents/docs.cloud.google.com/iam/docs/using-iam-securely
uri: https://docs.cloud.google.com/iam/docs/using-iam-securely
title: Use IAM securely
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page recommends security best practices that you should keep in mind when using IAM.

This page is designed for users who are proficient with IAM. If you are just starting out with IAM, these instructions will not teach you how to use it; instead, new users should start with the [IAM Quickstart](https://docs.cloud.google.com/iam/docs/grant-role-console) .

## Least privilege

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td>❑
Basic roles include thousands of permissions across all Google Cloud services. In production environments, do not grant basic roles unless there is no alternative. Instead, grant the most limited <a href="https://docs.cloud.google.com/iam/docs/roles-permissions">predefined roles</a> or <a href="https://docs.cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that meet your needs.
<p>If you need to replace a basic role, you can use <a href="https://docs.cloud.google.com/iam/docs/recommender-overview">role recommendations</a> to determine which roles to grant instead. You can also use the <a href="https://docs.cloud.google.com/iam/docs/understanding-simulator">Policy Simulator</a> to ensure that changing the role won't affect the principal's access.</p>
<p>It might be appropriate to grant basic roles when you want to grant broader permissions for a project. For example, you can grant basic roles for use in test or development environments.</p></td>
</tr>
<tr class="even">
<td>❑
Treat each component of your application as a separate trust boundary. If you have multiple services that require different permissions, <a href="https://docs.cloud.google.com/iam/docs/managing-service-accounts">create a separate service account</a> for each of the services, then grant only the required permissions to each service account.</td>
</tr>
<tr class="odd">
<td>❑
Remember that the allow policies for child resources inherit from the allow policies for their parent resources. For example, if the allow policy for a project grants a user the ability to administer Compute Engine virtual machine (VM) instances, then the user can administer any Compute Engine VM in that project, regardless of the allow policy you set on each VM.</td>
</tr>
<tr class="even">
<td>❑
Grant roles at the smallest scope needed. For example, if a user only needs access to publish Pub/Sub topics, grant the <a href="https://docs.cloud.google.com/pubsub/access_control#tbl_roles">Publisher</a> role to the user for that topic.</td>
</tr>
<tr class="odd">
<td>❑
Specify which principals can <a href="https://docs.cloud.google.com/iam/docs/service-account-permissions#user-role">act as service accounts</a> . Users who are granted the Service Account User role for a service account can access all the resources to which the service account has access. Therefore, be cautious when granting the Service Account User role to a user.</td>
</tr>
<tr class="even">
<td>❑
Specify who has access to create and manage service accounts in your project.</td>
</tr>
<tr class="odd">
<td>❑
Granting the <a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager">Project IAM Admin and Folder IAM Admin</a> predefined roles will allow access to modify allow policies without also allowing direct read, write, and administrative access to all resources.<br />
<br />
Granting the <a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code dir="ltr" translate="no">roles/owner</code> ) role to a principal will allow them to access and modify almost all resources, including modifying allow policies. This amount of privilege is potentially risky. Grant the Owner role only when (nearly) universal access is required.</td>
</tr>
<tr class="even">
<td>❑
Use <a href="https://docs.cloud.google.com/iam/docs/configuring-temporary-access">conditional role bindings</a> to let access expire automatically, and consider granting <a href="https://docs.cloud.google.com/iam/docs/temporary-elevated-access">temporary elevated access.</a></td>
</tr>
</tbody>
</table>

<span id="service_accounts_and_service_account_keys"></span>

## Service accounts

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td>❑
<a href="https://docs.cloud.google.com/iam/docs/best-practices-service-accounts">Adopt best practices for working with service accounts</a> . Ensure that service accounts have limited privileges, and protect against potential security threats.</td>
</tr>
<tr class="even">
<td>❑
Do not delete service accounts that are in use by running instances. This could result in all or parts of your application to fail if you have not transitioned to using an alternative service account first.</td>
</tr>
<tr class="odd">
<td>❑
Use the display name of a service account to keep track of what the service account is used for and what permissions it needs.</td>
</tr>
</tbody>
</table>

## Service account keys

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td>❑
<strong>Avoid using service account keys if another option is available.</strong> Service account keys are a security risk if not managed correctly. You should <a href="https://docs.cloud.google.com/docs/authentication#auth-decision-tree">choose a more secure alternative to service account keys</a> whenever possible. If you must authenticate with a service account key, you are responsible for the security of the private key and for other operations described by <a href="https://docs.cloud.google.com/iam/docs/best-practices-for-managing-service-account-keys">Best practices for managing service account keys</a> . If you are prevented from creating a service account key, service account key creation might be disabled for your organization. For more information, see <a href="https://docs.cloud.google.com/resource-manager/docs/secure-by-default-organizations">Managing secure-by-default organization resources</a> .
<p>If you acquired the service account key from an external source, you must validate it before use. For more information, see <a href="https://docs.cloud.google.com/docs/authentication/external/externally-sourced-credentials">Security requirements for externally sourced credentials</a> .</p></td>
</tr>
<tr class="even">
<td>❑
Rotate your service account keys using the <a href="https://docs.cloud.google.com/iam/reference/rest/v1">IAM service account API</a> . You can rotate a key by creating a new key, switching applications to use the new key, disabling the old key, and then deleting the old key when you are sure that it is no longer needed.</td>
</tr>
<tr class="odd">
<td>❑
<a href="https://docs.cloud.google.com/iam/docs/best-practices-for-managing-service-account-keys">Implement processes</a> to manage user-managed service account keys.</td>
</tr>
<tr class="even">
<td>❑
Be careful not to confuse encryption keys with service account keys. Encryption keys are typically used to encrypt data and service account keys are used for secure access to Google Cloud APIs.</td>
</tr>
<tr class="odd">
<td>❑
Don't check in the service account keys into the source code or leave them in the Downloads directory.</td>
</tr>
</tbody>
</table>

## Auditing

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td>❑
Use logs from <a href="https://docs.cloud.google.com/logging/docs/audit">Cloud Audit Logs</a> to regularly audit changes to your allow policy.</td>
</tr>
<tr class="even">
<td>❑
<a href="https://docs.cloud.google.com/logging/docs/export">Export audit logs</a> to Cloud Storage to store your logs for long periods of time.</td>
</tr>
<tr class="odd">
<td>❑
Audit who has the ability to change your allow policies on your projects.</td>
</tr>
<tr class="even">
<td>❑
Manage access to logs using <a href="https://docs.cloud.google.com/logging/docs/access-control">Logging roles</a> .</td>
</tr>
<tr class="odd">
<td>❑
Apply the same access policies to the Google Cloud resource that you use to route logs as applied to the Logs Explorer.</td>
</tr>
<tr class="even">
<td>❑
Use logs from Cloud Audit Logs to regularly audit access to service account keys.</td>
</tr>
</tbody>
</table>

## Policy management

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td>❑
If a principal needs access to all projects in your organization, grant roles to the principal at the <a href="https://docs.cloud.google.com/resource-manager/docs/access-control-org">organization level</a> .</td>
</tr>
<tr class="even">
<td>❑
Grant roles to groups instead of individual users when possible. It is easier to update the members of a group than to update the principals in your allow policies.</td>
</tr>
</tbody>
</table>
