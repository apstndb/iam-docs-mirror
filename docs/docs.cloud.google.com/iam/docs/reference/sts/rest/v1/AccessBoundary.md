---
name: documents/docs.cloud.google.com/iam/docs/reference/sts/rest/v1/AccessBoundary
uri: https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/AccessBoundary
title: AccessBoundary
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/AccessBoundary#SCHEMA_REPRESENTATION)
  - [AccessBoundaryRule](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/AccessBoundary#AccessBoundaryRule)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/sts/rest/v1/AccessBoundary#AccessBoundaryRule.SCHEMA_REPRESENTATION)

An access boundary defines the upper bound of what a principal may access. It includes a list of access boundary rules that each defines the resource that may be allowed as well as permissions that may be used on those resources.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessBoundaryRules&quot;: [{object (AccessBoundaryRule)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessBoundaryRules[]`

` object ( AccessBoundaryRule  ` )

A list of access boundary rules which defines the upper bound of the permission a principal may carry. If multiple rules are specified, the effective access boundary is the union of all the access boundary rules attached.

One access boundary can contain at most 10 rules.

## AccessBoundaryRule

An access boundary rule defines an upper bound of IAM permissions on a single resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;availableResource&quot;: string,&quot;availablePermissions&quot;: [string],&quot;availabilityCondition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`availableResource`

`string`

The full resource name of a Google Cloud resource entity. The format definition is at <https://cloud.google.com/apis/design/resource_names> .

Example value: `//cloudresourcemanager.googleapis.com/projects/my-project` .

`availablePermissions[]`

`string`

A list of permissions that may be allowed for use on the specified resource.

The only supported values in the list are IAM roles, following the format of `  google.iam.v1.Binding.role  ` .

Example value: `inRole:roles/logging.viewer` for predefined roles and `inRole:organizations/{ORGANIZATION_ID}/roles/logging.viewer` for custom roles.

`availabilityCondition`

` object ( Expr  ` )

The availability condition further constrains the access allowed by the access boundary rule.

If the condition evaluates to `true` , then this access boundary rule will provide access to the specified resource, assuming the principal has the required permissions for the resource.

If the condition does not evaluate to `true` , then access to the specified resource will not be available. Note that all access boundary rules in an access boundary are evaluated together as a union. As such, another access boundary rule may allow access to the resource, even if this access boundary rule does not allow access.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

The maximum length of the `expression` field is 2048 characters.
