---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/generativelanguage
title: Gemini API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Gemini API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Gemini API roles

Gemini API offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="generativelanguage.serviceAgent" class="role-title add-link" data-text="Generative Language Service Agent" tabindex="-1">Generative Language Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  generativelanguage.serviceAgent</code> )</p>
<p>Grants Generative Language Service Agent permissions required to read data from GCS buckets.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
</tbody>
</table>

## Gemini API permissions

There are no IAM permissions for this service.
