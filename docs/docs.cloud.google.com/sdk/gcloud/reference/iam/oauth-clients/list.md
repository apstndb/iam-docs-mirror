---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list
title: gcloud iam oauth-clients list
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam oauth-clients list - list OAuth clients

SYNOPSIS

`gcloud iam oauth-clients list` [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--location) = `LOCATION` \[ [`--show-deleted`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--show-deleted) \] \[ [`--filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--filter) = `EXPRESSION` \] \[ [`--limit`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--limit) = `LIMIT` \] \[ [`--page-size`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--page-size) = `PAGE_SIZE` \] \[ [`--sort-by`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#--sort-by) =\[ `FIELD` , …\]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/oauth-clients/list#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

List OAuth clients.

EXAMPLES

The following command lists all OAuth clients in the default project, including the soft-deleted ones:

```
gcloud iam oauth-clients list --location="global" --show-deleted
```

REQUIRED FLAGS

Location resource - The location you want to list OAuth clients for. This represents a Cloud resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `--location` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` .

This must be specified.

`--location` = `LOCATION`  
ID of the location or fully qualified identifier for the location.

To set the `location` attribute:

- provide the argument `--location` on the command line.

FLAGS

`--show-deleted`  
Whether to return soft-deleted OAuth clients.

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

This variant is also available:

```
gcloud alpha iam oauth-clients list
```
