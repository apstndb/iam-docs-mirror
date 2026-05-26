---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec
title: PolicySpec
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#SCHEMA_REPRESENTATION)
  - [PolicyRule](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#PolicyRule)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#PolicyRule.SCHEMA_REPRESENTATION)
  - [StringValues](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#StringValues)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#StringValues.SCHEMA_REPRESENTATION)

Defines a Google Cloud policy specification which is used to specify constraints for configurations of Google Cloud resources.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;etag&quot;: string,&quot;updateTime&quot;: string,&quot;rules&quot;: [{object (PolicyRule)}],&quot;inheritFromParent&quot;: boolean,&quot;reset&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`etag`

`string`

An opaque tag indicating the current version of the policySpec, used for concurrency control.

This field is ignored if used in a `CreatePolicy` request.

When the policy is returned from either a `GetPolicy` or a `ListPolicies` request, this `etag` indicates the version of the current policySpec to use when executing a read-modify-write loop.

When the policy is returned from a `policies.getEffectivePolicy` request, the `etag` will be unset.

`updateTime`

` string ( Timestamp  ` format)

Output only. The time stamp this was previously updated. This represents the last time a call to `CreatePolicy` or `UpdatePolicy` was made for that policy.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`rules[]`

` object ( PolicyRule  ` )

In policies for boolean constraints, the following requirements apply:

  - There must be one and only one policy rule where condition is unset.
  - Boolean policy rules with conditions must set `enforced` to the opposite of the policy rule without a condition.
  - During policy evaluation, policy rules with conditions that are true for a target resource take precedence.

`inheritFromParent`

`boolean`

Determines the inheritance behavior for this policy.

If `inheritFromParent` is true, policy rules set higher up in the hierarchy (up to the closest root) are inherited and present in the effective policy. If it is false, then no rules are inherited, and this policy becomes the new root for evaluation. This field can be set only for policies which configure list constraints.

`reset`

`boolean`

Ignores policies set above this resource and restores the `constraintDefault` enforcement behavior of the specific constraint at this resource. This field can be set in policies for either list or boolean constraints. If set, `rules` must be empty and `inheritFromParent` must be set to false.

## PolicyRule

A rule used to express this policy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;condition&quot;: {object (Expr)},&quot;parameters&quot;: {object},// Union field kind can be only one of the following:&quot;values&quot;: {object (StringValues)},&quot;allowAll&quot;: boolean,&quot;denyAll&quot;: boolean,&quot;enforce&quot;: boolean// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`condition`

` object ( Expr  ` )

A condition that determines whether this rule is used to evaluate the policy.

When set, the `  google.type.Expr.expression  ` field must contain 1 to 10 subexpressions, joined by the `||` or `&&` operators. Each subexpression must use the `resource.matchTag()` , `resource.matchTagId()` , `resource.hasTagKey()` , or `resource.hasTagKeyId()` Common Expression Language (CEL) function.

The `resource.matchTag()` function takes the following arguments:

  - `key_name` : the namespaced name of the tag key, with the organization ID and a slash ( `/` ) as a prefix; for example, `123456789012/environment`
  - `value_name` : the short name of the tag value

For example: `resource.matchTag('123456789012/environment, 'prod')`

The `resource.matchTagId()` function takes the following arguments:

  - `key_id` : the permanent ID of the tag key; for example, `tagKeys/123456789012`
  - `value_id` : the permanent ID of the tag value; for example, `tagValues/567890123456`

For example: `resource.matchTagId('tagKeys/123456789012', 'tagValues/567890123456')`

The `resource.hasTagKey()` function takes the following argument:

  - `key_name` : the namespaced name of the tag key, with the organization ID and a slash ( `/` ) as a prefix; for example, `123456789012/environment`

For example: `resource.hasTagKey('123456789012/environment')`

The `resource.hasTagKeyId()` function takes the following arguments:

  - `key_id` : the permanent ID of the tag key; for example, `tagKeys/123456789012`

For example: `resource.hasTagKeyId('tagKeys/123456789012')`

`parameters`

` object ( Struct  ` format)

Optional. Required for managed constraints if parameters are defined. Passes parameter values when policy enforcement is enabled. Ensure that parameter value types match those defined in the constraint definition. For example:

    {
      "allowedLocations" : ["us-east1", "us-west1"],
      "allowAll" : true
    }

Union field `kind` .

`kind` can be only one of the following:

`values`

` object ( StringValues  ` )

List of values to be used for this policy rule. This field can be set only in policies for list constraints.

`allowAll`

`boolean`

Setting this to true means that all values are allowed. This field can be set only in policies for list constraints.

`denyAll`

`boolean`

Setting this to true means that all values are denied. This field can be set only in policies for list constraints.

`enforce`

`boolean`

If `true` , then the policy is enforced. If `false` , then any configuration is acceptable. This field can be set in policies for boolean constraints, custom constraints and managed constraints.

## StringValues

A message that holds specific allowed and denied values. This message can define specific values and subtrees of the Resource Manager resource hierarchy ( `Organizations` , `Folders` , `Projects` ) that are allowed or denied. This is achieved by using the `under:` and optional `is:` prefixes. The `under:` prefix is used to denote resource subtree values. The `is:` prefix is used to denote specific values, and is required only if the value contains a ":". Values prefixed with "is:" are treated the same as values with no prefix. Ancestry subtrees must be in one of the following formats:

  - `projects/<project-id>` (for example, `projects/tokyo-rain-123` )
  - `folders/<folder-id>` (for example, `folders/1234` )
  - `organizations/<organization-id>` (for example, `organizations/1234` )

The `supportsUnder` field of the associated `Constraint` defines whether ancestry prefixes can be used.

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
  &quot;allowedValues&quot;: [
    string
  ],
  &quot;deniedValues&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`allowedValues[]`

`string`

List of values allowed at this resource.

`deniedValues[]`

`string`

List of values denied at this resource.
