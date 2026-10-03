---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete
title: gcloud iam roles delete
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam roles delete - delete a custom role from an organization or a project

SYNOPSIS

`gcloud iam roles delete` [`ROLE_ID`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete#ROLE_ID) ( [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete#--organization) = `ORGANIZATION` \| [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete#--project) = `PROJECT_ID` ) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/delete#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

This command deletes a role.

This command can fail for the following reasons:

- The role specified does not exist.
- The active user does not have permission to access the given role.

EXAMPLES

To delete the role `ProjectUpdater` of the organization `1234567` , run:

```
gcloud iam roles delete ProjectUpdater --organization=1234567
```

To delete the role `ProjectUpdater` of the project `myproject` , run:

```
gcloud iam roles delete ProjectUpdater --project=myproject
```

POSITIONAL ARGUMENTS

`ROLE_ID`  
ID of the custom role to delete. You must also specify the `--organization` or `--project` flag.

REQUIRED FLAGS

Exactly one of these must be specified:

`--organization` = `ORGANIZATION`  
Organization of the role you want to delete.

`--project` = `PROJECT_ID`  
Project of the role you want to delete.

The Google Cloud project ID to use for this invocation. If omitted, then the current project is assumed; the current project can be listed using `gcloud config list --format='text(core.project)'` and can be set using `gcloud config set project PROJECTID` .

`--project` and its fallback `core/project` property play two roles in the invocation: they specify both the project of the resource to operate on, and the project for API enablement checks, quota, and billing. To specify a different project for quota and billing, use the `--billing-project` flag or the `billing/quota_project` property.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam roles delete
```

```
gcloud beta iam roles delete
```
