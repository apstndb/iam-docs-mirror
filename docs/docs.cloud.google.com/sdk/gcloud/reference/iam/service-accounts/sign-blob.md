---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/sign-blob
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/sign-blob
title: gcloud iam service-accounts sign-blob
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam service-accounts sign-blob - sign a blob with a managed service account key

SYNOPSIS

`gcloud iam service-accounts sign-blob` `INPUT-FILE` `OUTPUT-FILE` [`--iam-account`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/sign-blob#--iam-account) = `IAM_ACCOUNT` \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/service-accounts/sign-blob#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

This command signs a file containing arbitrary binary data (a blob) using a system-managed service account key.

If the service account does not exist, this command returns a `PERMISSION_DENIED` error.

EXAMPLES

To sign a blob file with a system-managed service account key, run:

```
gcloud iam service-accounts sign-blob --iam-account=my-iam-account@my-project.iam.gserviceaccount.com input.bin output.bin
```

POSITIONAL ARGUMENTS

`INPUT-FILE`  
A path to the blob file to be signed.

`OUTPUT-FILE`  
A path the resulting signed blob will be written to.

REQUIRED FLAGS

`--iam-account` = `IAM_ACCOUNT`  
The service account to sign as.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

SEE ALSO

For more information on how this command ties into the wider cloud infrastructure, please see <https://cloud.google.com/appengine/docs/java/appidentity/>

NOTES

These variants are also available:

```
gcloud alpha iam service-accounts sign-blob
```

```
gcloud beta iam service-accounts sign-blob
```
