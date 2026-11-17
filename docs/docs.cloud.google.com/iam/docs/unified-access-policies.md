---
name: documents/docs.cloud.google.com/iam/docs/unified-access-policies
uri: https://docs.cloud.google.com/iam/docs/unified-access-policies
title: Unified Access Policies
description: Conceptual information about Unified Access Policies, which you can use to grant and deny access to supported resources.
data_source: docs.cloud.google.com
---

> **Preview**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

*Unified Access Policies (UAPs)* let you grant and deny access to Google Cloud resources. Unlike allow and deny policies, UAPs let you grant and deny access in the same policy, allowing for simplified policy management. UAPs are also reusable, meaning you can apply the same UAP to multiple resources.

## How Unified Access Policies work

To grant or deny access in IAM, you need to specify *who* should be allowed or not allowed to do *what* on *which resource* .

In UAPs, you specify *who* should be allowed or not allowed to do *what* by creating *UAP rules* . Each rule lists a set of principals, a set of roles and permissions, and an effect. The effect—allow or deny—specifies whether the listed principals are granted the roles and permissions in the rule or prevented from using the permissions in the rule. You can have up to 100 rules in a single UAP.

To specify *which resource* a UAP controls access for, you use a UAP binding to *bind* the UAP to a resource. You can bind a single UAP to up to 5 resources. A single resource can have up to 5 policies bound to it.

### Use cases

In IAM, there are multiple policy types that you can use to allow and deny access:

- To allow access, you can use [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) or UAP allow rules.
- To deny access, you can use [deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) or UAP deny rules.

If you already use allow or deny policies to control access, then we recommend continuing to use those policies. These policy types are also supported in Policy Troubleshooter, which makes it easier to understand the root cause of access errors.

Use UAPs in the following circumstances:

- You're setting up a new organization and plan to use UAPs to control access across your organization.
- You want to set up fine-grained access control using [UAP conditions](https://docs.cloud.google.com/iam/docs/unified-access-policies#conditions) .

## Unified Access Policy rules

UAPs are made of allow and deny rules. These rules contain the following components:

- **An effect** : Whether the rule grants access or denies access. Rules that grant access are called *allow rules* . Rules that deny access are called *deny rules* .

- **A set of principals** : The principals—for example, users, groups, or service accounts—that you want to include in the rule. In allow rules, these principals are granted access. In deny rules, these principals are denied access.

- **A list of roles and permissions** : The roles and permissions that you want to include in the rule. In allow rules, these permissions are granted. In deny rules, these permissions are denied.

- **Optional: A condition expression** : An IAM Conditions expression specifying the conditions that must be true for the rule to apply. For more information, see [Conditions in UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies#conditions) on this page.

### Principals in Unified Access Policy rules

To specify principals that you want to include in the rule, you define the following:

- **Included principals** : The principals that you want to include in the rule.
- **Excluded principals** : The principals that you want to exclude from the rule, even if they're in a group in the list of included principals.

With these two lists, you can concisely specify which principals you want to include in the rule. For example, imagine you're creating an allow rule to grant access to users in `example.com` . If you wanted to grant access to everyone in the group `all@example.com` except for the user `reduced-access@example.com` , then you would add `all@example.com` to the list of included principals and `reduced-access@example.com` to the list of excluded principals.

### Roles and permissions in Unified Access Policy rules

To create an exact list of permissions that you want to include in the rule, you define the following:

- **Included permissions** : The permissions that you want to include in the rule.
- **Excluded permissions** : The permissions that you don't want to include in the rule, even if they're in a role or permission group in the list of included permissions.

To add permissions to the list of included permissions or excluded permissions, you can reference any of the following:

- **Permissions** : Individual permission names in the fully qualified domain name (FQDN) format. For example, `cloudresourcemanager.googleapis.com/projects.get` .

- **Roles (allow rules only)** : Predefined role names, such as `roles/logging.logsViewer` . If you include a role name in a rule, then the rule includes all of the permissions in that role. To see all of the permissions in a role, see [the roles and permissions reference](https://docs.cloud.google.com/iam/docs/roles-permissions) .

  In the UAP JSON, these names are always prefaced with `role:` —for example, `role:roles/logging.logsViewer` .

  Roles are only permitted in allow rules. [Custom roles](https://docs.cloud.google.com/iam/docs/roles-overview#custom) aren't supported in any rules.

- **Permission groups** : Sets of permissions, such as `aiplatform.googleapis.com/*.*` . Permission groups are sets of permissions that match a specified pattern. There are some restrictions on the permission groups you can reference and the permissions included in those groups. For more information, see [Permission groups](https://docs.cloud.google.com/iam/docs/unified-access-policies#permission-groups) on this page.

## Permission groups

Permission groups are sets of permissions that match a specified pattern. You can use a permission group to grant or deny sets of related permissions—for example, you can deny all permissions for a single service or grant all permissions that end in a certain verb.

Permission groups work differently in allow and deny rules. The following sections explain how to use permission groups in each rule type.

### Permission groups in allow rules

To identify a permission group in an allow rule, replace one or more sections of a permission name with a wildcard character ( `*` ). The permissions that each group includes depend on the position of the wildcard:

- `SERVICE_FQDN `` / `` RESOURCE `` .*` : Includes all permissions for the specified resource.
- `SERVICE_FQDN `` /*.*` : Includes all permissions for the specified service.
- `SERVICE_FQDN `` /*. `` VERB` : Includes all permissions for a service that end in the specified verb.
- `*/*. `` VERB` : Includes all permissions that end in the specified verb.
- `*` : Includes all permissions. This value is allowed only when listing included permissions, not excluded permissions.

Permission groups only include the permissions that are supported in custom roles. Other permissions aren't included, even if they match the specified format.

To learn which permissions are supported in custom roles, see [Support levels for permissions in custom roles](https://docs.cloud.google.com/iam/docs/custom-roles-permissions-support) .

The permissions listed on that page don't use the same format as the permissions in UAPs:

- Custom roles use the `v1` format for permission names, which is `SERVICE_ID `` . `` RESOURCE `` . `` VERB` .
- UAPs use the fully qualified domain name format for permission names, which is `SERVICE_FQDN `` / `` RESOURCE `` . `` VERB` .

However, the values for `SERVICE_ID` and `SERVICE_FQDN` are typically similar. In most cases, the value of `SERVICE_FQDN` is the value of `SERVICE_ID` from the `v1` API, followed by `.googleapis.com` . For example, the permission to delete a role can be written in the following ways:

- `v1` format: `iam.roles.delete`
- Fully qualified domain name format: `iam.googleapis.com/roles.delete`

You can use this similarity to translate between the two formats when reviewing permission groups for allow rules.

There are some exceptions to this rule. To see these exceptions, review the [list of permissions supported in deny policies](https://docs.cloud.google.com/iam/docs/deny-permissions-support) and search for `IAM v1 API` in the filter field.

### Permission groups in deny rules

Deny rules only support certain permission groups. Supported permission groups are listed in [Permissions supported in deny policies](https://docs.cloud.google.com/iam/docs/deny-permissions-support) . The identifiers for the supported permission groups replace one or more sections of a permission name with a wildcard character ( `*` ). The permissions that each group includes depend on the position of the wildcard:

- `SERVICE_FQDN `` / `` RESOURCE `` .*` : Denies all permissions for the specified resource.
- `SERVICE_FQDN `` /*.*` : Denies all permissions for the specified service.
- `SERVICE_FQDN `` /*. `` VERB` : Denies all permissions for a service that end in the specified verb.

Permission groups include all current and future permissions that match the specified pattern. For example, imagine that you use the permission group `example.googleapis.com/exampleResource.*` to deny a user all permissions for the `exampleResource` resource type. If `example.googleapis.com` adds a new permission for the `exampleResource` resource type, such as `example.googleapis.com/exampleResource.newPermission` , the user will automatically be denied the new permission.

You can only use wildcards in supported permission groups. Using wildcards in other permission names in deny rules is not supported.

## Create Unified Access Policies

You can create UAPs in a project, folder, or organization. The resource that you create the UAP in becomes the parent of the UAP. However, the UAP doesn't have any effect until you [apply the UAP](https://docs.cloud.google.com/iam/docs/unified-access-policies#apply-unified-access-policies) .

The UAP's parent appears in the UAP's name. Policy names have the format `RESOURCE_TYPE `` / `` RESOURCE_ID `` /locations/global/accessPolicies/ `` POLICY_ID` , where the placeholders represent the following:

- `RESOURCE_TYPE` : The type of the resource where the UAP was created. This value is either `projects` , `folders` , or `organizations` .
- `RESOURCE_ID` : The ID of the resource where the UAP was created.
- `POLICY_ID` : The alphanumeric ID of the UAP.

For example, if you create a UAP `example-policy` in the project `example-project` , then that UAP's parent resource is `example-project` and the UAP's name is `projects/example-project/locations/global/accessPolicies/example-policy` .

### Where to create Unified Access Policies

A UAP's parent doesn't affect the resources that you can apply the UAP to. However, it does affect who has permission to view and edit the UAP. To help ensure that the appropriate users have permission to view and edit the appropriate UAPs, we recommend choosing a parent resource that best reflects the scope of the UAP.

For example, if you want to apply a UAP to your organization, we recommend creating the UAP in the organization.

## Apply policies to resources

To apply a UAP, you create a *binding* . Each binding specifies a UAP and a resource to bind the UAP to. After you create the binding, the rules in the UAP become effective for that resource, as well as any of that resource's [descendants](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .

For example, imagine that you have a UAP, `compute-access-management` . This UAP grants the Compute Editor role ( `roles/compute.editor` ) to the group `compute-users@example.com` and denies the `compute.googleapis.com/instances.*` permissions to all users except `compute-users@example.com` .

Without any bindings, this UAP has no effect.

You want this UAP to apply for all resources in your organization `example.com` , so you create a binding that attaches the `compute-access-management` UAP to `example.com` . After you create the binding, the UAP has the following effects:

- Members of `compute-users@example.com` can use the permissions in the Compute Editor role to access resources in `example.com` .
- All users that are not members of `compute-users@example.com` are prevented from using instance-related permissions to access resources in `example.com` .

### Supported resources

The following table lists the resources that you can bind UAPs to. Each row contains the following:

- The type of resource
- The format of IDs for that resource
- The Resource Manager resource (project, folder, or organization) that parents bindings for that type of resource

| Resource                                                                                                                                                   | Resource ID                                                                                                               | Bindings' parent resource        |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| [Resource Manager projects](https://docs.cloud.google.com/resource-manager/reference/rest/v3/projects)                                                     | `//cloudresourcemanager.googleapis.com/projects/ `` PROJECT_ID`                                                           | The project in the binding       |
| [Resource Manager folders](https://docs.cloud.google.com/resource-manager/reference/rest/v3/folders)                                                       | `//cloudresourcemanager.googleapis.com/folders/ `` FOLDER_ID`                                                             | The folder in the binding        |
| [Resource Manager organizations](https://docs.cloud.google.com/resource-manager/reference/rest/v3/organizations)                                           | `//cloudresourcemanager.googleapis.com/organizations/ `` ORG_ID`                                                          | The organization in the binding  |
| [Agent Registry AI applications](https://docs.cloud.google.com/agent-registry/reference/rest/v1/projects.locations.aiApplications)                         | `//agentregistry.googleapis.com/projects/ `` PROJECT_ID `` /locations/ `` LOCATION `` /aiApplications/ `` APPLICATION_ID` | The application's parent project |
| [Network Services API agent gateways](https://docs.cloud.google.com/service-mesh/docs/reference/network-services/rest/v1/projects.locations.agentGateways) | `//networkservices.googleapis.com/projects/ `` PROJECT_ID `` /locations/ `` LOCATION `` /agentGateways/ `` GATEWAY_ID`    | The gateway's parent project     |

### Disable binding creation

If you want to disable the creation of bindings in your organization, then you can enforce the [`iam.managed.disableAccessPolicyBinding` organization policy constraint](https://docs.cloud.google.com/organization-policy/reference/org-policy-constraints#constraints/iam.managed.disableAccessPolicyBinding) in your organization. This constraint prevents principals in your organization from creating bindings for UAPs.

To learn how to enable or disable this constraint, see [Using managed constraints in an organization policy](https://docs.cloud.google.com/organization-policy/create-organization-policies#managed-constraints) .

### Policy inheritance

If you bind a UAP to a project, folder, or organization, that UAP is inherited through the [resource hierarchy](https://docs.cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy) .

The resource hierarchy consists of the organization (root) at the top, followed by folders (optional) for grouping, and then projects, which contain service-specific resources like Compute Engine virtual machines and Cloud Storage buckets.

In this hierarchy, projects, folders, and organizations are *parent resources* . In other words, they're resources that contain other resources:

- Projects contain service-specific resources.
- Folders contain other folders, projects, and the projects' resources.
- Organizations contain folders, projects, and the projects' resources.

The resources that a parent resource contains are that resource's *descendants* .

When you bind a UAP to a parent resource, that UAP applies to the parent resource *and* to all of that resource's descendants. In other words, the UAP is *inherited* by the resource's descendants.

Policy inheritance lets you apply policies to large sets of resources with a single binding. For example, imagine you create a UAP that gives `taylor@example.com` the Compute Engine Admin role ( `roles/compute.admin` ). The UAP also denies `noam@example.com` the `compute.googleapis.com/instances.delete` permission.

You want this UAP to be effective for all resources in your organization, `example.com` . To accomplish this, you bind this UAP to your organization resource. After you bind the UAP to the organization, the UAP is inherited through all resources in that organization.

Binding the UAP to the organization has the following effects:

- `taylor@example.com` can use the permissions in the Compute Engine Admin role to access any resource in `example.com` .
- `noam@example.com` can't use the `compute.googleapis.com/instances.delete` permission on any resource in `example.com` , even if a UAP on a descendant resource grants them access.

If you want a UAP to apply to fewer resources, then you can bind the UAP to a lower level of the resource hierarchy—for example, to a project or a supported service-specific resource.

### Cross-organization bindings

You can't create a *cross-organization binding* for a UAP. A cross-organization binding is a binding that binds a UAP in one organization to a resource in another organization.

IAM periodically deletes any existing cross-organization bindings. Cross-organization bindings can occur when you [move a project](https://docs.cloud.google.com/resource-manager/docs/project-migration) from one organization to another. For example, consider the following situation:

- You have a project, `example-project` , in the organization `example.com` .
- You create a UAP in the project `example-project` and bind it to `example-project` .
- You move `example-project` from `example.com` to `cymbalgroup.com` .

In this situation, moving the project creates a cross-organization binding. This is because the UAP in `example.com` is bound to a resource in `cymbalgroup.com` . If you don't delete the binding manually, IAM eventually deletes it automatically. Deleting this binding helps ensure that `cymbalgroup.com` administrators have access to all UAPs bound to resources in their organization.

### Bindings for deleted Unified Access Policies

Typically, you must delete bindings for a UAP before deleting the UAP. Attempts to delete a UAP that has existing bindings result in an error.

However, if you want to delete a UAP without deleting existing bindings, you can forcefully delete the UAP.

Forcefully deleting a UAP removes it from all of the resources that it's bound to. Any bindings that reference the UAP will eventually be deleted. However, until they are deleted, the bindings still count against the limit of the number of bindings that can refer to a single resource.

## Conditions in Unified Access Policies

IAM Conditions let you define and enforce conditional, attribute-based access control for Google Cloud resources. In UAPs, you can add conditions to individual rules to control when that rule applies. You can't add conditions to UAP bindings.

Conditions are composed of a title, description, and a boolean expression. If the expression evaluates to `true` for the request, then the rule applies for the request. If it evaluates to `false` , then the rule doesn't apply for the request.

Different services offer different attributes and functions that you can use to write condition expressions. When you add conditions to a rule, you always preface the condition with the name of the service whose attributes and functions you're using. You can add multiple conditions to a rule, but a single condition can't mix attributes from different services.

For example, if you're adding a condition that uses an attribute provided by IAM, you preface the condition with `iam.googleapis.com` :

```
"conditions": {
  "iam.googleapis.com": {
    "title": "CONDITION_TITLE",
    "description": "CONDITION_DESCRIPTION",
    "expression": "CONDITION_EXPRESSION"
  }
}
```

To learn how to create UAP rules with conditions, see [Create and apply UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply) .

### Applicable permissions for condition attributes

Some service-specific attributes only apply for requests involving certain permissions. For example, the `eventarc.googleapis.com` attribute `message.id` only applies for requests that require the `eventarc.googleapis.com/messageBuses.publish` permission.

You can only use these attributes in rules that include the applicable permission. If you try to use the attribute in a rule without the applicable permission, then the UAP creation will fail.

### Supported condition attributes

The following attributes are supported in UAP rules:

| Service                                                                                          | Attribute     | Applicable permissions                         | More information                                                                                                                                                           |
|--------------------------------------------------------------------------------------------------|---------------|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `iam.googleapis.com` ( [Preview](https://cloud.google.com/products#product-launch-stages) )      | Resource tags | Any                                            | [Resource tags attribute](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#resource-tags)                                                             |
| `eventarc.googleapis.com` ( [Preview](https://cloud.google.com/products#product-launch-stages) ) | Messages      | `eventarc.googleapis.com/messageBuses.publish` | [Eventarc message attributes](https://docs.cloud.google.com/eventarc/advanced/docs/receive-events/use-cel#attributes)                                                      |
| `iap.googleapis.com` ( [GA](https://cloud.google.com/products#product-launch-stages) )           | Destinations  | `iap.googleapis.com/resources.egressViaIAP`    | [Identity-Aware Proxy destinations attributes](https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern/policies/configure-iam-policies-uap#example-policies) |

## What's next

- Learn how to [create and apply UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply) .
- Learn how to [view existing UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-view) .
