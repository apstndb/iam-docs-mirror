---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create
title: gcloud iam service-accounts create
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam service-accounts create - create a service account for a project

SYNOPSIS

`gcloud iam service-accounts create` [`NAME`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create#NAME) \[ [`--description`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create#--description) = `DESCRIPTION` \] \[ [`--display-name`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create#--display-name) = `DISPLAY_NAME` \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/create#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

This command creates a service account with the provided name. For subsequent commands regarding service accounts, this service account should be referred to by the email account in the response.

EXAMPLES

To create a service account for your project, run:

```
gcloud iam service-accounts create some-account-name --display-name="My Service Account"
```

To work with this service account in subsequent IAM commands, use the email resulting from this call as the IAM_ACCOUNT argument.

POSITIONAL ARGUMENTS

`NAME`  
The internal name of the new service account. Used to generate an IAM_ACCOUNT (an IAM internal email address used as an identifier of service account), which must be passed to subsequent commands.

FLAGS

`--description` = `DESCRIPTION`  
A textual description for the account.

`--display-name` = `DISPLAY_NAME`  
A textual name to display for the account.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam service-accounts create
```

```
gcloud beta iam service-accounts create
```
