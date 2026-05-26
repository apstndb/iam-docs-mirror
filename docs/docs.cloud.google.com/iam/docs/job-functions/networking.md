---
name: documents/docs.cloud.google.com/iam/docs/job-functions/networking
uri: https://docs.cloud.google.com/iam/docs/job-functions/networking
title: IAM roles for Networking-related Job Functions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

> **Note:** Identity and Access Management (IAM) offers predefined roles that are tailored to specific job functions. If you want to give a user the necessary permissions to perform a specific job function in your organization, consider granting one of these predefined roles. To determine if IAM offers a predefined role for your use case, see [Predefined roles for job functions](https://docs.cloud.google.com/iam/docs/job-functions/roles-for-job-functions) .

This topic shows how to configure Identity and Access Management (IAM) permissions for networking scenarios. It provides guidance on what IAM roles to grant to the networking-related functional roles in your company for the scenarios. This content is mainly targeted at network administrators and employees who manage networking tasks for an organization. The scenarios described below all assume that a Google Cloud organization is configured.

This document does not explain in detail the networking roles and permissions. For a detailed description of roles and permissions associated with compute and networking APIs, read [Predefined Compute Engine IAM roles](https://docs.cloud.google.com/compute/docs/access/iam#predefinedroles) .

## Single team manages security & network for organization

In this scenario, a large organization has a central team that manages security and networking controls for the entire organization. Developers do not have permissions to make changes to any network or security settings defined by the security and networking team but they are granted permission to create resources such as virtual machines in shared subnets.

To facilitate this the organization makes use of a [shared VPC](https://docs.cloud.google.com/compute/docs/shared-vpc) (Virtual Private Cloud). A shared VPC allows creation of a VPC network of [RFC 1918](https://tools.ietf.org/html/rfc1918) IP spaces that associated projects (service projects) can then use. Developers using the associated projects can create VM instances in the shared VPC network spaces. The organization's network and security admins can create subnets, VPNs, and firewall rules usable by all the projects in the VPC network.

The tables below explain the IAM roles that need to be granted to the security and admin team and the development team, as well as the resource level at which the roles are granted.

Resource:

Organization

Roles:

Shared VPC Admin  
Network Admin  
Security Admin

Principal:

Security & network admin team

Resource:

Host Project

This role grants permission to use subnets that the shared VPC has shared.

Role:

Network user

Principal:

Developers

Resource:

Service project

Note this role allows the permission to use External IP addresses. See the note below for guidance on how to prevent this action.

Role:

compute.instanceAdmin

Principal:

Developers

> **Note:** If you need to prevent principals from associating external IP addresses with instances in a project, you can apply an [organization policy](https://docs.cloud.google.com/compute/docs/configure-ip-addresses#disableexternalip) . Organization administrators can override this policy when necessary.

For this scenario you need three separate allow policies: one for the organization, one for the host project, and one for the service projects.

The first allow policy, which needs to be attached at the organization level, grants the network and security team the roles they need to administer shared VPC host projects. This includes the ability to associate service projects with the host project. It also grants the network and security team the ability to manage all network and security resources in all projects in the organization.

    {
      "bindings": [
        {
          "role": "roles/compute.xpnAdmin",
          "members&quobal/workforcePools/example-pool/group/sec-net"
          ]
        },
        {
          "role":"roles/compute.netalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/sec-net"
          ]
        },
        {
          &q  "group:sec-net@example.comprincipalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/sec-net"
          ]    }  ]}

The second allow policy needs to be associated with the host project and enables the developers in the organization the ability to use the shared networks in the shared VPC host project.

    {
      "bindings": [
        {
          "role": "roles/compute.networkUser",
          "members":/workforcePools/example-pool/group/developers"
          ]    }  ]}

The third allow policy needs to be associated with each service project. This enables the developers using the project to manage instances in the service project and the ability to use the shared subnets in the host project.

You could place all service projects in a folder and set this particular allow policy at that level of the hierarchy. This would allow all projects created in that folder to inherit the permissions set at the folder within which the service project is created.

> **Note:** If using folders place all host and service projects for a given shared VPC setup within the same folder. The parent folder of the host project should be in the parent hierarchy of the service projects, so that the parent folder of the host project contains all the projects in the shared VPC setup.

You also need to grant the developers the Network User role in the service project.

    {
      "bindings": [
        {
          "role": "roles/compute.networkUser",
          "members":/workforcePools/example-pool/group/developers"
          ]
        },
        {
          "role": "roles/compute.instancet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/developers"
          ]    }  ]}

The best practice is to use groups to manage principals. In the example above, you would add the user IDs of the users who manage the security & network controls to the `sec-net` group, and developers into the `developers` group. When you need to modify who is able to carry out the function, you simply need to adjust the group membership, negating the need to update the allow policy.

## Separate network & security teams

In this scenario, a large organization has two central teams: one that manages security controls, and another that manages all other networking resources for the entire organization. Developers do not have permissions to make changes to any network or security settings defined by the security and networking team, but they are granted permission to create resources such as virtual machines in shared subnets.

As with the first scenario, a shared VPC will be used and the appropriate permissions configured for the three groups network, security, and developers.

The tables below explain the IAM roles that need to be granted to the security and admin team and the development team, as well as the resource level at which the roles are granted.

Resource:

Organization

Roles:

Shared VPC Admin  
Network Admin

Principal:

Network Admin team

Resource:

Organization

Roles:

Security Admin  
Organization Admin

Principal:

Security team

Resource:

Host Project

This role grants permission to use subnets that the shared VPC has shared.

Role:

Network user

Principal:

Developers

Resource:

Service project

Note this role allows the permission to use External IP addresses. See the note below for guidance on how to prevent this action.

Role:

compute.instanceAdmin

Principal:

Developers

> **Note:** If you need to prevent principals from associating external IP addresses with instances in a project, you can apply an [organization policy](https://docs.cloud.google.com/compute/docs/configure-ip-addresses#disableexternalip) . Organization administrators can override this policy when necessary.

For this scenario you need three separate allow policies: one for the organization, one for the host project, and one for the service projects.

The first allow policy, which needs to be attached at the organization level, grants the network team the roles they need to administer shared VPC host projects and to manage all network resources. This includes the ability to associate service projects with the host project. The network admin role also grants the network team the ability to view but not modify firewall rules. It also grants the security team the ability to set allow policies and manage firewall rules and SSL certificates in all projects in the organization.

    {
      "bindings": [
        {
          "role": "roles/compute.xpnAdmin",
          "members&quotal/workforcePools/example-pool/group/networks"
          ]
        },
        {
          "role": "roles/compute.netwlSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/networks"
          ]
        },
        {
          &qu"group:security@example.comprincipalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/security"
      ;,
          "members": [        "group:security@example.comprincipalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/security"      ]    }  ]}

The second allow policy needs to be associated with the host project. This allow policy enables the developers in the organization to use the shared networks in the shared VPC host project.

    {
      "bindings": [
        {
          "role": "roles/compute.networkUser",
          "members":/workforcePools/example-pool/group/developers"
          ]    }  ]}

The third allow policy needs to be associated with each service project. This enables the developers using the project to manage instances in the service project and the ability to use the shared subnets in the host project.

You could place all service projects in a folder and set this particular allow policy at that level of the hierarchy. This would allow all projects created in that folder to inherit the permissions set at the folder within which the service project is created.

> **Note:** You also need to grant the developers the network user role in the service project.

    {
      "bindings": [
        {
          "role": "roles/compute.networkUser",
          "members":/workforcePools/example-pool/group/developers"
          ]
        },
        {
          "role": "roles/compute.instancet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/developers"
          ]    }  ]}

## Each team can manage its own network

A digital native wants to give their development teams the ability to work in an autonomous manner. They have no central IT admin teams and trust their teams to manage all aspects of their projects.

Despite this, they equally want to be able to put in place some loose controls to allow them to adopt a more formal set-up as they grow and their product goes GA.

To implement this scenario, each team of developers is assigned its own folder. This structure ensures that individual projects created under the folder inherit the appropriate permissions, while allowing each team to work independently. Each team should still follow the principle of least privilege when it sets allow policies for its own resources.

Even though it will initially be the same team members who will be managing the network resources and the actual resources in the projects, creating separate groups for the logical duties is best practice.

This approach facilitates limiting access to those resources that temporary staff need or maybe new staff that need training up before they can modify network resources. It also allows the ability to change who has access to what resources without having to modify the allow policy every time a personnel change occurs.

Resource:

Folder

A service account can be used to create and own projects.

Roles:

Project creator  
Folder Admin

Principal:

Dev Teamleads  
Service account

> **Note:** Refer to [IAM roles for billing-related job functions](https://docs.cloud.google.com/iam/docs/job-functions/billing) for the IAM settings to allow a service account or user to associate a project with a billing account.

Resource:

Folder

Roles:

Network Admin

Security Admin

Principal:

Network & security team

Resource:

Folder

These roles allow the developers to manage all aspects of BigQuery and Compute engine.

Roles:

Instance Admin  
BigQuery Admin

Principal:

Developers

This requires an allow policy bound at each team's allocated folder.

    {
      "bindings": [
        {
          "role": "roles/resourcemanager.foldersAdmin",
          "members": [
     kforcePools/example-pool/group/devteamleads01",
            "serviam.gserviceaccount.comiceAccount:dev01-project-creator@shared-resources-proj."
          ]
        },
        {
          "role":"roles/resourcemanager.prcipalSet://iam.googleapis.com/locations/global/workforcePools/example-piam.gserviceaccount.comool/group/devteamleads01",
            "serviceAccount:dev01-project-creator@shared-resources-proj."
          ]
        },
    [
            "group:net-sec-dev01@example.comprincipalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/Admin",
          "members": [
            "group:net-sec-dev01@example.comprincipalSet://iam.googleapis.co  {
          "role": "roles/compute.instanceAdmin",
          "members": [
            "xample-pool/group/dev01"
          ]    },    {      "role": "roles/bigquery.admin",      "members": [        "group:dev01@example.comprincipalSet://iam.googleapis.com/locations/global/workforcePools/example-pool/group/dev01"      ]    }  ]}
