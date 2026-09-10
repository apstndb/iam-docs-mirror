---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles
title: 'REST Resource: organizations.roles'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Role](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role.SCHEMA_REPRESENTATION)
      - [RoleLaunchStage](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role.RoleLaunchStage)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#METHODS_SUMMARY)

## Resource: Role

A role in the Identity and Access Management API.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;title&quot;: string,&quot;description&quot;: string,&quot;includedPermissions&quot;: [string],&quot;stage&quot;: enum (RoleLaunchStage),&quot;etag&quot;: string,&quot;deleted&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The name of the role.

When `Role` is used in `roles.create` , the role name must not be set.

When `Role` is used in output and other input such as `roles.patch` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles.

`title`

`string`

Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.

`description`

`string`

Optional. A human-readable description for the role.

`includedPermissions[]`

`string`

The names of the permissions this role grants when bound in an IAM policy.

`stage`

` enum ( RoleLaunchStage  ` )

The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.

`etag`

`string ( bytes format)`

Used to perform a consistent read-modify-write.

A base64-encoded string.

`deleted`

`boolean`

The current deleted state of the role. This field is read only. It will be ignored in calls to roles.create and roles.patch.

### RoleLaunchStage

A stage representing a role's lifecycle phase.

Enums

`ALPHA`

The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role.

`BETA`

The user has indicated this role is currently in a Beta phase.

`GA`

The user has indicated this role is generally available.

`DEPRECATED`

The user has indicated this role is being deprecated.

`DISABLED`

This role is disabled and will not contribute permissions to any principals it is granted to in policies.

`EAP`

The user has indicated this role is currently in an EAP phase.

## Methods

### `            create           `

Creates a new custom `  Role  ` .

### `            delete           `

Deletes a custom `  Role  ` .

### `            get           `

Gets the definition of a `  Role  ` .

### `            list           `

Lists every predefined `  Role  ` that IAM supports, or every custom role that is defined for an organization or project.

### `            patch           `

Updates the definition of a custom `  Role  ` .

### `            undelete           `

Undeletes a custom `  Role  ` .
