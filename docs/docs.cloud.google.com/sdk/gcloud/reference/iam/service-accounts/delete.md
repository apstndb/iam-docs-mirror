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

`gcloud iam service-accounts delete` [`SERVICE_ACCOUNT`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/delete#SERVICE_ACCOUNT) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/delete#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

If the service account does not exist, this command returns a `PERMISSION_DENIED` error.

EXAMPLES

To delete an service account from your project, run:

```
gcloud iam service-accounts delete my-iam-account@my-project.iam.gserviceaccount.com
```

POSITIONAL ARGUMENTS

`SERVICE_ACCOUNT`  
The service account to delete. The account should be formatted either as a numeric service account ID or as an email, like this: 123456789876543212345 or my-iam-account@somedomain.com.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam service-accounts delete
```

```
gcloud beta iam service-accounts delete
```
