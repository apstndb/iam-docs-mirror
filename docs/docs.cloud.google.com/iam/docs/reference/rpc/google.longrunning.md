---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning
title: Package google.longrunning
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  Operations  ` (interface)
  - `  GetOperationRequest  ` (message)
  - `  Operation  ` (message)

## Operations

Manages long-running operations with an API service.

When an API method normally takes long time to complete, it can be designed to return `  Operation  ` to the client, and the client can use this interface to receive the real response asynchronously by polling the operation resource, or pass the operation resource to another API (such as Pub/Sub API) to receive the response. Any API service that returns long-running operations should implement the `Operations` interface so developers can have a consistent client experience.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetOperation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetOperation(              GetOperationRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Gets the latest state of a long-running operation. Clients can use this method to poll the operation result at intervals as recommended by the API service.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## GetOperationRequest

The request message for `  Operations.GetOperation  ` .

Fields

`name`

`string`

The name of the operation resource.

## Operation

This resource represents a long-running operation that is the result of a network API call.

Fields

`name`

`string`

The server-assigned name, which is only unique within the same service that originally returns it. If you use the default HTTP mapping, the `name` should be a resource name ending with `operations/{unique_id}` .

`metadata`

`  Any  `

Service-specific metadata associated with the operation. It typically contains progress information and common metadata such as create time. Some services might not provide such metadata. Any method that returns a long-running operation should document the metadata type, if any.

`done`

`bool`

If the value is `false` , it means the operation is still in progress. If `true` , the operation is completed, and either `error` or `response` is available.

Union field `result` . The operation result, which can be either an `error` or a valid `response` . If `done` == `false` , neither `error` nor `response` is set. If `done` == `true` , exactly one of `error` or `response` can be set. Some services might not provide the result. `result` can be only one of the following:

`error`

`  Status  `

The error result of the operation in case of failure or cancellation.

`response`

`  Any  `

The normal, successful response of the operation. If the original method returns no data on success, such as `Delete` , the response is `google.protobuf.Empty` . If the original method is standard `Get` / `Create` / `Update` , the response should be the resource. For other methods, the response should have the type `XxxResponse` , where `Xxx` is the original method name. For example, if the original method name is `TakeSnapshot()` , the inferred response type is `TakeSnapshotResponse` .
