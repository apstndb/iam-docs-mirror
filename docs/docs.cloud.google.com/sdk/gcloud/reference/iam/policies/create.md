---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create
title: gcloud iam policies create
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam policies create - create a policy on the given attachment point with the given name

SYNOPSIS

`gcloud iam policies create` [`POLICY_ID`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create#POLICY_ID) [`--attachment-point`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create#--attachment-point) = `ATTACHMENT_POINT` [`--kind`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create#--kind) = `KIND` [`--policy-file`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create#--policy-file) = `POLICY_FILE` \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Create a policy on the given attachment point with the given name.

EXAMPLES

The following command creates the IAM policy defined at the resource project `123` of kind `denypolicies` and id `my-deny-policy` from the file `policy.json` :

```
gcloud iam policies create my-deny-policy --attachment-point=cloudresourcemanager.googleapis.com/projects/123 --kind=denypolicies --policy-file=policy.json
```

POSITIONAL ARGUMENTS

`POLICY_ID`  
Policy ID that is unique for the resource to which the policy is attached.

REQUIRED FLAGS

`--attachment-point` = `ATTACHMENT_POINT`  
Resource to which the policy is attached. For valid formats, see <https://cloud.google.com/iam/help/deny/attachment-point> .

`--kind` = `KIND`  
Policy type. Use `denypolicies` for deny policies.

`--policy-file` = `POLICY_FILE`  
Path to the file that contains the policy, in JSON or YAML format. For valid syntax, see <https://cloud.google.com/iam/help/deny/policy-syntax> .

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

NOTES

These variants are also available:

```
gcloud alpha iam policies create
```

```
gcloud beta iam policies create
```
