---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy
title: Policy
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy#SCHEMA_REPRESENTATION)

Defines an organization policy which is used to specify constraints for configurations of Google Cloud resources.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;spec&quot;: {object (PolicySpec)},&quot;alternate&quot;: {object (AlternatePolicySpec)},&quot;dryRunSpec&quot;: {object (PolicySpec)},&quot;etag&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. The resource name of the policy. Must be one of the following forms, where `constraint_name` is the name of the constraint which this policy configures:

  - `projects/{projectNumber}/policies/{constraint_name}`
  - `folders/{folderId}/policies/{constraint_name}`
  - `organizations/{organizationId}/policies/{constraint_name}`

For example, `projects/123/policies/compute.disableSerialPortAccess` .

Note: `projects/{projectId}/policies/{constraint_name}` is also an acceptable name for API requests, but responses will return the name using the equivalent project number.

`spec`

` object ( PolicySpec  ` )

Basic information about the organization policy.

` alternate (deprecated)  `

` object ( AlternatePolicySpec  ` )

> This item is deprecated\!

Deprecated.

`dryRunSpec`

` object ( PolicySpec  ` )

Dry-run policy. Audit-only policy, can be used to monitor how the policy would have impacted the existing and future resources if it's enforced.

`etag`

`string`

Optional. An opaque tag indicating the current state of the policy, used for concurrency control. This 'etag' is computed by the server based on the value of other fields, and may be sent on update and delete requests to ensure the client has an up-to-date value before proceeding.
