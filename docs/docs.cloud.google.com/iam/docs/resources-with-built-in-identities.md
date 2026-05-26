---
name: documents/docs.cloud.google.com/iam/docs/resources-with-built-in-identities
uri: https://docs.cloud.google.com/iam/docs/resources-with-built-in-identities
title: Resource types with built-in identities
description: A list of {{dynamic_data.site_values.cloud_name_short}} resources that have built-in identities
data_source: docs.cloud.google.com
---

Some Google Cloud resources have [built-in identities](https://docs.cloud.google.com/iam/docs/built-in-resource-identities) . These identities let the resources act like [principals](https://docs.cloud.google.com/iam/docs/principals-overview) . As a result, resources with built-in identities can do the following:

  - Be [granted IAM roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) using the resource's principal identifier
  - Access other resources without using [service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents)

## Principal identifiers for single resources

The following table lists the resource types that have built-in identities. It also lists the accepted formats for the resource's principal identifier. Use one of the accepted formats for the principal identifier in your allow policies to grant roles to the resource.

| Resource type                                                                                                                                                            | Principal identifier format                                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Parameter Manager](https://docs.cloud.google.com/secret-manager/parameter-manager/docs/overview) parameters                                                             | ` principal://parametermanager.googleapis.com/  projects/          PROJECT_NUMBER        /  uid/  locations/  global/  parameters/          PARAMETER_UID        `  |
| [Workload identity pool](https://docs.cloud.google.com/iam/docs/workload-identity-federation#pools) [(preview)](https://cloud.google.com/products#product-launch-stages) | ` principal://iam.googleapis.com/projects/         PROJECT_NUMBER        /name/locations/global/workloadIdentityPools/         WORKLOAD_IDENTITY_POOL_NAME        ` |

## Principal identifiers for sets of resources

Use the following formats in your allow policies to grant roles to sets of resources with built-in identities:

> **Note:** These principal sets don't include resources that don't have built-in identities.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Description</th>
<th>Format</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>All resources for the specified service in the specified project</td>
<td><code dir="ltr" translate="no">principalSet://         RESOURCE_SERVICE        /  projects/         PROJECT_NUMBER        /  *</code></td>
</tr>
<tr class="even">
<td>All resources in the specified project with the specified type</td>
<td><code dir="ltr" translate="no">principalSet://         RESOURCE_SERVICE        /  projects/         PROJECT_NUMBER        /  type/         RESOURCE_TYPE        /  *</code></td>
</tr>
<tr class="odd">
<td>All resources with the specified ancestor</td>
<td><p><code dir="ltr" translate="no">principalSet://          RESOURCE_SERVICE         /  projects/          PROJECT_NUMBER         /  ancestor.name/          ANCESTOR_RESOURCE_TYPE         /           ANCESTOR_RESOURCE_NAME        </code></p>
<p><code dir="ltr" translate="no">principalSet://          RESOURCE_SERVICE         /  projects/          PROJECT_NUMBER         /  ancestor.uid/          ANCESTOR_RESOURCE_TYPE         /           ANCESTOR_RESOURCE_UID        </code></p></td>
</tr>
<tr class="even">
<td>All resources with the specified type and the specified ancestor</td>
<td><p><code dir="ltr" translate="no">principalSet://          RESOURCE_SERVICE         /  projects/          PROJECT_NUMBER         /  type/          RESOURCE_TYPE         /  ancestor.name/          ANCESTOR_RESOURCE_TYPE         /           ANCESTOR_RESOURCE_NAME        </code></p>
<p><code dir="ltr" translate="no">principalSet://          RESOURCE_SERVICE         /  projects/          PROJECT_NUMBER         /  type/          RESOURCE_TYPE         /  ancestor.uid/          ANCESTOR_RESOURCE_TYPE         /           ANCESTOR_RESOURCE_UID        </code></p></td>
</tr>
</tbody>
</table>
