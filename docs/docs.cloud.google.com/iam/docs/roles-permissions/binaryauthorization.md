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
<td>Binary Authorization Admin
<p>( <code>roles/ binaryauthorization.admin</code> )</p>
<p>Admin role for Binary Authorization</p></td>
<td><p><code>binaryauthorization.*</code></p>
<ul>
<li><code>binaryauthorization. attestors. create</code></li>
<li><code>binaryauthorization. attestors. delete</code></li>
<li><code>binaryauthorization. attestors. get</code></li>
<li><code>binaryauthorization. attestors. getIamPolicy</code></li>
<li><code>binaryauthorization. attestors. list</code></li>
<li><code>binaryauthorization. attestors. setIamPolicy</code></li>
<li><code>binaryauthorization. attestors. update</code></li>
<li><code>binaryauthorization. attestors. verifyImageAttested</code></li>
<li><code>binaryauthorization. continuousValidationConfig. get</code></li>
<li><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></li>
<li><code>binaryauthorization. continuousValidationConfig. setIamPolicy</code></li>
<li><code>binaryauthorization. continuousValidationConfig. update</code></li>
<li><code>binaryauthorization. platformPolicies. create</code></li>
<li><code>binaryauthorization. platformPolicies. delete</code></li>
<li><code>binaryauthorization. platformPolicies. evaluatePolicy</code></li>
<li><code>binaryauthorization. platformPolicies. get</code></li>
<li><code>binaryauthorization. platformPolicies. list</code></li>
<li><code>binaryauthorization. platformPolicies. replace</code></li>
<li><code>binaryauthorization. policy. evaluatePolicy</code></li>
<li><code>binaryauthorization.policy.get</code></li>
<li><code>binaryauthorization. policy. getIamPolicy</code></li>
<li><code>binaryauthorization. policy. setIamPolicy</code></li>
<li><code>binaryauthorization. policy. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Binary Authorization Editor
<p>( <code>roles/ binaryauthorization.editor</code> )</p>
<p>Editor role for Binary Authorization</p></td>
<td><p><code>binaryauthorization. attestors. create</code></p>
<p><code>binaryauthorization. attestors. delete</code></p>
<p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. getIamPolicy</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. update</code></p>
<p><code>binaryauthorization. attestors. verifyImageAttested</code></p>
<p><code>binaryauthorization. continuousValidationConfig. get</code></p>
<p><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></p>
<p><code>binaryauthorization. continuousValidationConfig. update</code></p>
<p><code>binaryauthorization. platformPolicies.*</code></p>
<ul>
<li><code>binaryauthorization. platformPolicies. create</code></li>
<li><code>binaryauthorization. platformPolicies. delete</code></li>
<li><code>binaryauthorization. platformPolicies. evaluatePolicy</code></li>
<li><code>binaryauthorization. platformPolicies. get</code></li>
<li><code>binaryauthorization. platformPolicies. list</code></li>
<li><code>binaryauthorization. platformPolicies. replace</code></li>
</ul>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>binaryauthorization. policy. getIamPolicy</code></p>
<p><code>binaryauthorization. policy. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Viewer
<p>( <code>roles/ binaryauthorization.viewer</code> )</p>
<p>Viewer role for Binary Authorization</p></td>
<td><p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. getIamPolicy</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. verifyImageAttested</code></p>
<p><code>binaryauthorization. continuousValidationConfig. get</code></p>
<p><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></p>
<p><code>binaryauthorization. platformPolicies. evaluatePolicy</code></p>
<p><code>binaryauthorization. platformPolicies. get</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>binaryauthorization. policy. getIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Binary Authorization Attestor Admin
<p>( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p>Administrator of Binary Authorization Attestors</p></td>
<td><p><code>binaryauthorization. attestors.*</code></p>
<ul>
<li><code>binaryauthorization. attestors. create</code></li>
<li><code>binaryauthorization. attestors. delete</code></li>
<li><code>binaryauthorization. attestors. get</code></li>
<li><code>binaryauthorization. attestors. getIamPolicy</code></li>
<li><code>binaryauthorization. attestors. list</code></li>
<li><code>binaryauthorization. attestors. setIamPolicy</code></li>
<li><code>binaryauthorization. attestors. update</code></li>
<li><code>binaryauthorization. attestors. verifyImageAttested</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Attestor Editor
<p>( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p>Editor of Binary Authorization Attestors</p></td>
<td><p><code>binaryauthorization. attestors. create</code></p>
<p><code>binaryauthorization. attestors. delete</code></p>
<p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. update</code></p>
<p><code>binaryauthorization. attestors. verifyImageAttested</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Binary Authorization Attestor Image Verifier
<p>( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p>Caller of Binary Authorization Attestors VerifyImageAttested</p></td>
<td><p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. verifyImageAttested</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Attestor Viewer
<p>( <code>roles/ binaryauthorization.attestorsViewer</code> )</p>
<p>Viewer of Binary Authorization Attestors</p></td>
<td><p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Binary Authorization Policy Administrator
<p>( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p>Administrator of Binary Authorization Policy</p></td>
<td><p><code>binaryauthorization. continuousValidationConfig.*</code></p>
<ul>
<li><code>binaryauthorization. continuousValidationConfig. get</code></li>
<li><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></li>
<li><code>binaryauthorization. continuousValidationConfig. setIamPolicy</code></li>
<li><code>binaryauthorization. continuousValidationConfig. update</code></li>
</ul>
<p><code>binaryauthorization. platformPolicies.*</code></p>
<ul>
<li><code>binaryauthorization. platformPolicies. create</code></li>
<li><code>binaryauthorization. platformPolicies. delete</code></li>
<li><code>binaryauthorization. platformPolicies. evaluatePolicy</code></li>
<li><code>binaryauthorization. platformPolicies. get</code></li>
<li><code>binaryauthorization. platformPolicies. list</code></li>
<li><code>binaryauthorization. platformPolicies. replace</code></li>
</ul>
<p><code>binaryauthorization.policy.*</code></p>
<ul>
<li><code>binaryauthorization. policy. evaluatePolicy</code></li>
<li><code>binaryauthorization.policy.get</code></li>
<li><code>binaryauthorization. policy. getIamPolicy</code></li>
<li><code>binaryauthorization. policy. setIamPolicy</code></li>
<li><code>binaryauthorization. policy. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Policy Editor
<p>( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p>Editor of Binary Authorization Policy</p></td>
<td><p><code>binaryauthorization. continuousValidationConfig. get</code></p>
<p><code>binaryauthorization. continuousValidationConfig. update</code></p>
<p><code>binaryauthorization. platformPolicies.*</code></p>
<ul>
<li><code>binaryauthorization. platformPolicies. create</code></li>
<li><code>binaryauthorization. platformPolicies. delete</code></li>
<li><code>binaryauthorization. platformPolicies. evaluatePolicy</code></li>
<li><code>binaryauthorization. platformPolicies. get</code></li>
<li><code>binaryauthorization. platformPolicies. list</code></li>
<li><code>binaryauthorization. platformPolicies. replace</code></li>
</ul>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>binaryauthorization. policy. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Binary Authorization Policy Evaluator
<p>( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p>Evaluator of Binary Authorization Policy</p></td>
<td><p><code>binaryauthorization. platformPolicies. evaluatePolicy</code></p>
<p><code>binaryauthorization. platformPolicies. get</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Binary Authorization Policy Viewer
<p>( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p>Viewer of Binary Authorization Policy</p></td>
<td><p><code>binaryauthorization. continuousValidationConfig. get</code></p>
<p><code>binaryauthorization. platformPolicies. get</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Binary Authorization Service Agent
<p>( <code>roles/ binaryauthorization.serviceAgent</code> )</p>
<p>Can read Notes and Occurrences from the Container Analysis Service to find and verify signatures.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. dockerimages. get</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>binaryauthorization. attestors. get</code></p>
<p><code>binaryauthorization. attestors. list</code></p>
<p><code>binaryauthorization. attestors. verifyImageAttested</code></p>
<p><code>binaryauthorization. platformPolicies. evaluatePolicy</code></p>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.feeds.create</code></p>
<p><code>cloudasset.feeds.delete</code></p>
<p><code>cloudasset.feeds.get</code></p>
<p><code>cloudasset.feeds.update</code></p>
<p><code>containeranalysis.notes.get</code></p>
<p><code>containeranalysis.notes.list</code></p>
<p><code>containeranalysis. notes. listOccurrences</code></p>
<p><code>containeranalysis. occurrences. get</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.objects.list</code></p></td>
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
<td><code>binaryauthorization. attestors. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. attestors. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. attestors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code>roles/ binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. attestors. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. attestors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code>roles/ binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. attestors. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. attestors. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. attestors. verifyImageAttested</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. continuousValidationConfig. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. continuousValidationConfig. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. continuousValidationConfig. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. continuousValidationConfig. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. platformPolicies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. platformPolicies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. platformPolicies. evaluatePolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. platformPolicies. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. platformPolicies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. platformPolicies. replace</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. policy. evaluatePolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>binaryauthorization.policy.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. policy. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>binaryauthorization. policy. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p></td>
</tr>
<tr class="odd">
<td><code>binaryauthorization. policy. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
