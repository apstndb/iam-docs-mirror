---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/delete
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/delete
title: gcloud iam service-accounts delete
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam service-accounts delete - delete a service account from a project

SYNOPSIS

`gcloud iam service-accounts delete` `  SERVICE_ACCOUNT  ` \[ `  GCLOUD_WIDE_FLAG …  ` \]

DESCRIPTION

If the service account does not exist, this command returns a `PERMISSION_DENIED` error.

EXAMPLES

To delete an service account from your project, run:

    gcloud iam service-accounts delete my-iam-account@my-project.iam.gserviceaccount.com

POSITIONAL ARGUMENTS

  - `  SERVICE_ACCOUNT  `  
    The service account to delete. The account should be formatted either as a numeric service account ID or as an email, like this: 123456789876543212345 or my-iam-account@somedomain.com.

GCLOUD WIDE FLAGS

These flags are available to all commands: `  --access-token-file  ` , `  --account  ` , `  --billing-project  ` , `  --configuration  ` , `  --flags-file  ` , `  --flatten  ` , `  --format  ` , `  --help  ` , `  --impersonate-service-account  ` , `  --log-http  ` , `  --project  ` , `  --quiet  ` , `  --trace-token  ` , `  --user-output-enabled  ` , `  --verbosity  ` .

Run ` $ gcloud help  ` for details.

NOTES

These variants are also available:

    gcloud alpha iam service-accounts delete

    gcloud beta iam service-accounts delete
