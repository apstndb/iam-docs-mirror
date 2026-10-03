---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule
title: gcloud iam workload-identity-pools add-attestation-rule
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workload-identity-pools add-attestation-rule - add an attestation rule on a workload identity pool

SYNOPSIS

`gcloud iam workload-identity-pools add-attestation-rule` ( [`WORKLOAD_IDENTITY_POOL`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule#WORKLOAD_IDENTITY_POOL) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule#--location) = `LOCATION` ) [`--google-cloud-resource`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule#--google-cloud-resource) = `GOOGLE_CLOUD_RESOURCE` \[ [`--async`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule#--async) \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/add-attestation-rule#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Add an attestation rule on a workload identity pool.

EXAMPLES

The following command adds an attestation rule with a Google Cloud resource on a workload identity pool `my-pool` .

```
gcloud iam workload-identity-pools add-attestation-rule my-pool --location="global" --google-cloud-resource="//run.googleapis.com/projects/123/type/Service/*"
```

POSITIONAL ARGUMENTS

Workload identity pool resource - The workload identity pool to add the attestation rule on. The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `workload_identity_pool` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` .

This must be specified.

`WORKLOAD_IDENTITY_POOL`  
ID of the workload identity pool or fully qualified identifier for the workload identity pool.

To set the `workload_identity_pool` attribute:

- provide the argument `workload_identity_pool` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location name.

To set the `location` attribute:

- provide the argument `workload_identity_pool` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

REQUIRED FLAGS

`--google-cloud-resource` = `GOOGLE_CLOUD_RESOURCE`  
A single workload running on Google Cloud. This will be set in the attestation rule to be added.

OPTIONAL FLAGS

`--async`  
Return immediately, without waiting for the operation in progress to complete.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.
