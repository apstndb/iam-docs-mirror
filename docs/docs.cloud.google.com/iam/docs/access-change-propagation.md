---
name: documents/docs.cloud.google.com/iam/docs/access-change-propagation
uri: https://docs.cloud.google.com/iam/docs/access-change-propagation
title: Access change propagation
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

In IAM, access changes, such as granting a role or denying a permission, are [eventually consistent](https://wikipedia.org/wiki/Eventual_consistency) . This means that it takes time for access changes to propagate through the system. In the meantime, recent access changes might not be effective everywhere. For example, principals might still be able to use a recently revoked role or a recently denied permission. Alternatively, they might not be able to use a recently granted role or a permission they were, until recently, denied from using.

The amount of time it takes for an access change to propagate depends on how you make the access change:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Method</th>
<th>Examples</th>
<th>Propagation time</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Change a policy</strong></p>
<p>Change a principal's access by editing an allow or deny policy.</p>
<p>When making policy changes, you can't exceed the <a href="https://docs.cloud.google.com/iam/quotas#limits">limits on the number of principals allowed in a policy</a> .</p></td>
<td><ul>
<li>You edit your organization's allow policy to grant a principal the Organization Administrator role ( <code dir="ltr" translate="no">roles/resourcemanager.organizationAdmin</code> ).</li>
<li>You edit an organization-level deny policy to deny a principal the <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  projects.setIamPolicy</code> permission.</li>
</ul></td>
<td>Typically 2 minutes, potentially 7 minutes or longer</td>
</tr>
<tr class="even">
<td><p><strong>Change a group's membership</strong></p>
<p>Change a principal's access by adding or removing them from a Google group that's included in an allow or deny policy.</p></td>
<td><ul>
<li>You have a group, <code dir="ltr" translate="no">org-admins@example.com</code> , that is granted the Organization Administrator role on your organization. You add a principal to the group to give them the Organization Administrator role.</li>
<li>You have a group, <code dir="ltr" translate="no">eng@example.com</code> , that is denied the <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  projects.setIamPolicy</code> permission at the organization level. You add a principal to the group to deny them the <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  projects.setIamPolicy</code> permission.</li>
</ul></td>
<td>Typically several minutes, potentially hours or longer</td>
</tr>
<tr class="odd">
<td><p><strong>Change a nested group's membership</strong></p>
<p>Change a principal's access by adding or removing them from a <a href="https://support.google.com/a/answer/167100" class="external">nested group</a> whose parent group is included in an allow or deny policy.</p></td>
<td><ul>
<li>You have a group, <code dir="ltr" translate="no">admins@example.com</code> , that is granted the Tag Viewer role ( <code dir="ltr" translate="no">roles/resourcemanager.tagViewer</code> ) on your organization. This group's membership is made up of a number of other groups, including <code dir="ltr" translate="no">org-admins@example.com</code> . You add a principal to the <code dir="ltr" translate="no">org-admins@example.com</code> group to give them the Tag Viewer role.</li>
<li>You have a group, <code dir="ltr" translate="no">eng@example.com</code> , that is denied the <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  projects.setIamPolicy</code> permission at the organization level. This group's membership is made up of a number of other groups, including <code dir="ltr" translate="no">eng-prod@example.com</code> . You add a principal to the <code dir="ltr" translate="no">eng-prod@example.com</code> group to deny them the <code dir="ltr" translate="no">cloudresourcemanager.googleapis.com/  projects.setIamPolicy</code> permission.</li>
</ul></td>
<td>Typically several minutes, potentially hours or longer</td>
</tr>
</tbody>
</table>

Also keep in mind the following details for how group membership changes propagate:

  - In general, adding a principal to a group propagates faster than removing a principal from a group.
  - In general, group membership changes propagate faster than nested group membership changes.

You can use these propagation time estimates to inform the way you modify your principals' access.
