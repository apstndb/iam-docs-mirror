---
name: documents/docs.cloud.google.com/iam/docs/pam-best-practices
uri: https://docs.cloud.google.com/iam/docs/pam-best-practices
title: Best practices for Privileged Access Manager
description: Learn best practices for using Privileged Access Manager
data_source: docs.cloud.google.com
---

This document describes best practices for using Privileged Access Manager to control just-in-time temporary privilege elevation with Identity and Access Management (IAM).

## Manage IAM policy size

Privileged Access Manager grants time-bound access by adding a [conditional IAM role binding](https://docs.cloud.google.com/iam/docs/managing-conditional-role-bindings) to a resource's policy. Each active Privileged Access Manager grant consumes space and counts toward your standard IAM policy size limits. For more information, see [IAM quotas and limits](https://docs.cloud.google.com/iam/quotas#limits) .

If a resource's IAM policy reaches its maximum size, new Privileged Access Manager grant requests for that resource fail until you free space in the policy.

If you are approaching or have reached the IAM policy size limit, then you can do the following:

  - [Revoke existing grants](https://docs.cloud.google.com/iam/docs/pam-best-practices#revoke-grants)
  - [Optimize your Privileged Access Manager setup](https://docs.cloud.google.com/iam/docs/pam-best-practices#optimize-setup)

### Revoke existing grants

Revoke active Privileged Access Manager grants that are no longer needed to remove their corresponding IAM binding from the policy and free up space. For instructions, see [Revoke grants](https://docs.cloud.google.com/iam/docs/pam-revoke-grants) .

### Optimize your Privileged Access Manager setup

To optimize your Privileged Access Manager entitlements and reduce the space each grant consumes in an IAM policy, do the following:

1.  Consolidate roles within entitlements:
    
    1.  Consolidate multiple predefined roles into fewer custom roles to reduce the space consumed.
    2.  Use a single broader role—for example, `roles/reader` instead of multiple service-specific reader roles.
    3.  Remove redundant roles and overlapping permissions. For example, if all permissions in `Role A` are also in `Role B` , remove `Role A` from the entitlement.

2.  Reduce the number and complexity of IAM conditions:
    
    1.  If you use a list of multiple resource names in `OR` conditions, consider using a [tag condition](https://docs.cloud.google.com/iam/docs/tags-access-control) instead.
    2.  For grants using scope customization, don't use resource-name-based filters.

3.  Grant access at the minimum required scope.
    
    Following the principle of least privilege, set up Privileged Access Manager entitlements to grant access at the narrowest possible scope. For example, if a user only needs access to a single Cloud Storage bucket in a project, then grant access to that bucket instead of the entire project, folder, or organization.

## What's next

  - [Learn more about IAM quotas and limits](https://docs.cloud.google.com/iam/quotas#limits) .
  - [Learn more about custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) .
  - [Learn how to use tags for access control](https://docs.cloud.google.com/iam/docs/tags-access-control) .
