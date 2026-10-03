---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules
title: gcloud iam workload-identity-pools list-attestation-rules
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workload-identity-pools list-attestation-rules - list the attestation rules on a workload identity pool

SYNOPSIS

`gcloud iam workload-identity-pools list-attestation-rules` ( [`WORKLOAD_IDENTITY_POOL`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#WORKLOAD_IDENTITY_POOL) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--location) = `LOCATION` ) \[ [`--container-id-filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--container-id-filter) = `CONTAINER_ID_FILTER` \] \[ [`--filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--filter) = `EXPRESSION` \] \[ [`--limit`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--limit) = `LIMIT` \] \[ [`--page-size`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--page-size) = `PAGE_SIZE` \] \[ [`--sort-by`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#--sort-by) =\[ `FIELD` , …\]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list-attestation-rules#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

List the attestation rules on a workload identity pool.

EXAMPLES

The following command lists the attestation rules on a workload identity pool `my-pool` with a container id filter.

```
gcloud iam workload-identity-pools list-attestation-rules my-pool --location="global" --container-id-filter="projects/123,projects/456"
```

POSITIONAL ARGUMENTS

Workload identity pool resource - The workload identity pool to list attestation rules for. The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

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

FLAGS

`--container-id-filter` = `CONTAINER_ID_FILTER`  
Apply a filter on the container ids of the attestation rules being listed. Expects a comma-delimited string of project numbers in the format `projects/<project-number>,…` .

LIST COMMAND FLAGS

`--filter` = `EXPRESSION`  
Apply a Boolean filter `EXPRESSION` to each resource item to be listed. If the expression evaluates `True` , then that item is listed. For more details and examples of filter expressions, run \$ [gcloud topic filters](https://docs.cloud.google.com/sdk/gcloud/reference/topic/filters) . This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .

`--limit` = `LIMIT`  
Maximum number of resources to list. The default is `unlimited` . This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .

`--page-size` = `PAGE_SIZE`  
Some services group resource list output into pages. This flag specifies the maximum number of resources per page. The default is determined by the service if it supports paging, otherwise it is `unlimited` (no paging). Paging may be applied before or after `--filter` and `--limit` depending on the service.

`--sort-by` =\[ `FIELD` ,…\]  
Comma-separated list of resource field key names to sort by. The default order is ascending. Prefix a field with \`\`\~´´ for descending order on that field. This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.
