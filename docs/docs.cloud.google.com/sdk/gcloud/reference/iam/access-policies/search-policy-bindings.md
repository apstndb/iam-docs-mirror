---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings
title: gcloud iam access-policies search-policy-bindings
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam access-policies search-policy-bindings - search accessPolicies

SYNOPSIS

`gcloud iam access-policies search-policy-bindings` ( [`ACCESS_POLICY`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#ACCESS_POLICY) : [`--folder`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--folder) = `FOLDER` [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--location) = `LOCATION` [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--organization) = `ORGANIZATION` ) \[ [`--filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--filter) = `EXPRESSION` \] \[ [`--limit`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--limit) = `LIMIT` \] \[ [`--page-size`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--page-size) = `PAGE_SIZE` \] \[ [`--sort-by`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#--sort-by) =\[ `FIELD` , …\]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

search accessPolicies

EXAMPLES

To search all accessPolicies, run:

```
gcloud iam access-policies search-policy-bindings
```

POSITIONAL ARGUMENTS

AccessPolicy resource - The name of the access policy. Format: `organizations/{organization_id}/locations/{location}/accessPolicies/{access_policy_id}` `folders/{folder_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_number}/locations/{location}/accessPolicies/{access_policy_id}` The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `access_policy` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` . This resource can be one of the following types: \[iam.folders.locations.accessPolicies, iam.organizations.locations.accessPolicies, iam.projects.locations.accessPolicies\].

This must be specified.

`ACCESS_POLICY`  
ID of the accessPolicy or fully qualified identifier for the accessPolicy.

To set the `access_policy` attribute:

- provide the argument `access_policy` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--folder` = `FOLDER`  
The folder id of the accessPolicy resource.

To set the `folder` attribute:

- provide the argument `access_policy` on the command line with a fully specified name;
- provide the argument `--folder` on the command line. Must be specified for resource of type \[iam.folders.locations.accessPolicies\].

`--location` = `LOCATION`  
The location id of the accessPolicy resource.

To set the `location` attribute:

- provide the argument `access_policy` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--organization` = `ORGANIZATION`  
The organization id of the accessPolicy resource.

To set the `organization` attribute:

- provide the argument `access_policy` on the command line with a fully specified name;
- provide the argument `--organization` on the command line. Must be specified for resource of type \[iam.organizations.locations.accessPolicies\].

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

This command uses the `iam/v3` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

This variant is also available:

```
gcloud beta iam access-policies search-policy-bindings
```
