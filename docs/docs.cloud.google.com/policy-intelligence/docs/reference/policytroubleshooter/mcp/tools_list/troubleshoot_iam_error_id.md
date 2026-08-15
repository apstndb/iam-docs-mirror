---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_iam_error_id
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_iam_error_id
title: 'MCP Tools Reference: policytroubleshooter.googleapis.com'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

## Tool: `troubleshoot_iam_error_id`

Checks the access request associated with the error identifier and explains why the access is blocked by IAM policies.

If the error ID is not found by the backend, retry using an exponential backoff strategy. Start with an initial delay of `1m` , then retry. If the error ID is not found, double the delay time for each retry attempt (for example, `2m` , `4m` , `8m` , etc.). If the total duration from the first attempt exceeds `60 minutes` , terminate the process. Assume that the backend will not be able to provide an explanation for the error. It is possible that troubleshooting for this specific error ID is not supported or there is an issue on the backend.

If you are an agent that does not have the capability to wait or understand time, do not retry. Instead, return an error stating that waiting is required to retry finding the error ID, but your environment does not support waiting or tracking time.

The following sample demonstrate how to use `curl` to invoke the `troubleshoot_iam_error_id` MCP tool.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>Curl Request</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" data-syntax="Bash" translate="no"><code>                  
curl --location &#39;https://policytroubleshooter.googleapis.com/mcp&#39; \
--header &#39;content-type: application/json&#39; \
--header &#39;accept: application/json, text/event-stream&#39; \
--data &#39;{
  &quot;method&quot;: &quot;tools/call&quot;,
  &quot;params&quot;: {
    &quot;name&quot;: &quot;troubleshoot_iam_error_id&quot;,
    &quot;arguments&quot;: {
      // provide these details according to the tool&#39;s MCP specification
    }
  },
  &quot;jsonrpc&quot;: &quot;2.0&quot;,
  &quot;id&quot;: 1
}&#39;
                </code></pre></td>
</tr>
</tbody>
</table>

## Input Schema

Request to troubleshoot access denial with the IAM error identifier.

### TroubleshootIamPolicyErrorRequest

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field kind can be only one of the following:&quot;errorInfoId&quot;: string// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `kind` . The unique identifier for the access denied request. `kind` can be only one of the following:

`errorInfoId`

`string`

This identifier is returned in the `ErrorInfo.metadata` with key 'error\_info\_id' when an access requests is denied by the IAM service.

## Output Schema

Response for troubleshoot access denial with the IAM error identifier.

### TroubleshootIamPolicyErrorResponse

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;overallAccessState&quot;: enum (OverallAccessState),&quot;accessContext&quot;: {object (AccessContext)},&quot;allowPolicyExplanation&quot;: {object (AllowPolicyExplanation)},&quot;denyPolicyExplanation&quot;: {object (DenyPolicyExplanation)},&quot;pabPolicyExplanation&quot;: {object (PABPolicyExplanation)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`overallAccessState`

` enum ( OverallAccessState  ` )

Indicates whether the principal has the permission to access the resource, based on evaluating all types of the applicable IAM policies.

`accessContext`

` object ( AccessContext  ` )

The access context associated with the ErrorInfoId.

`allowPolicyExplanation`

` object ( AllowPolicyExplanation  ` )

An explanation of how the applicable IAM allow policies affect the final access state.

`denyPolicyExplanation`

` object ( DenyPolicyExplanation  ` )

An explanation of how the applicable IAM deny policies affect the final access state.

`pabPolicyExplanation`

` object ( PABPolicyExplanation  ` )

An explanation of how the applicable principal access boundary policies affect the final access state.

### AccessContext

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;principal&quot;: string,&quot;permission&quot;: string,// Union field resource can be only one of the following:&quot;name&quot;: string,&quot;parent&quot;: string// End of list of possible types for union field resource.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principal`

`string`

The email address of the principal who requested access. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` .

The principal must be a Google Account or a service account. Other types of principals are not supported.

`permission`

`string`

Required. The IAM permission name provided by the user in the access denied request.

Union field `resource` . The resource for which access was requested or its parent. `resource` can be only one of the following:

`name`

`string`

The relative resource name, not including the / prefix. For example, `projects/project-id` , `projects/-/serviceAccounts/11112222`

`parent`

`string`

The full resource name of the parent where IAM policy is configured. For example, `//cloudresourcemanager.googleapis.com/folders/444446666`

### AllowPolicyExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;allowAccessState&quot;: enum (AllowAccessState),&quot;explainedPolicies&quot;: [{object (ExplainedAllowPolicy)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`allowAccessState`

` enum ( AllowAccessState  ` )

Indicates whether the principal has the specified permission for the specified resource, based on evaluating all applicable IAM allow policies.

`explainedPolicies[]`

` object ( ExplainedAllowPolicy  ` )

List of IAM allow policies that were evaluated to check the principal's permissions, with annotations to indicate how each policy contributed to the final result.

The list of policies includes the policy for the resource itself, as well as allow policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project.

To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the allow policy type to the overall access state.

### ExplainedAllowPolicy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;allowAccessState&quot;: enum (AllowAccessState),&quot;fullResourceName&quot;: string,&quot;bindingExplanations&quot;: [{object (AllowBindingExplanation)}],&quot;relevance&quot;: enum (HeuristicRelevance),&quot;policy&quot;: {object (Policy)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`allowAccessState`

` enum ( AllowAccessState  ` )

Required. Indicates whether *this policy* provides the specified permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the `  TroubleshootIamPolicyResponse  ` .

`fullResourceName`

`string`

The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

If the sender of the request does not have access to the policy, this field is omitted.

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`bindingExplanations[]`

` object ( AllowBindingExplanation  ` )

Details about how each role binding in the policy affects the principal's ability, or inability, to use the permission for the resource. The order of the role bindings matches the role binding order in the policy.

If the sender of the request does not have access to the policy, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall access state in the `  TroubleshootIamPolicyResponse  ` .

If the sender of the request does not have access to the policy, this field is omitted.

`policy`

` object ( Policy  ` )

The IAM allow policy attached to the resource.

If the sender of the request does not have access to the policy, this field is empty.

### AllowBindingExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;allowAccessState&quot;: enum (AllowAccessState),&quot;role&quot;: string,&quot;rolePermission&quot;: enum (RolePermissionInclusionState),&quot;rolePermissionRelevance&quot;: enum (HeuristicRelevance),&quot;combinedMembership&quot;: {object (AnnotatedAllowMembership)},&quot;memberships&quot;: {string: {object (AnnotatedAllowMembership)},...},&quot;relevance&quot;: enum (HeuristicRelevance),&quot;condition&quot;: {object (Expr)},&quot;conditionExplanation&quot;: {object (ConditionExplanation)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`allowAccessState`

` enum ( AllowAccessState  ` )

Required. Indicates whether *this role binding* gives the specified permission to the specified principal on the specified resource.

This field does *not* indicate whether the principal actually has the permission on the resource. There might be another role binding that overrides this role binding. To determine whether the principal actually has the permission, use the `overall_access_state` field in the `  TroubleshootIamPolicyResponse  ` .

`role`

`string`

The role that this role binding grants. For example, `roles/compute.admin` .

For a complete list of predefined IAM roles, as well as the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .

`rolePermission`

` enum ( RolePermissionInclusionState  ` )

Indicates whether the role granted by this role binding contains the specified permission.

`rolePermissionRelevance`

` enum ( HeuristicRelevance  ` )

The relevance of the permission's existence, or nonexistence, in the role to the overall determination for the entire policy.

`combinedMembership`

` object ( AnnotatedAllowMembership  ` )

The combined result of all memberships. Indicates if the principal is included in any role binding, either directly or indirectly.

`memberships`

` map (key: string, value: object ( AnnotatedAllowMembership  ` ))

Indicates whether each role binding includes the principal specified in the request, either directly or indirectly. Each key identifies a principal in the role binding, and each value indicates whether the principal in the role binding includes the principal in the request.

For example, suppose that a role binding includes the following principals:

  - `user:alice@example.com`
  - `group:product-eng@example.com`

You want to troubleshoot access for `user:bob@example.com` . This user is a member of the group `group:product-eng@example.com` .

For the first principal in the role binding, the key is `user:alice@example.com` , and the `membership` field in the value is set to `NOT_INCLUDED` .

For the second principal in the role binding, the key is `group:product-eng@example.com` , and the `membership` field in the value is set to `INCLUDED` .

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this role binding to the overall determination for the entire policy.

`condition`

` object ( Expr  ` )

A condition expression that specifies when the role binding grants access.

To learn about IAM Conditions, see <https://cloud.google.com/iam/help/conditions/overview> .

`conditionExplanation`

` object ( ConditionExplanation  ` )

Condition evaluation state for this role binding.

### AnnotatedAllowMembership

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;membership&quot;: enum (MembershipMatchingState),&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`membership`

` enum ( MembershipMatchingState  ` )

Indicates whether the role binding includes the principal.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the principal's status to the overall determination for the role binding.

### MembershipsEntry

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: string,&quot;value&quot;: {object (AnnotatedAllowMembership)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` object ( AnnotatedAllowMembership  ` )

### Expr

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
  &quot;expression&quot;: string,
  &quot;title&quot;: string,
  &quot;description&quot;: string,
  &quot;location&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`expression`

`string`

Textual representation of an expression in Common Expression Language syntax.

`title`

`string`

Optional. Title for the expression, i.e. a short string describing its purpose. This can be used e.g. in UIs which allow to enter the expression.

`description`

`string`

Optional. Description of the expression. This is a longer text which describes the expression, e.g. when hovered over it in a UI.

`location`

`string`

Optional. String indicating the location of the expression for error reporting, e.g. a file name and a position in the file.

### ConditionExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;value&quot;: value,&quot;errors&quot;: [{object (Status)}],&quot;evaluationStates&quot;: [{object (EvaluationState)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`value`

` value ( Value  ` format)

Value of the condition.

`errors[]`

` object ( Status  ` )

Any errors that prevented complete evaluation of the condition expression.

`evaluationStates[]`

` object ( EvaluationState  ` )

The value of each statement of the condition expression. The value can be `true` , `false` , or `null` . The value is `null` if the statement can't be evaluated.

### Value

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field kind can be only one of the following:&quot;nullValue&quot;: null,&quot;numberValue&quot;: number,&quot;stringValue&quot;: string,&quot;boolValue&quot;: boolean,&quot;structValue&quot;: {object},&quot;listValue&quot;: array// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `kind` . The kind of value. `kind` can be only one of the following:

`nullValue`

`null`

Represents a JSON `null` .

`numberValue`

`number`

Represents a JSON number. Must not be `NaN` , `Infinity` or `-Infinity` , since those are not supported in JSON. This also cannot represent large Int64 values, since JSON format generally does not support them in its number type.

`stringValue`

`string`

Represents a JSON string.

`boolValue`

`boolean`

Represents a JSON boolean ( `true` or `false` literal in JSON).

`structValue`

` object ( Struct  ` format)

Represents a JSON object.

`listValue`

` array ( ListValue  ` format)

Represents a JSON array.

### Struct

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
  &quot;fields&quot;: {
    string: value,
    ...
  }
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`fields`

` map (key: string, value: value ( Value  ` format))

Unordered map of dynamically typed values.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

### FieldsEntry

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
  &quot;key&quot;: string,
  &quot;value&quot;: value
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` value ( Value  ` format)

### ListValue

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
  &quot;values&quot;: [
    value
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`values[]`

` value ( Value  ` format)

Repeated field of dynamically typed values.

### Status

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
  &quot;code&quot;: integer,
  &quot;message&quot;: string,
  &quot;details&quot;: [
    {
      &quot;@type&quot;: string,
      field1: ...,
      ...
    }
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`code`

`integer`

The status code, which should be an enum value of `google.rpc.Code` .

`message`

`string`

A developer-facing error message, which should be in English. Any user-facing error message should be localized and sent in the `google.rpc.Status.details` field, or localized by the client.

`details[]`

`object`

A list of messages that carry the error details. There is a common set of message types for APIs to use.

An object containing fields of an arbitrary type. An additional field `"@type"` contains a URI identifying the type. Example: `{ "id": 1234, "@type": "types.example.com/standard/id" }` .

### Any

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
  &quot;typeUrl&quot;: string,
  &quot;value&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`typeUrl`

`string`

Identifies the type of the serialized Protobuf message with a URI reference consisting of a prefix ending in a slash and the fully-qualified type name.

Example: type.googleapis.com/google.protobuf.StringValue

This string must contain at least one `/` character, and the content after the last `/` must be the fully-qualified name of the type in canonical form, without a leading dot. Do not write a scheme on these URI references so that clients do not attempt to contact them.

The prefix is arbitrary and Protobuf implementations are expected to simply strip off everything up to and including the last `/` to identify the type. `type.googleapis.com/` is a common default prefix that some legacy implementations require. This prefix does not indicate the origin of the type, and URIs containing it are not expected to respond to any requests.

All type URL strings must be legal URI references with the additional restriction (for the text format) that the content of the reference must consist only of alphanumeric characters, percent-encoded escapes, and characters in the following set (not including the outer backticks): `/-.~_!$&()*+,;=` . Despite our allowing percent encodings, implementations should not unescape them to prevent confusion with existing parsers. For example, `type.googleapis.com%2FFoo` should be rejected.

In the original design of `Any` , the possibility of launching a type resolution service at these type URLs was considered but Protobuf never implemented one and considers contacting these URLs to be problematic and a potential security issue. Do not attempt to contact type URLs.

`value`

`string ( bytes format)`

Holds a Protobuf serialization of the type described by type\_url.

A base64-encoded string.

### EvaluationState

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;start&quot;: integer,&quot;end&quot;: integer,&quot;value&quot;: value,&quot;errors&quot;: [{object (Status)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`start`

`integer`

Start position of an expression in the condition, by character.

`end`

`integer`

End position of an expression in the condition, by character, end included, for example: the end position of the first part of `a==b || c==d` would be 4.

`value`

` value ( Value  ` format)

Value of this expression.

`errors[]`

` object ( Status  ` )

Any errors that prevented complete evaluation of the condition expression.

### Policy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;version&quot;: integer,&quot;bindings&quot;: [{object (Binding)}],&quot;auditConfigs&quot;: [{object (AuditConfig)}],&quot;etag&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`version`

`integer`

Specifies the format of the policy.

Valid values are `0` , `1` , and `3` . Requests that specify an invalid value are rejected.

Any operation that affects conditional role bindings must specify version `3` . This requirement applies to the following operations:

  - Getting a policy that includes a conditional role binding
  - Adding a conditional role binding to a policy
  - Changing a conditional role binding in a policy
  - Removing any role binding, with or without a condition, from a policy that includes conditions

**Important:** If you use IAM Conditions, you must include the `etag` field whenever you call `setIamPolicy` . If you omit this field, then IAM allows you to overwrite a version `3` policy with a version `1` policy, and all of the conditions in the version `3` policy are lost.

If a policy does not include any conditions, operations on that policy may specify any valid version or leave the field unset.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

`bindings[]`

` object ( Binding  ` )

Associates a list of `members` , or principals, with a `role` . Optionally, may specify a `condition` that determines how and when the `bindings` are applied. Each of the `bindings` must contain at least one principal.

The `bindings` in a `Policy` can refer to up to 1,500 principals; up to 250 of these principals can be Google groups. Each occurrence of a principal counts towards these limits. For example, if the `bindings` grant 50 different roles to `user:alice@example.com` , and not to any other principal, then you can add another 1,450 principals to the `bindings` in the `Policy` .

`auditConfigs[]`

` object ( AuditConfig  ` )

Specifies cloud audit logging configuration for this policy.

`etag`

`string ( bytes format)`

`etag` is used for optimistic concurrency control as a way to help prevent simultaneous updates of a policy from overwriting each other. It is strongly suggested that systems make use of the `etag` in the read-modify-write cycle to perform policy updates in order to avoid race conditions: An `etag` is returned in the response to `getIamPolicy` , and systems are expected to put that etag in the request to `setIamPolicy` to ensure that their change will be applied to the same version of the policy.

**Important:** If you use IAM Conditions, you must include the `etag` field whenever you call `setIamPolicy` . If you omit this field, then IAM allows you to overwrite a version `3` policy with a version `1` policy, and all of the conditions in the version `3` policy are lost.

A base64-encoded string.

### Binding

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;role&quot;: string,&quot;members&quot;: [string],&quot;condition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`role`

`string`

Role that is assigned to the list of `members` , or principals. For example, `roles/viewer` , `roles/editor` , or `roles/owner` .

For an overview of the IAM roles and permissions, see the [IAM documentation](https://cloud.google.com/iam/docs/roles-overview) . For a list of the available pre-defined roles, see [here](https://cloud.google.com/iam/docs/understanding-roles) .

`members[]`

`string`

Specifies the principals requesting access for a Google Cloud resource. `members` can have the following values:

  - `allUsers` : A special identifier that represents anyone who is on the internet; with or without a Google account.

  - `allAuthenticatedUsers` : A special identifier that represents anyone who is authenticated with a Google account or a service account. Does not include identities that come from external identity providers (IdPs) through identity federation.

  - `user:{emailid}` : An email address that represents a specific Google account. For example, `alice@example.com` .

<!-- end list -->

  - `serviceAccount:{emailid}` : An email address that represents a Google service account. For example, `my-other-app@appspot.gserviceaccount.com` .

  - `serviceAccount:{projectid}.svc.id.goog[{namespace}/{kubernetes-sa}]` : An identifier for a [Kubernetes service account](https://cloud.google.com/kubernetes-engine/docs/how-to/kubernetes-service-accounts) . For example, `my-project.svc.id.goog[my-namespace/my-kubernetes-sa]` .

  - `group:{emailid}` : An email address that represents a Google group. For example, `admins@example.com` .

<!-- end list -->

  - `domain:{domain}` : The G Suite domain (primary) that represents all the users of that domain. For example, `google.com` or `example.com` .

<!-- end list -->

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `deleted:user:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a user that has been recently deleted. For example, `alice@example.com?uid=123456789012345678901` . If the user is recovered, this value reverts to `user:{emailid}` and the recovered user retains the role in the binding.

  - `deleted:serviceAccount:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a service account that has been recently deleted. For example, `my-other-app@appspot.gserviceaccount.com?uid=123456789012345678901` . If the service account is undeleted, this value reverts to `serviceAccount:{emailid}` and the undeleted service account retains the role in the binding.

  - `deleted:group:{emailid}?uid={uniqueid}` : An email address (plus unique identifier) representing a Google group that has been recently deleted. For example, `admins@example.com?uid=123456789012345678901` . If the group is recovered, this value reverts to `group:{emailid}` and the recovered group retains the role in the binding.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`condition`

` object ( Expr  ` )

The condition that is associated with this binding.

If the condition evaluates to `true` , then this binding applies to the current request.

If the condition evaluates to `false` , then this binding does not apply to the current request. However, a different role binding might grant the same role to one or more of the principals in this binding.

To learn which resources support conditions in their IAM policies, see the [IAM documentation](https://cloud.google.com/iam/help/conditions/resource-policies) .

### AuditConfig

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;service&quot;: string,&quot;auditLogConfigs&quot;: [{object (AuditLogConfig)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`service`

`string`

Specifies a service that will be enabled for audit logging. For example, `storage.googleapis.com` , `cloudsql.googleapis.com` . `allServices` is a special value that covers all services.

`auditLogConfigs[]`

` object ( AuditLogConfig  ` )

The configuration for logging of each type of permission.

### AuditLogConfig

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;logType&quot;: enum (LogType),&quot;exemptedMembers&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`logType`

` enum ( LogType  ` )

The log type that this config enables.

`exemptedMembers[]`

`string`

Specifies the identities that do not cause logging for this type of permission. Follows the same format of `Binding.members` .

### DenyPolicyExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;denyAccessState&quot;: enum (DenyAccessState),&quot;explainedResources&quot;: [{object (ExplainedDenyResource)}],&quot;relevance&quot;: enum (HeuristicRelevance),&quot;permissionDeniable&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`denyAccessState`

` enum ( DenyAccessState  ` )

Indicates whether the principal is denied the specified permission for the specified resource, based on evaluating all applicable IAM deny policies.

`explainedResources[]`

` object ( ExplainedDenyResource  ` )

List of resources with IAM deny policies that were evaluated to check the principal's denied permissions, with annotations to indicate how each policy contributed to the final result.

The list of resources includes the policy for the resource itself, as well as policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project. The order of the resources starts from the resource and climbs up the resource hierarchy.

To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the deny policy result to the overall access state.

`permissionDeniable`

`boolean`

Indicates whether the permission to troubleshoot is supported in deny policies.

### ExplainedDenyResource

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;denyAccessState&quot;: enum (DenyAccessState),&quot;fullResourceName&quot;: string,&quot;explainedPolicies&quot;: [{object (ExplainedDenyPolicy)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`denyAccessState`

` enum ( DenyAccessState  ` )

Required. Indicates whether any policies attached to *this resource* deny the specific permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the `  TroubleshootIamPolicyResponse  ` .

`fullResourceName`

`string`

The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

If the sender of the request does not have access to the policy, this field is omitted.

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`explainedPolicies[]`

` object ( ExplainedDenyPolicy  ` )

List of IAM deny policies that were evaluated to check the principal's denied permissions, with annotations to indicate how each policy contributed to the final result.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall access state in the `  TroubleshootIamPolicyResponse  ` .

If the sender of the request does not have access to the policy, this field is omitted.

### ExplainedDenyPolicy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;denyAccessState&quot;: enum (DenyAccessState),&quot;policy&quot;: {object (Policy)},&quot;ruleExplanations&quot;: [{object (DenyRuleExplanation)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`denyAccessState`

` enum ( DenyAccessState  ` )

Required. Indicates whether *this policy* denies the specified permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the `  TroubleshootIamPolicyResponse  ` .

`policy`

` object ( Policy  ` )

The IAM deny policy attached to the resource.

If the sender of the request does not have access to the policy, this field is omitted.

`ruleExplanations[]`

` object ( DenyRuleExplanation  ` )

Details about how each rule in the policy affects the principal's inability to use the permission for the resource. The order of the deny rule matches the order of the rules in the deny policy.

If the sender of the request does not have access to the policy, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall access state in the `  TroubleshootIamPolicyResponse  ` .

If the sender of the request does not have access to the policy, this field is omitted.

### Policy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;kind&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;etag&quot;: string,&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;deleteTime&quot;: string,&quot;rules&quot;: [{object (PolicyRule)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachment_point}/denypolicies/{policy_id}`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID.

`uid`

`string`

Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.

`kind`

`string`

Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .

`displayName`

`string`

A user-specified description of the `Policy` . This value can be up to 63 characters.

`annotations`

`map (key: string, value: string)`

A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`etag`

`string`

An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another.

If this field is present in a `CreatePolicyRequest` , the value is ignored.

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was last updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`deleteTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`rules[]`

` object ( PolicyRule  ` )

A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .

### AnnotationsEntry

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
  &quot;key&quot;: string,
  &quot;value&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

`string`

### Timestamp

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
  &quot;seconds&quot;: string,
  &quot;nanos&quot;: integer
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`seconds`

`string ( int64 format)`

Represents seconds of UTC time since Unix epoch 1970-01-01T00:00:00Z. Must be between -62135596800 and 253402300799 inclusive (which corresponds to 0001-01-01T00:00:00Z to 9999-12-31T23:59:59Z).

`nanos`

`integer`

Non-negative fractions of a second at nanosecond resolution. This field is the nanosecond portion of the duration, not an alternative to seconds. Negative second values with fractions must still have non-negative nanos values that count forward in time. Must be between 0 and 999,999,999 inclusive.

### PolicyRule

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;description&quot;: string,// Union field kind can be only one of the following:&quot;denyRule&quot;: {object (DenyRule)}// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`description`

`string`

A user-specified description of the rule. This value can be up to 256 characters.

Union field `kind` .

`kind` can be only one of the following:

`denyRule`

` object ( DenyRule  ` )

A rule for a deny policy.

### DenyRule

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;deniedPrincipals&quot;: [string],&quot;exceptionPrincipals&quot;: [string],&quot;deniedPermissions&quot;: [string],&quot;exceptionPermissions&quot;: [string],&quot;denialCondition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`deniedPrincipals[]`

`string`

The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{group_id}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/public:all` : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.

  - `principalSet://goog/cloudIdentityCustomerId/{customer_id}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAccount` : All service accounts grouped under a resource (project, folder, or organization).

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAgent` : All service agents grouped under a resource (project, folder, or organization).

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{group_id}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`exceptionPrincipals[]`

`string`

The identities that are excluded from the deny rule, even if they are listed in the `denied_principals` . For example, you could add a Google group to the `denied_principals` , then exclude specific users who belong to that group.

This field can contain the same values as the `denied_principals` field, excluding `principalSet://goog/public:all` , which represents all users on the internet.

`deniedPermissions[]`

`string`

The permissions that are explicitly denied by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. For example, `iam.googleapis.com/roles.list` .

`exceptionPermissions[]`

`string`

Specifies the permissions that this rule excludes from the set of denied permissions given by `denied_permissions` . If a permission appears in `denied_permissions` *and* in `exception_permissions` then it will *not* be denied.

The excluded permissions can be specified using the same syntax as `denied_permissions` .

`denialCondition`

` object ( Expr  ` )

The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to `true` , then the deny rule is applied; otherwise, the deny rule is not applied.

Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.

The condition can use CEL functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) . Other functions and operators are not supported.

### DenyRuleExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;denyAccessState&quot;: enum (DenyAccessState),&quot;combinedDeniedPermission&quot;: {object (AnnotatedPermissionMatching)},&quot;deniedPermissions&quot;: {string: {object (AnnotatedPermissionMatching)},...},&quot;combinedExceptionPermission&quot;: {object (AnnotatedPermissionMatching)},&quot;exceptionPermissions&quot;: {string: {object (AnnotatedPermissionMatching)},...},&quot;combinedDeniedPrincipal&quot;: {object (AnnotatedDenyPrincipalMatching)},&quot;deniedPrincipals&quot;: {string: {object (AnnotatedDenyPrincipalMatching)},...},&quot;combinedExceptionPrincipal&quot;: {object (AnnotatedDenyPrincipalMatching)},&quot;exceptionPrincipals&quot;: {string: {object (AnnotatedDenyPrincipalMatching)},...},&quot;relevance&quot;: enum (HeuristicRelevance),&quot;condition&quot;: {object (Expr)},&quot;conditionExplanation&quot;: {object (ConditionExplanation)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`denyAccessState`

` enum ( DenyAccessState  ` )

Required. Indicates whether *this rule* denies the specified permission to the specified principal for the specified resource.

This field does *not* indicate whether the principal is actually denied on the permission for the resource. There might be another rule that overrides this rule. To determine whether the principal actually has the permission, use the `overall_access_state` field in the `  TroubleshootIamPolicyResponse  ` .

`combinedDeniedPermission`

` object ( AnnotatedPermissionMatching  ` )

Indicates whether the permission in the request is listed as a denied permission in the deny rule.

`deniedPermissions`

` map (key: string, value: object ( AnnotatedPermissionMatching  ` ))

Lists all denied permissions in the deny rule and indicates whether each permission matches the permission in the request.

Each key identifies a denied permission in the rule, and each value indicates whether the denied permission matches the permission in the request.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`combinedExceptionPermission`

` object ( AnnotatedPermissionMatching  ` )

Indicates whether the permission in the request is listed as an exception permission in the deny rule.

`exceptionPermissions`

` map (key: string, value: object ( AnnotatedPermissionMatching  ` ))

Lists all exception permissions in the deny rule and indicates whether each permission matches the permission in the request.

Each key identifies a exception permission in the rule, and each value indicates whether the exception permission matches the permission in the request.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`combinedDeniedPrincipal`

` object ( AnnotatedDenyPrincipalMatching  ` )

Indicates whether the principal is listed as a denied principal in the deny rule, either directly or through membership in a principal set.

`deniedPrincipals`

` map (key: string, value: object ( AnnotatedDenyPrincipalMatching  ` ))

Lists all denied principals in the deny rule and indicates whether each principal matches the principal in the request, either directly or through membership in a principal set.

Each key identifies a denied principal in the rule, and each value indicates whether the denied principal matches the principal in the request.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`combinedExceptionPrincipal`

` object ( AnnotatedDenyPrincipalMatching  ` )

Indicates whether the principal is listed as an exception principal in the deny rule, either directly or through membership in a principal set.

`exceptionPrincipals`

` map (key: string, value: object ( AnnotatedDenyPrincipalMatching  ` ))

Lists all exception principals in the deny rule and indicates whether each principal matches the principal in the request, either directly or through membership in a principal set.

Each key identifies a exception principal in the rule, and each value indicates whether the exception principal matches the principal in the request.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this role binding to the overall determination for the entire policy.

`condition`

` object ( Expr  ` )

A condition expression that specifies when the deny rule denies the principal access.

To learn about IAM Conditions, see <https://cloud.google.com/iam/help/conditions/overview> .

`conditionExplanation`

` object ( ConditionExplanation  ` )

Condition evaluation state for this role binding.

### AnnotatedPermissionMatching

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;permissionMatchingState&quot;: enum (PermissionPatternMatchingState),&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`permissionMatchingState`

` enum ( PermissionPatternMatchingState  ` )

Indicates whether the permission in the request is denied by the deny rule.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the permission status to the overall determination for the rule.

### DeniedPermissionsEntry

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: string,&quot;value&quot;: {object (AnnotatedPermissionMatching)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` object ( AnnotatedPermissionMatching  ` )

### ExceptionPermissionsEntry

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: string,&quot;value&quot;: {object (AnnotatedPermissionMatching)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` object ( AnnotatedPermissionMatching  ` )

### AnnotatedDenyPrincipalMatching

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;membership&quot;: enum (MembershipMatchingState),&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`membership`

` enum ( MembershipMatchingState  ` )

Indicates whether the principal is listed as a denied principal in the deny rule, either directly or through membership in a principal set.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the principal's status to the overall determination for the role binding.

### DeniedPrincipalsEntry

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: string,&quot;value&quot;: {object (AnnotatedDenyPrincipalMatching)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` object ( AnnotatedDenyPrincipalMatching  ` )

### ExceptionPrincipalsEntry

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;key&quot;: string,&quot;value&quot;: {object (AnnotatedDenyPrincipalMatching)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

` object ( AnnotatedDenyPrincipalMatching  ` )

### PABPolicyExplanation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;principalAccessBoundaryAccessState&quot;: enum (PABAccessState),&quot;explainedBindingsAndPolicies&quot;: [{object (ExplainedPABBindingAndPolicy)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principalAccessBoundaryAccessState`

` enum ( PABAccessState  ` )

Output only. Indicates whether the principal is allowed to access specified resource, based on evaluating all applicable principal access boundary bindings and policies.

`explainedBindingsAndPolicies[]`

` object ( ExplainedPABBindingAndPolicy  ` )

List of principal access boundary policies and bindings that are applicable to the principal's access state, with annotations to indicate how each binding and policy contributes to the overall access state.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of the principal access boundary access state to the overall access state.

### ExplainedPABBindingAndPolicy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;bindingAndPolicyAccessState&quot;: enum (PABAccessState),&quot;explainedPolicyBinding&quot;: {object (ExplainedPolicyBinding)},&quot;explainedPolicy&quot;: {object (ExplainedPABPolicy)},&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`bindingAndPolicyAccessState`

` enum ( PABAccessState  ` )

Output only. Indicates whether the principal is allowed to access the specified resource based on evaluating the binding and policy.

`explainedPolicyBinding`

` object ( ExplainedPolicyBinding  ` )

Details about how this binding contributes to the principal access boundary explanation, with annotations to indicate how the binding contributes to the overall access state.

`explainedPolicy`

` object ( ExplainedPABPolicy  ` )

Optional. Details about how this policy contributes to the principal access boundary explanation, with annotations to indicate how the policy contributes to the overall access state.

If the caller doesn't have permission to view the policy in the binding, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this principal access boundary binding and policy to the overall access state.

### ExplainedPolicyBinding

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyBindingState&quot;: enum (PolicyBindingState),&quot;policyBinding&quot;: {object (PolicyBinding)},&quot;conditionExplanation&quot;: {object (ConditionExplanation)},&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyBindingState`

` enum ( PolicyBindingState  ` )

Output only. Indicates whether the policy binding takes effect.

`policyBinding`

` object ( PolicyBinding  ` )

The policy binding that is explained.

`conditionExplanation`

` object ( ConditionExplanation  ` )

Optional. Explanation of the condition in the policy binding.

If the policy binding doesn't have a condition, this field is omitted.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy binding to the overall access state.

### PolicyBinding

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;etag&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;target&quot;: {object (Target)},&quot;policyKind&quot;: enum (PolicyKind),&quot;policy&quot;: string,&quot;policyUid&quot;: string,&quot;condition&quot;: {object (Expr)},&quot;createTime&quot;: string,&quot;updateTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The name of the policy binding, in the format `{binding_parent/locations/{location}/policyBindings/{policy_binding_id}` . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.

Format:

  - `projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}`
  - `folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}`

`uid`

`string`

Output only. The globally unique ID of the policy binding. Assigned when the policy binding is created.

`etag`

`string`

Optional. The etag for the policy binding. If this is provided on update, it must match the server's etag.

`displayName`

`string`

Optional. The description of the policy binding. Must be less than or equal to 63 characters.

`annotations`

`map (key: string, value: string)`

Optional. User-defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`target`

` object ( Target  ` )

Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.

`policyKind`

` enum ( PolicyKind  ` )

Immutable. The kind of the policy to attach in this binding. This field must be one of the following:

  - Left empty (will be automatically set to the policy kind)
  - The input policy kind

`policy`

`string`

Required. Immutable. The resource name of the policy to be bound. The binding parent and policy must belong to the same organization.

`policyUid`

`string`

Output only. The globally unique ID of the policy to be bound.

`condition`

` object ( Expr  ` )

Optional. The condition to apply to the policy binding. When set, the `expression` field in the `Expr` must include from 1 to 10 subexpressions, joined by the "||"(Logical OR), "&&"(Logical AND) or "\!"(Logical NOT) operators and cannot contain more than 250 characters.

The condition is currently only supported when bound to policies of kind principal access boundary.

When the bound policy is a principal access boundary policy, the only supported attributes in any subexpression are `principal.type` and `principal.subject` . An example expression is: "principal.type == 'iam.googleapis.com/ServiceAccount'" or "principal.subject == 'bob@example.com'".

Allowed operations for `principal.subject` :

  - `principal.subject == <principal subject string>`
  - `principal.subject != <principal subject string>`
  - `principal.subject in [<list of principal subjects>]`
  - `principal.subject.startsWith(<string>)`
  - `principal.subject.endsWith(<string>)`

Allowed operations for `principal.type` :

  - `principal.type == <principal type string>`
  - `principal.type != <principal type string>`
  - `principal.type in [<list of principal types>]`

Supported principal types are workspace, workforce pool, workload pool, service account, and agent identity. Allowed string must be one of:

  - `iam.googleapis.com/WorkspaceIdentity`
  - `iam.googleapis.com/WorkforcePoolIdentity`
  - `iam.googleapis.com/WorkloadPoolIdentity`
  - `iam.googleapis.com/ServiceAccount`
  - `iam.googleapis.com/AgentPoolIdentity` (available in Preview)

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the policy binding was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the policy binding was most recently updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

### AnnotationsEntry

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
  &quot;key&quot;: string,
  &quot;value&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

`string`

### Target

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field target can be only one of the following:&quot;principalSet&quot;: string,&quot;resource&quot;: string// End of list of possible types for union field target.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `target` . The different types of targets that can be bound to a policy. `target` can be only one of the following:

`principalSet`

`string`

Immutable. The full resource name that's used for principal access boundary policy bindings. The principal set must be directly parented by the policy binding's parent or same as the parent if the target is a project, folder, or organization.

Examples:

  - For bindings parented by an organization:
      - Organization: `//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID`
      - Workforce Identity: `//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID`
      - Workspace Identity: `//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID`
  - For bindings parented by a folder:
      - Folder: `//cloudresourcemanager.googleapis.com/folders/FOLDER_ID`
  - For bindings parented by a project:
      - Project:
          - `//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER`
          - `//cloudresourcemanager.googleapis.com/projects/PROJECT_ID`
      - Workload Identity Pool: `//iam.googleapis.com/projects/PROJECT_NUMBER/locations/LOCATION/workloadIdentityPools/WORKLOAD_POOL_ID`

`resource`

`string`

Immutable. The full resource name that's used for access policy bindings.

Examples:

  - Organization: `//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID`
  - Folder: `//cloudresourcemanager.googleapis.com/folders/FOLDER_ID`
  - Project:
      - `//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER`
      - `//cloudresourcemanager.googleapis.com/projects/PROJECT_ID`

### ExplainedPABPolicy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyAccessState&quot;: enum (PABAccessState),&quot;policy&quot;: {object (PrincipalAccessBoundaryPolicy)},&quot;policyVersion&quot;: {object (ExplainedPABPolicyVersion)},&quot;explainedRules&quot;: [{object (ExplainedPABRule)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyAccessState`

` enum ( PABAccessState  ` )

Output only. Indicates whether the policy allows access to the specified resource.

`policy`

` object ( PrincipalAccessBoundaryPolicy  ` )

The policy that is explained.

`policyVersion`

` object ( ExplainedPABPolicyVersion  ` )

Output only. Explanation of the principal access boundary policy's version.

`explainedRules[]`

` object ( ExplainedPABRule  ` )

List of principal access boundary rules that were explained to check the principal's access to specified resource, with annotations to indicate how each rule contributes to the overall access state.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this policy to the overall access state.

### PrincipalAccessBoundaryPolicy

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;etag&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;details&quot;: {object (PrincipalAccessBoundaryPolicyDetails)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The resource name of the principal access boundary policy.

The following format is supported: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{policy_id}`

`uid`

`string`

Output only. The globally unique ID of the principal access boundary policy.

`etag`

`string`

Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.

`displayName`

`string`

Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.

`annotations`

`map (key: string, value: string)`

Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the principal access boundary policy was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the principal access boundary policy was most recently updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`details`

` object ( PrincipalAccessBoundaryPolicyDetails  ` )

Optional. The details for the principal access boundary policy.

### AnnotationsEntry

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
  &quot;key&quot;: string,
  &quot;value&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`key`

`string`

`value`

`string`

### PrincipalAccessBoundaryPolicyDetails

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;rules&quot;: [{object (PrincipalAccessBoundaryPolicyRule)}],&quot;enforcementVersion&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`rules[]`

` object ( PrincipalAccessBoundaryPolicyRule  ` )

Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500.

`enforcementVersion`

`string`

Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.

### PrincipalAccessBoundaryPolicyRule

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;description&quot;: string,&quot;resources&quot;: [string],&quot;effect&quot;: enum (Effect),&quot;operation&quot;: {object (Operation)},&quot;excludedResources&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`description`

`string`

Optional. The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.

`resources[]`

`string`

Required. A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.

The following resource types are supported:

  - Organizations, such as `//cloudresourcemanager.googleapis.com/organizations/123` .
  - Folders, such as `//cloudresourcemanager.googleapis.com/folders/123` .
  - Projects, such as `//cloudresourcemanager.googleapis.com/projects/123` or `//cloudresourcemanager.googleapis.com/projects/my-project-id` .

`effect`

` enum ( Effect  ` )

Required. The access relationship of principals to the resources in this rule.

`operation`

` object ( Operation  ` )

Optional. The operation attributes that determine whether this rule applies to a request. If this field is not specified, the rule applies to all operations.

`excludedResources[]`

`string`

Optional. A list of Resource Manager resources. If an excluded resource is listed in the rule, then the rule does not apply for that resource and its descendants. This takes precedence over the `resources` field. The number of excluded resources in this field is limited to 500 across all rules in the policy.

The following resource types are supported:

  - Organizations, such as `//cloudresourcemanager.googleapis.com/organizations/123` .
  - Folders, such as `//cloudresourcemanager.googleapis.com/folders/123` .
  - Projects, such as `//cloudresourcemanager.googleapis.com/projects/123` or `//cloudresourcemanager.googleapis.com/projects/my-project-id` .

### Operation

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
  &quot;permissions&quot;: [
    string
  ],
  &quot;excludedPermissions&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`permissions[]`

`string`

Optional. The permissions that are explicitly affected by this rule. The number of permission strings in this field is limited to 50 across all rules in the policy.

Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. `*` can be used as a wildcard to match all permissions for a specific service, resource type, or verb.

The following formats are supported:

  - `{service_fqdn}/{resource}.{verb}` : A specific permission.
  - `{service_fqdn}/{resource}.*` : All permissions for a specific resource type.
  - `{service_fqdn}/*.*` : All permissions for all resource types under a specific service.
  - `{service_fqdn}/*.{verb}` : All permissions with a specific verb under a specific service.
  - `*` : All permissions across all services.

For example, `compute.googleapis.com/*.setIamPolicy` refers to all setIamPolicy permissions for any compute resource.

Wildcards expand only to the permissions specified in the `enforcement_version` of the policy. If the `enforcement_version` is updated, the wildcard will automatically expand to include new permissions in the updated version.

`excludedPermissions[]`

`string`

Optional. Specifies the permissions that this rule excludes from the set of affected permissions given by `permissions` . The number of excluded permission strings in this field is limited to 50 across all rules in the policy.

If a permission appears in both `permissions` and `excluded_permissions` then it will *not* be subject to the policy effect.

The excluded permissions can be specified using the same syntax as `permissions` .

### ExplainedPABPolicyVersion

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;version&quot;: integer,&quot;enforcementState&quot;: enum (PABPolicyEnforcementState)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`version`

`integer`

Output only. The actual version of the policy. - If the policy uses static version, this field is the chosen static version. - If the policy uses dynamic version, this field is the effective latest version.

`enforcementState`

` enum ( PABPolicyEnforcementState  ` )

Output only. Indicates whether the policy is enforced based on its version.

### ExplainedPABRule

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;ruleAccessState&quot;: enum (PABAccessState),&quot;effect&quot;: enum (Effect),&quot;combinedResourceInclusionState&quot;: enum (ResourceInclusionState),&quot;combinedResourceRelevance&quot;: enum (HeuristicRelevance),&quot;explainedResources&quot;: [{object (ExplainedResource)}],&quot;pabUnsupportedFeatures&quot;: [string],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`ruleAccessState`

` enum ( PABAccessState  ` )

Output only. Indicates whether the rule allows access to the specified resource.

`effect`

` enum ( Effect  ` )

Required. The effect of the rule which describes the access relationship.

`combinedResourceInclusionState`

` enum ( ResourceInclusionState  ` )

Output only. Indicates whether any resource of the rule is the specified resource or includes the specified resource.

`combinedResourceRelevance`

` enum ( HeuristicRelevance  ` )

The relevance of the combined resource inclusion state to the overall access state.

`explainedResources[]`

` object ( ExplainedResource  ` )

List of resources that were explained to check the principal's access to specified resource, with annotations to indicate how each resource contributes to the overall access state.

`pabUnsupportedFeatures[]`

`string`

Output only. Unsupported features detected in this rule. Supported values: \* `OPERATION` : Permission Subsetting (Operation constraints). See `google.iam.v3.PrincipalAccessBoundaryPolicyRule.operation` .

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this rule to the overall access state.

### ExplainedResource

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;resourceInclusionState&quot;: enum (ResourceInclusionState),&quot;resource&quot;: string,&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`resourceInclusionState`

` enum ( ResourceInclusionState  ` )

Output only. Indicates whether the resource is the specified resource or includes the specified resource.

`resource`

`string`

The [full resource name](https://cloud.google.com/iam/docs/full-resource-names) that identifies the resource that is explained.

This can only be a project, a folder, or an organization which is what a PAB rule accepts.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this resource to the overall access state.

### OverallAccessState

Whether the principal has the permission to access the resource.

Enums

`OVERALL_ACCESS_STATE_UNSPECIFIED`

Not specified.

`OVERALL_ACCESS_STATE_CAN_ACCESS`

The principal has the permission.

`OVERALL_ACCESS_STATE_CANNOT_ACCESS`

The principal doesn't have the permission.

`OVERALL_ACCESS_STATE_UNKNOWN_INFO`

The principal might have the permission, but the sender can't access all of the information needed to fully evaluate the principal's access.

`OVERALL_ACCESS_STATE_UNKNOWN_CONDITIONAL`

The principal might have the permission, but Policy Troubleshooter can't fully evaluate the principal's access because of the missing context to evaluate the condition.

### AllowAccessState

Whether IAM allow policies gives the principal the permission.

Enums

`ALLOW_ACCESS_STATE_UNSPECIFIED`

Not specified.

`ALLOW_ACCESS_STATE_GRANTED`

The allow policy gives the principal the permission.

`ALLOW_ACCESS_STATE_NOT_GRANTED`

The allow policy doesn't give the principal the permission.

`ALLOW_ACCESS_STATE_UNKNOWN_CONDITIONAL`

The allow policy gives the principal the permission if a condition expression evaluate to `true` . However, the sender of the request didn't provide enough context for Policy Troubleshooter to evaluate the condition expression.

`ALLOW_ACCESS_STATE_UNKNOWN_INFO`

The sender of the request doesn't have access to all of the allow policies that Policy Troubleshooter needs to evaluate the principal's access.

### RolePermissionInclusionState

Whether a role includes a specific permission.

Enums

`ROLE_PERMISSION_INCLUSION_STATE_UNSPECIFIED`

Not specified.

`ROLE_PERMISSION_INCLUDED`

The permission is included in the role.

`ROLE_PERMISSION_NOT_INCLUDED`

The permission is not included in the role.

`ROLE_PERMISSION_UNKNOWN_INFO`

The sender of the request is not allowed to access the role definition.

### HeuristicRelevance

The extent to which a single data point contributes to an overall determination.

Enums

`HEURISTIC_RELEVANCE_UNSPECIFIED`

Not specified.

`HEURISTIC_RELEVANCE_NORMAL`

The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination.

`HEURISTIC_RELEVANCE_HIGH`

The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.

### MembershipMatchingState

Whether the principal in the request matches the principal in the policy.

Enums

`MEMBERSHIP_MATCHING_STATE_UNSPECIFIED`

Not specified.

`MEMBERSHIP_MATCHED`

The principal in the request matches the principal in the policy. The principal can be included directly or indirectly:

  - A principal is included directly if that principal is listed in the role binding.
  - A principal is included indirectly if that principal is in a Google group, Google Workspace account, or Cloud Identity domain that is listed in the policy.

`MEMBERSHIP_NOT_MATCHED`

The principal in the request doesn't match the principal in the policy.

`MEMBERSHIP_UNKNOWN_INFO`

The principal in the policy is a group or domain, and the sender of the request doesn't have permission to view whether the principal in the request is a member of the group or domain.

`MEMBERSHIP_UNKNOWN_UNSUPPORTED`

The principal is an unsupported type.

### NullValue

Represents a JSON `null` .

`NullValue` is a sentinel, using an enum with only one value to represent the null value for the `Value` type union.

A field of type `NullValue` with any value other than `0` is considered invalid. Most ProtoJSON serializers will emit a `Value` with a `null_value` set as a JSON `null` regardless of the integer value, and so will round trip to a `0` value.

Enums

`NULL_VALUE`

Null value.

### LogType

The list of valid permission types for which logging can be configured. Admin writes are always logged, and are not configurable.

Enums

`LOG_TYPE_UNSPECIFIED`

Default case. Should never be this.

`ADMIN_READ`

Admin reads. Example: CloudIAM getIamPolicy

`DATA_WRITE`

Data writes. Example: CloudSQL Users create

`DATA_READ`

Data reads. Example: CloudSQL Users list

### DenyAccessState

Whether IAM deny policies deny the principal the permission.

Enums

`DENY_ACCESS_STATE_UNSPECIFIED`

Not specified.

`DENY_ACCESS_STATE_DENIED`

The deny policy denies the principal the permission.

`DENY_ACCESS_STATE_NOT_DENIED`

The deny policy doesn't deny the principal the permission.

`DENY_ACCESS_STATE_UNKNOWN_CONDITIONAL`

The deny policy denies the principal the permission if a condition expression evaluates to `true` . However, the sender of the request didn't provide enough context for Policy Troubleshooter to evaluate the condition expression.

`DENY_ACCESS_STATE_UNKNOWN_INFO`

The sender of the request does not have access to all of the deny policies that Policy Troubleshooter needs to evaluate the principal's access.

### PermissionPatternMatchingState

Whether the permission in the request matches the permission in the policy.

Enums

`PERMISSION_PATTERN_MATCHING_STATE_UNSPECIFIED`

Not specified.

`PERMISSION_PATTERN_MATCHED`

The permission in the request matches the permission in the policy.

`PERMISSION_PATTERN_NOT_MATCHED`

The permission in the request matches the permission in the policy.

### PABAccessState

Whether a principal access boundary component allows the principal to access the specified resource.

A PAB component refers to a PAB rule, a PAB policy, a PAB policy and binding pair, all PAB policies bound to a target, or PAB overall. This is because this enum is shared across all these messages.

Enums

`PAB_ACCESS_STATE_UNSPECIFIED`

Not specified.

`PAB_ACCESS_STATE_ALLOWED`

The PAB component allows the principal's access to the specified resource.

`PAB_ACCESS_STATE_NOT_ALLOWED`

The PAB component doesn't allow the principal's access to the specified resource.

`PAB_ACCESS_STATE_NOT_ENFORCED`

The PAB component is not enforced on the principal, or the specified resource.

This state refers to the following scenarios:

  - IAM doesn't enforce the specified permission at the PAB policy's [enforcement version](https://cloud.google.com/iam/help/pab/enforcement-versions) , so the PAB policy can't block access.
  - The binding doesn't apply to the principal, so the policy is not enforced.
  - The PAB policy doesn't have any rules

`PAB_ACCESS_STATE_UNKNOWN_INFO`

The sender of the request does not have access to the PAB component, or the relevant data to explain the PAB component.

### PolicyBindingState

Whether the policy binding is enforced.

Enums

`POLICY_BINDING_STATE_UNSPECIFIED`

An error occurred when checking whether the policy binding is enforced.

`POLICY_BINDING_STATE_ENFORCED`

The policy binding is enforced.

`POLICY_BINDING_STATE_NOT_ENFORCED`

The policy binding is not enforced.

### PolicyKind

The different policy kinds supported in this binding.

Enums

`POLICY_KIND_UNSPECIFIED`

Unspecified policy kind; Not a valid state

`PRINCIPAL_ACCESS_BOUNDARY`

Principal access boundary policy kind

`ACCESS`

Access policy kind.

### Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

Effect unspecified.

`ALLOW`

Allows access to the resources in this rule.

`DENY`

Denies access to the resources in this rule.

### PABPolicyEnforcementState

Whether a principal access boundary policy is enforced based on its version.

Enums

`PAB_POLICY_ENFORCEMENT_STATE_UNSPECIFIED`

An error occurred when checking whether a principal access boundary policy is enforced based on its version.

`PAB_POLICY_ENFORCEMENT_STATE_ENFORCED`

The principal access boundary policy is enforced based on its version.

`PAB_POLICY_ENFORCEMENT_STATE_NOT_ENFORCED`

The principal access boundary policy is not enforced based on its version.

### ResourceInclusionState

Whether the resource is the specified resource or includes the specified resource.

Enums

`RESOURCE_INCLUSION_STATE_UNSPECIFIED`

An error occurred when checking whether the resource includes the specified resource.

`RESOURCE_INCLUSION_STATE_INCLUDED`

The resource includes the specified resource.

`RESOURCE_INCLUSION_STATE_NOT_INCLUDED`

The resource doesn't include the specified resource.

`RESOURCE_INCLUSION_STATE_UNKNOWN_INFO`

The sender of the request does not have access to the relevant data to check whether the resource includes the specified resource.

`RESOURCE_INCLUSION_STATE_UNKNOWN_UNSUPPORTED`

The resource is of an unsupported type, such as non-CRM resources.

### Tool Annotations

Destructive Hint: ❌ | Idempotent Hint: ✅ | Read Only Hint: ✅ | Open World Hint: ❌
