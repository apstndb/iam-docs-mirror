---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy
title: 'Method: iamPolicies.lintPolicy'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.HTTP_TEMPLATE)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.LintPolicyResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#body.aspect)
- [LintResult](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#LintResult)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#LintResult.SCHEMA_REPRESENTATION)
- [Level](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#Level)
- [Severity](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#Severity)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#try-it)

Lints, or validates, an IAM policy. Currently checks the [`google.iam.v1.Binding.condition`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/Policy#Binding.FIELDS.condition) field, which contains a condition expression for a role binding.

Successful calls to this method always return an HTTP `200 OK` status code, even if the linter detects an issue in the IAM policy.

### HTTP request

`POST https://iam.googleapis.com/v1/iamPolicies:lintPolicy`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "fullResourceName": string,

  // Union field lint_object can be only one of the following:
  "condition": {
    object (Expr)
  }
  // End of list of possible types for union field lint_object.
}
```

| Fields                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `fullResourceName`                                                                                                 | `string` The full resource name of the policy this lint request is about. The name follows the Google Cloud format for full resource names. For example, a Google Cloud project with ID `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` . The resource name is not used to read a policy from IAM. Only the data in the request object is linted. |
| Union field `lint_object` . Required. The IAM object to be linted. `lint_object` can be only one of the following: |                                                                                                                                                                                                                                                                                                                                                                                          |
| `condition`                                                                                                        | `object ( `[`Expr`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Expr)` )` [`google.iam.v1.Binding.condition`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/Policy#Binding.FIELDS.condition) object to be linted.                                                                                                                                      |

### Response body

The response of a lint operation. An empty response indicates the operation was able to fully execute and no lint issue was found.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "lintResults": [
    {
      object (LintResult)
    }
  ]
}
```

| Fields          |                                                                                                                                                                                          |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `lintResults[]` | `object ( `[`LintResult`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#LintResult)` )` List of lint results sorted by `severity` in descending order. |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## LintResult

Structured response of a single validation unit.

**JSON representation**

```
{
  "level": enum (Level),
  "validationUnitName": string,
  "severity": enum (Severity),
  "fieldName": string,
  "locationOffset": integer,
  "debugMessage": string
}
```

| Fields               |                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `level`              | `enum ( `[`Level`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#Level)` )` The validation unit level.                                                                                                                                                                                                                                                 |
| `validationUnitName` | `string` The validation unit name, for instance "lintValidationUnits/ConditionComplexityCheck".                                                                                                                                                                                                                                                                                          |
| `severity`           | `enum ( `[`Severity`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/iamPolicies/lintPolicy#Severity)` )` The validation unit severity.                                                                                                                                                                                                                                        |
| `fieldName`          | `string` The name of the field for which this lint result is about. For nested messages `fieldName` consists of names of the embedded fields separated by period character. The top-level qualifier is the input object to lint in the request. For example, the `fieldName` value `condition.expression` identifies a lint result for the `expression` field of the provided condition. |
| `locationOffset`     | `integer` 0-based character position of problematic construct within the object identified by `fieldName` . Currently, this is populated only for condition expression.                                                                                                                                                                                                                  |
| `debugMessage`       | `string` Human readable debug message associated with the issue.                                                                                                                                                                                                                                                                                                                         |

## Level

Possible Level values of a validation unit corresponding to its domain of discourse.

| Enums               |                                                                               |
|---------------------|-------------------------------------------------------------------------------|
| `LEVEL_UNSPECIFIED` | Level is unspecified.                                                         |
| `CONDITION`         | A validation unit which operates on an individual condition within a binding. |

## Severity

Possible Severity values of an issued result.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Enums</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>SEVERITY_UNSPECIFIED</code></td>
<td>Severity is unspecified.</td>
</tr>
<tr class="even">
<td><code>ERROR</code></td>
<td>A validation unit returns an error only for critical issues. If an attempt is made to set the problematic policy without rectifying the critical issue, it causes the <code>setPolicy</code> operation to fail.</td>
</tr>
<tr class="odd">
<td><code>WARNING</code></td>
<td><p>Any issue which is severe enough but does not cause an error. For example, suspicious constructs in the input object will not necessarily fail <code>setPolicy</code> , but there is a high likelihood that they won't behave as expected during policy evaluation in <code>checkPolicy</code> . This includes the following common scenarios:</p>
<ul>
<li>Unsatisfiable condition: Expired timestamp in date/time condition.</li>
<li>Ineffective condition: Condition on a &lt;principal, role&gt; pair which is granted unconditionally in another binding of the same policy.</li>
</ul></td>
</tr>
<tr class="even">
<td><code>NOTICE</code></td>
<td>Reserved for the issues that are not severe as <code>ERROR</code> / <code>WARNING</code> , but need special handling. For instance, messages about skipped validation units are issued as <code>NOTICE</code> .</td>
</tr>
<tr class="odd">
<td><code>INFO</code></td>
<td>Any informative statement which is not severe enough to raise <code>ERROR</code> / <code>WARNING</code> / <code>NOTICE</code> , like auto-correction recommendations on the input content. Note that current version of the linter does not utilize <code>INFO</code> .</td>
</tr>
<tr class="even">
<td><code>DEPRECATED</code></td>
<td>Deprecated severity level.</td>
</tr>
</tbody>
</table>
