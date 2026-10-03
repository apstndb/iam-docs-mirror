---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/simulator/replay-recent-access
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/simulator/replay-recent-access
title: gcloud iam simulator replay-recent-access
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam simulator replay-recent-access - determine affected recent access attempts before IAM policy change deployment

SYNOPSIS

`gcloud iam simulator replay-recent-access` [`RESOURCE`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/simulator/replay-recent-access#RESOURCE) [`POLICY_FILE`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/simulator/replay-recent-access#POLICY_FILE) \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/simulator/replay-recent-access#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Replay the most recent 1,000 access logs from the past 90 days using the simulated policy. For each log entry, the replay determines if setting the provided policy on the given resource would result in a change in the access state, e.g. a previously granted access becoming denied. Any differences found are returned.

EXAMPLES

To simulate a permission change of a member on a resource, run:

```
gcloud iam simulator replay-recent-access projects/project-id path/to/policy_file.json
```

See <https://cloud.google.com/iam/docs/managing-policies> for details of policy role and member types.

POSITIONAL ARGUMENTS

`RESOURCE`  
Full resource name to simulate the IAM policy for.

See: <https://cloud.google.com/apis/design/resource_names#full_resource_name> .

`POLICY_FILE`  
Path to a local JSON or YAML formatted file containing a valid policy.

The output of the `get-iam-policy` command is a valid file, as is any JSON or YAML file conforming to the structure of a Policy. See [the Policy reference](https://cloud.google.com/iam/reference/rest/v1/Policy) for details.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.
