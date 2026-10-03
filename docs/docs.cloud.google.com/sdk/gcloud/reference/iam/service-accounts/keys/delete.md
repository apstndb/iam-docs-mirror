---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/delete
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/delete
title: gcloud iam service-accounts keys delete
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam service-accounts keys delete - delete a service account key

SYNOPSIS

`gcloud iam service-accounts keys delete` `KEY-ID` [`--iam-account`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/delete#--iam-account) = `IAM_ACCOUNT` \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/delete#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

If the service account does not exist, this command returns a `PERMISSION_DENIED` error.

EXAMPLES

To delete a key with ID `b4f1037aeef9ab37deee9` for the service account `my-iam-account@my-project.iam.gserviceaccount.com` , run:

```
gcloud iam service-accounts keys delete b4f1037aeef9ab37deee9 --iam-account=my-iam-account@my-project.iam.gserviceaccount.com
```

POSITIONAL ARGUMENTS

`KEY-ID`  
The key to delete.

REQUIRED FLAGS

`--iam-account` = `IAM_ACCOUNT`  
The service account from which to delete a key.

To list all service accounts in the project, run:

```
gcloud iam service-accounts list
```

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam service-accounts keys delete
```

```
gcloud beta iam service-accounts keys delete
```
