---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint
title: CustomConstraint
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint#SCHEMA_REPRESENTATION)

A custom constraint defined by customers which can *only* be applied to the given resource types and organization.

By creating a custom constraint, customers can apply policies of this custom constraint. *Creating a custom constraint itself does NOT apply any policy enforcement* .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;resourceTypes&quot;: [string],&quot;methodTypes&quot;: [enum (MethodType)],&quot;condition&quot;: string,&quot;actionType&quot;: enum (ActionType),&quot;displayName&quot;: string,&quot;description&quot;: string,&quot;updateTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. Name of the constraint. This is unique within the organization. Format of the name should be

  - `organizations/{organizationId}/customConstraints/{custom_constraint_id}`

Example: `organizations/123/customConstraints/custom.createOnlyE2TypeVms`

The max length is 70 characters and the minimum length is 1. Note that the prefix `organizations/{organizationId}/customConstraints/` is not counted.

`resourceTypes[]`

`string`

Immutable. The resource instance type on which this policy applies. Format will be of the form : `<service name>/<type>` Example:

  - `compute.googleapis.com/Instance` .

`methodTypes[]`

` enum ( MethodType  ` )

All the operations being applied for this constraint.

`condition`

`string`

A Common Expression Language (CEL) condition which is used in the evaluation of the constraint. For example: `resource.instanceName.matches("(production|test)_(.+_)?[\d]+")` or, `resource.management.auto_upgrade == true`

The max length of the condition is 1000 characters.

`actionType`

` enum ( ActionType  ` )

Allow or deny type.

`displayName`

`string`

One line display name for the UI. The max length of the displayName is 200 characters.

`description`

`string`

Detailed information about this custom policy constraint. The max length of the description is 2000 characters.

`updateTime`

` string ( Timestamp  ` format)

Output only. The last time this custom constraint was updated. This represents the last time that the `customConstraints.create` or `customConstraints.patch` methods were called.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .
