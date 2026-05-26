---
name: documents/docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies
uri: https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies
title: Test deny policy changes with Policy Simulator
description: Instructions for using Policy Simulator to see how a change to a deny policy might impact a principal's access.
data_source: docs.cloud.google.com
---

> **Preview — Policy insights for BigQuery datasets**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

This page describes how to simulate a change to an IAM [deny policy](https://docs.cloud.google.com/iam/docs/deny-overview) using Policy Simulator. It also explains how to interpret the results of the simulation, and how to apply the simulated deny policy if you choose to.

This feature only evaluates access based on deny policies.

To learn how to simulate other types of policies, see the following:

  - [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies)
  - [Test principal access boundary policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies)
  - [Test role changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-iam-policies)

## Before you begin

  - Enable the Policy Simulator and Identity and Access Management APIs.
    
    **Roles required to enable APIs**
    
    To enable APIs, you need the Service Usage Admin IAM role ( `roles/serviceusage.serviceUsageAdmin` ), which contains the `serviceusage.services.enable` permission. [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

  - Optional: Learn [how Policy Simulator for deny policies works](https://docs.cloud.google.com/policy-intelligence/docs/deny-simulator-overview) .

### Required roles

To get the permissions that you need to test changes to deny policies, ask your administrator to grant you the [Deny Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin) ( `roles/iam.denyAdmin` ) IAM role on the organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

You might also be able to get the required permissions through [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Simulate a change to a deny policy

Simulating a deny policy involves the following steps:

1.  [Starting the simulation](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies#start-simulation)
2.  [Waiting for the simulation to finish](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies#wait)
3.  [Viewing the simulation report](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies#view-report)
4.  [Taking action based on the simulation](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies#take-action)

### Start a simulation

You can start a simulation in the following ways:

  - Simulate a new deny policy:
    
    1.  In the Google Cloud console, go to the **Deny** tab on the **IAM** page.
    
    <!-- end list -->
    
    1.  Select a project, folder, or organization.
    2.  Follow the steps to [create a deny policy](https://docs.cloud.google.com/iam/docs/deny-access#create-deny-policy) , but don't click **Create** after entering the deny policy details. Instead, click **Test policy** .

  - Simulate an edit to a deny policy:
    
    1.  In the Google Cloud console, go to the **Deny** tab on the **IAM** page.
    
    2.  Select a project, folder, or organization.
    
    3.  In the **Policy ID** column, click the ID of the policy that you want to edit.
    
    4.  Click edit **Edit** .
    
    5.  Update the deny policy:
        
          - To change the policy display name, edit the **Display name** field.
          - To edit an existing deny rule, click the deny rule, and then modify the rule's principals, exception principals, denied permissions, exception permissions, or denial condition.
          - To remove a deny rule, find the deny rule that you want to delete, and then click delete **Delete** in that row.
          - To add a deny rule, click **Add deny rule** , and then create a deny rule like you do when you [create a deny policy](https://docs.cloud.google.com/iam/docs/deny-access#create-deny-policy) .
    
    6.  When you're done updating the deny policy, click **Test changes** .

When you click **Test policy** or **Test changes** , Policy Simulator starts the simulation and redirects you to the **Deny simulation reports** page. You can navigate away from this page without losing progress.

### Wait for a simulation to complete

After you start a simulation, the Google Cloud console generates a notification that the simulation is running.

After the simulation finishes, the Google Cloud console generates another notification that the simulation is complete. When you receive this notification, you can [view the simulation report](https://docs.cloud.google.com/policy-intelligence/docs/simulate-deny-policies#view-report) .

Each user can have up to 10 in-progress simulations.

### View a simulation report

1.  In the Google Cloud console, go to the **Deny simulation reports** page.

2.  Find the simulation whose report you want to view, then click **View report** in that row.

The simulation report contains the following:

  - An overview of the simulation details, including the simulated policy, the simulated action, and the simulation time.
  - A **View policy** or **View policy changes** button, which, when clicked, displays the simulated policy in JSON format. If you're simulating the policy change, then it might also display the difference between the current policy and the simulated policy.
  - A **Replay results** section, which displays the results of the simulation. To learn how to interpret these results, see [Policy Simulator results](https://docs.cloud.google.com/policy-intelligence/docs/deny-simulator-overview#review-results) .

## Take action based on a simulation

After reviewing a simulation report, you can take the following actions:

  - **Export the simulation results** : To export the results of a simulation as a CSV file, click **Export results** .
    
    When you click this button, a CSV file with the simulation reports is downloaded to your computer.

  - **Apply the simulated policy change** : To apply the simulated policy or policy change, click **Set policy** .
    
    When you click this button, the Google Cloud console sets the simulated policy.

  - **Edit the simulated change to the policy** : To make further changes to the simulated policy or policy change, click **Modify policy** .
    
    When you click this button, the Google Cloud console redirects you to the deny policy editor.

Alternatively, you can click **Cancel** to leave the simulation report without taking any action.

## View simulation history

The **Deny simulation reports** page contains a table listing all of the simulations that you've run over the past 14 days. This list is unique to each user and can't be shared.

To view the **Deny simulation reports** page, do the following:

1.  In the Google Cloud console, go to the **Deny** tab on the **IAM** page.

2.  Select the project, folder, or organization that you want to view simulations for.

3.  Click schedule **Simulation history** .

For each simulation, the page lists the policy that the simulation is for, the date that you started the simulation, and the status of the simulation.

Simulations can have the following statuses:

  - **In progress** : The simulation is running, but hasn't completed yet. You can have up to 10 in-progress simulations.
  - **Completed** : The simulation is complete.
  - **Error** : The simulation couldn't be completed due to an error.

## What's next

  - [Test organization policy changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/test-organization-policies)
  - [Test role changes with Policy Simulator](https://docs.cloud.google.com/policy-intelligence/docs/simulate-iam-policies)
