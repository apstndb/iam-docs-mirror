---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization
title: Binary Authorization roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Binary Authorization. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Binary Authorization roles

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
<td><h4 id="binaryauthorization.admin" class="role-title add-link" data-text="Binary Authorization Admin" tabindex="-1">Binary Authorization Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p>Admin role for Binary Authorization</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  update</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  update</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  replace</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.policy.get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.editor" class="role-title add-link" data-text="Binary Authorization Editor" tabindex="-1">Binary Authorization Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p>Editor role for Binary Authorization</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.  create</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  delete</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  update</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  update</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  replace</code></li>
</ul>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.viewer" class="role-title add-link" data-text="Binary Authorization Viewer" tabindex="-1">Binary Authorization Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p>Viewer role for Binary Authorization</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestorsAdmin" class="role-title add-link" data-text="Binary Authorization Attestor Admin" tabindex="-1">Binary Authorization Attestor Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p>Administrator of Binary Authorization Attestors</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  update</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.attestorsEditor" class="role-title add-link" data-text="Binary Authorization Attestor Editor" tabindex="-1">Binary Authorization Attestor Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p>Editor of Binary Authorization Attestors</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.  create</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  delete</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  update</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestorsVerifier" class="role-title add-link" data-text="Binary Authorization Attestor Image Verifier" tabindex="-1">Binary Authorization Attestor Image Verifier</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p>Caller of Binary Authorization Attestors VerifyImageAttested</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.attestorsViewer" class="role-title add-link" data-text="Binary Authorization Attestor Viewer" tabindex="-1">Binary Authorization Attestor Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.attestorsViewer</code> )</p>
<p>Viewer of Binary Authorization Attestors</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.policyAdmin" class="role-title add-link" data-text="Binary Authorization Policy Administrator" tabindex="-1">Binary Authorization Policy Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p>Administrator of Binary Authorization Policy</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  replace</code></li>
</ul>
<p><code dir="ltr" translate="no">binaryauthorization.policy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.policy.get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  policy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.policyEditor" class="role-title add-link" data-text="Binary Authorization Policy Editor" tabindex="-1">Binary Authorization Policy Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p>Editor of Binary Authorization Policy</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  update</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  create</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></li>
<li><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  replace</code></li>
</ul>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.policyEvaluator" class="role-title add-link" data-text="Binary Authorization Policy Evaluator" tabindex="-1">Binary Authorization Policy Evaluator</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p>Evaluator of Binary Authorization Policy</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.policyViewer" class="role-title add-link" data-text="Binary Authorization Policy Viewer" tabindex="-1">Binary Authorization Policy Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p>Viewer of Binary Authorization Policy</p></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="binaryauthorization.serviceAgent" class="role-title add-link" data-text="Binary Authorization Service Agent" tabindex="-1">Binary Authorization Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</p>
<p>Can read Notes and Occurrences from the Container Analysis Service to find and verify signatures.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.delete</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.get</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.update</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.notes.list</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  notes.  listOccurrences</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  get</code></p>
<p><code dir="ltr" translate="no">containeranalysis.  occurrences.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Binary Authorization permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="binaryauthorization.attestors.create" class="permission-name add-link" data-text="binaryauthorization.attestors.create" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestors.delete" class="permission-name add-link" data-text="binaryauthorization.attestors.delete" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.attestors.get" class="permission-name add-link" data-text="binaryauthorization.attestors.get" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestors.getIamPolicy" class="permission-name add-link" data-text="binaryauthorization.attestors.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.attestors.list" class="permission-name add-link" data-text="binaryauthorization.attestors.list" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestors.setIamPolicy" class="permission-name add-link" data-text="binaryauthorization.attestors.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.attestors.update" class="permission-name add-link" data-text="binaryauthorization.attestors.update" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.attestors.verifyImageAttested" class="permission-name add-link" data-text="binaryauthorization.attestors.verifyImageAttested" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  attestors.  verifyImageAttested</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.continuousValidationConfig.get" class="permission-name add-link" data-text="binaryauthorization.continuousValidationConfig.get" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.continuousValidationConfig.getIamPolicy" class="permission-name add-link" data-text="binaryauthorization.continuousValidationConfig.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.continuousValidationConfig.setIamPolicy" class="permission-name add-link" data-text="binaryauthorization.continuousValidationConfig.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.continuousValidationConfig.update" class="permission-name add-link" data-text="binaryauthorization.continuousValidationConfig.update" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  continuousValidationConfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.platformPolicies.create" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.create" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.platformPolicies.delete" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.delete" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.platformPolicies.evaluatePolicy" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.evaluatePolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.platformPolicies.get" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.get" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.platformPolicies.list" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.list" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.platformPolicies.replace" class="permission-name add-link" data-text="binaryauthorization.platformPolicies.replace" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  replace</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.policy.evaluatePolicy" class="permission-name add-link" data-text="binaryauthorization.policy.evaluatePolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.policy.get" class="permission-name add-link" data-text="binaryauthorization.policy.get" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.policy.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.policy.getIamPolicy" class="permission-name add-link" data-text="binaryauthorization.policy.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  policy.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="binaryauthorization.policy.setIamPolicy" class="permission-name add-link" data-text="binaryauthorization.policy.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  policy.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="binaryauthorization.policy.update" class="permission-name add-link" data-text="binaryauthorization.policy.update" tabindex="-1"><code dir="ltr" translate="no">binaryauthorization.  policy.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p></td>
</tr>
</tbody>
</table>
