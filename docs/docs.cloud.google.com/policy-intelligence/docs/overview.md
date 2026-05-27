---
name: documents/docs.cloud.google.com/policy-intelligence/docs/overview
uri: https://docs.cloud.google.com/policy-intelligence/docs/overview
title: Policy Intelligence overview
description: Overview of all Policy Intelligence tools, which help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

Large organizations often have an extensive set of Google Cloud policies to control resources and manage access. Policy Intelligence tools help you understand and manage your policies to proactively improve your security configuration.

The following sections explain what you can do with Policy Intelligence tools.

## Understand policies and usage

There are several Policy Intelligence tools that help you understand what access your policies allow and how the policies are being used.

### Analyze access

Cloud Asset Inventory provides Policy Analyzer for IAM allow policies, which lets you find out what principals have access to which Google Cloud resources based on your [IAM allow policies](https://docs.cloud.google.com/iam/docs/policies) .

Policy Analyzer helps you answer questions like the following:

  - "Who has any access to this IAM service account?"
  - "What roles and permissions does this user have on this BigQuery dataset?"
  - "Which BigQuery datasets does this user have permission to read?"

By helping you answer these questions, Policy Analyzer lets you effectively administer access. You can also use Policy Analyzer for audit-related and compliance-related tasks.

To learn more about Policy Analyzer for allow policies, see [Policy Analyzer overview](https://docs.cloud.google.com/policy-intelligence/docs/policy-analyzer-overview) .

To learn how to use Policy Analyzer for allow policies, see [Analyzing IAM policies](https://docs.cloud.google.com/asset-inventory/docs/analyzing-iam-policy) .

### Analyze organization policies

> **Preview — Securing the Policy Troubleshooter API with VPC Service Controls**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Policy Intelligence provides Policy Analyzer for Organization Policy, which you can use to create an analysis query to get information on both custom and predefined organization policies.

You can use Policy Analyzer to return a list of organization policies with a particular constraint and the resources to which those policies are attached.

To learn how to use Policy Analyzer for Organization Policy, see [Analyze existing organization policies](https://docs.cloud.google.com/policy-intelligence/docs/analyze-organization-policies) .

### Troubleshoot access issues

To help you understand and remedy access issues, Policy Intelligence offers the following troubleshooters:

  - Policy Troubleshooter for Identity and Access Management
  - VPC Service Controls troubleshooter
  - Policy Troubleshooter for Chrome Enterprise Premium

Access troubleshooters help answer "why" questions like the following:

  - "Why does this user have the `bigquery.datasets.create` permission on this BigQuery dataset?"
  - "Why isn't this user able to view the allow policy of this Cloud Storage bucket?"

To learn more about these troubleshooters, see [Access-related troubleshooters](https://docs.cloud.google.com/policy-intelligence/docs/access-troubleshooters) .

### Understand service account usage and permissions

[Service accounts](https://docs.cloud.google.com/iam/docs/service-accounts) are a special type of principal that you can use to authenticate applications in Google Cloud.

To help you understand service account usage, Policy Intelligence offers the following features:

  - **Activity Analyzer** : Activity Analyzer lets you see when your service accounts and keys were last used to call a Google API. To learn how to use Activity Analyzer, see [View recent usage for service accounts and keys](https://docs.cloud.google.com/policy-intelligence/docs/activity-analyzer-service-account-authentication) .

  - **Service account insights** : Service account insights are a type of [insight](https://docs.cloud.google.com/recommender/docs/insights/using-insights) that identify which service accounts in your project have not been used in the past 90 days. To learn how to manage service account insights, see [Find unused service accounts](https://docs.cloud.google.com/policy-intelligence/docs/service-account-insights) .

To help you understand service account permissions, Policy Intelligence offers lateral movement insights. Lateral movement insights are a type of [insight](https://docs.cloud.google.com/recommender/docs/insights/using-insights) that identify roles that allow a service account in one project to impersonate a service account in another project. For more information about lateral movement insights, see [How lateral movement insights are generated](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview#lateral-movement-insights) . To learn how to manage lateral movement insights, see [Identify service accounts with lateral movement permissions](https://docs.cloud.google.com/policy-intelligence/docs/lateral-movement-insights) .

Lateral movement insights are sometimes linked to [role recommendations](https://docs.cloud.google.com/policy-intelligence/docs/overview#improve) . Role recommendations suggest actions that you can take to remediate the issues identified by lateral movement insights.

## Improve your policies

You can improve your [IAM allow policies](https://docs.cloud.google.com/iam/docs/policies) by using role recommendations. Role recommendations help you enforce the principle of least privilege by ensuring that principals have only the permissions that they actually need. Each role recommendation suggests that you remove or replace an [IAM role](https://docs.cloud.google.com/iam/docs/overview#roles) that gives your principals excess permissions.

To learn more about role recommendations, including how they're generated, see [Enforce least privilege with role recommendations](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview) .

To learn how to manage role recommendations, see one of the following guides:

  - [Review and apply role recommendations for projects, folders, and organizations](https://docs.cloud.google.com/policy-intelligence/docs/review-apply-role-recommendations)
  - [Review and apply role recommendations for Cloud Storage buckets](https://docs.cloud.google.com/policy-intelligence/docs/review-apply-role-recommendations-buckets)
  - [Review and apply role recommendations for BigQuery datasets](https://docs.cloud.google.com/policy-intelligence/docs/review-apply-role-recommendations-datasets)

## Prevent policy misconfigurations

There are several Policy Intelligence tools that you can use to see how changes to policies will impact your organization. After you see the effect of the changes, you can decide whether or not to make them.

> **Note:** If you want to get warnings when you're about to make a change that Google Cloud views as risky, you can enable [change risk recommendations](https://docs.cloud.google.com/recommender/docs/change-risk-recommendations) . Change risk recommendations generate warnings when you try to make certain high-risk changes, like revoking a project-level role that Google Cloud has identified as important.

### Test changes to access-related policies

To let you see how a change to an access-related policy might affect your principals' access, Policy Intelligence provides the following policy simulators:

  - [Policy Simulator for allow policies](https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview)
  - [Policy Simulator for deny policies](https://docs.cloud.google.com/policy-intelligence/docs/deny-simulator-overview)
  - [Policy Simulator for principal access boundary policies](https://docs.cloud.google.com/policy-intelligence/docs/pab-simulator-overview)

Each of these simulators lets you see how a change to a policy of that type would affect access for your principals before you commit to making the change. Each simulator only evaluates one policy type—they don't take into account whether other types of policies would permit or block access.

### Test organization policy changes

Policy Simulator for Organization Policy lets you preview the impact of a new custom constraint or organization policy that enforces a custom constraint before it is enforced on your production environment.

Policy Simulator provides a list of resources that violate the proposed policy before it is enforced, allowing you to reconfigure those resources, request exceptions, or change the scope of your organization policy, all without disrupting your developers or bringing down your environment.

To learn how to use Policy Simulator to test changes to organization policies, see [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies) .
