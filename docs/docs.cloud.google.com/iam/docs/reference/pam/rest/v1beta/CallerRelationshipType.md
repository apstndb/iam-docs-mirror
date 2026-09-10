---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CallerRelationshipType
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/CallerRelationshipType
title: CallerRelationshipType
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

Different types of relationships a user can have with a grant.

Enums

`CALLER_RELATIONSHIP_TYPE_UNSPECIFIED`

Unspecified caller relationship type.

`HAD_CREATED`

The user created this grant by calling `CreateGrant` earlier.

`CAN_APPROVE`

The user is an approver for the entitlement that this grant is parented under and can currently approve/deny it.

`HAD_APPROVED`

The caller had successfully approved/denied this grant earlier.
