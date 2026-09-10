---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles
title: 'Method: projects.locations.global.recommendIamRoles'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.RecommendIamRolesResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#body.aspect)
  - [Prompt](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Prompt)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Prompt.SCHEMA_REPRESENTATION)
  - [Recommendation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Recommendation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Recommendation.SCHEMA_REPRESENTATION)
  - [Role](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Role)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#Role.SCHEMA_REPRESENTATION)
  - [RoleType](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#RoleType)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/rest/v1/projects.locations.global/recommendIamRoles#try-it)

Gets role suggestions for individual principals with AI assistance. To get the role suggestions, make sure the following pre-requisites are met:

  - [Vertex AI API](https://cloud.google.com/vertex-ai/docs/reference/rest) is enabled on the project.
  - The user has the `aiplatform.endpoints.predict` permission on the project. You can give this permissions to the user by granting the [Vertex AI Platform Express User](https://cloud.google.com/vertex-ai/docs/general/access-control#aiplatform.expressUser) role on the project.

### HTTP request

`POST https://policyassist.googleapis.com/v1/{parent=projects/*}/locations/global:recommendIamRoles`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The project on which the user wants to grant the suggested roles. Use one of the following formats:

  - `projects/{projectId}`
  - `projects/{project_number}`

### Request body

The request body contains data with the following structure:

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;prompt&quot;: {object (Prompt)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`prompt`

` object ( Prompt  ` )

Required. The user's prompt.

### Response body

Response to the recommendIamRoles method.

If successful, the response body contains data with the following structure:

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;summary&quot;: string,&quot;recommendations&quot;: [{object (Recommendation)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`summary`

`string`

A summary of the reasoning for the suggested roles. If no role suggestions are provided, this field displays the reasoning for no suggestions.

`recommendations[]`

` object ( Recommendation  ` )

A list of the suggested roles that are considered appropriate based on the user's prompt.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## Prompt

Prompt object defines the building block for the user's prompt.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;userInstructions&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`userInstructions`

`string`

Required. The user's prompt. For example, "Suggest a role that lets me view storage buckets.

## Recommendation

A role recommendation.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;intro&quot;: string,&quot;roles&quot;: [{object (Role)}],&quot;detailedReasoning&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`intro`

`string`

Short intro text displayed before the role recommendations.

`roles[]`

` object ( Role  ` )

A list of the suggested roles.

`detailedReasoning`

`string`

Detailed reasoning for why the suggested roles are considered appropriate.

## Role

An IAM role.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;roleType&quot;: enum (RoleType),&quot;grantableScopes&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The role name. For example, roles/storage.admin.

`roleType`

` enum ( RoleType  ` )

The type of role suggested. For example, a predefined role or a custom role.

`grantableScopes[]`

`string`

The list of scopes where the role can be granted. For example, a role can be granted at the project-, folder-, or organization-level.

## RoleType

RoleType defines a list of role types. Current supported values include predefined roles and custom roles.

Enums

`ROLE_TYPE_UNSPECIFIED`

Default value.

`ROLE_TYPE_PREDEFINED`

Predefined roles.

`ROLE_TYPE_CUSTOM`

Custom roles defined by the user.
