---
name: documents/docs.cloud.google.com/iam/docs/workforce-delete-user-data
uri: https://docs.cloud.google.com/iam/docs/workforce-delete-user-data
title: Delete Workforce Identity Federation users and their data
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This guide shows you how to delete workforce users (also known as principals) and data that they exclusively own, collectively "users and data". To learn more about how Google Cloud deletes data, see [Data deletion on Google Cloud](https://docs.cloud.google.com/docs/security/deletion) .

## Delete Workforce Identity Federation user data

> **Caution:** Deleting users also deletes all of their data on Google Cloud.

To delete workforce users and data, you must initiate a delete request with a user resource ID that is formatted as follows:

    principal://iam.googleapis.com/locations/LOCATION/workforcePools/WORKFORCE_POOL_ID/subject/SUBJECT_ID

The stages in the data-deletion pipeline are as follows:

**Stage-1: Soft-deletion state:** After you initiate a delete request, the users and data are immediately marked for deletion and enter a 30-day soft- deletion state. In that state, the data can be deleted at anytime. After it is deleted, it cannot be accessed unless it is first recovered. You can *usually* recover data that is in this state.

**Stage-2: Purged state:** Users and data that remain deleted longer than 30 days are in the purged state, meaning they are permanently deleted and cannot be recovered. After the data enters the purged state, the user identifier can be reused and assigned to another user. This is because the identifier is processed as a new entity in Identity and Access Management (IAM).

### Required permissions

This section details the IAM roles or permissions required to perform delete and undelete operations.

The permissions are as follows:

  - `iam.googleapis.com/workforcePoolSubjects.delete`
  - `iam.googleapis.com/workforcePoolSubjects.undelete`

These permissions are included in the Workforce Pool Admin role ( `roles/iam.workforcePoolAdmin` ).

### Delete users and data

To delete users and data, do the following:

### gcloud

Execute the following command:

    gcloud iam workforce-pools subjects delete \
        SUBJECT_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace the following:

  - `  SUBJECT_ID  ` : the user resource ID to delete.
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID.

### Undelete users and data

During the soft-deletion or pre-purge deletion phase, you can undo a user deletion.

To undelete a user, do the following:

### gcloud

To undo a user deletion, execute the following command:

    gcloud iam workforce-pools subjects undelete SUBJECT_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace the following:

  - `  SUBJECT_ID  ` : the user resource ID for which to undo a previous delete.
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID.
