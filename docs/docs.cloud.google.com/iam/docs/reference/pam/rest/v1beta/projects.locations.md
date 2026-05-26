---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations
title: 'REST Resource: projects.locations'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Location](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations#Location)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations#Location.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations#METHODS_SUMMARY)

## Resource: Location

A resource that represents a Google Cloud location.

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
  &quot;name&quot;: string,
  &quot;locationId&quot;: string,
  &quot;displayName&quot;: string,
  &quot;labels&quot;: {
    string: string,
    ...
  },
  &quot;metadata&quot;: {
    &quot;@type&quot;: string,
    field1: ...,
    ...
  }
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Resource name for the location, which may vary between implementations. For example: `"projects/example-project/locations/us-east1"`

`locationId`

`string`

The canonical id for this location. For example: `"us-east1"` .

`displayName`

`string`

The friendly name for this location, typically a nearby city name. For example, "Tokyo".

`labels`

`map (key: string, value: string)`

Cross-service attributes for the location. For example

    {"cloud.googleapis.com/region": "us-east1"}

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`metadata`

`object`

Service-specific metadata. For example the available capacity at the given location.

An object containing fields of an arbitrary type. An additional field `"@type"` contains a URI identifying the type. Example: `{ "id": 1234, "@type": "types.example.com/standard/id" }` .

## Methods

### `            checkOnboardingStatus           `

`CheckOnboardingStatus` reports the onboarding status for a project, folder, or organization.

### `            fetchEffectiveSettings           `

`FetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

### `            get           `

Gets information about a location.

### `            getSettings           `

`GetSettings` returns the PAM Settings for the given project, folder, or organization.

### `            list           `

Lists information about the supported locations for this service.

### `            updateSettings           `

`UpdateSettings` updates the PAM Settings resource specified in the request.
