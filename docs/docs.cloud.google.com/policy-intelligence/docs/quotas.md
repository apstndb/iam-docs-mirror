---
name: documents/docs.cloud.google.com/policy-intelligence/docs/quotas
uri: https://docs.cloud.google.com/policy-intelligence/docs/quotas
title: Quotas and limits
description: Review quotas and limits for Policy Intelligence.
data_source: docs.cloud.google.com
---

This document lists the quotas and system limits that apply to Policy Intelligence.

  - *Quotas* have default values, but you can typically request adjustments.
  - *System limits* are fixed values that can't be changed.

Google Cloud uses quotas to help ensure fairness and reduce spikes in resource use and availability. A quota restricts how much of a Google Cloud resource your Google Cloud project can use. Quotas apply to a range of resource types, including hardware, software, and network components. For example, quotas can restrict the number of API calls to a service, the number of load balancers used concurrently by your project, or the number of projects that you can create. Quotas protect the community of Google Cloud users by preventing the overloading of services. Quotas also help you to manage your own Google Cloud resources.

The Cloud Quotas system does the following:

  - Monitors your consumption of Google Cloud products and services
  - Restricts your consumption of those resources
  - Provides a way to [request changes to the quota value](https://docs.cloud.google.com/docs/quotas/help/request_increase) and [automate quota adjustments](https://docs.cloud.google.com/docs/quotas/quota-adjuster)

In most cases, when you attempt to consume more of a resource than its quota allows, the system blocks access to the resource, and the task that you're trying to perform fails.

Quotas generally apply at the Google Cloud project level. Your use of a resource in one project doesn't affect your available quota in another project. Within a Google Cloud project, quotas are shared across all applications and IP addresses.

For more information, see the [Cloud Quotas overview](https://docs.cloud.google.com/docs/quotas/overview) .

To adjust most quotas, use the Google Cloud console. For more information, see [Request a quota adjustment](https://docs.cloud.google.com/docs/quotas/help/request_increase) .

There are also *system limits* on Policy Intelligence resources. System limits can't be changed.

## Policy Analyzer quotas

Cloud Asset Inventory enforces the rate of incoming requests based on the consumer project. Default quotas are listed below:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Quota</th>
<th>Value</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code dir="ltr" translate="no">AnalyzeIamPolicy</code></td>
<td><p>100 per minute per consumer project</p>
<p>1,000 per day per consumer project</p></td>
</tr>
<tr class="even">
<td><code dir="ltr" translate="no">AnalyzeIamPolicyLongrunning</code></td>
<td><p>100 per minute per consumer project</p>
<p>1,000 per day per consumer project</p></td>
</tr>
</tbody>
</table>

You can use the [APIs and services quotas dashboard](https://console.cloud.google.com/projectselector/apis/api/cloudasset.googleapis.com/quotas) to view current quotas and usage for your project.

Policy Analyzer also limits the number of queries that you can make if you don't have an [organization-level activation of the Premium or Enterprise tier of Security Command Center](https://docs.cloud.google.com/security-command-center/pricing#security-command-center-pricing) .

| Quota                                                  | Value |
| ------------------------------------------------------ | ----- |
| Analysis queries per organization per day <sup>1</sup> | 20    |

<sup>1</sup> This quota only applies for organizations that don't have an organization-level activation of the Premium or Enterprise tier of Security Command Center.

For more details, see [Billing questions](https://docs.cloud.google.com/policy-intelligence/docs/billing-questions) .

## Policy Analyzer limits

Policy Analyzer limits group expansion within the group memberships and resource expansion within the resource hierarchy to the following values.

| Limit                         | Value                |
| ----------------------------- | -------------------- |
| `AnalyzeIamPolicy`            | 1,000 per group      |
| `AnalyzeIamPolicy`            | 1,000 per resource   |
| `AnalyzeIamPolicyLongrunning` | 100,000 per resource |

## Recommendations limits

The following limits apply to IAM recommendations:

| Limit                                                                                                                                    | Value |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| Number of [recommendations](https://docs.cloud.google.com/iam/docs/recommender-overview) per day to add a custom role to an organization | 15    |
| Number of [recommendations](https://docs.cloud.google.com/iam/docs/recommender-overview) per day to add a custom role to a project       | 5     |
| Number of custom roles in an organization that prevents recommendations to create new custom roles <sup>1</sup>                          | 100   |
| Number of custom roles in a project that prevents recommendations to create new custom roles <sup>2</sup>                                | 25    |

<sup>1</sup> If your organization contains more than 100 custom roles, you will continue to receive role recommendations from Recommender. However, none of the recommendations will suggest that you [create a new custom role](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview#custom-roles) .

<sup>2</sup> If your project contains more than 25 custom roles, you will continue to receive role recommendations from Recommender. However, none of the recommendations for that project will suggest that you [create a new custom role](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview#custom-roles) .
