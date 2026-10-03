---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse
title: CheckOnboardingStatusResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#SCHEMA_REPRESENTATION)
- [Finding](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#Finding)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#Finding.SCHEMA_REPRESENTATION)
- [IAMAccessDenied](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#IAMAccessDenied)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#IAMAccessDenied.SCHEMA_REPRESENTATION)

Response message for `CheckOnboardingStatus` method.

**JSON representation**

```
{
  "serviceAccount": string,
  "findings": [
    {
      object (Finding)
    }
  ]
}
```

| Fields           |                                                                                                                                                                                                                                                                                                          |
|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `serviceAccount` | `string` The service account that PAM uses to act on this resource.                                                                                                                                                                                                                                      |
| `findings[]`     | `object ( `[`Finding`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#Finding)` )` List of issues that are preventing PAM from functioning for this resource and need to be fixed to complete onboarding. Some issues might not be detected or reported. |

## Finding

Finding represents an issue which prevents PAM from functioning properly for this resource.

**JSON representation**

```
{

  // Union field finding_type can be only one of the following:
  "iamAccessDenied": {
    object (IAMAccessDenied)
  }
  // End of list of possible types for union field finding_type.
}
```

| Fields                                                                        |                                                                                                                                                                                                               |
|-------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Union field `finding_type` . `finding_type` can be only one of the following: |                                                                                                                                                                                                               |
| `iamAccessDenied`                                                             | `object ( `[`IAMAccessDenied`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CheckOnboardingStatusResponse#IAMAccessDenied)` )` PAM's service account is being denied access by Cloud IAM. |

## IAMAccessDenied

PAM's service account is being denied access by Cloud IAM. This can be fixed by granting a role that contains the missing permissions to the service account or exempting it from deny policies if they are blocking the access.

**JSON representation**

```
{
  "missingPermissions": [
    string
  ]
}
```

| Fields                 |                                                     |
|------------------------|-----------------------------------------------------|
| `missingPermissions[]` | `string` List of permissions that are being denied. |
