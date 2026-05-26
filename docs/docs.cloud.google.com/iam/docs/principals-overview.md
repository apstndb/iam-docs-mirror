---
name: documents/docs.cloud.google.com/iam/docs/principals-overview
uri: https://docs.cloud.google.com/iam/docs/principals-overview
title: IAM principals
description: Overview of the principal types that you can use in {{dynamic_data.site_values.cloud_name}} Identity and Access Management (IAM).
data_source: docs.cloud.google.com
---

In Identity and Access Management (IAM), you control access for *principals* . A principal represents one or more identities that have authenticated to Google Cloud.

## Use principals in your policies

To use principals in your policies, do the following:

1.  **Configure identities that Google Cloud can recognize.** Configuring identities is the process of creating identities that Google Cloud can recognize. You can configure identities for users and for workloads.
    
    To learn how to configure identities, see the following:
    
      - To learn how to configure identities for users, see [Identities for users](https://docs.cloud.google.com/iam/docs/user-identities) .
      - To learn how to configure identities for workloads, see [Identities for workloads](https://docs.cloud.google.com/iam/docs/workload-identities) .

2.  **Determine the principal identifier that you will use.** The principal identifier is how you refer to a principal in your policies. This identifier can refer to a single identity or to a group of identities.
    
    The format that you use for the principal identifier depends on the following:
    
      - The type of principal
      - The type of the policy that you want to include the principal in
    
    To see the principal identifier format for each type of principal in each type of policy, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .
    
    After you know the format of the identifier, you can determine the principal's unique identifier based on the attributes of the principal, such as the principal's email address.

3.  **Include the principal's identifier in your policy.** Add your principal to your policy, following the format of the policy.
    
    To learn about the different types of policies in IAM, see [Policy types](https://docs.cloud.google.com/iam/docs/policy-types) .

### Support for principal types

Each IAM policy type supports a subset of the principal types that IAM supports. To see the principal types that are supported for each policy type, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

## Principal types

The following table briefly describes the different principal types supported by IAM. For a detailed description and examples of how a principal type might look when used in a policy, click the principal type name in the table.

Google Accounts Service accounts Service agents Google groups Domains allAuthenticatedUsers allUsers Workforce identity pool Workload identity pool Google Kubernetes Engine Pods Resource Manager principal sets

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal type</th>
<th>Description</th>
<th>Single principal or principal set</th>
<th>Google-managed or federated</th>
<th>Policy type support</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#google-account">Google Accounts</a></td>
<td>User accounts that represent a human who interacts with Google APIs and services.</td>
<td>Single principal</td>
<td>Google-managed</td>
<td><p>The following policy types support Google Accounts:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support Google Accounts:</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#service-account">Service accounts</a></td>
<td>An account that is used by a machine workload rather than a person.</td>
<td>Single principal</td>
<td>Google-managed</td>
<td><p>The following policy types support service accounts:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support service accounts:</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#service-account">A set of service accounts</a></td>
<td>All service accounts in a project, folder, or organization.</td>
<td>Principal set that contains service accounts.</td>
<td>Google-managed</td>
<td><p>The following policy types support a set of service accounts:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support a set of service accounts:</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#service-account">A set of service agents</a></td>
<td>All Google-managed service accounts (service agents) associated with a project, folder, or organization.</td>
<td>Principal set that contains service agents.</td>
<td>Google-managed</td>
<td><p>The following policy types support a set of service agents:</p>
<ul>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support a set of service agents:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#google-group">Google groups</a></td>
<td>A named collection of human or machine users with Google Accounts.</td>
<td><p>Principal set that can contain the following:</p>
<ul>
<li>Google Accounts</li>
<li>Service accounts</li>
</ul></td>
<td>Google-managed</td>
<td><p>The following policy types support Google groups:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support Google groups:</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#domains">Domains</a></td>
<td>A Google Workspace account or Cloud Identity domain that represents a virtual group. The group can contain both human users and service accounts.</td>
<td><p>Principal set that can contain the following principal types:</p>
<ul>
<li>Google Accounts</li>
<li>Service accounts</li>
</ul></td>
<td>Google-managed</td>
<td><p>The following policy types support domains:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#all-authenticated-users"><code dir="ltr" translate="no">allAuthenticatedUsers</code></a></td>
<td>A special identifier that represents all service accounts and human users on the internet who have authenticated with a Google Account.</td>
<td><p>Principal set that can contain the following principal types:</p>
<ul>
<li>Google Accounts</li>
<li>Service accounts</li>
<li>Workforce identities</li>
<li>Workload identities</li>
</ul></td>
<td>Google-managed</td>
<td><p>The following policy types support <code dir="ltr" translate="no">allAuthenticatedUsers</code> for some resources:</p>
<ul>
<li><strong>Allow</strong></li>
</ul>
<p>The following policy types don't support <code dir="ltr" translate="no">allAuthenticatedUsers</code> :</p>
<ul>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#all-users"><code dir="ltr" translate="no">allUsers</code></a></td>
<td>A special identifier that represents anyone who is on the internet—authenticated and unauthenticated.</td>
<td><p>Principal set that can contain the following principal types:</p>
<ul>
<li>Google Accounts</li>
<li>Service accounts</li>
<li>Workforce identities</li>
<li>Workload identities</li>
</ul></td>
<td>Both</td>
<td><p>The following policy types support <code dir="ltr" translate="no">allUsers</code> :</p>
<ul>
<li><strong>Allow</strong> (for some resources)</li>
<li><strong>Deny</strong></li>
</ul>
<p>The following policy types don't support <code dir="ltr" translate="no">allUsers</code> :</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#workforce">A single identity in a workforce identity pool</a></td>
<td>A human user with an identity that is managed by an external IdP and federated by using Workforce Identity Federation.</td>
<td>Single principal</td>
<td>Federated</td>
<td><p>The following policy types support a single identity in a workforce identity pool:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#workforce">A set of principals in a workforce identity pool</a></td>
<td>A set of human users with identities that are managed by an external IdP and federated by using Workforce Identity Federation.</td>
<td>Principal set that contains workforce identities.</td>
<td>Federated</td>
<td><p>The following policy types support a set of principals in a workforce identity pool:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#workload">A single principal in a workload identity pool</a></td>
<td>A workload (or machine user) with an identity that is managed by an external IdP and federated by using Workload Identity Federation.</td>
<td>Single principal</td>
<td>Federated</td>
<td><p>The following policy types support a single principal in a workload identity pool:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#workload">A set of principals in a workload identity pool</a></td>
<td>A set of workloads (or machine users) with identities that are managed by an external IdP and federated by using Workload Identity Federation.</td>
<td>Principal set that contains workload identities</td>
<td>Federated</td>
<td><p>The following policy types support a set of principals in a workload identity pool:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#pods">A set of Google Kubernetes Engine Pods</a></td>
<td>A workload (or machine user) running on and federated through GKE.</td>
<td>Principal set that can contain one or more federated workload identities</td>
<td>Federated</td>
<td><p>The following policy types support GKE pods:</p>
<ul>
<li><strong>Allow</strong></li>
</ul>
<p>The following policy types don't support GKE pods:</p>
<ul>
<li><strong>Deny</strong></li>
<li><strong>Principal access boundary</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#agent-identity">Agent identities</a></td>
<td>An identity for an agentic workload that is strongly attested is tied to the lifecycle of the agent.</td>
<td>Single principal</td>
<td>Google-managed</td>
<td><p>The following policy types support agent identities:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#agent-identity">A set of agent identities</a></td>
<td>All agent identities in an agent identity pool.</td>
<td>Principal set that contains agent identities.</td>
<td>Google-managed</td>
<td><p>The following policy types support a set of agent identities:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#crm-principal-sets">Resource Manager principal sets</a></td>
<td>A set of human or machine users associated with Google Cloud resources such as projects, folders, and organizations.</td>
<td><p>Principal set that can contain the following principal types:</p>
<ul>
<li>Google Accounts</li>
<li>Service accounts</li>
<li>Workforce identities</li>
<li>Workload identities</li>
</ul></td>
<td>Both</td>
<td><p>The following policy types support Resource Manager principal sets:</p>
<ul>
<li><strong>Principal access boundary</strong></li>
</ul>
<p>The following policy types don't support Resource Manager principal sets:</p>
<ul>
<li><strong>Allow</strong></li>
<li><strong>Deny</strong></li>
</ul></td>
</tr>
</tbody>
</table>

The following sections describe these principal types in more detail.

### Google Accounts

A Google Account represents a developer, an administrator, or any other person who interacts with Google Cloud by using an account they created with Google. Any email address that's associated with a Google Account, also called a *managed user account* , can be used as a principal. This includes `gmail.com` email addresses and email addresses with other domains.

The following examples show how you can identify a Google Account in different types of policies:

  - **Allow policies** : `user:alex@example.com`
  - **Deny policies** : `principal://goog/subject/alex@example.com`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

In your allow and deny policies, email aliases associated with a Google Account or a managed user account are automatically replaced with the primary email address. This means that the policy displays the user's primary email address when you grant access to an email alias.

For more information about setting up Google Accounts, see [Cloud Identity or Google Workspace accounts](https://docs.cloud.google.com/iam/docs/user-identities#google-accounts) .

### Service accounts

A service account is an account for an application or compute workload instead of an individual end user. Service accounts can be divided into *user-managed service accounts* and Google-managed service accounts, which are called *service agents* :

  - When you run code that's hosted on Google Cloud, you specify a service account to use as the identity for your application. You can create as many user-managed service accounts as needed to represent the different logical components of your application.

  - Some Google Cloud services need access to your resources so they can act on your behalf. Google creates and manages service agents to meet this need.

You can reference service accounts and service agents in the following ways:

  - A single service account
  - All service accounts in a project
  - All service agents associated with a project
  - All service accounts in all projects in a folder
  - All service agents associated with a folder and its descendants
  - All service accounts in all projects in an organization
  - All service agents associated with an organization and its descendants

The following examples show how you can identify an individual service account in different types of policies:

  - **A service account in allow policies** : `serviceAccount:my-service-account@my-project.iam.gserviceaccount.com`
  - **A service account in deny policies** : `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com`

The following examples show how you can identify all service accounts for a project, folder, or organization in different types of policies:

  - **All service accounts for a project in allow policies** : `principalSet://cloudresourcemanager.googleapis.com/projects/123456789012/type/ServiceAccount`
  - **All service agents associated with a folder in deny policies** : `principalSet://cloudresourcemanager.googleapis.com/folders/123456789012/type/ServiceAgent`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

For more information about service accounts, see the following pages:

  - [Service accounts overview](https://docs.cloud.google.com/iam/docs/service-account-overview)
  - [Types of service accounts](https://docs.cloud.google.com/iam/docs/service-account-types)

> **Note:** If you use Google Kubernetes Engine (GKE), you can also grant roles to [Kubernetes service accounts](https://docs.cloud.google.com/kubernetes-engine/docs/how-to/service-accounts#kubernetes-service-accounts) , which differ from IAM service accounts.

### Google groups

A Google group is a named collection of Google Accounts. Every Google group has a unique email address that's associated with the group. You can find the email address that's associated with a Google group by clicking **About** on the homepage of any Google group. For more information about Google Groups, see the [Google Groups](https://groups.google.com/) homepage.

Google groups are a convenient way to apply access controls to a collection of principals. You can grant and change access controls for a whole group at once instead of granting or changing access controls one at a time for individual principals. You can also add principals to or remove principals from a Google group instead of updating an allow policy to add or remove principals.

Google groups don't have login credentials, and you can't use Google groups to establish identity to make a request to access a resource.

The following examples show how you can identify a Google group in different types of policies:

  - **Allow policies** : `group:my-group@example.com`
  - **Deny policies** : `principalSet://goog/group/my-group@example.com`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

To learn more about using groups for access control, see [Best practices for using Google groups](https://docs.cloud.google.com/iam/docs/groups-best-practices) .

<span id="domains"></span>

### Domains

Domains can exist as either Google Workspace accounts or Cloud Identity domains. They are fundamentally the same because they both represent a virtual group of all the Google Accounts that they contain. The only difference is that Cloud Identity domain users don't have access to Google Workspace applications and features.

Like Google groups, domains can't be used to establish identity, but they enable convenient permission management.

When you create a Google Account for a new user, such as `username@example.com` , that Google Account is added to the virtual group for your Google Workspace account or Cloud Identity domain. When you modify access for the Google Workspace account or Cloud Identity domain, you modify access for all Google Accounts in that virtual group.

The following examples show how you can identify a domain in different types of policies:

  - **Allow policies** : `domain:example.com`
  - **Deny policies** : `principalSet://goog/cloudIdentityCustomerId/C01Abc35`
  - **Principal access boundary policies** : `//iam.googleapis.com/locations/global/workspace/C01Abc35`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

For more information about Cloud Identity, see [About Cloud Identity](https://support.google.com/a/answer/7319251) .

#### Secondary domains

When you create a Google Workspace account or a Cloud Identity domain, you're assigned a unique customer ID. Then, you provide a domain name that becomes your primary domain name—for example, `example.com` .

After you create your primary domain, you can optionally add [secondary domains](https://support.google.com/a/answer/7502379) with their own domain names. However, these domains are associated with the same customer ID as the primary domain.

IAM uses your customer ID to identify members in the domain, not the domain name. As a result, you can't manage access for primary and secondary domains separately. This is true even for allow policies, where you identify the domain using the domain name. When evaluating allow policies, IAM identifies the customer ID associated with that domain, then uses that customer ID—not the domain name—to identify members of that domain.

Domain names in allow policies default to the primary domain name. If you grant access to a domain using a secondary domain name, it will be automatically replaced with the corresponding primary domain name.

<span id="allauthenticatedusers"></span>

### `allAuthenticatedUsers`

The value `allAuthenticatedUsers` is a special identifier that represents all service accounts and all users on the internet who have authenticated with a Google Account. This identifier includes accounts that aren't connected to a Google Workspace account or Cloud Identity domain, such as personal Gmail accounts. Users who aren't authenticated, such as anonymous visitors, aren't included.

> **Note:** By default, organizations created on or after May 3, 2024 don't allow roles to be granted to `allAuthenticatedUsers` . This is because of the default configuration of the `iam.managed.allowedPolicyMembers` constraint. To learn how to change this setting, see [Restricting identities by domain](https://docs.cloud.google.com/resource-manager/docs/organization-policy/restricting-domains) .

> **Note:** Consider using [`allUsers`](https://docs.cloud.google.com/iam/docs/principals-overview#all-users) , as described on this page, rather than `allAuthenticatedUsers` . In many cases, granting access to all users is no more of a security risk than granting access only to authenticated users.

This principal type doesn't include federated identities, which are managed by external identity providers (IdPs). If you use [Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-identity-federation) or [Workload Identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation) , don't use `allAuthenticatedUsers` . Instead, use one of the following:

  - To include users from all IdPs, use `allUsers` .
  - To include users from specific external IdPs, use the identifier for [all identities in a workforce identity pool](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#representing-workforce-users) or [all identities in a workload identity pool](https://docs.cloud.google.com/iam/docs/workload-identity-federation#impersonation) .

Some resource types don't support this principal type.

<span id="allusers"></span>

### `allUsers`

The value `allUsers` is a special identifier that represents anyone who is on the internet, including authenticated and unauthenticated users.

Some resource types don't support this principal type.

> **Note:** By default, organizations created on or after May 3, 2024 don't allow roles to be granted to `allUsers` . This is because of the default configuration of the `iam.managed.allowedPolicyMembers` constraint. To learn how to change this setting, see [Restricting identities by domain](https://docs.cloud.google.com/resource-manager/docs/organization-policy/restricting-domains) .

> **Note:** Some Google Cloud services require authentication before a user can access the service. For these services, `allUsers` includes only authenticated users.

The following examples show how the `allUsers` identifier might look in different types of policies:

  - **Allow policies on supported resource types** : `allUsers`
  - **Deny policies** : `principalSet://goog/public:all`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

### Federated identities in a workforce identity pool

A workforce identity pool is a set of user identities that is managed by an external IdP and federated by using [Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-identity-federation) . You can reference principals in these pools in the following ways:

  - A single identity in a workforce identity pool
  - All workforce identities in a specified group
  - All workforce identities with a specific attribute value
  - All identities in a workforce identity pool

The following examples show how you can identify federated workforce identity pools in different types of policies:

  - **A single identity in allow policies** : `principal://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/subject/raha@altostrat.com`
  - **A group of identities in deny policies** : `principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/group/administrators-group@altostrat.com`
  - **A workforce identity pool in Principal access boundary policies** : `//iam.googleapis.com/locations/global/workforcePools/example-workforce-pool`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

### Federated identities in a workload identity pool

A workload identity pool is a set of workload identities that is managed by an external IdP and federated by using [Workload Identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation) . You can reference principals in these pools in the following ways:

  - A single identity in a workload identity pool
  - All workload identities in a specified group
  - All workload identities with a specific attribute value
  - All identities in a workload identity pool

The following examples show how you can identify federated workload identity pools in different types of policies:

  - **A single identity in allow policies** : `principal://iam.googleapis.com/projects/123456789012/locations/global/workloadIdentityPools/altostrat-contractors/subject/raha@altostrat.com`
  - **A group of identities in deny policies** : `principalSet://iam.googleapis.com/projects/123456789012/locations/global/workloadIdentityPools/altostrat-contractors/group/administrators-group@altostrat.com`
  - **A workload identity pool in Principal access boundary policies** : `//iam.googleapis.com/projects/123456789012/locations/global/workloadIdentityPools/example-workload-pool`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

### GKE Pods

Workloads running on GKE use [Workload Identity Federation for GKE](https://docs.cloud.google.com/kubernetes-engine/docs/concepts/workload-identity) to access Google Cloud services. For more information about principal identifiers for GKE Pods, see [Reference Kubernetes resources in IAM policies](https://docs.cloud.google.com/kubernetes-engine/docs/concepts/workload-identity#kubernetes-resources-iam-policies) .

The following example shows how you can identify all GKE pods in a specific cluster in an allow policy:

    principalSet://iam.googleapis.com/projects/123456789012/locations/global/workloadIdentityPools/123456789012.svc.id.goog/kubernetes.cluster/https://container.googleapis.com/v1/projects/123456789012/locations/global/clusters/example-gke-cluster

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

### Agent identities

> **Preview**
> 
> This product or feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA products and features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

An agent identity is a Google-managed identity for agentic workloads. An agent identity is attested and tied to the lifecycle of the agent, which provides a more secure way to manage agent access to Google Cloud resources than using service accounts.

Each agent is automatically provisioned with an agent identity. You can grant or deny access to Google Cloud resources using IAM policies.

The following example shows how you can identify an agent identity in an allow policy or deny policy:

`principal://agents.global.org-123456789012.system.id.goog/resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent`

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

### Resource Manager principal sets

Each Resource Manager resource—such as a project, folder, or organization—is associated with a set of principals. When you're creating principal access boundary policy bindings, you can use the principal set for a Resource Manager resource to reference all principals associated with that resource.

Principal sets for Resource Manager resources contain the following principals:

  - **Project principal set** : All service accounts and workload identity pools in the specified project.

  - **Folder principal set** : All service accounts and all workload identity pools in any project in the specified folder.

  - **Organization principal set** : Contains the following identities:
    
      - All identities in all domains associated with your Google Workspace customer ID
      - All workforce identity pools in your organization
      - All service accounts and workload identity pools in any project in the organization

The following example shows how you can identify a project's principal set in a principal access boundary policy:

    //cloudresourcemanager.googleapis.com/projects/example-project

To learn more about principal identifier formats, see [Principal identifiers](https://docs.cloud.google.com/iam/docs/principal-identifiers) .

## What's next

  - Learn about the [policy types](https://docs.cloud.google.com/iam/docs/policy-types) that IAM supports
  - [Grant a principal a role](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) on a Resource Manager project, folder, or organization
