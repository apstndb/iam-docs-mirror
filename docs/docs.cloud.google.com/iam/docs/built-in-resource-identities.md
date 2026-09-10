---
name: documents/docs.cloud.google.com/iam/docs/built-in-resource-identities
uri: https://docs.cloud.google.com/iam/docs/built-in-resource-identities
title: Built-in identities for resources
description: An overview of built-in resource identities
data_source: docs.cloud.google.com
---

This page describes built-in identities for resources, which let you grant roles to resources in your IAM allow policies.

## Built-in identities

Some resources have built-in identities. These identities let the resources act like [principals](https://docs.cloud.google.com/iam/docs/principals-overview) . As a result, resources with built-in identities can do the following:

  - Be [granted IAM roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) using the [resource's principal identifier](https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities)
  - Access other resources without using [service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents)

For example, consider Parameter Manager parameters, which have built-in identities. Parameters sometimes need access to Secret Manager to function properly. To let a parameter access Secret Manager, you use its identifier to grant it the Secret Manager Secret Accessor role ( `roles/secretmanager.secretAccessor` ). Then, the parameter can access Secret Manager secrets on your behalf.

For a list of resources with built-in identities, see [Resources with built-in identities](https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities) .

You can't use a resource's built-in identity to authenticate customer-managed workloads, like workloads running on Compute Engine instances. If you need to authenticate a workload, use one of the methods described in [Authentication methods at Google](https://docs.cloud.google.com/docs/authentication) .

## Granting roles to resources with built-in identities

If a resource has a built-in identity, you can grant roles to the resource by including the resource's *principal identifier* in your allow policies. To see what format to use for each resource's principal identifier, see [Principal identifiers for single resources](https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities#single-resources) .

IAM also offers identifiers for sets of resources with built-in identities that share certain characteristics, such as type or ancestor. You can use these identifiers in your allow policies to grant the same role to multiple resources. To see what formats are supported, see [Principal identifiers for sets of resources](https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities#resource-sets) .
