---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete
title: gcloud iam access-policies delete
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam access-policies delete - delete AccessPolicy instance

SYNOPSIS

`gcloud iam access-policies delete` ( [`ACCESS_POLICY`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#ACCESS_POLICY) : [`--folder`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--folder) = `FOLDER` [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--location) = `LOCATION` [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--organization) = `ORGANIZATION` ) \[ [`--async`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--async) \] \[ [`--etag`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--etag) = `ETAG` \] \[ [`--force`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--force) \] \[ [`--validate-only`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#--validate-only) \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Delete AccessPolicy instance.

EXAMPLES

To delete `my-policy` instance, run:

```
gcloud iam access-policies delete my-policy
```

POSITIONAL ARGUMENTS

AccessPolicy resource - The name of the access policy to delete.

Format: `projects/{project_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_number}/locations/{location}/accessPolicies/{access_policy_id}` `folders/{folder_id}/locations/{location}/accessPolicies/{access_policy_id}` `organizations/{organization_id}/locations/{location}/accessPolicies/{access_policy_id}` The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

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

FLAGS

`--async`  
Return immediately, without waiting for the operation in progress to complete.

`--etag` = `ETAG`  
The etag of the access policy. If this is provided, it must match the server's etag.

`--force`  
If set to true, the request will force the deletion of the Policy even if the Policy references PolicyBindings.

`--validate-only`  
If set, validate the request and preview the deletion, but do not actually post it.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v3` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

This variant is also available:

```
gcloud beta iam access-policies delete
```
