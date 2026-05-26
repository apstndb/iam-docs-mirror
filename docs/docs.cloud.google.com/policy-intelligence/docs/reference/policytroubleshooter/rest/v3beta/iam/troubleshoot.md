---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot
title: 'Method: iam.troubleshoot'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.HTTP_TEMPLATE)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.TroubleshootIamPolicyResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#body.aspect)
  - [AccessTuple](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AccessTuple)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AccessTuple.SCHEMA_REPRESENTATION)
  - [ConditionContext](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ConditionContext)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ConditionContext.SCHEMA_REPRESENTATION)
  - [Resource](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Resource)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Resource.SCHEMA_REPRESENTATION)
  - [Peer](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Peer)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Peer.SCHEMA_REPRESENTATION)
  - [Request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Request)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Request.SCHEMA_REPRESENTATION)
  - [EffectiveTag](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#EffectiveTag)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#EffectiveTag.SCHEMA_REPRESENTATION)
  - [OverallAccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#OverallAccessState)
  - [AllowPolicyExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AllowPolicyExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AllowPolicyExplanation.SCHEMA_REPRESENTATION)
  - [AllowAccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AllowAccessState)
  - [ExplainedAllowPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedAllowPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedAllowPolicy.SCHEMA_REPRESENTATION)
  - [AllowBindingExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AllowBindingExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AllowBindingExplanation.SCHEMA_REPRESENTATION)
  - [RolePermissionInclusionState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#RolePermissionInclusionState)
  - [HeuristicRelevance](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#HeuristicRelevance)
  - [AnnotatedAllowMembership](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedAllowMembership)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedAllowMembership.SCHEMA_REPRESENTATION)
  - [MembershipMatchingState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#MembershipMatchingState)
  - [ConditionExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ConditionExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ConditionExplanation.SCHEMA_REPRESENTATION)
  - [EvaluationState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#EvaluationState)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#EvaluationState.SCHEMA_REPRESENTATION)
  - [DenyPolicyExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#DenyPolicyExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#DenyPolicyExplanation.SCHEMA_REPRESENTATION)
  - [DenyAccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#DenyAccessState)
  - [ExplainedDenyResource](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedDenyResource)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedDenyResource.SCHEMA_REPRESENTATION)
  - [ExplainedDenyPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedDenyPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedDenyPolicy.SCHEMA_REPRESENTATION)
  - [DenyRuleExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#DenyRuleExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#DenyRuleExplanation.SCHEMA_REPRESENTATION)
  - [AnnotatedPermissionMatching](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedPermissionMatching)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedPermissionMatching.SCHEMA_REPRESENTATION)
  - [PermissionPatternMatchingState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PermissionPatternMatchingState)
  - [AnnotatedDenyPrincipalMatching](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedDenyPrincipalMatching)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#AnnotatedDenyPrincipalMatching.SCHEMA_REPRESENTATION)
  - [PABPolicyExplanation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PABPolicyExplanation)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PABPolicyExplanation.SCHEMA_REPRESENTATION)
  - [PABAccessState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PABAccessState)
  - [ExplainedPABBindingAndPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABBindingAndPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABBindingAndPolicy.SCHEMA_REPRESENTATION)
  - [ExplainedPolicyBinding](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPolicyBinding)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPolicyBinding.SCHEMA_REPRESENTATION)
  - [PolicyBindingState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PolicyBindingState)
  - [PolicyBinding](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PolicyBinding)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PolicyBinding.SCHEMA_REPRESENTATION)
  - [Target](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Target)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Target.SCHEMA_REPRESENTATION)
  - [PolicyKind](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PolicyKind)
  - [ExplainedPABPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABPolicy.SCHEMA_REPRESENTATION)
  - [PrincipalAccessBoundaryPolicy](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicy)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicy.SCHEMA_REPRESENTATION)
  - [PrincipalAccessBoundaryPolicyDetails](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicyDetails)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicyDetails.SCHEMA_REPRESENTATION)
  - [PrincipalAccessBoundaryPolicyRule](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicyRule)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PrincipalAccessBoundaryPolicyRule.SCHEMA_REPRESENTATION)
  - [Effect](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#Effect)
  - [ExplainedPABPolicyVersion](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABPolicyVersion)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABPolicyVersion.SCHEMA_REPRESENTATION)
  - [PABPolicyEnforcementState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#PABPolicyEnforcementState)
  - [ExplainedPABRule](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABRule)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedPABRule.SCHEMA_REPRESENTATION)
  - [ResourceInclusionState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ResourceInclusionState)
  - [ExplainedResource](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedResource)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#ExplainedResource.SCHEMA_REPRESENTATION)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/rest/v3beta/iam/troubleshoot#try-it)

Checks whether a principal has a specific permission for a specific resource, and explains why the principal does or doesn't have that permission.

### HTTP request

`POST https://policytroubleshooter.googleapis.com/v3beta/iam:troubleshoot`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessTuple&quot;: {object (AccessTuple)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessTuple`

` object ( AccessTuple  ` )

The information to use for checking whether a principal has a permission for a resource.

### Response body

Response for `  iam.troubleshoot  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;overallAccessState&quot;: enum (OverallAccessState),&quot;accessTuple&quot;: {object (AccessTuple)},&quot;allowPolicyExplanation&quot;: {object (AllowPolicyExplanation)},&quot;denyPolicyExplanation&quot;: {object (DenyPolicyExplanation)},&quot;pabPolicyExplanation&quot;: {object (PABPolicyExplanation)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`overallAccessState`

` enum ( OverallAccessState  ` )

Indicates whether the principal has the specified permission for the specified resource, based on evaluating all types of the applicable IAM policies.

`accessTuple`

` object ( AccessTuple  ` )

The access tuple from the request, including any provided context used to evaluate the condition.

`allowPolicyExplanation`

` object ( AllowPolicyExplanation  ` )

An explanation of how the applicable IAM allow policies affect the final access state.

`denyPolicyExplanation`

` object ( DenyPolicyExplanation  ` )

An explanation of how the applicable IAM deny policies affect the final access state.

`pabPolicyExplanation`

` object ( PABPolicyExplanation  ` )

An explanation of how the applicable principal access boundary policies affect the final access state.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## AccessTuple

Information about the principal, resource, and permission to check.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;principal&quot;: string,&quot;fullResourceName&quot;: string,&quot;permission&quot;: string,&quot;permissionFqdn&quot;: string,&quot;conditionContext&quot;: {object (ConditionContext)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principal`

`string`

Required. The email address of the principal whose access you want to check. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` .

The principal must be a Google Account or a service account. Other types of principals are not supported.

`fullResourceName`

`string`

Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`permission`

`string`

Required. The IAM permission to check for, either in the `v1` permission format or the `v2` permission format.

For a complete list of IAM permissions in the `v1` format, see <https://cloud.google.com/iam/help/permissions/reference> .

For a list of IAM permissions in the `v2` format, see <https://cloud.google.com/iam/help/deny/supported-permissions> .

For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> .

`permissionFqdn`

`string`

Output only. The permission that Policy Troubleshooter checked for, in the `v2` format.

`conditionContext`

` object ( ConditionContext  ` )

Optional. Additional context for the request, such as the request time or IP address. This context allows Policy Troubleshooter to troubleshoot conditional role bindings and deny rules.

## ConditionContext

Additional context for troubleshooting conditional role bindings and deny rules.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;resource&quot;: {object (Resource)},&quot;destination&quot;: {object (Peer)},&quot;request&quot;: {object (Request)},&quot;effectiveTags&quot;: [{object (EffectiveTag)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`resource`

` object ( Resource  ` )

Represents a target resource that is involved with a network activity. If multiple resources are involved with an activity, this must be the primary one.

`destination`

` object ( Peer  ` )

The destination of a network activity, such as accepting a TCP connection. In a multi-hop network activity, the destination represents the receiver of the last hop.

`request`

` object ( Request  ` )

Represents a network request, such as an HTTP request.

`effectiveTags[]`

` object ( EffectiveTag  ` )

Output only. The effective tags on the resource. The effective tags are fetched during troubleshooting.

## Resource

Core attributes for a resource. A resource is an addressable (named) entity provided by the destination service. For example, a Compute Engine instance.

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
  &quot;service&quot;: string,
  &quot;name&quot;: string,
  &quot;type&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`service`

`string`

The name of the service that this resource belongs to, such as `compute.googleapis.com` . The service name might not match the DNS hostname that actually serves the request.

For a full list of resource service values, see <https://cloud.google.com/iam/help/conditions/resource-services>

`name`

`string`

The stable identifier (name) of a resource on the `service` . A resource can be logically identified as `//{resource.service}/{resource.name}` . Unlike the resource URI, the resource name doesn't contain any protocol and version information.

For a list of full resource name formats, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names>

`type`

`string`

The type of the resource, in the format `{service}/{kind}` .

For a full list of resource type values, see <https://cloud.google.com/iam/help/conditions/resource-types>

## Peer

This message defines attributes for a node that handles a network request. The node can be either a service or an application that sends, forwards, or receives the request. Service peers should fill in `principal` and `labels` as appropriate.

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
  &quot;ip&quot;: string,
  &quot;port&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`ip`

`string`

The IPv4 or IPv6 address of the peer.

`port`

`string ( int64 format)`

The network port of the peer.

## Request

This message defines attributes for an HTTP request. If the actual request is not an HTTP request, the runtime system should try to map the actual request to an equivalent HTTP request.

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
  &quot;receiveTime&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`receiveTime`

` string ( Timestamp  ` format)

Optional. The timestamp when the destination service receives the first byte of the request.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## EffectiveTag

A tag that applies to a resource during policy evaluation. Tags can be either directly bound to a resource or inherited from its ancestor. `EffectiveTag` contains the `name` and `namespaced_name` of the tag value and tag key, with additional fields of `inherited` to indicate the inheritance status of the effective tag.

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
  &quot;tagValue&quot;: string,
  &quot;namespacedTagValue&quot;: string,
  &quot;tagKey&quot;: string,
  &quot;namespacedTagKey&quot;: string,
  &quot;tagKeyParentName&quot;: string,
  &quot;inherited&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`tagValue`

`string`

Output only. Resource name for TagValue in the format `tagValues/456` .

`namespacedTagValue`

`string`

Output only. The namespaced name of the TagValue. Can be in the form `{organizationId}/{tag_key_short_name}/{tag_value_short_name}` or `{projectId}/{tag_key_short_name}/{tag_value_short_name}` or `{projectNumber}/{tag_key_short_name}/{tag_value_short_name}` .

`tagKey`

`string`

Output only. The name of the TagKey, in the format `tagKeys/{id}` , such as `tagKeys/123` .

`namespacedTagKey`

`string`

Output only. The namespaced name of the TagKey. Can be in the form `{organizationId}/{tag_key_short_name}` or `{projectId}/{tag_key_short_name}` or `{projectNumber}/{tag_key_short_name}` .

`tagKeyParentName`

`string`

The parent name of the tag key. Must be in the format `organizations/{organizationId}` or `projects/{projectNumber}`

`inherited`

`boolean`

Output only. Indicates the inheritance status of a tag value attached to the given resource. If the tag value is inherited from one of the resource's ancestors, inherited will be true. If false, then the tag value is directly attached to the resource, inherited will be false.

## OverallAccessState

Whether the principal has the permission on the resource.

Enums

`OVERALL_ACCESS_STATE_UNSPECIFIED`

Not specified.

`CAN_ACCESS`

The principal has the permission.

`CANNOT_ACCESS`

The principal doesn't have the permission.

`UNKNOWN_INFO`

The principal might have the permission, but the sender can't access all of the information needed to fully evaluate the principal's access.

`UNKNOWN_CONDITIONAL`

The principal might have the permission, but Policy Troubleshooter can't fully evaluate the principal's access because the sender didn't provide the required context to evaluate the condition.

## AllowPolicyExplanation

Details about how the relevant IAM allow policies affect the final access state.

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

## AllowAccessState

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

## ExplainedAllowPolicy

Details about how a specific IAM allow policy contributed to the final access state.

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

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overallAccessState` field in the `  TroubleshootIamPolicyResponse  ` .

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

## AllowBindingExplanation

Details about how a role binding in an allow policy affects a principal's ability to use a permission.

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

This field does *not* indicate whether the principal actually has the permission on the resource. There might be another role binding that overrides this role binding. To determine whether the principal actually has the permission, use the `overallAccessState` field in the `  TroubleshootIamPolicyResponse  ` .

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

## RolePermissionInclusionState

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

## HeuristicRelevance

The extent to which a single data point contributes to an overall determination.

Enums

`HEURISTIC_RELEVANCE_UNSPECIFIED`

Not specified.

`HEURISTIC_RELEVANCE_NORMAL`

The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination.

`HEURISTIC_RELEVANCE_HIGH`

The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.

## AnnotatedAllowMembership

Details about whether the role binding includes the principal.

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

## MembershipMatchingState

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

## ConditionExplanation

Explanation for how a condition affects a principal's access

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

## EvaluationState

Evaluated state of a condition expression.

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

## DenyPolicyExplanation

Details about how the relevant IAM deny policies affect the final access state.

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

## DenyAccessState

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

## ExplainedDenyResource

Details about how a specific resource contributed to the deny policy evaluation.

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

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overallAccessState` field in the `  TroubleshootIamPolicyResponse  ` .

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

## ExplainedDenyPolicy

Details about how a specific IAM deny policy `Policy` contributed to the access check.

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

This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overallAccessState` field in the `  TroubleshootIamPolicyResponse  ` .

`policy`

`object ( Policy` )

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

## DenyRuleExplanation

Details about how a deny rule in a deny policy affects a principal's ability to use a permission.

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

This field does *not* indicate whether the principal is actually denied on the permission for the resource. There might be another rule that overrides this rule. To determine whether the principal actually has the permission, use the `overallAccessState` field in the `  TroubleshootIamPolicyResponse  ` .

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

## AnnotatedPermissionMatching

Details about whether the permission in the request is denied by the deny rule.

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

## PermissionPatternMatchingState

Whether the permission in the request matches the permission in the policy.

Enums

`PERMISSION_PATTERN_MATCHING_STATE_UNSPECIFIED`

Not specified.

`PERMISSION_PATTERN_MATCHED`

The permission in the request matches the permission in the policy.

`PERMISSION_PATTERN_NOT_MATCHED`

The permission in the request matches the permission in the policy.

## AnnotatedDenyPrincipalMatching

Details about whether the principal in the request is listed as a denied principal in the deny rule, either directly or through membership in a principal set.

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

## PABPolicyExplanation

Details about how the relevant principal access boundary policies affect the overall access state.

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

## PABAccessState

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

## ExplainedPABBindingAndPolicy

Details about how a principal access boundary binding and policy contributes to the principal access boundary explanation, with annotations to indicate how the binding and policy contribute to the overall access state.

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

## ExplainedPolicyBinding

Details about how a policy binding contributes to the policy explanation, with annotations to indicate how the policy binding contributes to the overall access state.

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

## PolicyBindingState

Whether the policy binding is enforced.

Enums

`POLICY_BINDING_STATE_UNSPECIFIED`

An error occurred when checking whether the policy binding is enforced.

`POLICY_BINDING_STATE_ENFORCED`

The policy binding is enforced.

`POLICY_BINDING_STATE_NOT_ENFORCED`

The policy binding is not enforced.

## PolicyBinding

IAM policy binding resource.

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

  - `projects/{projectId}/locations/{location}/policyBindings/{policy_binding_id}`
  - `projects/{projectNumber}/locations/{location}/policyBindings/{policy_binding_id}`
  - `folders/{folderId}/locations/{location}/policyBindings/{policy_binding_id}`
  - `organizations/{organizationId}/locations/{location}/policyBindings/{policy_binding_id}`

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

Supported principal types are workspace, workforce pool, workload pool, service account, and Agent Identity. Allowed string must be one of:

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

## Target

The full resource name of the resource to which the policy will be bound. Immutable once set.

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

## PolicyKind

The different policy kinds supported in this binding.

Enums

`POLICY_KIND_UNSPECIFIED`

Unspecified policy kind; Not a valid state

`PRINCIPAL_ACCESS_BOUNDARY`

Principal access boundary policy kind

`ACCESS`

Access policy kind.

## ExplainedPABPolicy

Details about how a principal access boundary policy contributes to the explanation, with annotations to indicate how the policy contributes to the overall access state.

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

## PrincipalAccessBoundaryPolicy

An IAM principal access boundary policy resource.

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

The following format is supported: `organizations/{organizationId}/locations/{location}/principalAccessBoundaryPolicies/{policyId}`

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

## PrincipalAccessBoundaryPolicyDetails

Principal access boundary policy details

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

## PrincipalAccessBoundaryPolicyRule

Principal access boundary policy rule that defines the resource boundary.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;description&quot;: string,&quot;resources&quot;: [string],&quot;effect&quot;: enum (Effect)}</code></pre></td>
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

## Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

Effect unspecified.

`ALLOW`

Allows access to the resources in this rule.

## ExplainedPABPolicyVersion

Details about how a principal access boundary policy's version contributes to the policy's enforcement state.

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

## PABPolicyEnforcementState

Whether a principal access boundary policy is enforced based on its version.

Enums

`PAB_POLICY_ENFORCEMENT_STATE_UNSPECIFIED`

An error occurred when checking whether a principal access boundary policy is enforced based on its version.

`PAB_POLICY_ENFORCEMENT_STATE_ENFORCED`

The principal access boundary policy is enforced based on its version.

`PAB_POLICY_ENFORCEMENT_STATE_NOT_ENFORCED`

The principal access boundary policy is not enforced based on its version.

## ExplainedPABRule

Details about how a principal access boundary rule contributes to the explanation, with annotations to indicate how the rule contributes to the overall access state.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;ruleAccessState&quot;: enum (PABAccessState),&quot;effect&quot;: enum (Effect),&quot;combinedResourceInclusionState&quot;: enum (ResourceInclusionState),&quot;explainedResources&quot;: [{object (ExplainedResource)}],&quot;relevance&quot;: enum (HeuristicRelevance)}</code></pre></td>
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

`explainedResources[]`

` object ( ExplainedResource  ` )

List of resources that were explained to check the principal's access to specified resource, with annotations to indicate how each resource contributes to the overall access state.

`relevance`

` enum ( HeuristicRelevance  ` )

The relevance of this rule to the overall access state.

## ResourceInclusionState

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

## ExplainedResource

Details about how a resource contributes to the explanation, with annotations to indicate how the resource contributes to the overall access state.

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
