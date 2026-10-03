---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create
title: gcloud iam principal-access-boundary-policies create
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam principal-access-boundary-policies create - create PrincipalAccessBoundaryPolicy instance

SYNOPSIS

`gcloud iam principal-access-boundary-policies create` ( [`PRINCIPAL_ACCESS_BOUNDARY_POLICY`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#PRINCIPAL_ACCESS_BOUNDARY_POLICY) : [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--location) = `LOCATION` [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--organization) = `ORGANIZATION` ) \[ [`--annotations`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--annotations) =\[ `ANNOTATIONS` , …\]\] \[ [`--async`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--async) \] \[ [`--display-name`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--display-name) = `DISPLAY_NAME` \] \[ [`--etag`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--etag) = `ETAG` \] \[\[ [`--details-rules`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--details-rules) =\[ `description` = `DESCRIPTION` \], \[ `effect` = `EFFECT` \], \[ `resources` = `RESOURCES` \] : [`--details-enforcement-version`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#--details-enforcement-version) = `DETAILS_ENFORCEMENT_VERSION` \]\] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/principal-access-boundary-policies/create#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Create PrincipalAccessBoundaryPolicy instance.

EXAMPLES

To create a policy instance called `my-policy` , run:

```
gcloud iam principal-access-boundary-policies create my-policy --organization=123 --location=global
```

POSITIONAL ARGUMENTS

PrincipalAccessBoundaryPolicy resource - Identifier. The resource name of the principal access boundary policy.

The following format is supported: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{policy_id}` The arguments in this group can be used to specify the attributes of this resource.

This must be specified.

`PRINCIPAL_ACCESS_BOUNDARY_POLICY`  
ID of the principalAccessBoundaryPolicy or fully qualified identifier for the principalAccessBoundaryPolicy.

To set the `principal_access_boundary_policy` attribute:

- provide the argument `principal_access_boundary_policy` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--location` = `LOCATION`  
The location id of the principalAccessBoundaryPolicy resource.

To set the `location` attribute:

- provide the argument `principal_access_boundary_policy` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--organization` = `ORGANIZATION`  
The organization id of the principalAccessBoundaryPolicy resource.

To set the `organization` attribute:

- provide the argument `principal_access_boundary_policy` on the command line with a fully specified name;
- provide the argument `--organization` on the command line.

FLAGS

`--annotations` =\[ `ANNOTATIONS` ,…\]  
User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations.

`KEY`  
Sets `KEY` value.

`VALUE`  
Sets `VALUE` value.

`Shorthand Example:`

```
--annotations=string=string
```

`JSON Example:`

```
--annotations='{"string": "string"}'
```

`File Example:`

```
--annotations=path_to_file.(yaml|json)
```

`--async`  
Return immediately, without waiting for the operation in progress to complete.

`--display-name` = `DISPLAY_NAME`  
The description of the principal access boundary policy. Must be less than or equal to 63 characters.

`--etag` = `ETAG`  
The etag for the principal access boundary. If this is provided on update, it must match the server's etag.

Principal access boundary policy details  
`--details-rules` =\[ `description` = `DESCRIPTION` \],\[ `effect` = `EFFECT` \],\[ `resources` = `RESOURCES` \]  
Required, A list of principal access boundary policy rules. The number of rules in a policy is limited to 500.

`description`  
The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.

`effect`  
The access relationship of principals to the resources in this rule.

`resources`  
A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.

The following resource types are supported:

- Organizations, such as `//cloudresourcemanager.googleapis.com/organizations/123` .
- Folders, such as `//cloudresourcemanager.googleapis.com/folders/123` .
- Projects, such as `//cloudresourcemanager.googleapis.com/projects/123` or `//cloudresourcemanager.googleapis.com/projects/my-project-id` .

`Shorthand Example:`

```
--details-rules=description=string,effect=string,resources=[string] --details-rules=description=string,effect=string,resources=[string]
```

`JSON Example:`

```
--details-rules='[{"description": "string", "effect": "string", "resources": ["string"]}]'
```

`File Example:`

```
--details-rules=path_to_file.(yaml|json)
```

This flag argument must be specified if any of the other arguments in this group are specified.

`--details-enforcement-version` = `DETAILS_ENFORCEMENT_VERSION`  
The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v3` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

This variant is also available:

```
gcloud beta iam principal-access-boundary-policies create
```
