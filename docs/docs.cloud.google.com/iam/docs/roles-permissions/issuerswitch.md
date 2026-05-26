---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch
title: Payment Gateway issuer switch roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Payment Gateway issuer switch. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Payment Gateway issuer switch roles

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
<td><h4 id="issuerswitch.admin" class="role-title add-link" data-text="Issuerswitch Admin Beta" tabindex="-1">Issuerswitch Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p>Access to all issuer switch roles</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  update</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.complaints.create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  complaints.  resolve</code></li>
<li><code dir="ltr" translate="no">issuerswitch.disputes.create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.disputes.resolve</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  get</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  update</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  get</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  update</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.operations.cancel</code></li>
<li><code dir="ltr" translate="no">issuerswitch.operations.delete</code></li>
<li><code dir="ltr" translate="no">issuerswitch.operations.get</code></li>
<li><code dir="ltr" translate="no">issuerswitch.operations.list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.operations.wait</code></li>
<li><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  delete</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.rules.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.viewer" class="role-title add-link" data-text="Issuerswitch Viewer Beta" tabindex="-1">Issuerswitch Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p>Viewer role for issuerswitch</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.wait</code></p>
<p><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.rules.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.accountManagerAdmin" class="role-title add-link" data-text="Issuerswitch Account Manager Admin Beta" tabindex="-1">Issuerswitch Account Manager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p>This role can perform all account manager related operations</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.managedAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  get</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.accountManagerTransactionsAdmin" class="role-title add-link" data-text="Issuerswitch Account Manager Transactions Admin Beta" tabindex="-1">Issuerswitch Account Manager Transactions Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p>This role can perform all account manager transactions related operations</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.accountManagerTransactionsViewer" class="role-title add-link" data-text="Issuerswitch Account Manager Transactions Viewer Beta" tabindex="-1">Issuerswitch Account Manager Transactions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p>This role can view all account manager transactions</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.issuerParticipantsAdmin" class="role-title add-link" data-text="Issuerswitch Participants Admin Beta" tabindex="-1">Issuerswitch Participants Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.issuerParticipantsAdmin</code> )</p>
<p>Full access to issuer switch participants</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  get</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.resolutionsAdmin" class="role-title add-link" data-text="Issuerswitch Resolutions Admin Beta" tabindex="-1">Issuerswitch Resolutions Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p>
<p>Full access to issuer switch resolutions</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.complaints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.complaints.create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  complaints.  resolve</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.disputes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.disputes.create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.disputes.resolve</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.rulesAdmin" class="role-title add-link" data-text="Issuerswitch Rules Admin Beta" tabindex="-1">Issuerswitch Rules Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p>Full access to issuer switch rules</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  create</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  delete</code></li>
<li><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">issuerswitch.rules.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.rulesViewer" class="role-title add-link" data-text="Issuerswitch Rules Viewer Beta" tabindex="-1">Issuerswitch Rules Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p>
<p>This role can view rules and related metadata.</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.rules.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.transactionsViewer" class="role-title add-link" data-text="Issuerswitch Transactions Viewer Beta" tabindex="-1">Issuerswitch Transactions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p>
<p>This role can view all transactions</p></td>
<td><p><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.get</code></p>
<p><code dir="ltr" translate="no">issuerswitch.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Payment Gateway issuer switch permissions

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
<td><h4 id="issuerswitch.accountManagerTransactions.list" class="permission-name add-link" data-text="issuerswitch.accountManagerTransactions.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.accountManagerTransactions.update" class="permission-name add-link" data-text="issuerswitch.accountManagerTransactions.update" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  accountManagerTransactions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.complaintTransactions.list" class="permission-name add-link" data-text="issuerswitch.complaintTransactions.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  complaintTransactions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.complaints.create" class="permission-name add-link" data-text="issuerswitch.complaints.create" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.complaints.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.complaints.resolve" class="permission-name add-link" data-text="issuerswitch.complaints.resolve" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  complaints.  resolve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.disputes.create" class="permission-name add-link" data-text="issuerswitch.disputes.create" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.disputes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.disputes.resolve" class="permission-name add-link" data-text="issuerswitch.disputes.resolve" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.disputes.resolve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.financialTransactions.list" class="permission-name add-link" data-text="issuerswitch.financialTransactions.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  financialTransactions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.issuerParticipants.get" class="permission-name add-link" data-text="issuerswitch.issuerParticipants.get" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.issuerParticipantsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.issuerParticipants.update" class="permission-name add-link" data-text="issuerswitch.issuerParticipants.update" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  issuerParticipants.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.issuerParticipantsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.managedAccounts.get" class="permission-name add-link" data-text="issuerswitch.managedAccounts.get" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.managedAccounts.update" class="permission-name add-link" data-text="issuerswitch.managedAccounts.update" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  managedAccounts.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.mandateTransactions.list" class="permission-name add-link" data-text="issuerswitch.mandateTransactions.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  mandateTransactions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.metadataTransactions.list" class="permission-name add-link" data-text="issuerswitch.metadataTransactions.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  metadataTransactions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.operations.cancel" class="permission-name add-link" data-text="issuerswitch.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.operations.delete" class="permission-name add-link" data-text="issuerswitch.operations.delete" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.operations.get" class="permission-name add-link" data-text="issuerswitch.operations.get" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.operations.list" class="permission-name add-link" data-text="issuerswitch.operations.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.transactionsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.operations.wait" class="permission-name add-link" data-text="issuerswitch.operations.wait" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.operations.wait</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.ruleMetadata.list" class="permission-name add-link" data-text="issuerswitch.ruleMetadata.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.ruleMetadata.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.ruleMetadataValues.create" class="permission-name add-link" data-text="issuerswitch.ruleMetadataValues.create" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.ruleMetadataValues.delete" class="permission-name add-link" data-text="issuerswitch.ruleMetadataValues.delete" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="issuerswitch.ruleMetadataValues.list" class="permission-name add-link" data-text="issuerswitch.ruleMetadataValues.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.  ruleMetadataValues.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="issuerswitch.rules.list" class="permission-name add-link" data-text="issuerswitch.rules.list" tabindex="-1"><code dir="ltr" translate="no">issuerswitch.rules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  issuerswitch.rulesViewer</code> )</p></td>
</tr>
</tbody>
</table>
