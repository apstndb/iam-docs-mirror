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

**JSON representation**

```
{
  "name": string,
  "state": enum (PreviewState),
  "overlay": {
    object (OrgPolicyOverlay)
  },
  "violationsCount": integer,
  "resourceCounts": {
    object (ResourceCounts)
  },
  "customConstraints": [
    string
  ],
  "createTime": string
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                | `string` Output only. The resource name of the `OrgPolicyViolationsPreview` . It has the following format: `organizations/{organization}/locations/{location}/orgPolicyViolationsPreviews/{orgPolicyViolationsPreview}` Example: `organizations/my-example-org/locations/global/orgPolicyViolationsPreviews/506a5f7f`                                                                                                                                                                                                                                                                              |
| `state`               | `enum ( `[`PreviewState`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#PreviewState)` )` Output only. The state of the `OrgPolicyViolationsPreview` .                                                                                                                                                                                                                                                                                                                                          |
| `overlay`             | `object ( `[`OrgPolicyOverlay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyOverlay)` )` Required. The proposed changes we are previewing violations for.                                                                                                                                                                                                                                                                                                                            |
| `violationsCount`     | `integer` Output only. The number of \[OrgPolicyViolations\]\[\] in this `OrgPolicyViolationsPreview` . This count may differ from `resource_summary.noncompliant_count` because each [`OrgPolicyViolation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#OrgPolicyViolation) is specific to a resource **and** constraint. If there are multiple constraints being evaluated (i.e. multiple policies in the overlay), a single resource may violate multiple constraints. |
| `resourceCounts`      | `object ( `[`ResourceCounts`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#ResourceCounts)` )` Output only. A summary of the state of all resources scanned for compliance with the changed OrgPolicy.                                                                                                                                                                                                                                                                                         |
| `customConstraints[]` | `string` Output only. The names of the constraints against which all `OrgPolicyViolations` were evaluated. If `OrgPolicyOverlay` only contains `PolicyOverlay` then it contains the name of the configured custom constraint, applicable to the specified policies. Otherwise it contains the name of the constraint specified in `CustomConstraintOverlay` . Format: `organizations/{organizationId}/customConstraints/{custom_constraint_id}` Example: `organizations/123/customConstraints/custom.createOnlyE2TypeVms`                                                                          |
| `createTime`          | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. Time when this `OrgPolicyViolationsPreview` was created. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                        |

## PreviewState

The current state of an [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) .

| Enums                       |                                                                                                                                                                                                                                                 |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `PREVIEW_STATE_UNSPECIFIED` | The state is unspecified.                                                                                                                                                                                                                       |
| `PREVIEW_PENDING`           | The [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) has not been created yet.       |
| `PREVIEW_RUNNING`           | The [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) is currently being created.     |
| `PREVIEW_SUCCEEDED`         | The [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) creation finished successfully. |
| `PREVIEW_FAILED`            | The [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) creation failed with an error.  |

## OrgPolicyOverlay

The proposed changes to OrgPolicy.

**JSON representation**

```
{
  "policies": [
    {
      object (PolicyOverlay)
    }
  ],
  "customConstraints": [
    {
      object (CustomConstraintOverlay)
    }
  ]
}
```

| Fields                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policies[]`          | `object ( `[`PolicyOverlay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#PolicyOverlay)` )` Optional. The OrgPolicy changes to preview violations for. Any existing OrgPolicies with the same name will be overridden in the simulation. That is, violations will be determined as if all policies in the overlay were created or updated.                                                                                                                                                                                                                                                                                |
| `customConstraints[]` | `object ( `[`CustomConstraintOverlay`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#CustomConstraintOverlay)` )` Optional. The OrgPolicy CustomConstraint changes to preview violations for. Any existing CustomConstraints with the same name will be overridden in the simulation. That is, violations will be determined as if all custom constraints in the overlay were instantiated. Only a single customConstraint is supported in the overlay at a time. For evaluating multiple constraints, multiple `orgPolicyViolationsPreviews.generate` requests are made, where each request evaluates a single constraint. |

## PolicyOverlay

A change to an OrgPolicy.

**JSON representation**

```
{
  "policyParent": string,
  "policy": {
    object (Policy)
  }
}
```

| Fields         |                                                                                                                                                                              |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyParent` | `string` Optional. The parent of the policy we are attaching to. Example: "projects/123456"                                                                                  |
| `policy`       | `object ( `[`Policy`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy)` )` Optional. The new or updated OrgPolicy. |

## CustomConstraintOverlay

A change to an OrgPolicy custom constraint.

**JSON representation**

```
{
  "customConstraintParent": string,
  "customConstraint": {
    object (CustomConstraint)
  }
}
```

| Fields                   |                                                                                                                                                                                                          |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `customConstraintParent` | `string` Optional. Resource the constraint is attached to. Example: "organization/987654"                                                                                                                |
| `customConstraint`       | `object ( `[`CustomConstraint`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint)` )` Optional. The new or updated custom constraint. |

## ResourceCounts

A summary of the state of all resources scanned for compliance with the changed OrgPolicy.

**JSON representation**

```
{
  "scanned": integer,
  "noncompliant": integer,
  "compliant": integer,
  "unenforced": integer,
  "errors": integer
}
```

| Fields         |                                                                                                                                            |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| `scanned`      | `integer` Output only. Number of resources checked for compliance. Must equal: unenforced + noncompliant + compliant + error               |
| `noncompliant` | `integer` Output only. Number of scanned resources with at least one violation.                                                            |
| `compliant`    | `integer` Output only. Number of scanned resources with zero violations.                                                                   |
| `unenforced`   | `integer` Output only. Number of resources where the constraint was not enforced, i.e. the Policy set `enforced: false` for that resource. |
| `errors`       | `integer` Output only. Number of resources that returned an error when scanned.                                                            |

| Methods                                                                                                                                                                 |                                                                                                                                                                                                                                                                                                                                                           |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/create)     | CreateOrgPolicyViolationsPreview creates an [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\].     |
| [`generate`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate) | GenerateOrgPolicyViolationsPreview generates an [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\]. |
| [`get`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/get)           | GetOrgPolicyViolationsPreview gets the specified [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) .                                                                                            |
| [`list`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/list)         | ListOrgPolicyViolationsPreviews lists each [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) in an organization.                                                                                |
