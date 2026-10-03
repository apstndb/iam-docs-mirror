---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations
title: 'REST Resource: organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [Resource: OrgPolicyViolation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#OrgPolicyViolation)
  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#OrgPolicyViolation.SCHEMA_REPRESENTATION)
- [ResourceContext](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#ResourceContext)
  - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#ResourceContext.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#METHODS_SUMMARY)

## Resource: OrgPolicyViolation

OrgPolicyViolation is a resource representing a single resource violating a single OrgPolicy constraint.

**JSON representation**

```
{
  "name": string,
  "resource": {
    object (ResourceContext)
  },
  "customConstraint": {
    object (CustomConstraint)
  },
  "error": {
    object (Status)
  }
}
```

| Fields             |                                                                                                                                                                                                                                                             |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`             | `string` The name of the `OrgPolicyViolation` . Example: organizations/my-example-org/locations/global/orgPolicyViolationsPreviews/506a5f7f/orgPolicyViolations/38ce\`                                                                                      |
| `resource`         | `object ( `[`ResourceContext`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations#ResourceContext)` )` The resource violating the constraint. |
| `customConstraint` | `object ( `[`CustomConstraint`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint)` )` The custom constraint being violated.                                                              |
| `error`            | `object ( `[`Status`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ListOperationsResponse#Status)` )` Any error encountered during the evaluation.                                                    |

## ResourceContext

ResourceContext provides the context we know about a resource. It is similar in concept to google.cloud.asset.v1.Resource, but focuses on the information specifically used by Simulator.

**JSON representation**

```
{
  "resource": string,
  "assetType": string,
  "ancestors": [
    string
  ]
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resource`    | `string` The full name of the resource. Example: `//compute.googleapis.com/projects/my_project_123/zones/zone1/instances/instance1` See [Resource names](https://cloud.google.com/apis/design/resource_names#fullResourceName) for more information.                                                                                                                                                                                                                                         |
| `assetType`   | `string` The asset type of the resource as defined by CAIS. Example: `compute.googleapis.com/Firewall` See [Supported asset types](https://cloud.google.com/asset-inventory/docs/supported-asset-types) for more information.                                                                                                                                                                                                                                                                |
| `ancestors[]` | `string` The ancestry path of the resource in Google Cloud [resource hierarchy](https://cloud.google.com/resource-manager/docs/cloud-platform-resource-hierarchy) , represented as a list of relative resource names. An ancestry path starts with the closest ancestor in the hierarchy and ends at root. If the resource is a project, folder, or organization, the ancestry path starts from the resource itself. Example: `["projects/123456789", "folders/5432", "organizations/1234"]` |

| Methods                                                                                                                                                                         |                                                                                                                                                                                                                                                                                                |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`list`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list) | ListOrgPolicyViolations lists the \[OrgPolicyViolations\]\[\] that are present in an [`OrgPolicyViolationsPreview`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews#OrgPolicyViolationsPreview) . |
