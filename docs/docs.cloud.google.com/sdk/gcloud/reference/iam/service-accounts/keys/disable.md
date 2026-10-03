---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/disable
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/disable
title: gcloud iam service-accounts keys disable
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam service-accounts keys disable - disable a service account key

SYNOPSIS

`gcloud iam service-accounts keys disable` ( [`IAM_KEY`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/disable#IAM_KEY) : [`--iam-account`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/disable#--iam-account) = `IAM_ACCOUNT` ) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/keys/disable#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Disable a service account key.

If the service account does not exist, this command returns a `PERMISSION_DENIED` error.

EXAMPLES

To disable a key with ID `b4f1037aeef9ab37deee9` for the service account `my-iam-account@my-project.iam.gserviceaccount.com` , run:

```
gcloud iam service-accounts keys disable b4f1037aeef9ab37deee9 --iam-account=my-iam-account@my-project.iam.gserviceaccount.com
```

POSITIONAL ARGUMENTS

IamKey resource - The id of the key to disable. The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `iam_key` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` .

This must be specified.

`IAM_KEY`  
ID of the iamKey or fully qualified identifier for the iamKey.

To set the `iam_key` attribute:

- provide the argument `iam_key` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--iam-account` = `IAM_ACCOUNT`  
The name of the IAM ServiceAccount. To set the `iam-account` attribute:

- provide the argument `iam_key` on the command line with a fully specified name;
- provide the argument `--iam-account` on the command line.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam service-accounts keys disable
```

```
gcloud beta iam service-accounts keys disable
```
