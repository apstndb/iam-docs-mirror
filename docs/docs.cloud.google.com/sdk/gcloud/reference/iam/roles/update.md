---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update
title: gcloud iam roles update
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam roles update - update an IAM custom role

SYNOPSIS

`gcloud iam roles update` [`ROLE_ID`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#ROLE_ID) ( [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--organization) = `ORGANIZATION` \| [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--project) = `PROJECT_ID` ) \[ [`--file`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--file) = `FILE` \] \[ [`--add-permissions`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--add-permissions) = `ADD_PERMISSIONS` [`--description`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--description) = `DESCRIPTION` [`--permissions`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--permissions) = `PERMISSIONS` [`--remove-permissions`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--remove-permissions) = `REMOVE_PERMISSIONS` [`--stage`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--stage) = `STAGE` [`--title`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#--title) = `TITLE` \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/roles/update#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

This command updates an IAM custom role.

EXAMPLES

To update the role `ProjectUpdater` from a YAML file, run:

```
gcloud iam roles update ProjectUpdater --organization=123 --file=role_file_path
```

To update the role `ProjectUpdater` with flags, run:

```
gcloud iam roles update ProjectUpdater --project=myproject --permissions=permission1,permission2
```

POSITIONAL ARGUMENTS

`ROLE_ID`  
ID of the custom role to update. You must also specify the `--organization` or `--project` flag.

REQUIRED FLAGS

Exactly one of these must be specified:

`--organization` = `ORGANIZATION`  
Organization of the role you want to update.

`--project` = `PROJECT_ID`  
Project of the role you want to update.

The Google Cloud project ID to use for this invocation. If omitted, then the current project is assumed; the current project can be listed using `gcloud config list --format='text(core.project)'` and can be set using `gcloud config set project PROJECTID` .

`--project` and its fallback `core/project` property play two roles in the invocation: they specify both the project of the resource to operate on, and the project for API enablement checks, quota, and billing. To specify a different project for quota and billing, use the `--billing-project` flag or the `billing/quota_project` property.

OPTIONAL FLAGS

`--file` = `FILE`  
The YAML file you want to use to update a role. Can not be specified with other flags except role-id.

The following flags determine the fields need to be updated. You can update a role by specifying the following flags, or you can update a role from a YAML file by specifying the file flag.  
`--add-permissions` = `ADD_PERMISSIONS`  
The permissions you want to add to the role. Use commas to separate them.

`--description` = `DESCRIPTION`  
The description of the role you want to update.

`--permissions` = `PERMISSIONS`  
The permissions of the role you want to set. Use commas to separate them.

`--remove-permissions` = `REMOVE_PERMISSIONS`  
The permissions you want to remove from the role. Use commas to separate them.

`--stage` = `STAGE`  
The state of the role you want to update.

`--title` = `TITLE`  
The title of the role you want to update.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam roles update
```

```
gcloud beta iam roles update
```
