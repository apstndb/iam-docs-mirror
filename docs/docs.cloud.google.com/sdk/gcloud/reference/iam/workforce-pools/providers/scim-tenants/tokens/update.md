---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update
title: gcloud iam workforce-pools providers scim-tenants tokens update
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools providers scim-tenants tokens update - update an IAM workforce identity pool provider SCIM tenant token

SYNOPSIS

`gcloud iam workforce-pools providers scim-tenants tokens update` ( [`TOKEN`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#TOKEN) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#--location) = `LOCATION` [`--provider`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#--provider) = `PROVIDER` [`--scim-tenant`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#--scim-tenant) = `SCIM_TENANT` [`--workforce-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#--workforce-pool) = `WORKFORCE_POOL` ) [`--display-name`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#--display-name) = `DISPLAY_NAME` \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/tokens/update#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Update an existing SCIM token associated with a specific workforce identity pool provider SCIM tenant.

EXAMPLES

To update the display name of a SCIM token with ID `my-token` under tenant `my-tenant` provider `my-provider` in pool `my-pool` located in `global` :

```
gcloud iam workforce-pools providers scim-tenants tokens update my-token --location=global --workforce-pool=my-pool --provider=my-provider --scim-tenant=my-tenant --display-name="New display name"
```

POSITIONAL ARGUMENTS

Workforce pool provider scim token resource - The SCIM token to update. The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`TOKEN`  
ID of the workforce pool provider scim token or fully qualified identifier for the workforce pool provider scim token.

To set the `token` attribute:

- provide the argument `token` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location for the workforce pool.

To set the `location` attribute:

- provide the argument `token` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--provider` = `PROVIDER`  
The ID to use for the workforce pool provider, which becomes the final component of the resource name. This value must be unique within the workforce pool, 4-32 characters in length, and may contain the characters \[a-z0-9-\]. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `provider` attribute:

- provide the argument `token` on the command line with a fully specified name;
- provide the argument `--provider` on the command line.

`--scim-tenant` = `SCIM_TENANT`  
The ID for the SCIM tenant, which becomes the final component of the resource name. This value must be 4-32 characters, alphanumeric (\[a-z0-9-\]), and cannot start with gcp-. To set the `scim-tenant` attribute:

- provide the argument `token` on the command line with a fully specified name;
- provide the argument `--scim-tenant` on the command line.

`--workforce-pool` = `WORKFORCE_POOL`  
The ID to use for the workforce pool, which becomes the final component of the resource name. This value must be a globally unique string of 6 to 63 lowercase letters, digits, or hyphens. It must start with a letter, and cannot have a trailing hyphen. The prefix `gcp-` is reserved for use by Google, and may not be specified. To set the `workforce-pool` attribute:

- provide the argument `token` on the command line with a fully specified name;
- provide the argument `--workforce-pool` on the command line.

REQUIRED FLAGS

`--display-name` = `DISPLAY_NAME`  
Optional, user-specified display name for the SCIM token (max 32 characters).

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam workforce-pools providers scim-tenants tokens update
```

```
gcloud beta iam workforce-pools providers scim-tenants tokens update
```
