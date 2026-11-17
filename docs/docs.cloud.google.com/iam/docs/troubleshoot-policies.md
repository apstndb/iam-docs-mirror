---
name: documents/docs.cloud.google.com/iam/docs/troubleshoot-policies
uri: https://docs.cloud.google.com/iam/docs/troubleshoot-policies
title: Troubleshoot IAM-related policies
description: Overview of the tools you can use to troubleshoot IAM-related policies.
data_source: docs.cloud.google.com
---

This page describes how to troubleshoot Identity and Access Management (IAM) allow policies, deny policies, Principal Access Boundary policies, and Unified Access Policies (UAPs).

## Use Policy Troubleshooter

If you need to troubleshoot access for a specific principal, use Policy Troubleshooter for IAM.

Policy Troubleshooter helps you understand whether a principal can access a resource. Given a principal, a resource, and a permission, Policy Troubleshooter examines the allow policies, deny policies, and Principal Access Boundary (PAB) policies that impact the principal's access. Then, it tells you whether, based on those policies, the principal can use the specified permission to access the resource. It also lists the relevant policies and explains how they affect the principal's access.

Policy Troubleshooter doesn't support troubleshooting UAPs. To learn how to troubleshoot UAPs, see [Troubleshoot manually](https://docs.cloud.google.com/iam/docs/troubleshoot-policies#manual-troubleshoot) on this page.

To learn how to use Policy Troubleshooter to troubleshoot allow policies, deny policies, and Principal Access Boundary policies, see [Troubleshoot IAM permissions](https://docs.cloud.google.com/policy-intelligence/docs/troubleshoot-access) .

## Search allow policies

If you need to find a specific role binding in an allow policy, you can search the allow policy.

Cloud Asset Inventory lets you search allow policies for role bindings that match the specified parameters. You can use a variety of search parameters, including the following:

- Resource type
- Principal type
- Role
- Project
- Folder
- Organization

For more information, see [Searching IAM allow policies](https://docs.cloud.google.com/asset-inventory/docs/searching-iam-policies) .

## Troubleshoot manually

To manually troubleshoot a principal's access to a resource, review all of the policies that can affect the principal's access.

### Required roles

To review all of the policies that affect a principal's access, you need permission to view allow policies, deny policies, UAP bindings, and UAPs.

To get the permissions that you need to view all allow and deny policies, ask your administrator to grant you the [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/iam.securityReviewer` ) IAM role on the organization that contains the resource.

To get the permissions that you need to view all UAP bindings that affect a target resource , ask your administrator to grant you the following IAM roles on the organization that contains the resource:

- [Organization Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin) ( `roles/resourcemanager.organizationAdmin` )
- List bindings for service-specific resources: A role with the permission `SERVICE `` . `` RESOURCE `` .searchPolicyBindings` , where `RESOURCE` is the resource type and `SERVICE` is the service that owns the resource.

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to view all UAP bindings that affect a target resource . To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to view all UAP bindings that affect a target resource :

- List bindings for organizations: `resourcemanager.organizations.searchPolicyBindings`
- List bindings for folders: `resourcemanager.folders.searchPolicyBindings`
- List bindings for projects: `resourcemanager.projects.searchPolicyBindings`
- List bindings for service-specific resources: `SERVICE `` . `` RESOURCE `` .searchPolicyBindings`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

To get the permissions that you need to view all UAP bindings that affect a target resource, ask your administrator to grant you roles that let you list bindings for that resource and that resource's ancestors. These roles must include the permission `SERVICE `` . `` RESOURCE `` .searchPolicyBindings` , where `RESOURCE` is the target resource type and `SERVICE` is the service that owns the resource.

To get the permissions that you need to view all UAPs, ask your administrator to grant you the [Access Policy Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer) ( `roles/iam.accessPolicyViewer` ) IAM role on the organization that contains the resource. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to view all UAPs. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to view all UAPs:

- List bindings for organizations: `resourcemanager.organizations.searchPolicyBindings`
- List bindings for folders: `resourcemanager.folders.searchPolicyBindings`
- List bindings for projects: `resourcemanager.projects.searchPolicyBindings`
- List bindings for service-specific resources: `SERVICE `` . `` RESOURCE `` .searchPolicyBindings`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### View all allow and deny policies that apply to a resource

In Google Cloud, the following allow and deny policies affect access to a resource:

- The resource's allow policy
- The resource's deny policies, if any
- The allow policies of the resource's parent project, folder, and organization, if any
- The deny policies of the resource's parent project, folder, and organization, if any

The allow and deny policies of parent projects, folders, and organizations affect access to a resource because of [policy inheritance](https://docs.cloud.google.com/iam/docs/policies#inheritance) . When you attach an allow or deny policy to a project, folder, or organization, that policy also applies for all resources inside that project, folder, or organization.

For example, if a deny policy for an organization says that a principal can't use a specific permission, then the principal can't use that permission for any resource within the organization. This rule applies even if the folders and projects within that organization have more permissive deny policies, or allow policies that give the principal the permission.

Similarly, if an allow policy for a project gives a principal a specific permission, then the principal has that permission for any resource within the project, provided that they aren't denied that permission.

The union of all of these policies is called the *applicable policy* or *effective policy* for the resource.

In Google Cloud, you can get a list of all of the allow and deny policies that affect access to a project by using the `gcloud beta projects get-ancestors-iam-policy` command with the `--include-deny` flag. Together, these policies make up the applicable policy for the project. You can investigate each policy to see how it affects the principal's access.

### gcloud

Before using any of the command data below, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .

Execute the [`gcloud beta projects get-ancestors-iam-policy`](https://docs.cloud.google.com/sdk/gcloud/reference/beta/projects/get-ancestors-iam-policy) command:

#### Linux, macOS, or Cloud Shell

```
gcloud beta projects get-ancestors-iam-policy PROJECT_ID --include-deny --format=json
```

#### Windows (PowerShell)

```
gcloud beta projects get-ancestors-iam-policy PROJECT_ID --include-deny --format=json
```

#### Windows (cmd.exe)

```
gcloud beta projects get-ancestors-iam-policy PROJECT_ID --include-deny --format=json
```

The response contains the allow and deny policies for the project; any folders that are ancestors of the project; and the organization. The following example shows allow policies for the organization `1234567890123` and the project `my-project` , as well as a deny policy for the project `my-project` :

```
[
  {
    "id": "1234567890123",
    "policy": {
      "bindings": [
        {
          "members": [
            "group:cloud-admins@example.com"
          ],
          "role": "roles/iam.denyAdmin"
        },
        {
          "members": [
            "user:raha@example.com"
          ],
          "role": "roles/iam.serviceAccountAdmin"
        }
      ],
      "etag": "BwXW6Eab7TI=",
      "version": 1
    },
    "type": "organization"
  },
  {
    "id": "my-project",
    "policy": {
      "bindings": [
        {
          "members": [
            "group:cloud-admins@example.com"
          ],
          "role": "roles/owner"
        }
      ],
      "etag": "BwXXjOM7L6M=",
      "type": "project"
    }
  },
  {
    "id": "my-project",
    "policy": {
      "createTime": "2022-02-14T21:46:35.865279Z",
      "displayName": "My deny policy",
      "etag": "MTgyMzg2ODcwNTEyMjMxMTM3Mjg=",
      "kind": "DenyPolicy",
      "name": "policies/cloudresourcemanager.googleapis.com%2Fprojects%2F123456789012/denypolicies/my-deny-policy",
      "rules": [
        {
          "denyRule": {
            "deniedPermissions": [
              "iam.googleapis.com/serviceAccounts.create"
            ],
            "deniedPrincipals": [
              "user:raha@example.com"
            ]
          },
          "description": "Prevent service account creation"
        }
      ],
      "uid": "c83e3dc3-d8a6-6f51-4018-814e9f200b05",
      "updateTime": "2022-02-14T21:46:35.865279Z"
    },
    "type": "project"
  }
]
```

In this example, Raha is granted the Service Account Admin role ( `roles/iam.serviceAccountAdmin` ) on the organization, but the project has a deny policy that prevents Raha from using the permission `iam.googleapis.com/serviceAccounts.create` . As a result, if Raha tries to create a service account in the project `my-project` , the request will be denied.

In some cases, you might only need to view the effective allow policy for a resource—for example, if your organization doesn't use deny policies. In these cases, you can use the following methods to view the effective allow policy:

- View the resource's IAM allow policy in the Google Cloud console. The Google Cloud console automatically shows each resource's effective policy.

  To learn how to view a resource's IAM allow policy in the Google Cloud console, see [View current access](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access#view-access) .

- Use the Cloud Asset API to get the resource's effective allow policy. To learn more, see [Viewing effective IAM policies](https://docs.cloud.google.com/asset-inventory/docs/view-effective-iam-policies) .

### View all Unified Access Policies that apply to a resource

> **Preview — Unified Access Policies (UAPs)**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

To view all UAPs that apply to a target resource, do the following:

### Console

1.  Identify all of the target resource's parent resources. The parent resources are any projects, folders, and organizations above the resource in the [resource hierarchy](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .
2.  [View the UAP bound to each parent resource](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#uap-list-console) . If the UAP mentions the principal, then it could affect the principal's access to the target resource.

### gcloud

1.  Identify all of the target resource's parent resources. The parent resources are any projects, folders, and organizations above the resource in the [resource hierarchy](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .
2.  [List UAP bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-target-bindings) for the target resource and each of the target resource's ancestors. Record the policy IDs in each binding.
3.  [View each UAP](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#get-uap) in each binding that you retrieved. If the UAP mentions the principal, then it could affect the principal's access to the target resource.

### REST

1.  Identify all of the target resource's parent resources. The parent resources are any projects, folders, and organizations above the resource in the [resource hierarchy](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .
2.  [List UAP bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-target-bindings) for the target resource and each of the target resource's ancestors. Record the policy IDs in each binding.
3.  [View each UAP](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#get-uap) in each binding that you retrieved. If the UAP mentions the principal, then it could affect the principal's access to the target resource.
