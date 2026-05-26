---
name: documents/docs.cloud.google.com/iam/docs/service-account-types
uri: https://docs.cloud.google.com/iam/docs/service-account-types
title: Types of service accounts
description: 'Learn about the different types of service accounts in {{dynamic_data.site_values.cloud_name}} IAM: user-managed and service agents. Explore how each are created and used.'
data_source: docs.cloud.google.com
---

[Service accounts](https://docs.cloud.google.com/iam/docs/service-account-overview) can be divided into the following categories:

  - *User-managed service accounts* , which you create and manage yourself
  - *Service agents* , which Google Cloud creates and manages

This page describes how each type of service account is created and used.

## User-managed service accounts

*User-managed service accounts* are service accounts that you create in your projects. You can update, disable, enable, and delete these service accounts at your discretion. You can also manage other principals' access to these service accounts.

You can create user-managed service accounts in your project using the IAM API, the Google Cloud console, or the Google Cloud CLI.

The number of service accounts that you can have in each project depends on your project. To view the quota for a project, [view your project's quotas in the Google Cloud console](https://docs.cloud.google.com/docs/quotas/view-manage#viewing_your_quota_console) and search for **Service Account Count** .

When you create a user-managed service account in your project, you choose a name for the service account. This name appears in the email address that identifies the service account, which uses the following format:

`  service-account-name @ project-id .iam.gserviceaccount.com `

To learn how to create a service account, see [Create service accounts](https://docs.cloud.google.com/iam/docs/service-accounts-create) .

### Default service accounts

Default service accounts are user-managed service accounts that are created automatically when you enable or use certain Google Cloud services. These service accounts let the service deploy jobs that access other Google Cloud resources. You are responsible for managing default service accounts after they are created.

If your application runs in a Google Cloud environment that has a default service account, your application can use the credentials for the default service account to call Google Cloud APIs. Alternatively, you can create your own user-managed service account and use it to authenticate. For details, see [Set up Application Default Credentials](https://docs.cloud.google.com/docs/authentication/set-up-adc-attached-service-account) .

Depending on your organization policy configuration, the default service account might automatically be granted the [Editor role](https://docs.cloud.google.com/iam/docs/roles-overview#basic) on your project. We strongly recommend that you disable the automatic role grant by [enforcing the `iam.automaticIamGrantsForDefaultServiceAccounts` organization policy constraint](https://docs.cloud.google.com/resource-manager/docs/organization-policy/restricting-service-accounts#disable_service_account_default_grants) . If you created your organization after May 3, 2024, this constraint is enforced by default.

If you disable the automatic role grant, you must decide which roles to grant to the default service accounts, and then [grant these roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) yourself.

If the default service account already has the Editor role, we recommend that you replace the Editor role with less permissive roles.To safely modify the service account's roles, use [Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-iam-policies) to see the impact of the change, and then [grant and revoke the appropriate roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

> **Note:** If you are replacing a role binding that has existed for more than 90 days, [role recommendations](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview) can help you determine which roles to grant instead. You can also use the [Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/iam-simulator-overview) to help ensure that changing the role won't affect the service account's access.

The following table lists the services that create default service accounts:

| Service                                                               | Service account name                   | Email address                                                            |
| --------------------------------------------------------------------- | -------------------------------------- | ------------------------------------------------------------------------ |
| App Engine, and any Google Cloud service that uses App Engine         | App Engine default service account     | `         project-id        @appspot.gserviceaccount.com `               |
| Compute Engine, and any Google Cloud service that uses Compute Engine | Compute Engine default service account | `         project-number        -compute@developer.gserviceaccount.com ` |

> **Note:** Both the creation time and the email address format for default service accounts are subject to change.

<span id="google-managed"></span>

## Service agents

Some Google Cloud services need access to your resources so that they can act on your behalf. For example, when you use Cloud Run to run a container, the service needs access to any Pub/Sub topics that can trigger the container.

To meet this need, Google Cloud creates and manages service accounts for many Google Cloud services. These service accounts are known as *service agents* . You might see service agents in your project's allow policy, in audit logs, or on the IAM page in the Google Cloud console. For a full list of service agents, see [Service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

Service agents aren't created in your projects, so you won't see them when viewing your projects' service accounts. You can't access them directly.

By default, service agents aren't listed in the **IAM** page in the Google Cloud console, even if they've been granted a role on your project. To view role grants for service agents, select the **Include Google-provided role grants** checkbox.

![](https://docs.cloud.google.com/static/iam/img/include-google-provided-role-grants.png)

![](https://docs.cloud.google.com/static/iam/img/include-google-provided-role-grants-2x.png)

> **Note:** Both the creation time and the email address format for service agents are subject to change.

Google Cloud has the following types of service agents:

  - [Service-specific service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents)
  - [Google APIs Service Agent](https://docs.cloud.google.com/iam/docs/service-account-types#google-apis-service-agent)
  - [Role manager for service agents](https://docs.cloud.google.com/iam/docs/service-account-types#role-manager)

### Service-specific service agents

Most service agents are *service-specific* —they act on behalf of individual services. In many cases, these service agents are required for services to function properly. For example, service agents are what allow Cloud Logging sinks to write logs to Cloud Storage buckets.

Each service agent is associated with a resource. This resource is typically a project, folder, or organization, though it can also be a service-specific resource—for example, a Cloud SQL instance. This resource defines the scope of the service agent's actions. For example, if a service agent is associated with a project, it will act on behalf of a service for the project and its descendant resources.

You can determine which type of resource a service agent is associated with by looking at its email address:

  - If the service agent is associated with a project, folder, or organization, its email address contains the numeric ID for that project, folder, or organization.
  - If the service agent is associated with a service-specific resource, its email address contains a numeric project ID and a unique identifier. The numeric project ID indicates which project owns the resource that the service agent is associated with. The unique identifier distinguishes the service agent from other similar service agents in the same project.

### Google APIs Service Agent

Your project's allow policy is likely to refer to a service account named the Google APIs Service Agent, with an email address that uses the following format: `  project-number @cloudservices.gserviceaccount.com ` .

This service account runs internal Google Cloud processes on your behalf. It is automatically granted the Editor role ( `roles/editor` ) on the project.

> **Warning:** Unless a [role recommendation](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview) suggests it, don't revoke the roles that are granted to the Google APIs Service Agent. If you revoke these roles in a way that is not suggested by a role recommendation, some Google Cloud services will no longer work.

### Role manager for service agents

Your [audit logs](https://docs.cloud.google.com/iam/docs/audit-logging) for IAM might refer to the service account `service-agent-manager@system.gserviceaccount.com` .

This service account manages the roles that are granted to other service agents. It is visible only in audit logs.

For example, if you use a new API, Google Cloud might automatically create a new service agent and grant it roles on your project. Granting these roles generates an audit log entry, which shows that `service-agent-manager@system.gserviceaccount.com` set the allow policy for the project.

## Service agent creation

The exact time that a service agent is created depends on what type of resource it's associated with.

Service agents that are associated with a service-specific resource are created when you create the resource. For more information on how to identify and configure these service agents, review the documentation for the associated resource.

Service agents that are associated with projects, folders, and organizations are created as you need them, usually when you first use a service. If necessary, you can also ask Google Cloud to create service agents for a service before you use the service. For more information, see [Create and grant roles to service agents](https://docs.cloud.google.com/iam/docs/create-service-agents) .

> **Note:** If multiple service agents are created at the same time, then you might get a [concurrent policy change error](https://docs.cloud.google.com/iam/docs/allow-policies#etag) while the [Service Agent Manager](https://docs.cloud.google.com/iam/docs/service-account-types#role-manager) tries to grant roles to the service agents. No action is required to resolve this error—the Service Agent Manager automatically retries the action until all service agents have the correct roles.

## IAM roles for service agents

Some actions in Google Cloud require service agents to create and access resources on your behalf. For example, when you create a Managed Service for Apache Spark cluster, the Managed Service for Apache Spark service agent needs permission to create Compute Engine instances in your project in order to create the cluster.

To get this access, service agents need specific IAM roles. Many project-level service agents are automatically granted the roles that they need. The names of these automatically granted roles typically end in `serviceAgent` or `ServiceAgent` . For other service agents, you need to grant them roles so that the service works correctly. To find out which service agents are granted roles automatically, see the [service agent reference](https://docs.cloud.google.com/iam/docs/service-agents) .

If you need to [deny certain permissions](https://docs.cloud.google.com/iam/docs/deny-overview) to principal sets that include service agents—for example, the principal set `principalSet://goog/public:all` —then we recommend adding your service agents as exceptions in the deny rule. This helps ensure that your services continue to function properly. When adding service agents as exceptions, use the project, folder, or organization's [service agent principal set](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny-service-agent-principal-sets) .

> **Warning:** Unless a [role recommendation](https://docs.cloud.google.com/policy-intelligence/docs/role-recommendations-overview) suggests it, don't revoke the roles that are granted to service agents. If you revoke these roles in a way that is not suggested by a role recommendation, some Google Cloud services will no longer work. To ensure that these roles aren't revoked, you can implement a [custom organization policy that prevents users from revoking service agent roles](https://docs.cloud.google.com/iam/docs/org-policy-custom-constraints#service-agents-constraint) .

If you ask Google Cloud to create service agents before you use a service, you must grant the service agents the roles that they are typically granted automatically. This is because service agents that are created at a user's request aren't automatically granted roles. If you don't grant the service agents these roles, some services might not function properly. To learn how to grant these roles to service agents, see [Create and grant roles to service agents](https://docs.cloud.google.com/iam/docs/create-service-agents) .

### Primary service agents

In the [service agent reference](https://docs.cloud.google.com/iam/docs/service-agents) , some service agents are identified as *primary service agents* . Primary service agents are service agents whose email address is returned when you [trigger service agent creation](https://docs.cloud.google.com/iam/docs/create-service-agents#create) for a service.

## Service agent audit logs

Sometimes, when a principal initiates an operation, a service agent executes an action on the principal's behalf. However, when you're reviewing audit logs for a service agent, it can be hard to tell who the service agent was acting on behalf of, and why.

To help you understand the context for a service agent's actions, some service agents include additional details in their audit logs, like the job the action is associated with and the principal that created the job.

The following service agents include these additional details in their audit logs:

  - [BigQuery Connection Service Agent](https://docs.cloud.google.com/iam/docs/service-agents#bigquery-connection-service-agent)
  - [BigQuery Connection Delegation Service Agent](https://docs.cloud.google.com/iam/docs/service-agents#bigquery-connection-delegation-service-agent)

These additional details are in the `serviceDelegationHistory` field of the audit log, which is nested in the `authenticationInfo` field. This field contains the following information:

  - The original principal who created the job
  - The service agent that executed the action
  - The service that the service agent belongs to
  - The job ID

For example, suppose `example-user@example.com` creates a job using the BigQuery Connection API. This job requires one of the BigQuery Connection API's service agents to execute an action. In this case, the audit log for the service agent's action would contain a `serviceDelegationHistory` field similar to the following:

    {
      "protoPayload": {
        "@type": "type.googleapis.com/google.cloud.audit.AuditLog",
        "authenticationInfo": {
          "principalEmail": "bqcx-442188550395-jujw@gcp-sa-bigquery-condel.iam.gserviceaccount.com",
          "serviceDelegationHistory": {
            "originalPrincipal": "user:my-user@example.com",
            "serviceMetadata": [
              {
                "principalSubject": "serviceAccount:bqcx-442188550395-jujw@gcp-sa-bigquery-condel.iam.gserviceaccount.com",
                "serviceDomain": "bigquery.googleapis.com",
              }
            ]
          }
        }
      }
    }

## What's next

  - Find out how to [create and manage service accounts](https://docs.cloud.google.com/iam/docs/managing-service-accounts) .
  - Learn how to [create and manage service account keys](https://docs.cloud.google.com/iam/docs/managing-service-account-keys) .
  - Get [best practices for working with service accounts](https://docs.cloud.google.com/iam/docs/best-practices-service-accounts) .
  - Review [best practices for managing service account keys](https://docs.cloud.google.com/iam/docs/best-practices-for-managing-service-account-keys) .
