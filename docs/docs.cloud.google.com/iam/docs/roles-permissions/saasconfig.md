---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/saasconfig
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig
title: SaaS Config API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for SaaS Config API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## SaaS Config API roles

| Role                                                                                                    | Permissions                                                                                           |
|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| SaaS Config Viewer <sup>Beta</sup> ( `roles/ saasconfig.viewer` ) Read access to SaaS Config resources. | `resourcemanager.projects.get` `resourcemanager.projects.list` `saasconfig. featureFlagsConfigs. get` |

## SaaS Config API permissions

| Permission                             | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `saasconfig. featureFlagsConfigs. get` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [SaaS Config Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer) ( `roles/ saasconfig.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
