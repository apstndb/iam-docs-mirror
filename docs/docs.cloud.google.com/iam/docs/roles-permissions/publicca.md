---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/publicca
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/publicca
title: Public Certificate Authority roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Public Certificate Authority. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Public Certificate Authority roles

| Role                                                                                                                                                 | Permissions                                                                                            |
|------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| Publicca Admin <sup>Beta</sup> ( `roles/ publicca.admin` ) Admin role for publicca                                                                   | `publicca. externalAccountKeys. create` `resourcemanager.projects.get` `resourcemanager.projects.list` |
| External Account Key Creator <sup>Beta</sup> ( `roles/ publicca.externalAccountKeyCreator` ) This role can create a new externalAccountKey resource. | `publicca. externalAccountKeys. create` `resourcemanager.projects.get` `resourcemanager.projects.list` |

## Public Certificate Authority permissions

| Permission                              | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `publicca. externalAccountKeys. create` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Publicca Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin) ( `roles/ publicca.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [External Account Key Creator](https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator) ( `roles/ publicca.externalAccountKeyCreator` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
