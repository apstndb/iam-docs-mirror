---
name: documents/docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update
uri: https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update
title: gcloud iam policy-bindings update
description: Offers tools and libraries that allow you to create and manage resources across Google Cloud.
data_source: docs.cloud.google.com
---

NAME

gcloud iam policy-bindings update - update PolicyBinding instance

SYNOPSIS

`gcloud iam policy-bindings update` ( [`POLICY_BINDING`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#POLICY_BINDING) : [`--folder`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--folder) = `FOLDER` [`--location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--location) = `LOCATION` [`--organization`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--organization) = `ORGANIZATION` ) \[ [`--async`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--async) \] \[ [`--display-name`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--display-name) = `DISPLAY_NAME` \] \[ [`--etag`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--etag) = `ETAG` \] \[ [`--annotations`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--annotations) =\[ `ANNOTATIONS` , …\] \| [`--update-annotations`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--update-annotations) =\[ `UPDATE_ANNOTATIONS` , …\] [`--clear-annotations`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--clear-annotations) \| [`--remove-annotations`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--remove-annotations) = `REMOVE_ANNOTATIONS` \] \[ [`--clear-condition`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--clear-condition) [`--condition-description`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--condition-description) = `CONDITION_DESCRIPTION` [`--condition-expression`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--condition-expression) = `CONDITION_EXPRESSION` [`--condition-location`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--condition-location) = `CONDITION_LOCATION` [`--condition-title`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#--condition-title) = `CONDITION_TITLE` \] \[ [`GCLOUD_WIDE_FLAG`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/update#GCLOUD-WIDE-FLAGS)` …` \]

DESCRIPTION

Update PolicyBinding instance.

EXAMPLES

To update display name of `my-binding` in organization `123` run:

```
gcloud iam policy-bindings update my-binding --organization=123 --location=global --display-name=new-display-name
```

POSITIONAL ARGUMENTS

PolicyBinding resource - Identifier. The name of the policy binding, in the format `{binding_parent/locations/{location}/policyBindings/{policy_binding_id}` . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.

Format:

- `projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}`
- `projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}`
- `folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}`
- `organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}` The arguments in this group can be used to specify the attributes of this resource. (NOTE) Some attributes are not given arguments in this group but can be set in other ways.

To set the `project` attribute:

- provide the argument `policy_binding` on the command line with a fully specified name;
- provide the argument `--project` on the command line;
- set the property `core/project` . This resource can be one of the following types: \[iam.folders.locations.policyBindings, iam.organizations.locations.policyBindings, iam.projects.locations.policyBindings\].

This must be specified.

`POLICY_BINDING`  
ID of the policyBinding or fully qualified identifier for the policyBinding.

To set the `policy_binding` attribute:

- provide the argument `policy_binding` on the command line.

This positional argument must be specified if any of the other arguments in this group are specified.

`--folder` = `FOLDER`  
The folder id of the policyBinding resource.

To set the `folder` attribute:

- provide the argument `policy_binding` on the command line with a fully specified name;
- provide the argument `--folder` on the command line. Must be specified for resource of type \[iam.folders.locations.policyBindings\].

`--location` = `LOCATION`  
The location id of the policyBinding resource.

To set the `location` attribute:

- provide the argument `policy_binding` on the command line with a fully specified name;
- provide the argument `--location` on the command line.

`--organization` = `ORGANIZATION`  
The organization id of the policyBinding resource.

To set the `organization` attribute:

- provide the argument `policy_binding` on the command line with a fully specified name;
- provide the argument `--organization` on the command line. Must be specified for resource of type \[iam.organizations.locations.policyBindings\].

FLAGS

`--async`

Return immediately, without waiting for the operation in progress to complete.

`--display-name` = `DISPLAY_NAME`

The description of the policy binding. Must be less than or equal to 63 characters.

`--etag` = `ETAG`

The etag for the policy binding. If this is provided on update, it must match the server's etag.

Update annotations.

At most one of these can be specified:

`--annotations` =\[ `ANNOTATIONS` ,…\]

Set annotations to new value. User-defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations.

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

Or at least one of these can be specified:

`--update-annotations` =\[ `UPDATE_ANNOTATIONS` ,…\]

Update annotations value or add key value pair. User-defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations.

`KEY`  
Sets `KEY` value.

`VALUE`  
Sets `VALUE` value.

`Shorthand Example:`

```
--update-annotations=string=string
```

`JSON Example:`

```
--update-annotations='{"string": "string"}'
```

`File Example:`

```
--update-annotations=path_to_file.(yaml|json)
```

At most one of these can be specified:

`--clear-annotations`  
Clear annotations value and set to empty map.

`--remove-annotations` = `REMOVE_ANNOTATIONS`  
Remove existing value from map annotations. Sets `remove_annotations` value. `Shorthand Example:`

```
--remove-annotations=string,string
```

`JSON Example:`

```
--remove-annotations=["string"]
```

`File Example:`

```
--remove-annotations=path_to_file.(yaml|json)
```

Represents a textual expression in the Common Expression Language (CEL) syntax. CEL is a C-like expression language. The syntax and semantics of CEL are documented at <https://github.com/google/cel-spec> .

Example (Comparison):

```
title: "Summary size limit"
description: "Determines if a summary is less than 100 chars"
expression: "document.summary.size() < 100"
```

Example (Equality):

```
title: "Requestor is owner"
description: "Determines if requestor is the document owner"
expression: "document.owner == request.auth.claims.email"
```

Example (Logic):

```
title: "Public documents"
description: "Determine whether the document should be publicly visible"
expression: "document.type != 'private' && document.type != 'internal'"
```

Example (Data Manipulation):

```
title: "Notification string"
description: "Create a notification string with a timestamp."
expression: "'New message received at ' + string(document.create_time)"
```

The exact variables and functions that may be referenced within an expression are determined by the service that evaluates it. See the service documentation for additional information.

`--clear-condition`

Set googleIamV3PolicyBinding.condition back to default value.

`--condition-description` = `CONDITION_DESCRIPTION`

Description of the expression. This is a longer text which describes the expression, e.g. when hovered over it in a UI.

`--condition-expression` = `CONDITION_EXPRESSION`

Textual representation of an expression in Common Expression Language syntax.

`--condition-location` = `CONDITION_LOCATION`

String indicating the location of the expression for error reporting, e.g. a file name and a position in the file.

`--condition-title` = `CONDITION_TITLE`

Title for the expression, i.e. a short string describing its purpose. This can be used e.g. in UIs which allow to enter the expression.

GCLOUD WIDE FLAGS

These flags are available to all commands: [`--access-token-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--access-token-file) , [`--account`](https://docs.cloud.google.com/sdk/gcloud/reference#--account) , [`--billing-project`](https://docs.cloud.google.com/sdk/gcloud/reference#--billing-project) , [`--configuration`](https://docs.cloud.google.com/sdk/gcloud/reference#--configuration) , [`--flags-file`](https://docs.cloud.google.com/sdk/gcloud/reference#--flags-file) , [`--flatten`](https://docs.cloud.google.com/sdk/gcloud/reference#--flatten) , [`--format`](https://docs.cloud.google.com/sdk/gcloud/reference#--format) , [`--help`](https://docs.cloud.google.com/sdk/gcloud/reference#--help) , [`--impersonate-service-account`](https://docs.cloud.google.com/sdk/gcloud/reference#--impersonate-service-account) , [`--log-http`](https://docs.cloud.google.com/sdk/gcloud/reference#--log-http) , [`--project`](https://docs.cloud.google.com/sdk/gcloud/reference#--project) , [`--quiet`](https://docs.cloud.google.com/sdk/gcloud/reference#--quiet) , [`--trace-token`](https://docs.cloud.google.com/sdk/gcloud/reference#--trace-token) , [`--user-output-enabled`](https://docs.cloud.google.com/sdk/gcloud/reference#--user-output-enabled) , [`--verbosity`](https://docs.cloud.google.com/sdk/gcloud/reference#--verbosity) .

Run `$ `[`gcloud help`](https://docs.cloud.google.com/sdk/gcloud/reference) for details.

API REFERENCE

This command uses the `iam/v3` API. The full documentation for this API can be found at: <https://cloud.google.com/iam/>

NOTES

This variant is also available:

```
gcloud beta iam policy-bindings update
```
