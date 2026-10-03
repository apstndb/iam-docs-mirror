---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list
title: gcloud iam workforce-pools providers keys list
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools providers keys list - list workforce pool provider keys

SYNOPSIS

`gcloud iam workforce-pools providers keys list` ( [`--provider`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--provider) = `PROVIDER` : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--location) = `LOCATION` [`--workforce-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--workforce-pool) = `WORKFORCE_POOL` ) \[ [`--show-deleted`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--show-deleted) \] \[ [`--filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--filter) = `EXPRESSION` \] \[ [`--limit`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--limit) = `LIMIT` \] \[ [`--page-size`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--page-size) = `PAGE_SIZE` \] \[ [`--sort-by`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#--sort-by) =\[ `FIELD` , …\]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/keys/list#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

List workforce pool provider keys.

EXAMPLES

The following command lists the keys in the workforce pool provider with ID `my-provider` , including soft-deleted keys:

```
gcloud iam workforce-pools providers keys list --workforce-pool="my-workforce-pool" --provider="my-provider" --location="global" --show-deleted
```

REQUIRED FLAGS

Workforce pool provider resource - The parent workforce pool provider of the keys to list. The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`--provider` = `PROVIDER`  
ID of the workforce pool provider or fully qualified identifier for the workforce pool provider.

To set the `provider` attribute:

- provide the argument `--provider` on the command line.

This flag argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location for the workforce pool.

To set the `location` attribute:

- provide the argument `--provider` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--workforce-pool` = `WORKFORCE_POOL`  
The ID to use for the workforce pool, which becomes the final component of the resource name. This value must be a globally unique string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `workforce-pool` attribute:

- provide the argument `--provider` on the command line with a fully specified name;
- provide the argument `--workforce-pool` on the command line.

FLAGS

`--show-deleted`  
Show soft-deleted keys by specifying this flag.

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

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam workforce-pools providers keys list
```

```
gcloud beta iam workforce-pools providers keys list
```
