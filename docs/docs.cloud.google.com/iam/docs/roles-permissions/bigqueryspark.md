---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryspark
title: Spark connector for BigQuery roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Spark connector for BigQuery. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Spark connector for BigQuery roles

Spark connector for BigQuery offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Role</th>
<th>Permissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="bigqueryspark.serviceAgent" class="role-title add-link" data-text="BigQuery Spark Service Agent" tabindex="-1">BigQuery Spark Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  bigqueryspark.serviceAgent</code> )</p>
<p>Gives BigQuery Spark access to the service accounts in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p></td>
</tr>
</tbody>
</table>

## Spark connector for BigQuery permissions

There are no IAM permissions for this service.
