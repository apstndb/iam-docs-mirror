---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules
title: gcloud iam workload-identity-pools managed-identities list-attestation-rules
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workload-identity-pools managed-identities list-attestation-rules - list the attestation rules on a workload identity pool managed identity

SYNOPSIS

`gcloud iam workload-identity-pools managed-identities list-attestation-rules` ( [`MANAGED_IDENTITY`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#MANAGED_IDENTITY) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--location) = `LOCATION` [`--namespace`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--namespace) = `NAMESPACE` [`--workload-identity-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--workload-identity-pool) = `WORKLOAD_IDENTITY_POOL` ) \[ [`--container-id-filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--container-id-filter) = `CONTAINER_ID_FILTER` \] \[ [`--filter`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--filter) = `EXPRESSION` \] \[ [`--limit`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--limit) = `LIMIT` \] \[ [`--page-size`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--page-size) = `PAGE_SIZE` \] \[ [`--sort-by`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#--sort-by) =\[ `FIELD` , …\]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/managed-identities/list-attestation-rules#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

List the attestation rules on a workload identity pool managed identity.

EXAMPLES

The following command lists the attestation rules on a workload identity pool managed identity `my-managed-identity` with a container id filter.

```
gcloud iam workload-identity-pools managed-identities list-attestation-rules my-managed-identity --namespace="my-namespace" --workload-identity-pool="my-workload-identity-pool" --location="global" --container-id-filter="projects/123,projects/456"
```

POSITIONAL ARGUMENTS

Workload identity pool managed identity resource - The managed identity to list attestation rules. The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `managed_identity` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` .

This must be specified.

`MANAGED_IDENTITY`  
ID of the workload identity pool managed identity or fully qualified identifier for the workload identity pool managed identity.

To set the `managed_identity` attribute:

- provide the argument `managed_identity` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location name.

To set the `location` attribute:

- provide the argument `managed_identity` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--namespace` = `NAMESPACE`  
The ID to use for the namespace. This value must be 2-63 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `namespace` attribute:

- provide the argument `managed_identity` on the command line with a fully specified name;
- provide the argument `--namespace` on the command line.

`--workload-identity-pool` = `WORKLOAD_IDENTITY_POOL`  
The ID to use for the pool, which becomes the final component of the resource name. This value should be 4-32 characters, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `workload-identity-pool` attribute:

- provide the argument `managed_identity` on the command line with a fully specified name;
- provide the argument `--workload-identity-pool` on the command line.

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
