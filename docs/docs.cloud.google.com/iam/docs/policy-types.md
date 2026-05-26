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
  - Principal access boundary (PAB) policies
  - Access policies

The following table summarizes the differences between these policy types:

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th>Policy</th>
<th>Policy function</th>
<th>API used to manage the policy</th>
<th>Relationship between policies and targets</th>
<th>Method of attaching policies to target</th>
<th>Policy's parent resource</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Allow policies</td>
<td>Grant principals access to resources</td>
<td>The API for the resource that you want to manage allow policies for</td>
<td><p>One-to-one relationship</p>
<p>Each allow policy is attached to one resource; each resource can only have one allow policy</p></td>
<td>Specify resource when creating the policy</td>
<td>Same as the resource that the allow policy is attached to</td>
</tr>
<tr class="even">
<td>Deny policies</td>
<td>Ensure that principals can't use specific permissions</td>
<td>The <a href="https://docs.cloud.google.com/iam/docs/reference/libraries#iam-v2">IAM v2 API</a></td>
<td><p>One-to-many relationship</p>
<p>Each deny policy is attached to one resource; each resource can have up to 500 deny policies</p></td>
<td>Specify resource when creating the deny policy</td>
<td>Same as the resource that the deny policy is attached to</td>
</tr>
<tr class="odd">
<td>PAB policies</td>
<td>Restrict the resources a principal is eligible to access</td>
<td>The <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies">IAM v3 API</a></td>
<td><p>Many-to-many relationship</p>
<p>Each PAB policy can be attached to an unlimited number of principal sets; each principal set can have up to 10 PAB policies bound to it</p></td>
<td>Create a policy binding that attaches the PAB policy to a principal set</td>
<td>The organization</td>
</tr>
<tr class="even">
<td>Access policies</td>
<td>Grant or deny principals access to resources for supported services</td>
<td>The <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies">IAM v3 API</a></td>
<td><p>Many-to-many relationship</p>
<p>Each access policy can be attached to up to 5 resources; each resource can have up to 5 access policies bound to it</p></td>
<td>Create an access policy binding that attaches the access policy to the resource</td>
<td>The project, folder, or organization where the access policy is created</td>
</tr>
</tbody>
</table>

The following sections provide details about each policy type.

## Policies to grant access to principals

To grant principals access to resources, use one of the following policies:

  - Use allow policies to grant access to any resource type.
  - Use access policies to grant access to Eventarc resources.

*Allow policies* let you grant access to resources in Google Cloud. Allow policies are made up of role bindings and metadata. Role bindings specify which principals should have a certain role on the resource.

Allow policies are always attached to a single resource. After you attach an allow policy to a resource, the policy is [inherited](https://docs.cloud.google.com/iam/docs/resource-hierarchy-access-control) by that resource's descendants.

To create and apply an allow policy, you identify a resource that [accepts allow policies](https://docs.cloud.google.com/iam/docs/resource-types-with-policies) , then use that resource's `setIamPolicy` method to create the allow policy. All principals in the allow policy are granted the specified roles on the resource and all of the resource's descendants. Each resource can have only one allow policy attached to it.

For more information about allow policies, see [Understanding allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) .

*Access policies* let you control access to Eventarc resources. Access policies can both allow and deny access to resources. To create and apply an access policy, you create an access policy, and then create a policy binding to connect that policy to a project with Eventarc resources.

Each policy binding binds one access policy to one resource. An access policy can be bound to up to 5 resources. Each resource can have up to 5 access policies bound to it. When an access policy is deleted, all of the policy bindings related to that policy are also deleted.

To learn more about using access policies to control access to Eventarc resources, see the [Eventarc documentation](https://docs.cloud.google.com/eventarc/advanced/docs/control-publishing-access) .

## Policies to deny access to principals

To deny principals access to resources, use one of the following:

  - Use deny policies to deny access for any resource type.
  - Use access policies to deny access for Eventarc resources.

*Deny policies* , like allow policies, are always attached to a single resource. You can attach a deny policy to a project, folder, or organization. This project, folder, or organization also acts as the policy's parent in the resource hierarchy. After you attach a deny policy to a resource, the policy is [inherited](https://docs.cloud.google.com/iam/docs/deny-overview#inheritance) by that resource's descendants.

To create and apply deny policies, you use the IAM v2 API. When you create a deny policy, you specify the resource that the deny policy is attached to. All principals in the deny policy are prevented from using the specified permissions to access that resource and any of that resource's descendants. Each resource can have up to 500 deny policies attached to it.

For more information about deny policies, see [Deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) .

*Access policies* let you control access to Eventarc resources. Access policies can both allow and deny access to resources. To create and apply an access policy, you create an access policy, and then create a policy binding to connect that policy to a project with Eventarc resources.

Each policy binding binds one access policy to one resource. An access policy can be bound to up to 5 resources. Each resource can have up to 5 access policies bound to it. When an access policy is deleted, all of the policy bindings related to that policy are also deleted.

To learn more about using access policies to control access to Eventarc resources, see the [Eventarc documentation](https://docs.cloud.google.com/eventarc/advanced/docs/control-publishing-access) .

## Policies to restrict the resources a principal can access

To restrict the resources that a principal is eligible to access, use a principal access boundary policy. Principal access boundary policies are available in the [IAM v3 API](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies) .

To create and apply a principal access boundary policy, you create a principal access boundary policy, and then create a policy binding to connect that policy to a principal set.

Principal access boundary policies are always children of your organization. Policy bindings for principal access boundary policies are children of the project, folder, or organization that is closest to the principal set referenced in the policy binding.

Each policy binding binds one principal access boundary policy to one principal set. A principal access boundary policy can be bound to any number of principal sets. Each principal set can have up to 10 principal access boundary policies bound to it. When a principal access boundary policy is deleted, all of the policy bindings related to that policy are also deleted.

For more information about principal access boundary policies, see [Principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .

## Policy evaluation

When a principal tries to access a resource, IAM evaluates all relevant allow, deny, and principal access boundary policies to see if the principal is allowed to access the resource. If any of these policies indicates that the principal shouldn't be able to access the resource, then IAM prevents access.

In reality, IAM evaluates all policy types simultaneously, then compiles the results to determine whether the principal can access the resource. However, it can be helpful to think of this policy evaluation taking place in the following stages:

1.  IAM checks all relevant principal access boundary policies to see if the principal is eligible to access the resource. A principal access boundary policy is relevant if the following are true:
    
      - The policy is bound to a principal set that includes the principal
      - The principal access boundary policy blocks the permission that the principal is trying to use. The permissions that a principal access boundary policy blocks depends on the principal access boundary policy version. You specify the policy version when you create the principal access boundary policy. For more information, see [Principal access boundary policy versions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#versions) .
    
    After checking the relevant principal access boundary policies, IAM does one of the following:
    
      - If the relevant principal access boundary policies don't include the resource that the principal is trying to access, or if IAM [can't evaluate](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#fail-closed) the relevant principal access boundary policies, then IAM prevents them from accessing the resource.
      - If the relevant principal access boundary policies include the resource that the principal is trying to access, then IAM continues to the next step.
      - If there are no relevant principal access boundary policies, then IAM continues to the next step.

2.  IAM checks all relevant deny policies to see if the principal has been denied the permission. Relevant deny policies are the deny policies attached to the resource, as well as any [inherited deny policies](https://docs.cloud.google.com/iam/docs/deny-overview#inheritance) .
    
    > For Eventarc resources, IAM also evaluates any access policies with the `DENY` action. If IAM fails to evaluate access policies, then it ignores them and continues with the evaluation.
    
      - If *any* of these deny policies prevent the principal from using a required permission, then IAM prevents them from accessing the resource.
      - If no deny policies prevent the principal from using a required permission, then IAM continues to the next step.

3.  IAM checks all relevant allow policies to see if the principal has the required permissions. Relevant allow policies are the allow policies attached to the resource, as well as any [inherited allow policies](https://docs.cloud.google.com/iam/docs/resource-hierarchy-access-control) .
    
    > For Eventarc resources, IAM also evaluates any access policies with the `ALLOW` action. If IAM fails to evaluate access policies, then it ignores them and continues with the evaluation.
    
      - If the principal does not have the required permissions, then IAM prevents them from accessing the resource.
      - If the principal has the required permissions, then IAM lets them access the resource.

The following diagram shows this policy evaluation flow:

![The IAM policy evaluation flow](https://docs.cloud.google.com/static/iam/img/iam-policy-evaluation.svg)

![The IAM policy evaluation flow](https://docs.cloud.google.com/static/iam/img/iam-policy-evaluation.svg)

## What's next

  - Learn more about [allow policies](https://docs.cloud.google.com/iam/docs/allow-policies) .
  - Learn more about [deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) .
  - Learn more about [principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .
