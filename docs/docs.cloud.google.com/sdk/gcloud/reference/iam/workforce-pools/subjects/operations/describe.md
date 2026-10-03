---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe
title: gcloud iam workforce-pools subjects operations describe
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools subjects operations describe - describe a workforce pool subject operation

SYNOPSIS

`gcloud iam workforce-pools subjects operations describe` ( [`OPERATION`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe#OPERATION) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe#--location) = `LOCATION` [`--subject`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe#--subject) = `SUBJECT` [`--workforce-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe#--workforce-pool) = `WORKFORCE_POOL` ) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/subjects/operations/describe#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Describe a workforce pool subject operation.

EXAMPLES

To describe the long-running workforce pool subject operation with the ID `my-operation` , run:

```
gcloud iam workforce-pools subjects operations describe my-operation --workforce-pool="my-workforce-pool" --subject="my-subject" --location="global"
```

POSITIONAL ARGUMENTS

Workforce pool subject operation resource - The workforce pool subject long-running operation to describe. The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`OPERATION`  
ID of the workforce pool subject operation or fully qualified identifier for the workforce pool subject operation.

To set the `operation` attribute:

- provide the argument `operation` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location for the workforce pool.

To set the `location` attribute:

- provide the argument `operation` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--subject` = `SUBJECT`  
The ID to use for the workforce pool subject, which becomes the final component of the resource name. To set the `subject` attribute:

- provide the argument `operation` on the command line with a fully specified name;
- provide the argument `--subject` on the command line.

`--workforce-pool` = `WORKFORCE_POOL`  
The ID to use for the workforce pool, which becomes the final component of the resource name. This value must be a globally unique string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `workforce-pool` attribute:

- provide the argument `operation` on the command line with a fully specified name;
- provide the argument `--workforce-pool` on the command line.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>
