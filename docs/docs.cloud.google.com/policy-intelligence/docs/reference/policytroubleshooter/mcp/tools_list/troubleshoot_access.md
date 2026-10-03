---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access
title: 'MCP Tools Reference: policytroubleshooter.googleapis.com'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

## Tool: `troubleshoot_access`

Analyzes Google Cloud IAM policies to diagnose why a principal has or does not have a specific permission on a resource. This tool examines allow policies, deny policies, and principal access boundary (PAB) policies that impact the principal's access.

Use this tool when a user or service account is unexpectedly denied access to a Google Cloud resource, or to verify that a principal has been granted a specific permission. Do not use this tool for troubleshooting Cloud Storage Access Control Lists (ACLs). For diagnosing VPC Service Controls violations, use the VPC Service Controls violation analyzer ( <https://docs.cloud.google.com/vpc-service-controls/docs/violation-analyzer> ) instead.

This tool requires the following parameters:

- `principal` (string): The email address of the principal (Google Account or service account) whose access you want to check. Only one principal can be specified per request. Group principals are not supported.
- `full_resource_name` (string): The full resource name of the Google Cloud resource, in the format described by <https://cloud.google.com/iam/docs/full-resource-names> . For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` .
- `permission` (string): The IAM permission to check for. For example, `storage.buckets.get` . Do not pass roles, always pass a single permission.

The tool returns an explanation of how the applicable IAM policies affect the final access state.

The following sample demonstrate how to use `curl` to invoke the `troubleshoot_access` MCP tool.

**Curl Request**

```
curl --location 'https://policytroubleshooter.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "troubleshoot_access",
    "arguments": {
      // provide these details according to the tool's MCP specification
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

Request for `TroubleshootIamPolicy` .

### TroubleshootIamPolicyRequest

**JSON representation**

```
{
  "accessTuple": {
    object (AccessTuple)
  }
}
```

| Fields        |                                                                                                                                                                                                                                                                            |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessTuple` | `object ( `[`AccessTuple`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.AccessTuple)` )` The information to use for checking whether a principal has a permission for a resource. |

### AccessTuple

**JSON representation**

```
{
  "principal": string,
  "fullResourceName": string,
  "permission": string,
  "permissionFqdn": string,
  "conditionContext": {
    object (ConditionContext)
  }
}
```

| Fields             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal`        | `string` Required. The email address of the principal whose access you want to check. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` . The principal must be a Google Account or a service account. Other types of principals are not supported.                                                                                                                                                                                                                     |
| `fullResourceName` | `string` Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                                                                       |
| `permission`       | `string` Required. The IAM permission to check for, either in the `v1` permission format or the `v2` permission format. For a complete list of IAM permissions in the `v1` format, see <https://cloud.google.com/iam/help/permissions/reference> . For a list of IAM permissions in the `v2` format, see <https://cloud.google.com/iam/help/deny/supported-permissions> . For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> . |
| `permissionFqdn`   | `string` Output only. The permission that Policy Troubleshooter checked for, in the `v2` format.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `conditionContext` | `object ( `[`ConditionContext`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.ConditionContext)` )` Optional. Additional context for the request, such as the request time or IP address. This context allows Policy Troubleshooter to troubleshoot conditional role bindings and deny rules.                                                                                                                             |

### ConditionContext

**JSON representation**

```
{
  "resource": {
    object (Resource)
  },
  "destination": {
    object (Peer)
  },
  "request": {
    object (Request)
  },
  "effectiveTags": [
    {
      object (EffectiveTag)
    }
  ]
}
```

| Fields            |                                                                                                                                                                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource`        | `object ( `[`Resource`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Resource)` )` Represents a target resource that is involved with a network activity. If multiple resources are involved with an activity, this must be the primary one.    |
| `destination`     | `object ( `[`Peer`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Peer)` )` The destination of a network activity, such as accepting a TCP connection. In a multi-hop network activity, the destination represents the receiver of the last hop. |
| `request`         | `object ( `[`Request`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Request)` )` Represents a network request, such as an HTTP request.                                                                                                         |
| `effectiveTags[]` | `object ( `[`EffectiveTag`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.EffectiveTag)` )` Output only. The effective tags on the resource. The effective tags are fetched during troubleshooting.                                              |

### Resource

**JSON representation**

```
{
  "service": string,
  "name": string,
  "type": string
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `service` | `string` The name of the service that this resource belongs to, such as `compute.googleapis.com` . The service name might not match the DNS hostname that actually serves the request. For a full list of resource service values, see <https://cloud.google.com/iam/help/conditions/resource-services>                                                                         |
| `name`    | `string` The stable identifier (name) of a resource on the `service` . A resource can be logically identified as `//{resource.service}/{resource.name}` . Unlike the resource URI, the resource name doesn't contain any protocol and version information. For a list of full resource name formats, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> |
| `type`    | `string` The type of the resource, in the format `{service}/{kind}` . For a full list of resource type values, see <https://cloud.google.com/iam/help/conditions/resource-types>                                                                                                                                                                                                |

### Peer

**JSON representation**

```
{
  "ip": string,
  "port": string
}
```

| Fields |                                                                                                                      |
|--------|----------------------------------------------------------------------------------------------------------------------|
| `ip`   | `string` The IPv4 or IPv6 address of the peer.                                                                       |
| `port` | `string ( `[`int64`](https://developers.google.com/discovery/v1/type-format)` format)` The network port of the peer. |

### Request

**JSON representation**

```
{
  "receiveTime": string
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `receiveTime` | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Optional. The timestamp when the destination service receives the first byte of the request. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |

### Timestamp

**JSON representation**

```
{
  "seconds": string,
  "nanos": integer
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                      |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `seconds` | `string ( `[`int64`](https://developers.google.com/discovery/v1/type-format)` format)` Represents seconds of UTC time since Unix epoch 1970-01-01T00:00:00Z. Must be between -62135596800 and 253402300799 inclusive (which corresponds to 0001-01-01T00:00:00Z to 9999-12-31T23:59:59Z).                            |
| `nanos`   | `integer` Non-negative fractions of a second at nanosecond resolution. This field is the nanosecond portion of the duration, not an alternative to seconds. Negative second values with fractions must still have non-negative nanos values that count forward in time. Must be between 0 and 999,999,999 inclusive. |

### EffectiveTag

**JSON representation**

```
{
  "tagValue": string,
  "namespacedTagValue": string,
  "tagKey": string,
  "namespacedTagKey": string,
  "tagKeyParentName": string,
  "inherited": boolean
}
```

| Fields               |                                                                                                                                                                                                                                                                                                |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `tagValue`           | `string` Output only. Resource name for TagValue in the format `tagValues/456` .                                                                                                                                                                                                               |
| `namespacedTagValue` | `string` Output only. The namespaced name of the TagValue. Can be in the form `{organization_id}/{tag_key_short_name}/{tag_value_short_name}` or `{project_id}/{tag_key_short_name}/{tag_value_short_name}` or `{project_number}/{tag_key_short_name}/{tag_value_short_name}` .                |
| `tagKey`             | `string` Output only. The name of the TagKey, in the format `tagKeys/{id}` , such as `tagKeys/123` .                                                                                                                                                                                           |
| `namespacedTagKey`   | `string` Output only. The namespaced name of the TagKey. Can be in the form `{organization_id}/{tag_key_short_name}` or `{project_id}/{tag_key_short_name}` or `{project_number}/{tag_key_short_name}` .                                                                                       |
| `tagKeyParentName`   | `string` The parent name of the tag key. Must be in the format `organizations/{organization_id}` or `projects/{project_number}`                                                                                                                                                                |
| `inherited`          | `boolean` Output only. Indicates the inheritance status of a tag value attached to the given resource. If the tag value is inherited from one of the resource's ancestors, inherited will be true. If false, then the tag value is directly attached to the resource, inherited will be false. |

## Output Schema

Response for `TroubleshootIamPolicy` .

### TroubleshootIamPolicyResponse

**JSON representation**

```
{
  "overallAccessState": enum (OverallAccessState),
  "accessTuple": {
    object (AccessTuple)
  },
  "allowPolicyExplanation": {
    object (AllowPolicyExplanation)
  },
  "denyPolicyExplanation": {
    object (DenyPolicyExplanation)
  },
  "pabPolicyExplanation": {
    object (PABPolicyExplanation)
  }
}
```

| Fields                   |                                                                                                                                                                                                                                                                                                                                                       |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `overallAccessState`     | `enum ( `[`OverallAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.OverallAccessState)` )` Indicates whether the principal has the specified permission for the specified resource, based on evaluating all types of the applicable IAM policies. |
| `accessTuple`            | `object ( `[`AccessTuple`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.AccessTuple)` )` The access tuple from the request, including any provided context used to evaluate the condition.                                                                   |
| `allowPolicyExplanation` | `object ( `[`AllowPolicyExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AllowPolicyExplanation)` )` An explanation of how the applicable IAM allow policies affect the final access state.                                                       |
| `denyPolicyExplanation`  | `object ( `[`DenyPolicyExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyPolicyExplanation)` )` An explanation of how the applicable IAM deny policies affect the final access state.                                                          |
| `pabPolicyExplanation`   | `object ( `[`PABPolicyExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABPolicyExplanation)` )` An explanation of how the applicable principal access boundary policies affect the final access state.                                           |

### AccessTuple

**JSON representation**

```
{
  "principal": string,
  "fullResourceName": string,
  "permission": string,
  "permissionFqdn": string,
  "conditionContext": {
    object (ConditionContext)
  }
}
```

| Fields             |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal`        | `string` Required. The email address of the principal whose access you want to check. For example, `alice@example.com` or `my-service-account@my-project.iam.gserviceaccount.com` . The principal must be a Google Account or a service account. Other types of principals are not supported.                                                                                                                                                                                                                     |
| `fullResourceName` | `string` Required. The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                                                                       |
| `permission`       | `string` Required. The IAM permission to check for, either in the `v1` permission format or the `v2` permission format. For a complete list of IAM permissions in the `v1` format, see <https://cloud.google.com/iam/help/permissions/reference> . For a list of IAM permissions in the `v2` format, see <https://cloud.google.com/iam/help/deny/supported-permissions> . For a complete list of predefined IAM roles and the permissions in each role, see <https://cloud.google.com/iam/help/roles/reference> . |
| `permissionFqdn`   | `string` Output only. The permission that Policy Troubleshooter checked for, in the `v2` format.                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `conditionContext` | `object ( `[`ConditionContext`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.ConditionContext)` )` Optional. Additional context for the request, such as the request time or IP address. This context allows Policy Troubleshooter to troubleshoot conditional role bindings and deny rules.                                                                                                                             |

### ConditionContext

**JSON representation**

```
{
  "resource": {
    object (Resource)
  },
  "destination": {
    object (Peer)
  },
  "request": {
    object (Request)
  },
  "effectiveTags": [
    {
      object (EffectiveTag)
    }
  ]
}
```

| Fields            |                                                                                                                                                                                                                                                                                                                                          |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource`        | `object ( `[`Resource`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Resource)` )` Represents a target resource that is involved with a network activity. If multiple resources are involved with an activity, this must be the primary one.    |
| `destination`     | `object ( `[`Peer`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Peer)` )` The destination of a network activity, such as accepting a TCP connection. In a multi-hop network activity, the destination represents the receiver of the last hop. |
| `request`         | `object ( `[`Request`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.Request)` )` Represents a network request, such as an HTTP request.                                                                                                         |
| `effectiveTags[]` | `object ( `[`EffectiveTag`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Input.Schema.EffectiveTag)` )` Output only. The effective tags on the resource. The effective tags are fetched during troubleshooting.                                              |

### Resource

**JSON representation**

```
{
  "service": string,
  "name": string,
  "type": string
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `service` | `string` The name of the service that this resource belongs to, such as `compute.googleapis.com` . The service name might not match the DNS hostname that actually serves the request. For a full list of resource service values, see <https://cloud.google.com/iam/help/conditions/resource-services>                                                                         |
| `name`    | `string` The stable identifier (name) of a resource on the `service` . A resource can be logically identified as `//{resource.service}/{resource.name}` . Unlike the resource URI, the resource name doesn't contain any protocol and version information. For a list of full resource name formats, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> |
| `type`    | `string` The type of the resource, in the format `{service}/{kind}` . For a full list of resource type values, see <https://cloud.google.com/iam/help/conditions/resource-types>                                                                                                                                                                                                |

### Peer

**JSON representation**

```
{
  "ip": string,
  "port": string
}
```

| Fields |                                                                                                                      |
|--------|----------------------------------------------------------------------------------------------------------------------|
| `ip`   | `string` The IPv4 or IPv6 address of the peer.                                                                       |
| `port` | `string ( `[`int64`](https://developers.google.com/discovery/v1/type-format)` format)` The network port of the peer. |

### Request

**JSON representation**

```
{
  "receiveTime": string
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `receiveTime` | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Optional. The timestamp when the destination service receives the first byte of the request. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |

### Timestamp

**JSON representation**

```
{
  "seconds": string,
  "nanos": integer
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                      |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `seconds` | `string ( `[`int64`](https://developers.google.com/discovery/v1/type-format)` format)` Represents seconds of UTC time since Unix epoch 1970-01-01T00:00:00Z. Must be between -62135596800 and 253402300799 inclusive (which corresponds to 0001-01-01T00:00:00Z to 9999-12-31T23:59:59Z).                            |
| `nanos`   | `integer` Non-negative fractions of a second at nanosecond resolution. This field is the nanosecond portion of the duration, not an alternative to seconds. Negative second values with fractions must still have non-negative nanos values that count forward in time. Must be between 0 and 999,999,999 inclusive. |

### EffectiveTag

**JSON representation**

```
{
  "tagValue": string,
  "namespacedTagValue": string,
  "tagKey": string,
  "namespacedTagKey": string,
  "tagKeyParentName": string,
  "inherited": boolean
}
```

| Fields               |                                                                                                                                                                                                                                                                                                |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `tagValue`           | `string` Output only. Resource name for TagValue in the format `tagValues/456` .                                                                                                                                                                                                               |
| `namespacedTagValue` | `string` Output only. The namespaced name of the TagValue. Can be in the form `{organization_id}/{tag_key_short_name}/{tag_value_short_name}` or `{project_id}/{tag_key_short_name}/{tag_value_short_name}` or `{project_number}/{tag_key_short_name}/{tag_value_short_name}` .                |
| `tagKey`             | `string` Output only. The name of the TagKey, in the format `tagKeys/{id}` , such as `tagKeys/123` .                                                                                                                                                                                           |
| `namespacedTagKey`   | `string` Output only. The namespaced name of the TagKey. Can be in the form `{organization_id}/{tag_key_short_name}` or `{project_id}/{tag_key_short_name}` or `{project_number}/{tag_key_short_name}` .                                                                                       |
| `tagKeyParentName`   | `string` The parent name of the tag key. Must be in the format `organizations/{organization_id}` or `projects/{project_number}`                                                                                                                                                                |
| `inherited`          | `boolean` Output only. Indicates the inheritance status of a tag value attached to the given resource. If the tag value is inherited from one of the resource's ancestors, inherited will be true. If false, then the tag value is directly attached to the resource, inherited will be false. |

### AllowPolicyExplanation

**JSON representation**

```
{
  "allowAccessState": enum (AllowAccessState),
  "explainedPolicies": [
    {
      object (ExplainedAllowPolicy)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `allowAccessState`    | `enum ( `[`AllowAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AllowAccessState)` )` Indicates whether the principal has the specified permission for the specified resource, based on evaluating all applicable IAM allow policies.                                                                                                                                                                                                                                                                                                                                                             |
| `explainedPolicies[]` | `object ( `[`ExplainedAllowPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedAllowPolicy)` )` List of IAM allow policies that were evaluated to check the principal's permissions, with annotations to indicate how each policy contributed to the final result. The list of policies includes the policy for the resource itself, as well as allow policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project. To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> . |
| `relevance`           | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the allow policy type to the overall access state.                                                                                                                                                                                                                                                                                                                                                                                                                                     |

### ExplainedAllowPolicy

**JSON representation**

```
{
  "allowAccessState": enum (AllowAccessState),
  "fullResourceName": string,
  "bindingExplanations": [
    {
      object (AllowBindingExplanation)
    }
  ],
  "relevance": enum (HeuristicRelevance),
  "policy": {
    object (Policy)
  }
}
```

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `allowAccessState`      | `enum ( `[`AllowAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AllowAccessState)` )` Required. Indicates whether *this policy* provides the specified permission to the specified principal for the specified resource. This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . |
| `fullResourceName`      | `string` The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . If the sender of the request does not have access to the policy, this field is omitted. For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                                                                                                                                                                                                                                                                                        |
| `bindingExplanations[]` | `object ( `[`AllowBindingExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AllowBindingExplanation)` )` Details about how each role binding in the policy affects the principal's ability, or inability, to use the permission for the resource. The order of the role bindings matches the role binding order in the policy. If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                                                                         |
| `relevance`             | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this policy to the overall access state in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                                 |
| `policy`                | `object ( `[`Policy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Policy)` )` The IAM allow policy attached to the resource. If the sender of the request does not have access to the policy, this field is empty.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

### AllowBindingExplanation

**JSON representation**

```
{
  "allowAccessState": enum (AllowAccessState),
  "role": string,
  "rolePermission": enum (RolePermissionInclusionState),
  "rolePermissionRelevance": enum (HeuristicRelevance),
  "combinedMembership": {
    object (AnnotatedAllowMembership)
  },
  "memberships": {
    string: {
      object (AnnotatedAllowMembership)
    },
    ...
  },
  "relevance": enum (HeuristicRelevance),
  "condition": {
    object (Expr)
  },
  "conditionExplanation": {
    object (ConditionExplanation)
  }
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
<td><code>allowAccessState</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AllowAccessState"><code>AllowAccessState</code></a><code> )</code></p>
<p>Required. Indicates whether <em>this role binding</em> gives the specified permission to the specified principal on the specified resource.</p>
<p>This field does <em>not</em> indicate whether the principal actually has the permission on the resource. There might be another role binding that overrides this role binding. To determine whether the principal actually has the permission, use the <code>overall_access_state</code> field in the <a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse"><code>TroubleshootIamPolicyResponse</code></a> .</p></td>
</tr>
<tr class="even">
<td><code>role</code></td>
<td><p><code>string</code></p>
<p>The role that this role binding grants. For example, <code>roles/compute.admin</code> .</p>
<p>For a complete list of predefined IAM roles, as well as the permissions in each role, see <a href="https://cloud.google.com/iam/help/roles/reference">https://cloud.google.com/iam/help/roles/reference</a> .</p></td>
</tr>
<tr class="odd">
<td><code>rolePermission</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.RolePermissionInclusionState"><code>RolePermissionInclusionState</code></a><code> )</code></p>
<p>Indicates whether the role granted by this role binding contains the specified permission.</p></td>
</tr>
<tr class="even">
<td><code>rolePermissionRelevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of the permission's existence, or nonexistence, in the role to the overall determination for the entire policy.</p></td>
</tr>
<tr class="odd">
<td><code>combinedMembership</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedAllowMembership"><code>AnnotatedAllowMembership</code></a><code> )</code></p>
<p>The combined result of all memberships. Indicates if the principal is included in any role binding, either directly or indirectly.</p></td>
</tr>
<tr class="even">
<td><code>memberships</code></td>
<td><p><code>map (key: string, value: object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedAllowMembership"><code>AnnotatedAllowMembership</code></a><code> ))</code></p>
<p>Indicates whether each role binding includes the principal specified in the request, either directly or indirectly. Each key identifies a principal in the role binding, and each value indicates whether the principal in the role binding includes the principal in the request.</p>
<p>For example, suppose that a role binding includes the following principals:</p>
<ul>
<li><code>user:alice@example.com</code></li>
<li><code>group:product-eng@example.com</code></li>
</ul>
<p>You want to troubleshoot access for <code>user:bob@example.com</code> . This user is a member of the group <code>group:product-eng@example.com</code> .</p>
<p>For the first principal in the role binding, the key is <code>user:alice@example.com</code> , and the <code>membership</code> field in the value is set to <code>NOT_INCLUDED</code> .</p>
<p>For the second principal in the role binding, the key is <code>group:product-eng@example.com</code> , and the <code>membership</code> field in the value is set to <code>INCLUDED</code> .</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><code>relevance</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance"><code>HeuristicRelevance</code></a><code> )</code></p>
<p>The relevance of this role binding to the overall determination for the entire policy.</p></td>
</tr>
<tr class="even">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>A condition expression that specifies when the role binding grants access.</p>
<p>To learn about IAM Conditions, see <a href="https://cloud.google.com/iam/help/conditions/overview">https://cloud.google.com/iam/help/conditions/overview</a> .</p></td>
</tr>
<tr class="odd">
<td><code>conditionExplanation</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ConditionExplanation"><code>ConditionExplanation</code></a><code> )</code></p>
<p>Condition evaluation state for this role binding.</p></td>
</tr>
</tbody>
</table>

### AnnotatedAllowMembership

**JSON representation**

```
{
  "membership": enum (MembershipMatchingState),
  "relevance": enum (HeuristicRelevance)
}
```

| Fields       |                                                                                                                                                                                                                                                                                           |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `membership` | `enum ( `[`MembershipMatchingState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.MembershipMatchingState)` )` Indicates whether the role binding includes the principal.                       |
| `relevance`  | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the principal's status to the overall determination for the role binding. |

### MembershipsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (AnnotatedAllowMembership)
  }
}
```

| Fields  |                                                                                                                                                                                                              |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                                                                                                     |
| `value` | `object ( `[`AnnotatedAllowMembership`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedAllowMembership)` )` |

### Expr

**JSON representation**

```
{
  "expression": string,
  "title": string,
  "description": string,
  "location": string
}
```

| Fields        |                                                                                                                                                            |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `expression`  | `string` Textual representation of an expression in Common Expression Language syntax.                                                                     |
| `title`       | `string` Optional. Title for the expression, i.e. a short string describing its purpose. This can be used e.g. in UIs which allow to enter the expression. |
| `description` | `string` Optional. Description of the expression. This is a longer text which describes the expression, e.g. when hovered over it in a UI.                 |
| `location`    | `string` Optional. String indicating the location of the expression for error reporting, e.g. a file name and a position in the file.                      |

### ConditionExplanation

**JSON representation**

```
{
  "value": value,
  "errors": [
    {
      object (Status)
    }
  ],
  "evaluationStates": [
    {
      object (EvaluationState)
    }
  ]
}
```

| Fields               |                                                                                                                                                                                                                                                                                                                                                              |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `value`              | `value ( `[`Value`](https://protobuf.dev/reference/protobuf/google.protobuf/#value)` format)` Value of the condition.                                                                                                                                                                                                                                        |
| `errors[]`           | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Status)` )` Any errors that prevented complete evaluation of the condition expression.                                                                                                          |
| `evaluationStates[]` | `object ( `[`EvaluationState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.EvaluationState)` )` The value of each statement of the condition expression. The value can be `true` , `false` , or `null` . The value is `null` if the statement can't be evaluated. |

### Value

**JSON representation**

```
{

  // Union field kind can be only one of the following:
  "nullValue": null,
  "numberValue": number,
  "stringValue": string,
  "boolValue": boolean,
  "structValue": {
    object
  },
  "listValue": array
  // End of list of possible types for union field kind.
}
```

| Fields                                                                           |                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `kind` . The kind of value. `kind` can be only one of the following: |                                                                                                                                                                                                                                                |
| `nullValue`                                                                      | `null` Represents a JSON `null` .                                                                                                                                                                                                              |
| `numberValue`                                                                    | `number` Represents a JSON number. Must not be `NaN` , `Infinity` or `-Infinity` , since those are not supported in JSON. This also cannot represent large Int64 values, since JSON format generally does not support them in its number type. |
| `stringValue`                                                                    | `string` Represents a JSON string.                                                                                                                                                                                                             |
| `boolValue`                                                                      | `boolean` Represents a JSON boolean ( `true` or `false` literal in JSON).                                                                                                                                                                      |
| `structValue`                                                                    | `object ( `[`Struct`](https://protobuf.dev/reference/protobuf/google.protobuf/#struct)` format)` Represents a JSON object.                                                                                                                     |
| `listValue`                                                                      | `array ( `[`ListValue`](https://protobuf.dev/reference/protobuf/google.protobuf/#list-value)` format)` Represents a JSON array.                                                                                                                |

### Struct

**JSON representation**

```
{
  "fields": {
    string: value,
    ...
  }
}
```

| Fields   |                                                                                                                                                                                                                                                                                          |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `fields` | `map (key: string, value: value ( `[`Value`](https://protobuf.dev/reference/protobuf/google.protobuf/#value)` format))` Unordered map of dynamically typed values. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` . |

### FieldsEntry

**JSON representation**

```
{
  "key": string,
  "value": value
}
```

| Fields  |                                                                                               |
|---------|-----------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                      |
| `value` | `value ( `[`Value`](https://protobuf.dev/reference/protobuf/google.protobuf/#value)` format)` |

### ListValue

**JSON representation**

```
{
  "values": [
    value
  ]
}
```

| Fields     |                                                                                                                                           |
|------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| `values[]` | `value ( `[`Value`](https://protobuf.dev/reference/protobuf/google.protobuf/#value)` format)` Repeated field of dynamically typed values. |

### Status

**JSON representation**

```
{
  "code": integer,
  "message": string,
  "details": [
    {
      "@type": string,
      field1: ...,
      ...
    }
  ]
}
```

| Fields      |                                                                                                                                                                                                                                                                                                              |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `code`      | `integer` The status code, which should be an enum value of `google.rpc.Code` .                                                                                                                                                                                                                              |
| `message`   | `string` A developer-facing error message, which should be in English. Any user-facing error message should be localized and sent in the `google.rpc.Status.details` field, or localized by the client.                                                                                                      |
| `details[]` | `object` A list of messages that carry the error details. There is a common set of message types for APIs to use. An object containing fields of an arbitrary type. An additional field `"@type"` contains a URI identifying the type. Example: `{ "id": 1234, "@type": "types.example.com/standard/id" }` . |

### Any

**JSON representation**

```
{
  "typeUrl": string,
  "value": string
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `typeUrl` | `string` Identifies the type of the serialized Protobuf message with a URI reference consisting of a prefix ending in a slash and the fully-qualified type name. Example: type.googleapis.com/google.protobuf.StringValue This string must contain at least one `/` character, and the content after the last `/` must be the fully-qualified name of the type in canonical form, without a leading dot. Do not write a scheme on these URI references so that clients do not attempt to contact them. The prefix is arbitrary and Protobuf implementations are expected to simply strip off everything up to and including the last `/` to identify the type. `type.googleapis.com/` is a common default prefix that some legacy implementations require. This prefix does not indicate the origin of the type, and URIs containing it are not expected to respond to any requests. All type URL strings must be legal URI references with the additional restriction (for the text format) that the content of the reference must consist only of alphanumeric characters, percent-encoded escapes, and characters in the following set (not including the outer backticks): `/-.~_!$&()*+,;=` . Despite our allowing percent encodings, implementations should not unescape them to prevent confusion with existing parsers. For example, `type.googleapis.com%2FFoo` should be rejected. In the original design of `Any` , the possibility of launching a type resolution service at these type URLs was considered but Protobuf never implemented one and considers contacting these URLs to be problematic and a potential security issue. Do not attempt to contact type URLs. |
| `value`   | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Holds a Protobuf serialization of the type described by type_url. A base64-encoded string.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

### EvaluationState

**JSON representation**

```
{
  "start": integer,
  "end": integer,
  "value": value,
  "errors": [
    {
      object (Status)
    }
  ]
}
```

| Fields     |                                                                                                                                                                                                                                                     |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `start`    | `integer` Start position of an expression in the condition, by character.                                                                                                                                                                           |
| `end`      | `integer` End position of an expression in the condition, by character, end included, for example: the end position of the first part of `a==b || c==d` would be 4.                                                                                 |
| `value`    | `value ( `[`Value`](https://protobuf.dev/reference/protobuf/google.protobuf/#value)` format)` Value of this expression.                                                                                                                             |
| `errors[]` | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Status)` )` Any errors that prevented complete evaluation of the condition expression. |

### Policy

**JSON representation**

```
{
  "version": integer,
  "bindings": [
    {
      object (Binding)
    }
  ],
  "auditConfigs": [
    {
      object (AuditConfig)
    }
  ],
  "etag": string
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
<td><code>version</code></td>
<td><p><code>integer</code></p>
<p>Specifies the format of the policy.</p>
<p>Valid values are <code>0</code> , <code>1</code> , and <code>3</code> . Requests that specify an invalid value are rejected.</p>
<p>Any operation that affects conditional role bindings must specify version <code>3</code> . This requirement applies to the following operations:</p>
<ul>
<li>Getting a policy that includes a conditional role binding</li>
<li>Adding a conditional role binding to a policy</li>
<li>Changing a conditional role binding in a policy</li>
<li>Removing any role binding, with or without a condition, from a policy that includes conditions</li>
</ul>
<p><strong>Important:</strong> If you use IAM Conditions, you must include the <code>etag</code> field whenever you call <code>setIamPolicy</code> . If you omit this field, then IAM allows you to overwrite a version <code>3</code> policy with a version <code>1</code> policy, and all of the conditions in the version <code>3</code> policy are lost.</p>
<p>If a policy does not include any conditions, operations on that policy may specify any valid version or leave the field unset.</p>
<p>To learn which resources support conditions in their IAM policies, see the <a href="https://cloud.google.com/iam/help/conditions/resource-policies">IAM documentation</a> .</p></td>
</tr>
<tr class="even">
<td><code>bindings[]</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Binding"><code>Binding</code></a><code> )</code></p>
<p>Associates a list of <code>members</code> , or principals, with a <code>role</code> . Optionally, may specify a <code>condition</code> that determines how and when the <code>bindings</code> are applied. Each of the <code>bindings</code> must contain at least one principal.</p>
<p>The <code>bindings</code> in a <code>Policy</code> can refer to up to 1,500 principals; up to 250 of these principals can be Google groups. Each occurrence of a principal counts towards these limits. For example, if the <code>bindings</code> grant 50 different roles to <code>user:alice@example.com</code> , and not to any other principal, then you can add another 1,450 principals to the <code>bindings</code> in the <code>Policy</code> .</p></td>
</tr>
<tr class="odd">
<td><code>auditConfigs[]</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AuditConfig"><code>AuditConfig</code></a><code> )</code></p>
<p>Specifies cloud audit logging configuration for this policy.</p></td>
</tr>
<tr class="even">
<td><code>etag</code></td>
<td><p><code>string ( </code><a href="https://developers.google.com/discovery/v1/type-format"><code>bytes</code></a><code> format)</code></p>
<p><code>etag</code> is used for optimistic concurrency control as a way to help prevent simultaneous updates of a policy from overwriting each other. It is strongly suggested that systems make use of the <code>etag</code> in the read-modify-write cycle to perform policy updates in order to avoid race conditions: An <code>etag</code> is returned in the response to <code>getIamPolicy</code> , and systems are expected to put that etag in the request to <code>setIamPolicy</code> to ensure that their change will be applied to the same version of the policy.</p>
<p><strong>Important:</strong> If you use IAM Conditions, you must include the <code>etag</code> field whenever you call <code>setIamPolicy</code> . If you omit this field, then IAM allows you to overwrite a version <code>3</code> policy with a version <code>1</code> policy, and all of the conditions in the version <code>3</code> policy are lost.</p>
<p>A base64-encoded string.</p></td>
</tr>
</tbody>
</table>

### Binding

**JSON representation**

```
{
  "role": string,
  "members": [
    string
  ],
  "condition": {
    object (Expr)
  }
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
<td><code>role</code></td>
<td><p><code>string</code></p>
<p>Role that is assigned to the list of <code>members</code> , or principals. For example, <code>roles/viewer</code> , <code>roles/editor</code> , or <code>roles/owner</code> .</p>
<p>For an overview of the IAM roles and permissions, see the <a href="https://cloud.google.com/iam/docs/roles-overview">IAM documentation</a> . For a list of the available pre-defined roles, see <a href="https://cloud.google.com/iam/docs/understanding-roles">here</a> .</p></td>
</tr>
<tr class="even">
<td><code>members[]</code></td>
<td><p><code>string</code></p>
<p>Specifies the principals requesting access for a Google Cloud resource. <code>members</code> can have the following values:</p>
<ul>
<li><p><code>allUsers</code> : A special identifier that represents anyone who is on the internet; with or without a Google account.</p></li>
<li><p><code>allAuthenticatedUsers</code> : A special identifier that represents anyone who is authenticated with a Google account or a service account. Does not include identities that come from external identity providers (IdPs) through identity federation.</p></li>
<li><p><code>user:{emailid}</code> : An email address that represents a specific Google account. For example, <code>alice@example.com</code> .</p></li>
</ul>
<ul>
<li><p><code>serviceAccount:{emailid}</code> : An email address that represents a Google service account. For example, <code>my-other-app@appspot.gserviceaccount.com</code> .</p></li>
<li><p><code>serviceAccount:{projectid}.svc.id.goog[{namespace}/{kubernetes-sa}]</code> : An identifier for a <a href="https://cloud.google.com/kubernetes-engine/docs/how-to/kubernetes-service-accounts">Kubernetes service account</a> . For example, <code>my-project.svc.id.goog[my-namespace/my-kubernetes-sa]</code> .</p></li>
<li><p><code>group:{emailid}</code> : An email address that represents a Google group. For example, <code>admins@example.com</code> .</p></li>
</ul>
<ul>
<li><code>domain:{domain}</code> : The G Suite domain (primary) that represents all the users of that domain. For example, <code>google.com</code> or <code>example.com</code> .</li>
</ul>
<ul>
<li><p><code>principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workforce identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}</code> : All workforce identities in a group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All workforce identities with a specific attribute value.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*</code> : All identities in a workforce identity pool.</p></li>
<li><p><code>principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workload identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}</code> : A workload identity pool group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All identities in a workload identity pool with a certain attribute.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*</code> : All identities in a workload identity pool.</p></li>
<li><p><code>deleted:user:{emailid}?uid={uniqueid}</code> : An email address (plus unique identifier) representing a user that has been recently deleted. For example, <code>alice@example.com?uid=123456789012345678901</code> . If the user is recovered, this value reverts to <code>user:{emailid}</code> and the recovered user retains the role in the binding.</p></li>
<li><p><code>deleted:serviceAccount:{emailid}?uid={uniqueid}</code> : An email address (plus unique identifier) representing a service account that has been recently deleted. For example, <code>my-other-app@appspot.gserviceaccount.com?uid=123456789012345678901</code> . If the service account is undeleted, this value reverts to <code>serviceAccount:{emailid}</code> and the undeleted service account retains the role in the binding.</p></li>
<li><p><code>deleted:group:{emailid}?uid={uniqueid}</code> : An email address (plus unique identifier) representing a Google group that has been recently deleted. For example, <code>admins@example.com?uid=123456789012345678901</code> . If the group is recovered, this value reverts to <code>group:{emailid}</code> and the recovered group retains the role in the binding.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : Deleted single identity in a workforce identity pool. For example, <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code> .</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>The condition that is associated with this binding.</p>
<p>If the condition evaluates to <code>true</code> , then this binding applies to the current request.</p>
<p>If the condition evaluates to <code>false</code> , then this binding does not apply to the current request. However, a different role binding might grant the same role to one or more of the principals in this binding.</p>
<p>To learn which resources support conditions in their IAM policies, see the <a href="https://cloud.google.com/iam/help/conditions/resource-policies">IAM documentation</a> .</p></td>
</tr>
</tbody>
</table>

### AuditConfig

**JSON representation**

```
{
  "service": string,
  "auditLogConfigs": [
    {
      object (AuditLogConfig)
    }
  ]
}
```

| Fields              |                                                                                                                                                                                                                                                    |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `service`           | `string` Specifies a service that will be enabled for audit logging. For example, `storage.googleapis.com` , `cloudsql.googleapis.com` . `allServices` is a special value that covers all services.                                                |
| `auditLogConfigs[]` | `object ( `[`AuditLogConfig`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AuditLogConfig)` )` The configuration for logging of each type of permission. |

### AuditLogConfig

**JSON representation**

```
{
  "logType": enum (LogType),
  "exemptedMembers": [
    string
  ]
}
```

| Fields              |                                                                                                                                                                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `logType`           | `enum ( `[`LogType`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.LogType)` )` The log type that this config enables. |
| `exemptedMembers[]` | `string` Specifies the identities that do not cause logging for this type of permission. Follows the same format of `Binding.members` .                                                                         |

### DenyPolicyExplanation

**JSON representation**

```
{
  "denyAccessState": enum (DenyAccessState),
  "explainedResources": [
    {
      object (ExplainedDenyResource)
    }
  ],
  "relevance": enum (HeuristicRelevance),
  "permissionDeniable": boolean
}
```

| Fields                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `denyAccessState`      | `enum ( `[`DenyAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyAccessState)` )` Indicates whether the principal is denied the specified permission for the specified resource, based on evaluating all applicable IAM deny policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `explainedResources[]` | `object ( `[`ExplainedDenyResource`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedDenyResource)` )` List of resources with IAM deny policies that were evaluated to check the principal's denied permissions, with annotations to indicate how each policy contributed to the final result. The list of resources includes the policy for the resource itself, as well as policies that are inherited from higher levels of the resource hierarchy, including the organization, the folder, and the project. The order of the resources starts from the resource and climbs up the resource hierarchy. To learn more about the resource hierarchy, see <https://cloud.google.com/iam/help/resource-hierarchy> . |
| `relevance`            | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the deny policy result to the overall access state.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `permissionDeniable`   | `boolean` Indicates whether the permission to troubleshoot is supported in deny policies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

### ExplainedDenyResource

**JSON representation**

```
{
  "denyAccessState": enum (DenyAccessState),
  "fullResourceName": string,
  "explainedPolicies": [
    {
      object (ExplainedDenyPolicy)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `denyAccessState`     | `enum ( `[`DenyAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyAccessState)` )` Required. Indicates whether any policies attached to *this resource* deny the specific permission to the specified principal for the specified resource. This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . |
| `fullResourceName`    | `string` The full resource name that identifies the resource. For example, `//compute.googleapis.com/projects/my-project/zones/us-central1-a/instances/my-instance` . If the sender of the request does not have access to the policy, this field is omitted. For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `explainedPolicies[]` | `object ( `[`ExplainedDenyPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedDenyPolicy)` )` List of IAM deny policies that were evaluated to check the principal's denied permissions, with annotations to indicate how each policy contributed to the final result.                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `relevance`           | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this policy to the overall access state in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                                                     |

### ExplainedDenyPolicy

**JSON representation**

```
{
  "denyAccessState": enum (DenyAccessState),
  "policy": {
    object (Policy)
  },
  "ruleExplanations": [
    {
      object (DenyRuleExplanation)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `denyAccessState`    | `enum ( `[`DenyAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyAccessState)` )` Required. Indicates whether *this policy* denies the specified permission to the specified principal for the specified resource. This field does *not* indicate whether the principal actually has the permission for the resource. There might be another policy that overrides this policy. To determine whether the principal actually has the permission, use the `overall_access_state` field in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . |
| `policy`             | `object ( `[`Policy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Policy_1)` )` The IAM deny policy attached to the resource. If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `ruleExplanations[]` | `object ( `[`DenyRuleExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyRuleExplanation)` )` Details about how each rule in the policy affects the principal's inability to use the permission for the resource. The order of the deny rule matches the order of the rules in the deny policy. If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                                                                                                 |
| `relevance`          | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this policy to the overall access state in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . If the sender of the request does not have access to the policy, this field is omitted.                                                                                                                                                                                                                                             |

### Policy

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "kind": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "etag": string,
  "createTime": string,
  "updateTime": string,
  "deleteTime": string,
  "rules": [
    {
      object (PolicyRule)
    }
  ]
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | `string` Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachment_point}/denypolicies/{policy_id}` The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID. |
| `uid`         | `string` Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `kind`        | `string` Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `displayName` | `string` A user-specified description of the `Policy` . This value can be up to 63 characters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `annotations` | `map (key: string, value: string)` A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                                                                                                                                                                                     |
| `etag`        | `string` An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another. If this field is present in a `CreatePolicyRequest` , the value is ignored.                                                                                                                                                                                                                                                                                                                                    |
| `createTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was created. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                                                       |
| `updateTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was last updated. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                                                  |
| `deleteTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                   |
| `rules[]`     | `object ( `[`PolicyRule`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PolicyRule)` )` A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .                                                                                                                                                                                                                                                                                                |

### AnnotationsEntry

**JSON representation**

```
{
  "key": string,
  "value": string
}
```

| Fields  |          |
|---------|----------|
| `key`   | `string` |
| `value` | `string` |

### PolicyRule

**JSON representation**

```
{
  "description": string,

  // Union field kind can be only one of the following:
  "denyRule": {
    object (DenyRule)
  }
  // End of list of possible types for union field kind.
}
```

| Fields                                                        |                                                                                                                                                                                                        |
|---------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `description`                                                 | `string` A user-specified description of the rule. This value can be up to 256 characters.                                                                                                             |
| Union field `kind` . `kind` can be only one of the following: |                                                                                                                                                                                                        |
| `denyRule`                                                    | `object ( `[`DenyRule`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyRule)` )` A rule for a deny policy. |

### DenyRule

**JSON representation**

```
{
  "deniedPrincipals": [
    string
  ],
  "exceptionPrincipals": [
    string
  ],
  "deniedPermissions": [
    string
  ],
  "exceptionPermissions": [
    string
  ],
  "denialCondition": {
    object (Expr)
  }
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
<td><code>deniedPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:</p>
<ul>
<li><p><code>principal://goog/subject/{email_id}</code> : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, <code>principal://goog/subject/alice@example.com</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}</code> : A Google Cloud service account. For example, <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com</code> .</p></li>
<li><p><code>principalSet://goog/group/{group_id}</code> : A Google group. For example, <code>principalSet://goog/group/admins@example.com</code> .</p></li>
<li><p><code>principalSet://goog/public:all</code> : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.</p></li>
<li><p><code>principalSet://goog/cloudIdentityCustomerId/{customer_id}</code> : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workforce identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}</code> : All workforce identities in a group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All workforce identities with a specific attribute value.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*</code> : All identities in a workforce identity pool.</p></li>
<li><p><code>principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workload identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}</code> : A workload identity pool group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All identities in a workload identity pool with a certain attribute.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*</code> : All identities in a workload identity pool.</p></li>
<li><p><code>principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAccount</code> : All service accounts grouped under a resource (project, folder, or organization).</p></li>
<li><p><code>principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAgent</code> : All service agents grouped under a resource (project, folder, or organization).</p></li>
<li><p><code>deleted:principal://goog/subject/{email_id}?uid={uid}</code> : A specific Google Account that was deleted recently. For example, <code>deleted:principal://goog/subject/alice@example.com?uid=1234567890</code> . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.</p></li>
<li><p><code>deleted:principalSet://goog/group/{group_id}?uid={uid}</code> : A Google group that was deleted recently. For example, <code>deleted:principalSet://goog/group/admins@example.com?uid=1234567890</code> . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}</code> : A Google Cloud service account that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890</code> . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : Deleted single identity in a workforce identity pool. For example, <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code> .</p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>exceptionPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>The identities that are excluded from the deny rule, even if they are listed in the <code>denied_principals</code> . For example, you could add a Google group to the <code>denied_principals</code> , then exclude specific users who belong to that group.</p>
<p>This field can contain the same values as the <code>denied_principals</code> field, excluding <code>principalSet://goog/public:all</code> , which represents all users on the internet.</p></td>
</tr>
<tr class="odd">
<td><code>deniedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>The permissions that are explicitly denied by this rule. Each permission uses the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. For example, <code>iam.googleapis.com/roles.list</code> .</p></td>
</tr>
<tr class="even">
<td><code>exceptionPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Specifies the permissions that this rule excludes from the set of denied permissions given by <code>denied_permissions</code> . If a permission appears in <code>denied_permissions</code> <em>and</em> in <code>exception_permissions</code> then it will <em>not</em> be denied.</p>
<p>The excluded permissions can be specified using the same syntax as <code>denied_permissions</code> .</p></td>
</tr>
<tr class="odd">
<td><code>denialCondition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to <code>true</code> , then the deny rule is applied; otherwise, the deny rule is not applied.</p>
<p>Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.</p>
<p>The condition can use CEL functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> . Other functions and operators are not supported.</p></td>
</tr>
</tbody>
</table>

### DenyRuleExplanation

**JSON representation**

```
{
  "denyAccessState": enum (DenyAccessState),
  "combinedDeniedPermission": {
    object (AnnotatedPermissionMatching)
  },
  "deniedPermissions": {
    string: {
      object (AnnotatedPermissionMatching)
    },
    ...
  },
  "combinedExceptionPermission": {
    object (AnnotatedPermissionMatching)
  },
  "exceptionPermissions": {
    string: {
      object (AnnotatedPermissionMatching)
    },
    ...
  },
  "combinedDeniedPrincipal": {
    object (AnnotatedDenyPrincipalMatching)
  },
  "deniedPrincipals": {
    string: {
      object (AnnotatedDenyPrincipalMatching)
    },
    ...
  },
  "combinedExceptionPrincipal": {
    object (AnnotatedDenyPrincipalMatching)
  },
  "exceptionPrincipals": {
    string: {
      object (AnnotatedDenyPrincipalMatching)
    },
    ...
  },
  "relevance": enum (HeuristicRelevance),
  "condition": {
    object (Expr)
  },
  "conditionExplanation": {
    object (ConditionExplanation)
  }
}
```

| Fields                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `denyAccessState`             | `enum ( `[`DenyAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.DenyAccessState)` )` Required. Indicates whether *this rule* denies the specified permission to the specified principal for the specified resource. This field does *not* indicate whether the principal is actually denied on the permission for the resource. There might be another rule that overrides this rule. To determine whether the principal actually has the permission, use the `overall_access_state` field in the [`TroubleshootIamPolicyResponse`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.TroubleshootIamPolicyResponse) . |
| `combinedDeniedPermission`    | `object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` )` Indicates whether the permission in the request is listed as a denied permission in the deny rule.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `deniedPermissions`           | `map (key: string, value: object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` ))` Lists all denied permissions in the deny rule and indicates whether each permission matches the permission in the request. Each key identifies a denied permission in the rule, and each value indicates whether the denied permission matches the permission in the request. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                                |
| `combinedExceptionPermission` | `object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` )` Indicates whether the permission in the request is listed as an exception permission in the deny rule.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `exceptionPermissions`        | `map (key: string, value: object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` ))` Lists all exception permissions in the deny rule and indicates whether each permission matches the permission in the request. Each key identifies a exception permission in the rule, and each value indicates whether the exception permission matches the permission in the request. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                       |
| `combinedDeniedPrincipal`     | `object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` )` Indicates whether the principal is listed as a denied principal in the deny rule, either directly or through membership in a principal set.                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `deniedPrincipals`            | `map (key: string, value: object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` ))` Lists all denied principals in the deny rule and indicates whether each principal matches the principal in the request, either directly or through membership in a principal set. Each key identifies a denied principal in the rule, and each value indicates whether the denied principal matches the principal in the request. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                      |
| `combinedExceptionPrincipal`  | `object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` )` Indicates whether the principal is listed as an exception principal in the deny rule, either directly or through membership in a principal set.                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `exceptionPrincipals`         | `map (key: string, value: object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` ))` Lists all exception principals in the deny rule and indicates whether each principal matches the principal in the request, either directly or through membership in a principal set. Each key identifies a exception principal in the rule, and each value indicates whether the exception principal matches the principal in the request. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                             |
| `relevance`                   | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this role binding to the overall determination for the entire policy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `condition`                   | `object ( `[`Expr`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Expr)` )` A condition expression that specifies when the deny rule denies the principal access. To learn about IAM Conditions, see <https://cloud.google.com/iam/help/conditions/overview> .                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `conditionExplanation`        | `object ( `[`ConditionExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ConditionExplanation)` )` Condition evaluation state for this role binding.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

### AnnotatedPermissionMatching

**JSON representation**

```
{
  "permissionMatchingState": enum (PermissionPatternMatchingState),
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                    |                                                                                                                                                                                                                                                                                                    |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `permissionMatchingState` | `enum ( `[`PermissionPatternMatchingState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PermissionPatternMatchingState)` )` Indicates whether the permission in the request is denied by the deny rule. |
| `relevance`               | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the permission status to the overall determination for the rule.                   |

### DeniedPermissionsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (AnnotatedPermissionMatching)
  }
}
```

| Fields  |                                                                                                                                                                                                                    |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                                                                                                           |
| `value` | `object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` )` |

### ExceptionPermissionsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (AnnotatedPermissionMatching)
  }
}
```

| Fields  |                                                                                                                                                                                                                    |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                                                                                                           |
| `value` | `object ( `[`AnnotatedPermissionMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedPermissionMatching)` )` |

### AnnotatedDenyPrincipalMatching

**JSON representation**

```
{
  "membership": enum (MembershipMatchingState),
  "relevance": enum (HeuristicRelevance)
}
```

| Fields       |                                                                                                                                                                                                                                                                                                                                                      |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `membership` | `enum ( `[`MembershipMatchingState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.MembershipMatchingState)` )` Indicates whether the principal is listed as a denied principal in the deny rule, either directly or through membership in a principal set. |
| `relevance`  | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the principal's status to the overall determination for the role binding.                                                            |

### DeniedPrincipalsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (AnnotatedDenyPrincipalMatching)
  }
}
```

| Fields  |                                                                                                                                                                                                                          |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                                                                                                                 |
| `value` | `object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` )` |

### ExceptionPrincipalsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (AnnotatedDenyPrincipalMatching)
  }
}
```

| Fields  |                                                                                                                                                                                                                          |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                                                                                                                 |
| `value` | `object ( `[`AnnotatedDenyPrincipalMatching`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.AnnotatedDenyPrincipalMatching)` )` |

### PABPolicyExplanation

**JSON representation**

```
{
  "principalAccessBoundaryAccessState": enum (PABAccessState),
  "explainedBindingsAndPolicies": [
    {
      object (ExplainedPABBindingAndPolicy)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                               |                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principalAccessBoundaryAccessState` | `enum ( `[`PABAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABAccessState)` )` Output only. Indicates whether the principal is allowed to access specified resource, based on evaluating all applicable principal access boundary bindings and policies.                                                                    |
| `explainedBindingsAndPolicies[]`     | `object ( `[`ExplainedPABBindingAndPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedPABBindingAndPolicy)` )` List of principal access boundary policies and bindings that are applicable to the principal's access state, with annotations to indicate how each binding and policy contributes to the overall access state. |
| `relevance`                          | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the principal access boundary access state to the overall access state.                                                                                                                                             |

### ExplainedPABBindingAndPolicy

**JSON representation**

```
{
  "bindingAndPolicyAccessState": enum (PABAccessState),
  "explainedPolicyBinding": {
    object (ExplainedPolicyBinding)
  },
  "explainedPolicy": {
    object (ExplainedPABPolicy)
  },
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `bindingAndPolicyAccessState` | `enum ( `[`PABAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABAccessState)` )` Output only. Indicates whether the principal is allowed to access the specified resource based on evaluating the binding and policy.                                                                                                                                                             |
| `explainedPolicyBinding`      | `object ( `[`ExplainedPolicyBinding`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedPolicyBinding)` )` Details about how this binding contributes to the principal access boundary explanation, with annotations to indicate how the binding contributes to the overall access state.                                                                                                 |
| `explainedPolicy`             | `object ( `[`ExplainedPABPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedPABPolicy)` )` Optional. Details about how this policy contributes to the principal access boundary explanation, with annotations to indicate how the policy contributes to the overall access state. If the caller doesn't have permission to view the policy in the binding, this field is omitted. |
| `relevance`                   | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this principal access boundary binding and policy to the overall access state.                                                                                                                                                                                          |

### ExplainedPolicyBinding

**JSON representation**

```
{
  "policyBindingState": enum (PolicyBindingState),
  "policyBinding": {
    object (PolicyBinding)
  },
  "conditionExplanation": {
    object (ConditionExplanation)
  },
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                 |                                                                                                                                                                                                                                                                                                                                           |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyBindingState`   | `enum ( `[`PolicyBindingState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PolicyBindingState)` )` Output only. Indicates whether the policy binding takes effect.                                                                            |
| `policyBinding`        | `object ( `[`PolicyBinding`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PolicyBinding)` )` The policy binding that is explained.                                                                                                              |
| `conditionExplanation` | `object ( `[`ConditionExplanation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ConditionExplanation)` )` Optional. Explanation of the condition in the policy binding. If the policy binding doesn't have a condition, this field is omitted. |
| `relevance`            | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this policy binding to the overall access state.                                                                          |

### PolicyBinding

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "etag": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "target": {
    object (Target)
  },
  "policyKind": enum (PolicyKind),
  "policy": string,
  "policyUid": string,
  "condition": {
    object (Expr)
  },
  "createTime": string,
  "updateTime": string
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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Identifier. The name of the policy binding, in the format <code>{binding_parent/locations/{location}/policyBindings/{policy_binding_id}</code> . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the policy binding. Assigned when the policy binding is created.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the policy binding. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the policy binding. Must be less than or equal to 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User-defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>target</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Target"><code>Target</code></a><code> )</code></p>
<p>Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.</p></td>
</tr>
<tr class="odd">
<td><code>policyKind</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PolicyKind"><code>PolicyKind</code></a><code> )</code></p>
<p>Immutable. The kind of the policy to attach in this binding. This field must be one of the following:</p>
<ul>
<li>Left empty (will be automatically set to the policy kind)</li>
<li>The input policy kind</li>
</ul></td>
</tr>
<tr class="even">
<td><code>policy</code></td>
<td><p><code>string</code></p>
<p>Required. Immutable. The resource name of the policy to be bound. The binding parent and policy must belong to the same organization.</p></td>
</tr>
<tr class="odd">
<td><code>policyUid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the policy to be bound.</p></td>
</tr>
<tr class="even">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>Optional. The condition to apply to the policy binding. When set, the <code>expression</code> field in the <code>Expr</code> must include from 1 to 10 subexpressions, joined by the "||"(Logical OR), "&amp;&amp;"(Logical AND) or "!"(Logical NOT) operators and cannot contain more than 250 characters.</p>
<p>The condition is currently only supported when bound to policies of kind principal access boundary.</p>
<p>When the bound policy is a principal access boundary policy, the only supported attributes in any subexpression are <code>principal.type</code> and <code>principal.subject</code> . An example expression is: "principal.type == 'iam.googleapis.com/ServiceAccount'" or "principal.subject == 'bob@example.com'".</p>
<p>Allowed operations for <code>principal.subject</code> :</p>
<ul>
<li><code>principal.subject == &lt;principal subject string&gt;</code></li>
<li><code>principal.subject != &lt;principal subject string&gt;</code></li>
<li><code>principal.subject in [&lt;list of principal subjects&gt;]</code></li>
<li><code>principal.subject.startsWith(&lt;string&gt;)</code></li>
<li><code>principal.subject.endsWith(&lt;string&gt;)</code></li>
</ul>
<p>Allowed operations for <code>principal.type</code> :</p>
<ul>
<li><code>principal.type == &lt;principal type string&gt;</code></li>
<li><code>principal.type != &lt;principal type string&gt;</code></li>
<li><code>principal.type in [&lt;list of principal types&gt;]</code></li>
</ul>
<p>Supported principal types are workspace, workforce pool, workload pool, service account, and agent identity. Allowed string must be one of:</p>
<ul>
<li><code>iam.googleapis.com/WorkspaceIdentity</code></li>
<li><code>iam.googleapis.com/WorkforcePoolIdentity</code></li>
<li><code>iam.googleapis.com/WorkloadPoolIdentity</code></li>
<li><code>iam.googleapis.com/ServiceAccount</code></li>
<li><code>iam.googleapis.com/AgentPoolIdentity</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the policy binding was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the policy binding was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
</tbody>
</table>

### AnnotationsEntry

**JSON representation**

```
{
  "key": string,
  "value": string
}
```

| Fields  |          |
|---------|----------|
| `key`   | `string` |
| `value` | `string` |

### Target

**JSON representation**

```
{

  // Union field target can be only one of the following:
  "principalSet": string,
  "resource": string
  // End of list of possible types for union field target.
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
<td>Union field <code>target</code> . The different types of targets that can be bound to a policy. <code>target</code> can be only one of the following:</td>
<td></td>
</tr>
<tr class="even">
<td><code>principalSet</code></td>
<td><p><code>string</code></p>
<p>Immutable. The full resource name that's used for principal access boundary policy bindings. The principal set must be directly parented by the policy binding's parent or same as the parent if the target is a project, folder, or organization.</p>
<p>Examples:</p>
<ul>
<li>For bindings parented by an organization:
<ul>
<li>Organization: <code>//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID</code></li>
<li>Workforce Identity: <code>//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID</code></li>
<li>Workspace Identity: <code>//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID</code></li>
</ul></li>
<li>For bindings parented by a folder:
<ul>
<li>Folder: <code>//cloudresourcemanager.googleapis.com/folders/FOLDER_ID</code></li>
</ul></li>
<li>For bindings parented by a project:
<ul>
<li>Project:
<ul>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_ID</code></li>
</ul></li>
<li>Workload Identity Pool: <code>//iam.googleapis.com/projects/PROJECT_NUMBER/locations/LOCATION/workloadIdentityPools/WORKLOAD_POOL_ID</code></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resource</code></td>
<td><p><code>string</code></p>
<p>Immutable. The full resource name that's used for access policy bindings.</p>
<p>Examples:</p>
<ul>
<li>Organization: <code>//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID</code></li>
<li>Folder: <code>//cloudresourcemanager.googleapis.com/folders/FOLDER_ID</code></li>
<li>Project:
<ul>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_ID</code></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

### ExplainedPABPolicy

**JSON representation**

```
{
  "policyAccessState": enum (PABAccessState),
  "policy": {
    object (PrincipalAccessBoundaryPolicy)
  },
  "policyVersion": {
    object (ExplainedPABPolicyVersion)
  },
  "explainedRules": [
    {
      object (ExplainedPABRule)
    }
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields              |                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyAccessState` | `enum ( `[`PABAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABAccessState)` )` Output only. Indicates whether the policy allows access to the specified resource.                                                                                                                           |
| `policy`            | `object ( `[`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PrincipalAccessBoundaryPolicy)` )` The policy that is explained.                                                                                                                                                |
| `policyVersion`     | `object ( `[`ExplainedPABPolicyVersion`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedPABPolicyVersion)` )` Output only. Explanation of the principal access boundary policy's version.                                                                                                          |
| `explainedRules[]`  | `object ( `[`ExplainedPABRule`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedPABRule)` )` List of principal access boundary rules that were explained to check the principal's access to specified resource, with annotations to indicate how each rule contributes to the overall access state. |
| `relevance`         | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this policy to the overall access state.                                                                                                                                            |

### PrincipalAccessBoundaryPolicy

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "etag": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "createTime": string,
  "updateTime": string,
  "details": {
    object (PrincipalAccessBoundaryPolicyDetails)
  }
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | `string` Identifier. The resource name of the principal access boundary policy. The following format is supported: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{policy_id}`                                                                                                                                                                                                                                            |
| `uid`         | `string` Output only. The globally unique ID of the principal access boundary policy.                                                                                                                                                                                                                                                                                                                                                                            |
| `etag`        | `string` Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.                                                                                                                                                                                                                                                                                                                                   |
| `displayName` | `string` Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.                                                                                                                                                                                                                                                                                                                                         |
| `annotations` | `map (key: string, value: string)` Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                                   |
| `createTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the principal access boundary policy was created. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .               |
| `updateTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the principal access boundary policy was most recently updated. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` . |
| `details`     | `object ( `[`PrincipalAccessBoundaryPolicyDetails`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PrincipalAccessBoundaryPolicyDetails)` )` Optional. The details for the principal access boundary policy.                                                                                                                                                             |

### AnnotationsEntry

**JSON representation**

```
{
  "key": string,
  "value": string
}
```

| Fields  |          |
|---------|----------|
| `key`   | `string` |
| `value` | `string` |

### PrincipalAccessBoundaryPolicyDetails

**JSON representation**

```
{
  "rules": [
    {
      object (PrincipalAccessBoundaryPolicyRule)
    }
  ],
  "enforcementVersion": string
}
```

| Fields               |                                                                                                                                                                                                                                                                                                                                               |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]`            | `object ( `[`PrincipalAccessBoundaryPolicyRule`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PrincipalAccessBoundaryPolicyRule)` )` Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500. |
| `enforcementVersion` | `string` Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.                                                                             |

### PrincipalAccessBoundaryPolicyRule

**JSON representation**

```
{
  "description": string,
  "resources": [
    string
  ],
  "effect": enum (Effect),
  "operation": {
    object (Operation)
  },
  "excludedResources": [
    string
  ]
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
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>resources[]</code></td>
<td><p><code>string</code></p>
<p>Required. A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.</p>
<p>The following resource types are supported:</p>
<ul>
<li>Organizations, such as <code>//cloudresourcemanager.googleapis.com/organizations/123</code> .</li>
<li>Folders, such as <code>//cloudresourcemanager.googleapis.com/folders/123</code> .</li>
<li>Projects, such as <code>//cloudresourcemanager.googleapis.com/projects/123</code> or <code>//cloudresourcemanager.googleapis.com/projects/my-project-id</code> .</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>effect</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Effect"><code>Effect</code></a><code> )</code></p>
<p>Required. The access relationship of principals to the resources in this rule.</p></td>
</tr>
<tr class="even">
<td><code>operation</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Operation"><code>Operation</code></a><code> )</code></p>
<p>Optional. The operation attributes that determine whether this rule applies to a request. If this field is not specified, the rule applies to all operations.</p></td>
</tr>
<tr class="odd">
<td><code>excludedResources[]</code></td>
<td><p><code>string</code></p>
<p>Optional. A list of Resource Manager resources. If an excluded resource is listed in the rule, then the rule does not apply for that resource and its descendants. This takes precedence over the <code>resources</code> field. The number of excluded resources in this field is limited to 500 across all rules in the policy.</p>
<p>The following resource types are supported:</p>
<ul>
<li>Organizations, such as <code>//cloudresourcemanager.googleapis.com/organizations/123</code> .</li>
<li>Folders, such as <code>//cloudresourcemanager.googleapis.com/folders/123</code> .</li>
<li>Projects, such as <code>//cloudresourcemanager.googleapis.com/projects/123</code> or <code>//cloudresourcemanager.googleapis.com/projects/my-project-id</code> .</li>
</ul></td>
</tr>
</tbody>
</table>

### Operation

**JSON representation**

```
{
  "permissions": [
    string
  ],
  "excludedPermissions": [
    string
  ]
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
<td><code>permissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The permissions that are explicitly affected by this rule. The number of permission strings in this field is limited to 50 across all rules in the policy.</p>
<p>Each permission uses the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. <code>*</code> can be used as a wildcard to match all permissions for a specific service, resource type, or verb.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>{service_fqdn}/{resource}.{verb}</code> : A specific permission.</li>
<li><code>{service_fqdn}/{resource}.*</code> : All permissions for a specific resource type.</li>
<li><code>{service_fqdn}/*.*</code> : All permissions for all resource types under a specific service.</li>
<li><code>{service_fqdn}/*.{verb}</code> : All permissions with a specific verb under a specific service.</li>
<li><code>*</code> : All permissions across all services.</li>
</ul>
<p>For example, <code>compute.googleapis.com/*.setIamPolicy</code> refers to all setIamPolicy permissions for any compute resource.</p>
<p>Wildcards expand only to the permissions specified in the <code>enforcement_version</code> of the policy. If the <code>enforcement_version</code> is updated, the wildcard will automatically expand to include new permissions in the updated version.</p></td>
</tr>
<tr class="even">
<td><code>excludedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Specifies the permissions that this rule excludes from the set of affected permissions given by <code>permissions</code> . The number of excluded permission strings in this field is limited to 50 across all rules in the policy.</p>
<p>If a permission appears in both <code>permissions</code> and <code>excluded_permissions</code> then it will <em>not</em> be subject to the policy effect.</p>
<p>The excluded permissions can be specified using the same syntax as <code>permissions</code> .</p></td>
</tr>
</tbody>
</table>

### ExplainedPABPolicyVersion

**JSON representation**

```
{
  "version": integer,
  "enforcementState": enum (PABPolicyEnforcementState)
}
```

| Fields             |                                                                                                                                                                                                                                                                                          |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `version`          | `integer` Output only. The actual version of the policy. - If the policy uses static version, this field is the chosen static version. - If the policy uses dynamic version, this field is the effective latest version.                                                                 |
| `enforcementState` | `enum ( `[`PABPolicyEnforcementState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABPolicyEnforcementState)` )` Output only. Indicates whether the policy is enforced based on its version. |

### ExplainedPABRule

**JSON representation**

```
{
  "ruleAccessState": enum (PABAccessState),
  "effect": enum (Effect),
  "combinedResourceInclusionState": enum (ResourceInclusionState),
  "combinedResourceRelevance": enum (HeuristicRelevance),
  "explainedResources": [
    {
      object (ExplainedResource)
    }
  ],
  "pabUnsupportedFeatures": [
    string
  ],
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                           |                                                                                                                                                                                                                                                                                                                                                                                     |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ruleAccessState`                | `enum ( `[`PABAccessState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.PABAccessState)` )` Output only. Indicates whether the rule allows access to the specified resource.                                                                                                             |
| `effect`                         | `enum ( `[`Effect`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.Effect)` )` Required. The effect of the rule which describes the access relationship.                                                                                                                                    |
| `combinedResourceInclusionState` | `enum ( `[`ResourceInclusionState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ResourceInclusionState)` )` Output only. Indicates whether any resource of the rule is the specified resource or includes the specified resource.                                                        |
| `combinedResourceRelevance`      | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of the combined resource inclusion state to the overall access state.                                                                                                  |
| `explainedResources[]`           | `object ( `[`ExplainedResource`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ExplainedResource)` )` List of resources that were explained to check the principal's access to specified resource, with annotations to indicate how each resource contributes to the overall access state. |
| `pabUnsupportedFeatures[]`       | `string` Output only. Unsupported features detected in this rule. Supported values: \* `OPERATION` : Permission Subsetting (Operation constraints). See `google.iam.v3.PrincipalAccessBoundaryPolicyRule.operation` .                                                                                                                                                               |
| `relevance`                      | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this rule to the overall access state.                                                                                                                              |

### ExplainedResource

**JSON representation**

```
{
  "resourceInclusionState": enum (ResourceInclusionState),
  "resource": string,
  "relevance": enum (HeuristicRelevance)
}
```

| Fields                   |                                                                                                                                                                                                                                                                                                                  |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resourceInclusionState` | `enum ( `[`ResourceInclusionState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.ResourceInclusionState)` )` Output only. Indicates whether the resource is the specified resource or includes the specified resource. |
| `resource`               | `string` The [full resource name](https://cloud.google.com/iam/docs/full-resource-names) that identifies the resource that is explained. This can only be a project, a folder, or an organization which is what a PAB rule accepts.                                                                              |
| `relevance`              | `enum ( `[`HeuristicRelevance`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policytroubleshooter/mcp/tools_list/troubleshoot_access#Output.Schema.HeuristicRelevance)` )` The relevance of this resource to the overall access state.                                                       |

### OverallAccessState

Whether the principal has the permission on the resource.

| Enums                              |                                                                                                                                                                                                  |
|------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `OVERALL_ACCESS_STATE_UNSPECIFIED` | Not specified.                                                                                                                                                                                   |
| `CAN_ACCESS`                       | The principal has the permission.                                                                                                                                                                |
| `CANNOT_ACCESS`                    | The principal doesn't have the permission.                                                                                                                                                       |
| `UNKNOWN_INFO`                     | The principal might have the permission, but the sender can't access all of the information needed to fully evaluate the principal's access.                                                     |
| `UNKNOWN_CONDITIONAL`              | The principal might have the permission, but Policy Troubleshooter can't fully evaluate the principal's access because the sender didn't provide the required context to evaluate the condition. |

### AllowAccessState

Whether IAM allow policies gives the principal the permission.

| Enums                                    |                                                                                                                                                                                                                                     |
|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ALLOW_ACCESS_STATE_UNSPECIFIED`         | Not specified.                                                                                                                                                                                                                      |
| `ALLOW_ACCESS_STATE_GRANTED`             | The allow policy gives the principal the permission.                                                                                                                                                                                |
| `ALLOW_ACCESS_STATE_NOT_GRANTED`         | The allow policy doesn't give the principal the permission.                                                                                                                                                                         |
| `ALLOW_ACCESS_STATE_UNKNOWN_CONDITIONAL` | The allow policy gives the principal the permission if a condition expression evaluate to `true` . However, the sender of the request didn't provide enough context for Policy Troubleshooter to evaluate the condition expression. |
| `ALLOW_ACCESS_STATE_UNKNOWN_INFO`        | The sender of the request doesn't have access to all of the allow policies that Policy Troubleshooter needs to evaluate the principal's access.                                                                                     |

### RolePermissionInclusionState

Whether a role includes a specific permission.

| Enums                                         |                                                                         |
|-----------------------------------------------|-------------------------------------------------------------------------|
| `ROLE_PERMISSION_INCLUSION_STATE_UNSPECIFIED` | Not specified.                                                          |
| `ROLE_PERMISSION_INCLUDED`                    | The permission is included in the role.                                 |
| `ROLE_PERMISSION_NOT_INCLUDED`                | The permission is not included in the role.                             |
| `ROLE_PERMISSION_UNKNOWN_INFO`                | The sender of the request is not allowed to access the role definition. |

### HeuristicRelevance

The extent to which a single data point contributes to an overall determination.

| Enums                             |                                                                                                                             |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| `HEURISTIC_RELEVANCE_UNSPECIFIED` | Not specified.                                                                                                              |
| `HEURISTIC_RELEVANCE_NORMAL`      | The data point has a limited effect on the result. Changing the data point is unlikely to affect the overall determination. |
| `HEURISTIC_RELEVANCE_HIGH`        | The data point has a strong effect on the result. Changing the data point is likely to affect the overall determination.    |

### MembershipMatchingState

Whether the principal in the request matches the principal in the policy.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>MEMBERSHIP_MATCHING_STATE_UNSPECIFIED</code></td>
<td>Not specified.</td>
</tr>
<tr class="even">
<td><code>MEMBERSHIP_MATCHED</code></td>
<td><p>The principal in the request matches the principal in the policy. The principal can be included directly or indirectly:</p>
<ul>
<li>A principal is included directly if that principal is listed in the role binding.</li>
<li>A principal is included indirectly if that principal is in a Google group, Google Workspace account, or Cloud Identity domain that is listed in the policy.</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>MEMBERSHIP_NOT_MATCHED</code></td>
<td>The principal in the request doesn't match the principal in the policy.</td>
</tr>
<tr class="even">
<td><code>MEMBERSHIP_UNKNOWN_INFO</code></td>
<td>The principal in the policy is a group or domain, and the sender of the request doesn't have permission to view whether the principal in the request is a member of the group or domain.</td>
</tr>
<tr class="odd">
<td><code>MEMBERSHIP_UNKNOWN_UNSUPPORTED</code></td>
<td>The principal is an unsupported type.</td>
</tr>
</tbody>
</table>

### NullValue

Represents a JSON `null` .

`NullValue` is a sentinel, using an enum with only one value to represent the null value for the `Value` type union.

A field of type `NullValue` with any value other than `0` is considered invalid. Most ProtoJSON serializers will emit a `Value` with a `null_value` set as a JSON `null` regardless of the integer value, and so will round trip to a `0` value.

| Enums        |             |
|--------------|-------------|
| `NULL_VALUE` | Null value. |

### LogType

The list of valid permission types for which logging can be configured. Admin writes are always logged, and are not configurable.

| Enums                  |                                             |
|------------------------|---------------------------------------------|
| `LOG_TYPE_UNSPECIFIED` | Default case. Should never be this.         |
| `ADMIN_READ`           | Admin reads. Example: CloudIAM getIamPolicy |
| `DATA_WRITE`           | Data writes. Example: CloudSQL Users create |
| `DATA_READ`            | Data reads. Example: CloudSQL Users list    |

### DenyAccessState

Whether IAM deny policies deny the principal the permission.

| Enums                                   |                                                                                                                                                                                                                                      |
|-----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `DENY_ACCESS_STATE_UNSPECIFIED`         | Not specified.                                                                                                                                                                                                                       |
| `DENY_ACCESS_STATE_DENIED`              | The deny policy denies the principal the permission.                                                                                                                                                                                 |
| `DENY_ACCESS_STATE_NOT_DENIED`          | The deny policy doesn't deny the principal the permission.                                                                                                                                                                           |
| `DENY_ACCESS_STATE_UNKNOWN_CONDITIONAL` | The deny policy denies the principal the permission if a condition expression evaluates to `true` . However, the sender of the request didn't provide enough context for Policy Troubleshooter to evaluate the condition expression. |
| `DENY_ACCESS_STATE_UNKNOWN_INFO`        | The sender of the request does not have access to all of the deny policies that Policy Troubleshooter needs to evaluate the principal's access.                                                                                      |

### PermissionPatternMatchingState

Whether the permission in the request matches the permission in the policy.

| Enums                                           |                                                                     |
|-------------------------------------------------|---------------------------------------------------------------------|
| `PERMISSION_PATTERN_MATCHING_STATE_UNSPECIFIED` | Not specified.                                                      |
| `PERMISSION_PATTERN_MATCHED`                    | The permission in the request matches the permission in the policy. |
| `PERMISSION_PATTERN_NOT_MATCHED`                | The permission in the request matches the permission in the policy. |

### PABAccessState

Whether a principal access boundary component allows the principal to access the specified resource.

A PAB component refers to a PAB rule, a PAB policy, a PAB policy and binding pair, all PAB policies bound to a target, or PAB overall. This is because this enum is shared across all these messages.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>PAB_ACCESS_STATE_UNSPECIFIED</code></td>
<td>Not specified.</td>
</tr>
<tr class="even">
<td><code>PAB_ACCESS_STATE_ALLOWED</code></td>
<td>The PAB component allows the principal's access to the specified resource.</td>
</tr>
<tr class="odd">
<td><code>PAB_ACCESS_STATE_NOT_ALLOWED</code></td>
<td>The PAB component doesn't allow the principal's access to the specified resource.</td>
</tr>
<tr class="even">
<td><code>PAB_ACCESS_STATE_NOT_ENFORCED</code></td>
<td><p>The PAB component is not enforced on the principal, or the specified resource.</p>
<p>This state refers to the following scenarios:</p>
<ul>
<li>IAM doesn't enforce the specified permission at the PAB policy's <a href="https://cloud.google.com/iam/help/pab/enforcement-versions">enforcement version</a> , so the PAB policy can't block access.</li>
<li>The binding doesn't apply to the principal, so the policy is not enforced.</li>
<li>The PAB policy doesn't have any rules</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>PAB_ACCESS_STATE_UNKNOWN_INFO</code></td>
<td>The sender of the request does not have access to the PAB component, or the relevant data to explain the PAB component.</td>
</tr>
</tbody>
</table>

### PolicyBindingState

Whether the policy binding is enforced.

| Enums                               |                                                                         |
|-------------------------------------|-------------------------------------------------------------------------|
| `POLICY_BINDING_STATE_UNSPECIFIED`  | An error occurred when checking whether the policy binding is enforced. |
| `POLICY_BINDING_STATE_ENFORCED`     | The policy binding is enforced.                                         |
| `POLICY_BINDING_STATE_NOT_ENFORCED` | The policy binding is not enforced.                                     |

### PolicyKind

The different policy kinds supported in this binding.

| Enums                       |                                            |
|-----------------------------|--------------------------------------------|
| `POLICY_KIND_UNSPECIFIED`   | Unspecified policy kind; Not a valid state |
| `PRINCIPAL_ACCESS_BOUNDARY` | Principal access boundary policy kind      |
| `ACCESS`                    | Access policy kind.                        |

### Effect

An effect to describe the access relationship.

| Enums                |                                              |
|----------------------|----------------------------------------------|
| `EFFECT_UNSPECIFIED` | Effect unspecified.                          |
| `ALLOW`              | Allows access to the resources in this rule. |
| `DENY`               | Denies access to the resources in this rule. |

### PABPolicyEnforcementState

Whether a principal access boundary policy is enforced based on its version.

| Enums                                       |                                                                                                              |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| `PAB_POLICY_ENFORCEMENT_STATE_UNSPECIFIED`  | An error occurred when checking whether a principal access boundary policy is enforced based on its version. |
| `PAB_POLICY_ENFORCEMENT_STATE_ENFORCED`     | The principal access boundary policy is enforced based on its version.                                       |
| `PAB_POLICY_ENFORCEMENT_STATE_NOT_ENFORCED` | The principal access boundary policy is not enforced based on its version.                                   |

### ResourceInclusionState

Whether the resource is the specified resource or includes the specified resource.

| Enums                                          |                                                                                                                                    |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| `RESOURCE_INCLUSION_STATE_UNSPECIFIED`         | An error occurred when checking whether the resource includes the specified resource.                                              |
| `RESOURCE_INCLUSION_STATE_INCLUDED`            | The resource includes the specified resource.                                                                                      |
| `RESOURCE_INCLUSION_STATE_NOT_INCLUDED`        | The resource doesn't include the specified resource.                                                                               |
| `RESOURCE_INCLUSION_STATE_UNKNOWN_INFO`        | The sender of the request does not have access to the relevant data to check whether the resource includes the specified resource. |
| `RESOURCE_INCLUSION_STATE_UNKNOWN_UNSUPPORTED` | The resource is of an unsupported type, such as non-CRM resources.                                                                 |

### Tool Annotations

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
