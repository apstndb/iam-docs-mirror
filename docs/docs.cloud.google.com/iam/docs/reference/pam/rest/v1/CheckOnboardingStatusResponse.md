---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse
title: CheckOnboardingStatusResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse#SCHEMA_REPRESENTATION)
  - [Finding](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse#Finding)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse#Finding.SCHEMA_REPRESENTATION)
  - [IAMAccessDenied](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse#IAMAccessDenied)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/CheckOnboardingStatusResponse#IAMAccessDenied.SCHEMA_REPRESENTATION)

Response message for `CheckOnboardingStatus` method.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;serviceAccount&quot;: string,&quot;findings&quot;: [{object (Finding)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`serviceAccount`

`string`

The service account that PAM uses to act on this resource.

`findings[]`

` object ( Finding  ` )

List of issues that are preventing PAM from functioning for this resource and need to be fixed to complete onboarding. Some issues might not be detected or reported.

## Finding

Finding represents an issue which prevents PAM from functioning properly for this resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field finding_type can be only one of the following:&quot;iamAccessDenied&quot;: {object (IAMAccessDenied)}// End of list of possible types for union field finding_type.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `finding_type` .

`finding_type` can be only one of the following:

`iamAccessDenied`

` object ( IAMAccessDenied  ` )

PAM's service account is being denied access by Cloud IAM.

## IAMAccessDenied

PAM's service account is being denied access by Cloud IAM. This can be fixed by granting a role that contains the missing permissions to the service account or exempting it from deny policies if they are blocking the access.

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
  &quot;missingPermissions&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`missingPermissions[]`

`string`

List of permissions that are being denied.
