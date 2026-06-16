---
name: documents/docs.cloud.google.com/iam/docs/role-picker-gemini
uri: https://docs.cloud.google.com/iam/docs/role-picker-gemini
title: Get predefined role suggestions with Gemini assistance
description: Ask Gemini for IAM role suggestions that adhere to the principal of least privilege.
data_source: docs.cloud.google.com
---

This page describes how you can find and grant Identity and Access Management (IAM) predefined roles to your principals with Gemini assistance.

The IAM role picker lets you ask Gemini which roles you should grant to your principals. Typically, to find the right predefined roles to grant, you need to search through the [IAM roles and permissions index](https://docs.cloud.google.com/iam/docs/roles-permissions) or the [**Roles** page in the Google Cloud console](https://console.cloud.google.com/iam-admin/roles) . With the IAM role picker, you can describe the actions you want the principal to perform and the resources that they need to perform them on. Based on your input, Gemini suggests the predefined roles that it considers appropriate.

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

6.  Click **Suggest roles** . Based on your input, Gemini suggests the predefined roles that it considers appropriate.
    
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

The following table illustrates some example use cases for the IAM role picker. By default, Gemini suggests roles that are designed to cover common user journeys within a service. For example, Gemini often suggests a service's Admin, Editor, or Viewer roles.

If you want Gemini to suggest the most granular, least privileged roles, you must specify this preference in your prompt using specific keywords. For a list of keywords you can use, see [Keywords for least privileged roles](https://docs.cloud.google.com/iam/docs/role-picker-gemini#keywords) . However, be aware that least privileged roles might not be sufficient for a user's future needs.

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
<td>Identifying roles for general service management</td>
<td><ul>
<li>"What permissions do I need to manage our AlloyDB for PostgreSQL setup?"</li>
<li>"What roles do I need to work with BigQuery?"</li>
<li>"How do I give someone access to run and debug Cloud Run services?"</li>
<li>"I need to provision a Vertex AI Agent identity to execute basic tool calls."</li>
</ul></td>
</tr>
<tr class="even">
<td>Identifying the roles necessary to perform specific tasks</td>
<td><ul>
<li>"What role is required to create, start, and stop VMs?"</li>
<li>"I need to allow a user to create and manage BigQuery datasets and tables."</li>
<li>"I need to grant a service account access to invoke Cloud Run functions."</li>
<li>"I want my agent to trigger a local MCP server that I have deployed on Cloud Run."</li>
</ul>
<p>Prompts that yield least privileged role suggestions:</p>
<ul>
<li>"What is the <em>minimal role</em> required to create, start, and stop VMs?"</li>
<li>"What are the <em>least-privileged</em> IAM roles required to create IAM policies?"</li>
<li>"I need to grant a service account access to invoke Cloud Run functions. What's the <em>narrowest access</em> required?"</li>
<li>"What is the <em>least permissive</em> role my agent needs to trigger a local MCP server I have deployed on Cloud Run?"</li>
</ul></td>
</tr>
<tr class="odd">
<td>Identifying roles necessary to run Google Cloud CLI commands</td>
<td><ul>
<li>"What IAM role is required to run: <code dir="ltr" translate="no">gcloud compute instances create instance-1</code> ?"</li>
</ul>
<p>Prompt that yields least privileged role suggestions:</p>
<ul>
<li>"What is the <em>smallest role</em> a service account needs to execute: <code dir="ltr" translate="no">gcloud datastore instances describe</code> ?"</li>
</ul></td>
</tr>
<tr class="even">
<td>Identifying roles for a task that includes transitive dependencies</td>
<td><ul>
<li>"I need to configure a Compute Engine instance to automatically scale based on CPU utilization. Which IAM roles should I grant to the service account?"</li>
</ul>
<p>Prompt that yields least privileged role suggestions:</p>
<ul>
<li>"I need to configure a Compute Engine instance to automatically scale based on CPU utilization. What are the <em>minimum permissions</em> I need to grant to a service account used by a Compute Engine instance autoscaler?"</li>
</ul></td>
</tr>
<tr class="odd">
<td>Identifying roles for a task that might require a combination of multiple granular roles</td>
<td><ul>
<li>"Provide users access only to a particular dataset in BigQuery. They shouldn't be able to create or delete datasets."</li>
</ul>
<p>Prompt that yields least privileged role suggestions:</p>
<ul>
<li>"What is the <em>most secure role</em> to give users read-only access to a single dataset in BigQuery, without allowing create or delete actions on any dataset?"</li>
</ul></td>
</tr>
</tbody>
</table>

## Best practices

To help Gemini provide the most accurate suggestions for your use case, we recommend that you adhere to the following best practices when drafting your prompt.

  - **Clearly describe your use case.** Avoid using vague language in your prompts. Be as clear as possible about what actions you want the principal to perform on which services and resource types. If you want Gemini to suggest the least privileged roles, be sure to create your prompt with [specific keywords](https://docs.cloud.google.com/iam/docs/role-picker-gemini#keywords) that describe your intent to adhere to the principle of least privilege.
    
    | Do                                                                                            | Don't                                              | Details                                                                                                                                                                                                                                                                                                                                                                |
    | --------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | "What role is required to execute SQL queries on a BigQuery table and read the data from it?" | "What role is required to execute SQL statements?" | SQL is a generic language used across multiple Google Cloud services. Without specifying the service or actions, Gemini can't suggest a precise role.                                                                                                                                                                                                                  |
    | "I need roles to start, stop, and reboot Compute Engine virtual machine instances."           | "I need to manage my virtual machines."            | The term *manage* is too vague. Manage could mean creating, deleting, updating, or viewing VMs. Clearly listing the specific actions to be performed (start, stop, reboot) and the exact resource type (Compute Engine virtual machine instances) yields more accurate suggestions.                                                                                    |
    | "I need to upload and download objects from a Cloud Storage bucket named `example-bucket` ."  | "Give me access to storage."                       | The term *Storage* alone could refer to various services like Cloud Storage, Filestore, or Persistent Disk. In addition, there are no actions specified. Without specifying the service (Cloud Storage), the resource type name ( `example-bucket` ), or the actions (upload and download objects), Gemini doesn't have enough information to suggest the right roles. |
    | "I need the least permissive role that provides list-only access to Secret Manager."          | "I need limited access to manage my secrets."      | The phrase *limited access* doesn't clearly define the required restrictions. *Manage my secrets* covers a broad range of actions (create, list, update, delete, access versions). Without using explicit keywords like *least privilege* , Gemini defaults to suggesting more general service-specific Admin, Editor, or Viewer roles.                                |
    

  - **Use official names.** Use the official names of Google Cloud services, resource types, and API operations in your prompt. If you are unsure about the official names of services, resource types, or API operations, we recommend consulting the official product documentation.
    
    | Do                                                                      | Don't                                                             | Details                                                                                                                                                                                                                      |
    | ----------------------------------------------------------------------- | ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | "What role do I need to update BigQuery datasets?"                      | "What role do I need to update Big query datasets?                | *BigQuery* is the official name of the product—not *Big query* .                                                                                                                                                             |
    | "What role is required to create a Cloud Storage bucket in my project?" | "What role is required to create a Storage bucket in my project?" | *Storage bucket* could refer to different resource types from services like Cloud Storage, Filestore, or Persistent Disk. Specifying the product name and the associated resource type will yield more accurate suggestions. |
    

### Keywords for least privileged roles

If you need role suggestions from Gemini that adhere to the principle of least privilege, you must use specific keywords in your prompt. The following is a non-exhaustive list of keywords that you can use to request least privileged roles:

  - *least permissive*
  - *most secure*
  - *smallest role*
  - *least privileged*
  - *minimum permissions*
  - *strictly granular*
  - *narrowest access*
  - *only the absolute minimum*
  - *only with the exact permissions*

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
