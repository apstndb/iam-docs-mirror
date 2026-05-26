---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise
title: reCAPTCHA roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for reCAPTCHA. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## reCAPTCHA roles

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
<td><h4 id="recaptchaenterprise.admin" class="role-title add-link" data-text="reCAPTCHA Enterprise Admin" tabindex="-1">reCAPTCHA Enterprise Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p>Access to view and modify reCAPTCHA Enterprise keys</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  create</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  delete</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  get</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  create</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  delete</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  retrievelegacysecretkey</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  keys.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.  metrics.  get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  get</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.editor" class="role-title add-link" data-text="Recaptchaenterprise Editor" tabindex="-1">Recaptchaenterprise Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p>Editor role for recaptchaenterprise</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  assessments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  annotate</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  create</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  create</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  delete</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  get</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  create</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  delete</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  retrievelegacysecretkey</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  update</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  metrics.  get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  get</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroupmemberships.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroups.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.viewer" class="role-title add-link" data-text="reCAPTCHA Enterprise Viewer" tabindex="-1">reCAPTCHA Enterprise Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p>Access to view reCAPTCHA Enterprise keys and metrics</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  metrics.  get</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.agent" class="role-title add-link" data-text="reCAPTCHA Enterprise Agent" tabindex="-1">reCAPTCHA Enterprise Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p>
<p>Access to create and annotate reCAPTCHA Enterprise assessments</p></td>
<td><p><code dir="ltr" translate="no">recaptchaenterprise.  assessments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  annotate</code></li>
<li><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  create</code></li>
</ul>
<p><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroupmemberships.  list</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroups.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## reCAPTCHA permissions

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
<td><h4 id="recaptchaenterprise.assessments.annotate" class="permission-name add-link" data-text="recaptchaenterprise.assessments.annotate" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  annotate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappcheck#firebaseappcheck.serviceAgent">Firebase App Check Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappcheck.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.assessments.create" class="permission-name add-link" data-text="recaptchaenterprise.assessments.create" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappcheck#firebaseappcheck.serviceAgent">Firebase App Check Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseappcheck.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.firewallpolicies.create" class="permission-name add-link" data-text="recaptchaenterprise.firewallpolicies.create" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.firewallpolicies.delete" class="permission-name add-link" data-text="recaptchaenterprise.firewallpolicies.delete" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.firewallpolicies.get" class="permission-name add-link" data-text="recaptchaenterprise.firewallpolicies.get" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.firewallpolicies.list" class="permission-name add-link" data-text="recaptchaenterprise.firewallpolicies.list" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.firewallpolicies.update" class="permission-name add-link" data-text="recaptchaenterprise.firewallpolicies.update" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  firewallpolicies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.keys.create" class="permission-name add-link" data-text="recaptchaenterprise.keys.create" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.keys.createTagBinding" class="permission-name add-link" data-text="recaptchaenterprise.keys.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.keys.delete" class="permission-name add-link" data-text="recaptchaenterprise.keys.delete" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.keys.deleteTagBinding" class="permission-name add-link" data-text="recaptchaenterprise.keys.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.keys.get" class="permission-name add-link" data-text="recaptchaenterprise.keys.get" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.serviceAgent">Identity Platform Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.keys.list" class="permission-name add-link" data-text="recaptchaenterprise.keys.list" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.keys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.keys.listEffectiveTags" class="permission-name add-link" data-text="recaptchaenterprise.keys.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.keys.listTagBindings" class="permission-name add-link" data-text="recaptchaenterprise.keys.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.keys.retrievelegacysecretkey" class="permission-name add-link" data-text="recaptchaenterprise.keys.retrievelegacysecretkey" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  retrievelegacysecretkey</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.keys.update" class="permission-name add-link" data-text="recaptchaenterprise.keys.update" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  keys.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.metrics.get" class="permission-name add-link" data-text="recaptchaenterprise.metrics.get" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  metrics.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.projectmetadata.get" class="permission-name add-link" data-text="recaptchaenterprise.projectmetadata.get" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.projectmetadata.update" class="permission-name add-link" data-text="recaptchaenterprise.projectmetadata.update" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  projectmetadata.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="recaptchaenterprise.relatedaccountgroupmemberships.list" class="permission-name add-link" data-text="recaptchaenterprise.relatedaccountgroupmemberships.list" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroupmemberships.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="recaptchaenterprise.relatedaccountgroups.list" class="permission-name add-link" data-text="recaptchaenterprise.relatedaccountgroups.list" tabindex="-1"><code dir="ltr" translate="no">recaptchaenterprise.  relatedaccountgroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recaptchaenterprise.agent</code> )</p></td>
</tr>
</tbody>
</table>
