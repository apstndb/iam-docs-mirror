---
name: documents/docs.cloud.google.com/iam/docs/service-accounts-custom-constraints
uri: https://docs.cloud.google.com/iam/docs/service-accounts-custom-constraints
title: Use custom organization policies for service accounts and service account keys
description: How to use custom organization policies for Service Accounts and Service Account Keys.
data_source: docs.cloud.google.com
---

Google Cloud Organization Policy gives you centralized, programmatic control over your organization's resources. As the [organization policy administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin) , you can define an organization policy, which is a set of restrictions called constraints that apply to Google Cloud resources and descendants of those resources in the [Google Cloud resource hierarchy](https://docs.cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy) . You can enforce organization policies at the organization, folder, or project level.

Organization Policy provides [predefined constraints](https://docs.cloud.google.com/resource-manager/docs/organization-policy/org-policy-constraints) for various Google Cloud services. However, if you want more granular, customizable control over the specific fields that are restricted in your organization policies, you can also create custom organization policies.

## Benefits

You can use custom organization policies to allow or deny specific operations on service accounts and service account keys. For example, you can set a policy to deny the creation of a key with a certain origin, causing any requests to create a key with that origin to fail and return an error to the user.

## Policy inheritance

By default, organization policies are inherited by the descendants of the resources on which you enforce the policy. For example, if you enforce a policy on a folder, Google Cloud enforces the policy on all projects in the folder. To learn more about this behavior and how to change it, refer to [Hierarchy evaluation rules](https://docs.cloud.google.com/resource-manager/docs/organization-policy/understanding-hierarchy#disallow_inheritance) .

## Before you begin

  - Ensure that you know your [organization ID](https://docs.cloud.google.com/resource-manager/docs/creating-managing-organization#retrieving_your_organization_id) .

  - If you want to test out custom organization policies that reference IAM resources, create a new project. Testing these organization policies in an existing project could disrupt security workflows.
    
    1.  In the Google Cloud console, go to the project selector page.
    
    2.  Select or create a Google Cloud project.
        
        **Roles required to select or create a project**
        
          - **Select a project** : Selecting a project doesn't require a specific IAM role—you can select any project that you've been granted a role on.
          - **Create a project** : To create a project, you need the Project Creator role ( `roles/resourcemanager.projectCreator` ), which contains the `resourcemanager.projects.create` permission. [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .
        
        > **Note** : If you don't plan to keep the resources that you create in this procedure, create a project instead of selecting an existing project. After you finish these steps, you can delete the project, removing all resources associated with the project.

### Required roles

To get the permissions that you need to manage organization policies, ask your administrator to grant you the [Organization policy administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin) ( `roles/orgpolicy.policyAdmin` ) IAM role on the organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to manage organization policies. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to manage organization policies:

  - `orgpolicy.constraints.list`
  - `orgpolicy.policies.create`
  - `orgpolicy.policies.delete`
  - `orgpolicy.policies.list`
  - `orgpolicy.policies.update`
  - `orgpolicy.policy.get`
  - `orgpolicy.policy.set`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Create a custom constraint

A custom constraint is defined in a YAML file by the resources, methods, conditions, and actions that are supported by the service on which you are enforcing the organization policy. Conditions for your custom constraints are defined using [Common Expression Language (CEL)](https://github.com/google/cel-spec/blob/master/doc/intro.md) . For more information about how to build conditions in custom constraints using CEL, see the CEL section of [Creating and managing custom constraints](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) .

To create a YAML file for a custom constraint:

    name: organizations/ORGANIZATION_ID/customConstraints/CONSTRAINT_NAME
    resourceTypes:
    - iam.googleapis.com/RESOURCE_TYPE
    methodTypes:
    - CREATE
    - UPDATE
    condition: "CONDITION"
    actionType: ACTION
    displayName: DISPLAY_NAME
    description: DESCRIPTION

Replace the following:

  - `  ORGANIZATION_ID  ` : your organization ID, such as `123456789` .

  - `  CONSTRAINT_NAME  ` : the name you want for your new custom constraint. A custom constraint must start with `custom.` , and can only include uppercase letters, lowercase letters, or numbers, for example, custom.denyServiceAccountCreation. The maximum length of this field is 70 characters, not counting the prefix, for example, `organizations/123456789/customConstraints/custom` .

  - `  RESOURCE_TYPE  ` : the name (not the URI) of the Identity and Access Management API REST resource containing the object and field you want to restrict. For example, iam.googleapis.com/ServiceAccount.

  - `  CONDITION  ` : a [CEL condition](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) that is written against a representation of a supported service resource. This field has a maximum length of 1000 characters. See [Supported resources](https://docs.cloud.google.com/iam/docs/service-accounts-custom-constraints#supported_resources) for more information about the resources available to write conditions against. For example, ` "resource.description.contains(' INVALID_DESCRIPTION ')"  ` .

  - `  ACTION  ` : the action to take if the `condition` is met. This can be either `ALLOW` or `DENY` .

  - `  DISPLAY_NAME  ` : a human-friendly name for the constraint. This field has a maximum length of 200 characters.

  - `  DESCRIPTION  ` : a human-friendly description of the constraint to display as an error message when the policy is violated. This field has a maximum length of 2000 characters.

For more information about how to create a custom constraint, see [Defining custom constraints](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#defining_custom_constraints) .

## Set up a custom constraint

### Console

To create a custom constraint, do the following:

In the Google Cloud console, go to the **Organization policies** page.

From the project picker, select the project that you want to set the organization policy for.

Click add **Custom constraint** .

In the **Display name** box, enter a human-readable name for the constraint. This name is used in error messages and can be used for identification and debugging. Don't use personally identifiable information (PII) or sensitive data in display names because this name could be exposed in error messages. This field can contain up to 200 characters.

In the **Constraint ID** box, enter the ID that you want for your new custom constraint. A custom constraint can only contain letters (including upper and lowercase) or numbers, for example `custom.denyServiceAccountCreation` . This field can contain up to 70 characters, not counting the prefix ( `custom.` ), for example, `organizations/123456789/customConstraints/custom` . Don't include PII or sensitive data in your constraint ID, because it could be exposed in error messages.

In the **Description** box, enter a human-readable description of the constraint. This description is used as an error message when the policy is violated. Include details about why the policy violation occurred and how to resolve the policy violation. Don't include PII or sensitive data in your description, because it could be exposed in error messages. This field can contain up to 2000 characters.

In the **Resource type** box, select the name of the Google Cloud REST resource containing the object and field that you want to restrict—for example, `container.googleapis.com/NodePool` . Most resource types support up to 20 custom constraints. If you attempt to create more custom constraints, the operation fails.

This constraint can only be enforced on the REST `CREATE` method.

To see supported methods for each service, find the service in [Services that support custom constraints](https://docs.cloud.google.com/organization-policy/reference/custom-constraint-supported-services) .

To define a condition, click edit **Edit condition** .

1.  In the **Add condition** panel, create a CEL condition that refers to a supported service resource, for example, `resource.management.autoUpgrade == false` . This field can contain up to 1000 characters. For details about CEL usage, see [Common Expression Language](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) . For more information about the service resources you can use in your custom constraints, see [Custom constraint supported services](https://docs.cloud.google.com/resource-manager/docs/organization-policy/custom-constraint-supported-services) .
2.  Click **Save** .

Under **Action** , select whether to allow or deny the evaluated method if the condition is met.

The deny action means that the operation to create or update the resource is blocked if the condition evaluates to true.

The allow action means that the operation to create or update the resource is permitted only if the condition evaluates to true. Every other case except those explicitly listed in the condition is blocked.

Click **Create constraint** .

When you have entered a value into each field, the equivalent YAML configuration for this custom constraint appears on the right.

### gcloud

To create a custom constraint, create a YAML file using the following format:

    name: organizations/ORGANIZATION_ID/customConstraints/CONSTRAINT_NAME
    resourceTypes: RESOURCE_NAME
    methodTypes:
      - CREATE
    condition: "CONDITION"
    actionType: ACTION
    displayName: DISPLAY_NAME
    description: DESCRIPTION

Replace the following:

  - `  ORGANIZATION_ID  ` : your organization ID, such as `123456789` .
  - `  CONSTRAINT_NAME  ` : the name that you want for your new custom constraint. A custom constraint can only contain letters (including upper and lowercase) or numbers, for example, `custom.denyServiceAccountCreation` . This field can contain up to 70 characters, not counting the prefix ( `custom.` )— for example, `organizations/123456789/customConstraints/custom` . Don't include PII or sensitive data in your constraint ID, because it could be exposed in error messages.
  - `  RESOURCE_NAME  ` : the fully qualified name of the Google Cloud resource containing the object and field that you want to restrict. For example, `iam.googleapis.com/ServiceAccount` . Most resource types support up to 20 custom constraints. If you attempt to create more custom constraints, the operation fails.
  - `methodTypes` : the REST methods that the constraint is enforced on. Can only be `CREATE` .
  - `  CONDITION  ` : a [CEL condition](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) that is written against a representation of a supported service resource. This field can contain up to 1000 characters. For example, ` "resource.description.contains(' INVALID_DESCRIPTION ')"  ` .
  - `  ACTION  ` : the action to take if the `condition` is met. Can only be `ALLOW` .
  - `  DISPLAY_NAME  ` : a human-readable name for the constraint. This name is used in error messages and can be used for identification and debugging. Don't use PII or sensitive data in display names because this name could be exposed in error messages. This field can contain up to 200 characters.
  - `  DESCRIPTION  ` : a human-friendly description of the constraint to display as an error message when the policy is violated. This field can contain up to 2000 characters.

After you have created the YAML file for a new custom constraint, you must set it up to make it available for organization policies in your organization. To set up a custom constraint, use the [`gcloud org-policies set-custom-constraint`](https://docs.cloud.google.com/sdk/gcloud/reference/org-policies/set-custom-constraint) command:

    gcloud org-policies set-custom-constraint CONSTRAINT_PATH

Replace `  CONSTRAINT_PATH  ` with the full path to your custom constraint file. For example, `/home/user/customconstraint.yaml` .

After this operation is complete, your custom constraints are available as organization policies in your list of Google Cloud organization policies.

To verify that the custom constraint exists, use the [`gcloud org-policies list-custom-constraints`](https://docs.cloud.google.com/sdk/gcloud/reference/org-policies/list-custom-constraints) command:

    gcloud org-policies list-custom-constraints --organization=ORGANIZATION_ID

Replace `  ORGANIZATION_ID  ` with the ID of your organization resource.

For more information, see [Viewing organization policies](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-policies#viewing_organization_policies) .

## Enforce a custom organization policy

You can enforce a constraint by creating an organization policy that references it, and then applying that organization policy to a Google Cloud resource.

### Console

1.  In the Google Cloud console, go to the **Organization policies** page.
2.  From the project picker, select the project that you want to set the organization policy for.
3.  From the list on the **Organization policies** page, select your constraint to view the **Policy details** page for that constraint.
4.  To configure the organization policy for this resource, click **Manage policy** .
5.  On the **Edit policy** page, select **Override parent's policy** .
6.  Click **Add a rule** .
7.  In the **Enforcement** section, select whether this organization policy is enforced or not.
8.  Optional: To make the organization policy conditional on a tag, click **Add condition** . Note that if you add a conditional rule to an organization policy, you must add at least one unconditional rule or the policy cannot be saved. For more information, see [Scope organization policies with tags](https://docs.cloud.google.com/organization-policy/scope-policies) .
9.  Click **Test changes** to simulate the effect of the organization policy. For more information, see [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies) .
10. To enforce the organization policy in dry-run mode, click **Set dry run policy** . For more information, see [Test organization policies](https://docs.cloud.google.com/organization-policy/test-policies) .
11. After you verify that the organization policy in dry-run mode works as intended, set the live policy by clicking **Set policy** .

### gcloud

To create an organization policy with boolean rules, create a policy YAML file that references the constraint:

    name: projects/PROJECT_ID/policies/CONSTRAINT_NAME
    spec:
      rules:
      - enforce: true
    
    dryRunSpec:
      rules:
      - enforce: true

Replace the following:

  - `  PROJECT_ID  ` : the project that you want to enforce your constraint on.
  - `  CONSTRAINT_NAME  ` : the name you defined for your custom constraint. For example, `custom.denyServiceAccountCreation` .

To enforce the organization policy in [dry-run mode](https://docs.cloud.google.com/organization-policy/test-policies) , run the following command with the `dryRunSpec` flag:

    gcloud org-policies set-policy POLICY_PATH --update-mask=dryRunSpec

Replace `  POLICY_PATH  ` with the full path to your organization policy YAML file. The policy requires up to 15 minutes to take effect.

After you verify that the organization policy in dry-run mode works as intended, set the live policy with the `org-policies set-policy` command and the `spec` flag:

    gcloud org-policies set-policy POLICY_PATH --update-mask=spec

Replace `  POLICY_PATH  ` with the full path to your organization policy YAML file. The policy requires up to 15 minutes to take effect.

## Test the custom organization policy

Optionally, you can test the organization policy by setting the policy and then trying to take an action that the policy should prevent.

This section describes how to test the following organization policy constraint:

    name: organizations/ORG_ID/customConstraints/custom.denyServiceAccountCreation
    resourceTypes: iam.googleapis.com/ServiceAccount
    methodTypes:
      - CREATE
      - UPDATE
    condition:
      "resource.description.contains('INVALID_DESCRIPTION')"
    actionType: DENY
    displayName: Do not allow service account with INVALID_DESCRIPTION to be created.

If you want to test this custom constraint, do the following:

1.  Copy the constraint into a YAML file and replace the following values:
    
      - `  ORG_ID  ` : the numeric ID of your Google Cloud organization.
      - `  INVALID_DESCRIPTION  ` : the description that you want to use to test the custom constraint. While the constraint is active, service accounts with a description containing this string won't be created on the project that you enforce the constraint for.

2.  [Set up](https://docs.cloud.google.com/iam/docs/service-accounts-custom-constraints#set_up_custom_constraint) the custom constraint and [enforce](https://docs.cloud.google.com/iam/docs/service-accounts-custom-constraints#enforce_custom_constraint) it for the project that you created to test the custom organization policy constraint.

3.  Ensure that you have the [Create Service Accounts role ( `roles/iam.serviceAccountCreator` )](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator) .

4.  Try to create a service account with the description you included in the custom constraint. Before running the command, replace the following values:
    
      - `  SERVICE_ACCOUNT_NAME  ` : The name of the service account
      - `  INVALID_DESCRIPTION  ` : The invalid string that will be checked for in the description of the service account
      - `  DISPLAY_NAME  ` : The service account name to display in the Google Cloud console

<!-- end list -->

    gcloud iam service-accounts create SERVICE_ACCOUNT_NAME \
        --description="INVALID_DESCRIPTION" --display-name="DISPLAY_NAME"

The output is the following:

    Operation denied by custom org policy: ["customConstraints/custom.denyServiceAccountCreation": "Do not allow service account with INVALID_DESCRIPTION to be created."]

## Identity and Access Management supported resources and operations

The following service account and service account key custom constraint fields are available to use when you create or update an account or key.

  - Service accounts
      - `resource.description`
      - `resource.displayName`
      - `resource.name`
          - Format: ` projects/ PROJECT_ID /serviceAccounts/ UNIQUE_ID  `
  - Service account keys
      - `resource.keyOrigin`
      - `resource.keyType`
      - `resource.name`
          - Format: ` projects/ PROJECT_ID /serviceAccounts/ UNIQUE_ID /keys/ KEY_ID  `

## Example custom organization policies for common use cases

The following table provides the syntax of some custom constraints for common use cases:

For more information about CEL macros available for use in custom constraint conditions, see [Common Expression Language](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-custom-constraints#common_expression_language) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Description</th>
<th>Constraint syntax</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Disable service account creation.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>    name: organizations/ORGANIZATION_ID/customConstraints/custom.disableServiceAccountCreation
    resourceTypes:
    - iam.googleapis.com/ServiceAccount
    methodTypes:
    - CREATE
    condition: &quot;True&quot;
    actionType: DENY
    displayName: Deny all service account creation.</code></pre></td>
</tr>
<tr class="even">
<td>Disable service account key creation.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>    name: organizations/ORGANIZATION_ID/customConstraints/custom.disableServiceAccountKeyCreation
    resourceTypes:
    - iam.googleapis.com/ServiceAccountKey
    methodTypes:
    - CREATE
    condition: &quot;resource.keyType == USER_MANAGED &amp;&amp; resource.keyOrigin == GOOGLE_PROVIDED&quot;
    actionType: DENY
    displayName: Deny all service account key creation.</code></pre></td>
</tr>
<tr class="odd">
<td>Disable service account key upload.</td>
<td><pre dir="ltr" data-is-upgraded="" data-syntax="YAML" translate="no"><code>    name: organizations/ORGANIZATION_ID/customConstraints/custom.disableServiceAccountKeyUpload
    resourceTypes:
    - iam.googleapis.com/ServiceAccountKey
    methodTypes:
    - CREATE
    condition: &quot;resource.keyType == USER_MANAGED &amp;&amp; resource.keyOrigin == USER_PROVIDED&quot;
    actionType: DENY
    displayName: Deny all service account key uploads.</code></pre></td>
</tr>
</tbody>
</table>

## What's next

  - See [Introduction to the Organization Policy Service](https://docs.cloud.google.com/resource-manager/docs/organization-policy/overview) to learn more about organization policies.
  - Learn more about how to [create and manage organization policies](https://docs.cloud.google.com/resource-manager/docs/organization-policy/using-constraints) .
  - See the full list of predefined [organization policy constraints](https://docs.cloud.google.com/resource-manager/docs/organization-policy/org-policy-constraints) .
