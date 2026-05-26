---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools
title: gcloud iam workforce-pools
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools - create and manage workforce pools

SYNOPSIS

`gcloud iam workforce-pools` `  GROUP  ` | `  COMMAND  ` \[ `  GCLOUD_WIDE_FLAG …  ` \]

DESCRIPTION

The gcloud iam workforce-pools group lets you create and manage workforce pools for organizations on the Google Cloud Platform.

GCLOUD WIDE FLAGS

These flags are available to all commands: `  --help  ` .

Run ` $ gcloud help  ` for details.

GROUPS

`  GROUP  ` is one of the following:

  - `  operations  `  
    Manage IAM workforce pool long-running operations.
  - `  providers  `  
    Create and manage workforce pool providers.
  - `  subjects  `  
    Create and manage workforce pool subjects.

COMMANDS

`  COMMAND  ` is one of the following:

  - `  create  `  
    Create a new workforce pool under an organization.
  - `  create-cred-config  `  
    Create a configuration file for generated credentials.
  - `  create-login-config  `  
    Create a login configuration file to enable sign-in via a web-based authorization flow using Workforce Identity Federation.
  - `  delete  `  
    Delete a workforce pool.
  - `  describe  `  
    Describe a workforce pool.
  - `  get-iam-policy  `  
    Get the IAM policy for a workforce pool.
  - `  list  `  
    List the workforce pools for an organization.
  - `  set-iam-policy  `  
    Set the IAM policy for a workforce pool.
  - `  undelete  `  
    Undelete a workforce pool.
  - `  update  `  
    Update a workforce pool.

NOTES

These variants are also available:

    gcloud alpha iam workforce-pools

    gcloud beta iam workforce-pools
