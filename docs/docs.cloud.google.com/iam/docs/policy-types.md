---
name: documents/docs.cloud.google.com/iam/docs/policy-types
uri: https://docs.cloud.google.com/iam/docs/policy-types
title: IAM policy types
description: Understand the different types of policies in {{dynamic_data.site_values.cloud_name_short}} IAM. Learn how to use allow, deny, and principal access boundary policies to control resource access.
data_source: docs.cloud.google.com
---

Identity and Access Management (IAM) offers several types of policies to help you control which resources principals can access. This page helps you understand the differences between how you use and manage these policy types.

## Types of IAM policies in Google Cloud

IAM offers the following types of policies:

- Allow policies
- Deny policies
- Principal Access Boundary (PAB) policies
- Unified Access Policies (UAPs)

The following table summarizes the differences between these policy types:

| Policy         | Policy function                                                     | API used to manage the policy                                                                                                      | Relationship between policies and targets                                                                                                                         | Method of attaching policies to target                                  | Policy's parent resource                                      |
|----------------|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|---------------------------------------------------------------|
| Allow policies | Grant principals access to resources                                | The API for the resource that you want to manage allow policies for                                                                | One-to-one relationship Each allow policy is attached to one resource; each resource can only have one allow policy                                               | Specify resource when creating the policy                               | Same as the resource that the allow policy is attached to     |
| Deny policies  | Ensure that principals can't use specific permissions               | The [IAM v2 API](https://docs.cloud.google.com/iam/docs/reference/libraries#iam-v2)                                                | One-to-many relationship Each deny policy is attached to one resource; each resource can have up to 500 deny policies                                             | Specify resource when creating the deny policy                          | Same as the resource that the deny policy is attached to      |
| PAB policies   | Restrict the resources a principal is eligible to access            | The [IAM v3 API](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies) | Many-to-many relationship Each PAB policy can be attached to an unlimited number of principal sets; each principal set can have up to 10 PAB policies bound to it | Create a policy binding that attaches the PAB policy to a principal set | The organization                                              |
| UAPs           | Grant or deny principals access to resources for supported services | The [IAM v3 API](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies)              | Many-to-many relationship Each UAP can be attached to up to 5 resources; each resource can have up to 5 UAPs bound to it                                          | Create a UAP binding that attaches the UAP to the resource              | The project, folder, or organization where the UAP is created |

The following sections provide details about each policy type.

## Policies to grant access to principals

To grant principals access to resources, use one of the following policies:

- Use allow policies to grant access to any resource type.
- Use UAPs to grant and deny access in the same policy.

### Allow policies

*Allow policies* let you grant access to resources in Google Cloud. Allow policies are made up of role bindings and metadata. Role bindings specify which principals are granted a certain role on the resource.

Allow policies are always attached to a single resource. After you attach an allow policy to a resource, the policy is [inherited](https://docs.cloud.google.com/iam/docs/resource-hierarchy-access-control) by that resource's descendants.

To create and apply an allow policy, you identify a resource that [accepts allow policies](https://docs.cloud.google.com/iam/docs/resource-types-with-policies) , then use that resource's `setIamPolicy` method to create the allow policy. All principals in the allow policy are granted the specified roles on the resource and all of the resource's descendants. Each resource can have only one allow policy attached to it.

For more information about allow policies, see [Understanding allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) .

### Unified Access Policies

*Unified Access Policies (UAPs)* let you allow and deny access to resources using the same policy. To grant access with a UAP, you first create a UAP with an allow rule. This rule specifies the principals that you want to grant access to and the roles and permissions that you want to grant them. After you create the policy, you create a binding to apply that policy to a supported resource, such as a project. The principals in the allow rule are then granted those roles and permissions on the resource.

Each policy binding binds one UAP to one resource. A UAP can be bound to up to 5 resources. Each resource can have up to 5 UAPs bound to it.

To learn more about using UAPs to grant access, see [UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies) .

## Policies to deny access to principals

To deny principals access to resources, use one of the following:

- Use deny policies to deny access for any resource type.
- Use UAPs to deny and grant access in the same policy.

### Deny policies

*Deny policies* , like allow policies, are always attached to a single resource. You can attach a deny policy to a project, folder, or organization. This project, folder, or organization also acts as the policy's parent in the resource hierarchy. After you attach a deny policy to a resource, the policy is [inherited](https://docs.cloud.google.com/iam/docs/deny-overview#inheritance) by that resource's descendants.

To create and apply deny policies, you use the IAM v2 API. When you create a deny policy, you specify the resource that the deny policy is attached to. All principals in the deny policy are prevented from using the specified permissions to access that resource and any of that resource's descendants. Each resource can have up to 500 deny policies attached to it.

For more information about deny policies, see [Deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) .

### Unified Access Policies

*Unified Access Policies (UAPs)* let you allow and deny access to resources using the same policy. To deny access with a UAP, you first create a UAP with a deny rule. This rule specifies the principals that you want to deny access to and the permissions that you want to deny them. After you create the policy, you create a policy binding to apply that policy to a supported resource, such as a project. The principals in the deny rule are then prevented from using those permissions to access the resource.

Each policy binding binds one UAP to one resource. A UAP can be bound to up to 5 resources. Each resource can have up to 5 UAPs bound to it.

To learn more about using UAPs to deny access, see [UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies) .

## Policies to restrict the resources a principal can access

To restrict the resources that a principal is eligible to access, use a Principal Access Boundary policy. Principal Access Boundary policies are available in the [IAM v3 API](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies) .

To create and apply a Principal Access Boundary policy, you create a Principal Access Boundary policy, and then create a policy binding to apply that policy to a principal set.

Principal Access Boundary policies are always children of your organization. Policy bindings for Principal Access Boundary policies are children of the project, folder, or organization that is closest to the principal set referenced in the policy binding.

Each policy binding binds one Principal Access Boundary policy to one principal set. A Principal Access Boundary policy can be bound to any number of principal sets. Each principal set can have up to 10 Principal Access Boundary policies bound to it. When a Principal Access Boundary policy is deleted, all of the policy bindings related to that policy are also deleted.

For more information about Principal Access Boundary policies, see [Principal Access Boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .

## Policy evaluation

When a principal tries to access a resource, IAM evaluates the relevant IAM-related policies to see if the principal is allowed to access the resource. IAM-related policies include the following:

- Allow policies
- Deny policies
- Principal Access Boundary policies
- UAPs

If any of these policies indicates that the principal shouldn't be able to access the resource, then IAM prevents access.

In reality, IAM evaluates all policy types simultaneously, then compiles the results to determine whether the principal can access the resource. However, it can be helpful to think of this policy evaluation taking place in the following stages:

1.  IAM determines whether the principal is *eligible* to access the resource. To do this, it [evaluates the Principal Access Boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#policy-evaluation) that the principal is subject to.

    - If the principal isn't eligible to access the resource, then IAM prevents them from accessing the resource.
    - If the principal is eligible to access the resource, then IAM continues to the next step.
    - If the principal isn't subject to any Principal Access Boundary policies, then IAM continues to the next step.

2.  IAM determines whether the principal is *denied* access to the resource. To do this, it checks all relevant deny policies and UAP deny rules to see if the principal has been denied the permission.

    Relevant deny policies are the deny policies attached to the resource and any [inherited deny policies](https://docs.cloud.google.com/iam/docs/deny-overview#inheritance) .

    Relevant UAPs are the UAPs bound to the resource and any [inherited UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .

    - If *any* of these deny policies or deny rules prevent the principal from using a required permission, then IAM prevents them from accessing the resource.
    - If no deny policies or deny rules prevent the principal from using a required permission, then IAM continues to the next step.

3.  IAM checks all relevant allow policies to see if the principal has the required permissions. Relevant allow policies are the allow policies attached to the resource and any [inherited allow policies](https://docs.cloud.google.com/iam/docs/resource-hierarchy-access-control) .

    IAM also evaluates any relevant UAPs with the allow effect (allow rules) to see if any of these rules gives the principal the required permissions. Relevant UAPs are the UAPs bound to the resource and any [inherited UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .

    - If the principal does not have the required permissions, then IAM prevents them from accessing the resource.
    - If the principal has the required permissions, then IAM lets them access the resource.

## What's next

- Learn more about [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) .
- Learn more about [deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) .
- Learn more about [Principal Access Boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .
