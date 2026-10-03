---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete
title: gcloud iam workforce-pools providers scim-tenants undelete
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools providers scim-tenants undelete - undelete an IAM workforce identity pool provider SCIM tenant

SYNOPSIS

`gcloud iam workforce-pools providers scim-tenants undelete` ( [`SCIM_TENANT`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete#SCIM_TENANT) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete#--location) = `LOCATION` [`--provider`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete#--provider) = `PROVIDER` [`--workforce-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete#--workforce-pool) = `WORKFORCE_POOL` ) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/undelete#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Undelete a previously deleted SCIM tenant associated with a specific workforce identity pool provider, restoring it to an active state.

EXAMPLES

To undelete a SCIM tenant with ID `my-tenant` under provider `my-okta-provider` in pool `my-pool` located in `global` :

```
gcloud iam workforce-pools providers scim-tenants undelete my-tenant --location=global --workforce-pool=my-pool --provider=my-okta-provider
```

POSITIONAL ARGUMENTS

Workforce pool provider scim tenant resource - The SCIM tenant to undelete. The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`SCIM_TENANT`  
ID of the workforce pool provider scim tenant or fully qualified identifier for the workforce pool provider scim tenant.

To set the `scim_tenant` attribute:

- provide the argument `scim_tenant` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location for the workforce pool.

To set the `location` attribute:

- provide the argument `scim_tenant` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--provider` = `PROVIDER`  
The ID to use for the workforce pool provider, which becomes the final component of the resource name. This value must be unique within the workforce pool, 4-32 characters in length, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `provider` attribute:

- provide the argument `scim_tenant` on the command line with a fully specified name;
- provide the argument `--provider` on the command line.

`--workforce-pool` = `WORKFORCE_POOL`  
The ID to use for the workforce pool, which becomes the final component of the resource name. This value must be a globally unique string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `workforce-pool` attribute:

- provide the argument `scim_tenant` on the command line with a fully specified name;
- provide the argument `--workforce-pool` on the command line.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam workforce-pools providers scim-tenants undelete
```

```
gcloud beta iam workforce-pools providers scim-tenants undelete
```
