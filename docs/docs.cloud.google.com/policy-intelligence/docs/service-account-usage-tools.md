---
name: documents/docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools
uri: https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools
title: Tools to understand service account usage
description: An overview of the tools that you can use to understand service account usage.
data_source: docs.cloud.google.com
---

There are several different tools that you can use to understand authentication activities for service accounts and keys. This page describes the available tools and their intended uses.

If you want to see how service accounts are using their permissions and identify over-privileged service accounts, use role recommendations. For more information, see [Overview of role recommendations](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview) .

## Authentication activities

Whenever a service account or key is used to call a Google API, including an API that is not part of Google Cloud, it generates an authentication activity. To understand service account usage, you can track these authentication activities using the tools described on this page.

Authentication activities include both successful and failed API calls. For example, if an API call fails because the caller is not authorized to call that API, or because the request referred to a resource that does not exist, the action still counts as an authentication activity for the service account or key that was used for that API call.

Authentication activities with a Google API outside of Google Cloud, such as [domain-wide delegation](https://docs.cloud.google.com/workspace/cloud-search/docs/guides/delegation) of authority to Google Workspace APIs, aren't tracked by [Activity Analyzer](https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools#sa-authn) or [service account insights](https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools#sa-insights) . To track these authentication activities, use Cloud Monitoring [service account usage metrics](https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools#sa-usage-metrics) .

Cloud Storage hash-based message authentication code (HMAC) authentication keys don't generate authentication activities for either service accounts or service account keys. For more information, see [HMAC keys](https://docs.cloud.google.com/storage/docs/authentication/hmackeys) .

## Activity Analyzer

> **Preview — Viewing service account and key authentication activities with Activity Analyzer**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Policy Intelligence's Activity Analyzer lets you view the most recent [authentication activities](https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools#understand-authn) for your service accounts and service account keys. The date of the most recent authentication activity is determined based on US and Canadian Pacific Standard Time (UTC-8), even when Pacific Daylight Time is in effect.

Use Activity Analyzer to identify unused service accounts and keys. With Activity Analyzer, you can use your own definition of what it means for a service account or key to be "unused." For example, some organizations might define "unused" as 90 days of inactivity, while others might define "unused" as 30 days of inactivity.

We recommend disabling or deleting these unused service accounts and keys because they create an unnecessary security risk. Cross reference Activity Analyzer results with Cloud Monitoring service account usage metrics before disabling or deleting a service account to prevent removing service accounts that are in use with Google APIs outside of Google Cloud.

To learn how to view service account authentication activities, see [View recent usage for service accounts and keys](https://docs.cloud.google.com/policy-intelligence/docs/activity-analyzer-service-account-authentication) .

## Service account insights

> **Preview — Service account insights**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Recommender provides service account insights, which identify the service accounts in your project that haven't authenticated in the past 90 days. Use service account insights to quickly identify unused service accounts.

We recommend that you disable or delete these unused service accounts because they create an unnecessary security risk. Cross reference service account insights with Cloud Monitoring service account usage metrics before you disable or delete a service account. This approach prevents you from removing service accounts that are in use with Google APIs outside of Google Cloud.

To learn how to use service account insights, see [Find unused service accounts](https://docs.cloud.google.com/policy-intelligence/docs/service-account-insights) .

## Service account usage metrics

Cloud Monitoring provides usage metrics for your service accounts and service account keys. Usage metrics report each [authentication activity](https://docs.cloud.google.com/policy-intelligence/docs/service-account-usage-tools#understand-authn) for your service accounts and service account keys.

Authentication activities for service account keys include any time a system lists the keys while attempting to authenticate a request, even if the system doesn't use the key to authenticate the request. This behavior is most common when using [signed URLs for Cloud Storage](https://docs.cloud.google.com/storage/docs/access-control/signed-urls) or when authenticating to third-party applications.

Use service account usage metrics to track service account usage patterns over time. These patterns can help you identify anomalies, either automatically or manually.

To learn how to view service account usage metrics, see [Monitor usage patterns for service accounts and keys](https://docs.cloud.google.com/iam/docs/service-account-monitoring) in the IAM documentation.

## Dormant service account detection

[Event Threat Detection](https://docs.cloud.google.com/security-command-center/docs/concepts-event-threat-detection-overview) detects and reports when a dormant service account triggers an action. Dormant service accounts are service accounts that have been inactive for more than 180 days.

This feature is only available for customers with organization-level activations of [the Premium or Enterprise tier of Security Command Center](https://docs.cloud.google.com/security-command-center/pricing#security-command-center-pricing) .

To learn how to view and remediate dormant service account action findings, see [Investigating and responding to threats](https://docs.cloud.google.com/security-command-center/docs/findings/threats/dormant-service-account-used-in-action) .
