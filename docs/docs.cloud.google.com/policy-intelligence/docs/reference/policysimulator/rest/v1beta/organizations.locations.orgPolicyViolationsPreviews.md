---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews
title: 'REST Resource: organizations.locations.orgPolicyViolationsPreviews'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [Resource: OrgPolicyViolationsPreview](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview.SCHEMA_REPRESENTATION)
  - [PreviewState](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#PreviewState)
  - [OrgPolicyOverlay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyOverlay)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyOverlay.SCHEMA_REPRESENTATION)
  - [PolicyOverlay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#PolicyOverlay)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#PolicyOverlay.SCHEMA_REPRESENTATION)
  - [CustomConstraintOverlay](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#CustomConstraintOverlay)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#CustomConstraintOverlay.SCHEMA_REPRESENTATION)
  - [ResourceCounts](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#ResourceCounts)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#ResourceCounts.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#METHODS_SUMMARY)

## Resource: OrgPolicyViolationsPreview

OrgPolicyViolationsPreview is a resource providing a preview of the violations that will exist if an OrgPolicy change is made.

The list of violations are modeled as child resources and retrieved via a \[ListOrgPolicyViolations\]\[\] API call. There are potentially more \[OrgPolicyViolations\]\[\] than could fit in an embedded field. Thus, the use of a child resource instead of a field.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;state&quot;: enum (PreviewState),&quot;overlay&quot;: {object (OrgPolicyOverlay)},&quot;violationsCount&quot;: integer,&quot;resourceCounts&quot;: {object (ResourceCounts)},&quot;customConstraints&quot;: [string],&quot;createTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. The resource name of the `OrgPolicyViolationsPreview` . It has the following format:

`organizations/{organization}/locations/{location}/orgPolicyViolationsPreviews/{orgPolicyViolationsPreview}`

Example: `organizations/my-example-org/locations/global/orgPolicyViolationsPreviews/506a5f7f`

`state`

` enum ( PreviewState  ` )

Output only. The state of the `OrgPolicyViolationsPreview` .

`overlay`

` object ( OrgPolicyOverlay  ` )

Required. The proposed changes we are previewing violations for.

`violationsCount`

`integer`

Output only. The number of \[OrgPolicyViolations\]\[\] in this `OrgPolicyViolationsPreview` . This count may differ from `resource_summary.noncompliant_count` because each `  OrgPolicyViolation  ` is specific to a resource **and** constraint. If there are multiple constraints being evaluated (i.e. multiple policies in the overlay), a single resource may violate multiple constraints.

`resourceCounts`

` object ( ResourceCounts  ` )

Output only. A summary of the state of all resources scanned for compliance with the changed OrgPolicy.

`customConstraints[]`

`string`

Output only. The names of the constraints against which all `OrgPolicyViolations` were evaluated.

If `OrgPolicyOverlay` only contains `PolicyOverlay` then it contains the name of the configured custom constraint, applicable to the specified policies. Otherwise it contains the name of the constraint specified in `CustomConstraintOverlay` .

Format: `organizations/{organizationId}/customConstraints/{custom_constraint_id}`

Example: `organizations/123/customConstraints/custom.createOnlyE2TypeVms`

`createTime`

` string ( Timestamp  ` format)

Output only. Time when this `OrgPolicyViolationsPreview` was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## PreviewState

The current state of an `  OrgPolicyViolationsPreview  ` .

Enums

`PREVIEW_STATE_UNSPECIFIED`

The state is unspecified.

`PREVIEW_PENDING`

The `  OrgPolicyViolationsPreview  ` has not been created yet.

`PREVIEW_RUNNING`

The `  OrgPolicyViolationsPreview  ` is currently being created.

`PREVIEW_SUCCEEDED`

The `  OrgPolicyViolationsPreview  ` creation finished successfully.

`PREVIEW_FAILED`

The `  OrgPolicyViolationsPreview  ` creation failed with an error.

## OrgPolicyOverlay

The proposed changes to OrgPolicy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policies&quot;: [{object (PolicyOverlay)}],&quot;customConstraints&quot;: [{object (CustomConstraintOverlay)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policies[]`

` object ( PolicyOverlay  ` )

Optional. The OrgPolicy changes to preview violations for.

Any existing OrgPolicies with the same name will be overridden in the simulation. That is, violations will be determined as if all policies in the overlay were created or updated.

`customConstraints[]`

` object ( CustomConstraintOverlay  ` )

Optional. The OrgPolicy CustomConstraint changes to preview violations for.

Any existing CustomConstraints with the same name will be overridden in the simulation. That is, violations will be determined as if all custom constraints in the overlay were instantiated.

Only a single customConstraint is supported in the overlay at a time. For evaluating multiple constraints, multiple `orgPolicyViolationsPreviews.generate` requests are made, where each request evaluates a single constraint.

## PolicyOverlay

A change to an OrgPolicy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyParent&quot;: string,&quot;policy&quot;: {object (Policy)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyParent`

`string`

Optional. The parent of the policy we are attaching to. Example: "projects/123456"

`policy`

` object ( Policy  ` )

Optional. The new or updated OrgPolicy.

## CustomConstraintOverlay

A change to an OrgPolicy custom constraint.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;customConstraintParent&quot;: string,&quot;customConstraint&quot;: {object (CustomConstraint)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`customConstraintParent`

`string`

Optional. Resource the constraint is attached to. Example: "organization/987654"

`customConstraint`

` object ( CustomConstraint  ` )

Optional. The new or updated custom constraint.

## ResourceCounts

A summary of the state of all resources scanned for compliance with the changed OrgPolicy.

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
  &quot;scanned&quot;: integer,
  &quot;noncompliant&quot;: integer,
  &quot;compliant&quot;: integer,
  &quot;unenforced&quot;: integer,
  &quot;errors&quot;: integer
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`scanned`

`integer`

Output only. Number of resources checked for compliance.

Must equal: unenforced + noncompliant + compliant + error

`noncompliant`

`integer`

Output only. Number of scanned resources with at least one violation.

`compliant`

`integer`

Output only. Number of scanned resources with zero violations.

`unenforced`

`integer`

Output only. Number of resources where the constraint was not enforced, i.e. the Policy set `enforced: false` for that resource.

`errors`

`integer`

Output only. Number of resources that returned an error when scanned.

## Methods

### `            create           `

CreateOrgPolicyViolationsPreview creates an `  OrgPolicyViolationsPreview  ` for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\].

### `            generate           `

GenerateOrgPolicyViolationsPreview generates an `  OrgPolicyViolationsPreview  ` for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\].

### `            get           `

GetOrgPolicyViolationsPreview gets the specified `  OrgPolicyViolationsPreview  ` .

### `            list           `

ListOrgPolicyViolationsPreviews lists each `  OrgPolicyViolationsPreview  ` in an organization.
