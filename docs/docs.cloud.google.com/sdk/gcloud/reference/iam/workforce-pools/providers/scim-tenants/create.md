---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create
title: gcloud iam workforce-pools providers scim-tenants create
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam workforce-pools providers scim-tenants create - create an IAM workforce identity pool provider SCIM tenant

SYNOPSIS

`gcloud iam workforce-pools providers scim-tenants create` ( [`SCIM_TENANT`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#SCIM_TENANT) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--location) = `LOCATION` [`--provider`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--provider) = `PROVIDER` [`--workforce-pool`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--workforce-pool) = `WORKFORCE_POOL` ) [`--claim-mapping`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--claim-mapping) = \[ `KEY` = `VALUE` , …\] \[ [`--description`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--description) = `DESCRIPTION` \] \[ [`--display-name`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#--display-name) = `DISPLAY_NAME` \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/scim-tenants/create#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Create a new SCIM tenant associated with a specific workforce identity pool provider.

Upon successful creation, the command returns the created SCIM tenant resource.

EXAMPLES

To create a SCIM tenant with ID `my-tenant` under provider `my-okta-provider` in pool `my-pool` located in `global` with claim mappings:

```
gcloud iam workforce-pools providers scim-tenants create my-tenant --location=global --workforce-pool=my-pool --provider=my-okta-provider --claim-mapping="google.subject=user.externalId,google.group=group.externalId"
```

To create a SCIM tenant `sales-tenant` under provider `salesforce` in pool `partner-pool` located in `europe-west1` with claim mappings:

```
gcloud iam workforce-pools providers scim-tenants create sales-tenant --location=europe-west1 --workforce-pool=partner-pool --provider=salesforce --claim-mapping="google.subject=user.externalId,google.group=group.externalId"
```

POSITIONAL ARGUMENTS

Workforce pool provider scim tenant resource - The ID of the SCIM tenant to create. Must be 4-32 characters, alphanumeric (\[a-z0-9-\]), and cannot start with gcp-. The arguments in this group can be used to specify the attributes of this resource.

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

REQUIRED FLAGS

`--claim-mapping` =\[ `KEY` = `VALUE` ,…\]  
A comma-separated list of KEY=VALUE pairs defining attribute mappings.

OPTIONAL FLAGS

`--description` = `DESCRIPTION`  
Optional, user-specified description for the SCIM tenant (max 256 characters).

`--display-name` = `DISPLAY_NAME`  
Optional, user-specified display name for the SCIM tenant (max 32 characters).

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v1` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

These variants are also available:

```
gcloud alpha iam workforce-pools providers scim-tenants create
```

```
gcloud beta iam workforce-pools providers scim-tenants create
```
