---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/seclm
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/seclm
title: SecLM roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for SecLM. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## SecLM roles

SecLM offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="seclm.serviceAgent" class="role-title add-link" data-text="SecLM Service Agent" tabindex="-1">SecLM Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  seclm.serviceAgent</code> )</p>
<p>Service agent used by SecLM to access resources used by SecLM Workbenches.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.query</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  completeQuery</code></p>
<p><code dir="ltr" translate="no">discoveryengine.dataStores.get</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  dataStores.  list</code></p>
<p><code dir="ltr" translate="no">discoveryengine.  servingConfigs.  search</code></p></td>
</tr>
</tbody>
</table>

## SecLM permissions

There are no IAM permissions for this service.
