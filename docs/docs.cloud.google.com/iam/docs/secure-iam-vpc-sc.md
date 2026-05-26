---
name: documents/docs.cloud.google.com/iam/docs/secure-iam-vpc-sc
uri: https://docs.cloud.google.com/iam/docs/secure-iam-vpc-sc
title: Help secure IAM with VPC Service Controls
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

With VPC Service Controls, you can create *perimeters* , which are boundaries around your Google Cloud resources. You can then define security policies that help prevent access to supported services from outside of the perimeter. For more information about VPC Service Controls, see the [VPC Service Controls overview](https://docs.cloud.google.com/vpc-service-controls/docs/overview) .

You can use VPC Service Controls to help secure the following IAM-related APIs:

  - Identity and Access Management API
  - Security Token Service API
  - Privileged Access Manager API

## Help secure the Identity and Access Management API

> **Beta — Using VPC Service Controls with IAM**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

You can help secure the following Identity and Access Management (IAM) resources by using VPC Service Controls:

  - Custom roles
  - Service account keys
  - Service accounts
  - Workload identity pools
  - Deny policies
  - Policy bindings for principal access boundary policies

### How VPC Service Controls works with IAM

When you restrict IAM with a perimeter, only actions that use the IAM API are restricted. These actions include the following:

  - Managing custom IAM roles
  - Managing workload identity pools
  - Managing service accounts and keys
  - Managing deny policies
  - Managing policy bindings for principal access boundary policies

The perimeter *doesn't* restrict actions related to workforce pools and principal access boundary policies because those resources are created at the organization level.

The perimeter also *doesn't* restrict allow policy management for resources owned by other services, like Resource Manager projects, folders, and organizations or Compute Engine virtual machine instances. To restrict allow policy management for these resources, create a perimeter that restricts the service that owns the resources. For a list of resources that accept allow policies and the services that own them, see [Resource types that accept allow policies](https://docs.cloud.google.com/iam/docs/resource-types-with-policies) .

Additionally, the perimeter *doesn't* restrict actions that use other APIs, including the following:

  - IAM Policy Simulator API
  - IAM Policy Troubleshooter API

<!-- end list -->

  - Security Token Service API
  - Service Account Credentials API (including the legacy `signBlob` and `signJwt` methods in the IAM API)

For more details about how VPC Service Controls works with IAM, see the [IAM entry in the VPC Service Controls supported products table](https://docs.cloud.google.com/vpc-service-controls/docs/supported-products#table_iam) .

## Help secure the Security Token Service API

You can help secure token exchanges by using VPC Service Controls.

> **Note:** VPC Service Controls only restricts token exchanges if the [audience](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token#body.request_body.FIELDS.audience) in the request is a project-level resource. For example, it does not restrict requests for [downscoped tokens](https://docs.cloud.google.com/iam/docs/downscoping-short-lived-credentials) , because those requests have no audience.

When you restrict the Security Token Service API with a perimeter, only the following entities can exchange tokens:

  - Resources within the same perimeter as the workload identity pool you're using to exchange the token
  - Principals with the attributes defined in the service perimeter

When you create an [ingress or egress rule](https://docs.cloud.google.com/vpc-service-controls/docs/ingress-egress-rules) to allow token exchanges, you must set the identity type to `ANY_IDENTITY` because the [token](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/TopLevel/token) method has no authorization.

For more details about how VPC Service Controls works with IAM, see the [Security Token Service entry in the VPC Service Controls supported products table](https://docs.cloud.google.com/vpc-service-controls/docs/supported-products#table_sts) .

## Help secure the Privileged Access Manager API

> **Preview — Using VPC Service Controls with Privileged Access Manager**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

You can help secure your Privileged Access Manager resources by using VPC Service Controls. Privileged Access Manager resources include the following:

  - Entitlements
  - Grants

VPC Service Controls doesn't support adding folder-level or organization-level resources into a service perimeter. You can't use a perimeter to protect folder-level or organization-level Privileged Access Manager resources. VPC Service Controls protects project-level Privileged Access Manager resources.

For more details about how VPC Service Controls works with Privileged Access Manager, see the [Privileged Access Manager entry in the VPC Service Controls supported products table](https://docs.cloud.google.com/vpc-service-controls/docs/supported-products#table_pam) .

## What's next

  - Learn how to [create a service perimeter](https://docs.cloud.google.com/vpc-service-controls/docs/create-service-perimeters) .
