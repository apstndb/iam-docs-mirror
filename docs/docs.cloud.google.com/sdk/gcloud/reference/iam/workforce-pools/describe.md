---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/describe
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/describe
title: gcloud iam workforce-pools describe
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools describe - describe a workforce pool

SYNOPSIS

`gcloud iam workforce-pools describe` ( [`WORKFORCE_POOL`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/describe#WORKFORCE_POOL) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/describe#--location) = `LOCATION` ) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/describe#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Describe a workforce pool.

EXAMPLES

The following command describes a workforce pool with ID `my-workforce-pool` :

```
gcloud iam workforce-pools describe my-workforce-pool --location=global
```

POSITIONAL ARGUMENTS

Workforce pool resource - The workforce pool to describe. The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`WORKFORCE_POOL`  
ID of the workforce pool or fully qualified identifier for the workforce pool.

To set the `workforce_pool` attribute:

- provide the argument `workforce_pool` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location for the workforce pool.

To set the `location` attribute:

- provide the argument `workforce_pool` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam workforce-pools describe
```

```
gcloud beta iam workforce-pools describe
```
