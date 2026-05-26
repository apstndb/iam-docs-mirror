---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query
title: 'Method: projects.locations.activityTypes.activities.query'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.QueryActivityResponse.SCHEMA_REPRESENTATION)
  - [Authorization Scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#body.aspect_1)
  - [Activity](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#Activity)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#Activity.SCHEMA_REPRESENTATION)
  - [ObservationPeriod](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#ObservationPeriod)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyanalyzer/rest/v1/projects.locations.activityTypes.activities/query#ObservationPeriod.SCHEMA_REPRESENTATION)

Queries policy activities on Google Cloud resources.

### HTTP request

`GET https://policyanalyzer.googleapis.com/v1/{parent=projects/*/locations/*/activityTypes/*}/activities:query`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The container resource on which to execute the request. Acceptable formats: `projects/[PROJECT_ID|PROJECT_NUMBER]/locations/[LOCATION]/activityTypes/[ACTIVITY_TYPE]`

LOCATION here refers to Google Cloud Locations: <https://cloud.google.com/about/locations/>

### Query parameters

Parameters

`filter`

`string`

Optional. Filter expression to restrict the activities returned.

For serviceAccountLastAuthentication activities, supported filters are:

  - `activities.full_resource_name {=} [STRING]`
  - `activities.fullResourceName {=} [STRING]`

where `[STRING]` is the full resource name of the service account.

For serviceAccountKeyLastAuthentication activities, supported filters are:

  - `activities.full_resource_name {=} [STRING]`
  - `activities.fullResourceName {=} [STRING]` where `[STRING]` is the full resource name of the service account key.

`pageSize`

`integer`

Optional. The maximum number of results to return from this request. Max limit is 1000. Non-positive values are ignored. The presence of `nextPageToken` in the response indicates that more results might be available.

`pageToken`

`string`

Optional. If present, then retrieve the next batch of results from the preceding call to this method. `pageToken` must be the value of `nextPageToken` from the previous response. The values of other method parameters should be identical to those in the previous call.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains data with the following structure:

Response to the `activities.query` method.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;activities&quot;: [{object (Activity)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`activities[]`

` object ( Activity  ` )

The set of activities that match the filter included in the request.

`nextPageToken`

`string`

If there might be more results than those appearing in this response, then `nextPageToken` is included. To get the next set of results, call this method again using the value of `nextPageToken` as `pageToken` .

### Authorization Scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://cloud.google.com/docs/authentication/) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permissions on the `parent` resource:

  - `policyanalyzer.serviceAccountKeyLastAuthenticationActivities.query`
  - `policyanalyzer.serviceAccountLastAuthenticationActivities.query`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

## Activity

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;fullResourceName&quot;: string,&quot;activityType&quot;: string,&quot;observationPeriod&quot;: {object (ObservationPeriod)},&quot;activity&quot;: {object}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`fullResourceName`

`string`

The full resource name that identifies the resource.

For examples of full resource names for Google Cloud services, see <https://cloud.google.com/iam/help/troubleshooter/full-resource-names> .

`activityType`

`string`

The type of the activity.

`observationPeriod`

` object ( ObservationPeriod  ` )

The data observation period to build the activity.

`activity`

` object ( Struct  ` format)

A struct of custom fields to explain the activity.

## ObservationPeriod

Represents data observation period.

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
  &quot;startTime&quot;: string,
  &quot;endTime&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`startTime`

` string ( Timestamp  ` format)

The observation start time. The time in this timestamp is always `07:00:00Z` .

A timestamp in RFC3339 UTC "Zulu" format, with nanosecond resolution and up to nine fractional digits. Examples: `"2014-10-02T15:01:23Z"` and `"2014-10-02T15:01:23.045123456Z"` .

`endTime`

` string ( Timestamp  ` format)

The observation end time. The time in this timestamp is always `07:00:00Z` .

A timestamp in RFC3339 UTC "Zulu" format, with nanosecond resolution and up to nine fractional digits. Examples: `"2014-10-02T15:01:23Z"` and `"2014-10-02T15:01:23.045123456Z"` .
