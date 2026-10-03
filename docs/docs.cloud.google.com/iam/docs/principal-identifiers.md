---
name: documents/docs.cloud.google.com/iam/docs/principal-identifiers
uri: https://docs.cloud.google.com/iam/docs/principal-identifiers
title: Principal identifiers
description: Understand principal identifier formats for Identity and Access Management (IAM) allow, deny, PAB, and access policies.
data_source: docs.cloud.google.com
---

When you refer to a principal in an Identity and Access Management (IAM) policy, you need to use the correct identifier for the principal. The format of the identifier depends on the [type of principal](https://docs.cloud.google.com/iam/docs/principals-overview#principal-types) that you want to refer to and the type of policy that you're writing.

This page lists the identifier formats for each policy type's supported principal types.

## Principal identifiers for allow policies

The following table describes the principal identifiers for [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) , which use the IAM `v1` API.

These identifiers are also used for [Privileged Access Manager entitlements](https://docs.cloud.google.com/iam/docs/pam-overview) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal type</th>
<th>Identifier</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Google Account</td>
<td><p><code>user: </code><var translate="no"> USER_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>user:alex@example.com</code></p>
<blockquote>
<strong>Note</strong> : When granting access to a new Google Account in the Google Cloud console, omit the <code>user:</code> prefix.
</blockquote></td>
</tr>
<tr class="even">
<td>Service account</td>
<td><p><code>serviceAccount: </code><var translate="no"> SA_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>serviceAccount:my-service-account@my-project.iam.gserviceaccount.com</code></p>
<blockquote>
When granting access to a new service account in the Google Cloud console, omit the <code>serviceAccount:</code> prefix.
</blockquote></td>
</tr>
<tr class="odd">
<td>All service accounts in a project, folder, or organization</td>
<td><p><code>principalSet://cloudresourcemanager.googleapis.com/ </code><var translate="no"> RESOURCE_TYPE </var><code> / </code><var translate="no"> RESOURCE_NUMBER </var><code> / type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in a project:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ projects/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in a folder:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ folders/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in an organization:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ organizations/ 123456789012/ type/ ServiceAccount</code></p>
<blockquote>
<strong>Note</strong> : Moving projects into or out of a folder or organization changes the service accounts included in this principal set. For example, if you move a project out of a folder or organization, then this principal set no longer includes that project's service accounts.
</blockquote></td>
</tr>
<tr class="even">
<td>Google group</td>
<td><p><code>group: </code><var translate="no"> GROUP_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>group:my-group@example.com</code></p>
<blockquote>
When granting access to a new Google group in the Google Cloud console, omit the <code>group:</code> prefix.
</blockquote></td>
</tr>
<tr class="odd">
<td>Google domain</td>
<td><p><code>domain: </code><var translate="no"> DOMAIN</var></p>
<p><strong>Example:</strong> <code>domain:example.com</code></p>
<blockquote>
When granting access to a new domain in the Google Cloud console, omit the <code>domain:</code> prefix.
</blockquote></td>
</tr>
<tr class="even">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#all-users">All users</a></td>
<td><code>allUsers</code></td>
</tr>
<tr class="odd">
<td><a href="https://docs.cloud.google.com/iam/docs/principals-overview#all-authenticated-users">All authenticated users</a></td>
<td><code>allAuthenticatedUsers</code></td>
</tr>
<tr class="even">
<td>Built-in resource identities</td>
<td>Only available for supported resources. The format varies depending on the resource. See <a href="https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities">Resources with built-in identities</a> for details.</td>
</tr>
<tr class="odd">
<td>Single identity in a workforce identity pool</td>
<td><code>principal://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var>
<p><strong>Example:</strong> <code>principal://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/subject/raha@altostrat.com</code></p></td>
</tr>
<tr class="even">
<td>All workforce identities in a group</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /group/ </code><var translate="no"> GROUP_ID</var>
<p><strong>Example using a group email:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/group/administrators-group@altostrat.com</code></p>
<p><strong>Example using a group UUID:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/group/abcdefgh-0123-0123-abcdef</code></p></td>
</tr>
<tr class="odd">
<td>All workforce identities with a specific attribute value</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /attribute. </code><var translate="no"> ATTRIBUTE_NAME </var><code> / </code><var translate="no"> ATTRIBUTE_VALUE</var>
<p><strong>Example:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/attribute.department/administration</code></p></td>
</tr>
<tr class="even">
<td>All identities in a workforce identity pool</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /*</code>
<p><strong>Example:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/*</code></p></td>
</tr>
<tr class="odd">
<td>Single identity in a workload identity pool</td>
<td><code>principal://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var></td>
</tr>
<tr class="even">
<td>Workload identity pool group</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /group/ </code><var translate="no"> GROUP_ID</var></td>
</tr>
<tr class="odd">
<td>All identities in a workload identity pool with a certain attribute</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /attribute. </code><var translate="no"> ATTRIBUTE_NAME </var><code> / </code><var translate="no"> ATTRIBUTE_VALUE</var></td>
</tr>
<tr class="even">
<td>All identities in a workload identity pool</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /*</code></td>
</tr>
<tr class="odd">
<td>Agent identity</td>
<td><p><code>principal:// </code><var translate="no"> TRUST_DOMAIN </var><code> /resources/ </code><var translate="no"> SERVICE </var><code> / </code><var translate="no"> RESOURCE_PATH</var></p>
<p><strong>Example (Vertex AI Agent Engine in an organization):</strong> <code>principal://agents.global.org-123456789012.system.id.goog/resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent</code></p>
<p><strong>Example (Vertex AI Agent Engine in a project without an organization):</strong> <code>principal://agents.global.proj-9876543210.system.id.goog/resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent</code></p>
<p><strong>Example (Gemini Enterprise):</strong> <code>principal://agents.global.org-123456789012.system.id.goog/resources/discoveryengine/projects/9876543210/locations/global/collections/default_collection/engines/my-test-agent</code></p></td>
</tr>
<tr class="even">
<td>All agent identities in a trust domain</td>
<td><p><code>principalSet:// </code><var translate="no"> TRUST_DOMAIN </var><code> /*</code></p>
<p><strong>Example:</strong> <code>principalSet://agents.global.org-123456789012.system.id.goog/*</code></p></td>
</tr>
<tr class="odd">
<td>All agent identities in a project</td>
<td><p><code>principalSet:// </code><var translate="no"> TRUST_DOMAIN </var><code> /attribute.platformContainer/aiplatform/projects/ </code><var translate="no"> PROJECT_NUMBER</var></p>
<p><strong>Example:</strong> <code>principalSet://agents.global.org-123456789012.system.id.goog/attribute.platformContainer/aiplatform/projects/9876543210</code></p></td>
</tr>
<tr class="even">
<td>All GKE Pods that use a specific Kubernetes service account</td>
<td><p>By service account name: <code>principal://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> PROJECT_ID </var><code> .svc.id.goog/subject/ns/ </code><var translate="no"> NAMESPACE </var><code> /sa/ </code><var translate="no"> KUBERNETES_SERVICE_ACCOUNT</var></p>
<p>By service account ID: <code>principal://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> PROJECT_ID </var><code> .svc.id.goog/kubernetes.serviceaccount.uid/ </code><var translate="no"> SERVICEACCOUNT_ID</var></p>
<p>Legacy format: <code>serviceAccount: </code><var translate="no"> PROJECT_ID </var><code> .svc.id.goog[ </code><var translate="no"> NAMESPACE </var><code> / </code><var translate="no"> KUBERNETES_SERVICE_ACCOUNT </var><code> ]</code></p></td>
</tr>
<tr class="odd">
<td>All GKE Pods in a Kubernetes namespace, regardless of service account or cluster</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> PROJECT_ID </var><code> .svc.id.goog/namespace/ </code><var translate="no"> NAMESPACE</var></td>
</tr>
<tr class="even">
<td>All GKE Pods in a specific cluster</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> PROJECT_ID </var><code> .svc.id.goog/kubernetes.cluster/https://container.googleapis.com/v1/projects/ </code><var translate="no"> PROJECT_ID </var><code> /locations/ </code><var translate="no"> LOCATION </var><code> /clusters/ </code><var translate="no"> CLUSTER_NAME</var></td>
</tr>
<tr class="odd">
<td>Deleted Google Account <sup>1</sup></td>
<td><p><code>deleted:user: </code><var translate="no"> USER_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:user:alex@example.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="even">
<td>Deleted service account <sup>1</sup></td>
<td><p><code>deleted:serviceAccount: </code><var translate="no"> SA_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:serviceAccount:my-service-account@my-project.iam.gserviceaccount.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="odd">
<td>Deleted Google group <sup>1</sup></td>
<td><p><code>deleted:group: </code><var translate="no"> GROUP_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:group:my-group@example.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="even">
<td>Deleted single identity in a workforce identity pool <sup>1</sup></td>
<td><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var></p>
<p><strong>Example:</strong> <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code></p></td>
</tr>
</tbody>
</table>

<sup>1</sup> Don't add deleted principals when creating or modifying policies.

## Principal identifiers for deny policies

The following table describes the principal identifiers for [deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) , which use the IAM `v2` API.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal type</th>
<th>Identifier</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Google Account</td>
<td><p><code>principal://goog/subject/ </code><var translate="no"> USER_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principal://goog/subject/alex@example.com</code></p></td>
</tr>
<tr class="even">
<td>Service account</td>
<td><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/ </code><var translate="no"> SA_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com</code></p></td>
</tr>
<tr class="odd">
<td>All service accounts in a project, folder, or organization</td>
<td><p><code>principalSet://cloudresourcemanager.googleapis.com/ </code><var translate="no"> RESOURCE_TYPE </var><code> / </code><var translate="no"> RESOURCE_NUMBER </var><code> / type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in a project:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ projects/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in a folder:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ folders/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in an organization:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ organizations/ 123456789012/ type/ ServiceAccount</code></p>
<blockquote>
<strong>Note</strong> : Moving projects into or out of a folder or organization changes the service accounts included in this principal set. For example, if you move a project out of a folder or organization, then this principal set no longer includes that project's service accounts.
</blockquote></td>
</tr>
<tr class="even">
<td>All <a href="https://docs.cloud.google.com/iam/docs/service-account-types#service-agents">service agents</a> associated with a project, folder, or organization</td>
<td><p><code>principalSet://cloudresourcemanager.googleapis.com/ </code><var translate="no"> RESOURCE_TYPE </var><code> / </code><var translate="no"> RESOURCE_NUMBER </var><code> / type/ ServiceAgent</code></p>
<p><strong>Example for all service agents associated with a project or its descendants:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ projects/ 123456789012/ type/ ServiceAgent</code></p>
<p><strong>Example for all service agents associated with a folder or its descendants:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ folders/ 123456789012/ type/ ServiceAgent</code></p>
<p><strong>Example for all service agents associated with an organization or its descendants:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ organizations/ 123456789012/ type/ ServiceAgent</code></p>
<blockquote>
<strong>Warning:</strong> Don't deny permissions for service agents—doing so might cause some Google Cloud services to stop working properly. Instead, use these principal sets to exempt service agents from deny rules.
</blockquote>
<blockquote>
<strong>Note</strong> : Moving projects into or out of a folder or organization changes the service agents included in this principal set. For example, if you move a project out of a folder or organization, then this principal set no longer includes that project's service agents.
</blockquote></td>
</tr>
<tr class="odd">
<td>Google group</td>
<td><p><code>principalSet://goog/group/ </code><var translate="no"> GROUP_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principalSet://goog/group/my-group@example.com</code></p></td>
</tr>
<tr class="even">
<td>All principals</td>
<td><code>principalSet://goog/public:all</code></td>
</tr>
<tr class="odd">
<td>All principals in a Cloud Identity account (domain)</td>
<td><p><code>principalSet://goog/cloudIdentityCustomerId/ </code><var translate="no"> CLOUD_IDENTITY_CUSTOMER_ID </var><sup><var translate="no">1</var></sup></p>
<p><strong>Example:</strong> <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code></p></td>
</tr>
<tr class="even">
<td>Single identity in a workforce identity pool</td>
<td><code>principal://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var>
<p><strong>Example:</strong> <code>principal://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/subject/raha@altostrat.com</code></p></td>
</tr>
<tr class="odd">
<td>All workforce identities in a group</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /group/ </code><var translate="no"> GROUP_ID</var>
<p><strong>Example using a group email:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/group/administrators-group@altostrat.com</code></p>
<p><strong>Example using a group UUID:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/group/abcdefgh-0123-0123-abcdef</code></p></td>
</tr>
<tr class="even">
<td>All workforce identities with a specific attribute value</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /attribute. </code><var translate="no"> ATTRIBUTE_NAME </var><code> / </code><var translate="no"> ATTRIBUTE_VALUE</var>
<p><strong>Example:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/attribute.department/administration</code></p></td>
</tr>
<tr class="odd">
<td>All identities in a workforce identity pool</td>
<td><code>principalSet://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /*</code>
<p><strong>Example:</strong> <code>principalSet://iam.googleapis.com/locations/global/workforcePools/altostrat-contractors/*</code></p></td>
</tr>
<tr class="even">
<td>Single identity in a workload identity pool</td>
<td><code>principal://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var></td>
</tr>
<tr class="odd">
<td>Workload identity pool group</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /group/ </code><var translate="no"> GROUP_ID</var></td>
</tr>
<tr class="even">
<td>All identities in a workload identity pool with a certain attribute</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /attribute. </code><var translate="no"> ATTRIBUTE_NAME </var><code> / </code><var translate="no"> ATTRIBUTE_VALUE</var></td>
</tr>
<tr class="odd">
<td>All identities in a workload identity pool</td>
<td><code>principalSet://iam.googleapis.com/projects/ </code><var translate="no"> PROJECT_NUMBER </var><code> /locations/global/workloadIdentityPools/ </code><var translate="no"> POOL_ID </var><code> /*</code></td>
</tr>
<tr class="even">
<td>Agent identity</td>
<td><p><code>principal:// </code><var translate="no"> TRUST_DOMAIN </var><code> /resources/ </code><var translate="no"> SERVICE </var><code> / </code><var translate="no"> RESOURCE_PATH</var></p>
<p><strong>Example (Vertex AI Agent Engine in an organization):</strong> <code>principal://agents.global.org-123456789012.system.id.goog/resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent</code></p>
<p><strong>Example (Vertex AI Agent Engine in a project without an organization):</strong> <code>principal://agents.global.proj-9876543210.system.id.goog/resources/aiplatform/projects/9876543210/locations/us-central1/reasoningEngines/my-test-agent</code></p>
<p><strong>Example (Gemini Enterprise):</strong> <code>principal://agents.global.org-123456789012.system.id.goog/resources/discoveryengine/projects/9876543210/locations/global/collections/default_collection/engines/my-test-agent</code></p></td>
</tr>
<tr class="odd">
<td>All agent identities in a trust domain</td>
<td><p><code>principalSet:// </code><var translate="no"> TRUST_DOMAIN </var><code> /*</code></p>
<p><strong>Example:</strong> <code>principalSet://agents.global.org-123456789012.system.id.goog/*</code></p></td>
</tr>
<tr class="even">
<td>All agent identities in a project</td>
<td><p><code>principalSet:// </code><var translate="no"> TRUST_DOMAIN </var><code> /attribute.platformContainer/aiplatform/projects/ </code><var translate="no"> PROJECT_NUMBER</var></p>
<p><strong>Example:</strong> <code>principalSet://agents.global.org-123456789012.system.id.goog/attribute.platformContainer/aiplatform/projects/9876543210</code></p></td>
</tr>
<tr class="odd">
<td>Deleted Google Account <sup>2</sup></td>
<td><p><code>deleted:principal://goog/subject/ </code><var translate="no"> USER_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:principal://goog/subject/alex@example.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="even">
<td>Deleted service account <sup>2</sup></td>
<td><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/ </code><var translate="no"> SA_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="odd">
<td>Deleted Google group <sup>2</sup></td>
<td><p><code>deleted:principalSet://goog/group/ </code><var translate="no"> GROUP_EMAIL_ADDRESS </var><code> ?uid= </code><var translate="no"> UNIQUE_ID</var></p>
<p><strong>Example:</strong> <code>deleted:principalSet://goog/group/my-group@example.com?uid=123456789012345678901</code></p></td>
</tr>
<tr class="even">
<td>Deleted single identity in a workforce identity pool <sup>2</sup></td>
<td><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/ </code><var translate="no"> POOL_ID </var><code> /subject/ </code><var translate="no"> SUBJECT_ATTRIBUTE_VALUE</var></p>
<p><strong>Example:</strong> <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code></p></td>
</tr>
</tbody>
</table>

<sup>1</sup> [Learn how to find your Cloud Identity customer ID](https://support.google.com/cloudidentity/answer/10070793) .

<sup>2</sup> Don't add deleted principals when creating or modifying policies.

## Principal identifiers for Principal Access Boundary policy bindings

The following table describes the identifiers for the principal sets that you can use in [Principal Access Boundary (PAB) policy bindings](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) . Principal Access Boundary policy bindings use the IAM `v3` API.

To learn which principals are included in each of these principal sets, see [Supported principal sets](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

| Principal type                                                                                                                | Identifier                                                                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Workforce identity pool                                                                                                       | `//iam.googleapis.com/locations/global/workforcePools/ `` WORKFORCE_POOL_ID` **Example:** `//iam.googleapis.com/locations/global/workforcePools/example-workforce-pool`                                                                   |
| Workload identity pool                                                                                                        | `//iam.googleapis.com/projects/ `` PROJECT_NUMBER `` /locations/global/workloadIdentityPools/ `` WORKLOAD_POOL_ID` **Example:** `//iam.googleapis.com/projects/123456789012/locations/global/workloadIdentityPools/example-workload-pool` |
| All [agent identities](https://docs.cloud.google.com/iam/docs/principals-overview#agent-identity) in a project's trust domain | `PROJECT_TRUST_DOMAIN `` / attribute.container/ projects/ `` PROJECT_NUMBER` **Example:** `//agents.global.proj-9876543210.system.id.goog/attribute.container/projects/9876543210`                                                        |
| Google Workspace domain                                                                                                       | `//iam.googleapis.com/locations/global/workspace/ `` CUSTOMER_ID `` `<sup>`1`</sup> **Example:** `//iam.googleapis.com/locations/global/workspace/C01Abc35`                                                                               |
| Project's principal set                                                                                                       | `//cloudresourcemanager.googleapis.com/projects/ `` PROJECT_ID` **Example:** `//cloudresourcemanager.googleapis.com/projects/example-project`                                                                                             |
| Folder's principal set                                                                                                        | `//cloudresourcemanager.googleapis.com/folders/ `` FOLDER_ID` **Example:** `//cloudresourcemanager.googleapis.com/folders/0123456789012`                                                                                                  |
| Organization's principal set                                                                                                  | `//cloudresourcemanager.googleapis.com/organizations/ `` ORGANIZATION_ID` **Example:** `//cloudresourcemanager.googleapis.com/organizations/0123456789012`                                                                                |

<sup>1</sup> [Learn how to find your Cloud Identity customer ID](https://support.google.com/cloudidentity/answer/10070793) .

## Principal types for access policies

The following table describes the principal identifiers that you can use in access policies. You can use access policies to control access to Eventarc resources. For more information, see the [Eventarc documentation](https://docs.cloud.google.com/eventarc/advanced/docs/control-publishing-access) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Principal type</th>
<th>Identifier</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>User</td>
<td><p><code>principal://goog/subject/ </code><var translate="no"> USER_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principal://goog/subject/alex@example.com</code></p></td>
</tr>
<tr class="even">
<td>Service account</td>
<td><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/ </code><var translate="no"> SA_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@my-project.iam.gserviceaccount.com</code></p></td>
</tr>
<tr class="odd">
<td>All service accounts in a project, folder, or organization</td>
<td><p><code>principalSet://cloudresourcemanager.googleapis.com/ </code><var translate="no"> RESOURCE_TYPE </var><code> / </code><var translate="no"> RESOURCE_NUMBER </var><code> / type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in a project:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ projects/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in a folder:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ folders/ 123456789012/ type/ ServiceAccount</code></p>
<p><strong>Example for all service accounts in all projects in an organization:</strong> <code>principalSet://cloudresourcemanager.googleapis.com/ organizations/ 123456789012/ type/ ServiceAccount</code></p>
<blockquote>
<strong>Note</strong> : Moving projects into or out of a folder or organization changes the service accounts included in this principal set. For example, if you move a project out of a folder or organization, then this principal set no longer includes that project's service accounts.
</blockquote></td>
</tr>
<tr class="even">
<td>Group</td>
<td><p><code>principalSet://goog/group/ </code><var translate="no"> GROUP_EMAIL_ADDRESS</var></p>
<p><strong>Example:</strong> <code>principalSet://goog/group/my-group@example.com</code></p></td>
</tr>
<tr class="odd">
<td>All principals <sup>1</sup></td>
<td><code>principalSet://goog/public:all</code></td>
</tr>
<tr class="even">
<td>All principals in a Cloud Identity account (domain)</td>
<td><p><code>principalSet://goog/cloudIdentityCustomerId/ </code><var translate="no"> CLOUD_IDENTITY_CUSTOMER_ID </var><sup><var translate="no">1</var></sup></p>
<p><strong>Example:</strong> <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code></p></td>
</tr>
</tbody>
</table>

<sup>1</sup> This value can only be used in access policies with the `DENY` action.
