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

**JSON representation**

```
{
  "etag": string,
  "updateTime": string,
  "rules": [
    {
      object (PolicyRule)
    }
  ],
  "inheritFromParent": boolean,
  "reset": boolean
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>An opaque tag indicating the current version of the policySpec, used for concurrency control.</p>
<p>This field is ignored if used in a <code>CreatePolicy</code> request.</p>
<p>When the policy is returned from either a <code>GetPolicy</code> or a <code>ListPolicies</code> request, this <code>etag</code> indicates the version of the current policySpec to use when executing a read-modify-write loop.</p>
<p>When the policy is returned from a <code>policies.getEffectivePolicy</code> request, the <code>etag</code> will be unset.</p></td>
</tr>
<tr class="even">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time stamp this was previously updated. This represents the last time a call to <code>CreatePolicy</code> or <code>UpdatePolicy</code> was made for that policy.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>rules[]</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#PolicyRule"><code>PolicyRule</code></a><code> )</code></p>
<p>In policies for boolean constraints, the following requirements apply:</p>
<ul>
<li>There must be one and only one policy rule where condition is unset.</li>
<li>Boolean policy rules with conditions must set <code>enforced</code> to the opposite of the policy rule without a condition.</li>
<li>During policy evaluation, policy rules with conditions that are true for a target resource take precedence.</li>
</ul></td>
</tr>
<tr class="even">
<td><code>inheritFromParent</code></td>
<td><p><code>boolean</code></p>
<p>Determines the inheritance behavior for this policy.</p>
<p>If <code>inheritFromParent</code> is true, policy rules set higher up in the hierarchy (up to the closest root) are inherited and present in the effective policy. If it is false, then no rules are inherited, and this policy becomes the new root for evaluation. This field can be set only for policies which configure list constraints.</p></td>
</tr>
<tr class="odd">
<td><code>reset</code></td>
<td><p><code>boolean</code></p>
<p>Ignores policies set above this resource and restores the <code>constraintDefault</code> enforcement behavior of the specific constraint at this resource. This field can be set in policies for either list or boolean constraints. If set, <code>rules</code> must be empty and <code>inheritFromParent</code> must be set to false.</p></td>
</tr>
</tbody>
</table>

## PolicyRule

A rule used to express this policy.

**JSON representation**

```
{
  "condition": {
    object (Expr)
  },
  "parameters": {
    object
  },

  // Union field kind can be only one of the following:
  "values": {
    object (StringValues)
  },
  "allowAll": boolean,
  "denyAll": boolean,
  "enforce": boolean
  // End of list of possible types for union field kind.
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Expr"><code>Expr</code></a><code> )</code></p>
<p>A condition that determines whether this rule is used to evaluate the policy.</p>
<p>When set, the <a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Expr#FIELDS.expression"><code>google.type.Expr.expression</code></a> field must contain 1 to 10 subexpressions, joined by the <code>||</code> or <code>&amp;&amp;</code> operators. Each subexpression must use the <code>resource.matchTag()</code> , <code>resource.matchTagId()</code> , <code>resource.hasTagKey()</code> , or <code>resource.hasTagKeyId()</code> Common Expression Language (CEL) function.</p>
<p>The <code>resource.matchTag()</code> function takes the following arguments:</p>
<ul>
<li><code>key_name</code> : the namespaced name of the tag key, with the organization ID and a slash ( <code>/</code> ) as a prefix; for example, <code>123456789012/environment</code></li>
<li><code>value_name</code> : the short name of the tag value</li>
</ul>
<p>For example: <code>resource.matchTag('123456789012/environment, 'prod')</code></p>
<p>The <code>resource.matchTagId()</code> function takes the following arguments:</p>
<ul>
<li><code>key_id</code> : the permanent ID of the tag key; for example, <code>tagKeys/123456789012</code></li>
<li><code>value_id</code> : the permanent ID of the tag value; for example, <code>tagValues/567890123456</code></li>
</ul>
<p>For example: <code>resource.matchTagId('tagKeys/123456789012', 'tagValues/567890123456')</code></p>
<p>The <code>resource.hasTagKey()</code> function takes the following argument:</p>
<ul>
<li><code>key_name</code> : the namespaced name of the tag key, with the organization ID and a slash ( <code>/</code> ) as a prefix; for example, <code>123456789012/environment</code></li>
</ul>
<p>For example: <code>resource.hasTagKey('123456789012/environment')</code></p>
<p>The <code>resource.hasTagKeyId()</code> function takes the following arguments:</p>
<ul>
<li><code>key_id</code> : the permanent ID of the tag key; for example, <code>tagKeys/123456789012</code></li>
</ul>
<p>For example: <code>resource.hasTagKeyId('tagKeys/123456789012')</code></p></td>
</tr>
<tr class="even">
<td><code>parameters</code></td>
<td><p><code>object ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#struct"><code>Struct</code></a><code> format)</code></p>
<p>Optional. Required for managed constraints if parameters are defined. Passes parameter values when policy enforcement is enabled. Ensure that parameter value types match those defined in the constraint definition. For example:</p>
<pre data-fenced=""><code>{
  &quot;allowedLocations&quot; : [&quot;us-east1&quot;, &quot;us-west1&quot;],
  &quot;allowAll&quot; : true
}</code></pre></td>
</tr>
<tr class="odd">
<td><p>Union field <code>kind</code> .</p>
<p><code>kind</code> can be only one of the following:</p></td>
<td></td>
</tr>
<tr class="even">
<td><code>values</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec#StringValues"><code>StringValues</code></a><code> )</code></p>
<p>List of values to be used for this policy rule. This field can be set only in policies for list constraints.</p></td>
</tr>
<tr class="odd">
<td><code>allowAll</code></td>
<td><p><code>boolean</code></p>
<p>Setting this to true means that all values are allowed. This field can be set only in policies for list constraints.</p></td>
</tr>
<tr class="even">
<td><code>denyAll</code></td>
<td><p><code>boolean</code></p>
<p>Setting this to true means that all values are denied. This field can be set only in policies for list constraints.</p></td>
</tr>
<tr class="odd">
<td><code>enforce</code></td>
<td><p><code>boolean</code></p>
<p>If <code>true</code> , then the policy is enforced. If <code>false</code> , then any configuration is acceptable. This field can be set in policies for boolean constraints, custom constraints and managed constraints.</p></td>
</tr>
</tbody>
</table>

## StringValues

A message that holds specific allowed and denied values. This message can define specific values and subtrees of the Resource Manager resource hierarchy ( `Organizations` , `Folders` , `Projects` ) that are allowed or denied. This is achieved by using the `under:` and optional `is:` prefixes. The `under:` prefix is used to denote resource subtree values. The `is:` prefix is used to denote specific values, and is required only if the value contains a ":". Values prefixed with "is:" are treated the same as values with no prefix. Ancestry subtrees must be in one of the following formats:

- `projects/<project-id>` (for example, `projects/tokyo-rain-123` )
- `folders/<folder-id>` (for example, `folders/1234` )
- `organizations/<organization-id>` (for example, `organizations/1234` )

The `supportsUnder` field of the associated `Constraint` defines whether ancestry prefixes can be used.

**JSON representation**

```
{
  "allowedValues": [
    string
  ],
  "deniedValues": [
    string
  ]
}
```

| Fields            |                                                   |
|-------------------|---------------------------------------------------|
| `allowedValues[]` | `string` List of values allowed at this resource. |
| `deniedValues[]`  | `string` List of values denied at this resource.  |
