---
name: documents/docs.cloud.google.com/iam/docs/workforce-identity-federation-scim
uri: https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim
title: SCIM provisioning for Workforce Identity Federation
description: Learn about SCIM support for Workforce Identity Federation; provision and manage groups in {{dynamic_data.site_values.cloud_name_short}} from your IdP.
data_source: docs.cloud.google.com
---

If your identity provider (IdP) supports [System for Cross-domain Identity Management (SCIM)](https://en.wikipedia.org/wiki/System_for_Cross-domain_Identity_Management) , you can configure your IdP to provision and manage groups in Google Cloud.

> **Important:** This feature applies only to Gemini Enterprise.

## Capabilities

Workforce Identity Federation SCIM support provides the following capabilities:

  - **Identity synchronization:** Sync read-only copies of user data from your IdP to get a holistic view of user properties and memberships in Google Cloud.

  - **Group flattening:** SCIM processes groups from your IdP so that all direct and indirect (nested) memberships for a user are flattened and synced to the Google Cloud Group Membership Service (GMS). IAM then uses these flattened groups for policy checks, overcoming the size constraints often found in IdP tokens.

  - **Gemini Enterprise integration:** SCIM tenants support sharing in Gemini Enterprise. The SCIM tenant enables two features related to sharing notebooks within NotebookLM Enterprise:
    
      - Autocomplete for email addresses and groups
    
      - The use of the group's name instead of its object ID (UUID)
    
    To learn more, see [Share a notebook with a group](https://docs.cloud.google.com/gemini/enterprise/notebooklm-enterprise/docs/share-notebooks#share-notebook-group) .

## Considerations

When you use Workforce Identity Federation SCIM support, the following considerations apply:

  - You must set up a workforce identity pool and provider before configuring a SCIM tenant.
  - Each workforce identity pool supports only one SCIM tenant. To configure a new SCIM tenant in the same workforce identity pool, you must first delete the existing one. When deleting a SCIM tenant, you have two options:
      - **Soft delete (Default):** Deleting a SCIM tenant initiates a 30-day soft-delete period. During this time, the tenant is hidden and cannot be used, and you cannot create a new SCIM tenant in the same workforce identity pool.
      - **Hard delete:** To permanently and immediately delete a SCIM tenant, use the `--hard-delete` flag with the delete command. This action is irreversible and lets you create a new SCIM tenant in the same workforce identity pool immediately after the deletion completes. Alternatively, you can create a new workforce identity pool and a new SCIM tenant or use a workforce identity pool that hasn't previously been configured with a SCIM tenant.
  - When you use SCIM, you map attributes in both the workforce identity pool provider and the SCIM tenant. The `google.subject` attribute must uniquely refer to the same identities. You specify the `google.subject` in the workforce identity pool provider by using the `--attribute-mapping` flag and in the SCIM tenant using the `--claim-mapping` flag. Mapping non-unique identity values can cause Google Cloud to treat different IdP identities as the same identity. As a result, access that's granted to one user or group identity can extend to others but revoking access from one might not remove it from all.
  - To use SCIM to map groups, set `--scim-usage=enabled-for-groups` . When you map groups using SCIM, any group mapping that's defined in the workforce identity pool provider is ignored. When referring to SCIM-managed groups, the mapped attribute is `google.group` , not `google.groups` . `google.groups` only refers to token-mapped groups.
  - When using SCIM, token-based attributes that are mapped with `--attribute-mapping` can still be used for authentication and in principal identifiers.
  - For Microsoft Entra ID configuration, to enable human-readable group names in Gemini Enterprise, use SCIM.

## Mapping OIDC and SAML providers to SCIM configuration

There must be consistency between the attribute mapping in the workforce identity pool provider configuration ( `--attribute-mapping` ) and the claim mappings in the SCIM tenant ( `--claim-mapping` ). The underlying IdP attribute used to populate `google.subject` (for users) must be the same, whether it's being read from a token claim or a SCIM attribute.

If these mappings are inconsistent, users might be able to sign in but won't be recognized as members of their SCIM-provisioned groups. For example, if the provider uses `assertion.email` for `google.subject` , the SCIM tenant must also use the equivalent SCIM attribute (for example, `user.emails[0].value` ) for `google.subject` .

The following table shows the mappings between token claim attributes and SCIM attributes:

| Google attribute | Workforce identity pool provider mapping    | SCIM tenant mapping (SCIM)          |
| ---------------- | ------------------------------------------- | ----------------------------------- |
| `google.subject` | `assertion.oid` (EntraId)                   | `user.externalId`                   |
| `google.subject` | `assertion.sub` (Okta)                      | `user.externalId`                   |
| `google.subject` | `assertion.preferred_username`              | `user.userName`                     |
| `google.subject` | `assertion.preferred_username.lowerAscii()` | `user.userName.lowerAscii()`        |
| `google.subject` | `assertion.email`                           | `user.emails[0].value`              |
| `google.subject` | `assertion.email.lowerAscii()`              | `user.emails[0].value.lowerAscii()` |
| `google.group`   | N/A (Mapped using SCIM)                     | `group.externalId`                  |

> **Note:** When you use SCIM for groups, you must update your provider with `--scim-usage=enabled-for-groups` . The `google.groups` attribute in the provider mapping is ignored for group-based authorization; instead, use `google.group` .

## Supported and unsupported endpoints

The following standard SCIM protocol endpoints are supported:

  - `/Users` : manage user resources. Supported operations: `Create` , `Get` , `Update` , `Delete` , `Patch` , and `Put` .

  - `/Groups` : manage group resources. Supported operations: `Create` , `Get` , `Update` , `Delete` , and `Patch` . The `PUT` method isn't supported for groups.

  - `/Schemas` : retrieve schema information.

  - `/ServiceProviderConfig` : retrieve the service provider configuration.

> **Note:** SCIM integration with Okta does not support `Import Users` and `Import Groups` features from Google Cloud to Okta.

The following SCIM protocol endpoints aren't supported:

  - `/Me`

  - `/Bulk`

  - `/Search`

  - `/ResourceTypes`

## Limitations

The following sections describe the limitations and deviations of the Workforce Identity Federation SCIM implementation from the SCIM specifications (RFC 7643 and 7644).

### Protocol feature limitations

  - **Filter support:** When you list users or groups using the `/Users` or `/Groups` endpoints, filter expressions only support the `eq` (equals) operator. You can combine multiple `eq` filters with `and` . Other SCIM filter operators, such as `co` (contains) or `sw` (starts with), aren't supported.

  - **Pagination:** The IAM SCIM API does not support standard pagination for listing users or groups.
    
      - `startIndex` : this parameter is always `1` . The API returns up to 100 results regardless of the value that you provide for `startIndex` .
    
      - `itemsPerPage` : the maximum number of resources that are returned in a single response is 100.
    
      - `totalResults` : the API does not return the actual total count of matching resources. The `totalResults` field in the response is always equal to the number of items that are returned in that response, with a maximum of 100.

  - **Get Group and list Groups without filter:** `GetGroup` and `ListGroups` APIs return an empty member list. To retrieve members for a specific group, use the `ListGroups` API with a member filter.

  - **Non-compliant JSON response with invalid tokens:** APIs that contain invalid API token result in a `401 HTTP error` from Google Cloud. The response is not a JSON structure as required by the specifications.

### SCIM behavior limitations

  - **Immutable identifiers:** The values of SCIM attributes that are mapped to `google.subject` or `google.group` are treated as immutable identifiers within Google Cloud. If you need to change these values, you must permanently delete the user or group from your IdP and then recreate it with the new value.

  - **Single email requirement:** For successful SCIM synchronization, each user must have exactly one email address of type `work` . Provisioning or updates will fail if your IdP sends multiple emails or if the single email provided is not typed as `work` .

  - **Case-insensitive transformations:** Limited Common Expression Language (CEL) transformations are supported for SCIM claim mappings. Only `.lowerAscii()` is supported for case-insensitive comparisons for `user.userName` and `user.emails[0].value` .

### Attribute limitations

The following sections describe the attribute support for users, groups, and the enterprise user schema extension.

#### User attributes

The following table details the support for user attributes:

| Attribute           | Sub-attributes                                                                                  | Supported | Limitations                              |
| ------------------- | ----------------------------------------------------------------------------------------------- | --------- | ---------------------------------------- |
| `userName`          | N/A                                                                                             | Yes       | N/A                                      |
| `name`              | `formatted` , `familyName` , `givenName` , `middleName` , `honorificPrefix` , `honorificSuffix` | Yes       | N/A                                      |
| `displayName`       | N/A                                                                                             | Yes       | N/A                                      |
| `nickName`          | N/A                                                                                             | Yes       | N/A                                      |
| `profileUrl`        | N/A                                                                                             | Yes       | N/A                                      |
| `title`             | N/A                                                                                             | Yes       | N/A                                      |
| `userType`          | N/A                                                                                             | Yes       | N/A                                      |
| `preferredLanguage` | N/A                                                                                             | Yes       | N/A                                      |
| `locale`            | N/A                                                                                             | Yes       | N/A                                      |
| `timezone`          | N/A                                                                                             | Yes       | N/A                                      |
| `active`            | N/A                                                                                             | Yes       | N/A                                      |
| `password`          | N/A                                                                                             | No        | N/A                                      |
| `emails`            | `display` , `type` , `value` , `primary`                                                        | Yes       | Only the `work` email type is supported. |
| `phoneNumbers`      | `display` , `type` , `value` , `primary`                                                        | Yes       | N/A                                      |
| `ims`               | `display` , `type` , `value`                                                                    | Yes       | N/A                                      |
| `photos`            | `display` , `type` , `value`                                                                    | Yes       | N/A                                      |
| `addresses`         | `formatted` , `streetAddress` , `locality` , `region` , `postalCode` , `country`                | Yes       | N/A                                      |
| `groups`            | N/A                                                                                             | No        | N/A                                      |
| `entitlements`      | `display` , `type` , `value`                                                                    | Yes       | N/A                                      |
| `roles`             | `type` , `value`                                                                                | Yes       | `display` isn't supported.               |
| `x509Certificates`  | `type` , `value`                                                                                | Yes       | `display` isn't supported.               |

#### Group attributes

The following table details the support for group attributes:

| Attribute     | Supported sub-attributes              |
| ------------- | ------------------------------------- |
| `displayName` | N/A                                   |
| `externalId`  | N/A                                   |
| `members`     | `value` , `type` , `$ref` , `display` |

#### Enterprise user schema extension attributes

The following table details the support for the enterprise user schema extension:

| Attribute        | Supported sub-attributes         |
| ---------------- | -------------------------------- |
| `employeeNumber` | N/A                              |
| `costCenter`     | N/A                              |
| `organization`   | N/A                              |
| `division`       | N/A                              |
| `department`     | N/A                              |
| `manager`        | `value` , `$ref` , `displayName` |

## What's next

  - [Configure SCIM support for Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/configuring-workforce-identity-federation#configure-scim)
  - [IAM SCIM audit logging](https://docs.cloud.google.com/iam/docs/audit-logging/audit-logging-iamscim)
