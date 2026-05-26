---
name: documents/docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies
uri: https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies
title: Test principal access boundary policy changes with Policy Simulator
description: Instructions for using Policy Simulator to see how a change to a principal access boundary policy or binding might impact a principal's access.
data_source: docs.cloud.google.com
---

> **Preview — Policy insights for BigQuery datasets**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

This page describes how to simulate a change to a [principal access boundary (PAB) policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) or [binding](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#binding) using Policy Simulator. It also explains how to interpret the results of the simulation, and how to apply the simulated principal access boundary policy or binding if you choose to.

This feature only evaluates access based on principal access boundary policies.

To learn how to simulate changes to other policy types, see the following:

  - [Test deny policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies)
  - [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies)
  - [Test role changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-iam-policies)

## Before you begin

  - Enable the Cloud Asset Inventory, Identity and Access Management, Policy Analyzer, and Policy Simulator APIs.
    
    **Roles required to enable APIs**
    
    To enable APIs, you need the Service Usage Admin IAM role ( `roles/serviceusage.serviceUsageAdmin` ), which contains the `serviceusage.services.enable` permission. [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

  - Optional: Learn [how Policy Simulator for principal access boundary policies works](https://docs.cloud.google.com/policy-intelligence/docs/pab-simulator-overview) .

### Required roles

To get the permissions that you need to test changes to principal access boundary policies and bindings, ask your administrator to grant you the following IAM roles on the organization:

  - [IAM Operation Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer) ( `roles/iam.operationViewer` )
  - [IAM Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` )
  - [IAM Workload Identity Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin) ( `roles/iam.workloadIdentityPoolAdmin` )
  - [Organization Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin) ( `roles/resourcemanager.organizationAdmin` )
  - [Principal Access Boundary Policy Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin) ( `roles/iam.principalAccessBoundaryAdmin` )
  - [Workspace Pool IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin) ( `roles/iam.workspacePoolAdmin` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

You might also be able to get the required permissions through [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Start a simulation

The following sections describe the ways that you can start a simulation for a change to a principal access boundary policy or binding.

### Simulate a new binding for a principal access boundary policy

Follow the steps to [create a policy binding](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#create-binding) , but don't click **Add** after entering the binding details. Instead, click **Test changes** .

### Simulate an edit to an existing principal access boundary policy

Follow the steps to [edit a principal access boundary policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit#edit-policy) , but don't click **Save** after editing the policy. Instead, click **Test changes** .

### Simulate an edit to an existing binding for a principal access boundary policy

Follow the steps to [edit a policy binding](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit#edit-binding) , but don't click **Save** after editing the binding. Instead, click **Test changes** .

### Simulate deleting principal access boundary rules

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy whose rules you want to delete.

3.  Click the policy ID of the principal access boundary policy whose rule you want to delete.

4.  In the **Boundary rules** table, select the rules that you want to delete, then click auto\_delete **Test delete rules** .

### Simulate deleting a principal access boundary policy

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy whose binding you want to delete.

3.  Find the ID of the policy that you want to delete. In that policy's row, click more\_vert **Actions** , then click **Test delete policy** .

### Simulate deleting a binding for a principal access boundary policy

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy whose binding you want to delete.

3.  Click the policy ID of the principal access boundary policy whose bindings you want to delete.

4.  Click the **Bindings** tab.

5.  Find the ID of the binding that you want to delete. In that binding's row, click more\_vert **Actions** , then click **Test delete binding** .

## Understand simulation results

The results page for a principal access boundary policy or binding simulation contains the following information:

  - An **Access revoked** section, which contains the following information:
    
      - The number of principals that would lose access if you applied the simulated principal access boundary policy or binding
      - The number of known resources that principals would lose access to if you applied the simulated principal access boundary policy or binding

  - An **Access gained** section, which contains the following information:
    
      - The number of principals that would gain access if you applied the simulated principal access boundary policy or binding
      - The number of known resources that principals would gain access to if you applied the simulated principal access boundary policy or binding

  - A table of the access changes, which shows the impact of the simulated policy or binding. To learn how to interpret these access changes, see [Policy Simulator results](https://docs.cloud.google.com/policy-intelligence/docs/pab-simulator-overview#review-results) .

## Take action based on a simulation

After reviewing a simulation report, you can take the following actions:

  - **Export the simulation results** : To export the results of a simulation as a CSV file, click **Export raw results** .
    
    When you click this button, a CSV file with the simulation reports is downloaded to your computer.

  - **Apply the simulated policy change** : The button that you click to apply a simulated policy change depends on the type of change you're simulating.
    
      - **Simulating an edited principal access boundary policy or rule, or a deleted rule** : click **Set policy** .
      - **Simulating a new or edited binding for a principal access boundary policy** : click **Set binding** .
      - **Simulating a deleted principal access boundary policy** : click **Delete policy** .
      - **Simulating a deleted binding for a principal access boundary policy** : click **delete binding** .
    
    When you click this button, the Google Cloud console sets the simulated policy or binding.

  - **Edit the simulated change to the policy or binding** : To make further changes to the simulated policy or policy binding, click **Back** or **Back to editing** .
    
    When you click this button, the Google Cloud console redirects you to the policy or policy binding editor.

## What's next

  - [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies)
  - [Test role changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-iam-policies)
