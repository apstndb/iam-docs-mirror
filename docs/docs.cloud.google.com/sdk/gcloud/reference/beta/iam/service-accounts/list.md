---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/beta/iam/service-accounts/list
uri: https://docs.cloud.google.com/sdk/gcloud/reference/beta/iam/service-accounts/list
title: gcloud beta iam service-accounts list
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud beta iam service-accounts list - list all of a project's service accounts

SYNOPSIS

`gcloud beta iam service-accounts list` \[ `  --filter  ` = `  EXPRESSION  ` \] \[ `  --limit  ` = `  LIMIT  ` \] \[ `  --sort-by  ` =\[ `  FIELD  ` , …\]\] \[ `  --uri  ` \] \[ `  GCLOUD_WIDE_FLAG …  ` \]

DESCRIPTION

`(BETA)` List all of a project's service accounts.

EXAMPLES

To list all service accounts in the current project, run:

    gcloud beta iam service-accounts list

LIST COMMAND FLAGS

  - `--filter` = `  EXPRESSION  `  
    Apply a Boolean filter `  EXPRESSION  ` to each resource item to be listed. If the expression evaluates `True` , then that item is listed. For more details and examples of filter expressions, run $ [gcloud topic filters](https://docs.cloud.google.com/sdk/gcloud/reference/topic/filters) . This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .
  - `--limit` = `  LIMIT  `  
    Maximum number of resources to list. The default is `unlimited` . This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .
  - `--sort-by` =\[ `  FIELD  ` ,…\]  
    Comma-separated list of resource field key names to sort by. The default order is ascending. Prefix a field with \`\`\~´´ for descending order on that field. This flag interacts with other flags that are applied in this order: `--flatten` , `--sort-by` , `--filter` , `--limit` .
  - `--uri`  
    Print a list of resource URIs instead of the default output, and change the command output to a list of URIs. If this flag is used with `--format` , the formatting is applied on this URI list. To display URIs alongside other keys instead, use the `uri()` transform.

GCLOUD WIDE FLAGS

These flags are available to all commands: `  --access-token-file  ` , `  --account  ` , `  --billing-project  ` , `  --configuration  ` , `  --flags-file  ` , `  --flatten  ` , `  --format  ` , `  --help  ` , `  --impersonate-service-account  ` , `  --log-http  ` , `  --project  ` , `  --quiet  ` , `  --trace-token  ` , `  --user-output-enabled  ` , `  --verbosity  ` .

Run ` $ gcloud help  ` for details.

NOTES

This command is currently in beta and might change without notice. These variants are also available:

    gcloud iam service-accounts list

    gcloud alpha iam service-accounts list
