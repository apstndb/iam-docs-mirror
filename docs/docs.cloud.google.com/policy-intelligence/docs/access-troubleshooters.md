---
name: documents/docs.cloud.google.com/policy-intelligence/docs/access-troubleshooters
uri: https://docs.cloud.google.com/policy-intelligence/docs/access-troubleshooters
title: Access-related troubleshooters
description: Overview of the access-related troubleshooters that Policy Intelligence provides.
data_source: docs.cloud.google.com
---

To help you understand and remedy access issues, Policy Intelligence offers the following troubleshooters:

  - Policy Troubleshooter
  - VPC Service Controls violation analyzer
  - Policy Troubleshooter for Chrome Enterprise Premium

<span id="iam-allow-troubleshooter"></span>

## Policy Troubleshooter

> **Preview — Troubleshooting principal access boundary policies**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Policy Troubleshooter helps you understand whether a principal can access a resource. Given a principal, a resource, and a permission, Policy Troubleshooter examines the allow policies, deny policies, and principal access boundary (PAB) policies that impact the principal's access. Then, it tells you whether, based on those policies, the principal can use the specified permission to access the resource. It also lists the relevant policies and explains how they affect the principal's access.

To learn how to use Policy Troubleshooter to troubleshoot IAM allow policies, deny policies, and principal access boundary (PAB) policies, see [Troubleshooting access](https://docs.cloud.google.com/policy-intelligence/docs/troubleshoot-access) .

To learn about the different types of policies that IAM supports, see [Policy types](https://docs.cloud.google.com/iam/docs/policy-types) .

## VPC Service Controls violation analyzer

The VPC Service Controls violation analyzer helps you troubleshoot access issues caused by improperly configured [VPC Service Controls service perimeters](https://docs.cloud.google.com/vpc-service-controls/docs/overview) . Given a unique denial ID, the VPC Service Controls violation analyzer investigates the denial and reports why a service perimeter denied a request.

To learn how to use the VPC Service Controls violation analyzer, see [Diagnose an access denial using unique ID in violation analyzer](https://docs.cloud.google.com/vpc-service-controls/docs/troubleshooter) .

## Policy Troubleshooter for Chrome Enterprise Premium

The Policy Troubleshooter for Chrome Enterprise Premium helps organizations using [Chrome Enterprise Premium](https://docs.cloud.google.com/chrome-enterprise-premium/docs/overview) understand why an end user is denied access. Policy Troubleshooter evaluates both your policies and the end user's context—for example, their location or device details—to determine why access was denied.

The Chrome Enterprise Premium Policy Troubleshooter is a premium feature and requires a Chrome Enterprise Premium license.

To learn how to use Policy Troubleshooter to troubleshoot Chrome Enterprise Premium, see [Troubleshooting by using the Policy Troubleshooter for Chrome Enterprise Premium](https://docs.cloud.google.com/chrome-enterprise-premium/docs/troubleshooter) .
