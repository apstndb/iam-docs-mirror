---
name: documents/docs.cloud.google.com/iam/docs/role-picker-gemini
uri: https://docs.cloud.google.com/iam/docs/role-picker-gemini
title: Get predefined role suggestions with Gemini assistance
description: Ask Gemini for IAM role suggestions that adhere to the principal of least privilege.
data_source: docs.cloud.google.com
---

This page describes how you can find and grant the least permissive Identity and Access Management (IAM) predefined roles to your principals with Gemini assistance.

The IAM role picker lets you ask Gemini which roles you should grant to your principals. Typically, to find the right predefined roles to grant, you would need to search through the [IAM roles and permissions index](https://docs.cloud.google.com/iam/docs/roles-permissions) or the [**Roles** page in the Google Cloud console](https://console.cloud.google.com/iam-admin/roles) . With the IAM role picker, you can describe the actions you want the principal to perform and the resources that they need to perform them on. Based on your input, Gemini suggests the least permissive predefined roles that it considers appropriate.

Gemini can suggest predefined roles for individual principals. If Gemini suggests granting a role at the project level, then you can use the IAM role picker to grant that role.

You *can't* use the IAM role picker to get suggestions for the following things:

  - Custom roles
  - Roles for multiple principals (with a single prompt)
  - Roles for Google Workspace products like Google Sheets and Google Docs

> **Note:** Gemini can't suggest custom roles through the IAM role picker, but you can still get custom role suggestions from Gemini by using the Gemini Cloud Assist chat panel. For instructions, see [Use Gemini Cloud Assist in the Google Cloud console](https://docs.cloud.google.com/cloud-assist/chat-panel) in the Gemini Cloud Assist documentation.

Learn [how and when Gemini for Google Cloud uses your data](https://docs.cloud.google.com/gemini/docs/discover/data-governance) .

## Required Roles

To get the permissions that you need to use the IAM role picker, ask your administrator to grant you the [Project IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin) ( `roles/resourcemanager.projectIamAdmin` ) IAM role on project. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to use the IAM role picker. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to use the IAM role picker:

  - `resourcemanager.projects.get`
  - `resourcemanager.projects.getIamPolicy`
  - `resourcemanager.projects.setIamPolicy`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Get role suggestions with Gemini assistance

> As an early-stage technology, Gemini for Google Cloud products can generate output that seems plausible but is factually incorrect. We recommend that you validate all output from Gemini for Google Cloud products before you use it. For more information, see [Gemini for Google Cloud and responsible AI](https://docs.cloud.google.com/gemini/docs/discover/responsible-ai) .

To get role suggestions from Gemini, you can access the IAM role picker on pages in the Google Cloud console that let you grant access at the project level. For example, the IAM role picker is available on the following pages:

  - The **IAM** page
  - The **Service Accounts** page
  - The Google Cloud console **Dashboard** page

The following procedure uses the **IAM** page as the primary entry point.

1.  In the Google Cloud console, go to the **IAM** page.

2.  Select a project.

3.  Select a principal to get role suggestions for:
    
      - To get role suggestions for a principal who already has other roles on the resource, find a row containing the principal, and then click edit **Edit principal** in that row.
        
        To grant a role to a [service agent](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) , select the **Include Google-provided role grants** checkbox to see its email address.
        
        > **Note:** You cannot edit inherited roles when managing access to a resource. To edit inherited roles, go to the resource where the role was granted.
    
      - To get role suggestions for a principal who doesn't have any existing roles on the resource, click person\_add **Grant Access** , then enter a [principal identifier](https://docs.cloud.google.com/iam/docs/principal-identifiers) —for example, `my-user@example.com` or `//iam.googleapis.com/locations/global/workforcePools/example-pool/group/example-group@example.com` .

4.  To open the IAM role picker dialog, click **Help me choose roles** .

5.  In your own words, describe the action you want the principal to perform and the resource in the project that they need to perform it on.

6.  Click **Suggest roles** . Based on your input, Gemini suggests the least permissive predefined roles that it considers appropriate.
    
    To get more information about the roles and why Gemini suggested them, click **Show reasoning** . We also recommend using the [roles and permissions reference](https://docs.cloud.google.com/iam/docs/roles-permissions) to validate Gemini's suggested roles before granting them to the principal.

7.  Optional: If Gemini doesn't suggest the right roles, you can refine your prompt.
    
    1.  To modify your prompt, click **Edit** .
    2.  Edit the description and then click **Update** . Gemini updates its role suggestions based on the new description.

8.  To accept the suggestions, click **Add roles** .

9.  Optional: Add a [condition](https://docs.cloud.google.com/iam/docs/conditions-overview) to the role.

10. Click **Save** . The principal is granted the role on the resource.

You can grant *project-level* roles suggested by Gemini directly from the IAM role picker. For organization-, folder-, or resource-level role suggestions, note the suggested roles and grant them to the principal at the appropriate level using the typical process in the Google Cloud console. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

If you don't have the permissions to grant the roles at the organization, folder, or resource levels, contact your administrator.

## Sample use cases

The following table illustrates some example use cases where Gemini can help you identify the least permissive roles for your principals.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Use case</th>
<th>Prompt examples</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Identifying least-permissive roles necessary to perform a specific task</td>
<td><ul>
<li>"What role is required to create, start, and stop VMs?"</li>
<li>"What are the least-privileged IAM roles required to create IAM policies?"</li>
<li>"I need to allow a user to create and manage BigQuery datasets and tables. What role should I assign?"</li>
<li>"I need to grant a service account access to invoke Cloud Run functions. What's the minimal role required?"</li>
<li>"Which role allows a service account to read data from Cloud Storage but not write or delete objects?"</li>
</ul></td>
</tr>
<tr class="even">
<td>Identifying least-permissive roles necessary to run Google Cloud CLI commands</td>
<td><ul>
<li>"What IAM role is required to run the following command: <code dir="ltr" translate="no">gcloud compute instances create instance-1 --zone=us-central1-a</code> "</li>
<li>"I would like to identify the necessary roles for a service account to execute the following command: <code dir="ltr" translate="no">gcloud datastore instances describe</code> "</li>
</ul></td>
</tr>
<tr class="odd">
<td>Identifying roles for a task that includes transitive dependencies</td>
<td>"I need to configure a Compute Engine instance to automatically scale based on CPU utilization. Which IAM role(s) should be granted to the service account used by the instance autoscaler?"</td>
</tr>
<tr class="even">
<td>Identifying roles for a task that might require a combination of multiple granular roles</td>
<td>"Provide users access only to a particular dataset. We don't want to share the access to all datasets, and we only allow users to access a particular dataset within BigQuery. They shouldn't be able to create new datasets or delete it"</td>
</tr>
</tbody>
</table>

## Best practices

To help Gemini provide the most accurate suggestions for your use case, we recommend that you adhere to the following best practices when drafting your prompt.

  - **Clearly describe your use case.** Avoid using vague language in your prompts. Be as clear as possible about what actions you want the principal to perform on which services and resource types.
    
    | Do                                                                                            | Don't                                              | Details                                                                                                                                                                                                                                                                                                                                                                |
    | --------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | "What role is required to execute SQL queries on a BigQuery table and read the data from it?" | "What role is required to execute SQL statements?" | SQL is a generic language used across multiple Google Cloud services. Without specifying the service or actions, Gemini can't suggest a precise role.                                                                                                                                                                                                                  |
    | "I need roles to start, stop, and reboot Compute Engine virtual machine instances."           | "I need to manage my virtual machines."            | The term *manage* is too vague. Manage could mean creating, deleting, updating, or viewing VMs. Clearly listing the specific actions to be performed (start, stop, reboot) and the exact resource type (Compute Engine virtual machine instances) yields more accurate suggestions.                                                                                    |
    | "I need to upload and download objects from a Cloud Storage bucket named `example-bucket` ."  | "Give me access to storage."                       | The term *Storage* alone could refer to various services like Cloud Storage, Filestore, or Persistent Disk. In addition, there are no actions specified. Without specifying the service (Cloud Storage), the resource type name ( `example-bucket` ), or the actions (upload and download objects), Gemini doesn't have enough information to suggest the right roles. |
    

  - **Use official names.** Use the official names of Google Cloud services, resource types, and API operations in your prompt. If you are unsure about the official names of services, resource types, or API operations, we recommend consulting the official product documentation.
    
    | Do                                                                      | Don't                                                             | Details                                                                                                                                                                                                                      |
    | ----------------------------------------------------------------------- | ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | "What role do I need to update BigQuery datasets?"                      | "What role do I need to update Big query datasets?                | *BigQuery* is the official name of the product—not *Big query* .                                                                                                                                                             |
    | "What role is required to create a Cloud Storage bucket in my project?" | "What role is required to create a Storage bucket in my project?" | *Storage bucket* could refer to different resource types from services like Cloud Storage, Filestore, or Persistent Disk. Specifying the product name and the associated resource type will yield more accurate suggestions. |
    

## Troubleshooting

This section describes resolutions for common issues with the IAM role picker.

### Gemini suggests roles that you can't grant at the project level

Gemini can suggest roles at all resource levels; however, you can only use the IAM role picker to grant the *project-level* roles that are suggested. When Gemini suggests organization, folder, or resource-level roles, the IAM role picker indicates that there are suggested roles that can't be granted and the **Add roles** button will be disabled.

When this occurs, you can copy the suggested roles and grant them to the principal at the appropriate level using the typical process in the Google Cloud console. For more information on granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

If you don't have the permissions to grant the roles at the organization, folder, or resource levels, contact your administrator.

## What's next

  - Read [Gemini for Google Cloud overview](https://docs.cloud.google.com/gemini/docs/overview) .
  - Learn [how Gemini for Google Cloud uses your data](https://docs.cloud.google.com/gemini/docs/discover/data-governance) .
  - Learn how to manually [find the right predefined roles](https://docs.cloud.google.com/iam/docs/choose-predefined-roles) .
