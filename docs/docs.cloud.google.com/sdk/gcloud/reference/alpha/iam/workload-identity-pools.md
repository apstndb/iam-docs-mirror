---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/alpha/iam/workload-identity-pools
uri: https://docs.cloud.google.com/sdk/gcloud/reference/alpha/iam/workload-identity-pools
title: gcloud alpha iam workload-identity-pools
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud alpha iam workload-identity-pools - manage IAM workload identity pools

SYNOPSIS

`gcloud alpha iam workload-identity-pools` `  GROUP  ` | `  COMMAND  ` \[ `  GCLOUD_WIDE_FLAG …  ` \]

DESCRIPTION

`(ALPHA)` Commands for managing IAM workload identity pools.

GCLOUD WIDE FLAGS

These flags are available to all commands: `  --help  ` .

Run ` $ gcloud help  ` for details.

GROUPS

`  GROUP  ` is one of the following:

  - `  operations  `  
    `(ALPHA)` Manage IAM workload identity pool long running operations.
  - `  providers  `  
    `(ALPHA)` Manage IAM workload identity pool providers.

COMMANDS

`  COMMAND  ` is one of the following:

  - `  create  `  
    `(ALPHA)` Create a new workload identity pool.
  - `  create-cred-config  `  
    `(ALPHA)` Create a configuration file for generated credentials.
  - `  delete  `  
    `(ALPHA)` Delete a workload identity pool.
  - `  describe  `  
    `(ALPHA)` Describe a workload identity pool.
  - `  list  `  
    `(ALPHA)` List workload identity pools.
  - `  undelete  `  
    `(ALPHA)` Undelete a workload identity pool.
  - `  update  `  
    `(ALPHA)` Update a workload identity pool.

NOTES

This command is currently in alpha and might change without notice. If this command fails with API permission errors despite specifying the correct project, you might be trying to access an API with an invitation-only early access allowlist. These variants are also available:

    gcloud iam workload-identity-pools

    gcloud beta iam workload-identity-pools
